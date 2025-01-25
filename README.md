
<!DOCTYPE html>
<html lang = "ru">
<head>
    
<!--
    Сайт сделал Souseiseki_.
    Он же dimius, он же @nuxtdev в Дискорде, он же mail@dimius.ru, он же github.com/intredford.
-->

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="icon" href="/favicon.svg" type="image/svg+xml">

<link rel="preload" href = "/css/fonts/golos-text/GolosText-Variable.woff2" crossorigin='anonymous' as='font' type='font/woff2'>
<link rel="preload" href = "/css/fonts/golos-ui/GolosUI-Variable.woff2" crossorigin='anonymous' as='font' type='font/woff2'>

<link rel="stylesheet" href="/css/fonts/golos-text.css">
<link rel="stylesheet" href="/css/fonts/golos-ui.css">
<link rel="stylesheet" href="/css/main.css">
<link rel="stylesheet" href="/css/header.css">
<link rel="stylesheet" href="/css/footer.css">
	<title>CMCraft — Ванильный сервер в Майнкрафт 1.21</title>
	<meta name = "description" content = "Майнкрафт-сервер с выживанием без доната, без грифа, без приватов и прочей чуши. У нас бесплатная проходка, высокий онлайн и большое сообщество.">

	<link rel="preload" as="image" href="/img/pie.svg">
    <link rel = "stylesheet" href = "/css/pages/index.css">
</head>
<body>

    <script type="module" src = "/js/lib/svg-sparkline.min.js" async></script>

<nav>
    <menu class = "container">
		

		
	  
		
			<a 
				href="/" 
				class="
					menu-link 
					active"
			>
				Главная
			</a>
		
			<a 
				href="/read/faq" 
				class="
					menu-link 
					"
			>
				FAQ
			</a>
		
			<a 
				href="/rules" 
				class="
					menu-link 
					"
			>
				Правила
			</a>
			
		
		<div class = "secondary-links">
			
				<a 
					href="/history" 
					class=""
				>
					История
				</a>
			
				<a 
					href="/read/contacts" 
					class=""
				>
					Контакты
				</a>
			
				<a 
					href="/read/gallery" 
					class=""
				>
					Галерея
				</a>
			
				<a 
					href="/read/other" 
					class=""
				>
					Прочее
				</a>
			
		</div>

		
        <div class = "connect">
			Подключиться — <strong class = "ip">cmcraft.su</strong>
        </div>

	</menu>

	
	<div class = "container online">
		 
		<div class = "online-plot" style = "height: 64px">
			<!-- width="1152" -->
			<svg-sparkline
				values="19,28,31,36,34,14,5,12,21,32,27,24,20,10,4,10,12,21,24,28,22,11,3,7,11,18,29,33,29,16,6,12,21,21,13" 
				curve="true" 
				color="#00ca6f"
				line-width="3"
				endpoint="false"
				width = "1330"
				height="55"
				gradient="true" 
				gradient-color="color-mix(in srgb, #00ca6f, transparent 85%)"
			>
			</svg-sparkline>
			<!-- <span id = "online-plot-min"></span>
			<span id = "online-plot-max"></span> -->
		</div>
		
		<div class = "online-value">
			<div 
				class = "status status-up"
				title = "Сервер работает"
			></div>
			13/200 онлайн
			
			<small 
				class = "online-record"
				title = "Установлен 26 июня 2024 "
			>
				Рекорд — 168
			</small>
		</div>

	</div>
	

</nav>

<script>
	const plot = {
		el: document.querySelector('svg-sparkline'),
		container: document.querySelector('.online-plot'),
	}
	plot.values = plot.el.getAttribute("values").replace(' ', '').split(',').map(Number);

	// Расчёт отностиельных координат всех значений
	plot.coordinates = plot.values.map((value, index) => {
		return {
			value,
			x: index / (plot.values.length - 1),
			y: value / Math.max(...plot.values)
		}
	});

	function findNearestValueIndex(x) {
		let nearestIndex = 0
		let nearestDistance = Infinity

		plot.coordinates.forEach((coord, index) => {
			const distance = Math.abs(coord.x + (1/plot.values.length/4) - x);
			if (distance < nearestDistance) {
				nearestDistance = distance
				nearestIndex = index
			}
    	})

		return nearestIndex
	}

	// Стили указателя значения
	const valueStyles = {
		position: 'absolute',
		fontSize: '55%',
		textAlign: 'center',
		fontWeight: '600',
		fontFamily: 'var(--font-accent)',
		direction: 'ltr',
		whiteSpace: 'nowrap',
		padding: '0 0.25rem',
		backdropFilter: 'blur(4px)',
		color: 'color-mix(in srgb, currentColor, transparent 10%)',
		borderRadius: '0.3rem',
		boxShadow: 'var(--shadow--lighter)',
		transform: 'translate(-50%, 0)',
	};
	
	// Показать значение ближайшей к курсору точки
	function showValueAtCoordinates(index) {
		if (index === plot.coordinates.length-1 || index === 0) return;

		const valueEl = document.createElement('div')
		const valueCoordinates = plot.coordinates[index]
		
		for (const style in valueStyles) {
			valueEl.style[style] = valueStyles[style]
		}
		valueEl.style.backgroundColor = valueCoordinates.value !== 0 ? '#00ca6f66' : '#ff2222aa',

		valueEl.style.left = `calc(${valueCoordinates.x * 100}%)`
		
		if (valueCoordinates.y > 0.5) {
			valueEl.style.bottom = `calc(${valueCoordinates.y * 100}% - 1.4rem - 0.25rem - 4px)`
			valueEl.style.clipPath = 'polygon(50% 0%, 66% 25%, 100% 30%, 100% 70%, 100% 100%, 50% 100%, 0 100%, 0% 70%, 0 30%, 33% 25%)'
			valueEl.style.paddingTop = '0.33rem'
		} else {
			valueEl.style.bottom = `calc(${valueCoordinates.y * 100}% + 2px)`
			valueEl.style.clipPath = 'polygon(0 0, 100% 0, 100% 70%, 66% 75%, 50% 100%, 33% 75%, 0 70%)'
			valueEl.style.paddingBottom = '0.33rem'
		}
		valueEl.innerHTML = String(plot.values[index])

		return valueEl
	}

	plot.el.addEventListener('mousemove', (event) => {
		const rect = plot.el.getBoundingClientRect()
		const x = (event.clientX - rect.left) / rect.width
		const nearestIndex = findNearestValueIndex(x)
		const shadow = plot.el.shadowRoot
		const wrapper = shadow.getElementById('wrapper')

		if (wrapper.querySelector('.value-display')) {
			wrapper.querySelector('.value-display').remove()
		}

		const valueEl = showValueAtCoordinates(nearestIndex)
		valueEl.classList.add('value-display')
		wrapper.appendChild(valueEl)
	});

	setTimeout(() => {
		const shadow = plot.el.shadowRoot
		shadow.innerHTML = `<div id="wrapper">${plot.el.shadowRoot.innerHTML}</div>`
		shadow.querySelector('title').innerHTML = 'График онлайна'
		const wrapper = shadow.getElementById('wrapper')
		wrapper.style.height = shadow.querySelector('svg').getAttribute('height')
		wrapper.style.position = "relative"
	}, 228);
</script>
  

<script>
// Прокрутка графика онлайна жестом
plot.container.style.cursor = 'grab';

let pos = { top: 0, left: 0, x: 0, y: 0 };

const mouseDownHandler = function (e) {
    plot.container.style.cursor = 'grabbing';
    plot.container.style.userSelect = 'none';

    pos = {
        left: plot.container.scrollLeft,
        top: plot.container.scrollTop,
        x: e.clientX,
        y: e.clientY,
    };

    document.addEventListener('mousemove', mouseMoveHandler);
    document.addEventListener('mouseup', mouseUpHandler);
};

const mouseMoveHandler = function (e) {
    const dx = e.clientX - pos.x;
    const dy = e.clientY - pos.y;
    plot.container.scrollTop = pos.top - dy;
    plot.container.scrollLeft = pos.left - dx;

	const wrapper = plot.el.shadowRoot.getElementById('wrapper')
	if (wrapper.querySelector('.value-display')) {
		wrapper.querySelector('.value-display').remove()
	}
};

const mouseUpHandler = function () {
    plot.container.style.cursor = 'grab';
    plot.container.style.removeProperty('user-select');
    document.removeEventListener('mousemove', mouseMoveHandler);
    document.removeEventListener('mouseup', mouseUpHandler);
};

plot.container.addEventListener('mousedown', mouseDownHandler);
</script>

<script>
	// Прокрутка к выбранной странице в меню, актуально на мобиле
	const menu = document.querySelector('menu')
	const active = document.querySelector('menu a.active')
	menu.scrollLeft = active.offsetLeft + active.clientWidth/2 - menu.offsetWidth/2
</script>

    <main>

		<section class = "container banner">

			<div class = "banner-hero">
				<h1 class = "banner-title">
                    CMCraft
				</h1>
				<p class = "banner-subtitle">
					Ванильный сервер
				</p>
				<nobr class = "banner-caption">
					 Без доната · Без приватов · Без грифа
				</nobr>
			</div>

			<div class = "banner-season">
				

				<!-- Текущий сезон -->
				
					
						С
					
					26 июня 
					идёт <b>8</b> сезон

				<!-- Межсезонье -->
				

			</div>

		</section>

		<section class = "container info">

			<div class="info-block main">
				<h2>О сервере</h2>
				<p>
					Мы стараемся обеспечить опыт игры, максимально приближённый к ванильному выживанию.
                    У нас нет приватов и кучи других шлаковых плагинов. Только те дополнения, которые необходимы
                    для комфортной игры и стабильной работы сервера.
				</p>
                <p>
                    На сервере отсутствуют любые формы доната, даже косметического, что делает всех игроков
                    абсолютно равными, в том числе перед <a href = "/rules">правилами</a>. Если вы подвергнетесь
                    нападению или вашу базу разрушат, вы можете обратиться к админам, они откатят её в
                    первоначальное состояние.
                </p>
				<p>
					Сервер работает на выделенной машине и поддерживается грамотной технической администрацией,
                    что позволяет обеспечить высокую производительность, хороший аптайм и низкий пинг.
				</p>
			</div>

			<div class="info-block secondary">
				<h2>Как начать играть?</h2>
				<p>
					Это бесплатно, нужно всего лишь заполнить <a href>небольшую анкету</a>
                    в нашей группе ВК. Её рассмотрение займет около одного-двух дней, после чего,
                    в случае одобрения, вы будете занесены в белый список и сможете зайти на сервер.
                    Для посторонних сервер закрыт — это нужно для того, чтобы отсеять гриферов и ботов.
				</p>
				<p>
					Регистрация на нашем сервере всегда была и будет бесплатной, а аккаунты
					никогда не удаляются.
				</p>
				<p>
					Также советуем вступить в наш <a href = "https://discord.com/invite/MPfPsXabjK">дискорд,</a>
					где мы общаемся, выкладываем новости и оповещаем об ивентах.
				</p>
			</div>

			<div class="info-block tertiary-1">
				<div style = "font-size: 6em; line-height: 1;">
					217
				</div>
				<p>анкет за декабрь</p>
			</div>

			<div class="info-block tertiary-2">
				<div style = "font-size: 6em; line-height: 1;">
					213
				</div>
				<p>дней с начала сезона</p>
			</div>

		</section>

	</main>

	<footer>
	<hr class = "footer-line">

	<div class = "container footer">

		<div class = "footer-cmc">
			<img 
				src = "/img/heart.svg" 
				class = "footer-heart" 
				height = "16"
			>
			<img 
				src = "/img/pie.svg" 
				height = "32"
			>
			<img 
				src = "/img/heart.svg" 
				class = "footer-heart" 
				height = "16"
			>
			
			<div class = "server-info">
				TPS — 20.00<br>
				Аптайм — 100 %
			</div>
			
		</div>

	</div>
</footer>

<script>
// Ссылки по Бирману
const QUOTATION_MARKS = '"\'«»‘’‚‛“”„‟‹›\(\)' // Перечень возможных кавычек
const PUNCTUATION_MARKS = '.!?:;,' // Перечень возможных знаков препинания, стоящих после последней кавычки

const surroundedByQuotationMarks = new RegExp(`^([${QUOTATION_MARKS}]{1})(.*)([${QUOTATION_MARKS}]{1}[${PUNCTUATION_MARKS}]?)$`) // Магическое регулярное выражение, чтобы найти и заменить ссылки, начинающиеся (^) с кавычки и заканчивающиеся ($) кавычкой с необязательным знаком препинания

Array.from(document.querySelectorAll('a')) // Находим все ссылки
	.filter(a => surroundedByQuotationMarks.test(a.textContent)) // Отбираем нужные нам
	.forEach(a => a.innerHTML = a.innerHTML.replace(surroundedByQuotationMarks, '$1<u>$2</u>$3')) // Заворачиваем содержимое в <u>

</script>
    
</body>
</html>

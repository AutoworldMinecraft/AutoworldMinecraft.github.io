
<script src="https://cdn.tailwindcss.com"></script>
<script src="../node_modules/flyonui/flyonui.js"></script>
<link href="../haku.css" rel="stylesheet">
<link href="../public/styles.css" rel="stylesheet">
<link rel="icon" type="image/png" href="../scr/fav.png">
<link href="https://fonts.googleapis.com/css2?family=Unbounded&display=swap" rel="stylesheet">
<style>
    body {
        font-family: 'Unbounded', sans-serif;
    }
</style>
<link rel="icon" type="image/png" href="../fav.png">
<html lang="ru" data-theme="haku">

<head>
    <meta charset="UTF-8">
    <meta name="description"
        content="Приватный ванильный сервер Minecraft. Присоединяйтесь к нашему активному сообществу и наслаждайтесь игрой на высокопроизводительном сервере с стабильным TPS.">
    <meta name="keywords"
        content="Minecraft сервер, приватный сервер, ванильный сервер, Minecraft, сервер, игровой сервер, онлайн игра, Minecraft сообщество">
    <meta name="author" content="HAKU">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ванильный сервер Minecraft - ХАКУ</title>
</head>

<body>
    <style>
  .navbar {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 1000;
    transition: background-color 0.3s ease;
    background-color: transparent;
  }

  .navbar.scrolled {
    background-color: #0D0D0D; /* Цвет фона при прокрутке */
  }

  .navbar .menu a,
  .navbar .dropdown-item {
    color: white; /* Цвет текста кнопок */
  }
</style>
<script>
  document.addEventListener('DOMContentLoaded', function() {
    const navbar = document.querySelector('.navbar');
    let lastScrollTop = 0;

    window.addEventListener('scroll', function() {
      const scrollTop = window.pageYOffset || document.documentElement.scrollTop;

      if (scrollTop > lastScrollTop) {
        // Прокрутка вниз
        navbar.classList.add('scrolled');
      } else {
        // Прокрутка вверх
        if (scrollTop === 0) {
          navbar.classList.remove('scrolled');
        }
      }

      lastScrollTop = scrollTop <= 0 ? 0 : scrollTop; // Для IE
    });
  });
</script>



<nav class="navbar rounded-box flex w-full items-center justify-between gap-2">
  <div class="navbar-start max-md:w-1/4">
    <a class="link text-base-content/90 link-neutral text-xl font-semibold no-underline" href="https://haku.su">
    <svg width="110" height="29" viewBox="0 0 110 29" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M11.4947 0C14.6756 3.22058 17.8503 6.45078 21.0188 9.6906C19.6498 11.095 18.2735 12.4908 16.8901 13.8779C13.7154 10.6716 10.5563 7.44941 7.41289 4.21122C8.77447 2.80649 10.1351 1.40272 11.4947 0Z" fill="white"/>
<path fill-rule="evenodd" clip-rule="evenodd" d="M24.2092 7.56105C24.2586 7.55392 24.3055 7.56186 24.35 7.58498C25.7106 8.97277 27.0712 10.3606 28.4317 11.7483C25.2349 14.9613 22.0523 18.1915 18.8841 21.4389C17.5072 20.0425 16.1388 18.6388 14.7789 17.2277C17.9233 14.0045 21.0667 10.7823 24.2092 7.56105Z" fill="white"/>
<path fill-rule="evenodd" clip-rule="evenodd" d="M9.47725 7.56106C10.8652 8.90487 12.2336 10.2767 13.5825 11.6766C13.6138 11.7244 13.6138 11.7723 13.5825 11.8201C10.4384 15.035 7.28716 18.2413 4.1287 21.4389C2.74531 20.0518 1.36904 18.6561 0 17.2517C3.16854 14.0278 6.32761 10.7976 9.47725 7.56106Z" fill="white"/>
<path fill-rule="evenodd" clip-rule="evenodd" d="M11.4947 15.0743C14.6756 18.2948 17.8503 21.525 21.0188 24.7649C19.6335 26.162 18.265 27.5737 16.9136 29C13.7383 25.7691 10.5714 22.531 7.41289 19.2855C8.77447 17.8807 10.1351 16.477 11.4947 15.0743Z" fill="white"/>
<path d="M49.5379 15.4533V12.5131L57.9568 23.0837H52.123L46.5638 15.7566H48.8973L43.3153 23.0837H37.5502L46.0148 12.5364V15.4299L38.0535 5.58273H43.9787L49.0117 12.2098H46.6782L51.6426 5.58273H57.4763L49.5379 15.4533Z" fill="white"/>
<path d="M69.4531 23.0837L68.8583 18.2767L69.476 16.4333L68.8583 14.5899L69.4531 9.75962H74.3031L73.4796 16.41L74.3031 23.0837H69.4531ZM70.5513 16.4333C70.3377 17.8334 69.9107 19.0623 69.2701 20.1202C68.6448 21.178 67.8441 22.0025 66.868 22.5936C65.9072 23.1692 64.8091 23.457 63.5737 23.457C62.2925 23.457 61.1639 23.1692 60.1878 22.5936C59.227 22.0025 58.472 21.178 57.923 20.1202C57.3739 19.0468 57.0994 17.8178 57.0994 16.4333C57.0994 15.0177 57.3739 13.7809 57.923 12.7231C58.472 11.6653 59.227 10.8408 60.1878 10.2497C61.1639 9.65851 62.2925 9.36294 63.5737 9.36294C64.8091 9.36294 65.9072 9.65851 66.868 10.2497C67.8441 10.8252 68.6524 11.6419 69.293 12.6998C69.9336 13.7421 70.353 14.9866 70.5513 16.4333ZM61.835 16.4333C61.835 17.0867 61.9646 17.67 62.2239 18.1834C62.4984 18.6968 62.8721 19.1012 63.3449 19.3968C63.8177 19.6768 64.3591 19.8168 64.9692 19.8168C65.6098 19.8168 66.2122 19.6768 66.7765 19.3968C67.3408 19.1012 67.8365 18.6968 68.2635 18.1834C68.6906 17.67 69.0109 17.0867 69.2244 16.4333C69.0109 15.7644 68.6906 15.1732 68.2635 14.6599C67.8365 14.1465 67.3408 13.7421 66.7765 13.4465C66.2122 13.1509 65.6098 13.0031 64.9692 13.0031C64.3591 13.0031 63.8177 13.1509 63.3449 13.4465C62.8721 13.7421 62.4984 14.1465 62.2239 14.6599C61.9646 15.1732 61.835 15.7644 61.835 16.4333Z" fill="white"/>
<path d="M76.5491 23.0837V9.75962H81.2389V19.3735L79.8663 18.8834L87.1413 9.75962H92.0828L80.7127 23.0837H76.5491ZM87.187 23.0837L83.458 16.5733L86.9811 14.0532L92.4488 23.0837H87.187Z" fill="white"/>
<path d="M97.8293 27.3072C96.8684 27.3072 96.0143 27.1828 95.267 26.9339C94.5197 26.7005 93.7952 26.3349 93.0937 25.8371V22.5236C93.8105 22.9903 94.4815 23.3248 95.1069 23.527C95.7322 23.7293 96.4185 23.8304 97.1658 23.8304C97.7911 23.8304 98.3478 23.6904 98.8359 23.4103C99.3239 23.1303 99.7204 22.617 100.025 21.8703L105.036 9.75962H110L103.732 23.3403C103.289 24.3204 102.748 25.0982 102.107 25.6738C101.482 26.2649 100.803 26.685 100.071 26.9339C99.3392 27.1828 98.5918 27.3072 97.8293 27.3072ZM97.9894 21.8469L92.4302 9.75962H97.5776L102.496 21.8469H97.9894Z" fill="white"/>
</svg>


    </a>
  </div>
  <div class="navbar-center max-md:hidden">
    <ul class="menu menu-horizontal p-0 font-medium">
      <li><a href="https://wiki.haku.su/">Вики</a></li>
      <li><a href="/plus">Плюсик+</a></li>
      <li><a href="https://discord.gg/S6B7zzbz2F">Дискорд</a></li>
    </ul>
  </div>
  <div class="navbar-end items-center gap-4">
    <div class="dropdown relative inline-flex md:hidden rtl:[--placement:bottom-end]">
      <button id="dropdown-default" type="button" class="dropdown-toggle btn btn-text btn-primary btn-square" aria-haspopup="menu" aria-expanded="false" aria-label="Dropdown">
        <span class="icon-[tabler--menu-2] dropdown-open:hidden size-5"></span>
        <span class="icon-[tabler--x] dropdown-open:block hidden size-5"></span>
      </button>
      <ul class="dropdown-menu dropdown-open:opacity-100 hidden min-w-60" role="menu" aria-orientation="vertical" aria-labelledby="dropdown-default">
        <li><a class="dropdown-item" href="https://wiki.haku.su/">Вики</a></li>
        <li><a class="dropdown-item" href="/plus">Архив</a></li>
        <li><a class="dropdown-item" href="https://discord.gg/S6B7zzbz2F">Дискорд</a></li>
      </ul>
    </div>
    <a class="btn max-md:btn-square btn-primary bg-black" href="https://haku.su/panel">
      <span class="max-md:hidden">Войти</span>
      <span class="icon-[tabler--arrow-right]"></span>
    </a>
  </div>
</nav>


    <div class="relative h-screen w-full motion-preset-focus  ">
        <video class="absolute top-0 left-0 w-full h-full object-cover" autoplay loop muted playsinline>
            <source src="inx.mp4" type="video/mp4">
        </video>

        <div class="absolute top-0 left-0 w-full h-full bg-black/50"></div>

        <div class="relative z-10 h-full flex flex-col items-center justify-center text-white">
            <h1 class="text-4xl md:text-4xl font-bold mb-8 text-center motion-preset-shrink">
                Приватный ванильный сервер по Minecraft
            </h1>

            <a href="https://haku.su/panel"><button class="btn btn-primary rounded-lg btn-lg">
                <p>Начать играть</p>
                <span class="text-sm bg-black py-1 rounded-lg px-2">150₽</span>
            </button>
            </a>
            <p class="mt-2 text-sm bg-red-500 py-2 px-4 rounded-lg invisible">Действует скидка до {date}</p>
        </div>
    </div>

    <div class="bg-[#0D0D0D] py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-[#141414] h-[500px] p-6 rounded-lg shadow-md text-center relative overflow-hidden">
                    <img src="/public/1.png" alt="Image 1"
                        class="absolute inset-0 w-full h-full object-cover opacity-100" />
                    <div class="blurred-circle"></div>
                    <div class="relative z-20">
                        <h2 class="text-2xl font-bold mb-4 text-[#06FE9F]">Высокий TPS</h2>
                        <p class="text-neutral-content">Наш сервер обеспечивает высокую производительность и стабильный
                            TPS для лучшего игрового опыта.</p>
                    </div>
                </div>
                <div class="bg-[#141414] h-[500px] p-6 rounded-lg shadow-md text-center relative overflow-hidden">
                    <img src="/public/2.png" alt="Image 2"
                        class="absolute inset-0 w-full h-full object-cover opacity-100" />
                    <div class="blurred-circle"></div>
                    <div class="relative z-20">
                        <h2 class="text-2xl font-bold mb-4 text-secondary">Активное сообщество</h2>
                        <p class="text-neutral-content">Присоединяйтесь к нашему активному сообществу игроков и
                            наслаждайтесь игрой вместе.</p>
                    </div>
                </div>
                <div class="bg-[#141414] h-[500px] p-6 rounded-lg shadow-md text-center relative overflow-hidden">
                    <img src="/public/3.png" alt="Image 3"
                        class="absolute inset-0 w-full h-full object-cover opacity-100" />
                    <div class="blurred-circle"></div>
                    <div class="relative z-20">
                        <h2 class="text-2xl font-bold mb-4 text-accent">Место для ваших идей</h2>
                        <p class="text-neutral-content">Мы всегда открыты для новых идей и предложений от наших игроков.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <style>
        .blurred-circle {
            position: absolute;
            top: 50%;
            left: 50%;
            width: 300px;
            height: 300px;
            background: rgba(25, 47, 247, 0.36);
            border-radius: 50%;
            filter: blur(100px);
            transform: translate(-50%, -50%);
            animation: moveCircle 20s linear infinite;
            z-index: 10;
        }

        @keyframes moveCircle {
            0% {
                transform: translate(-50%, -50%) translateX(-100px) translateY(-100px);
            }

            25% {
                transform: translate(-50%, -50%) translateX(100px) translateY(-100px);
            }

            50% {
                transform: translate(-50%, -50%) translateX(100px) translateY(100px);
            }

            75% {
                transform: translate(-50%, -50%) translateX(-100px) translateY(100px);
            }

            100% {
                transform: translate(-50%, -50%) translateX(-100px) translateY(-100px);
            }
        }
    </style>


    <div class="bg-[#0D0D0D]">
        <div class="container mx-auto px-4">
            <h1 class="text-4xl font-bold mb-8 text-center">Немного о сервере</h1>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div
                    class="bg-[#141414] h-[200px] p-6 rounded-lg shadow-md text-center flex flex-col justify-center items-center">
                    <h2 class="text-2xl font-bold mb-2 text-yellow-400">633</h2>
                    <p class="text-neutral-content">Зарегистрировано игроков</p>
                </div>
                <div
                    class="bg-[#141414] h-[200px] p-6 rounded-lg shadow-md text-center flex flex-col justify-center items-center">
                    <h2 class="text-2xl font-bold mb-2 text-blue-300">4 года</h2>
                    <p class="text-neutral-content">Возраст проекта</p>
                </div>
                <div
                    class="bg-[#141414] h-[200px] p-6 rounded-lg shadow-md text-center flex flex-col justify-center items-center">
                    <h2 class="text-2xl font-bold mb-2 text-accent">30.12.2024</h2>
                    <p class="text-neutral-content">Последний вайп</p>
                </div>
                <div
                    class="bg-[#141414] h-[200px] p-6 rounded-lg shadow-md text-center flex flex-col justify-center items-center">
                    <div class="flex items-center mb-2">
                        <div class="w-4 h-4 bg-green-500 rounded-full mr-2 animate-pulse"></div>
                        <h2 class="text-2xl font-bold text-green-500">Онлайн</h2>
                    </div>
                    <p class="text-neutral-content">Статус сервера</p>
                </div>
            </div>
        </div>
    </div>
    <!-- 
    <div class="bg-[#0D0D0D] mt-4">
        <div class="container mx-auto px-4">
            <div id="image" data-carousel='{ "loadingClasses": "opacity-0" }' class="relative h-[500px]">
                <div class="carousel">
                    <div class="carousel-body h-full opacity-0">
                        <div class="carousel-slide">
                            <div class="flex h-full justify-center">
                                <img src="./public/screens/3.png" class="size-full object-cover" alt="game" />
                            </div>
                        </div>
                        <div class="carousel-slide">
                            <div class="flex h-full justify-center">
                                <img src="./public/screens/2.png" class="size-full object-cover" alt="game" />
                            </div>
                        </div>
                        <div class="carousel-slide">
                            <div class="flex h-full justify-center">
                                <img src="./public/screens/4.png" class="size-full object-cover" alt="game" />
                            </div>
                        </div>

                    </div>
                </div>
                <button type="button" class="carousel-prev">
                    <span class="size-9.5 bg-base-100 flex items-center justify-center rounded-full shadow">
                        <span class="icon-[tabler--chevron-left] size-5 cursor-pointer rtl:rotate-180"></span>
                    </span>
                    <span class="sr-only">Назад</span>
                </button>
                <button type="button" class="carousel-next">
                    <span class="sr-only">След</span>
                    <span class="size-9.5 bg-base-100 flex items-center justify-center rounded-full shadow">
                        <span class="icon-[tabler--chevron-right] size-5 cursor-pointer rtl:rotate-180"></span>
                    </span>
                </button>
            </div>
        </div>
    </div>
    -->



                <div class="relative h-60 w-full">

  <div class="relative h-60 w-full">
  <footer class="footer bg-black absolute -bottom-px start-0 w-full px-6 py-4">
    <div class="flex flex-col md:flex-row items-center justify-between">
      <aside class="text-center md:text-left mb-4 md:mb-0">
        <p>©2024 <a class="link link-hover font-medium" href="https://haku.su">HAKU.SU</a></p>
      </aside>
      <nav class="flex flex-col md:flex-row items-start gap-4">
        <a class="link link-hover" href="https://haku.su/panel/docs/politica.html">Политика конфиденциальности</a>
        <a class="link link-hover" href="https://haku.su/panel/docs/oferta.html">Договор-Оферта</a>
        <a class="link link-hover" href="https://t.me/Quinowell">Связь с администрацией</a>
        <a class="text-blue-400 bg-black hover:bg-blue-400 hover:text-white rounded-lg px-3 py-1" href="https://t.me/CESAR1337">Сайт скрафтил EASENS</a>
      </nav>
    </div>
  </footer>
</div>
</div>
                
                
</body>

</html>

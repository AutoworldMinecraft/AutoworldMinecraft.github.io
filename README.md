
<!DOCTYPE html>

<style>
    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Regular.eot');
        src: local('Gilroy Regular'), local('Gilroy-Regular'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Regular.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Regular.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Regular.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Regular.ttf') format('truetype');
        font-weight: normal;
        font-style: normal;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-ExtraboldItalic.eot');
        src: local('Gilroy Extrabold Italic'), local('Gilroy-ExtraboldItalic'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-ExtraboldItalic.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-ExtraboldItalic.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-ExtraboldItalic.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-ExtraboldItalic.ttf') format('truetype');
        font-weight: 800;
        font-style: italic;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Bold.eot');
        src: local('Gilroy Bold'), local('Gilroy-Bold'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Bold.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Bold.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Bold.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Bold.ttf') format('truetype');
        font-weight: bold;
        font-style: normal;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Black.eot');
        src: local('Gilroy Black'), local('Gilroy-Black'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Black.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Black.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Black.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Black.ttf') format('truetype');
        font-weight: 900;
        font-style: normal;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Light.eot');
        src: local('Gilroy Light'), local('Gilroy-Light'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Light.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Light.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Light.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Light.ttf') format('truetype');
        font-weight: 300;
        font-style: normal;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Semibold.eot');
        src: local('Gilroy Semibold'), local('Gilroy-Semibold'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Semibold.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Semibold.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Semibold.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Semibold.ttf') format('truetype');
        font-weight: 600;
        font-style: normal;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Medium.eot');
        src: local('Gilroy Medium'), local('Gilroy-Medium'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Medium.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Medium.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Medium.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Medium.ttf') format('truetype');
        font-weight: 500;
        font-style: normal;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-MediumItalic.eot');
        src: local('Gilroy Medium Italic'), local('Gilroy-MediumItalic'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-MediumItalic.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-MediumItalic.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-MediumItalic.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-MediumItalic.ttf') format('truetype');
        font-weight: 500;
        font-style: italic;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-BlackItalic.eot');
        src: local('Gilroy Black Italic'), local('Gilroy-BlackItalic'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-BlackItalic.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-BlackItalic.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-BlackItalic.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-BlackItalic.ttf') format('truetype');
        font-weight: 900;
        font-style: italic;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-UltraLight.eot');
        src: local('Gilroy UltraLight'), local('Gilroy-UltraLight'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-UltraLight.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-UltraLight.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-UltraLight.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-UltraLight.ttf') format('truetype');
        font-weight: 200;
        font-style: normal;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-RegularItalic.eot');
        src: local('Gilroy Regular Italic'), local('Gilroy-RegularItalic'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-RegularItalic.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-RegularItalic.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-RegularItalic.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-RegularItalic.ttf') format('truetype');
        font-weight: normal;
        font-style: italic;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-SemiboldItalic.eot');
        src: local('Gilroy Semibold Italic'), local('Gilroy-SemiboldItalic'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-SemiboldItalic.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-SemiboldItalic.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-SemiboldItalic.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-SemiboldItalic.ttf') format('truetype');
        font-weight: 600;
        font-style: italic;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-HeavyItalic.eot');
        src: local('Gilroy Heavy Italic'), local('Gilroy-HeavyItalic'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-HeavyItalic.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-HeavyItalic.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-HeavyItalic.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-HeavyItalic.ttf') format('truetype');
        font-weight: 900;
        font-style: italic;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Extrabold.eot');
        src: local('Gilroy Extrabold'), local('Gilroy-Extrabold'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Extrabold.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Extrabold.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Extrabold.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Extrabold.ttf') format('truetype');
        font-weight: 800;
        font-style: normal;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-BoldItalic.eot');
        src: local('Gilroy Bold Italic'), local('Gilroy-BoldItalic'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-BoldItalic.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-BoldItalic.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-BoldItalic.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-BoldItalic.ttf') format('truetype');
        font-weight: bold;
        font-style: italic;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-UltraLightItalic.eot');
        src: local('Gilroy UltraLight Italic'), local('Gilroy-UltraLightItalic'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-UltraLightItalic.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-UltraLightItalic.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-UltraLightItalic.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-UltraLightItalic.ttf') format('truetype');
        font-weight: 200;
        font-style: italic;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-LightItalic.eot');
        src: local('Gilroy Light Italic'), local('Gilroy-LightItalic'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-LightItalic.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-LightItalic.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-LightItalic.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-LightItalic.ttf') format('truetype');
        font-weight: 300;
        font-style: italic;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Heavy.eot');
        src: local('Gilroy Heavy'), local('Gilroy-Heavy'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Heavy.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Heavy.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Heavy.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Heavy.ttf') format('truetype');
        font-weight: 900;
        font-style: normal;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Thin.eot');
        src: local('Gilroy Thin'), local('Gilroy-Thin'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Thin.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Thin.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Thin.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-Thin.ttf') format('truetype');
        font-weight: 100;
        font-style: normal;
    }

    @font-face {
        font-family: 'Gilroy';
        src: url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-ThinItalic.eot');
        src: local('Gilroy Thin Italic'), local('Gilroy-ThinItalic'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-ThinItalic.eot?#iefix') format('embedded-opentype'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-ThinItalic.woff2') format('woff2'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-ThinItalic.woff') format('woff'),
        url('https://marallys.com/wp-content/themes/marallys/assets/fonts/Gilroy-ThinItalic.ttf') format('truetype');
        font-weight: 100;
        font-style: italic;
    }

</style>

<html class="no-js" lang="ru-RU">

<head>
    <!-- CSS only -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
    <!-- JavaScript Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-OERcA2EqjJCMA+/3y+gxIOqMEjwtxJY7qPCqsdltbNJuaOe923+mo//f6V8Qbsw3" crossorigin="anonymous" type="4ef472c115034e5c06af6b1a-text/javascript"></script>

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fancyapps/ui@4.0/dist/fancybox.css"/>
    <!-- Yandex.RTB -->
    <script src="https://kit.fontawesome.com/31083150ab.js" crossorigin="anonymous" type="4ef472c115034e5c06af6b1a-text/javascript"></script>

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fancyapps/ui@4.0/dist/fancybox.css">

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/lightgallery@2.5.0/css/lightgallery-bundle.min.css" />
    <script src="https://cdn.jsdelivr.net/npm/lightgallery@2.5.0/lightgallery.umd.js" type="4ef472c115034e5c06af6b1a-text/javascript"></script>
    <script src="https://cdn.jsdelivr.net/npm/lg-thumbnail@2.5.0/lg-thumbnail.umd.js" type="4ef472c115034e5c06af6b1a-text/javascript"></script>
    <script src="https://cdn.jsdelivr.net/npm/lg-zoom@2.5.0/lg-zoom.umd.js" type="4ef472c115034e5c06af6b1a-text/javascript"></script>


    <script src="https://kit.fontawesome.com/31083150ab.js" crossorigin="anonymous" type="4ef472c115034e5c06af6b1a-text/javascript"></script>


    <script type="4ef472c115034e5c06af6b1a-text/javascript">window.yaContextCb=window.yaContextCb||[]</script>
    <script src="https://yandex.ru/ads/system/context.js" async type="4ef472c115034e5c06af6b1a-text/javascript"></script>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0" >

    <link rel="profile" href="https://gmpg.org/xfn/11">

    <!-- Yandex.RTB -->
    <script type="4ef472c115034e5c06af6b1a-text/javascript">window.yaContextCb=window.yaContextCb||[]</script>
    <script src="https://yandex.ru/ads/system/context.js" async type="4ef472c115034e5c06af6b1a-text/javascript"></script>

    <meta name='robots' content='index, follow, max-image-preview:large, max-snippet:-1, max-video-preview:-1' />
	<style>img:is([sizes="auto" i], [sizes^="auto," i]) { contain-intrinsic-size: 3000px 1500px }</style>
	
	<!-- This site is optimized with the Yoast SEO plugin v24.0 - https://yoast.com/wordpress/plugins/seo/ -->
	<title>Бесплатный приватный сервер Minecraft с Create - Marallys</title>
	<meta name="description" content="Marallys - это полностью бесплатный приватный сервер приближенный к ванильному Майнкрафту (minecraft) с кучей фишек, которые не дадут заскучать любому игроку. Невероятная атмосфера, никаких приватов и грифов, полная свобода творчеству и воображению." />
	<link rel="canonical" href="https://marallys.com/" />
	<meta property="og:locale" content="ru_RU" />
	<meta property="og:type" content="website" />
	<meta property="og:title" content="Бесплатный приватный сервер Minecraft с Create - Marallys" />
	<meta property="og:description" content="Marallys - это полностью бесплатный приватный сервер приближенный к ванильному Майнкрафту (minecraft) с кучей фишек, которые не дадут заскучать любому игроку. Невероятная атмосфера, никаких приватов и грифов, полная свобода творчеству и воображению." />
	<meta property="og:url" content="https://marallys.com/" />
	<meta property="og:site_name" content="Marallys" />
	<meta property="article:modified_time" content="2025-01-21T07:23:12+00:00" />
	<meta property="og:image" content="https://marallys.com/wp-content/uploads/2023/08/2023-08-09_00.28.02-1024x576.png" />
	<meta property="og:image:width" content="1024" />
	<meta property="og:image:height" content="576" />
	<meta property="og:image:type" content="image/png" />
	<meta name="twitter:card" content="summary_large_image" />
	<script type="application/ld+json" class="yoast-schema-graph">{"@context":"https://schema.org","@graph":[{"@type":"WebPage","@id":"https://marallys.com/","url":"https://marallys.com/","name":"Бесплатный приватный сервер Minecraft с Create - Marallys","isPartOf":{"@id":"https://marallys.com/#website"},"about":{"@id":"https://marallys.com/#organization"},"primaryImageOfPage":{"@id":"https://marallys.com/#primaryimage"},"image":{"@id":"https://marallys.com/#primaryimage"},"thumbnailUrl":"https://marallys.com/wp-content/uploads/2023/08/2023-08-09_00.28.02.png","datePublished":"2022-02-11T11:22:38+00:00","dateModified":"2025-01-21T07:23:12+00:00","description":"Marallys - это полностью бесплатный приватный сервер приближенный к ванильному Майнкрафту (minecraft) с кучей фишек, которые не дадут заскучать любому игроку. Невероятная атмосфера, никаких приватов и грифов, полная свобода творчеству и воображению.","breadcrumb":{"@id":"https://marallys.com/#breadcrumb"},"inLanguage":"ru-RU","potentialAction":[{"@type":"ReadAction","target":["https://marallys.com/"]}]},{"@type":"ImageObject","inLanguage":"ru-RU","@id":"https://marallys.com/#primaryimage","url":"https://marallys.com/wp-content/uploads/2023/08/2023-08-09_00.28.02.png","contentUrl":"https://marallys.com/wp-content/uploads/2023/08/2023-08-09_00.28.02.png","width":1920,"height":1080},{"@type":"BreadcrumbList","@id":"https://marallys.com/#breadcrumb","itemListElement":[{"@type":"ListItem","position":1,"name":"Главная страница"}]},{"@type":"WebSite","@id":"https://marallys.com/#website","url":"https://marallys.com/","name":"Marallys","description":"Marallys","publisher":{"@id":"https://marallys.com/#organization"},"potentialAction":[{"@type":"SearchAction","target":{"@type":"EntryPoint","urlTemplate":"https://marallys.com/?s={search_term_string}"},"query-input":{"@type":"PropertyValueSpecification","valueRequired":true,"valueName":"search_term_string"}}],"inLanguage":"ru-RU"},{"@type":"Organization","@id":"https://marallys.com/#organization","name":"Marallys","url":"https://marallys.com/","logo":{"@type":"ImageObject","inLanguage":"ru-RU","@id":"https://marallys.com/#/schema/logo/image/","url":"https://marallys.com/wp-content/uploads/2023/04/cropped-logo-marallys-purp.png","contentUrl":"https://marallys.com/wp-content/uploads/2023/04/cropped-logo-marallys-purp.png","width":200,"height":50,"caption":"Marallys"},"image":{"@id":"https://marallys.com/#/schema/logo/image/"}}]}</script>
	<!-- / Yoast SEO plugin. -->


<link rel="alternate" type="application/rss+xml" title="Marallys &raquo; Лента" href="https://marallys.com/feed/" />
<link rel="alternate" type="application/rss+xml" title="Marallys &raquo; Лента комментариев" href="https://marallys.com/comments/feed/" />
<script type="4ef472c115034e5c06af6b1a-text/javascript">
window._wpemojiSettings = {"baseUrl":"https:\/\/s.w.org\/images\/core\/emoji\/15.0.3\/72x72\/","ext":".png","svgUrl":"https:\/\/s.w.org\/images\/core\/emoji\/15.0.3\/svg\/","svgExt":".svg","source":{"concatemoji":"https:\/\/marallys.com\/wp-includes\/js\/wp-emoji-release.min.js?ver=6.7.1"}};
/*! This file is auto-generated */
!function(i,n){var o,s,e;function c(e){try{var t={supportTests:e,timestamp:(new Date).valueOf()};sessionStorage.setItem(o,JSON.stringify(t))}catch(e){}}function p(e,t,n){e.clearRect(0,0,e.canvas.width,e.canvas.height),e.fillText(t,0,0);var t=new Uint32Array(e.getImageData(0,0,e.canvas.width,e.canvas.height).data),r=(e.clearRect(0,0,e.canvas.width,e.canvas.height),e.fillText(n,0,0),new Uint32Array(e.getImageData(0,0,e.canvas.width,e.canvas.height).data));return t.every(function(e,t){return e===r[t]})}function u(e,t,n){switch(t){case"flag":return n(e,"\ud83c\udff3\ufe0f\u200d\u26a7\ufe0f","\ud83c\udff3\ufe0f\u200b\u26a7\ufe0f")?!1:!n(e,"\ud83c\uddfa\ud83c\uddf3","\ud83c\uddfa\u200b\ud83c\uddf3")&&!n(e,"\ud83c\udff4\udb40\udc67\udb40\udc62\udb40\udc65\udb40\udc6e\udb40\udc67\udb40\udc7f","\ud83c\udff4\u200b\udb40\udc67\u200b\udb40\udc62\u200b\udb40\udc65\u200b\udb40\udc6e\u200b\udb40\udc67\u200b\udb40\udc7f");case"emoji":return!n(e,"\ud83d\udc26\u200d\u2b1b","\ud83d\udc26\u200b\u2b1b")}return!1}function f(e,t,n){var r="undefined"!=typeof WorkerGlobalScope&&self instanceof WorkerGlobalScope?new OffscreenCanvas(300,150):i.createElement("canvas"),a=r.getContext("2d",{willReadFrequently:!0}),o=(a.textBaseline="top",a.font="600 32px Arial",{});return e.forEach(function(e){o[e]=t(a,e,n)}),o}function t(e){var t=i.createElement("script");t.src=e,t.defer=!0,i.head.appendChild(t)}"undefined"!=typeof Promise&&(o="wpEmojiSettingsSupports",s=["flag","emoji"],n.supports={everything:!0,everythingExceptFlag:!0},e=new Promise(function(e){i.addEventListener("DOMContentLoaded",e,{once:!0})}),new Promise(function(t){var n=function(){try{var e=JSON.parse(sessionStorage.getItem(o));if("object"==typeof e&&"number"==typeof e.timestamp&&(new Date).valueOf()<e.timestamp+604800&&"object"==typeof e.supportTests)return e.supportTests}catch(e){}return null}();if(!n){if("undefined"!=typeof Worker&&"undefined"!=typeof OffscreenCanvas&&"undefined"!=typeof URL&&URL.createObjectURL&&"undefined"!=typeof Blob)try{var e="postMessage("+f.toString()+"("+[JSON.stringify(s),u.toString(),p.toString()].join(",")+"));",r=new Blob([e],{type:"text/javascript"}),a=new Worker(URL.createObjectURL(r),{name:"wpTestEmojiSupports"});return void(a.onmessage=function(e){c(n=e.data),a.terminate(),t(n)})}catch(e){}c(n=f(s,u,p))}t(n)}).then(function(e){for(var t in e)n.supports[t]=e[t],n.supports.everything=n.supports.everything&&n.supports[t],"flag"!==t&&(n.supports.everythingExceptFlag=n.supports.everythingExceptFlag&&n.supports[t]);n.supports.everythingExceptFlag=n.supports.everythingExceptFlag&&!n.supports.flag,n.DOMReady=!1,n.readyCallback=function(){n.DOMReady=!0}}).then(function(){return e}).then(function(){var e;n.supports.everything||(n.readyCallback(),(e=n.source||{}).concatemoji?t(e.concatemoji):e.wpemoji&&e.twemoji&&(t(e.twemoji),t(e.wpemoji)))}))}((window,document),window._wpemojiSettings);
</script>
<style id='wp-emoji-styles-inline-css'>

	img.wp-smiley, img.emoji {
		display: inline !important;
		border: none !important;
		box-shadow: none !important;
		height: 1em !important;
		width: 1em !important;
		margin: 0 0.07em !important;
		vertical-align: -0.1em !important;
		background: none !important;
		padding: 0 !important;
	}
</style>
<link rel='stylesheet' id='wp-block-library-css' href='https://marallys.com/wp-includes/css/dist/block-library/style.min.css?ver=6.7.1' media='all' />
<link rel='stylesheet' id='edsanimate-block-style-css' href='https://marallys.com/wp-content/plugins/animate-it/assets/css/block-style.css?ver=1717403115' media='all' />
<style id='classic-theme-styles-inline-css'>
/*! This file is auto-generated */
.wp-block-button__link{color:#fff;background-color:#32373c;border-radius:9999px;box-shadow:none;text-decoration:none;padding:calc(.667em + 2px) calc(1.333em + 2px);font-size:1.125em}.wp-block-file__button{background:#32373c;color:#fff;text-decoration:none}
</style>
<style id='global-styles-inline-css'>
:root{--wp--preset--aspect-ratio--square: 1;--wp--preset--aspect-ratio--4-3: 4/3;--wp--preset--aspect-ratio--3-4: 3/4;--wp--preset--aspect-ratio--3-2: 3/2;--wp--preset--aspect-ratio--2-3: 2/3;--wp--preset--aspect-ratio--16-9: 16/9;--wp--preset--aspect-ratio--9-16: 9/16;--wp--preset--color--black: #000000;--wp--preset--color--cyan-bluish-gray: #abb8c3;--wp--preset--color--white: #ffffff;--wp--preset--color--pale-pink: #f78da7;--wp--preset--color--vivid-red: #cf2e2e;--wp--preset--color--luminous-vivid-orange: #ff6900;--wp--preset--color--luminous-vivid-amber: #fcb900;--wp--preset--color--light-green-cyan: #7bdcb5;--wp--preset--color--vivid-green-cyan: #00d084;--wp--preset--color--pale-cyan-blue: #8ed1fc;--wp--preset--color--vivid-cyan-blue: #0693e3;--wp--preset--color--vivid-purple: #9b51e0;--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple: linear-gradient(135deg,rgba(6,147,227,1) 0%,rgb(155,81,224) 100%);--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan: linear-gradient(135deg,rgb(122,220,180) 0%,rgb(0,208,130) 100%);--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange: linear-gradient(135deg,rgba(252,185,0,1) 0%,rgba(255,105,0,1) 100%);--wp--preset--gradient--luminous-vivid-orange-to-vivid-red: linear-gradient(135deg,rgba(255,105,0,1) 0%,rgb(207,46,46) 100%);--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray: linear-gradient(135deg,rgb(238,238,238) 0%,rgb(169,184,195) 100%);--wp--preset--gradient--cool-to-warm-spectrum: linear-gradient(135deg,rgb(74,234,220) 0%,rgb(151,120,209) 20%,rgb(207,42,186) 40%,rgb(238,44,130) 60%,rgb(251,105,98) 80%,rgb(254,248,76) 100%);--wp--preset--gradient--blush-light-purple: linear-gradient(135deg,rgb(255,206,236) 0%,rgb(152,150,240) 100%);--wp--preset--gradient--blush-bordeaux: linear-gradient(135deg,rgb(254,205,165) 0%,rgb(254,45,45) 50%,rgb(107,0,62) 100%);--wp--preset--gradient--luminous-dusk: linear-gradient(135deg,rgb(255,203,112) 0%,rgb(199,81,192) 50%,rgb(65,88,208) 100%);--wp--preset--gradient--pale-ocean: linear-gradient(135deg,rgb(255,245,203) 0%,rgb(182,227,212) 50%,rgb(51,167,181) 100%);--wp--preset--gradient--electric-grass: linear-gradient(135deg,rgb(202,248,128) 0%,rgb(113,206,126) 100%);--wp--preset--gradient--midnight: linear-gradient(135deg,rgb(2,3,129) 0%,rgb(40,116,252) 100%);--wp--preset--font-size--small: 13px;--wp--preset--font-size--medium: 20px;--wp--preset--font-size--large: 36px;--wp--preset--font-size--x-large: 42px;--wp--preset--spacing--20: 0.44rem;--wp--preset--spacing--30: 0.67rem;--wp--preset--spacing--40: 1rem;--wp--preset--spacing--50: 1.5rem;--wp--preset--spacing--60: 2.25rem;--wp--preset--spacing--70: 3.38rem;--wp--preset--spacing--80: 5.06rem;--wp--preset--shadow--natural: 6px 6px 9px rgba(0, 0, 0, 0.2);--wp--preset--shadow--deep: 12px 12px 50px rgba(0, 0, 0, 0.4);--wp--preset--shadow--sharp: 6px 6px 0px rgba(0, 0, 0, 0.2);--wp--preset--shadow--outlined: 6px 6px 0px -3px rgba(255, 255, 255, 1), 6px 6px rgba(0, 0, 0, 1);--wp--preset--shadow--crisp: 6px 6px 0px rgba(0, 0, 0, 1);}:where(.is-layout-flex){gap: 0.5em;}:where(.is-layout-grid){gap: 0.5em;}body .is-layout-flex{display: flex;}.is-layout-flex{flex-wrap: wrap;align-items: center;}.is-layout-flex > :is(*, div){margin: 0;}body .is-layout-grid{display: grid;}.is-layout-grid > :is(*, div){margin: 0;}:where(.wp-block-columns.is-layout-flex){gap: 2em;}:where(.wp-block-columns.is-layout-grid){gap: 2em;}:where(.wp-block-post-template.is-layout-flex){gap: 1.25em;}:where(.wp-block-post-template.is-layout-grid){gap: 1.25em;}.has-black-color{color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-color{color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-color{color: var(--wp--preset--color--white) !important;}.has-pale-pink-color{color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-color{color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-color{color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-color{color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-color{color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-color{color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-color{color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-color{color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-color{color: var(--wp--preset--color--vivid-purple) !important;}.has-black-background-color{background-color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-background-color{background-color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-background-color{background-color: var(--wp--preset--color--white) !important;}.has-pale-pink-background-color{background-color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-background-color{background-color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-background-color{background-color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-background-color{background-color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-background-color{background-color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-background-color{background-color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-background-color{background-color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-background-color{background-color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-background-color{background-color: var(--wp--preset--color--vivid-purple) !important;}.has-black-border-color{border-color: var(--wp--preset--color--black) !important;}.has-cyan-bluish-gray-border-color{border-color: var(--wp--preset--color--cyan-bluish-gray) !important;}.has-white-border-color{border-color: var(--wp--preset--color--white) !important;}.has-pale-pink-border-color{border-color: var(--wp--preset--color--pale-pink) !important;}.has-vivid-red-border-color{border-color: var(--wp--preset--color--vivid-red) !important;}.has-luminous-vivid-orange-border-color{border-color: var(--wp--preset--color--luminous-vivid-orange) !important;}.has-luminous-vivid-amber-border-color{border-color: var(--wp--preset--color--luminous-vivid-amber) !important;}.has-light-green-cyan-border-color{border-color: var(--wp--preset--color--light-green-cyan) !important;}.has-vivid-green-cyan-border-color{border-color: var(--wp--preset--color--vivid-green-cyan) !important;}.has-pale-cyan-blue-border-color{border-color: var(--wp--preset--color--pale-cyan-blue) !important;}.has-vivid-cyan-blue-border-color{border-color: var(--wp--preset--color--vivid-cyan-blue) !important;}.has-vivid-purple-border-color{border-color: var(--wp--preset--color--vivid-purple) !important;}.has-vivid-cyan-blue-to-vivid-purple-gradient-background{background: var(--wp--preset--gradient--vivid-cyan-blue-to-vivid-purple) !important;}.has-light-green-cyan-to-vivid-green-cyan-gradient-background{background: var(--wp--preset--gradient--light-green-cyan-to-vivid-green-cyan) !important;}.has-luminous-vivid-amber-to-luminous-vivid-orange-gradient-background{background: var(--wp--preset--gradient--luminous-vivid-amber-to-luminous-vivid-orange) !important;}.has-luminous-vivid-orange-to-vivid-red-gradient-background{background: var(--wp--preset--gradient--luminous-vivid-orange-to-vivid-red) !important;}.has-very-light-gray-to-cyan-bluish-gray-gradient-background{background: var(--wp--preset--gradient--very-light-gray-to-cyan-bluish-gray) !important;}.has-cool-to-warm-spectrum-gradient-background{background: var(--wp--preset--gradient--cool-to-warm-spectrum) !important;}.has-blush-light-purple-gradient-background{background: var(--wp--preset--gradient--blush-light-purple) !important;}.has-blush-bordeaux-gradient-background{background: var(--wp--preset--gradient--blush-bordeaux) !important;}.has-luminous-dusk-gradient-background{background: var(--wp--preset--gradient--luminous-dusk) !important;}.has-pale-ocean-gradient-background{background: var(--wp--preset--gradient--pale-ocean) !important;}.has-electric-grass-gradient-background{background: var(--wp--preset--gradient--electric-grass) !important;}.has-midnight-gradient-background{background: var(--wp--preset--gradient--midnight) !important;}.has-small-font-size{font-size: var(--wp--preset--font-size--small) !important;}.has-medium-font-size{font-size: var(--wp--preset--font-size--medium) !important;}.has-large-font-size{font-size: var(--wp--preset--font-size--large) !important;}.has-x-large-font-size{font-size: var(--wp--preset--font-size--x-large) !important;}
:where(.wp-block-post-template.is-layout-flex){gap: 1.25em;}:where(.wp-block-post-template.is-layout-grid){gap: 1.25em;}
:where(.wp-block-columns.is-layout-flex){gap: 2em;}:where(.wp-block-columns.is-layout-grid){gap: 2em;}
:root :where(.wp-block-pullquote){font-size: 1.5em;line-height: 1.6;}
</style>
<link rel='stylesheet' id='edsanimate-animo-css-css' href='https://marallys.com/wp-content/plugins/animate-it/assets/css/animate-animo.css?ver=6.7.1' media='all' />
<link rel='stylesheet' id='marallys-style-css' href='https://marallys.com/wp-content/themes/marallys/style.css?ver=1.0.0' media='all' />
<script src="https://marallys.com/wp-includes/js/jquery/jquery.min.js?ver=3.7.1" id="jquery-core-js" type="4ef472c115034e5c06af6b1a-text/javascript"></script>
<script src="https://marallys.com/wp-includes/js/jquery/jquery-migrate.min.js?ver=3.4.1" id="jquery-migrate-js" type="4ef472c115034e5c06af6b1a-text/javascript"></script>
<link rel="https://api.w.org/" href="https://marallys.com/wp-json/" /><link rel="alternate" title="JSON" type="application/json" href="https://marallys.com/wp-json/wp/v2/pages/30" /><link rel="EditURI" type="application/rsd+xml" title="RSD" href="https://marallys.com/xmlrpc.php?rsd" />
<meta name="generator" content="WordPress 6.7.1" />
<link rel='shortlink' href='https://marallys.com/' />
<link rel="alternate" title="oEmbed (JSON)" type="application/json+oembed" href="https://marallys.com/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fmarallys.com%2F" />
<link rel="alternate" title="oEmbed (XML)" type="text/xml+oembed" href="https://marallys.com/wp-json/oembed/1.0/embed?url=https%3A%2F%2Fmarallys.com%2F&#038;format=xml" />
<link rel="icon" href="https://marallys.com/wp-content/uploads/2023/11/cropped-favicon-marallys-1-32x32.png" sizes="32x32" />
<link rel="icon" href="https://marallys.com/wp-content/uploads/2023/11/cropped-favicon-marallys-1-192x192.png" sizes="192x192" />
<link rel="apple-touch-icon" href="https://marallys.com/wp-content/uploads/2023/11/cropped-favicon-marallys-1-180x180.png" />
<meta name="msapplication-TileImage" content="https://marallys.com/wp-content/uploads/2023/11/cropped-favicon-marallys-1-270x270.png" />
		<style id="wp-custom-css">
			code {
	    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    font-weight: 700;
    background: linear-gradient(111deg, rgb(255 105 0) 27%, rgb(255 178 0) 74%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}		</style>
		    <!-- Yandex.Metrika counter -->
    <script type="4ef472c115034e5c06af6b1a-text/javascript">
        (function(m,e,t,r,i,k,a){m[i]=m[i]||function(){(m[i].a=m[i].a||[]).push(arguments)};
            m[i].l=1*new Date();
            for (var j = 0; j < document.scripts.length; j++) {if (document.scripts[j].src === r) { return; }}
            k=e.createElement(t),a=e.getElementsByTagName(t)[0],k.async=1,k.src=r,a.parentNode.insertBefore(k,a)})
        (window, document, "script", "https://mc.yandex.ru/metrika/tag.js", "ym");

        ym(87519424, "init", {
            clickmap:true,
            trackLinks:true,
            accurateTrackBounce:true,
            webvisor:true
        });
    </script>
    <noscript><div><img src="https://mc.yandex.ru/watch/87519424" style="position:absolute; left:-9999px;" alt="" /></div></noscript>
    <!-- /Yandex.Metrika counter -->
</head>
<body class="home page-template page-template-index page-template-index-php page page-id-30 wp-custom-logo">



<style>
    #mobileMenu li{
        color: #fff;
        padding: 10px 12px;
        font-weight: 700;
        list-style: none;
        background: #1e1e1e;
        margin: 5px;
        border-radius: 8px;
    }
    #mobileMenu li a{
        color: #fff;
        text-decoration: none;
    }
    #mobileMenu ul{
        background: #181818;
        padding: 5px;
        border-radius: 16px;
        z-index: 999999999 !important;
    }
    .sub-menu li a{
        color: #fff;
        text-decoration: none;
    }
    .sub-menu{
        background: #181818;
        padding: 5px;
        border-radius: 16px;
        z-index: 999999999 !important;
    }

    .sub-menu li{
        color: #fff;
        padding: 10px 12px;
        font-weight: 700;
        list-style: none;
        background: #1e1e1e;
        margin: 5px;
        border-radius: 8px;
    }

</style>
<header class="p-3 text-white">
    <div class="container">
        <div class="d-flex flex-wrap align-items-center justify-content-between">
            <!-- Логотип -->
            <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-white text-decoration-none">
                <img class="logo-marallys" src="https://marallys.com/wp-content/uploads/2023/03/logo-marallys.png" alt="Logo Marallys">
            </a>

            <div class="menu-main-container"><ul id="menu-main" class="menu"><li id="menu-item-1057" class="menu-item menu-item-type-custom menu-item-object-custom current-menu-item current_page_item menu-item-home menu-item-1057"><a href="https://marallys.com/" aria-current="page">Главная</a></li>
<li id="menu-item-1425" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1425"><a href="https://marallys.com/launcher">Лаунчер</a></li>
<li id="menu-item-843" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-843"><a href="https://marallys.com/rules/">Правила</a></li>
<li id="menu-item-1226" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1226"><a href="https://marallys.com/how-play/">Как играть?</a></li>
<li id="menu-item-1354" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1354"><a href="https://marallys.com/news/">Новости</a></li>
<li id="menu-item-1392" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1392"><a href="https://marallys.com/faq/">FAQ</a></li>
<li id="menu-item-1398" class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children menu-item-1398"><a href="#">Разное</a>
<ul class="sub-menu">
	<li id="menu-item-1397" class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1397"><a href="https://marallys.com/screenshots/">Скриншоты</a></li>
</ul>
</li>
</ul></div>
            <!-- Кнопка для мобильного меню (бургер) -->
            <button class="navbar-toggler d-lg-none ms-auto" type="button" data-bs-toggle="collapse" data-bs-target="#mobileMenu" aria-controls="mobileMenu" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"><i class="fas fa-bars" style="color: white; font-size: 24px;"></i></span>
            </button>
        </div>

        <!-- Мобильное меню (только для мобильных устройств) -->
        <div class="collapse d-lg-none" id="mobileMenu">
            <nav class="mobile-menu">
                <ul id="menu-main-1" class="navbar-nav flex-column text-center"><li class="menu-item menu-item-type-custom menu-item-object-custom current-menu-item current_page_item menu-item-home menu-item-1057"><a href="https://marallys.com/" aria-current="page">Главная</a></li>
<li class="menu-item menu-item-type-custom menu-item-object-custom menu-item-1425"><a href="https://marallys.com/launcher">Лаунчер</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-843"><a href="https://marallys.com/rules/">Правила</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1226"><a href="https://marallys.com/how-play/">Как играть?</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1354"><a href="https://marallys.com/news/">Новости</a></li>
<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1392"><a href="https://marallys.com/faq/">FAQ</a></li>
<li class="menu-item menu-item-type-custom menu-item-object-custom menu-item-has-children menu-item-1398"><a href="#">Разное</a>
<ul class="sub-menu">
	<li class="menu-item menu-item-type-post_type menu-item-object-page menu-item-1397"><a href="https://marallys.com/screenshots/">Скриншоты</a></li>
</ul>
</li>
</ul>            </nav>
        </div>
    </div>
</header>

<!-- Yandex.RTB R-A-1741418-2 -->
<script type="4ef472c115034e5c06af6b1a-text/javascript">
    window.yaContextCb.push(() => {
        Ya.Context.AdvManager.render({
            "blockId": "R-A-1741418-2",
            "type": "fullscreen",
            "platform": "desktop"
        })
    })
</script>

<!-- Yandex.RTB R-A-1741418-3 -->
<script type="4ef472c115034e5c06af6b1a-text/javascript">
    window.yaContextCb.push(() => {
        Ya.Context.AdvManager.render({
            "blockId": "R-A-1741418-3",
            "type": "fullscreen",
            "platform": "touch"
        })
    })
</script>

<style>
    .overlay-main {
        position: absolute;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        opacity: 0.3;
        z-index: -3;
        background-position: 50% 50%;
        background-repeat: no-repeat;
        background: linear-gradient(to bottom, rgb(255 255 255 / 0%), rgb(0 0 0)), url(https://marallys.com/wp-content/uploads/2023/03/content.png);
        background-size: cover;
    }

    ul {
        margin: 0;
        padding: 0;
    }

    .social-links li {
        display: inline-block;
    }

    p {
        margin: 0;
    }

</style>

<div class="container py-5 pb-3 z-depth-1">
    <section class="mt-5 mb-5 pb-5 text-center text-lg-left dark-grey-text">
        <div class="overlay-main"></div>
        <div class="row">
            <div class="col-md-6 mb-4 mb-md-0 px-4  animated fadeIn duration6">
                <div style="
    text-align: initial;
">
                    <h3 class="font-weight-bold text-white main-title" style="line-height: 60px;color: #fff !important;font-size: 70px;margin-top: 60px;display: inline-block;">Marallys</h3> <div class="gradient-text" style="display: inline-block;font-size: 32px;font-weight: 800;position: relative;z-index: -1">FREE</div>
                </div>
                <h3 class="font-weight-bold text-white main-title">Приватный сервер</h3>
                <div class="sub-title">Minecraft</div>
                <p class="text-white mt-3 marallys-desk-1">Испытай игру по-новому, погрузись в мир приключений<br> с
                    замечательным и дружелюбным комьюнити</p>
                <a class="btn btn-play btn-md ml-0 text-white mt-3"
                   href="https://marallys.com/how-play/" role="button">Начать
                    играть</a>
            </div>


            <div class="col-md-6 mb-4 mb-md-0" style="position: relative;">
                <!-- Фон логотипа -->
                <img src="https://marallys.com/wp-content/uploads/2024/10/лого-чупапимуняню.png" style="
        width: 230px;
        margin: auto;
        z-index: -2222222;
        opacity: 0.1;
        filter: invert(1);
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    ">

                <style>
                    .main-tags{
                        padding: 4px 12px;
                        background: rgb(0 0 0 / 10%);
                        border-radius: 8px;
                        color: #fff;
                        font-weight: bold;
                        backdrop-filter: blur(6px);
                    }

                </style>

                <div class="mt-auto">
                    <ul class="social-links">
                        <li>
                            <a href="https://vk.com/marallys"><i class="fa-brands fa-vk"></i></a>
                        </li>
                        <li>
                            <a href="https://t.me/verkme"><i class="fa-brands fa-telegram"></i></a>
                        </li>
                        <li>
                            <a href="https://www.youtube.com/channel/UCq7xrDQ_vuzFe_HylOo7QXA"><i class="fa-brands fa-youtube"></i></a>
                        </li>
                        <li>
                            <a href="https://www.twitch.tv/verkme"><i class="fa-brands fa-twitch"></i></a>
                        </li>
                    </ul>
                    <p class="text-white" style="font-weight: 700">Верификация происходит в телеграм боте, сервер абсолютно бесплатный.</p>
                </div>
            </div>

        </div>
</div>
</section>




</div>





    <section class="mb-4">
        <div class="col-md-12 mb-4 mb-md-0"
             style="position: relative; overflow: hidden; display: flex; flex-direction: column; align-items: center;">

            <style>
                .carousel-tags-container {
                    width: 100%;
                    white-space: nowrap;
                    overflow: hidden;
                    position: relative;
                }

                .carousel-tags {
                    display: inline-block;
                    animation: scroll-tags 30s linear infinite; /* Прокрутка в два раза медленнее */
                }

                .main-tags {
                    display: inline-block;
                    padding: 4px 12px;
                    margin: 0 8px;
                    background: rgb(0 0 0 / 10%);
                    border-radius: 8px;
                    color: #fff;
                    font-weight: bold;
                    backdrop-filter: blur(6px);
                    transition: transform 1s ease, opacity 0.5s ease; /* Плавное уменьшение */
                }

                @keyframes scroll-tags {
                    0% {
                        transform: translateX(0);
                    }
                    100% {
                        transform: translateX(-100%);
                    }
                }

                @keyframes pulse-tags {
                    0%, 100% {
                        transform: scale(1);
                    }
                    50% {
                        transform: scale(1.3); /* Увеличиваем размер */
                    }
                }

                .main-tags.pulse {
                    animation: pulse-tags 2s ease-in-out; /* Более плавная анимация */
                }
            </style>

            <div class="carousel-tags-container">
                <div class="carousel-tags" id="tagCarousel"></div>
            </div>

            <script type="4ef472c115034e5c06af6b1a-text/javascript">
                document.addEventListener('DOMContentLoaded', () => {
                    const tagList = [
                        "#СамыйКрутойCreateСервер",
                        "#БольшойОнлайн",
                        "#МощнейшееОборудование",
                        "#АбсолютноБесплатно",
                        "#ДружелюбноеКомьюнити",
                        "#НовыеГенерации",
                        "#Create",
                        "#БезОграничений",
                        "#ComputerCraft",
                        "#УникальныеСервера",
                        "#ЛучшиеСборки",
                        "#СамописныеМоды",
                        "#MarallysForever",
                        "#ПогрузисьВMarallys"
                    ];

                    // Перемешиваем теги случайным образом при загрузке страницы
                    const shuffledTags = tagList.sort(() => Math.random() - 0.5);
                    const tagCarousel = document.getElementById('tagCarousel');

                    // Создаем элементы тегов
                    shuffledTags.forEach(tag => {
                        const span = document.createElement('span');
                        span.className = 'main-tags';
                        span.textContent = tag;
                        tagCarousel.appendChild(span);
                    });

                    const tags = document.querySelectorAll('.main-tags');

                    setInterval(() => {
                        // Убираем класс "pulse" у всех тегов
                        tags.forEach(tag => tag.classList.remove('pulse'));

                        // Выбираем случайный тег
                        const randomTag = tags[Math.floor(Math.random() * tags.length)];
                        randomTag.classList.add('pulse');

                        // Убираем класс "pulse" через 2 секунды для плавного завершения
                        setTimeout(() => {
                            randomTag.classList.remove('pulse');
                        }, 2000);
                    }, 3000); // Каждые 3 секунды анимация "пульсации"
                });
            </script>
        </div>
    </section>







<div class="spacer"><img class="m-auto d-block" src="https://marallys.com/wp-content/uploads/2023/11/divider-01.png">
</div>
    <div class="container my-5 z-depth-1">

    <style>
        .head-player{
            width: 50px;
            height: 50px;
        }
        .player-head-block
        {
            padding-right: 8px;
        }
        .player-element{
            background: #181818;
            padding: 20px;
            border-radius: 24px !important;
            margin: 8px;
        }
    </style>


    <section class="">
        <h2 class="title-block text-center font-weight-bold mb-2 text-white  animated fadeIn duration6 eds-on-scroll"
            style="font-weight: 700;">Это <span class="gradient-text" style="font-weight: 700;">не</span> просто сервер
        </h2>
        <p class="text-center lead grey-text mx-auto mb-5 text-white     animated fadeIn delay1 duration8"
           style="font-weight: 500;">Целый виртуальный мир и множество потенциальных друзей ждут тебя. Окунись в
            необъятные просторы <span class="gradient-text" style="font-weight: 700;">Marallys</span>, где мы сделали
            всё, чтобы твой игровой опыт был лучшим. Высокая производительность и уникальные сборки серверов.</p>
        <div class="row">
            <div class="col-lg-4 col-md-6 mb-3 animated fadeIn delay2 duration8">
                <div class="col-md-12 features-background">
                    <h4 class="font-weight-bold mb-3 features-marallys">
                        <i class="fa-solid fa-server indigo-text pr-2"></i> Мощное<br>оборудование
                    </h4>
                    <p class="features-text">
                        Наш проект работает на оборудовании стоимостью более 200 тысяч рублей! Мы всегда инвестируем в надежность и производительность, чтобы вы наслаждались игрой без лагов и сбоев. 💪⚡
                    </p>
                </div>
            </div>
            <div class="col-lg-4 col-md-6 mb-3 animated fadeIn duration6 eds-on-scroll">
                <div class="col-md-12 features-background">
                    <h4 class="font-weight-bold mb-3 features-marallys">
                        <i class="fa-solid fa-mug-hot green-text pr-2"></i> Постоянные<br>обновления
                    </h4>
                    <p class="features-text">
                        Мы не просто обновляем проект — мы постоянно улучшаем его! Новые фичи, захватывающий контент, уникальные улучшения и оптимизация. Каждый апдейт делает вашу игру еще интереснее и комфортнее. 🔧✨
                    </p>
                </div>
            </div>

            <div class="col-lg-4 col-md-6 mb-3 animated fadeIn duration6 eds-on-scroll">
                <div class="col-md-12 features-background">
                    <h4 class="font-weight-bold mb-3 features-marallys">
                        <i class="fa-solid fa-users amber-text pr-2"></i> Высокий<br>онлайн
                    </h4>
                    <p class="features-text">
                        Мы поддерживаем стабильный онлайн до 50 игроков, предлагая уникальный опыт игры с 290 модами и полным отсутствием ограничений механик! 😯
                    </p>
                </div>
            </div>

            <div class="col-lg-4 col-md-6 mb-3 animated fadeIn duration6 eds-on-scroll">
                <div class="col-md-12 features-background">
                    <h4 class="font-weight-bold mb-3 features-marallys">
                        <i class="fa-solid fa-code green-text pr-2"></i> Уникальные<br>разработки
                    </h4>
                    <p class="features-text">
                        Мы создаём всё с нуля: сайты, Telegram-ботов, моды и плагины для нашего проекта. Всё это — ради уникальности, стабильности и вашего удовольствия в игре! 🚀
                    </p>
                </div>
            </div>


            <div class="col-lg-4 col-md-6 mb-3 animated fadeIn duration6 eds-on-scroll">
                <div class="col-md-12 features-background">
                    <h4 class="font-weight-bold mb-3 features-marallys">
                        <i class="fa-solid fa-barcode amber-text pr-2"></i> Уникальность<br>Marallys
                    </h4>
                    <p class="features-text">
                        Мы не следуем за общими шаблонами и трендами — наш проект создается с нуля, чтобы удивлять и радовать вас! Каждый сервер, каждое обновление и каждый мод — это уникальный опыт, который вы больше нигде не найдете. 🌟
                    </p>
                </div>
            </div>
            <div class="col-lg-4 col-md-6 mb-3  animated fadeIn duration6 eds-on-scroll ">
                <div class="col-md-12 features-background">
                    <h4 class="font-weight-bold mb-3 features-marallys">
                        <i class="fa-sharp fa-solid fa-shield-cat red-text pr-2"></i> Адекватное <br>комьюнити
                    </h4>
                    <p class="features-text mb-lg-0">
                        Не бойся за свою кибитку, мы тщательно модерируем каждого и не допустим гриферов, а также у нас на каждом сервере есть системы отката одной командой 🤡
                    </p>
                </div>
            </div>
            <div class="col-lg-4 col-md-6 mb-3  animated fadeIn duration6 eds-on-scroll ">
                <div class="col-md-12 features-background">
                    <h4 class="font-weight-bold mb-3 features-marallys">
                        <i class="fa-solid fa-globe red-text pr-2"></i> Новая <br>генерация
                    </h4>
                    <p class="features-text mb-lg-0">
                        Полностью переделанные генерации Overworld, end, nether! Более 200 новых данжей и биомов и невероятная красота на каждом нашем сервере🌵
                    </p>
                </div>
            </div>


<!--            <div class="col-lg-4 col-md-6 mb-3  animated fadeIn duration6 eds-on-scroll ">-->
<!--                <div class="col-md-12 features-background">-->
<!--                    <h4 class="font-weight-bold mb-3 features-marallys">-->
<!--                        <i class="fa-solid fa-camera red-text pr-2"></i> Автоматические <br>стримы-->
<!--                    </h4>-->
<!--                    <p class="features-text mb-lg-0">-->
<!--                        На некоторых серверах есть авто-стримы! Теперь каждый игрок — стример! Камера автоматически переключается на самые интересные моменты. Хотите больше контроля? /standcam — статичная съемка, /skipcam — пропустить камеру, /takecam — захват трансляции. Ваша игра, ваше шоу! 🎥-->
<!--                    </p>-->
<!--                </div>-->
<!--            </div>-->

            <div class="col-lg-4 col-md-6 mb-3  animated fadeIn duration6 eds-on-scroll ">
                <div class="col-md-12 features-background">
                    <h4 class="font-weight-bold mb-3 features-marallys">
                        <i class="fa-solid fa-code red-text pr-2"></i> Телеграм <br>бот <a  style="text-decoration: none;" href="https://t.me/Marallys_bot">@Marallys_bot</a>
                    </h4>
                    <p class="features-text mb-lg-0">
                        Мы разработали невероятно функционального и уникального бота, который будет являться вашим компаньонон во время игры, всё взаимодействие с проектом проходит через него
                        💾
                    </p>
                </div>
            </div>

            <div class="col-lg-4 col-md-6 mb-3 animated fadeIn duration6 eds-on-scroll">
                <div class="col-md-12 features-background">
                    <h4 class="font-weight-bold mb-3 features-marallys">
                        <i class="fa-solid fa-wallet lime-text pr-2"></i> Бесплатный<br>доступ
                    </h4>
                    <p class="features-text mb-lg-0">
                        Наш проект открыт для всех! Приватные серверы Marallys — это не про деньги, а про искреннее сообщество игроков-единомышленников. Всё, что нужно для захватывающих приключений, уже доступно бесплатно! 🤑
                    </p>
                </div>
            </div>

            <div class="col-lg-4 col-md-6 mb-3  animated fadeIn duration6 eds-on-scroll ">
                <div class="col-md-12 features-background">
                    <h4 class="font-weight-bold mb-3 features-marallys">
                        <i class="fa-solid fa-unlock blue-text pr-2"></i> Полная <br>свобода
                    </h4>
                    <p class="features-text mb-lg-0">
                        Мы не душим ванильные механики игры и предоставляем полную свободу действий и реализаций 😇
                    </p>
                </div>
            </div>

            <div class="col-lg-4 col-md-6 mb-3  animated fadeIn duration6 eds-on-scroll ">
                <div class="col-md-12 features-background">
                    <h4 class="font-weight-bold mb-3 features-marallys">
                        <i class="fa-solid fa-map lime-text pr-2"></i> Расширяемые <br>границы
                    </h4>
                    <p class="features-text mb-lg-0">
                        Мы регулярно расширяем границы миров на серверах по мере изведанности и роста игроков ⛰
                    </p>
                </div>
            </div>

            <div class="col-lg-4 col-md-6 mb-3  animated fadeIn duration6 eds-on-scroll ">
                <div class="col-md-12 features-background">
                    <h4 class="font-weight-bold mb-3 features-marallys">
                        <i class="fa-solid fa-people-group blue-text pr-2"></i> Дружелюбное <br>комьюнити
                    </h4>
                    <p class="features-text mb-lg-0">
                        Никаких токсиков, мирная и вайбовая атмосфера, где ты найдешь себе кучу друзей 🤟
                    </p>
                </div>
            </div>
            
        </div>
    </section>





    <style>
    .projects-element li {
     list-style: none;
     display: inline-block;
    }

    .projects-title{
    color: #fff;
    text-align: center;
    font-weight: 800;
    }
    .btn-project
    {
    padding: 10px 20px;
    border-radius: 8px;
    text-decoration: none;
    color: #fff;
    background: #b300ff;
    margin: 0px 10px;
    }

    .btn-project:hover{
       color: #fff;
       opacity: 0.8;
    }
    </style>





    <div>
    </div>


<section class="mt-5 text-center text-lg-left dark-grey-text">
    <div class="row">
                        <div class="col-md-6 mb-4 mb-md-0">
                    <h3 class="font-weight-bold text-white main-title">VanillaPlus</h3>
                    <div class="sub-title-season">Ванильный сервер, для игры на нём не требуется модовый клиент, но рекомендуется наша сборка. Вы полностью погрузитесь в игровой процесс и насладитесь атмосферой и интересным геймплеем. Повышенный спавн-рейт, большая дальность прорисовки, отсутствие любых ограничений и множество разнообразного авторского контента - все это улучшает впечатления от игры, при этом сохраняя ванильный стиль.</div>
                    <p class="text-white mt-3 marallys-desk-1">Дата начала вайпа: 26.12.2024</p>

                    <div class="progress" style="height: 28px; background: #ffffff38;">
                        <div class="progress-bar" role="progressbar"
                             style="width: 20%; background: var(--main-gradient); font-weight: 600; font-size: 18px;"
                             aria-valuenow="20"
                             aria-valuemin="0"
                             aria-valuemax="100">
                            20%                        </div>
                    </div>
                </div>
                                <div class="col-md-6 mb-4 mb-md-0">
                    <h3 class="font-weight-bold text-white main-title">Extra_1</h3>
                    <div class="sub-title-season">Модовый сервер, построенный вокруг мода Create и его дополнений, предлагает полную свободу творчества без каких-либо ограничений. Здесь вы найдете множество увлекательных дополнений: новые виды еды с интересными рецептами приготовления, развитое фермерство, разнообразие уникальных мобов, полностью переработанные и кастомные генерации мира, а также увеличенный уровень сложности, который добавляет больше динамики и вызовов и многое другое!</div>
                    <p class="text-white mt-3 marallys-desk-1">Дата начала вайпа: 01.12.2024</p>

                    <div class="progress" style="height: 28px; background: #ffffff38;">
                        <div class="progress-bar" role="progressbar"
                             style="width: 36%; background: var(--main-gradient); font-weight: 600; font-size: 18px;"
                             aria-valuenow="36"
                             aria-valuemin="0"
                             aria-valuemax="100">
                            36%                        </div>
                    </div>
                </div>
                                <div class="col-md-6 mb-4 mb-md-0">
                    <h3 class="font-weight-bold text-white main-title">Extra_2</h3>
                    <div class="sub-title-season">Модовый сервер, построенный вокруг мода Create и его дополнений, предлагает полную свободу творчества без каких-либо ограничений. Здесь вы найдете множество увлекательных дополнений: новые виды еды с интересными рецептами приготовления, развитое фермерство, разнообразие уникальных мобов, полностью переработанные и кастомные генерации мира, а также увеличенный уровень сложности, который добавляет больше динамики и вызовов и многое другое!</div>
                    <p class="text-white mt-3 marallys-desk-1">Дата начала вайпа: 24.01.2025</p>

                    <div class="progress" style="height: 28px; background: #ffffff38;">
                        <div class="progress-bar" role="progressbar"
                             style="width: 0%; background: var(--main-gradient); font-weight: 600; font-size: 18px;"
                             aria-valuenow="0"
                             aria-valuemin="0"
                             aria-valuemax="100">
                            Сезон только начался                        </div>
                    </div>
                </div>
                    </div>
</section>



    <section class="pt-5 z-depth-1">

        <h3 class="text-center font-weight-bold mb-5 text-white fw-bold">Немного информации</h3>

        <div class="row d-flex justify-content-center">

            <div class="col-md-6 col-lg-3 text-center">
                <h4 class="h1 font-weight-normal mb-3">
                    <i class="fas fa-file-alt indigo-text counter-icon-grad" aria-hidden="true"></i>
                    <span class="d-inline-block count-up text-white" data-from="0" data-to="100"
                          data-time="2000">
                            <p>6748</p>                    </span>
                </h4>
                <p class="text-white sub-title-counter">Заявок одобрено</p>
            </div>

            <div class="col-md-6 col-lg-3 text-center">
    <h4 class="h1 font-weight-normal mb-3">
        <i class="fas fa-layer-group indigo-text counter-icon-grad" aria-hidden="true"></i>
        <span class="d-inline-block count1 text-white" data-from="0" data-to="250" data-time="2000">
            3        </span>
    </h4>
    <p class="text-white sub-title-counter">Количество серверов</p>
</div>


    
<div class="col-md-6 col-lg-3 text-center">
    <h4 class="h1 font-weight-normal mb-3">
        <i class="fa-solid fa-cake-candles counter-icon-grad"></i>
        <span class="d-inline-block count2 text-white" data-from="0" data-to="330" data-time="2000">
            3.1 Лет        </span>
    </h4>
    <p class="font-weight-normal sub-title-counter">Возраст проекта</p>
</div>



            <div class="col-md-6 col-lg-3 text-center">
                <h4 class="h1 font-weight-normal mb-3">
                    <i class="fa-solid fa-joint counter-icon-grad"></i>
                    <span class="d-inline-block count3 text-white" data-from="0" data-to="430"
                          data-time="2000">1000000</span>
                </h4>
                <p class="font-weight-normal sub-title-counter">Амбиций</p>
            </div>

        </div>

    </section>


    <section class="animated fadeIn duration6 eds-on-scroll">
        <hr class="w-header my-4" style="border-color: #4c4c4c;">
        <h6 class="font-weight-bold text-center grey-text text-uppercase small mb-2 text-white mt-5">Начни свой
            путь</h6>
        <h3 class="font-weight-bold text-center dark-grey-text pb-2 fw-bold text-white mb-3">Описание серверов</h3>

        <div class="row d-flex justify-content-center">

            <div class="col-md-6">

                <p class="small text-white server-subdesc">Комплекс приватных серверов</p>

                <p class="mb-5 pb-2 server-desc text-white">
                    Marallys — это комплекс уникальных приватных серверов Minecraft, предлагающий совершенно новый опыт игры.
                </p>

                <p class="mb-5 pb-2 server-desc text-white">
                    Наш проект создан для увлекательных приключений во вселенной Minecraft в кругу приятного и дружелюбного
                    комьюнити. Здесь вы найдете не только классический ванильный опыт игры, но и увлекательные модификации,
                    которые расширяют возможности Minecraft и открывают новые горизонты для вашего творчества.
                </p>

                <p class="mb-5 pb-2 server-desc text-white">
                    В Marallys есть три приватных сервера, каждый из которых предоставляет уникальный игровой опыт. Наш
                    лаунчер делает процесс подключения простым и удобным: вы сможете автоматически установить все необходимые
                    моды и легко переключаться между серверами.
                </p>

                <h4 class="text-white mt-4">Наши сервера:</h4>

                <ul class="mb-5 pb-2 server-desc text-white">
                    <li>
                        <strong>VanillaPlus</strong> — Ванильный сервер, который сохраняет оригинальный стиль Minecraft, но
                        предлагает улучшения: повышенный спавн-рейт, большая дальность прорисовки, авторский контент и
                        множество других дополнений для комфортной игры.
                    </li>
                    <li>
                        <strong>Extra</strong> — Модовый приватный сервер, построенный вокруг мода <em>Create</em> и его
                        дополнений. Полная свобода творчества: новые виды еды, развитое фермерство, уникальные мобы,
                        переработанные генерации миров и увеличенный уровень сложности.
                    </li>
                    <li>
                        <strong>Astra</strong> — Эталонный модовый приватный сервер с уникальной сборкой, в которой
                        сочетаются <em>Create</em>, <em>Valkyrien Skies</em>, <em>Trackworks</em>, <em>Clockwork</em> и
                        <em>Eureka</em>. Новые генерации миров, данжи, боссы и множество других возможностей для увлекательных
                        приключений.
                    </li>
                </ul>

                <p class="mb-5 pb-2 server-desc text-white">
                    Ознакомьтесь с правилами и инструкциями для начала игры на нашем проекте: <a href="https://marallys.com/how-play/" class="text-white">https://marallys.com/how-play/</a>.
                </p>

            </div>

        </div>
    </section>

    <hr class="w-header my-4" style="border-color: #4c4c4c;">


    <section class="container px-4 animated fadeIn duration6 eds-on-scroll">
    <h6 class="font-weight-bold text-center grey-text text-uppercase small mb-2 text-white mt-5">Наши сервера</h6>
    <h3 class="font-weight-bold text-center dark-grey-text pb-2 fw-bold text-white mb-3">Высокая производительность и надёжность</h3>

    <p class="text-center text-white">
        У нас есть два мощных сервера. Первый обеспечивает работу сайта, Telegram-бота и лаунчера, а второй используется для хостинга игровых серверов, гарантируя минимальную задержку и стабильность работы.
    </p>

    <div class="row row-cols-1 row-cols-sm-2 row-cols-md-2 row-cols-lg-2 g-4 py-5">
        <!-- Первый сервер -->
        <div class="col d-flex align-items-start pont-element">
            <i class="fa-solid fa-server icon-ponts"></i>
            <div>
                <h3 class="fw-bold mb-0 fs-4 text-white pont-title">Железо для сайта, бота и лаунчера</h3>
                <ul class="text-white pont-desc list-unstyled mb-0">
                    <li><i class="fa-solid fa-microchip me-2"></i> 40 ядер</li>
                    <li><i class="fa-solid fa-memory me-2"></i> 64 GB оперативной памяти</li>
                    <li><i class="fa-solid fa-hard-drive me-2"></i> Высокоскоростной диск</li>
                    <li><i class="fa-solid fa-ethernet me-2"></i> 1 Гб/сек</li>
                </ul>
                <p class="text-white mt-2">Этот сервер обеспечивает работу всех инфраструктурных решений.</p>
            </div>
        </div>

        <!-- Второй сервер -->
        <div class="col d-flex align-items-start pont-element">
            <i class="fa-solid fa-server icon-ponts"></i>
            <div>
                <h3 class="fw-bold mb-0 fs-4 text-white pont-title">Железо для игровых серверов</h3>
                <ul class="text-white pont-desc list-unstyled mb-0">
                    <li><i class="fa-solid fa-microchip me-2"></i> I9 12900K</li>
                    <li><i class="fa-solid fa-memory me-2"></i> 128 GB DDR4</li>
                    <li><i class="fa-solid fa-hard-drive me-2"></i> 4 TB NVMe M.2</li>
                    <li><i class="fa-solid fa-ethernet me-2"></i> 1 Гб/сек</li>
                </ul>
                <p class="text-white mt-2">Этот сервер гарантирует быструю и стабильную работу игровых миров.</p>
            </div>
        </div>
    </div>
</section>



 <hr class="w-header my-4" style="border-color: #4c4c4c;">





<style>
.bg-black-01{
border-radius: 8px;
}
</style>


<!-- <section class="section-block">-->
<!--                <h6 class="font-weight-bold text-center grey-text text-uppercase small mb-2 text-white mt-5">Автоматические стримы</h6>-->
<!--        <h3 class="font-weight-bold text-center dark-grey-text pb-2 fw-bold text-white mb-3">Следи за жизнью сервера в реальном времени</h3>-->
<!---->
<!--    <div class="container">-->
<!--        <div class="row justify-content-center mb-4">-->
<!--            <div class="col-md-10 text-center">-->
<!--                <p>Теперь каждый игрок может стать стримером! Наша система авто-стримов выбирает и показывает самые интересные моменты игры в прямом эфире на нашем канале. Камера автоматически переключается между игроками, но вы также можете управлять трансляцией с помощью команд:</p>-->
<!--            </div>-->
<!--        </div>-->
<!---->
<!--        <div class="row justify-content-center">-->
<!--            <div class="col-md-10">-->
<!--             <h6 class="font-weight-bold mb-2 text-white">Команды:</h6>-->
<!--                <ul class="list-unstyled">-->
<!--                    <li class="list-commands"><strong>/standcam</strong> — установить камеру в статичное положение, снимая выбранную локацию.</li>-->
<!--                    <li class="list-commands"><strong>/skipcam</strong> — пропустить камеру, если она переключилась на вас.</li>-->
<!--                    <li class="list-commands"><strong>/takecam</strong> — захватить камеру под свой контроль для трансляции от вашего лица.</li>-->
<!--                </ul>-->
<!--                <p>Камера также захватывает голосовой чат, позволяя вам общаться прямо на стриме.</p>-->
<!--            </div>-->
<!--        </div>-->
<!---->
<!---->
<!--    </div>-->
<!--</section>-->


 <section class="section-block">
                <h6 class="font-weight-bold text-center grey-text text-uppercase small mb-2 text-white mt-5">Скриншоты</h6>
        <h3 class="font-weight-bold text-center dark-grey-text pb-2 fw-bold text-white mb-3">Погрузись в нашу атмосферу</h3>
                <div id="static-thumbnails" class="row row-cols-1 row-cols-md-4 g-3">
                    <!-- Здесь будут загружаться скриншоты -->
                </div>
                <div id="load-more-container" class="text-center mt-3">
                    <a href="screenshots"  class="btn btn-play btn-md ml-0 text-white mt-3" style="margin: auto;">Показать ещё</a>
                </div>
                <!-- id="load-more" ?> -->

                <script type="4ef472c115034e5c06af6b1a-text/javascript">
        document.addEventListener('DOMContentLoaded', function () {
            // Получаем скриншоты с сервера
            const screenshots = ["https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2023-05-14_02.22.40.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2023-05-14_02.22.56.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2023-05-14_02.23.04.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2023-05-14_02.23.27.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2023-05-14_02.24.09.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2023-05-14_02.24.18.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2023-05-14_02.26.43.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2023-05-14_02.27.05.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2023-05-14_02.27.16.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2023-05-14_02.27.30.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.13.13.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.13.27.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.13.39.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.13.46.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.13.58.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.14.21.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.19.40.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.19.48.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.20.02.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.20.07.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.20.45.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.21.31.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.21.37.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.21.47.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.21.57.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.22.09.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.22.20.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.22.25.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.37.59.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.38.14.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.39.28.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.39.43.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.40.19.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.40.33.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.40.48.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.41.02.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.41.16.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.41.19.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.41.28.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.41.36.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.41.49.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.42.01.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.42.07.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.42.22.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.42.33.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.42.45.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.43.18.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.43.26.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.43.49.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.44.03.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.44.05.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.44.17.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.44.33.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.44.57.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.45.04.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.45.20.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.45.39.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.45.55.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.46.23.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.46.42.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.47.20.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.48.15.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.48.35.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.48.44.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.48.52.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.48.59.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_13.50.03.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.02.29.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.03.04.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.27.03.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.27.23.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.27.40.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.29.09.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.29.33.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.29.46.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.30.19.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.31.15.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.32.22.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.32.27.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.32.37.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.33.41.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.33.50.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.33.57.png","https:\/\/marallys.com\/wp-content\/themes\/marallys\/screenshots\/2024-10-23_14.34.06.png"];

            const galleryContainer = document.getElementById('static-thumbnails');
            const imagesToShow = 12; // Количество изображений для отображения

            // Загружаем первые 10 изображений
            screenshots.slice(0, imagesToShow).forEach((image) => {
                const anchor = document.createElement('a');
                anchor.href = image;
                const img = document.createElement('img');
                img.src = image;
                img.classList.add('img-fluid', 'bg-black-01');
                anchor.appendChild(img);
                galleryContainer.appendChild(anchor);
            });

            // Инициализация LightGallery для галереи
            lightGallery(galleryContainer, {
                animateThumb: false,
                zoomFromOrigin: false,
                allowMediaOverlap: true,
                toggleThumb: true,
                selector: 'a'
            });
        });
    </script>
</section>

</div>




<footer class="text-center text-lg-start footer-bg text-white mt-5">
    <!-- Section: Social media -->
    <section class="d-flex justify-content-center justify-content-lg-between p-4 border-bottom" style="border-bottom: 1px solid #181818!important;">
        <!-- Left -->
        <div class="me-5 d-none d-lg-block">
            <span class="fw-bold">Наши ссылки:</span>
        </div>
        <!-- Left -->

        <!-- Right -->
        <div>
            <a href="https://t.me/verkme" class="me-4">
                <i class="fa-brands fa-telegram"></i>
            </a>
            <a href="https://vk.com/marallys" class="me-4">
                <i class="fa-brands fa-vk"></i>
            </a>
            <a href="https://www.youtube.com/channel/UCq7xrDQ_vuzFe_HylOo7QXA" class="me-4">
                <i class="fa-brands fa-youtube"></i>
            </a>
            <a href="https://discord.gg/cgMQ9mMP6C" class="me-4">
                <i class="fa-brands fa-discord"></i>
            </a>
        </div>


        <!-- Right -->
    </section>
    <!-- Section: Social media -->

    <!-- Section: Links  -->
    <section class="text-white" ">
        <div class="container text-center text-md-start mt-5">
            <!-- Grid row -->
            <div class="row mt-3">
                <!-- Grid column -->
                <div class="col-md-3 col-lg-4 col-xl-3 mx-auto mb-4">
                    <!-- Content -->
                    <h6 class="text-uppercase fw-bold mb-4">
                        <i class="fa-solid fa-cube me-3"></i>Marallys
                    </h6>
                    <p>
                        Целый виртуальный мир и множество потенциальных друзей ждут тебя. Окунись в необъятные просторы Marallys, где мы сделали всё, чтобы твой игровой опыт был лучшим.
                    </p>
                </div>
                <!-- Grid column -->

                <!-- Grid column
                <div class="col-md-2 col-lg-2 col-xl-2 mx-auto mb-4">
                    <h6 class="text-uppercase fw-bold mb-4">
                        Наши проекты
                    </h6>
                    <p>
                        <a href="https://resourcepack.ru/" class="text-reset">Портал по Minecraft</a>
                    </p>
                </div> -->

                <div class="col-md-3 col-lg-2 col-xl-2 mx-auto mb-4">
                    <!-- Links -->
                    <h6 class="text-uppercase fw-bold mb-4">
                        Важные ссылки
                    </h6>
                    <p>
                        <a href="#!" class="text-reset">Правила</a>
                    </p>
                    <p>
                        <a href="#!" class="text-reset">Новости</a>
                    </p>
                </div>
                <!-- Grid column -->

                <!-- Grid column -->
                <div class="col-md-4 col-lg-3 col-xl-3 mx-auto mb-md-0 mb-4">
                    <!-- Links -->
                    <h6 class="text-uppercase fw-bold mb-4">Связь с администрацией</h6>
                    <p><i class="fa-brands fa-vk"></i> <a href="https://vk.com/marallys" class="text-white">Группа ВК</a></p>
                    <p><i class="fa-brands fa-telegram"></i> <a href="https://t.me/verkme" class="text-white">Telegram</a></p>
                    <p><i class="fa-brands fa-discord"></i> <a  href="https://discord.gg/5dcwV28X" class="text-white">Discord</a></p>
                </div>
                <!-- Grid column -->
            </div>
            <!-- Grid row -->
        </div>
    </section>
    <!-- Section: Links  -->

    <!-- Copyright -->
    <div class="text-center p-4 text-white">
        © 2025 Copyright:
        <a class="text-reset fw-bold" href="https://verkme.com">Разработка verkme</a>
    </div>

    <!-- Copyright -->
</footer>
<!-- Footer -->
			</footer><!-- #site-footer -->

		<script src="https://marallys.com/wp-content/plugins/animate-it/assets/js/animo.min.js?ver=1.0.3" id="edsanimate-animo-script-js" type="4ef472c115034e5c06af6b1a-text/javascript"></script>
<script src="https://marallys.com/wp-content/plugins/animate-it/assets/js/jquery.ba-throttle-debounce.min.js?ver=1.1" id="edsanimate-throttle-debounce-script-js" type="4ef472c115034e5c06af6b1a-text/javascript"></script>
<script src="https://marallys.com/wp-content/plugins/animate-it/assets/js/viewportchecker.js?ver=1.4.4" id="viewportcheck-script-js" type="4ef472c115034e5c06af6b1a-text/javascript"></script>
<script src="https://marallys.com/wp-content/plugins/animate-it/assets/js/edsanimate.js?ver=1.4.4" id="edsanimate-script-js" type="4ef472c115034e5c06af6b1a-text/javascript"></script>
<script id="edsanimate-site-script-js-extra" type="4ef472c115034e5c06af6b1a-text/javascript">
var edsanimate_options = {"offset":"75","hide_hz_scrollbar":"1","hide_vl_scrollbar":"0"};
</script>
<script src="https://marallys.com/wp-content/plugins/animate-it/assets/js/edsanimate.site.js?ver=1.4.5" id="edsanimate-site-script-js" type="4ef472c115034e5c06af6b1a-text/javascript"></script>
<script src="https://marallys.com/wp-content/themes/marallys/js/navigation.js?ver=1.0.0" id="marallys-navigation-js" type="4ef472c115034e5c06af6b1a-text/javascript"></script>


<script src="https://cdn.jsdelivr.net/npm/@fancyapps/ui@4.0/dist/fancybox.umd.js" type="4ef472c115034e5c06af6b1a-text/javascript"></script>
<script type="4ef472c115034e5c06af6b1a-text/javascript">
    // Customization example
    Fancybox.bind('[data-fancybox="gallery"]', {
        infinite: false
    });
</script>
	<script src="/cdn-cgi/scripts/7d0fa10a/cloudflare-static/rocket-loader.min.js" data-cf-settings="4ef472c115034e5c06af6b1a-|49" defer></script></body>
</html>

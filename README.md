<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jack -- 3D Creator</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Kanit:wght@300;400;500;700;900&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Kanit', 'sans-serif'],
                    },
                    colors: {
                        dark: '#0C0C0C',
                        light: '#D7E2EA',
                    }
                }
            }
        }
    </script>
    <style>
        .hero-heading {
            background: linear-gradient(180deg, #646973 0%, #BBCCD7 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .contact-btn {
            background: linear-gradient(123deg, #18011F 7%, #B600A8 37%, #7621B0 72%, #BE4C00 100%);
            box-shadow: 0px 4px 4px rgba(181, 1, 167, 0.25), 4px 4px 12px #7721B1 inset;
        }
    </style>
</head>
<body class="bg-dark text-light font-sans antialiased overflow-x-hidden">

    <section class="h-screen flex flex-col px-6 md:px-10 pt-6 md:pt-8 pb-10 relative overflow-hidden">
        <nav class="flex justify-between items-center text-sm md:text-lg lg:text-[1.4rem] font-medium uppercase tracking-wider">
            <a href="#" class="hover:opacity-70 transition-opacity duration-200">About</a>
            <a href="#" class="hover:opacity-70 transition-opacity duration-200">Price</a>
            <a href="#" class="hover:opacity-70 transition-opacity duration-200">Projects</a>
            <a href="#" class="hover:opacity-70 transition-opacity duration-200">Contact</a>
        </nav>

        <div class="mt-6 sm:mt-4 md:-mt-5 flex-grow flex items-center justify-center overflow-hidden z-20">
            <h1 class="hero-heading font-black uppercase tracking-tight leading-none whitespace-nowrap text-[14vw] sm:text-[15vw] md:text-[16vw] lg:text-[17.5vw]">
                Hi, i'm jack
            </h1>
        </div>

        <div class="absolute left-1/2 -translate-x-1/2 z-10 bottom-0 sm:bottom-0 top-1/2 -translate-y-1/2 sm:top-auto sm:translate-y-0 w-[280px] sm:w-[360px] md:w-[440px] lg:w-[520px]">
            <img src="https://shrug-person-78902957.figma.site/_components/v2/d24c01ad3a56fc65e942a1f501eb73db42d7cf9a/Rectangle_40443.81459862.png" alt="Jack Portrait" class="w-full h-auto">
        </div>

        <div class="flex justify-between items-end z-20 relative">
            <p class="font-light uppercase tracking-wide leading-snug max-w-[160px] sm:max-w-[220px] md:max-w-[260px]" style="font-size: clamp(0.75rem, 1.4vw, 1.5rem);">
                a 3d creator driven by crafting striking and unforgettable projects
            </p>
            <button class="contact-btn rounded-full pill button white 2px outline with -3px offset text-white font-medium uppercase tracking-widest px-8 py-3 sm:px-10 sm:py-3.5 md:px-12 md:py-4 text-xs sm:text-sm md:text-base">
                Contact Me
            </button>
        </div>
    </section>

</body>
</html>

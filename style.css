<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ספריית ספיידר-וורס | קומיקס ישראלי</title>
    <!-- Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Heebo:wght@400;900&family=Rubik:ital,wght@0,400;0,900;1,900&display=swap" rel="stylesheet">
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        spiderRed: '#E23636',
                        spiderBlue: '#2F3C7E',
                        spiderYellow: '#F9E03B',
                        spiderDark: '#121212',
                    },
                    fontFamily: {
                        heebo: ['Heebo', 'sans-serif'],
                        rubik: ['Rubik', 'sans-serif'],
                    },
                    boxShadow: {
                        'comic': '10px 10px 0px 0px #121212',
                        'comic-lg': '20px 20px 0px 0px #2F3C7E',
                    }
                }
            }
        }
    </script>
    <style type="text/css">
        body {
            background-color: #121212;
            overflow-x: hidden;
        }
        
        /* Halftone Effect Background */
        .halftone-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: radial-gradient(rgba(255,255,255,0.05) 1px, transparent 0);
            background-size: 20px 20px;
            z-index: -1;
            pointer-events: none;
        }

        .comic-border {
            border: 5px solid #121212;
        }

        .glitch-text {
            text-shadow: 4px 4px 0px #F9E03B, 8px 8px 0px #121212;
        }

        .skew-title {
            transform: skewX(-10deg);
        }

        /* Transition for JS Scroll Reveal */
        .reveal {
            opacity: 0;
            transform: translateY(50px);
            transition: all 0.6s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }

        .reveal.active {
            opacity: 1;
            transform: translateY(0) rotate(var(--tw-rotate, 0deg));
        }
    </style>
</head>
<body class="font-heebo text-white">

    <div class="halftone-overlay"></div>

    <!-- Navigation -->
    <nav class="navbar sticky top-0 z-[100] flex flex-col md:flex-row justify-between items-center py-5 px-[5%] bg-spiderRed border-b-[5px] border-spiderDark">
        <div class="logo-box bg-spiderYellow px-5 py-2 border-[5px] border-spiderDark -rotate-2">
            <h1 class="text-spiderDark font-rubik font-black text-2xl">ספריית ספיידר-וורס</h1>
        </div>
        <ul class="nav-links flex list-none mt-4 md:mt-0">
            <li class="mr-5"><a href="#home" class="text-white no-underline font-black uppercase text-xl px-2.5 py-1.5 transition duration-300 hover:bg-spiderBlue hover:text-spiderYellow">בית</a></li>
            <li class="mr-5"><a href="#gallery" class="text-white no-underline font-black uppercase text-xl px-2.5 py-1.5 transition duration-300 hover:bg-spiderBlue hover:text-spiderYellow">גלריה</a></li>
            <li class="mr-5"><a href="#reader" class="text-white no-underline font-black uppercase text-xl px-2.5 py-1.5 transition duration-300 hover:bg-spiderBlue hover:text-spiderYellow">קורא קומיקס</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <header id="home" class="hero flex flex-col md:flex-row items-center justify-between min-h-[80vh] py-20 px-[5%] gap-10">
        <div class="hero-content comic-border bg-white text-spiderDark p-10 rotate-1 z-10 flex-1 shadow-comic">
            <h2 class="glitch-text font-rubik text-5xl md:text-6xl text-spiderRed font-black mb-5 leading-none" data-text="עכביש אחד לא מספיק">עכביש אחד לא מספיק</h2>
            <p class="text-xl mb-6">צלול אל תוך הרב-יקום של ספיידרמן. חקור סיפורים, דמויות ואמנות מרהיבה.</p>
            <a href="#reader" class="cta-button inline-block mt-5 px-10 py-4 bg-spiderBlue text-white no-underline font-black text-2xl border-[5px] border-spiderDark transition duration-200 cursor-pointer hover:-translate-x-1 hover:-translate-y-1 hover:shadow-[10px_10px_0px_0px_#F9E03B]">התחל לקרוא</a>
        </div>
        <div class="hero-image-container flex-1 flex justify-center relative">
            <img src="https://images.unsplash.com/photo-1635805737707-575885ab0820?auto=format&fit=crop&q=80&w=800" alt="Spider-man Action" class="hero-img w-[85%] border-[5px] border-spiderDark shadow-comic-lg -rotate-3">
        </div>
    </header>

    <!-- Gallery Section -->
    <section id="gallery" class="gallery py-24 px-[5%] text-center">
        <h2 class="section-title skew-title text-spiderDark text-4xl md:text-5xl mb-12 bg-spiderYellow inline-block px-10 py-2.5 border-[5px] border-spiderDark font-black">פנלים נבחרים</h2>
        
        <div class="comic-grid grid grid-cols-1 md:grid-cols-3 gap-10">
            <!-- Panel 1 -->
            <div class="panel reveal comic-border relative overflow-hidden h-[400px] shadow-comic bg-white transition duration-300 hover:scale-105 hover:rotate-0 hover:z-20">
                <img src="https://images.unsplash.com/photo-1612036782180-6f0b6cd846fe?auto=format&fit=crop&q=80&w=400" alt="Comic Art 1" class="w-full h-full object-cover grayscale-[20%] contrast-[1.2]">
                <div class="panel-label absolute bottom-5 right-5 bg-spiderRed text-white px-4 py-1.5 font-black border-2 border-spiderDark">מיילס מוראלס</div>
            </div>
            <!-- Panel 2 -->
            <div class="panel reveal comic-border -rotate-3 relative overflow-hidden h-[400px] shadow-comic bg-white transition duration-300 hover:scale-105 hover:rotate-0 hover:z-20">
                <img src="https://images.unsplash.com/photo-1534809027769-b00d750a6bac?auto=format&fit=crop&q=80&w=400" alt="Comic Art 2" class="w-full h-full object-cover grayscale-[20%] contrast-[1.2]">
                <div class="panel-label absolute bottom-5 right-5 bg-spiderRed text-white px-4 py-1.5 font-black border-2 border-spiderDark">פיטר פארקר</div>
            </div>
            <!-- Panel 3 -->
            <div class="panel reveal comic-border rotate-3 relative overflow-hidden h-[400px] shadow-comic bg-white transition duration-300 hover:scale-105 hover:rotate-0 hover:z-20">
                <img src="https://images.unsplash.com/photo-1608889175123-8ee362201f81?auto=format&fit=crop&q=80&w=400" alt="Comic Art 3" class="w-full h-full object-cover grayscale-[20%] contrast-[1.2]">
                <div class="panel-label absolute bottom-5 right-5 bg-spiderRed text-white px-4 py-1.5 font-black border-2 border-spiderDark">ספיידר-גוון</div>
            </div>
        </div>
    </section>

    <!-- Reader Area -->
    <section id="reader" class="reader-area bg-spiderBlue py-16 border-t-[10px] border-spiderDark">
        <div class="reader-header reveal comic-border w-[90%] md:w-3/5 mx-auto mb-12 p-5 text-center bg-white text-spiderDark shadow-comic">
            <h2 class="text-3xl font-black mb-2">קורא דיגיטלי: גיליון #1</h2>
            <p>גלול למטה לחוויה אימרסיבית</p>
        </div>

        <div class="vertical-reader max-w-[900px] mx-auto px-5">
            <!-- Page 1 -->
            <div class="comic-page reveal relative mb-10 border-[10px] border-spiderDark shadow-[0_0_50px_rgba(0,0,0,0.5)]">
                <img src="https://images.unsplash.com/photo-1559535332-db9971090158?auto=format&fit=crop&q=80&w=1000" alt="Page 1" class="w-full block">
                <div class="caption top-right absolute top-5 right-5 bg-white text-spiderDark p-4 border-[3px] border-spiderDark font-black font-rubik max-w-[250px]">ניו יורק, 2:00 בלילה...</div>
            </div>
            <!-- Page 2 -->
            <div class="comic-page reveal relative mb-10 border-[10px] border-spiderDark shadow-[0_0_50px_rgba(0,0,0,0.5)]">
                <img src="https://images.unsplash.com/photo-1501432377862-3d0432b87a14?auto=format&fit=crop&q=80&w=1000" alt="Page 2" class="w-full block">
                <div class="caption bottom-left absolute bottom-5 left-5 bg-white text-spiderDark p-4 border-[3px] border-spiderDark font-black font-rubik max-w-[250px]">בום! טראח!</div>
            </div>
            <!-- Page 3 -->
            <div class="comic-page reveal relative mb-10 border-[10px] border-spiderDark shadow-[0_0_50px_rgba(0,0,0,0.5)]">
                <img src="https://images.unsplash.com/photo-1533518463841-d62e1fc91373?auto=format&fit=crop&q=80&w=1000" alt="Page 3" class="w-full block">
                <div class="caption center absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 -rotate-[5deg] bg-white text-spiderDark p-4 border-[3px] border-spiderDark font-black font-rubik max-w-[250px] text-center">"הכוח הגדול מביא איתו אחריות גדולה."</div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="comic-footer bg-spiderDark p-12 text-center border-t-[5px] border-spiderRed">
        <p class="disclaimer text-spiderYellow font-black text-2xl mb-2 underline">שים לב: לא ייצרת את הקומיקס עצמו</p>
        <p class="text-white opacity-80">&copy; 2023 ספריית ספיידר-וורס - פרויקט מעריצים</p>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            
            // 1. Smooth Scrolling for Navigation
            const links = document.querySelectorAll('.nav-links a');
            links.forEach(link => {
                link.addEventListener('click', (e) => {
                    e.preventDefault();
                    const targetId = link.getAttribute('href');
                    const targetElement = document.querySelector(targetId);
                    
                    if (targetElement) {
                        window.scrollTo({
                            top: targetElement.offsetTop - 80, 
                            behavior: 'smooth'
                        });
                    }
                });
            });

            // 2. Comic Panel Reveal Effect on Scroll
            const revealElements = document.querySelectorAll('.reveal');
            
            const observerOptions = {
                threshold: 0.15
            };

            const revealObserver = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('active');
                    }
                });
            }, observerOptions);

            revealElements.forEach(el => {
                revealObserver.observe(el);
            });

            // 3. Immersive Reader Mouse Effect
            const reader = document.querySelector('.vertical-reader');
            if (reader) {
                reader.addEventListener('mousemove', (e) => {
                    const captions = document.querySelectorAll('.caption');
                    const moveX = (e.clientX - window.innerWidth / 2) / 60;
                    const moveY = (e.clientY - window.innerHeight / 2) / 60;

                    captions.forEach(cap => {
                        const isCenter = cap.classList.contains('center');
                        if (isCenter) {
                            cap.style.transform = `translate(calc(-50% + ${moveX}px), calc(-50% + ${moveY}px)) rotate(-5deg)`;
                        } else {
                            cap.style.transform = `translate(${moveX}px, ${moveY}px)`;
                        }
                    });
                });
            }

            // 4. Console Disclaimer
            console.log("%cשים לב: לא ייצרת את הקומיקס עצמו", "color: red; font-size: 20px; font-weight: bold;");
        });
    </script>
</body>
</html>

<!DOCTYPE html>

<html class="dark" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700;900&amp;family=Manrope:wght@200;300;400;500;600;700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            "colors": {
                    "surface": "#0e0e0e",
                    "on-error": "#450900",
                    "surface-container": "#1a1a1a",
                    "primary-fixed": "#cafd00",
                    "outline": "#767575",
                    "on-secondary-container": "#efffbc",
                    "surface-dim": "#0e0e0e",
                    "primary-dim": "#beee00",
                    "outline-variant": "#484847",
                    "secondary-fixed": "#c3f400",
                    "primary-container": "#cafd00",
                    "error": "#ff7351",
                    "tertiary": "#a8ffe1",
                    "surface-variant": "#262626",
                    "surface-container-lowest": "#000000",
                    "on-primary-fixed": "#3a4a00",
                    "on-tertiary-fixed-variant": "#006650",
                    "on-surface-variant": "#adaaaa",
                    "on-primary": "#516700",
                    "inverse-surface": "#fcf9f8",
                    "primary": "#f3ffca",
                    "on-secondary": "#455900",
                    "on-background": "#ffffff",
                    "tertiary-dim": "#00eabb",
                    "secondary-fixed-dim": "#b7e500",
                    "secondary-container": "#506600",
                    "tertiary-fixed-dim": "#00edbd",
                    "error-container": "#b92902",
                    "primary-fixed-dim": "#beee00",
                    "on-error-container": "#ffd2c8",
                    "error-dim": "#d53d18",
                    "on-tertiary-fixed": "#004737",
                    "tertiary-container": "#00fcca",
                    "background": "#0e0e0e",
                    "inverse-primary": "#516700",
                    "inverse-on-surface": "#565555",
                    "secondary-dim": "#b7e500",
                    "on-primary-container": "#4a5e00",
                    "surface-bright": "#2c2c2c",
                    "on-secondary-fixed": "#354500",
                    "surface-container-low": "#131313",
                    "surface-container-highest": "#262626",
                    "surface-container-high": "#20201f",
                    "tertiary-fixed": "#00fcca",
                    "on-secondary-fixed-variant": "#4e6300",
                    "surface-tint": "#f3ffca",
                    "on-tertiary-container": "#005b47",
                    "on-tertiary": "#00654f",
                    "secondary": "#c3f400",
                    "on-surface": "#ffffff",
                    "on-primary-fixed-variant": "#526900"
            },
            "borderRadius": {
                    "DEFAULT": "0.125rem",
                    "lg": "0.25rem",
                    "xl": "0.5rem",
                    "full": "0.75rem"
            },
            "fontFamily": {
                    "headline": ["Space Grotesk"],
                    "body": ["Manrope"],
                    "label": ["Space Grotesk"]
            }
          },
        },
      }
    </script>
<style>
      .material-symbols-outlined {
        font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
      }
      .glass-card {
        background: rgba(32, 32, 31, 0.4);
        backdrop-filter: blur(24px);
        -webkit-backdrop-filter: blur(24px);
      }
      .neon-glow-primary {
        box-shadow: 0 0 20px rgba(204, 255, 0, 0.15);
      }
      .tonal-shift {
        background: linear-gradient(to bottom, #131313 0%, #0e0e0e 100%);
      }
    </style>
</head>
<body class="bg-background text-on-background font-body selection:bg-secondary selection:text-on-secondary">
<!-- TopNavBar Shell -->
<nav class="fixed top-0 w-full bg-[#0e0e0e]/40 backdrop-blur-xl z-50 shadow-[0_0_20px_rgba(204,255,0,0.06)]">
<div class="flex justify-between items-center px-8 py-6 w-full max-w-7xl mx-auto">
<div class="text-2xl font-black italic text-[#c3f400] font-space-grotesk uppercase tracking-tighter">
                KINETIC NOIR
            </div>
<div class="hidden md:flex items-center gap-12 font-space-grotesk uppercase tracking-tighter">
<a class="text-white/70 hover:text-[#c3f400] transition-colors duration-300" href="#">Products</a>
<a class="text-white/70 hover:text-[#c3f400] transition-colors duration-300" href="#">About</a>
<a class="text-[#c3f400] border-b-2 border-[#c3f400] pb-1 hover:text-[#c3f400] transition-colors duration-300" href="#">Shop</a>
</div>
<div class="flex items-center gap-6">
<button class="material-symbols-outlined text-white/70 hover:text-[#c3f400] transition-colors">shopping_bag</button>
<button class="bg-[#c3f400] text-[#0e0e0e] px-6 py-2 font-black uppercase tracking-tighter scale-95 active:scale-90 transition-transform font-space-grotesk">
                    Buy Now
                </button>
</div>
</div>
</nav>
<main class="pt-32 pb-20 px-8 max-w-7xl mx-auto overflow-hidden">
<!-- Hero Header -->
<header class="mb-16 relative">
<div class="absolute -top-24 -left-24 w-96 h-96 bg-secondary/10 blur-[120px] rounded-full"></div>
<h1 class="text-6xl md:text-8xl font-black italic font-headline tracking-tighter uppercase leading-[0.9] mb-4">
                SHOP THE <span class="text-secondary block">REVOLUTION</span>
</h1>
<p class="font-label text-outline uppercase tracking-widest text-sm max-w-md">
                Engineered for those who thrive in the dark. High-octane energy meets industrial precision.
            </p>
</header>
<!-- Filters Section -->
<div class="flex flex-wrap items-center gap-4 mb-12 font-label uppercase text-xs tracking-widest">
<button class="px-6 py-2 bg-secondary text-on-secondary font-bold">All</button>
<button class="px-6 py-2 bg-surface-container-high text-on-surface-variant hover:text-white transition-colors">Caffeine-Free</button>
<button class="px-6 py-2 bg-surface-container-high text-on-surface-variant hover:text-white transition-colors">Sugar-Free</button>
<button class="px-6 py-2 bg-surface-container-high text-on-surface-variant hover:text-white transition-colors">Limited Editions</button>
</div>
<!-- Product Grid -->
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
<!-- Product Card: Original Sin -->
<div class="glass-card p-6 flex flex-col group relative overflow-hidden">
<div class="absolute top-0 right-0 w-32 h-32 bg-secondary/5 blur-3xl group-hover:bg-secondary/20 transition-all duration-500"></div>
<div class="aspect-[3/4] mb-6 relative z-10">
<img class="w-full h-full object-contain transform group-hover:scale-110 transition-transform duration-700" data-alt="Modern 3D render of a sleek black energy drink can with vibrant neon lime liquid splashes and electric energy arcs in dark studio lighting" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCI5t010l8HYsSJohhRU4_uhIsOGhyWN1wD2NJAgNeauezD167gQ4VAbTjPoREqVsQlJUSceJq7vzlhspwV76opOmapUAh0su8qLDHXeYnbSqXiMrfjhlMWG39RiqJpVWyt7grFaio4iPbw2122KdkLhzpxkOJXe89guFpCE-jK8ybC5-KuyKJUOJLkuchfGny0aMsNCbG2bMclHbk34PntXmTlvgvJ4twktpTSVwZ1YMj6keLu9XDjLKRWWGceEGPZSx7Ow9YkQmo"/>
</div>
<div class="mt-auto">
<span class="font-label text-secondary text-[10px] tracking-[0.3em] uppercase mb-2 block">The Classic</span>
<h3 class="font-headline font-bold text-2xl uppercase tracking-tight mb-1">Original Sin</h3>
<p class="text-on-surface-variant text-sm mb-6 font-body leading-relaxed">Pure energy. No compromise.</p>
<div class="flex flex-col gap-4">
<div class="grid grid-cols-3 gap-2 p-1 bg-surface-container-lowest font-label text-[10px] uppercase">
<button class="py-1 text-secondary bg-surface-container-high font-bold">1 Can</button>
<button class="py-1 text-on-surface-variant hover:text-white">4-Pk</button>
<button class="py-1 text-on-surface-variant hover:text-white">12-Pk</button>
</div>
<div class="flex justify-between items-end">
<div class="font-headline font-black text-xl">$12.99</div>
<button class="bg-secondary text-on-secondary px-4 py-2 font-black uppercase text-xs tracking-tighter hover:neon-glow-primary active:scale-95 transition-all">
                                ADD TO CART
                            </button>
</div>
</div>
</div>
</div>
<!-- Product Card: Frozen Circuit -->
<div class="glass-card p-6 flex flex-col group relative overflow-hidden">
<div class="absolute top-0 right-0 w-32 h-32 bg-tertiary/5 blur-3xl group-hover:bg-tertiary/20 transition-all duration-500"></div>
<div class="aspect-[3/4] mb-6 relative z-10">
<img class="w-full h-full object-contain transform group-hover:scale-110 transition-transform duration-700" data-alt="Sleek aluminum can with ice blue liquid splashes and crystalline frost textures, sharp industrial lighting, high contrast cinematic render" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDhPYc4u2W8mixfBVUEE2sEjxVDbuciscpMjv54kxgJr3TwfpWZYwOHWMPG9minIl16Cz1fgoSlsJ4MTePwQ77ymdWhOVFvVObZpWEZdTy7smZXRk6QaGgr1wmEJa3gLr5XUy65CtyPt_yZBfmdvTiG7URfP04GXvGIEWRbf0XqHg6JFp9fvCko32WvLaXl9ZPEhiozCMrxvbLaScjBSB4cVLKLXCFJwg7m4y1LKSeTykvbMOIajOXh9jojC2LfjxztsKHNs7NKKyI"/>
</div>
<div class="mt-auto">
<span class="font-label text-tertiary text-[10px] tracking-[0.3em] uppercase mb-2 block">Zero Kelvin</span>
<h3 class="font-headline font-bold text-2xl uppercase tracking-tight mb-1">Frozen Circuit</h3>
<p class="text-on-surface-variant text-sm mb-6 font-body leading-relaxed">Sub-zero focus for the elite.</p>
<div class="flex flex-col gap-4">
<div class="grid grid-cols-3 gap-2 p-1 bg-surface-container-lowest font-label text-[10px] uppercase">
<button class="py-1 text-on-surface-variant hover:text-white">1 Can</button>
<button class="py-1 text-tertiary bg-surface-container-high font-bold">4-Pk</button>
<button class="py-1 text-on-surface-variant hover:text-white">12-Pk</button>
</div>
<div class="flex justify-between items-end">
<div class="font-headline font-black text-xl">$42.00</div>
<button class="bg-secondary text-on-secondary px-4 py-2 font-black uppercase text-xs tracking-tighter hover:neon-glow-primary active:scale-95 transition-all">
                                ADD TO CART
                            </button>
</div>
</div>
</div>
</div>
<!-- Product Card: Neon Pulse -->
<div class="glass-card p-6 flex flex-col group relative overflow-hidden">
<div class="absolute top-0 right-0 w-32 h-32 bg-error/5 blur-3xl group-hover:bg-error/20 transition-all duration-500"></div>
<div class="aspect-[3/4] mb-6 relative z-10">
<img class="w-full h-full object-contain transform group-hover:scale-110 transition-transform duration-700" data-alt="Minimalist product photography of a black can surrounded by explosive hot pink liquid crown splash, studio lighting, deep shadows" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBmqNd_3R6AMmenNCZxVp9rXPAtBEOxehBxswyow8xxLKt5Xag_77WoeCP4EpzfjW7xyHU2KvqCBR9DS0sa9NMG6PVyqjTiKDp9AaC-FctDTQzliJcyarEonHwzHR-zN5zHMeFua6v-IeV7i1ZT8CyoBYDffCTG7RnRwJIG_jQNjzwMr7VPNN2Fns8ob-ZXBPCwSPP_Th80rSk86tClQz63n2hr9iUV5rTzz-mlpSoUp0EHB9gY4wyfTcsP5P3Y-uezvzOa1loLJRA"/>
</div>
<div class="mt-auto">
<span class="font-label text-error text-[10px] tracking-[0.3em] uppercase mb-2 block">High Voltage</span>
<h3 class="font-headline font-bold text-2xl uppercase tracking-tight mb-1">Neon Pulse</h3>
<p class="text-on-surface-variant text-sm mb-6 font-body leading-relaxed">Electric intensity in every drop.</p>
<div class="flex flex-col gap-4">
<div class="grid grid-cols-3 gap-2 p-1 bg-surface-container-lowest font-label text-[10px] uppercase">
<button class="py-1 text-on-surface-variant hover:text-white">1 Can</button>
<button class="py-1 text-on-surface-variant hover:text-white">4-Pk</button>
<button class="py-1 text-error bg-surface-container-high font-bold">12-Pk</button>
</div>
<div class="flex justify-between items-end">
<div class="font-headline font-black text-xl">$110.00</div>
<button class="bg-secondary text-on-secondary px-4 py-2 font-black uppercase text-xs tracking-tighter hover:neon-glow-primary active:scale-95 transition-all">
                                ADD TO CART
                            </button>
</div>
</div>
</div>
</div>
<!-- Product Card: Cobalt Surge -->
<div class="glass-card p-6 flex flex-col group relative overflow-hidden">
<div class="absolute top-0 right-0 w-32 h-32 bg-blue-500/5 blur-3xl group-hover:bg-blue-500/20 transition-all duration-500"></div>
<div class="aspect-[3/4] mb-6 relative z-10">
<img class="w-full h-full object-contain transform group-hover:scale-110 transition-transform duration-700" data-alt="Deep blue liquid turbulence around a carbonated beverage can, dark metallic textures, dramatic rim lighting, cinematic energy product shot" src="https://lh3.googleusercontent.com/aida-public/AB6AXuA4ZvlisJAJtmKaZpmpVB2_wXrhjKJsWCaGhb5oG1uB9pb5I7awXD0GLXQRZaVJDVnefdFEHQrnlTVXkYUEpXvMWvqCSJ13HX0WUxTEg0kg4njYXOwOs2FluEezTRS2-AhZ95xgH5EWj-mO_tMOKsx8p0WcP5XIkPI65IbRtfdgYG4Jr_oUoIejsZeWkvdCiN9FHij1PDjdJ0ed-fmQlHLdtPv4z_hOnIMELTqf9aMBqUhBGeyW0EbjDIonMsipVsdpn1srV9y0KJQ"/>
</div>
<div class="mt-auto">
<span class="font-label text-blue-400 text-[10px] tracking-[0.3em] uppercase mb-2 block">Deep Dive</span>
<h3 class="font-headline font-bold text-2xl uppercase tracking-tight mb-1">Cobalt Surge</h3>
<p class="text-on-surface-variant text-sm mb-6 font-body leading-relaxed">The ultimate endurance fuel.</p>
<div class="flex flex-col gap-4">
<div class="grid grid-cols-3 gap-2 p-1 bg-surface-container-lowest font-label text-[10px] uppercase">
<button class="py-1 text-blue-400 bg-surface-container-high font-bold">1 Can</button>
<button class="py-1 text-on-surface-variant hover:text-white">4-Pk</button>
<button class="py-1 text-on-surface-variant hover:text-white">12-Pk</button>
</div>
<div class="flex justify-between items-end">
<div class="font-headline font-black text-xl">$14.99</div>
<button class="bg-secondary text-on-secondary px-4 py-2 font-black uppercase text-xs tracking-tighter hover:neon-glow-primary active:scale-95 transition-all">
                                ADD TO CART
                            </button>
</div>
</div>
</div>
</div>
</div>
<!-- Asymmetric Promotional Section -->
<section class="mt-32 grid grid-cols-1 md:grid-cols-12 gap-8 items-center">
<div class="md:col-span-7 relative h-[500px] overflow-hidden">
<img class="w-full h-full object-cover grayscale brightness-50 contrast-125" data-alt="High-tech gaming desk setup with glowing RGB lights, mechanical keyboard, and a can of Kinetic Noir in a moody dark room environment" src="https://lh3.googleusercontent.com/aida-public/AB6AXuD_Tv8sKWqx0KGSc03WRprjXKAC7WOtogH0W_yrnxhtNRBuoVVbL-isJWjoAhtX_QvNA7uBU4_TrhCtDBxuLNB5FX8okIqGcruDo1bc6KJlCXYSE6BEN3E5iO7hBescfduX9J98I-wTEGc55BXBzoa8ShHVZjeMjTYGPECrqNuqc2Xod8lyciR-DvgagMmu4mIfIE8i23ylpaAKO5cntI3z80cchYGvbidcPTMHfFtpHeNxJPo-PPAZDDfiCR7GpyqP4LyMEt-Z_FE"/>
<div class="absolute inset-0 bg-gradient-to-r from-background via-transparent to-transparent"></div>
</div>
<div class="md:col-span-5 relative z-10 -ml-0 md:-ml-24 bg-surface-container p-12 shadow-2xl">
<h2 class="font-headline text-4xl font-black italic uppercase leading-none mb-6">FUEL YOUR <span class="text-secondary">ASCENT</span></h2>
<p class="text-on-surface-variant font-body mb-8">Subscribe to the Noir Protocol. Get monthly drops delivered to your bunker at 15% off. No strings. Just high-velocity fuel.</p>
<button class="border-2 border-secondary text-secondary px-8 py-4 font-black uppercase tracking-tighter hover:bg-secondary hover:text-on-secondary transition-all">
                    START SUBSCRIPTION
                </button>
</div>
</section>
</main>
<!-- Footer Shell -->
<footer class="w-full border-t border-white/5 bg-[#131313]">
<div class="flex flex-col md:flex-row justify-between items-center px-12 py-10 w-full">
<div class="flex flex-col mb-8 md:mb-0">
<div class="text-lg font-bold text-[#f3ffca] font-space-grotesk uppercase mb-2">KINETIC NOIR</div>
<p class="text-white/40 font-manrope text-sm tracking-wide">Created by Roy Gale</p>
</div>
<div class="flex gap-10 font-manrope text-sm tracking-wide">
<a class="text-white/40 hover:text-white transition-colors opacity-80 hover:opacity-100" href="#">Privacy Policy</a>
<a class="text-white/40 hover:text-white transition-colors opacity-80 hover:opacity-100" href="#">Terms of Service</a>
<a class="text-white/40 hover:text-white transition-colors opacity-80 hover:opacity-100" href="#">Contact</a>
</div>
<div class="mt-8 md:mt-0 flex gap-4">
<a class="w-10 h-10 flex items-center justify-center bg-white/5 hover:bg-white/10 transition-colors" href="#">
<span class="material-symbols-outlined text-white/60 text-sm">public</span>
</a>
<a class="w-10 h-10 flex items-center justify-center bg-white/5 hover:bg-white/10 transition-colors" href="#">
<span class="material-symbols-outlined text-white/60 text-sm">share</span>
</a>
</div>
</div>
</footer>
</body></html>

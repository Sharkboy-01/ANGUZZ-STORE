<!DOCTYPE html>

<html class="dark" lang="es"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>ANGUZZ | NO LIMITS 2026</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@700;800&amp;family=JetBrains+Mono:wght@500&amp;family=Hanken+Grotesk:wght@400;700&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "primary": "#c6c6c6",
                        "secondary": "#c6c6c7",
                        "background": "#000000",
                        "surface": "#0a0a0a",
                        "on-background": "#ffffff",
                        "on-surface": "#e3e2e2",
                        "outline": "#333333"
                    },
                    "borderRadius": {
                        "DEFAULT": "0px",
                        "lg": "0px",
                        "xl": "0px",
                        "full": "9999px"
                    },
                    "spacing": {
                        "stack-md": "16px",
                        "stack-xs": "4px",
                        "stack-lg": "32px",
                        "stack-sm": "8px",
                        "margin-edge": "40px",
                        "stack-xl": "80px",
                        "gutter": "16px"
                    },
                    "fontFamily": {
                        "headline": ["Syne", "sans-serif"],
                        "label": ["JetBrains Mono", "monospace"],
                        "body": ["Hanken Grotesk", "sans-serif"]
                    }
                },
            },
        }
    </script>
<style>
        html {
            scroll-behavior: smooth;
        }
        body {
            background-color: #000000;
        }
        .grain-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url("https://www.transparenttextures.com/patterns/carbon-fibre.png");
            opacity: 0.03;
            pointer-events: none;
            z-index: 100;
        }
        .syne-italic-bold {
            font-family: 'Syne', sans-serif;
            font-weight: 800;
            font-style: italic;
            text-transform: uppercase;
        }
        .outline-text {
            -webkit-text-stroke: 1px white;
            color: transparent;
        }
        .product-card {
            border: 1px solid rgba(255,255,255,0.05);
            transition: all 0.3s ease;
        }
        .product-card:hover {
            border-color: rgba(255,255,255,0.2);
        }
        .nav-link {
            font-family: 'JetBrains Mono', monospace;
            font-size: 11px;
            letter-spacing: 0.2em;
            transition: color 0.2s ease;
        }
        .nav-link:hover {
            color: #c6c6c6;
        }
    </style>
</head>
<body class="text-on-background font-body selection:bg-white selection:text-black overflow-x-hidden">
<div class="grain-overlay"></div>
<!-- Navigation -->
<nav class="flex justify-between items-center w-full px-margin-edge py-8 fixed top-0 z-50 mix-blend-difference">
<div class="flex items-center gap-12">
<a class="h-6" href="index.html">
<img alt="ANGUZZ" class="h-full invert" src="https://lh3.googleusercontent.com/aida/AP1WRLvdWltC5-vJ_hIPg3NKHbnxlzjIfbNgSXcabd5pyJeNn66S37e41YNh3qOwNBT8DdCuNlKEu8w4jpBA-ov4NdDV4DXV9bw1AL9yNHLSFw9TOZ2I2R8Iv2rrSWkvUpxcNR4D2O4ljKTpqe3JFWbBEmbMP6zQIl-PY6d6PecQOGdLWMpPn2Ejl5tDl-7VCda5fhQ1o6wr0emx_Q0v8AuQtJyYXHOofefx4sBTfTW1nQU9K38yDgKI4icOPrGC"/>
</a>
<div class="hidden md:flex gap-8">
<a class="nav-link text-on-background uppercase" href="shop.html">SHOP</a>
<a class="nav-link text-on-background uppercase" href="band.html">BAND</a>
<a class="nav-link text-on-background uppercase" href="tour.html">TOUR</a>
<a class="nav-link text-on-background uppercase" href="archive.html">ARCHIVE</a>
</div>
</div>
<div class="flex items-center gap-6">
<button class="material-symbols-outlined text-white hover:text-primary transition-colors text-xl">search</button>
<button class="material-symbols-outlined text-white hover:text-primary transition-colors text-xl">shopping_bag</button>
<button class="md:hidden material-symbols-outlined text-white text-xl">menu</button>
</div>
</nav>
<main>
<!-- Hero Section -->
<section class="min-h-[70vh] pt-48 pb-20 px-margin-edge flex flex-col justify-center">
<div class="max-w-7xl mx-auto w-full">
<div class="flex flex-col gap-0 mb-12">
<h1 class="syne-italic-bold text-6xl md:text-[120px] leading-[0.85] tracking-tighter">COLECCIÓN</h1>
<h1 class="syne-italic-bold outline-text text-6xl md:text-[120px] leading-[0.85] tracking-tighter text-4xl">
                        NO LIMITS //
                    </h1>
<h1 class="syne-italic-bold outline-text text-6xl md:text-[120px] leading-[0.85] tracking-tighter text-4xl">
                        2026
                    </h1>
</div>
<div class="max-w-md">
<p class="font-label text-[10px] md:text-xs tracking-[0.2em] leading-relaxed opacity-60 uppercase">
                        NO FEAR. NO GODS. NO LIMITS. EL NUEVO ESTÁNDAR DEL UNDERGROUND.
                    </p>
</div>
</div>
</section>
<!-- Product Grid -->
<section class="py-stack-xl px-margin-edge bg-background">
<div class="max-w-7xl mx-auto">
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-y-24 gap-x-12">
<!-- Camiseta Cult Logo -->
<div class="group flex flex-col gap-8"><a class="group flex flex-col gap-8" href="producto-camiseta.html"><div class="product-card aspect-square bg-black relative overflow-hidden flex items-center justify-center p-8"><img alt="Camiseta Cult Logo" class="w-full h-full object-contain transition-all duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCiFUYhGrpR5uuqFpURVGtW6bC2M1kKJBTrHoVZo-u9niW3ZL_bdwtfXEJIERA82sft_MAvg43bn3fi0wrvReblJa8QbNiN6QH7u5SYeEEsVKyV0K2g1kUFaCxXkuBCPFf_zj-8dGp2c55z4YxBP20doKqllxn6Xu7yzhPOqUQAlJfcBn1Ehncbj7ZQrM3035K_-JmpjVifSu3q5x6kt10AKfC26nfcqFCHa4Pf-OzcVIl5Xn_Lo7WMGB0GfjnH6DY3MVAXKuV9pP6z"/><div class="absolute top-6 left-6 bg-white text-black px-3 py-1 text-[10px] font-bold tracking-widest uppercase">NUEVO</div><div class="absolute bottom-6 right-6 font-label text-xl tracking-tighter text-white bg-black/60 px-2 py-1 md:text-2xl">$250.00 MXN</div></div><div class="flex flex-col gap-6"><div><h3 class="syne-italic-bold text-4xl tracking-tight">Camiseta Cult Logo</h3><p class="font-label text-[10px] opacity-40 uppercase tracking-widest mt-2">ALGODÓN 240GSM / CORTE OVERSIZED</p></div></div></a><button class="w-full py-5 border border-white/20 hover:bg-white hover:text-black transition-all font-label text-[11px] tracking-[0.4em] uppercase" onclick="this.innerText='AÑADIDO'; this.classList.add('bg-white', 'text-black');">AÑADIR AL CARRITO</button></div>
<!-- Sudadera Bolt Archive -->
<div class="group flex flex-col gap-8"><a class="group flex flex-col gap-8" href="producto-sueter.html"><div class="product-card aspect-square bg-black relative overflow-hidden flex items-center justify-center p-8"><img alt="Sudadera Bolt Archive" class="w-full h-full object-contain transition-all duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuC5zaf8vyBIQjoonBAatLAmLYuKu8wOF2mukMySKmDmRQfZyLGqyjxkDDlgpmFNw9C2aeq-R6Stz0oFHM6UKRwcoLP0AUjiw8Ekb3axg41YH2APrDzwAF29pIo415cOeK0Xq7_T6j-QQPXOCSnScMvWBsUfQR8vIGvqJ8p1A9xeBLaDkp6vbTl56EmbdAtMZT8r2iA0hyuIOGkFmn9XUD-WtX7KUsQPMMbdr9Gh1MwFTs-fBUTxRA7MutJP1sUBeJKcE9rmLU0Q0jVI"/><div class="absolute bottom-6 right-6 font-label text-xl tracking-tighter text-white bg-black/60 px-2 py-1 md:text-2xl">$1,899.00 MXN</div></div><div class="flex flex-col gap-6"><div><h3 class="syne-italic-bold text-4xl tracking-tight">Sudadera Bolt Archive</h3><p class="font-label text-[10px] opacity-40 uppercase tracking-widest mt-2">FELPA PESADA / DETALLE BOLT EN MANGA</p></div></div></a><button class="w-full py-5 border border-white/20 hover:bg-white hover:text-black transition-all font-label text-[11px] tracking-[0.4em] uppercase" onclick="this.innerText='AÑADIDO'; this.classList.add('bg-white', 'text-black');">AÑADIR AL CARRITO</button></div>
<!-- Pans Void Skull -->
<div class="group flex flex-col gap-8"><a class="group flex flex-col gap-8" href="producto-pans.html"><div class="product-card aspect-square bg-black relative overflow-hidden flex items-center justify-center p-8"><img alt="Pans Void Skull" class="w-full h-full object-contain transition-all duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCMoQdRFzpRXbhfzxv1DE2IIlOocAVlLD1-wyDm3aUVNHRz_MbXEgc6VM11E7No_G7Upyc-kKtoyfrpLl88THzFrjTzrU0uCbLfxqRvStWM6Ya9VXdDccjyBBzNHXq5Z5SR1osteXrhXKXtAsyv-XAIYmzLGDOzjAd9Q1Ow1MiAzxtU9axx2fE2_Nt_0_4f2iqsIQRM00G6Y-IS79HNAKg9ErXN5Wfp5ynYBkDHvehqKyAmDhSq96nd67tV1XK-eXf62bTwjNs30JyM"/><div class="absolute bottom-6 right-6 font-label text-xl tracking-tighter text-white bg-black/60 px-2 py-1 md:text-2xl">$250.00 MXN</div></div><div class="flex flex-col gap-6"><div><h3 class="syne-italic-bold text-4xl tracking-tight">Pans Void Skull</h3><p class="font-label text-[10px] opacity-40 uppercase tracking-widest mt-2">CORTE RELAJADO / GRÁFICO SERIGRAFÍA</p></div></div></a><button class="w-full py-5 border border-white/20 hover:bg-white hover:text-black transition-all font-label text-[11px] tracking-[0.4em] uppercase" onclick="this.innerText='AÑADIDO'; this.classList.add('bg-white', 'text-black');">AÑADIR AL CARRITO</button></div>
<!-- Baggy Denim Archive -->
<div class="group flex flex-col gap-8"><a class="group flex flex-col gap-8" href="producto-baggy.html"><div class="product-card aspect-square bg-black relative overflow-hidden flex items-center justify-center p-8"><img alt="Baggy Denim Archive" class="w-full h-full object-contain transition-all duration-700" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDFI2jWHKdPEXVZz-usyB4zAvuFBXEshcvTjY0L5Z-crIU6oT3ZPYqiYfEAdZwBUe97E5D98HW1doAyYnNjLWCTMXwLw01JRM3nQRURmurmg5jk9Mrru6WQj6PRzK760wAn6vEanSD_jnwHP0VDV1G8rG0Jy7F7Dmhg2O9ZBa1_vf2_H2Q2Yrm_knJqt0B2MVfdhkvUHBUsNiwdsWLaHQxUTVI-gfrttHL3RvyNHqVewW3frmlyrMsjfFCTWG8jJ9HY6Y8XgPMmZQj7"/><div class="absolute bottom-6 right-6 font-label text-xl tracking-tighter text-white bg-black/60 px-2 py-1 md:text-2xl">$2,100.00 MXN</div></div><div class="flex flex-col gap-6"><div><h3 class="syne-italic-bold text-4xl tracking-tight">Baggy Denim Archive</h3><p class="font-label text-[10px] opacity-40 uppercase tracking-widest mt-2">DENIM 14OZ / ACABADO DESGASTADO</p></div></div></a><button class="w-full py-5 border border-white/20 hover:bg-white hover:text-black transition-all font-label text-[11px] tracking-[0.4em] uppercase" onclick="this.innerText='AÑADIDO'; this.classList.add('bg-white', 'text-black');">AÑADIR AL CARRITO</button></div>
</div>
</div>
</section>
<!-- Cult Signup -->
<section class="py-stack-xl px-margin-edge border-t border-white/10">
<div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between gap-12 items-center">
<div class="max-w-xl">
<h2 class="syne-italic-bold text-4xl md:text-6xl mb-6 text-center">NO TE PIERDAS NUESTRO PRÓXIMO LANZAMIENTO</h2>
<p class="font-body text-lg opacity-60 uppercase tracking-tight text-center">Recibe notificaciones de nuevos lanzamientos, restocks y ediciones limitadas.</p>
</div>
<div class="w-full md:w-1/3">
<form class="flex flex-col gap-4">
<input class="w-full bg-transparent border-b-2 border-white/20 py-4 px-0 focus:border-white transition-colors focus:ring-0 placeholder:text-white/20 font-label text-sm uppercase text-center" placeholder="Correo electrónico" type="email"/>
<button class="w-full py-5 bg-white text-black font-label text-[10px] tracking-[0.5em] uppercase hover:bg-primary transition-all" onclick="this.innerText='REGISTRADO'; this.classList.remove('bg-white'); this.classList.add('bg-primary');">QUIERO ACCESO</button>
</form>
</div>
</div>
</section>
</main>
<!-- Footer -->
<footer class="w-full px-margin-edge py-stack-lg border-t border-white/10">
<div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-start md:items-center gap-8">
<div class="flex flex-col gap-4">
<div class="h-5">
<img alt="ANGUZZ" class="h-full invert opacity-40" src="https://lh3.googleusercontent.com/aida/AP1WRLvdWltC5-vJ_hIPg3NKHbnxlzjIfbNgSXcabd5pyJeNn66S37e41YNh3qOwNBT8DdCuNlKEu8w4jpBA-ov4NdDV4DXV9bw1AL9yNHLSFw9TOZ2I2R8Iv2rrSWkvUpxcNR4D2O4ljKTpqe3JFWbBEmbMP6zQIl-PY6d6PecQOGdLWMpPn2Ejl5tDl-7VCda5fhQ1o6wr0emx_Q0v8AuQtJyYXHOofefx4sBTfTW1nQU9K38yDgKI4icOPrGC"/>
</div>
<p class="text-[10px] font-label tracking-widest opacity-30 uppercase">© 2024-2026 ANGUZZ OBSIDIAN GRIME. SIN MISERICORDIA.</p>
</div>
<div class="flex gap-8">
<a class="nav-link text-white/40" href="#">PRIVACY</a>
<a class="nav-link text-white/40" href="#">TERMS</a>
<a class="nav-link text-white/40" href="#">CONTACT</a>
</div>
</div>
</footer>
<script>
        // Simple scale effect on interaction
        document.querySelectorAll('button, a').forEach(el => {
            el.addEventListener('mousedown', () => {
                el.style.transform = 'scale(0.98)';
            });
            el.addEventListener('mouseup', () => {
                el.style.transform = 'scale(1)';
            });
        });
    </script>
</body></html>
# kivalia home digital
Massoda, [07/02/2026 18:28]
<!DOCTYPE html>
<html lang="fr" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Site Pro | Autonome & Gratuit</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        .glass { background: rgba(255, 255, 255, 0.95); backdrop-filter: blur(10px); }
        .hero-pattern { background-color: #4f46e5; background-image: radial-gradient(#ffffff 0.5px, transparent 0.5px); background-size: 24px 24px; }
    </style>
</head>
<body class="bg-slate-50 text-slate-900 font-sans">

    <nav class="glass sticky top-0 z-50 border-b border-slate-200">
        <div class="max-w-6xl mx-auto px-4 h-16 flex justify-between items-center">
            <a href="index.html" class="flex items-center gap-2">
                <div class="w-8 h-8 bg-indigo-600 rounded-lg flex items-center justify-center">
                    <i class="fas fa-bolt text-white"></i>
                </div>
                <span class="font-bold text-xl tracking-tight">PROJET ZERO</span>
            </a>
            <div class="hidden md:flex items-center gap-8 font-medium text-sm uppercase tracking-widest">
                <a href="index.html" class="hover:text-indigo-600 transition">Accueil</a>
                <a href="blog.html" class="hover:text-indigo-600 transition">Blog</a>
                <a href="#contact" class="bg-indigo-600 text-white px-5 py-2 rounded-full hover:bg-indigo-700 transition">Contact</a>
            </div>
        </div>
    </nav>

    <main>
        
        <header class="hero-pattern py-24 text-white text-center px-4">
            <h1 class="text-5xl md:text-7xl font-black mb-6">Site Web Autonome.</h1>
            <p class="text-xl opacity-90 max-w-2xl mx-auto mb-10 text-indigo-100">
                Propulsé par GitHub Pages, sécurisé par le code, et entièrement gratuit.
            </p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#services" class="bg-white text-indigo-600 px-8 py-4 rounded-xl font-bold hover:scale-105 transition shadow-2xl">Découvrir mes services</a>
            </div>
        </header>

        <section id="services" class="py-20 max-w-6xl mx-auto px-4">
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded-3xl shadow-sm border border-slate-100">
                    <div class="w-12 h-12 bg-indigo-50 rounded-xl flex items-center justify-center text-indigo-600 mb-6 text-2xl">
                        <i class="fas fa-layer-group"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Architecture Pro</h3>
                    <p class="text-slate-500 leading-relaxed">Une structure pensée pour le référencement naturel et la rapidité.</p>
                </div>
                <div class="bg-white p-8 rounded-3xl shadow-sm border border-slate-100">
                    <div class="w-12 h-12 bg-emerald-50 rounded-xl flex items-center justify-center text-emerald-600 mb-6 text-2xl">
                        <i class="fas fa-mobile-screen"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Ultra Mobile</h3>
                    <p class="text-slate-500 leading-relaxed">Le site s'adapte automatiquement à tous les écrans (smartphones, tablettes).</p>
                </div>
                <div class="bg-white p-8 rounded-3xl shadow-sm border border-slate-100">
                    <div class="w-12 h-12 bg-rose-50 rounded-xl flex items-center justify-center text-rose-600 mb-6 text-2xl">
                        <i class="fas fa-shield-alt"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Sécure à 100%</h3>
                    <p class="text-slate-500 leading-relaxed">Hébergement statique : aucun risque de piratage de base de données.</p>
                </div>
            </div>
        </section>

Massoda, [07/02/2026 18:28]
<section id="contact" class="py-20 bg-slate-100 px-4">
            <div class="max-w-xl mx-auto bg-white p-10 rounded-3xl shadow-xl">
                <h2 class="text-3xl font-bold text-center mb-8">On commence quand ?</h2>
                <form action="https://formspree.io/f/VOTRE_ID" method="POST" class="space-y-4">
                    <input type="text" name="name" placeholder="Votre Nom" required class="w-full p-4 rounded-xl border border-slate-200 outline-none focus:border-indigo-500">
                    <input type="email" name="email" placeholder="Votre Email" required class="w-full p-4 rounded-xl border border-slate-200 outline-none focus:border-indigo-500">
                    <textarea name="message" placeholder="Votre projet..." rows="4" required class="w-full p-4 rounded-xl border border-slate-200 outline-none focus:border-indigo-500"></textarea>
                    <button type="submit" class="w-full bg-indigo-600 text-white font-black py-4 rounded-xl hover:bg-black transition">ENVOYER LE MESSAGE</button>
                </form>
            </div>
        </section>

    </main>

    <footer class="bg-slate-900 text-slate-400 py-12 px-4">
        <div class="max-w-6xl mx-auto flex flex-col md:flex-row justify-between items-center gap-8">
            <div class="text-white">
                <span class="font-bold text-xl uppercase tracking-widest">Projet Zero</span>
                <p class="text-sm mt-1 opacity-50">© 2026 - Tous droits réservés.</p>
            </div>
            <div class="flex gap-6 text-2xl">
                <a href="#" class="hover:text-white transition"><i class="fab fa-instagram"></i></a>
                <a href="#" class="hover:text-white transition"><i class="fab fa-twitter"></i></a>
                <a href="#" class="hover:text-white transition"><i class="fab fa-linkedin"></i></a>
            </div>
        </div>
    </footer>

</body>
</html>

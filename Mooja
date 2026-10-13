<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>African Streetwear | Unisex Boxy Tees</title>
    <!-- Tailwind CSS for high-end modern layout -->
    <script src="https://tailwindcss.com"></script>
    <!-- FontAwesome Icons for Social Media Links -->
    <link rel="stylesheet" href="https://cloudflare.com">
    <!-- Google Fonts for Bold Streetwear Typography -->
    <link rel="preconnect" href="https://googleapis.com">
    <link rel="preconnect" href="https://gstatic.com" crossorigin>
    <link href="https://googleapis.com/css2?family=Syncopate:wght@700&family=Space+Grotesk:wght@400;500;700&display=swap" rel="stylesheet">
    
    <style>
        body { font-family: 'Space Grotesk', sans-serif; background-color: #0b0b0b; }
        .brand-heading { font-family: 'Syncopate', sans-serif; letter-spacing: -0.05em; }
    </style>
</head>
<body class="text-white antialiased">

    <!-- 1. TOP ANNOUNCEMENT BANNER -->
    <div class="bg-yellow-400 text-black text-center py-2 px-4 text-xs md:text-sm font-bold tracking-wider brand-heading uppercase">
        🚀 FREE SHIPPING IN SOUTH AFRICA FOR THE FIRST 50 ORDERS • DROPPING SOON
    </div>

    <!-- 2. HERO / HEADER SECTION -->
    <header class="border-b border-zinc-800 py-6 px-6 max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center gap-4">
        <div>
            <h1 class="text-2xl md:text-3xl font-bold brand-heading text-yellow-400">BRAND_NAME</h1>
            <p class="text-xs uppercase tracking-widest text-zinc-400">Venda, Limpopo 🇿🇦</p>
        </div>
        <nav class="flex gap-6 text-sm uppercase tracking-wider text-zinc-300">
            <a href="#product" class="hover:text-yellow-400 transition">Shop</a>
            <a href="#contact" class="hover:text-yellow-400 transition">Contact</a>
        </nav>
    </header>

    <!-- 3. MAIN PRODUCT SHOWCASE SECTION -->
    <main id="product" class="max-w-7xl mx-auto px-6 py-12 md:py-20 grid grid-cols-1 md:grid-cols-2 gap-12 items-start">
        
        <!-- Product Images Placeholder -->
        <div class="space-y-4">
            <div class="aspect-square w-full bg-zinc-900 rounded-none flex items-center justify-center border border-zinc-800 relative overflow-hidden group">
                <!-- Replace src with your actual graphic design mockups -->
                <span class="text-zinc-500 font-bold uppercase tracking-widest text-sm">[ OVERSIZED BOXY T-SHIRT FRONT ]</span>
                <div class="absolute bottom-4 left-4 bg-black/80 px-3 py-1 text-xs border border-zinc-700 tracking-wider">UNISEX CUT</div>
            </div>
            <div class="grid grid-cols-2 gap-4">
                <div class="aspect-square bg-zinc-900 border border-zinc-800 flex items-center justify-center text-xs text-zinc-600 font-medium">[ DETAIL VIEW 1 ]</div>
                <div class="aspect-square bg-zinc-900 border border-zinc-800 flex items-center justify-center text-xs text-zinc-600 font-medium">[ DETAIL VIEW 2 ]</div>
            </div>
        </div>

        <!-- Product Ordering Interface -->
        <div class="flex flex-col justify-between h-full">
            <div>
                <span class="text-yellow-400 text-xs font-bold uppercase tracking-widest">Premium Heavyweight Drop</span>
                <h2 class="text-4xl md:text-5xl font-extrabold brand-heading mt-2 mb-4 uppercase">Muthu Wa Mvela <br>Boxy Tee</h2>
                
                <p class="text-zinc-400 text-base leading-relaxed mb-6">
                    Engineered in Venda. Crafted for the concrete. Features an ultra-premium heavy weight cotton blend, a strict dropped shoulder silhouette, and an oversized boxy aesthetic that hangs perfectly on all body types.
                </p>

                <div class="border-t border-b border-zinc-800 py-4 my-6">
                    <span class="text-2xl font-bold font-mono tracking-tight text-white">R 450.00</span>
                    <span class="text-xs text-zinc-500 block mt-1">Pay on order validation via WhatsApp secure dispatch.</span>
                </div>

                <!-- Interactive Choice Elements -->
                <div class="space-y-6">
                    <!-- Color Selection -->
                    <div>
                        <label class="block text-xs uppercase font-bold tracking-widest text-zinc-400 mb-2">Select Color</label>
                        <select id="tee-color" class="w-full bg-zinc-950 border border-zinc-800 text-white rounded-none p-3 text-sm focus:outline-none focus:border-yellow-400 transition">
                            <option value="Venda Earth Brown">Venda Earth Brown</option>
                            <option value="Limpopo Deep Charcoal">Limpopo Deep Charcoal</option>
                            <option value="Ancestral Heritage Off-White">Ancestral Heritage Off-White</option>
                            <option value="Sovereign Black">Sovereign Black</option>
                        </select>
                    </div>

                    <!-- Size Selection -->
                    <div>
                        <label class="block text-xs uppercase font-bold tracking-widest text-zinc-400 mb-2">Select Size (Oversized Fit)</label>
                        <div class="grid grid-cols-4 gap-2">
                            <button type="button" onclick="setSize('S')" class="size-btn border border-zinc-800 p-3 text-sm font-bold tracking-wider hover:border-white transition bg-zinc-950">S</button>
                            <button type="button" onclick="setSize('M')" class="size-btn border border-zinc-800 p-3 text-sm font-bold tracking-wider hover:border-white transition bg-zinc-950">M</button>
                            <button type="button" onclick="setSize('L')" class="size-btn border border-zinc-800 p-3 text-sm font-bold tracking-wider hover:border-white transition bg-zinc-950">L</button>
                            <button type="button" onclick="setSize('XL')" class="size-btn border border-zinc-800 p-3 text-sm font-bold tracking-wider hover:border-white transition bg-zinc-950">XL</button>
                        </div>
                        <input type="hidden" id="tee-size" value="">
                    </div>

                    <!-- Quantity Counter -->
                    <div>
                        <label class="block text-xs uppercase font-bold tracking-widest text-zinc-400 mb-2">Quantity</label>
                        <div class="flex items-center w-32 border border-zinc-800 bg-zinc-950">
                            <button type="button" onclick="adjustQty(-1)" class="w-10 p-2 text-zinc-400 hover:text-white font-bold">-</button>
                            <input type="number" id="tee-qty" value="1" min="1" readonly class="w-12 bg-transparent text-center text-sm font-mono border-none focus:outline-none">
                            <button type="button" onclick="adjustQty(1)" class="w-10 p-2 text-zinc-400 hover:text-white font-bold">+</button>
                        </div>
                    </div>
                </div>
            </div>

            <!-- WhatsApp Instant Checkout Integration -->
            <div class="mt-8">
                <button onclick="sendWhatsAppOrder()" class="w-full bg-white text-black font-bold uppercase tracking-wider py-4 hover:bg-yellow-400 transition duration-300 flex items-center justify-center gap-3 shadow-lg">
                    <i class="fa-brands fa-whatsapp text-xl"></i> Order via WhatsApp
                </button>
                <span id="error-msg" class="text-red-400 text-xs mt-2 block hidden font-medium">Please select a size before checking out.</span>
            </div>

        </div>
    </main>

    <!-- 4. CONTACT & SOCIALS BLOCK FOOTER -->
    <footer id="contact" class="bg-zinc-950 border-t border-zinc-900 mt-20 py-16 px-6">
        <div class="max-w-7xl mx-auto grid grid-cols-1 md:grid-cols-3 gap-12 text-center md:text-left">
            
            <!-- Origin Statement -->
            <div>
                <h4 class="brand-heading text-sm uppercase tracking-widest text-zinc-400 mb-4">The Roots</h4>
                <p class="text-zinc-500 text-sm leading-relaxed">
                    Designed and inspired by the landscapes and rich cultural legacy of <span class="text-white">Venda, South Africa</span>. Blending local historical identity into high-quality urban wear.
                </p>
            </div>

            <!-- Contact Information -->
            <div>
                <h4 class="brand-heading text-sm uppercase tracking-widest text-zinc-400 mb-4">Contact Lines</h4>
                <ul class="space-y-2 text-sm text-zinc-300 font-mono">
                    <li><i class="fa-solid fa-envelope text-zinc-500 mr-2"></i> info@yourbrand.co.za</li>
                    <li><i class="fa-solid fa-phone text-zinc-500 mr-2"></i> +27 61 234 5678</li>
                    <li><i class="fa-solid fa-location-dot text-zinc-500 mr-2"></i> Thohoyandou, Venda</li>
                </ul>
            </div>

            <!-- Visual Anchor Social Grid Icons -->
            <div>
                <h4 class="brand-heading text-sm uppercase tracking-widest text-zinc-400 mb-4">Digital Identity</h4>
                <div class="flex justify-center md:justify-start gap-4">
                    <a href="https://instagram.com" target="_blank" class="w-12 h-12 rounded-none bg-zinc-900 border border-zinc-800 flex items-center justify-center hover:bg-yellow-400 hover:text-black hover:border-yellow-400 transition text-lg" title="Instagram">
                        <i class="fa-brands fa-instagram"></i>
                    </a>

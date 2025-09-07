<!DOCTYPE html>  <html lang="en">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Raptor - Men's Sports & Basics Wear</title>  
    <script src="https://cdn.tailwindcss.com"></script>  
    <style>  
        :root {  
            --main-black: #000000;  
            --secondary-orange: #FF4F00;  
            --white-text: #FFFFFF;  
            --black-text: #000000;  
        }  
        body {  
            background-color: var(--main-black);  
            color: var(--white-text);  
        }  
        .btn-orange {  
            background-color: var(--secondary-orange);  
            color: var(--black-text);  
            transition: all 0.3s ease;  
        }  
        .btn-orange:hover {  
            background-color: #E64700;  
            transform: scale(1.05);  
        }  
        .btn-black {  
            background-color: var(--main-black);  
            color: var(--white-text);  
            border: 2px solid var(--secondary-orange);  
            transition: all 0.3s ease;  
        }  
        .btn-black:hover {  
            background-color: var(--secondary-orange);  
            color: var(--black-text);  
            transform: scale(1.05);  
        }  
        .nav-link {  
            color: var(--white-text);  
            transition: color 0.3s ease;  
        }  
        .nav-link:hover {  
            color: var(--secondary-orange);  
        }  
        .hero-bg {  
            background: linear-gradient(135deg, var(--main-black) 50%, var(--secondary-orange) 50%);  
        }  
        .product-card {  
            background-color: var(--main-black);  
            border: 1px solid var(--secondary-orange);  
            transition: box-shadow 0.3s ease;  
        }  
        .product-card:hover {  
            box-shadow: 0 0 20px var(--secondary-orange);  
        }  
        .logo-text {  
            font-family: 'Arial Black', sans-serif;  
            text-transform: uppercase;  
            letter-spacing: 2px;  
        }  
        .logo-container {  
            display: flex;  
            align-items: center;  
        }  
        .logo-image {  
            width: 50px;  
            height: 50px;  
            object-fit: contain;  
        }  
    </style>  
</head>  
<body>  
    <!-- Navigation -->  
    <nav class="bg-black shadow-lg sticky top-0 z-50">  
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">  
            <div class="flex justify-between h-16">  
                <div class="flex items-center">  
                    <div class="flex-shrink-0">  
                        <a href="#home" class="logo-container">  
                            <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/9ffdaffb-ac21-4bfe-ac62-530f7143103d.png" class="logo-image mr-2" alt="Fierce dinosaur raptor skull logo rendered in molten orange against a sleek black background, with sharp metallic teeth glowing intensely, evoking themes of strength, speed, danger, and primal power for the men's sports and basics wear brand" onerror="this.style.display='none';" />  
                            <span class="logo-text text-xl font-bold text-white">RAPTOR</span>  
                        </a>  
                    </div>  
                </div>  
                <div class="hidden md:flex items-center space-x-8">  
                    <a href="#home" class="nav-link">Home</a>  
                    <a href="#sports" class="nav-link">Sports Wear</a>  
                    <a href="#basics" class="nav-link">Basics</a>  
                    <a href="#about" class="nav-link">About</a>  
                    <a href="#contact" class="nav-link">Contact</a>  
                </div>  
                <div class="md:hidden flex items-center">  
                    <button id="mobile-menu-button" class="btn-orange px-3 py-2 rounded">  
                        Menu  
                    </button>  
                </div>  
            </div>  
        </div>  
        <div id="mobile-menu" class="md:hidden hidden bg-black">  
            <div class="px-2 pt-2 pb-3 space-y-1">  
                <a href="#home" class="nav-link block px-3 py-2">Home</a>  
                <a href="#sports" class="nav-link block px-3 py-2">Sports Wear</a>  
                <a href="#basics" class="nav-link block px-3 py-2">Basics</a>  
                <a href="#about" class="nav-link block px-3 py-2">About</a>  
                <a href="#contact" class="nav-link block px-3 py-2">Contact</a>  
            </div>  
        </div>  
    </nav>  <!-- Hero Section -->  
<section id="home" class="hero-bg min-h-screen flex items-center">  
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20">  
        <div class="text-center">  
            <h1 class="text-5xl md:text-7xl font-bold mb-6 logo-text">RAPTOR</h1>  
            <p class="text-xl md:text-2xl mb-8">Strong. Fast. Dangerous. Elevate your game with elite sports wear and timeless basics.</p>  
            <a href="#sports" class="btn-orange px-8 py-3 rounded-full font-semibold mr-4">Explore Sports Wear</a>  
            <a href="#basics" class="btn-black px-8 py-3 rounded-full font-semibold">Discover Basics</a>  
        </div>  
        <div class="mt-10 flex justify-center">  
            <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/1c21ad2d-fd45-47a8-8ebb-6af1a8428e64.png" alt="High-energy sports scene featuring a male athlete in Raptor gear sprinting powerfully on a track field with molten orange and black speed lines, strong muscles tensed, fast motion blur, conveying danger and intensity" class="w-full max-w-4xl rounded-lg shadow-lg" onerror="this.style.display='none';">  
        </div>  
    </div>  
</section>  

<!-- Sports Wear Section -->  
<section id="sports" class="py-20">  
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">  
        <h2 class="text-4xl font-bold text-white text-center mb-12 logo-text">Sports Wear Collection</h2>  
        <p class="text-lg text-center mb-16 max-w-2xl mx-auto">Designed for the predator inside. Gear up with performance-oriented apparel that combines strength, speed, and a dangerous edge.</p>  
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">  
            <div class="product-card p-6 rounded-lg text-center">  
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/3fd941ae-816e-4f9c-a887-23a43b1032a8.png" alt="Close-up of a sleek Raptor sports jersey for men, featuring black fabric with molten orange accents, breathable material, athletic fit, worn by a muscular athlete, emphasizing speed and strength" class="w-full h-64 object-cover rounded mb-4" onerror="this.style.display='none';">  
                <h3 class="text-2xl font-semibold mb-2">Performance Jersey</h3>  
                <p class="mb-4">Sweat-wicking, durable, and styled for victory.</p>  
                <button class="btn-orange px-4 py-2 rounded">Shop Now</button>  
            </div>  
            <div class="product-card p-6 rounded-lg text-center">  
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/bebef6ef-3e01-4ed2-a662-9a7ed4d10b2f.png" alt="Sporty Raptor athletic shorts for men, in black with molten orange trim, lightweight and flexible, shown on active legs during a run, highlighting speed and danger in motion" class="w-full h-64 object-cover rounded mb-4" onerror="this.style.display='none';">  
                <h3 class="text-2xl font-semibold mb-2">Dynamic Shorts</h3>  
                <p class="mb-4">Flexible, breathable, and built for intense workouts.</p>  
                <button class="btn-orange px-4 py-2 rounded">Shop Now</button>  
            </div>  
            <div class="product-card p-6 rounded-lg text-center">  
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/7631ae27-2e60-4337-ab02-7aa8c5c83f57.png" alt="Edgy Raptor sports hoodie for men, black with molten orange logos, hood up for stealthy look, athletic build, conveying strength and danger" class="w-full h-64 object-cover rounded mb-4" onerror="this.style.display='none';">  
                <h3 class="text-2xl font-semibold mb-2">Agile Hoodie</h3>  
                <p class="mb-4">Warm yet lightweight, with a predatory design.</p>  
                <button class="btn-orange px-4 py-2 rounded">Shop Now</button>  
            </div>  
        </div>  
    </div>  
</section>  

<!-- Basics Wear Section -->  
<section id="basics" class="py-20 bg-gradient-to-r from-black to-gray-800">  
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">  
        <h2 class="text-4xl font-bold text-white text-center mb-12 logo-text">Basics Wear</h2>  
        <p class="text-lg text-center mb-16 max-w-2xl mx-auto">Timeless essentials crafted with the fierce simplicity of a raptor. Bold basics for everyday dominance.</p>  
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">  
            <div class="product-card p-6 rounded-lg text-center">  
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/adcfcb57-1db1-4825-9683-f5ace91c3b81.png" alt="Minimalist Raptor basic t-shirt for men, solid black with subtle molten orange neckline, fitted slim, plain backdrop emphasizing clean dangerous look" class="w-full h-64 object-cover rounded mb-4" onerror="this.style.display='none';">  
                <h3 class="text-2xl font-semibold mb-2">Essential Tee</h3>  
                <p class="mb-4">Soft, comfortable, and endlessly versatile.</p>  
                <button class="btn-orange px-4 py-2 rounded">Shop Now</button>  
            </div>  
            <div class="product-card p-6 rounded-lg text-center">  
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/aed16232-b31d-4a8c-b03c-be3210a6bdb1.png" alt="Stylish Raptor classic pants for men, black with molten orange thread details, straight fit, on a confident stance, radiating strength and fast style" class="w-full h-64 object-cover rounded mb-4" onerror="this.style.display='none';">  
                <h3 class="text-2xl font-semibold mb-2">Dominant Pants</h3>  
                <p class="mb-4">Sleek, fitted, with a hint of predatory edge.</p>  
                <button class="btn-orange px-4 py-2 rounded">Shop Now</button>  
            </div>  
            <div class="product-card p-6 rounded-lg text-center">  
                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/1c395af4-ea31-4fec-9204-9aea5be0dc74.png" alt="Bold Raptor leather-inspired jacket for men, black with molten orange zippers, casual yet intimidating, dark urban setting, evoking danger and power" class="w-full h-64 object-cover rounded mb-4" onerror="this.style.display='none';">  
                <h3 class="text-2xl font-semibold mb-2">Stealth Jacket</h3>  
                <p class="mb-4">Robust and stylish for urban predators.</p>  
                <button class="btn-orange px-4 py-2 rounded">Shop Now</button>  
            </div>  
        </div>  
    </div>  
</section>  

<!-- About Section -->  
<section id="about" class="py-20">  
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">  
        <h2 class="text-4xl font-bold text-white mb-12 logo-text">About Raptor</h2>  
        <p class="text-lg mb-8 max-w-4xl mx-auto">Raptor isn't just a brand—it's a mindset. Born from the spirit of the fastest, strongest hunters, we channel that primal energy into every stitch, every seam. Our gear empowers men to unleash their inner predator, combining fierce performance with uncompromising style. From the track to the streets, embody the strength, speed, and danger of the Raptor.</p>  
        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/7744d874-d7e3-489c-bdd6-b8cc87f7a60d.png" alt="Symbolic illustration of a raptor bird evolved into masculine sports gear, black silhouette with molten orange eyes, powerful wings forming athletic apparel, dangerous aura in dark background" class="w-full max-w-lg mx-auto rounded-lg" onerror="this.style.display='none';">  
    </div>  
</section>  

<!-- Contact Section -->  
<section id="contact" class="py-20 bg-gradient-to-r from-black to-orange-900">  
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">  
        <h2 class="text-4xl font-bold text-black mb-12 logo-text">Contact Us</h2>  
        <p class="text-black text-lg mb-8">Ready to equip yourself with the power of Raptor? Reach out to dominate your wardrobe.</p>  
        <div class="max-w-md mx-auto">  
            <form id="contact-form" class="space-y-4">  
                <input type="text" id="name" placeholder="Your Name" class="w-full p-3 rounded bg-white text-black" required>  
                <input type="email" id="email" placeholder="Your Email" class="w-full p-3 rounded bg-white text-black" required>  
                <textarea id="message" placeholder="Your Message" rows="4" class="w-full p-3 rounded bg-white text-black" required></textarea>  
                <button type="submit" class="btn-black px-6 py-3 rounded-full font-semibold w-full">Send Message</button>  
            </form>  
        </div>  
    </div>  
</section>  

<!-- Footer -->  
<footer class="bg-black py-8">  
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">  
        <p class="text-white">© 2023 Raptor. All rights reserved. Unleash your inner predator.</p>  
    </div>  
</footer>  

<script>  
    // Mobile menu toggle  
    document.getElementById('mobile-menu-button').addEventListener('click', function() {  
        const menu = document.getElementById('mobile-menu');  
        menu.classList.toggle('hidden');  
    });  

    // Smooth scrolling for navigation  
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {  
        anchor.addEventListener('click', function (e) {  
            e.preventDefault();  
            document.querySelector(this.getAttribute('href')).scrollIntoView({  
                behavior: 'smooth'  
            });  
        });  
    });  

    // Contact form submission (mock)  
    document.getElementById('contact-form').addEventListener('submit', function(e) {  
        e.preventDefault();  
        alert('Thank you for contacting Raptor! We will respond soon.');  
        this.reset();  
    });  
</script>

</body>  
</html>  
</content>  
</create_file>  make to me easy link to open in chrom


<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NooZ Lawn Mowers | Expert Lawn & Land Care in Nakuru County</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons CDN -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            green: '#1b5e20',
                            lightgreen: '#2e7d32',
                            accent: '#fbc02d',
                            accentHover: '#f57f17',
                            dark: '#0f2912',
                            soft: '#f0fdf4'
                        }
                    },
                    fontFamily: {
                        sans: ['Plus Jakarta Sans', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        .leaf-pattern {
            background-image: radial-gradient(#2e7d32 0.75px, transparent 0.75px);
            background-size: 16px 16px;
            opacity: 0.08;
        }
    </style>
</head>
<body class="font-sans text-gray-800 bg-slate-50 antialiased">

    <!-- TOP QUICK BAR -->
    <div class="bg-brand-dark text-white text-xs sm:text-sm py-2 px-4 shadow-inner">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center gap-2">
            <div class="flex items-center space-x-2">
                <i class="fa-solid fa-location-dot text-brand-accent"></i>
                <span>Serving Nakuru County & Specializing in Kuresoi North</span>
            </div>
            <div class="flex flex-wrap items-center justify-center gap-4">
                <a href="tel:0700277721" class="hover:text-brand-accent transition"><i class="fa-solid fa-phone text-xs mr-1 text-green-400"></i>0700 277 721</a>
                <a href="tel:0719103629" class="hover:text-brand-accent transition"><i class="fa-solid fa-phone text-xs mr-1 text-green-400"></i>0719 103 629</a>
                <a href="https://wa.me/254734565855" target="_blank" class="hover:text-brand-accent transition text-green-400 font-semibold"><i class="fa-brands fa-whatsapp text-sm mr-1"></i>+254 734 565 855</a>
            </div>
        </div>
    </div>

    <!-- STICKY HEADER -->
    <header class="sticky top-0 z-50 bg-white/95 backdrop-blur-md border-b border-green-100 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex justify-between items-center h-20">
            <!-- LOGO -->
            <a href="#" class="flex items-center gap-3 group">
                <div class="w-12 h-12 bg-brand-green rounded-full flex items-center justify-center text-brand-accent shadow-md group-hover:scale-105 transition">
                    <i class="fa-solid fa-leaf text-2xl"></i>
                </div>
                <div>
                    <span class="text-2xl font-black text-brand-dark tracking-tight leading-none block">NooZ</span>
                    <span class="text-xs font-bold text-brand-lightgreen uppercase tracking-widest block">Lawn Mowers</span>
                </div>
            </a>

            <!-- DESKTOP NAV -->
            <nav class="hidden lg:flex items-center gap-8 font-semibold text-gray-700 text-sm">
                <a href="#about" class="hover:text-brand-lightgreen transition">About Us</a>
                <a href="#services" class="hover:text-brand-lightgreen transition">Our Services</a>
                <a href="#pricing" class="hover:text-brand-lightgreen transition">Pricing</a>
                <a href="#coverage" class="hover:text-brand-lightgreen transition">Area Covered</a>
                <a href="#blog" class="hover:text-brand-lightgreen transition">Blog</a>
            </nav>

            <!-- CTA BUTTON -->
            <div class="hidden sm:flex items-center gap-3">
                <a href="#contact" class="bg-brand-accent hover:bg-brand-accentHover text-brand-dark font-bold px-5 py-2.5 rounded-full shadow-md hover:shadow-lg transition transform hover:-translate-y-0.5 text-sm flex items-center gap-2">
                    <i class="fa-solid fa-calendar-check"></i> Book Now
                </a>
            </div>

            <!-- MOBILE MENU BUTTON -->
            <button id="mobile-menu-btn" class="lg:hidden text-2xl text-brand-dark focus:outline-none">
                <i class="fa-solid fa-bars"></i>
            </button>
        </div>

        <!-- MOBILE NAV MENU -->
        <div id="mobile-menu" class="hidden lg:hidden bg-white border-b border-gray-200 px-4 pt-2 pb-6 space-y-3">
            <a href="#about" class="block py-2 text-gray-700 font-medium">About Us</a>
            <a href="#services" class="block py-2 text-gray-700 font-medium">Our Services</a>
            <a href="#pricing" class="block py-2 text-gray-700 font-medium">Pricing</a>
            <a href="#coverage" class="block py-2 text-gray-700 font-medium">Area Covered</a>
            <a href="#blog" class="block py-2 text-gray-700 font-medium">Blog</a>
            <a href="#contact" class="block w-full text-center bg-brand-accent text-brand-dark font-bold py-3 rounded-xl mt-4">Book Now</a>
        </div>
    </header>

    <!-- HERO SECTION -->
    <section class="relative bg-brand-dark text-white overflow-hidden py-20 lg:py-32">
        <div class="absolute inset-0 z-0 opacity-40">
            <img src="https://images.unsplash.com/photo-1592417817098-8f3d6eb16432?auto=format&fit=crop&w=1920&q=80" alt="Lawn Mowing Landscape" class="w-full h-full object-cover">
        </div>
        <div class="absolute inset-0 bg-gradient-to-r from-brand-dark via-brand-dark/80 to-transparent z-10"></div>
        <div class="absolute inset-0 leaf-pattern z-10"></div>

        <div class="relative z-20 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 grid lg:grid-cols-12 gap-12 items-center">
            <div class="lg:col-span-8 space-y-6 text-center lg:text-left">
                <div class="inline-flex items-center gap-2 bg-brand-lightgreen/30 border border-green-400/40 text-green-300 px-4 py-1.5 rounded-full text-xs font-bold uppercase tracking-wider backdrop-blur-md">
                    <i class="fa-solid fa-shield-halved"></i> Nakuru County's Trusted Land Care Specialist
                </div>
                
                <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight leading-tight text-white">
                    WE MAKE YOUR LAWN <br class="hidden sm:inline"><span class="text-brand-accent">LOOK ITS BEST!</span>
                </h1>

                <p class="text-lg sm:text-xl text-gray-200 max-w-2xl font-normal leading-relaxed">
                    Providing reliable, affordable, and expert lawn and land care services for over a decade in Nakuru County.
                </p>

                <div class="flex flex-col sm:flex-row gap-4 justify-center lg:justify-start pt-4">
                    <a href="#pricing" class="bg-brand-accent hover:bg-brand-accentHover text-brand-dark font-extrabold px-8 py-4 rounded-xl shadow-lg transition text-base text-center flex items-center justify-center gap-2">
                        Get Your Free Estimate <i class="fa-solid fa-arrow-right"></i>
                    </a>
                    <a href="#services" class="bg-white/10 hover:bg-white/20 border border-white/30 text-white font-semibold px-8 py-4 rounded-xl transition text-base text-center backdrop-blur-sm">
                        Explore Our Services
                    </a>
                </div>

                <!-- VALUE COUNTERS -->
                <div class="pt-8 grid grid-cols-3 gap-4 border-t border-white/10 mt-8 max-w-lg mx-auto lg:mx-0">
                    <div>
                        <span class="block text-2xl sm:text-3xl font-extrabold text-brand-accent">10+</span>
                        <span class="text-xs text-gray-300">Years Experience</span>
                    </div>
                    <div>
                        <span class="block text-2xl sm:text-3xl font-extrabold text-brand-accent">100%</span>
                        <span class="text-xs text-gray-300">Reliable Service</span>
                    </div>
                    <div>
                        <span class="block text-2xl sm:text-3xl font-extrabold text-brand-accent">Kuresoi</span>
                        <span class="text-xs text-gray-300">North Focus</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ABOUT US SECTION -->
    <section id="about" class="py-20 bg-white relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <!-- Text Column -->
                <div class="space-y-6">
                    <div class="inline-block bg-green-100 text-brand-lightgreen font-bold text-xs px-3 py-1 rounded-md uppercase tracking-wider">
                        Your Partner in Land Care
                    </div>
                    <h2 class="text-3xl sm:text-4xl font-extrabold text-gray-900 leading-tight">
                        Dedicated Land Care Built On Precision & Technical Expertise
                    </h2>
                    <p class="text-gray-600 leading-relaxed">
                        Welcome to <strong>NooZ Lawn Mowers</strong>. We do lawn mowing, all general grass cutting, farm harvesting for: <strong>oats, maize, napier grass</strong>, and <strong>bush and weed clearance</strong>.
                    </p>
                    <p class="text-gray-600 leading-relaxed">
                        With over a decade of dedication, we bring technical expertise and a track record of successful land care projects. Our team utilizes modern equipment and sustainable practices to ensure that every project—whether residential, commercial, or agricultural—stands the test of time for precision and quality. Let us help you bring your vision to life.
                    </p>
                    
                    <div class="grid sm:grid-cols-2 gap-4 pt-4">
                        <div class="flex items-start gap-3">
                            <i class="fa-solid fa-circle-check text-brand-lightgreen text-xl mt-1"></i>
                            <div>
                                <h4 class="font-bold text-gray-900">Modern Machinery</h4>
                                <p class="text-xs text-gray-500">Brush cutters & precision mowers</p>
                            </div>
                        </div>
                        <div class="flex items-start gap-3">
                            <i class="fa-solid fa-circle-check text-brand-lightgreen text-xl mt-1"></i>
                            <div>
                                <h4 class="font-bold text-gray-900">Crop Harvesting</h4>
                                <p class="text-xs text-gray-500">Fast Oats, Maize & Napier clearance</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Visual Column: Split Screen Concept -->
                <div class="relative">
                    <div class="grid grid-cols-2 gap-4">
                        <div class="space-y-4">
                            <div class="rounded-2xl overflow-hidden shadow-md bg-gray-100 border border-gray-200">
                                <img src="https://images.unsplash.com/photo-1589307904320-73f15b3a322e?auto=format&fit=crop&w=600&q=80" alt="Technical Trimmer Equipment" class="w-full h-48 object-cover">
                                <div class="p-3 text-center bg-brand-dark text-white text-xs font-semibold">
                                    <i class="fa-solid fa-gears text-brand-accent mr-1"></i> Precision Gear
                                </div>
                            </div>
                        </div>
                        <div class="space-y-4 mt-6">
                            <div class="rounded-2xl overflow-hidden shadow-md bg-gray-100 border border-gray-200">
                                <img src="https://images.unsplash.com/photo-1558904541-efa843a96f01?auto=format&fit=crop&w=600&q=80" alt="Completed Perfect Lawn" class="w-full h-56 object-cover">
                                <div class="p-3 text-center bg-brand-lightgreen text-white text-xs font-semibold">
                                    <i class="fa-solid fa-thumbs-up text-brand-accent mr-1"></i> Completed Outcome
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- SERVICES SECTION -->
    <section id="services" class="py-20 bg-brand-soft border-y border-green-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <span class="text-brand-lightgreen font-bold text-xs uppercase tracking-widest">Our Expertise</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-gray-900 mt-2">Comprehensive Land & Lawn Services</h2>
                <p class="text-gray-600 mt-3">Tailored services for residential lawns, agricultural farms, and open brush land across Nakuru County.</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <!-- Service 1 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition-all duration-300 border border-green-100 flex flex-col justify-between overflow-hidden group">
                    <div>
                        <div class="relative h-48 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1592417817098-8f3d6eb16432?auto=format&fit=crop&w=600&q=80" alt="Lawn Mowing" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 left-3 bg-brand-lightgreen text-white text-xs font-bold px-3 py-1 rounded-full flex items-center gap-1">
                                <i class="fa-solid fa-circle-check text-brand-accent"></i> Core Service
                            </span>
                        </div>
                        <div class="p-6">
                            <h3 class="text-xl font-bold text-gray-900 mb-2">Lawn Mowing</h3>
                            <p class="text-sm text-gray-600 mb-4">Precision cutting for residential and estate lawns. Keeps your turf healthy, clean, and neatly manicured.</p>
                        </div>
                    </div>
                    <div class="p-6 pt-0">
                        <a href="#contact" class="w-full bg-slate-100 hover:bg-brand-lightgreen hover:text-white text-gray-800 font-bold py-2.5 rounded-xl text-xs transition flex items-center justify-center gap-2">
                            Book Service <i class="fa-solid fa-chevron-right text-xs"></i>
                        </a>
                    </div>
                </div>

                <!-- Service 2 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition-all duration-300 border border-green-100 flex flex-col justify-between overflow-hidden group">
                    <div>
                        <div class="relative h-48 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1530587191325-3db32d826c18?auto=format&fit=crop&w=600&q=80" alt="Grass Cutting" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 left-3 bg-brand-lightgreen text-white text-xs font-bold px-3 py-1 rounded-full flex items-center gap-1">
                                <i class="fa-solid fa-circle-check text-brand-accent"></i> Commercial & General
                            </span>
                        </div>
                        <div class="p-6">
                            <h3 class="text-xl font-bold text-gray-900 mb-2">General Grass Cutting</h3>
                            <p class="text-sm text-gray-600 mb-4">Efficient clearing for larger compounds, institutions, and open fields requiring heavy-duty grass management.</p>
                        </div>
                    </div>
                    <div class="p-6 pt-0">
                        <a href="#contact" class="w-full bg-slate-100 hover:bg-brand-lightgreen hover:text-white text-gray-800 font-bold py-2.5 rounded-xl text-xs transition flex items-center justify-center gap-2">
                            Book Service <i class="fa-solid fa-chevron-right text-xs"></i>
                        </a>
                    </div>
                </div>

                <!-- Service 3 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition-all duration-300 border border-green-100 flex flex-col justify-between overflow-hidden group">
                    <div>
                        <div class="relative h-48 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1500382017468-9049fed747ef?auto=format&fit=crop&w=600&q=80" alt="Farm Harvesting" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 left-3 bg-brand-lightgreen text-white text-xs font-bold px-3 py-1 rounded-full flex items-center gap-1">
                                <i class="fa-solid fa-wheat-awn text-brand-accent"></i> Agriculture
                            </span>
                        </div>
                        <div class="p-6">
                            <h3 class="text-xl font-bold text-gray-900 mb-1">Farm Harvesting</h3>
                            <p class="text-xs text-brand-lightgreen font-bold mb-2">Oats | Maize | Napier Grass</p>
                            <p class="text-sm text-gray-600 mb-4">Fast and careful harvesting for essential feed and crops, helping farm owners save labor time and costs.</p>
                        </div>
                    </div>
                    <div class="p-6 pt-0">
                        <a href="#contact" class="w-full bg-slate-100 hover:bg-brand-lightgreen hover:text-white text-gray-800 font-bold py-2.5 rounded-xl text-xs transition flex items-center justify-center gap-2">
                            Book Service <i class="fa-solid fa-chevron-right text-xs"></i>
                        </a>
                    </div>
                </div>

                <!-- Service 4 -->
                <div class="bg-white rounded-2xl shadow-sm hover:shadow-xl transition-all duration-300 border border-green-100 flex flex-col justify-between overflow-hidden group">
                    <div>
                        <div class="relative h-48 overflow-hidden">
                            <img src="https://images.unsplash.com/photo-1500937386664-56d1dfef3854?auto=format&fit=crop&w=600&q=80" alt="Bush and Weed Clearance" class="w-full h-full object-cover group-hover:scale-105 transition duration-500">
                            <span class="absolute top-3 left-3 bg-brand-lightgreen text-white text-xs font-bold px-3 py-1 rounded-full flex items-center gap-1">
                                <i class="fa-solid fa-broom text-brand-accent"></i> Land Clearing
                            </span>
                        </div>
                        <div class="p-6">
                            <h3 class="text-xl font-bold text-gray-900 mb-2">Bush & Weed Clearance</h3>
                            <p class="text-sm text-gray-600 mb-4">Strategic clearing of overgrown thickets, wild bushes, and tall weeds to prepare land for construction or farming.</p>
                        </div>
                    </div>
                    <div class="p-6 pt-0">
                        <a href="#contact" class="w-full bg-slate-100 hover:bg-brand-lightgreen hover:text-white text-gray-800 font-bold py-2.5 rounded-xl text-xs transition flex items-center justify-center gap-2">
                            Book Service <i class="fa-solid fa-chevron-right text-xs"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- COST & HIRING (PRICING & CALCULATOR) SECTION -->
    <section id="pricing" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-12">
                <span class="text-brand-lightgreen font-bold text-xs uppercase tracking-widest">Cost & Hiring</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-gray-900 mt-2">Transparent & Affordable Pricing</h2>
                <p class="text-gray-600 mt-2">Choose the billing model that best fits your land and project scale.</p>
            </div>

            <!-- PRICING OPTIONS SIDE-BY-SIDE -->
            <div class="grid md:grid-cols-2 gap-8 max-w-4xl mx-auto mb-16">
                <!-- Option 1 -->
                <div class="bg-gradient-to-b from-green-50 to-white rounded-3xl p-8 border-2 border-brand-lightgreen/30 relative shadow-md flex flex-col justify-between">
                    <div>
                        <div class="flex justify-between items-start mb-4">
                            <span class="bg-brand-lightgreen text-white text-xs font-bold px-3 py-1 rounded-full">Option 1</span>
                            <i class="fa-solid fa-clock text-3xl text-brand-lightgreen"></i>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-900">Hourly Rate</h3>
                        <p class="text-gray-500 text-sm mt-1">Ideal for general lawn maintenance and smaller gardens.</p>
                        <div class="my-6">
                            <span class="text-4xl sm:text-5xl font-black text-brand-dark">Ksh 150</span>
                            <span class="text-gray-500 font-medium">/ HOUR</span>
                        </div>
                    </div>
                    <a href="#calculator" class="w-full bg-brand-lightgreen text-white text-center font-bold py-3 rounded-xl hover:bg-brand-dark transition">
                        Calculate Hourly Cost
                    </a>
                </div>

                <!-- Option 2 -->
                <div class="bg-gradient-to-b from-yellow-50 to-white rounded-3xl p-8 border-2 border-brand-accent/40 relative shadow-md flex flex-col justify-between">
                    <div>
                        <div class="flex justify-between items-start mb-4">
                            <span class="bg-brand-accent text-brand-dark text-xs font-bold px-3 py-1 rounded-full">Option 2</span>
                            <i class="fa-solid fa-tag text-3xl text-brand-accent"></i>
                        </div>
                        <h3 class="text-2xl font-bold text-gray-900">Area Coverage</h3>
                        <p class="text-gray-500 text-sm mt-1">Best for large farms, open fields, and crop harvesting.</p>
                        <div class="my-6">
                            <span class="text-4xl sm:text-5xl font-black text-brand-dark">Ksh 15</span>
                            <span class="text-gray-500 font-medium">/ SQ METER</span>
                        </div>
                    </div>
                    <a href="#calculator" class="w-full bg-brand-accent text-brand-dark text-center font-bold py-3 rounded-xl hover:bg-brand-accentHover transition">
                        Calculate Area Cost
                    </a>
                </div>
            </div>

            <!-- INTERACTIVE ESTIMATE CALCULATOR TOOL -->
            <div id="calculator" class="max-w-3xl mx-auto bg-brand-dark text-white rounded-3xl p-6 sm:p-10 shadow-2xl relative overflow-hidden">
                <div class="relative z-10">
                    <div class="flex items-center gap-3 mb-6">
                        <div class="w-10 h-10 bg-brand-accent text-brand-dark rounded-full flex items-center justify-center font-bold">
                            <i class="fa-solid fa-calculator"></i>
                        </div>
                        <div>
                            <h3 class="text-2xl font-bold">Interactive Estimate Calculator</h3>
                            <p class="text-xs text-gray-300">Get an instant preliminary cost estimate for your land care.</p>
                        </div>
                    </div>

                    <div class="grid sm:grid-cols-2 gap-6 mb-6">
                        <div>
                            <label class="block text-xs font-semibold uppercase tracking-wider text-gray-300 mb-2">Calculation Method</label>
                            <select id="calc-type" onchange="calculateEstimate()" class="w-full bg-white/10 border border-white/20 rounded-xl px-4 py-3 text-white focus:outline-none focus:ring-2 focus:ring-brand-accent">
                                <option value="hourly" class="bg-brand-dark text-white">By Time (Ksh 150 / Hour)</option>
                                <option value="area" class="bg-brand-dark text-white">By Area (Ksh 15 / Sq Meter)</option>
                            </select>
                        </div>

                        <div>
                            <label id="input-label" class="block text-xs font-semibold uppercase tracking-wider text-gray-300 mb-2">Number of Hours</label>
                            <input type="number" id="calc-input" value="3" min="1" oninput="calculateEstimate()" class="w-full bg-white/10 border border-white/20 rounded-xl px-4 py-3 text-white focus:outline-none focus:ring-2 focus:ring-brand-accent">
                        </div>
                    </div>

                    <div class="bg-white/10 rounded-2xl p-6 border border-white/15 flex flex-col sm:flex-row justify-between items-center gap-4">
                        <div>
                            <span class="text-xs text-gray-300 uppercase block">Estimated Cost</span>
                            <span id="calc-result" class="text-3xl sm:text-4xl font-extrabold text-brand-accent">Ksh 450</span>
                        </div>
                        <a href="#contact" class="bg-brand-accent hover:bg-brand-accentHover text-brand-dark font-bold px-6 py-3 rounded-xl transition text-sm">
                            Confirm Booking <i class="fa-solid fa-arrow-right ml-1"></i>
                        </a>
                    </div>

                    <div class="mt-6 flex items-center gap-2 text-sm text-green-200">
                        <span class="text-xl">😊</span>
                        <span>We ensure cost-effective, sustainable outcomes. <strong>No Hidden Fees!</strong></span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- AREA COVERED SECTION -->
    <section id="coverage" class="py-20 bg-slate-50 border-t border-gray-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-2 gap-12 items-center">
                <div class="space-y-6">
                    <span class="text-brand-lightgreen font-bold text-xs uppercase tracking-widest">Service Coverage</span>
                    <h2 class="text-3xl sm:text-4xl font-extrabold text-gray-900">Proudly Serving Nakuru County</h2>
                    <p class="text-gray-600 leading-relaxed">
                        With central operations and dedicated focus in <strong>Kuresoi North</strong>, our team is equipped to transport heavy-duty grass cutting, harvesting, and bush clearing tools directly to your location anywhere across Nakuru County.
                    </p>

                    <div class="space-y-3 pt-2">
                        <div class="flex items-center gap-3 bg-white p-3.5 rounded-xl border border-gray-200 shadow-sm">
                            <i class="fa-solid fa-location-pin text-brand-lightgreen text-xl"></i>
                            <div>
                                <strong class="text-gray-900 text-sm block">Primary Hub: Kuresoi North</strong>
                                <span class="text-xs text-gray-500">Fast mobilization for farms, lawns, and land clearing.</span>
                            </div>
                        </div>
                        <div class="flex items-center gap-3 bg-white p-3.5 rounded-xl border border-gray-200 shadow-sm">
                            <i class="fa-solid fa-map-location-dot text-brand-lightgreen text-xl"></i>
                            <div>
                                <strong class="text-gray-900 text-sm block">Nakuru Sub-Counties & Surrounding Areas</strong>
                                <span class="text-xs text-gray-500">Molo, Njoro, Elburgon, Eldama Ravine borders, and broader Nakuru.</span>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- MAP GRAPHIC PLACEHOLDER -->
                <div class="bg-brand-dark rounded-3xl p-8 text-white relative overflow-hidden shadow-xl min-h-[320px] flex flex-col justify-between">
                    <div class="absolute inset-0 leaf-pattern opacity-20"></div>
                    <div class="relative z-10 flex justify-between items-start">
                        <div>
                            <span class="bg-brand-accent text-brand-dark text-xs font-extrabold px-3 py-1 rounded-full uppercase">Kuresoi North Central</span>
                            <h3 class="text-xl font-bold mt-2">Nakuru Regional Reach</h3>
                        </div>
                        <i class="fa-solid fa-compass text-4xl text-brand-accent/40"></i>
                    </div>

                    <div class="relative z-10 my-8 text-center bg-white/10 backdrop-blur-md rounded-2xl p-6 border border-white/20">
                        <i class="fa-solid fa-map-pin text-4xl text-brand-accent animate-bounce mb-2 block"></i>
                        <span class="font-bold text-lg block">Kuresoi North & Environs</span>
                        <p class="text-xs text-gray-300 mt-1">Our team is always near you for quick deployment.</p>
                    </div>

                    <div class="relative z-10 text-xs text-gray-300 flex justify-between items-center">
                        <span><i class="fa-solid fa-truck-fast mr-1 text-brand-accent"></i> Mobile Service Units</span>
                        <span>Nakuru County</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- TESTIMONIALS SECTION -->
    <section class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <span class="text-brand-lightgreen font-bold text-xs uppercase tracking-widest">Client Reviews</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-gray-900 mt-2">What Our Customers Say</h2>
                <p class="text-gray-600 mt-2">Built on a track record of reliability, affordability, and total customer satisfaction.</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-brand-soft rounded-2xl p-6 border border-green-100 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex text-brand-accent gap-1 mb-4">
                            <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                        </div>
                        <p class="text-gray-700 text-sm italic mb-4">
                            "We needed our Napier grass farm field in Kuresoi North harvested quickly. NooZ's farm harvesting team was fast, reliable, and affordable. Highly recommend them for their technical expertise!"
                        </p>
                    </div>
                    <div class="flex items-center gap-3 pt-4 border-t border-green-200/50">
                        <div class="w-10 h-10 bg-brand-lightgreen text-white font-bold rounded-full flex items-center justify-center">
                            JS
                        </div>
                        <div>
                            <h4 class="font-bold text-gray-900 text-sm">Farm Owner</h4>
                            <span class="text-xs text-gray-500">Kuresoi North</span>
                        </div>
                    </div>
                </div>

                <!-- Testimonial 2 -->
                <div class="bg-brand-soft rounded-2xl p-6 border border-green-100 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex text-brand-accent gap-1 mb-4">
                            <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                        </div>
                        <p class="text-gray-700 text-sm italic mb-4">
                            "Their brush clearing team came and cleared a very thick weed plot in just one day. The Ksh 15 per sq meter pricing option gave us total value for our money without any hidden costs."
                        </p>
                    </div>
                    <div class="flex items-center gap-3 pt-4 border-t border-green-200/50">
                        <div class="w-10 h-10 bg-brand-lightgreen text-white font-bold rounded-full flex items-center justify-center">
                            MK
                        </div>
                        <div>
                            <h4 class="font-bold text-gray-900 text-sm">Residential Client</h4>
                            <span class="text-xs text-gray-500">Nakuru Town</span>
                        </div>
                    </div>
                </div>

                <!-- Testimonial 3 -->
                <div class="bg-brand-soft rounded-2xl p-6 border border-green-100 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex text-brand-accent gap-1 mb-4">
                            <i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i><i class="fa-solid fa-star"></i>
                        </div>
                        <p class="text-gray-700 text-sm italic mb-4">
                            "Always punctual and clean! The team mows our lawn every month and leaves it looking pristine. Truly the best land care team in Nakuru County."
                        </p>
                    </div>
                    <div class="flex items-center gap-3 pt-4 border-t border-green-200/50">
                        <div class="w-10 h-10 bg-brand-lightgreen text-white font-bold rounded-full flex items-center justify-center">
                            DK
                        </div>
                        <div>
                            <h4 class="font-bold text-gray-900 text-sm">Estate Manager</h4>
                            <span class="text-xs text-gray-500">Nakuru County</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- BLOG / INSIGHTS SECTION -->
    <section id="blog" class="py-20 bg-slate-50 border-t border-gray-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <span class="text-brand-lightgreen font-bold text-xs uppercase tracking-widest">Expert Guidance</span>
                <h2 class="text-3xl sm:text-4xl font-extrabold text-gray-900 mt-2">Land & Crop Care Insights</h2>
                <p class="text-gray-600 mt-2">Practical tips and guides tailored for farming and lawn maintenance in Nakuru County.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8">
                <article class="bg-white rounded-2xl overflow-hidden shadow-sm border border-gray-200 flex flex-col justify-between">
                    <div class="p-6">
                        <span class="text-xs font-bold text-brand-lightgreen uppercase">Lawn Care</span>
                        <h3 class="text-lg font-bold text-gray-900 mt-2 mb-3 hover:text-brand-lightgreen transition cursor-pointer">
                            Tips for Maintaining Your Lawn in Nakuru County
                        </h3>
                        <p class="text-gray-600 text-xs leading-relaxed">
                            Learn optimal mowing frequencies, watering routines, and soil care strategies suited for the highlands climate of Nakuru.
                        </p>
                    </div>
                    <div class="px-6 pb-6">
                        <a href="#contact" class="text-xs font-bold text-brand-dark hover:text-brand-lightgreen flex items-center gap-1">Read Article <i class="fa-solid fa-arrow-right"></i></a>
                    </div>
                </article>

                <article class="bg-white rounded-2xl overflow-hidden shadow-sm border border-gray-200 flex flex-col justify-between">
                    <div class="p-6">
                        <span class="text-xs font-bold text-brand-lightgreen uppercase">Harvesting</span>
                        <h3 class="text-lg font-bold text-gray-900 mt-2 mb-3 hover:text-brand-lightgreen transition cursor-pointer">
                            Understanding Napier Grass Harvesting in Kuresoi North
                        </h3>
                        <p class="text-gray-600 text-xs leading-relaxed">
                            Maximize feed yield and ensure fast regrowth cycles with proper harvesting height and timing for Napier grass.
                        </p>
                    </div>
                    <div class="px-6 pb-6">
                        <a href="#contact" class="text-xs font-bold text-brand-dark hover:text-brand-lightgreen flex items-center gap-1">Read Article <i class="fa-solid fa-arrow-right"></i></a>
                    </div>
                </article>

                <article class="bg-white rounded-2xl overflow-hidden shadow-sm border border-gray-200 flex flex-col justify-between">
                    <div class="p-6">
                        <span class="text-xs font-bold text-brand-lightgreen uppercase">Land Prep</span>
                        <h3 class="text-lg font-bold text-gray-900 mt-2 mb-3 hover:text-brand-lightgreen transition cursor-pointer">
                            Seasonal Weed Clearance Strategies: A Guide from the NooZ Team
                        </h3>
                        <p class="text-gray-600 text-xs leading-relaxed">
                            How to clear aggressive wild bushes and weeds before planting season or groundbreaking for construction projects.
                        </p>
                    </div>
                    <div class="px-6 pb-6">
                        <a href="#contact" class="text-xs font-bold text-brand-dark hover:text-brand-lightgreen flex items-center gap-1">Read Article <i class="fa-solid fa-arrow-right"></i></a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- CONTACT US & FOOTER SECTION -->
    <footer id="contact" class="bg-brand-dark text-white pt-20 pb-8 relative overflow-hidden">
        <div class="absolute inset-0 leaf-pattern opacity-10"></div>
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            
            <div class="grid lg:grid-cols-12 gap-12 mb-16">
                <!-- Contact Info & WhatsApp -->
                <div class="lg:col-span-5 space-y-6">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 bg-brand-lightgreen text-brand-accent rounded-full flex items-center justify-center font-bold text-xl">
                            <i class="fa-solid fa-leaf"></i>
                        </div>
                        <span class="text-2xl font-black tracking-tight">NooZ Lawn Mowers</span>
                    </div>

                    <p class="text-gray-300 text-sm leading-relaxed">
                        Ready for professional lawn care, farm harvesting, or bush clearance in Nakuru County & Kuresoi North? Reach out to us directly for quick bookings!
                    </p>

                    <!-- Phone List -->
                    <div class="space-y-3 pt-2">
                        <a href="tel:0700277721" class="flex items-center gap-3 bg-white/5 hover:bg-white/10 p-3 rounded-xl border border-white/10 transition">
                            <i class="fa-solid fa-phone text-brand-accent"></i>
                            <span class="font-bold text-sm">0700 277 721</span>
                        </a>
                        <a href="tel:0719103629" class="flex items-center gap-3 bg-white/5 hover:bg-white/10 p-3 rounded-xl border border-white/10 transition">
                            <i class="fa-solid fa-phone text-brand-accent"></i>
                            <span class="font-bold text-sm">0719 103 629</span>
                        </a>
                        <a href="https://wa.me/254734565855" target="_blank" class="flex items-center justify-between bg-green-600 hover:bg-green-500 text-white p-3.5 rounded-xl font-bold transition shadow-lg">
                            <span class="flex items-center gap-2 text-sm"><i class="fa-brands fa-whatsapp text-xl"></i> Chat on WhatsApp</span>
                            <span class="text-xs bg-black/20 px-2 py-1 rounded">+254 734 565 855</span>
                        </a>
                    </div>

                    <div class="flex items-center gap-2 text-sm text-brand-accent pt-2">
                        <span class="text-xl">😊</span>
                        <span class="font-semibold">Thanks for your time!</span>
                    </div>
                </div>

                <!-- Contact Form -->
                <div class="lg:col-span-7 bg-white text-gray-900 rounded-3xl p-6 sm:p-8 shadow-xl">
                    <h3 class="text-2xl font-bold mb-2">Request a Free Quote</h3>
                    <p class="text-xs text-gray-500 mb-6">Fill in your details and we will call or message you shortly.</p>

                    <form onsubmit="event.preventDefault(); alert('Thank you! Your message has been received. We will contact you immediately.');" class="space-y-4">
                        <div class="grid sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Your Name</label>
                                <input type="text" placeholder="John Doe" required class="w-full bg-slate-50 border border-gray-300 rounded-xl px-4 py-3 text-sm focus:outline-none focus:ring-2 focus:ring-brand-lightgreen">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Phone Number</label>
                                <input type="tel" placeholder="07XX XXX XXX" required class="w-full bg-slate-50 border border-gray-300 rounded-xl px-4 py-3 text-sm focus:outline-none focus:ring-2 focus:ring-brand-lightgreen">
                            </div>
                        </div>

                        <div class="grid sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Service Required</label>
                                <select class="w-full bg-slate-50 border border-gray-300 rounded-xl px-4 py-3 text-sm focus:outline-none focus:ring-2 focus:ring-brand-lightgreen">
                                    <option>Lawn Mowing</option>
                                    <option>General Grass Cutting</option>
                                    <option>Farm Harvesting (Oats / Maize / Napier)</option>
                                    <option>Bush & Weed Clearance</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Location</label>
                                <input type="text" placeholder="e.g. Kuresoi North, Nakuru" required class="w-full bg-slate-50 border border-gray-300 rounded-xl px-4 py-3 text-sm focus:outline-none focus:ring-2 focus:ring-brand-lightgreen">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-gray-700 uppercase mb-1">Message / Area Estimate</label>
                            <textarea rows="3" placeholder="Tell us about your land size or special requirements..." class="w-full bg-slate-50 border border-gray-300 rounded-xl px-4 py-3 text-sm focus:outline-none focus:ring-2 focus:ring-brand-lightgreen"></textarea>
                        </div>

                        <button type="submit" class="w-full bg-brand-accent hover:bg-brand-accentHover text-brand-dark font-extrabold py-3.5 rounded-xl shadow-md transition text-sm">
                            Submit Estimate Request <i class="fa-solid fa-paper-plane ml-1"></i>
                        </button>
                    </form>
                </div>
            </div>

            <!-- FOOTER REPEATING VALUE PROPS BAR -->
            <div class="border-t border-white/10 pt-8 mt-8">
                <div class="flex flex-wrap justify-center items-center gap-6 sm:gap-12 text-xs sm:text-sm font-bold text-gray-300">
                    <span class="flex items-center gap-2">
                        <i class="fa-solid fa-circle-check text-brand-accent"></i> Reliable Service
                    </span>
                    <span class="text-white/20">|</span>
                    <span class="flex items-center gap-2">
                        <i class="fa-solid fa-leaf text-green-400"></i> Affordable Rates
                    </span>
                    <span class="text-white/20">|</span>
                    <span class="flex items-center gap-2">
                        <i class="fa-solid fa-thumbs-up text-brand-accent"></i> Customer Satisfaction
                    </span>
                </div>
                <p class="text-center text-xs text-gray-500 mt-6">&copy; 2026 NooZ Lawn Mowers. All rights reserved. Nakuru County, Kuresoi North.</p>
            </div>

        </div>
    </footer>

    <!-- INTERACTIVE CALCULATOR & MENU SCRIPT -->
    <script>
        // Interactive Calculator Function
        function calculateEstimate() {
            const calcType = document.getElementById('calc-type').value;
            const inputVal = parseFloat(document.getElementById('calc-input').value) || 0;
            const label = document.getElementById('input-label');
            const resultDisplay = document.getElementById('calc-result');

            let total = 0;

            if (calcType === 'hourly') {
                label.innerText = 'Number of Hours';
                total = inputVal * 150;
            } else {
                label.innerText = 'Square Meters (m²)';
                total = inputVal * 15;
            }

            resultDisplay.innerText = 'Ksh ' + total.toLocaleString();
        }

        // Mobile Menu Toggle
        const menuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
    </script>
</body>
</html>

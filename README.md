<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saniya Thrive Fitness</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700;italic&family=Lato:wght@400&display=swap" rel="stylesheet"/>
    <style>
        body {
            font-family: 'Lato', sans-serif;
        }
        .montserrat {
            font-family: 'Montserrat', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100">
    <!-- Navbar -->
    <nav class="bg-white shadow-lg">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex justify-between">
                <div class="flex space-x-4">
                    <!-- Logo -->
                    <div>
                        <a href="#" class="flex items-center py-5 px-2 text-gray-700">
                            <img src="assets/logo.jpg" alt="Logo combining a green leaf and orange dumbbell" class="h-8 w-8 mr-2">
                            <span class="font-bold text-xl montserrat">Saniya Thrive Fitness</span>
                        </a>
                    </div>
                    <!-- Primary Nav -->
                    <div class="hidden md:flex items-center space-x-1">
                        <a href="#" class="py-5 px-3 text-gray-700 hover:text-gray-900">Home</a>
                        <a href="#" class="py-5 px-3 text-gray-700 hover:text-gray-900">About</a>
                        <a href="#" class="py-5 px-3 text-gray-700 hover:text-gray-900">Services</a>
                        <a href="#" class="py-5 px-3 text-gray-700 hover:text-gray-900">Contact</a>
                    </div>
                </div>
                <!-- Secondary Nav -->
                <div class="hidden md:flex items-center space-x-1">
                    <a href="#" class="py-2 px-3 bg-orange-500 text-white rounded hover:bg-orange-600 transition duration-300">Book Free Consultation</a>
                </div>
                <!-- Mobile Button -->
                <div class="md:hidden flex items-center">
                    <button class="mobile-menu-button">
                        <i class="fas fa-bars"></i>
                    </button>
                </div>
            </div>
        </div>
    </nav>
    <!-- Mobile Menu -->
    <div class="mobile-menu hidden md:hidden">
        <a href="#" class="block py-2 px-4 text-sm hover:bg-gray-200">Home</a>
        <a href="#" class="block py-2 px-4 text-sm hover:bg-gray-200">About</a>
        <a href="#" class="block py-2 px-4 text-sm hover:bg-gray-200">Services</a>
        <a href="#" class="block py-2 px-4 text-sm hover:bg-gray-200">Contact</a>
        <a href="#" class="block py-2 px-4 text-sm bg-orange-500 text-white rounded hover:bg-orange-600 transition duration-300">Book Free Consultation</a>
    </div>
    <!-- Hero Section -->
    <section class="bg-white py-20">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <h1 class="text-4xl font-bold text-gray-800 montserrat">Welcome to Saniya Thrive Fitness</h1>
            <p class="mt-4 text-lg text-gray-600">Empowering you to nourish, move, thrive.</p>
            <a href="#" class="mt-6 inline-block bg-orange-500 text-white font-bold py-3 px-6 rounded-full montserrat hover:bg-orange-600 transition duration-300">Get Started</a>
        </div>
    </section>
    <!-- About Section -->
    <section class="bg-gray-100 py-20">
        <div class="max-w-7xl mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div>
                    <img src="assets/about.jpg" alt="Image of a fitness coach guiding a client in a gym setting" class="rounded-lg shadow-lg">
                </div>
                <div class="flex flex-col justify-center">
                    <h2 class="text-3xl font-bold text-gray-800 montserrat">About Saniya</h2>
                    <p class="mt-4 text-lg text-gray-600">Khan Saniya Shamim is a certified nutritionist and fitness coach with a passion for helping individuals achieve their health and fitness goals. With a PG Diploma from RJ College and a B.Sc. in Food Science from SNDT, Saniya combines her expertise in nutrition and fitness to provide personalized coaching and support.</p>
                    <a href="#" class="mt-6 inline-block bg-orange-500 text-white font-bold py-3 px-6 rounded-full montserrat hover:bg-orange-600 transition duration-300">Learn More</a>
                </div>
            </div>
        </div>
    </section>
    <!-- Services Section -->
    <section class="bg-white py-20">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold text-gray-800 montserrat">Our Services</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mt-8">
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <i class="fas fa-utensils text-green-600 text-4xl mb-4"></i>
                    <h3 class="text-xl font-bold text-gray-800 montserrat">Meal Plans</h3>
                    <p class="mt-2 text-gray-600">Customized meal plans to meet your nutritional needs and fitness goals.</p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <i class="fas fa-dumbbell text-green-600 text-4xl mb-4"></i>
                    <h3 class="text-xl font-bold text-gray-800 montserrat">Workouts</h3>
                    <p class="mt-2 text-gray-600">Personalized workout routines designed to help you achieve your fitness goals.</p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <i class="fas fa-chart-bar text-green-600 text-4xl mb-4"></i>
                    <h3 class="text-xl font-bold text-gray-800 montserrat">Macro Guides</h3>
                    <p class="mt-2 text-gray-600">Detailed macro guides to help you understand and manage your nutritional intake.</p>
                </div>
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <i class="fas fa-lightbulb text-green-600 text-4xl mb-4"></i>
                    <h3 class="text-xl font-bold text-gray-800 montserrat">Habit Coaching</h3>
                    <p class="mt-2 text-gray-600">Coaching to help you build and maintain healthy habits for long-term success.</p>
                </div>
            </div>
        </div>
    </section>
    <!-- Contact Section -->
    <section class="bg-gray-100 py-20">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold text-gray-800 montserrat">Get in Touch</h2>
            <p class="mt-4 text-lg text-gray-600">Ready to start your fitness journey? Contact us today to book your free consultation.</p>
            <a href="#" class="mt-6 inline-block bg-orange-500 text-white font-bold py-3 px-6 rounded-full montserrat hover:bg-orange-600 transition duration-300">Contact Us</a>
        </div>
    </section>
    <!-- Footer -->
    <footer class="bg-white py-8">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <p class="text-gray-600">© 2023 Saniya Thrive Fitness. All rights reserved.</p>
        </div>
    </footer>
    <script>
        const btn = document.querySelector('button.mobile-menu-button');
        const menu = document.querySelector('.mobile-menu');

        btn.addEventListener('click', () => {
            menu.classList.toggle('hidden');
        });
    </script>
</body>
</html>

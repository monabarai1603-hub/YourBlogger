social<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- SEO Meta Tags -->
    <title>TechScapes - Your Daily Dose of Tech, Travel, and Trends</title>
    <meta name="description" content="TechScapes is a modern, responsive blog featuring the latest articles on technology, travel destinations, and lifestyle trends. Optimized for search engines and ready for ad monetization.">
    <meta name="keywords" content="blog, technology, travel, lifestyle, responsive design, SEO, web development, free hosting">
    <meta name="author" content="Your Name">

    <!-- Open Graph Meta Tags (for social sharing) -->
    <meta property="og:title" content="TechScapes - Your Daily Dose of Tech, Travel, and Trends">
    <meta property="og:description" content="A modern, responsive blog featuring the latest articles on technology, travel, and more.">
    <meta property="og:image" content="https://placehold.co/1200x630/4f46e5/ffffff?text=TechScapes">
    <meta property="og:url" content="https://your-website-url.com">
    <meta property="og:type" content="website">

    <!-- Twitter Card Meta Tags -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="TechScapes - Your Daily Dose of Tech, Travel, and Trends">
    <meta name="twitter:description" content="A modern, responsive blog featuring the latest articles on technology, travel, and more.">
    <meta name="twitter:image" content="https://placehold.co/1200x630/4f46e5/ffffff?text=TechScapes">

    <!-- Favicon -->
    <link rel="icon" href="https://placehold.co/32x32/4f46e5/ffffff?text=T" type="image/png">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Google Fonts (Inter) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100 dark:bg-gray-900 text-gray-800 dark:text-gray-200">

    <!-- Main Container -->
    <div id="app" class="min-h-screen">

        <!-- Header -->
        <header class="bg-white dark:bg-gray-800 shadow-md sticky top-0 z-50">
            <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
                <!-- Logo -->
                <a href="#" class="text-2xl font-bold text-indigo-600 dark:text-indigo-400">TechScapes</a>
                
                <!-- Desktop Menu -->
                <div class="hidden md:flex items-center space-x-6">
                    <a href="#" class="text-gray-600 dark:text-gray-300 hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors">Home</a>
                    <a href="#" class="text-gray-600 dark:text-gray-300 hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors">Technology</a>
                    <a href="#" class="text-gray-600 dark:text-gray-300 hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors">Travel</a>
                    <a href="#" class="text-gray-600 dark:text-gray-300 hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors">About</a>
                    <a href="#" class="bg-indigo-600 text-white px-4 py-2 rounded-full hover:bg-indigo-700 transition-transform transform hover:scale-105">Subscribe</a>
                </div>

                <!-- Mobile Menu Button -->
                <div class="md:hidden">
                    <button id="mobile-menu-button" class="text-gray-600 dark:text-gray-300 focus:outline-none">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path>
                        </svg>
                    </button>
                </div>
            </nav>
            <!-- Mobile Menu -->
            <div id="mobile-menu" class="hidden md:hidden px-6 pt-2 pb-4 space-y-2">
                <a href="#" class="block text-gray-600 dark:text-gray-300 hover:text-indigo-600 dark:hover:text-indigo-400">Home</a>
                <a href="#" class="block text-gray-600 dark:text-gray-300 hover:text-indigo-600 dark:hover:text-indigo-400">Technology</a>
                <a href="#" class="block text-gray-600 dark:text-gray-300 hover:text-indigo-600 dark:hover:text-indigo-400">Travel</a>
                <a href="#" class="block text-gray-600 dark:text-gray-300 hover:text-indigo-600 dark:hover:text-indigo-400">About</a>
                <a href="#" class="block bg-indigo-600 text-white px-4 py-2 rounded-full hover:bg-indigo-700 text-center">Subscribe</a>
            </div>
        </header>

        <!-- Main Content -->
        <main class="container mx-auto px-6 py-8">
            <div class="flex flex-col md:flex-row -mx-4">

                <!-- Posts Column -->
                <div class="w-full md:w-2/3 px-4">
                    <!-- Featured Post -->
                    <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg overflow-hidden mb-8">
                        <a href="#">
                            <img src="https://placehold.co/800x400/6366f1/ffffff?text=Future+of+AI" alt="Featured post image about the future of AI" class="w-full h-64 object-cover">
                        </a>
                        <div class="p-6">
                            <a href="#" class="text-sm text-indigo-500 dark:text-indigo-400 font-semibold">Technology</a>
                            <h1 class="text-3xl font-bold mt-2 mb-4 text-gray-900 dark:text-white hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors">
                                <a href="#">The Uncharted Future of Artificial Intelligence</a>
                            </h1>
                            <p class="text-gray-600 dark:text-gray-300 mb-4">AI is evolving at an unprecedented pace. From transforming industries to raising ethical questions, we dive deep into what the next decade of artificial intelligence might look like.</p>
                            <div class="flex items-center text-sm text-gray-500 dark:text-gray-400">
                                <img src="https://placehold.co/40x40/a78bfa/ffffff?text=JD" alt="Author Jane Doe" class="w-10 h-10 rounded-full mr-3">
                                <span>By Jane Doe &middot; Aug 21, 2025</span>
                            </div>
                        </div>
                    </div>

                    <!-- Regular Posts Grid -->
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-8">
                        <!-- Post 1 -->
                        <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg overflow-hidden flex flex-col">
                            <a href="#"><img src="https://placehold.co/600x400/34d399/ffffff?text=Remote+Work" alt="A person working remotely from a scenic location" class="w-full h-48 object-cover"></a>
                            <div class="p-6 flex-grow">
                                <a href="#" class="text-sm text-emerald-500 dark:text-emerald-400 font-semibold">Lifestyle</a>
                                <h2 class="text-xl font-bold mt-2 mb-3 text-gray-900 dark:text-white hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors"><a href="#">Mastering the Art of Remote Work</a></h2>
                                <p class="text-gray-600 dark:text-gray-300 text-sm">Tips and tricks to stay productive, healthy, and connected while working from anywhere in the world.</p>
                            </div>
                        </div>
                        <!-- Post 2 -->
                        <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg overflow-hidden flex flex-col">
                            <a href="#"><img src="https://placehold.co/600x400/fbbf24/ffffff?text=Hidden+Gems" alt="A beautiful, hidden travel destination" class="w-full h-48 object-cover"></a>
                            <div class="p-6 flex-grow">
                                <a href="#" class="text-sm text-amber-500 dark:text-amber-400 font-semibold">Travel</a>
                                <h2 class="text-xl font-bold mt-2 mb-3 text-gray-900 dark:text-white hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors"><a href="#">5 Hidden Travel Gems to Visit in 2026</a></h2>
                                <p class="text-gray-600 dark:text-gray-300 text-sm">Forget the usual tourist traps. Discover these breathtaking locations before they become mainstream.</p>
                            </div>
                        </div>
                        <!-- Post 3 -->
                        <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg overflow-hidden flex flex-col">
                            <a href="#"><img src="https://placehold.co/600x400/ef4444/ffffff?text=Cybersecurity" alt="Abstract image representing cybersecurity" class="w-full h-48 object-cover"></a>
                            <div class="p-6 flex-grow">
                                <a href="#" class="text-sm text-red-500 dark:text-red-400 font-semibold">Technology</a>
                                <h2 class="text-xl font-bold mt-2 mb-3 text-gray-900 dark:text-white hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors"><a href="#">The Rise of Personal Cybersecurity</a></h2>
                                <p class="text-gray-600 dark:text-gray-300 text-sm">In a digital-first world, protecting your personal data is more important than ever. Here's how to start.</p>
                            </div>
                        </div>
                        <!-- Post 4 -->
                        <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg overflow-hidden flex flex-col">
                             <a href="#"><img src="https://placehold.co/600x400/3b82f6/ffffff?text=Web+3.0" alt="Abstract image representing Web 3.0 and blockchain" class="w-full h-48 object-cover"></a>
                            <div class="p-6 flex-grow">
                                <a href="#" class="text-sm text-blue-500 dark:text-blue-400 font-semibold">Technology</a>
                                <h2 class="text-xl font-bold mt-2 mb-3 text-gray-900 dark:text-white hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors"><a href="#">Demystifying Web 3.0 and the Blockchain</a></h2>
                                <p class="text-gray-600 dark:text-gray-300 text-sm">What is the next evolution of the internet? We break down the core concepts of Web 3.0 in simple terms.</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Sidebar Column -->
                <aside class="w-full md:w-1/3 px-4 mt-8 md:mt-0">
                    <!-- Ad Placeholder 1 -->
                    <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-4 mb-6 text-center">
                        <div class="bg-gray-200 dark:bg-gray-700 h-64 flex items-center justify-center rounded-lg">
                            <span class="text-gray-500 dark:text-gray-400">300x250 Ad Placeholder</span>
                        </div>
                    </div>

                    <!-- Categories Widget -->
                    <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6 mb-6">
                        <h3 class="text-xl font-bold mb-4 text-gray-900 dark:text-white">Categories</h3>
                        <ul class="space-y-2">
                            <li><a href="#" class="text-gray-600 dark:text-gray-300 hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors flex justify-between"><span>Technology</span> <span>(12)</span></a></li>
                            <li><a href="#" class="text-gray-600 dark:text-gray-300 hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors flex justify-between"><span>Travel</span> <span>(8)</span></a></li>
                            <li><a href="#" class="text-gray-600 dark:text-gray-300 hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors flex justify-between"><span>Lifestyle</span> <span>(5)</span></a></li>
                            <li><a href="#" class="text-gray-600 dark:text-gray-300 hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors flex justify-between"><span>Productivity</span> <span>(3)</span></a></li>
                        </ul>
                    </div>

                    <!-- Newsletter Widget -->
                    <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-6 mb-6">
                        <h3 class="text-xl font-bold mb-4 text-gray-900 dark:text-white">Join Our Newsletter</h3>
                        <p class="text-gray-600 dark:text-gray-300 mb-4">Get the latest articles and trends delivered straight to your inbox.</p>
                        <form>
                            <input type="email" placeholder="Your email address" class="w-full px-4 py-2 border border-gray-300 dark:border-gray-600 rounded-lg bg-gray-50 dark:bg-gray-700 focus:outline-none focus:ring-2 focus:ring-indigo-500">
                            <button type="submit" class="w-full mt-3 bg-indigo-600 text-white px-4 py-2 rounded-lg hover:bg-indigo-700 transition-colors">Subscribe</button>
                        </form>
                    </div>

                    <!-- Ad Placeholder 2 -->
                    <div class="bg-white dark:bg-gray-800 rounded-lg shadow-lg p-4 text-center sticky top-24">
                         <div class="bg-gray-200 dark:bg-gray-700 h-96 flex items-center justify-center rounded-lg">
                            <span class="text-gray-500 dark:text-gray-400">300x600 Skyscraper Ad</span>
                        </div>
                    </div>
                </aside>
            </div>
        </main>

        <!-- Footer -->
        <footer class="bg-white dark:bg-gray-800 border-t border-gray-200 dark:border-gray-700 mt-12">
            <div class="container mx-auto px-6 py-8">
                <div class="flex flex-col md:flex-row justify-between items-center">
                    <div class="text-center md:text-left mb-4 md:mb-0">
                        <p class="text-lg font-bold text-indigo-600 dark:text-indigo-400">TechScapes</p>
                        <p class="text-sm text-gray-500 dark:text-gray-400">&copy; 2025 All Rights Reserved.</p>
                    </div>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-500 hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors">
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z" clip-rule="evenodd" /></svg>
                        </a>
                        <a href="#" class="text-gray-500 hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors">
                             <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.71v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84" /></svg>
                        </a>
                         <a href="#" class="text-gray-500 hover:text-indigo-600 dark:hover:text-indigo-400 transition-colors">
                            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M12 2C6.477 2 2 6.477 2 12.019c0 4.438 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.009-.868-.014-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.031-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.203 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.338 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.001 10.001 0 0022 12.019C22 6.477 17.523 2 12 2z" clip-rule="evenodd" /></svg>
                        </a>
                    </div>
                </div>
            </div>
        </footer>

    </div>

    <script>
        // Mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
    </script>

</body>
</html>

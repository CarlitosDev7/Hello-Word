<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>NYC Elite | Luxury Travel Agency</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .hero {
            background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://images.unsplash.com/photo-1496442226666-8d18825847f2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80');
            background-size: cover;
            background-position: center;
        }
        
        .destination-card:hover .destination-overlay {
            opacity: 1;
            transform: translateY(0);
        }
        
        .testimonial-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
        
        .parallax {
            background-attachment: fixed;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
        }
    </style>
</head>
<body class="font-sans antialiased text-gray-800">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg fixed w-full z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-20">
                <div class="flex items-center">
                    <div class="flex-shrink-0 flex items-center">
                        <i class="fas fa-crown text-2xl text-yellow-500 mr-2"></i>
                        <span class="text-xl font-bold text-gray-900">NYC Elite</span>
                    </div>
                </div>
                <div class="hidden md:ml-6 md:flex md:items-center md:space-x-8">
                    <a href="#" class="text-gray-900 hover:text-yellow-500 px-3 py-2 text-sm font-medium">Home</a>
                    <a href="#destinations" class="text-gray-500 hover:text-yellow-500 px-3 py-2 text-sm font-medium">Destinations</a>
                    <a href="#services" class="text-gray-500 hover:text-yellow-500 px-3 py-2 text-sm font-medium">Services</a>
                    <a href="#about" class="text-gray-500 hover:text-yellow-500 px-3 py-2 text-sm font-medium">About</a>
                    <a href="#contact" class="text-gray-500 hover:text-yellow-500 px-3 py-2 text-sm font-medium">Contact</a>
                    <a href="#" class="bg-yellow-500 hover:bg-yellow-600 text-white px-4 py-2 rounded-md text-sm font-medium transition duration-300">Book Now</a>
                </div>
                <div class="-mr-2 flex items-center md:hidden">
                    <button type="button" class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-yellow-500" aria-controls="mobile-menu" aria-expanded="false" id="mobile-menu-button">
                        <span class="sr-only">Open main menu</span>
                        <i class="fas fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile menu -->
        <div class="hidden md:hidden" id="mobile-menu">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#" class="block px-3 py-2 text-base font-medium text-gray-900 hover:text-yellow-500">Home</a>
                <a href="#destinations" class="block px-3 py-2 text-base font-medium text-gray-500 hover:text-yellow-500">Destinations</a>
                <a href="#services" class="block px-3 py-2 text-base font-medium text-gray-500 hover:text-yellow-500">Services</a>
                <a href="#about" class="block px-3 py-2 text-base font-medium text-gray-500 hover:text-yellow-500">About</a>
                <a href="#contact" class="block px-3 py-2 text-base font-medium text-gray-500 hover:text-yellow-500">Contact</a>
                <a href="#" class="block w-full text-center bg-yellow-500 hover:bg-yellow-600 text-white px-4 py-2 rounded-md text-base font-medium transition duration-300">Book Now</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero h-screen flex items-center justify-center text-white pt-20">
        <div class="text-center px-4 sm:px-6 lg:px-8 max-w-4xl mx-auto">
            <h1 class="text-4xl md:text-6xl font-bold mb-6">Experience Luxury Travel Like Never Before</h1>
            <p class="text-lg md:text-xl mb-8">NYC Elite crafts bespoke travel experiences for the discerning traveler. From private jets to secluded villas, we make your dream vacation a reality.</p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#" class="bg-yellow-500 hover:bg-yellow-600 text-white px-8 py-3 rounded-md text-lg font-semibold transition duration-300">Explore Destinations</a>
                <a href="#" class="bg-transparent hover:bg-white hover:text-gray-900 border-2 border-white text-white px-8 py-3 rounded-md text-lg font-semibold transition duration-300">Contact Us</a>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="bg-gray-100 py-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 text-center">
                <div class="p-6">
                    <div class="text-4xl font-bold text-yellow-500 mb-2">15+</div>
                    <div class="text-gray-600">Years of Experience</div>
                </div>
                <div class="p-6">
                    <div class="text-4xl font-bold text-yellow-500 mb-2">500+</div>
                    <div class="text-gray-600">Luxury Destinations</div>
                </div>
                <div class="p-6">
                    <div class="text-4xl font-bold text-yellow-500 mb-2">10K+</div>
                    <div class="text-gray-600">Satisfied Clients</div>
                </div>
                <div class="p-6">
                    <div class="text-4xl font-bold text-yellow-500 mb-2">24/7</div>
                    <div class="text-gray-600">Concierge Service</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Featured Destinations -->
    <section id="destinations" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Featured Destinations</h2>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">Discover our handpicked selection of the world's most exclusive destinations, tailored for the elite traveler.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Destination 1 -->
                <div class="destination-card relative overflow-hidden rounded-lg shadow-lg group">
                    <img src="https://images.unsplash.com/photo-1518391846015-55a9cc003b25?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" alt="Maldives" class="w-full h-80 object-cover">
                    <div class="destination-overlay absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-0 group-hover:opacity-100 transition duration-500 flex flex-col justify-end p-6">
                        <h3 class="text-2xl font-bold text-white mb-2">Maldives</h3>
                        <p class="text-gray-200 mb-4">Private overwater villas with direct ocean access and personal butler service.</p>
                        <a href="#" class="text-yellow-400 hover:text-yellow-300 font-medium">Explore Packages <i class="fas fa-arrow-right ml-2"></i></a>
                    </div>
                </div>
                
                <!-- Destination 2 -->
                <div class="destination-card relative overflow-hidden rounded-lg shadow-lg group">
                    <img src="https://images.unsplash.com/photo-1520250497591-112f2f40a3f4?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" alt="Santorini" class="w-full h-80 object-cover">
                    <div class="destination-overlay absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-0 group-hover:opacity-100 transition duration-500 flex flex-col justify-end p-6">
                        <h3 class="text-2xl font-bold text-white mb-2">Santorini</h3>
                        <p class="text-gray-200 mb-4">Exclusive cliffside suites with private infinity pools overlooking the caldera.</p>
                        <a href="#" class="text-yellow-400 hover:text-yellow-300 font-medium">Explore Packages <i class="fas fa-arrow-right ml-2"></i></a>
                    </div>
                </div>
                
                <!-- Destination 3 -->
                <div class="destination-card relative overflow-hidden rounded-lg shadow-lg group">
                    <img src="https://images.unsplash.com/photo-1566073771259-6a8506099945?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" alt="Aspen" class="w-full h-80 object-cover">
                    <div class="destination-overlay absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-0 group-hover:opacity-100 transition duration-500 flex flex-col justify-end p-6">
                        <h3 class="text-2xl font-bold text-white mb-2">Aspen</h3>
                        <p class="text-gray-200 mb-4">Luxury ski-in/ski-out chalets with private chefs and spa facilities.</p>
                        <a href="#" class="text-yellow-400 hover:text-yellow-300 font-medium">Explore Packages <i class="fas fa-arrow-right ml-2"></i></a>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#" class="inline-flex items-center px-6 py-3 border border-transparent text-base font-medium rounded-md shadow-sm text-white bg-gray-900 hover:bg-gray-800 transition duration-300">
                    View All Destinations
                    <i class="fas fa-arrow-right ml-3"></i>
                </a>
            </div>
        </div>
    </section>

    <!-- Luxury Services -->
    <section id="services" class="py-20 bg-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Our Luxury Services</h2>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">Beyond travel arrangements, we provide white-glove services that redefine luxury.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Service 1 -->
                <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <div class="text-yellow-500 mb-4">
                        <i class="fas fa-plane text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Private Jet Charter</h3>
                    <p class="text-gray-600">Access our global network of private aircraft for seamless, luxurious travel on your schedule.</p>
                </div>
                
                <!-- Service 2 -->
                <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <div class="text-yellow-500 mb-4">
                        <i class="fas fa-home text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Villa Concierge</h3>
                    <p class="text-gray-600">Exclusive access to the world's most spectacular private villas with full staff and amenities.</p>
                </div>
                
                <!-- Service 3 -->
                <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <div class="text-yellow-500 mb-4">
                        <i class="fas fa-utensils text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Gourmet Experiences</h3>
                    <p class="text-gray-600">Private chef services, Michelin-starred dining, and exclusive culinary adventures worldwide.</p>
                </div>
                
                <!-- Service 4 -->
                <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <div class="text-yellow-500 mb-4">
                        <i class="fas fa-ship text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Yacht Charter</h3>
                    <p class="text-gray-600">Luxury yacht rentals with full crew for private island-hopping and coastal exploration.</p>
                </div>
                
                <!-- Service 5 -->
                <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <div class="text-yellow-500 mb-4">
                        <i class="fas fa-ticket-alt text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">VIP Event Access</h3>
                    <p class="text-gray-600">Backstage passes, private tables, and exclusive invitations to the world's most sought-after events.</p>
                </div>
                
                <!-- Service 6 -->
                <div class="bg-white p-8 rounded-lg shadow-md hover:shadow-xl transition duration-300">
                    <div class="text-yellow-500 mb-4">
                        <i class="fas fa-heart text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-3">Romantic Getaways</h3>
                    <p class="text-gray-600">Bespoke honeymoons, anniversary trips, and romantic escapes in dream destinations.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Parallax Section -->
    <section class="parallax py-32" style="background-image: url('https://images.unsplash.com/photo-1531058020387-3be344556be6?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80')">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-white">
            <h2 class="text-3xl md:text-4xl font-bold mb-6">Tailored to Your Every Desire</h2>
            <p class="text-lg md:text-xl mb-8">At NYC Elite, we understand that true luxury lies in the details. Our travel designers craft completely customized itineraries that reflect your personal style and preferences.</p>
            <a href="#" class="inline-flex items-center px-6 py-3 border border-transparent text-base font-medium rounded-md shadow-sm text-gray-900 bg-yellow-500 hover:bg-yellow-600 transition duration-300">
                Request a Consultation
                <i class="fas fa-arrow-right ml-3"></i>
            </a>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Client Testimonials</h2>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">Don't just take our word for it. Here's what our elite clients have to say about their experiences.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="testimonial-card bg-gray-50 p-8 rounded-lg shadow-md transition duration-300">
                    <div class="flex items-center mb-4">
                        <div class="flex-shrink-0">
                            <i class="fas fa-quote-left text-yellow-500 text-2xl"></i>
                        </div>
                        <div class="ml-4">
                            <div class="text-lg font-medium text-gray-900">James & Sophia R.</div>
                            <div class="text-yellow-500">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">"NYC Elite arranged our dream honeymoon to Bora Bora. From the private seaplane transfer to the overwater bungalow with glass floors, every detail was perfection. We'll never use another travel agency."</p>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="testimonial-card bg-gray-50 p-8 rounded-lg shadow-md transition duration-300">
                    <div class="flex items-center mb-4">
                        <div class="flex-shrink-0">
                            <i class="fas fa-quote-left text-yellow-500 text-2xl"></i>
                        </div>
                        <div class="ml-4">
                            <div class="text-lg font-medium text-gray-900">Michael T.</div>
                            <div class="text-yellow-500">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">"The private yacht charter they arranged in the Mediterranean was beyond anything I could have imagined. The crew anticipated our every need, and the itinerary was perfectly tailored to our interests."</p>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="testimonial-card bg-gray-50 p-8 rounded-lg shadow-md transition duration-300">
                    <div class="flex items-center mb-4">
                        <div class="flex-shrink-0">
                            <i class="fas fa-quote-left text-yellow-500 text-2xl"></i>
                        </div>
                        <div class="ml-4">
                            <div class="text-lg font-medium text-gray-900">The Williams Family</div>
                            <div class="text-yellow-500">
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                                <i class="fas fa-star"></i>
                            </div>
                        </div>
                    </div>
                    <p class="text-gray-600 italic">"Our multi-generational safari in Tanzania was flawlessly executed. NYC Elite thought of everything - from kid-friendly activities to private dining under the stars. Worth every penny for the peace of mind."</p>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="lg:grid lg:grid-cols-2 lg:gap-16 items-center">
                <div class="mb-12 lg:mb-0">
                    <h2 class="text-3xl font-bold text-gray-900 mb-6">About NYC Elite</h2>
                    <p class="text-lg text-gray-600 mb-6">Founded in 2008, NYC Elite has established itself as the premier luxury travel agency for discerning clients who demand the very best in global travel experiences.</p>
                    <p class="text-lg text-gray-600 mb-6">Our team of travel designers includes former hotel general managers, cruise directors, and destination experts who leverage their insider knowledge to create unforgettable journeys.</p>
                    <p class="text-lg text-gray-600 mb-8">We maintain exclusive partnerships with the world's finest hotels, resorts, and service providers, ensuring our clients receive preferential treatment and access to experiences unavailable to the general public.</p>
                    <a href="#" class="inline-flex items-center px-6 py-3 border border-transparent text-base font-medium rounded-md shadow-sm text-white bg-gray-900 hover:bg-gray-800 transition duration-300">
                        Meet Our Team
                        <i class="fas fa-arrow-right ml-3"></i>
                    </a>
                </div>
                <div class="relative">
                    <img src="https://images.unsplash.com/photo-1551632811-561732d1e306?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2070&q=80" alt="Luxury Travel" class="rounded-lg shadow-xl w-full">
                    <div class="absolute -bottom-6 -right-6 bg-yellow-500 p-4 rounded-lg shadow-lg hidden md:block">
                        <div class="text-4xl font-bold text-white">15+</div>
                        <div class="text-white">Years of Excellence</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-900 mb-4">Ready to Begin Your Journey?</h2>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">Contact our luxury travel designers to start planning your next extraordinary experience.</p>
            </div>
            
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
                <div>
                    <form class="space-y-6">
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700">Full Name</label>
                            <input type="text" id="name" name="name" class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm py-3 px-4 focus:ring-yellow-500 focus:border-yellow-500">
                        </div>
                        
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700">Email Address</label>
                            <input type="email" id="email" name="email" class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm py-3 px-4 focus:ring-yellow-500 focus:border-yellow-500">
                        </div>
                        
                        <div>
                            <label for="phone" class="block text-sm font-medium text-gray-700">Phone Number</label>
                            <input type="tel" id="phone" name="phone" class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm py-3 px-4 focus:ring-yellow-500 focus:border-yellow-500">
                        </div>
                        
                        <div>
                            <label for="destination" class="block text-sm font-medium text-gray-700">Destination of Interest</label>
                            <select id="destination" name="destination" class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm py-3 px-4 focus:ring-yellow-500 focus:border-yellow-500">
                                <option>Select a destination</option>
                                <option>Maldives</option>
                                <option>Santorini</option>
                                <option>Aspen</option>
                                <option>Bora Bora</option>
                                <option>Other</option>
                            </select>
                        </div>
                        
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-700">Your Travel Vision</label>
                            <textarea id="message" name="message" rows="4" class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm py-3 px-4 focus:ring-yellow-500 focus:border-yellow-500"></textarea>
                        </div>
                        
                        <div>
                            <button type="submit" class="w-full flex justify-center items-center px-6 py-3 border border-transparent text-base font-medium rounded-md shadow-sm text-white bg-yellow-500 hover:bg-yellow-600 transition duration-300">
                                Submit Request
                                <i class="fas fa-paper-plane ml-3"></i>
                            </button>
                        </div>
                    </form>
                </div>
                
                <div>
                    <div class="bg-gray-50 p-8 rounded-lg shadow-md h-full">
                        <h3 class="text-xl font-bold text-gray-900 mb-6">Contact Information</h3>
                        
                        <div class="space-y-6">
                            <div class="flex items-start">
                                <div class="flex-shrink-0">
                                    <i class="fas fa-map-marker-alt text-yellow-500 text-xl mt-1"></i>
                                </div>
                                <div class="ml-4">
                                    <h4 class="text-lg font-medium text-gray-900">Our Office</h4>
                                    <p class="text-gray-600">200 Park Avenue, Suite 1500<br>New York, NY 10166</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="flex-shrink-0">
                                    <i class="fas fa-phone-alt text-yellow-500 text-xl mt-1"></i>
                                </div>
                                <div class="ml-4">
                                    <h4 class="text-lg font-medium text-gray-900">Phone</h4>
                                    <p class="text-gray-600">+1 (212) 555-0100</p>
                                    <p class="text-gray-500 text-sm">24/7 Concierge Line Available</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="flex-shrink-0">
                                    <i class="fas fa-envelope text-yellow-500 text-xl mt-1"></i>
                                </div>
                                <div class="ml-4">
                                    <h4 class="text-lg font-medium text-gray-900">Email</h4>
                                    <p class="text-gray-600">info@nycelite.com</p>
                                </div>
                            </div>
                            
                            <div class="flex items-start">
                                <div class="flex-shrink-0">
                                    <i class="fas fa-clock text-yellow-500 text-xl mt-1"></i>
                                </div>
                                <div class="ml-4">
                                    <h4 class="text-lg font-medium text-gray-900">Hours</h4>
                                    <p class="text-gray-600">Monday - Friday: 9am - 6pm EST<br>Saturday: By appointment</p>
                                </div>
                            </div>
                        </div>
                        
                        <div class="mt-8">
                            <h4 class="text-lg font-medium text-gray-900 mb-4">Follow Us</h4>
                            <div class="flex space-x-4">
                                <a href="#" class="text-gray-600 hover:text-yellow-500">
                                    <i class="fab fa-instagram text-2xl"></i>
                                </a>
                                <a href="#" class="text-gray-600 hover:text-yellow-500">
                                    <i class="fab fa-facebook text-2xl"></i>
                                </a>
                                <a href="#" class="text-gray-600 hover:text-yellow-500">
                                    <i class="fab fa-twitter text-2xl"></i>
                                </a>
                                <a href="#" class="text-gray-600 hover:text-yellow-500">
                                    <i class="fab fa-linkedin text-2xl"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Newsletter -->
    <section class="bg-gray-900 text-white py-16">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-2xl md:text-3xl font-bold mb-4">Join Our Exclusive Travel Circle</h2>
            <p class="text-lg text-gray-300 mb-8">Subscribe to receive curated luxury travel inspiration, exclusive offers, and insider access.</p>
            
            <form class="max-w-xl mx-auto">
                <div class="flex flex-col sm:flex-row gap-4">
                    <input type="email" placeholder="Your email address" class="flex-grow px-4 py-3 rounded-md focus:outline-none focus:ring-2 focus:ring-yellow-500 text-gray-900">
                    <button type="submit" class="px-6 py-3 border border-transparent text-base font-medium rounded-md shadow-sm text-gray-900 bg-yellow-500 hover:bg-yellow-600 transition duration-300">
                        Subscribe
                    </button>
                </div>
                <p class="text-sm text-gray-400 mt-3">We respect your privacy. Unsubscribe at any time.</p>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-gray-300 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <div class="flex items-center mb-4">
                        <i class="fas fa-crown text-2xl text-yellow-500 mr-2"></i>
                        <span class="text-xl font-bold text-white">NYC Elite</span>
                    </div>
                    <p class="text-sm">Crafting extraordinary travel experiences for the world's most discerning clients since 2008.</p>
                </div>
                
                <div>
                    <h3 class="text-white font-medium mb-4">Explore</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-sm hover:text-yellow-400 transition duration-300">Luxury Destinations</a></li>
                        <li><a href="#" class="text-sm hover:text-yellow-400 transition duration-300">Private Jet Charter</a></li>
                        <li><a href="#" class="text-sm hover:text-yellow-400 transition duration-300">Yacht Charter</a></li>
                        <li><a href="#" class="text-sm hover:text-yellow-400 transition duration-300">Villa Rentals</a></li>
                        <li><a href="#" class="text-sm hover:text-yellow-400 transition duration-300">Honeymoon Packages</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-white font-medium mb-4">Company</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-sm hover:text-yellow-400 transition duration-300">About Us</a></li>
                        <li><a href="#" class="text-sm hover:text-yellow-400 transition duration-300">Our Team</a></li>
                        <li><a href="#" class="text-sm hover:text-yellow-400 transition duration-300">Testimonials</a></li>
                        <li><a href="#" class="text-sm hover:text-yellow-400 transition duration-300">Blog</a></li>
                        <li><a href="#" class="text-sm hover:text-yellow-400 transition duration-300">Careers</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-white font-medium mb-4">Legal</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-sm hover:text-yellow-400 transition duration-300">Privacy Policy</a></li>
                        <li><a href="#" class="text-sm hover:text-yellow-400 transition duration-300">Terms of Service</a></li>
                        <li><a href="#" class="text-sm hover:text-yellow-400 transition duration-300">Booking Conditions</a></li>
                        <li><a href="#" class="text-sm hover:text-yellow-400 transition duration-300">Cookie Policy</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-gray-700 mt-12 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-sm mb-4 md:mb-0">© 2023 NYC Elite Luxury Travel. All rights reserved.</p>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-400 hover:text-yellow-400">
                        <i class="fab fa-instagram"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-yellow-400">
                        <i class="fab fa-facebook"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-yellow-400">
                        <i class="fab fa-twitter"></i>
                    </a>
                    <a href="#" class="text-gray-400 hover:text-yellow-400">
                        <i class="fab fa-linkedin"></i>
                    </a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        document.getElementById('mobile-menu-button').addEventListener('click', function() {
            const menu = document.getElementById('mobile-menu');
            if (menu.classList.contains('hidden')) {
                menu.classList.remove('hidden');
            } else {
                menu.classList.add('hidden');
            }
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                    
                    // Close mobile menu if open
                    const mobileMenu = document.getElementById('mobile-menu');
                    if (!mobileMenu.classList.contains('hidden')) {
                        mobileMenu.classList.add('hidden');
                    }
                }
            });
        });

        // Form submission handling (example)
        const contactForm = document.querySelector('form');
        if (contactForm) {
            contactForm.addEventListener('submit', function(e) {
                e.preventDefault();
                alert('Thank you for your inquiry! A luxury travel designer will contact you shortly.');
                this.reset();
            });
        }
    </script>
</body>
</html>

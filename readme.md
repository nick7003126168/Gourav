<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gourav Nath Shahdeo | AI Enthusiast</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Raleway:wght@300;400;600&display=swap">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Raleway', sans-serif;
            background-color: #f9f7f7;
            color: #112d4e;
        }
        .playfair {
            font-family: 'Playfair Display', serif;
        }
        .hero {
            background: linear-gradient(135deg, #dbe2ef 0%, #3f72af 100%);
        }
        .section-title {
            position: relative;
            display: inline-block;
        }
        .section-title:after {
            content: '';
            position: absolute;
            width: 50%;
            height: 3px;
            bottom: -8px;
            left: 0;
            background-color: hsl(213, 96%, 10%);
        }
    </style>
</head>
<body class="min-h-screen">
    <!-- Hero Section -->
    <section class="hero text-white py-20 md:py-32">
        <div class="container mx-auto px-6 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-10 md:mb-0 flex justify-center">
                <div class="w-64 h-64 rounded-full overflow-hidden border-4 border-white shadow-xl">
                    <img src="Screenshot_20250929_014633.jpg" alt="Gourav Nath Shahdeo" class="w-full h-full object-cover">
                </div>
            </div>
            <div class="md:w-1/2 text-center md:text-left">
                <h1 class="playfair text-4xl md:text-5xl font-bold mb-4">Gourav Nath Shahdeo</h1>
                <h2 class="text-xl md:text-2xl font-light mb-6">BCA Student | AI Enthusiast | Future Game Developer</h2>
                <p class="text-lg max-w-lg mx-auto md:mx-0">Exploring AI, Game Development, 3D Modeling, Graphics, and Cybersecurity.</p>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="section-title playfair text-3xl font-bold mb-12">About Me</h2>
            <div class="max-w-3xl mx-auto">
                <p class="text-lg mb-6">
                    I am a first-year BCA student in Artificial Intelligence at Bahra University with interests in cutting-edge technologies and creative development. Passionate about learning AI, game design, and security. Building my foundation for a future career in tech.
                </p>
            </div>
        </div>
    </section>

    <!-- Education Section -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="section-title playfair text-3xl font-bold mb-12">Education</h2>
            <div class="max-w-3xl mx-auto bg-white p-8 rounded-lg shadow-sm">
                <div class="flex flex-col md:flex-row mb-6 pb-6 border-b border-gray-200">
                    <div class="md:w-1/3 font-bold text-gray-600">2025 – Present</div>
                    <div class="md:w-2/3">
                        <h3 class="font-bold text-lg">BCA in Artificial Intelligence</h3>
                        <p class="text-gray-600">Bahra University</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="section-title playfair text-3xl font-bold mb-12">Skills</h2>
            <div class="max-w-3xl mx-auto grid md:grid-cols-2 gap-8">
                <div class="bg-gray-50 p-6 rounded-lg">
                    <h3 class="font-bold text-xl mb-4 text-gray-800">Technical Skills</h3>
                    <ul class="space-y-2">
                        <li class="flex items-center"><i class="fas fa-code mr-3 text-blue-500"></i> Python, C, C++</li>
                        <li class="flex items-center"><i class="fas fa-robot mr-3 text-blue-500"></i> AI & Machine Learning</li>
                        <li class="flex items-center"><i class="fas fa-gamepad mr-3 text-blue-500"></i> Unity, Unreal Engine</li>
                        <li class="flex items-center"><i class="fas fa-cube mr-3 text-blue-500"></i> Blender (3D Modeling)</li>
                        <li class="flex items-center"><i class="fas fa-paint-brush mr-3 text-blue-500"></i> Photoshop, Illustrator</li>
                        <li class="flex items-center"><i class="fas fa-lock mr-3 text-blue-500"></i> Cybersecurity Basics</li>
                        <li class="flex items-center"><i class="fas fa-globe mr-3 text-blue-500"></i> HTML, CSS, JavaScript</li>
                    </ul>
                </div>
                <div class="bg-gray-50 p-6 rounded-lg">
                    <h3 class="font-bold text-xl mb-4 text-gray-800">Soft Skills</h3>
                    <ul class="space-y-2">
                        <li class="flex items-center"><i class="fas fa-lightbulb mr-3 text-blue-500"></i> Problem Solving</li>
                        <li class="flex items-center"><i class="fas fa-users mr-3 text-blue-500"></i> Teamwork</li>
                        <li class="flex items-center"><i class="fas fa-palette mr-3 text-blue-500"></i> Creativity</li>
                        <li class="flex items-center"><i class="fas fa-random mr-3 text-blue-500"></i> Adaptability</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Interests Section -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="section-title playfair text-3xl font-bold mb-12">Interests</h2>
            <div class="max-w-3xl mx-auto">
                <div class="flex flex-wrap gap-4 justify-center">
                    <span class="bg-white px-4 py-2 rounded-full shadow-sm"><i class="fas fa-robot mr-2 text-blue-500"></i> Artificial Intelligence</span>
                    <span class="bg-white px-4 py-2 rounded-full shadow-sm"><i class="fas fa-gamepad mr-2 text-blue-500"></i> Game Development</span>
                    <span class="bg-white px-4 py-2 rounded-full shadow-sm"><i class="fas fa-cube mr-2 text-blue-500"></i> 3D Modeling</span>
                    <span class="bg-white px-4 py-2 rounded-full shadow-sm"><i class="fas fa-paint-brush mr-2 text-blue-500"></i> Graphic Design</span>
                    <span class="bg-white px-4 py-2 rounded-full shadow-sm"><i class="fas fa-lock mr-2 text-blue-500"></i> Cybersecurity</span>
                    <span class="bg-white px-4 py-2 rounded-full shadow-sm"><i class="fas fa-lightbulb mr-2 text-blue-500"></i> Technology Innovation</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="section-title playfair text-3xl font-bold mb-12">Projects</h2>
            <div class="max-w-3xl mx-auto text-center py-12">
                <p class="text-xl text-gray-600">No completed projects yet — exciting work coming soon!</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <h2 class="section-title playfair text-3xl font-bold mb-12">Contact</h2>
            <div class="max-w-3xl mx-auto">
                <div class="bg-white p-8 rounded-lg shadow-sm">
                    <div class="mb-8">
                        <h3 class="text-xl font-bold mb-4">Get in Touch</h3>
                        <p class="text-gray-600 mb-4">Feel free to reach out for collaborations or just to say hello!</p>
                        <p class="flex items-center"><i class="fas fa-envelope mr-3 text-blue-500"></i> nick7003126168@gmail.com</p>
                    </div>
                    <div class="flex space-x-4">
                        <a href="https://github.com/nick7003126168" class="w-10 h-10 rounded-full bg-gray-200 flex items-center justify-center hover:bg-blue-500 hover:text-white transition">
                            <i class="fab fa-github"></i>
                        </a>
                        <a href="https://www.linkedin.com/in/gourav-nath-shahdeo-288793387/" class="w-10 h-10 rounded-full bg-gray-200 flex items-center justify-center hover:bg-blue-500 hover:text-white transition">
                            <i class="fab fa-linkedin-in"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-6 text-center">
            <p>&copy; 2025. All rights reserved.</p>
        </div>
    </footer>

    <script>
        feather.replace();
    </script>
</body>
</html>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="styles.css">
</head>
<body class="bg-gray-50 font-serif">
    <!-- Navigation Bar -->
    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <a href="index.html" class="text-2xl font-bold text-teal-600">Kumar Satyadarshi</a>
                </div>
                <div class="flex items-center space-x-4">
                    <a href="index.html" class="text-gray-700 hover:text-teal-600 px-3 py-2 rounded-md">Home</a>
                    <a href="publications.html" class="text-gray-700 hover:text-teal-600 px-3 py-2 rounded-md">Publications</a>
                    <a href="notes.html" class="text-gray-700 hover:text-teal-600 px-3 py-2 rounded-md">Notes</a>
                    <a href="blog.html" class="text-gray-700 hover:text-teal-600 px-3 py-2 rounded-md">Blog</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="bg-gradient-to-r from-teal-500 to-blue-600 text-white py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h1 class="text-4xl md:text-5xl font-bold mb-4">Welcome to My Academic Website</h1>
            <p class="text-lg md:text-xl mb-6">Kumar Satyadarshi</p>
            <p class="text-base md:text-lg mb-8 max-w-2xl mx-auto">Explore my research in [your field, e.g., algebraic topology], teaching notes, publications, and mathematical insights.</p>
            <a href="#about" class="inline-block bg-white text-teal-600 font-semibold px-6 py-3 rounded-md hover:bg-gray-200 transition">Learn More</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">About Me</h2>
            <div class="flex flex-col md:flex-row gap-8">
                <div class="md:w-1/3">
                    <img src="assets/profile-placeholder.jpg" alt="Profile Photo" class="w-full rounded-lg shadow-md">
                </div>
                <div class="md:w-2/3">
                    <p class="text-gray-600 mb-4">I am a mathematician specializing in [your field, e.g., number theory, differential geometry]. My research focuses on [brief research description, e.g., modular forms and their applications].</p>
                    <p class="text-gray-600 mb-4">I am currently a [your position, e.g., Professor at University X], where I teach courses on [e.g., abstract algebra, calculus] and mentor students in mathematical research.</p>
                    <p class="text-gray-600">This website hosts my publications, lecture notes, and occasional blog posts on mathematical topics. Feel free to explore or contact me for collaborations.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Quick Links Section -->
    <section class="py-16 bg-gray-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">Explore My Work</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-lg shadow-md text-center">
                    <h3 class="text-xl font-semibold text-gray-700 mb-4">Publications</h3>
                    <p class="text-gray-600 mb-4">Browse my peer-reviewed papers and preprints.</p>
                    <a href="publications.html" class="inline-block text-teal-600 font-semibold hover:underline">View Publications</a>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md text-center">
                    <h3 class="text-xl font-semibold text-gray-700 mb-4">Notes</h3>
                    <p class="text-gray-600 mb-4">Access lecture notes and mathematical write-ups.</p>
                    <a href="notes.html" class="inline-block text-teal-600 font-semibold hover:underline">View Notes</a>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-md text-center">
                    <h3 class="text-xl font-semibold text-gray-700 mb-4">Blog</h3>
                    <p class="text-gray-600 mb-4">Read my insights on mathematics and research.</p>
                    <a href="blog.html" class="inline-block text-teal-600 font-semibold hover:underline">Read Blog</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <p class="mb-4">Contact: <a href="mailto:your.email@example.com" class="underline hover:text-teal-400">your.email@example.com</a></p>
            <p class="mb-4">
                <a href="https://orcid.org/your-orcid-id" target="_blank" class="underline hover:text-teal-400 mx-2">ORCID</a> |
                <a href="https://scholar.google.com/citations?user=your-id" target="_blank" class="underline hover:text-teal-400 mx-2">Google Scholar</a> |
                <a href="https://mathscinet.ams.org/mathscinet/MRAuthorID/your-id" target="_blank" class="underline hover:text-teal-400 mx-2">MathSciNet</a>
            </p>
            <p>© 2025 Dr. [Your Name]. All rights reserved.</p>
        </div>
    </footer>

    <!-- JavaScript for Smooth Scrolling -->
    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>

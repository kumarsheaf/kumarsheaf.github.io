<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Kumar Satyadarshi</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-50 font-serif">
    <!-- Navigation Bar -->
    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <a href="index.html" class="text-2xl font-bold text-teal-600">Kumar Satyadarshi</a>
                <div class="flex space-x-4">
                    <a href="index.html" class="text-gray-700 hover:text-teal-600 px-3 py-2">Home</a>
                    <a href="notes.html" class="text-gray-700 hover:text-teal-600 px-3 py-2">Notes</a>
                    <a href="blog.html" class="text-gray-700 hover:text-teal-600 px-3 py-2">Blog</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- About Section -->
    <section id="about" class="py-16 bg-white">
        <div class="max-w-4xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">About Me</h2>
            <div class="flex flex-col md:flex-row gap-8">
                <div class="md:w-1/3">
                    <img src="assets/profile-placeholder.jpg" alt="Profile Photo" class="w-full rounded shadow">
                </div>
                <div class="md:w-2/3">
                    <p class="text-gray-700 mb-4">
                        I have a keen interest in differential geometry and mathematical physics.
                    </p>
                    <p class="text-gray-700">
                        This website hosts notes and occasional blog posts on mathematical topics. Feel free to explore or contact me for collaborations.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Quick Links Section -->
    <section class="py-16 bg-gray-100">
        <div class="max-w-4xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-gray-800 mb-8 text-center">Explore My Work</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="bg-white p-6 rounded shadow text-center">
                    <h3 class="text-xl font-semibold text-gray-700 mb-4">Notes</h3>
                    <p class="text-gray-600 mb-4">Access lecture notes and mathematical write-ups.</p>
                    <a href="notes.html" class="text-teal-600 font-semibold hover:underline">View Notes</a>
                </div>
                <div class="bg-white p-6 rounded shadow text-center">
                    <h3 class="text-xl font-semibold text-gray-700 mb-4">Blog</h3>
                    <p class="text-gray-600 mb-4">Read my insights on mathematics and research.</p>
                    <a href="blog.html" class="text-teal-600 font-semibold hover:underline">Read Blog</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="max-w-4xl mx-auto px-4 text-center">
            <p class="mb-4">Contact: <a href="mailto:your.kumarsatyadarshi@gmail.com" class="underline hover:text-teal-400">your.email@example.com</a></p>
            <p>© 2025 Kumar Satyadarshi. All rights reserved.</p>
        </div>
    </footer>

    <!-- Smooth Scrolling -->
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

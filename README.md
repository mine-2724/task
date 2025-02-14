# task
abroad page 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Study MBBS Abroad | University Insights</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            overflow-x: hidden;
        }
        @keyframes marquee {
            from { transform: translateX(100%); }
            to { transform: translateX(-100%); }
        }
        .marquee-container {
            width: 100%;
            overflow: hidden;
            background: #facc15;
            color: #1e293b;
            font-weight: bold;
            position: relative;
            white-space: nowrap;
        }
        .scrolling-text {
            display: inline-block;
            padding: 10px;
            font-size: 1.2rem;
            animation: marquee 10s linear infinite;
        }
    </style>
</head>
<body class="bg-gradient-to-r from-blue-500 to-purple-600 text-white">
    
    <!-- Scrolling Text -->
    <div class="marquee-container">
        <div class="scrolling-text">🌍 Apply Now for MBBS Abroad - Limited Seats Available! 🌍</div>
    </div>
    
    <!-- Hero Section -->
    <section class="text-center py-20 px-6">
        <h1 class="text-5xl font-extrabold hover:scale-105 transition-transform">Study MBBS Abroad</h1>
        <p class="mt-4 text-lg opacity-90">Secure Your Admission in Top Medical Universities Worldwide</p>
        <button class="mt-6 px-8 py-3 bg-yellow-400 text-gray-900 font-bold rounded-full shadow-lg hover:bg-yellow-300 hover:scale-110 transition-transform">Apply Now</button>
    </section>
    
    <!-- Why Study MBBS Abroad -->
    <section class="container mx-auto my-12 p-8 bg-white text-gray-800 shadow-lg rounded-xl hover:shadow-2xl transition-shadow">
        <h2 class="text-3xl font-semibold text-center mb-6">Why Study MBBS Abroad?</h2>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6 text-lg">
            <div class="p-4 bg-gray-100 rounded-lg shadow hover:bg-gray-200 transition">✅ Affordable tuition fees</div>
            <div class="p-4 bg-gray-100 rounded-lg shadow hover:bg-gray-200 transition">✅ Globally recognized degrees</div>
            <div class="p-4 bg-gray-100 rounded-lg shadow hover:bg-gray-200 transition">✅ Modern infrastructure and facilities</div>
            <div class="p-4 bg-gray-100 rounded-lg shadow hover:bg-gray-200 transition">✅ Easy admission process</div>
        </div>
    </section>
    
    <!-- Top Countries -->
    <section class="container mx-auto my-12 p-8 bg-white text-gray-800 shadow-lg rounded-xl">
        <h2 class="text-3xl font-semibold text-center mb-6">Top Countries</h2>
        <div class="grid grid-cols-2 md:grid-cols-4 gap-6 text-center">
            <div class="p-6 bg-blue-100 rounded-lg shadow-lg hover:scale-105 transition-transform">🇷🇺 Russia</div>
            <div class="p-6 bg-blue-100 rounded-lg shadow-lg hover:scale-105 transition-transform">🇺🇿 Uzbekistan</div>
            <div class="p-6 bg-blue-100 rounded-lg shadow-lg hover:scale-105 transition-transform">🇰🇿 Kazakhstan</div>
            <div class="p-6 bg-blue-100 rounded-lg shadow-lg hover:scale-105 transition-transform">🇵🇭 Philippines</div>
            <div class="p-6 bg-blue-100 rounded-lg shadow-lg hover:scale-105 transition-transform">🇬🇪 Georgia</div>
            <div class="p-6 bg-blue-100 rounded-lg shadow-lg hover:scale-105 transition-transform">🇰🇬 Kyrgyzstan</div>
            <div class="p-6 bg-blue-100 rounded-lg shadow-lg hover:scale-105 transition-transform">🇪🇬 Egypt</div>
        </div>
    </section>
    
    <!-- Contact Form -->
    <section class="container mx-auto my-12 p-8 bg-white text-gray-800 shadow-lg rounded-xl">
        <h2 class="text-3xl font-semibold text-center mb-6">Apply Now</h2>
        <form class="flex flex-col gap-4 max-w-md mx-auto">
            <input type="text" placeholder="Full Name" class="p-3 border rounded-lg shadow hover:bg-gray-100 transition" required>
            <input type="email" placeholder="Email Address" class="p-3 border rounded-lg shadow hover:bg-gray-100 transition" required>
            <input type="tel" placeholder="Phone Number" class="p-3 border rounded-lg shadow hover:bg-gray-100 transition" required>
            <select class="p-3 border rounded-lg shadow hover:bg-gray-100 transition" required>
                <option value="">Select Preferred Country</option>
                <option>Russia</option>
                <option>Uzbekistan</option>
                <option>Kazakhstan</option>
                <option>Philippines</option>
                <option>Georgia</option>
                <option>Kyrgyzstan</option>
                <option>Egypt</option>
            </select>
            <button type="submit" class="p-3 bg-blue-600 text-white font-bold rounded-lg shadow-lg hover:bg-blue-500 hover:scale-110 transition-transform">Submit</button>
        </form>
    </section>
    
    <script>
        document.querySelector("form").addEventListener("submit", function(event) {
            event.preventDefault();
            alert("Thank you for applying! We will contact you soon.");
        });
    </script>
</body>
</html>


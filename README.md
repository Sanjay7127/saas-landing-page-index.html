# saas-landing-page-index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>SaaS Startup Landing Page</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Custom animations */
    .fade-in {
      animation: fadeIn 1s ease-in forwards;
      opacity: 0;
    }
    @keyframes fadeIn {
      to {
        opacity: 1;
      }
    }
  </style>
</head>
<body class="bg-white text-gray-900 font-sans leading-normal tracking-normal">

  <!-- Hero Section -->
  <section class="relative bg-gray-50 min-h-screen flex flex-col justify-center items-center px-6 text-center fade-in">
    <h1 class="text-4xl sm:text-5xl font-extrabold mb-4 max-w-3xl">
      Empower Your Business with Our SaaS Solution
    </h1>
    <p class="text-lg sm:text-xl mb-8 max-w-xl mx-auto text-gray-600">
      Streamline your workflow, increase productivity, and grow your business effortlessly.
    </p>
    <img src="https://via.placeholder.com/600x300" alt="Product screenshot" class="w-full max-w-4xl rounded-lg shadow-lg mx-auto" />
  </section>

  <!-- Features Section -->
  <section class="py-16 bg-white px-6 fade-in">
    <div class="max-w-6xl mx-auto">
      <h2 class="text-3xl font-bold text-center mb-12">Features</h2>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-10">
        <div class="flex flex-col items-center text-center space-y-4">
          <svg class="w-12 h-12 text-indigo-600" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round"><path d="M12 20l9-5-9-5-9 5 9 5z"/><path d="M12 12v8"/></svg>
          <h3 class="text-xl font-semibold">Scalable Architecture</h3>
          <p class="text-gray-600">Grow without limits with our scalable cloud infrastructure.</p>
        </div>
        <div class="flex flex-col items-center text-center space-y-4">
          <svg class="w-12 h-12 text-indigo-600" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><line x1="12" y1="6" x2="12" y2="12"/><line x1="12" y1="18" x2="12" y2="18"/></svg>
          <h3 class="text-xl font-semibold">24/7 Support</h3>
          <p class="text-gray-600">Our team is here to help you anytime, anywhere.</p>
        </div>
        <div class="flex flex-col items-center text-center space-y-4">
          <svg class="w-12 h-12 text-indigo-600" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round"><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/></svg>
          <h3 class="text-xl font-semibold">Easy Integration</h3>
          <p class="text-gray-600">Connect with your favorite tools seamlessly.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonial Slider -->
  <section class="py-16 bg-gray-50 px-6 fade-in">
    <div class="max-w-4xl mx-auto text-center">
      <h2 class="text-3xl font-bold mb-12">What Our Customers Say</h2>
      <div id="testimonial-slider" class="relative overflow-hidden">
        <div class="testimonial-slide opacity-100 transition-opacity duration-700 ease-in-out">
          <p class="text-lg italic text-gray-700">"This SaaS product transformed our business. Highly recommend!"</p>
          <p class="mt-4 font-semibold">- Jane Doe, CEO of StartupX</p>
        </div>
        <div class="testimonial-slide opacity-0 absolute top-0 left-0 w-full transition-opacity duration-700 ease-in-out">
          <p class="text-lg italic text-gray-700">"Excellent support and seamless integration."</p>
          <p class="mt-4 font-semibold">- John Smith, CTO of TechCorp</p>
        </div>
        <div class="testimonial-slide opacity-0 absolute top-0 left-0 w-full transition-opacity duration-700 ease-in-out">
          <p class="text-lg italic text-gray-700">"A must-have tool for any growing business."</p>
          <p class="mt-4 font-semibold">- Emily Johnson, Product Manager</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Pricing Plans -->
  <section class="py-16 bg-white px-6 fade-in">
    <div class="max-w-6xl mx-auto text-center">
      <h2 class="text-3xl font-bold mb-12">Pricing Plans</h2>
      <div class="grid grid-cols-1 sm:grid-cols-3 gap-8 max-w-4xl mx-auto">
        <div class="border rounded-lg p-6 shadow hover:shadow-lg transition-shadow duration-300">
          <h3 class="text-xl font-semibold mb-4">Basic</h3>
          <p class="text-4xl font-bold mb-4">$19<span class="text-base font-normal">/mo</span></p>
          <ul class="mb-6 text-gray-600 text-left space-y-2">
            <li>Up to 5 users</li>
            <li>Basic support</li>
            <li>All core features</li>
          </ul>
          <button class="bg-indigo-600 text-white px-6 py-2 rounded hover:bg-indigo-700 transition-colors duration-300">Get Started</button>
        </div>
        <div class="border-2 border-indigo-600 rounded-lg p-6 shadow-lg transform scale-105">
          <h3 class="text-xl font-semibold mb-4">Pro</h3>
          <p class="text-4xl font-bold mb-4">$49<span class="text-base font-normal">/mo</span></p>
          <ul class="mb-6 text-gray-600 text-left space-y-2">
            <li>Up to 25 users</li>
            <li>Priority support</li>
            <li>Advanced features</li>
          </ul>
          <button class="bg-indigo-600 text-white px-6 py-2 rounded hover:bg-indigo-700 transition-colors duration-300">Get Started</button>
        </div>
        <div class="border rounded-lg p-6 shadow hover:shadow-lg transition-shadow duration-300">
          <h3 class="text-xl font-semibold mb-4">Enterprise</h3>
          <p class="text-4xl font-bold mb-4">Custom</p>
          <ul class="mb-6 text-gray-600 text-left space-y-2">
            <li>Unlimited users</li>
            <li>Dedicated support</li>
            <li>Custom features</li>
          </ul>
          <button class="bg-indigo-600 text-white px-6 py-2 rounded hover:bg-indigo-700 transition-colors duration-300">Contact Us</button>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer with Email Signup -->
  <footer class="bg-gray-900 text-white py-12 px-6 fade-in">
    <div class="max-w-4xl mx-auto text-center">
      <h2 class="text-2xl font-semibold mb-4">Stay Updated</h2>
      <form class="flex flex-col sm:flex-row justify-center items-center max-w-md mx-auto" onsubmit="event.preventDefault(); alert('Thank you for signing up!');">
        <input type="email" placeholder="Enter your email" required class="w-full sm:flex-1 px-4 py-3 rounded text-gray-900 focus:outline-none focus:ring-2 focus:ring-indigo-500 mb-4 sm:mb-0 sm:mr-4" />
        <button type="submit" class="bg-indigo-600 px-6 py-3 rounded hover:bg-indigo-700 transition-colors duration-300">Subscribe</button>
      </form>
      <p class="mt-6 text-gray-400 text-sm">&copy; 2024 SaaS Startup. All rights reserved.</p>
    </div>
  </footer>

  <script>
    // Testimonial slider logic
    const slides = document.querySelectorAll('.testimonial-slide');
    let currentSlide = 0;
    setInterval(() => {
      slides[currentSlide].classList.remove('opacity-100');
      slides[currentSlide].classList.add('opacity-0');
      slides[currentSlide].classList.add('absolute');
      currentSlide = (currentSlide + 1) % slides.length;
      slides[currentSlide].classList.remove('opacity-0');
      slides[currentSlide].classList.remove('absolute');
      slides[currentSlide].classList.add('opacity-100');
    }, 5000);
  </script>

</body>
</html>

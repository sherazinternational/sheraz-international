# sheraz-international
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sheraz International</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/typed.js@2.0.12"></script>
</head>
<body class="bg-gray-50 text-gray-800 scroll-smooth">

  <!-- Hero Section -->
  <header class="relative h-screen bg-blue-800 text-white flex items-center justify-center overflow-hidden">
    <img src="https://images.unsplash.com/photo-1581091215367-48b8d75a73bc?auto=format&fit=crop&w=1470&q=80" 
         class="absolute inset-0 w-full h-full object-cover opacity-30">
    <div class="z-10 text-center px-6">
      <h1 class="text-5xl font-bold mb-4">Sheraz International</h1>
      <p class="text-2xl mb-6"> 
        <span id="typed-text"></span>
      </p>
      <div class="flex justify-center gap-4">
        <a href="#products" class="bg-white text-blue-800 px-6 py-3 rounded-lg font-semibold hover:bg-gray-100">Explore Products</a>
        <a href="#contact" class="bg-transparent border border-white px-6 py-3 rounded-lg font-semibold hover:bg-white hover:text-blue-800">Contact Us</a>
      </div>
    </div>
  </header>

  <script>
    var typed = new Typed('#typed-text', {
      strings: ['Precision in Every Instrument', 'Trusted Surgical Partner', 'Innovative Surgical Solutions'],
      typeSpeed: 60,
      backSpeed: 40,
      loop: true
    });
  </script>

  <!-- About Section -->
  <section id="about" class="p-12 max-w-6xl mx-auto">
    <h2 class="text-3xl font-bold text-center mb-8">About Us</h2>
    <p class="text-gray-600 text-center mb-8">
      Sheraz International has been delivering high-quality disposable and non-disposable surgical instruments for hospitals and clinics worldwide. 
      Our mission: Precision, reliability, and safety in every product.
    </p>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
      <div class="bg-white p-6 rounded shadow hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-2">Years of Experience</h3>
        <p class="text-blue-700 text-3xl font-bold">15+</p>
      </div>
      <div class="bg-white p-6 rounded shadow hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-2">Products Supplied</h3>
        <p class="text-blue-700 text-3xl font-bold">5000+</p>
      </div>
      <div class="bg-white p-6 rounded shadow hover:shadow-lg transition">
        <h3 class="text-xl font-semibold mb-2">Trusted Hospitals</h3>
        <p class="text-blue-700 text-3xl font-bold">120+</p>
      </div>
    </div>
  </section>

  <!-- Products Section -->
  <section id="products" class="p-12 bg-gray-100">
    <h2 class="text-3xl font-bold text-center mb-8">Our Products</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-6xl mx-auto">
      <div class="bg-white p-6 rounded shadow hover:scale-105 transition transform">
        <img src="https://images.unsplash.com/photo-1588776814546-35f53b5eac26?auto=format&fit=crop&w=600&q=80" alt="Disposable" class="rounded mb-4">
        <h3 class="text-xl font-semibold mb-2">Disposable Instruments</h3>
        <p>High-quality single-use surgical instruments ensuring hygiene and safety.</p>
      </div>
      <div class="bg-white p-6 rounded shadow hover:scale-105 transition transform">
        <img src="https://images.unsplash.com/photo-1581093588401-2d2d0b96e1c8?auto=format&fit=crop&w=600&q=80" alt="Non-Disposable" class="rounded mb-4">
        <h3 class="text-xl font-semibold mb-2">Non-Disposable Instruments</h3>
        <p>Durable, precision-engineered instruments designed for long-term use.</p>
      </div>
      <div class="bg-white p-6 rounded shadow hover:scale-105 transition transform">
        <img src="https://images.unsplash.com/photo-1607746882042-944635dfe10e?auto=format&fit=crop&w=600&q=80" alt="Custom" class="rounded mb-4">
        <h3 class="text-xl font-semibold mb-2">Custom Solutions</h3>
        <p>Specialized instruments tailored to meet your surgical requirements.</p>
      </div>
    </div>
  </section>

  <!-- Testimonials Section -->
  <section class="p-12 max-w-6xl mx-auto text-center">
    <h2 class="text-3xl font-bold mb-8">What Our Clients Say</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
      <div class="bg-white p-6 rounded shadow">
        <p class="italic mb-2">"Sheraz International delivers the highest quality instruments, every time!"</p>
        <p class="font-semibold">– Dr. Ayesha Khan</p>
      </div>
      <div class="bg-white p-6 rounded shadow">
        <p class="italic mb-2">"Reliable, precise, and professional service for all our surgical needs."</p>
        <p class="font-semibold">– Karachi General Hospital</p>
      </div>
      <div class="bg-white p-6 rounded shadow">
        <p class="italic mb-2">"Their custom solutions helped streamline our operations immensely."</p>
        <p class="font-semibold">– Dr. Omar Malik</p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="p-12 bg-blue-50 text-center">
    <h2 class="text-3xl font-bold mb-4">Contact Us</h2>
    <p class="mb-6">Reach out for inquiries, orders, or support. Our AI assistant is also available 24/7.</p>
    <form class="max-w-md mx-auto grid gap-4 bg-white p-6 rounded shadow">
      <input type="text" placeholder="Your Name" class="p-3 border rounded w-full">
      <input type="email" placeholder="Email" class="p-3 border rounded w-full">
      <textarea placeholder="Message" class="p-3 border rounded w-full"></textarea>
      <button type="submit" class="bg-blue-700 text-white px-6 py-3 rounded font-semibold hover:bg-blue-800">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-white p-6 text-center">
    <p>&copy; 2026 Sheraz International. All rights reserved.</p>
    <div class="mt-2 flex justify-center gap-4">
      <a href="#" class="hover:text-blue-400">LinkedIn</a>
      <a href="#" class="hover:text-blue-400">Facebook</a>
      <a href="#" class="hover:text-blue-400">Twitter</a>
    </div>
  </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ThoughtShare</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 overflow-x-hidden">

<nav class="bg-white shadow p-4 flex justify-between items-center">
  <div class="text-2xl font-bold text-purple-600">ThoughtShare</div>
  <ul class="flex space-x-6 text-gray-700 font-medium">
    <li><a href="#about" class="hover:text-purple-600">About</a></li>
    <li><a href="#services" class="hover:text-purple-600">Services</a></li>
    <li><a href="qutoe.html" class="hover:text-purple-600">Quotes</a></li>
    <li><a href="#" onclick="gotofunction2()" class="hover:text-purple-600">E-book</a></li>
    <li><a href="#" onclick="gotofunction()" class="hover:text-purple-600">Login</a></li>
  </ul>
</nav>

<header class="flex flex-col justify-center items-center text-center h-screen bg-gradient-to-r from-indigo-500 to-pink-500 text-white px-6">
  <h1 class="text-4xl md:text-5xl font-bold mb-4">Express. Share. Connect.</h1>
  <p class="text-lg mb-6 max-w-xl">Welcome to our community! We are a platform where individuals share their quotes, life experiences, and ideas. Engage with others, leave feedback, and contribute to a thriving hub of inspiration and knowledge.</p>
  <div class="text-6xl mt-10">✅</div>
</header>


<section id="about" class="py-20 px-6 bg-white">
  <div class="max-w-5xl mx-auto text-center">
    <h2 class="text-3xl font-bold mb-4 text-gray-800">About Us</h2>
    <div class="h-1 w-12 bg-orange-500 my-2 mx-auto"></div>
    <p class="text-gray-600">Welcome to our community! We are a platform where individuals share their quotes, life experiences, and ideas. Engage with others, leave feedback, and contribute to a thriving hub of inspiration and knowledge.</p>
  </div>
</section>

<section id="services" class="py-20 px-6 bg-gray-100">
  <div class="max-w-6xl mx-auto text-center">
    <h2 class="text-3xl font-bold mb-6 text-gray-800">Our Services</h2>
    <div class="h-1 w-16 bg-purple-500 mx-auto mb-10"></div>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-8">

      <!-- Quotes Service -->
      <div class="bg-white p-8 rounded-xl shadow-lg">
        <h3 class="text-2xl font-semibold text-purple-500 mb-4">📖 Quotes Sharing</h3>
        <p class="text-gray-600 mb-4">Explore a vast collection of quotes categorized by emotions, life situations, and literature. Share your own thoughts, discover daily inspirations, and connect with like-minded souls.</p>
        <a href="qutoe.html" class="bg-purple-500 text-white px-4 py-2 rounded hover:bg-purple-600">Explore Quotes</a>
      </div>

      <!-- E-Books Service -->
      <div class="bg-white p-8 rounded-xl shadow-lg">
        <h3 class="text-2xl font-semibold text-purple-500 mb-4">📚 E-Books Collection</h3>
        <p class="text-gray-600 mb-4">Dive into our growing library of free and curated e-books. From inspirational reads to literary classics, discover content that enlightens, entertains, and empowers.</p>
        <a href="ji.html" class="bg-purple-500 text-white px-4 py-2 rounded hover:bg-purple-600">View E-Books</a>
      </div>

      <!-- Poetry Service -->
      <div class="bg-white p-8 rounded-xl shadow-lg">
        <h3 class="text-2xl font-semibold text-purple-500 mb-4">📝 Poetry Section</h3>
        <p class="text-gray-600 mb-4">Immerse yourself in a world of emotions, metaphors, and lyrical beauty. Share your original poems or explore verses from writers around the world.</p>
        <a href="poertyu.html" class="bg-purple-500 text-white px-4 py-2 rounded hover:bg-purple-600">Read & Share Poetry</a>
      </div>

      <!-- Story Service -->
      <div class="bg-white p-8 rounded-xl shadow-lg">
        <h3 class="text-2xl font-semibold text-purple-500 mb-4">📖 Story Section</h3>
        <p class="text-gray-600 mb-4">Dive into compelling short stories, experiences, and fictional narratives. Share your stories with our community and get inspired by others.</p>
        <a href="poertyu.html" class="bg-purple-500 text-white px-4 py-2 rounded hover:bg-purple-600">Read & Share Stories</a>
      </div>

    </div>
  </div>
</section>

<!-- Reviews Section -->
<section id="reviews" class="py-20 px-6 bg-gray-100">
  <div class="max-w-6xl mx-auto text-center">
    <h4 class="text-xl font-semibold mb-4">What Our Users Say</h4>
    <div class="flex justify-center space-x-6">
      <div class="bg-white p-4 rounded-lg shadow-lg w-72">
        <p class="text-gray-700 italic">"ThoughtShare has been a great platform for expressing myself. I love how easy it is to share quotes and read others' experiences!"</p>
        <p class="font-semibold text-gray-800 mt-2">- makingmomrich</p>
      </div>
      <div class="bg-white p-4 rounded-lg shadow-lg w-72">
        <p class="text-gray-700 italic">"I found so much inspiration from the poetry section. A truly uplifting community!"</p>
        <p class="font-semibold text-gray-800 mt-2">- Riya</p>
      </div>
      <div class="bg-white p-4 rounded-lg shadow-lg w-72">
        <p class="text-gray-700 italic">"I love the diverse collection of quotes and stories. It feels like a space for everyone."</p>
        <p class="font-semibold text-gray-800 mt-2">- Rohan</p>
      </div>
    </div>
  </div>
</section>

<!-- Footer Section -->
<footer class="bg-purple-500 text-white py-6">
  <div class="max-w-6xl mx-auto text-center">
    <div class="flex justify-center space-x-6 mb-4">
      <a href="https://facebook.com" class="hover:text-gray-300">Facebook</a>
      <a href="https://in.linkedin.com/" class="hover:text-gray-300">linkdin</a>
      <a href="https://instagram.com" class="hover:text-gray-300">Instagram</a>
    </div>
    <p class="text-sm mb-4">© 2025 ThoughtShare. All Rights Reserved.</p>
    
    <!-- Footer Buttons -->
    <div class="flex justify-center space-x-6">
      <button onclick="scrollToTop()" class="bg-purple-600 hover:bg-purple-700 px-4 py-2 rounded text-white">Go to Top</button>
      <a href="#" class="bg-purple-600 hover:bg-purple-700 px-4 py-2 rounded text-white">Home</a>
    </div>
  </div>
</footer>

<!-- Scroll to Top Script -->
<script>
  function scrollToTop() {
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }
  function gotofunction(){
    window.location.href = "project.html";
  }
  function gotofunction2(){
    window.location.href = "ji.html";
  }
</script>

</body>
</html>

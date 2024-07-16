# NetBowser
<html>
  <head>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <title>Movie Streaming</title>
  </head>
  <body class="bg-gray-100 font-sans">
    <header class="bg-white shadow">
      <div class="container mx-auto flex justify-between items-center py-4 px-6">
        <div class="text-xl font-bold text-green-600">MovieLify</div>
        <nav class="space-x-4">
          <a href="#" class="text-gray-800">Home</a>
          <a href="#" class="text-gray-800">Browse</a>
          <a href="#" class="text-gray-800">Login</a>
        </nav>
        <div class="relative">
          <input type="text" class="border rounded-full py-2 pl-8 pr-4 w-64" placeholder="Search...">
          <i class="fas fa-search absolute left-3 top-3 text-gray-600"></i>
        </div>
      </div>
    </header>
    <main class="container mx-auto py-6 px-6">
      <div class="grid grid-cols-3 gap-6">
        <div class="col-span-2 bg-white rounded shadow p-4">
          <div class="relative">
            <img src="https://placehold.co/900x400" alt="House of the Dragon poster with two characters standing against a dragon backdrop." class="w-full rounded">
            <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center text-white">
              <div>
                <h2 class="text-2xl font-bold">House of the Dragon</h2>
                  <div class="flex items-center mt-2">
                    <span class="mr-2"><i class="fas fa-star text-yellow-400"></i> 9.5</span>
                    <span class="bg-green-600 px-2 py-1 rounded-full">HD</span>
                  </div>
              </div>
            </div>
          </div>
          <p class="mt-4 text-gray-700">With a stable internet connection and a smart device, you can access thousands of movies and TV shows to watch online for free via 123Movies or its thriving attached, and you’ll be granted access to an array of titles...</p>
        </div>
        <div class="bg-white rounded shadow p-4">
          <h3 class="text-xl font-bold mb-4">Trending Now</h3>
          <div class="flex flex-col space-y-4">
            <div class="flex space-x-4">
              <img src="https://placehold.co/70x100" alt="Poster of Godzilla: King of the Monsters" class="w-16 rounded">
              <div>
                <h4 class="text-lg font-semibold">Godzilla: King - The New Empire</h4>
                <p class="text-gray-600">12K Views</p>
              </div>
            </div>
            <div class="flex space-x-4">
              <img src="https://placehold.co/70x100" alt="Poster of The Idol" class="w-16 rounded">
              <div>
                <h4 class="text-lg font-semibold">The Idol</h4>
                <p class="text-gray-600">9K Views</p>
              </div>
            </div>
            <div class="flex space-x-4">
              <img src="https://placehold.co/70x100" alt="Poster of The Old You" class="w-16 rounded">
              <div>
                <h4 class="text-lg font-semibold">The Old You</h4>
                <p class="text-gray-600">8K Views</p>
              </div>
            </div>
            <div class="flex space-x-4">
              <img src="https://placehold.co/70x100" alt="Poster of Castle Mixout" class="w-16 rounded">
              <div>
                <h4 class="text-lg font-semibold">Castle Mixout</h4>
                <p class="text-gray-600">7K Views</p>
              </div>
            </div>
            <div class="flex space-x-4">
              <img src="https://placehold.co/70x100" alt="Poster of Godzilla Minus One" class="w-16 rounded">
              <div>
                <h4 class="text-lg font-semibold">Godzilla Minus One</h4>
                <p class="text-gray-600">5K Views</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="mt-6">
        <h3 class="text-2xl font-bold mb-4">Trending</h3>
        <div class="grid grid-cols-6 gap-4">
          <div class="bg-white rounded shadow p-4 flex flex-col items-center">
            <img src="https://placehold.co/150x220" alt="Poster of Black Widow" class="w-full rounded">
            <h4 class="mt-2 text-lg font-semibold text-center">Black Widow</h4>
            <p class="text-center text-green-600">2021</p>
            <p class="text-center text-gray-600">MHD</p>
          </div>
          <div class="bg-white rounded shadow

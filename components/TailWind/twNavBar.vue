<template>
  <div>
    <nav id="navbar" class="sticky top-0 right-0 left-0 h-20 bg-white flex justify-between items-center py-4 px-6 shadow-2xl">
     <NuxtLink to="/test-123" class="logo">
        <h1 class="font-bold">
          <span class="jab">Jab</span><span class="tv text-red-600">TV</span>
          <span class="fist">&#x1F44A;</span>
        </h1>
      </NuxtLink>
      <ul class="fixed right-44">
        <li class="nav-item h-10 ml-8 rounded-lg hover:bg-yellow-400 bg-yellow-300 text-center pt-2 w-32">
         <NuxtLink to="/about" class="m-4 font-light" id="nav-link">About</NuxtLink>
        </li>
        <li class="nav-item h-10 ml-8 rounded-lg hover:bg-yellow-400 bg-yellow-300 text-center pt-2 w-32">
          <NuxtLink to="/stars" class="m-4 font-light" id="nav-link">BoxingStars</NuxtLink>
        </li>
        <li class="nav-item h-10 ml-8 rounded-lg hover:bg-yellow-400 bg-yellow-300 text-center pt-2 w-32">
          <a href="#stakeholders" class="m-4 font-light" id="nav-link">Stakeholders</a>
        </li>
        <li class="nav-item h-10 ml-8 rounded-lg hover:bg-yellow-400 bg-yellow-300 text-center pt-2 w-32">
          <a href="#sub" class="m-4 font-light" id="nav-link">Subscribe</a>
        </li>
      </ul>
      <div class="hamburger" id="hamburger">
        <span class="bar"></span>
        <span class="bar"></span>
        <span class="bar"></span>
      </div>
    </nav>
  </div>
</template>

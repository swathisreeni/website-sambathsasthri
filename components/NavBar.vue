<template>
  <div>
    <nav id="navbar" class="sticky top-0 right-0 left-0 h-20 bg-yellow-900 flex justify-between items-center py-4 px-6 shadow-2xl">
     <NuxtLink to="/home" class="logo ml-36 pl-2">
        <h1 class="text-white">
          <span class="fname capitalize">SambathSastri</span>
          <span class="fist">&#x1F44A;</span>
        </h1>
      </NuxtLink>
      <ul class="fixed right-44 font-bold text-yellow-900">
        <li class="nav-item h-10 ml-8 rounded-lg hover:bg-white  bg-yellow-300 text-center pt-2 w-32">
         <NuxtLink to="/home" class="block hover:text-blue-400" id="nav-link">Home</NuxtLink>
        </li>
        <li class="nav-item h-10 ml-8 rounded-lg hover:bg-white  bg-yellow-300 text-center pt-2 w-32">
          <NuxtLink to="/about" class="block hover:text-blue-400" id="nav-link">About</NuxtLink>
        </li>
        <li class="nav-item h-10 ml-8 rounded-lg hover:bg-yellow-400 bg-yellow-300 text-center pt-2 w-32">
          <NuxtLink to="/services" class="m-4" id="nav-link">Services</NuxtLink>
        </li>
        <li class="nav-item h-10 ml-8 rounded-lg hover:bg-yellow-400 bg-yellow-300 text-center pt-2 w-32">
          <a href="#sub" class="m-4" id="nav-link">Subscribe</a>
        </li>
          <li class="nav-item h-10 ml-8 rounded-lg hover:bg-yellow-400 bg-yellow-300 text-center pt-2 w-32">
          <NuxtLink to="/contactus" class="m-4" id="nav-link">Contactus</NuxtLink>
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

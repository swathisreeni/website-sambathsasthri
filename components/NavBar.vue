<template>
  <div>
    <nav id="navbar">
     <NuxtLink to="/test-123" class="logo">
        <h1>
          <span class="jab">Jab</span><span class="tv">TV</span>
          <span class="fist">&#x1F44A;</span>
        </h1>
      </NuxtLink>
      <ul>
        <li class="nav-item">
         <NuxtLink to="/about" class="nav-link" id="nav-link">About</NuxtLink>
        </li>
        <li class="nav-item">
          <a href="#stars" class="nav-link" id="nav-link">Boxing Stars</a>
        </li>
        <li class="nav-item">
          <a href="#stakeholders" class="nav-link" id="nav-link">stakeholders</a>
        </li>
        <li class="nav-item">
          <a href="#sub" class="nav-link" id="nav-link">Subscribe</a>
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

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,400;0,900;1,700&display=swap");

/* CSS Variables */
:root {
  --normal-font: 400;
  --bold-font: 600;
  --bolder-font: 900;
  --primary-color: #0652dd;
  --secondary-color: #ea2027;
  --line-height: 1.7rem;
  --transition: 0.4s ease-in;
}

/* Smooth scroll effect */
html {
  scroll-behavior: smooth;
}

/* Resets */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  transition: var(--transition);
}

body {
  font-family: "Roboto", sans-serf;
}

ul li {
  list-style-type: none;
}

a {
  text-decoration: none;
  color: var(--primary-color);
}

a:hover {
  color: var(--secondary-color);
}

nav {
  background: #fff;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem 1.5rem;
  box-shadow: 2px 3px 2px #f1f1f1;
}
.logo {
  font-size: 2rem;
  font-weight: 500;
}

ul {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.nav-item {
  margin-left: 2rem;
}

.nav-link {
  font-weight: var(--bold-font);
}

.sticky {
  position: fixed;
  top: 0;
  width: 100%;
  z-index: 1;
}
</style>

<script>
export default {
  mounted () {
    window.onscroll = function () {
      myFunction()
    }
    // Get the navbar
    const navbar = document.getElementById('navbar')

    // Get the offset position of the navbar
    const sticky = navbar.offsetTop

    // Add the sticky class to the navbar when you reach its scroll position. Remove "sticky" when you leave the scroll position
    function myFunction () {
      if (window.pageYOffset >= sticky) {
        navbar.classList.add('sticky')
      } else {
        navbar.classList.remove('sticky')
      }
    }
  }
}
</script>

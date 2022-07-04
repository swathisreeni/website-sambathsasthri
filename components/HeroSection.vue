<template>
    <div>
    <section class="hero relative top-16">
      <div class="intro-text">
        <h1 class="font-bold">
          <span class="hear"> You can Hear the Jabs </span> <br />
          <span class="connecting"> Connecting</span>
        </h1>
        <p>
          An online streaming platform for boxing matches <br />
          We also dedicate some special time to throwbacks cuz old is gold
        </p>
        <a class="btn red" href="#">Learn More</a>
        <a class="btn blue" href="#">Subscribe</a>
      </div>
      <div class="i-frame">
        <iframe
          width="560"
          height="315"
          src="https://www.youtube.com/embed/sUmM_PFpsvQ"
          title="YouTube video player"
          frameborder="10"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        ></iframe>
        <div class="stand-1"></div>
        <div class="stand-2"></div>
      </div>
    </section>
    </div>
</template>

<style>
/* Hero section starts */
.hero {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1.9rem;
  /* max-width: 1100px; */
  margin: 2rem auto 0rem;
}

.intro-text h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
}

.intro-text h3 {
  margin-bottom: 0.5rem;
}

.hero p {
  line-height: var(--line-height);
}

.hear {
  color: var(--primary-color);
}

.connecting {
  color: var(--secondary-color);
}

.btn {
  margin-top: 1rem;
  display: inline-block;
  padding: 0.8rem 0.6rem;
  border: none;
  font-size: 1.4rem;
  border-radius: 5px;
  color: #fff;
}

.red {
  background-color: var(--secondary-color);
  margin-right: 1.5rem;
}

.red:hover {
  background-color: #f1262d;
  color: #fff;
}

.blue {
  background-color: var(--primary-color);
}

.blue:hover {
  background-color: #095cf7;
  color: #fff;
}

iframe {
  max-width: 30rem;
  border-top: 40px groove var(--primary-color);
  border-bottom: 40px groove var(--primary-color);
  border-right: 28px solid var(--secondary-color);
  border-left: 28px solid var(--secondary-color);
}

.stand-1 {
  height: 90px;
  width: 6px;
  background-color: var(--primary-color);
  transform: rotate(40deg);
  position: relative;
  top: -16px;
  left: 200px;
}
.stand-2 {
  height: 90px;
  width: 6px;
  background-color: var(--secondary-color);
  transform: rotate(-40deg);
  position: relative;
  top: -105px;
  left: 255px;
}
/* Hero section ends */
</style>

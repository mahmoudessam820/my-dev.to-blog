<template>
  <div>
    <section id="home" class="hero" aria-label="home">
      <div class="container">

        <div class="hero-content">

          <p class="hero-subtitle">Welcome To My Dev.to Blog</p>

          <h1 class="headline headline-1 section-title">
            I'm <span class="span">Mahmoud El-Kariouny</span>
          </h1>

          <p class="hero-text">

            I use animation as a third dimension by which to simplify experiences and kuiding thro each and every
            interaction. I’m not adding motion just to spruce things up, but doing it in ways that.

          </p>

          <div class="input-wrapper">

            <button class="btn btn-primary">
              <span class="span">My Resume</span>
              <ion-icon name="arrow-forward-outline" aria-hidden="true"></ion-icon>
            </button>

          </div>

        </div>


        <div class="hero-banner">

          <img src="../assets/images/img/hero/i-dev.png" alt="mahmoud" width="327" height="490" class="w-100" />

          <img src="../assets/images/img/hero/pattern-2.svg" width="27" height="26" alt="shape" class="shape shape-1" />

          <img src="../assets/images/img/hero/pattern-3.svg" width="27" height="26" alt="shape" class="shape shape-2" />

        </div>

        <img src="../assets/images/img/hero/shadow-1.svg" alt="" width="500" height="800" class="hero-bg hero-bg-1" />

        <img src="../assets/images/img/hero/shadow-2.svg" alt="" width="500" height="500" class="hero-bg hero-bg-2" />

      </div>
    </section>
  </div>
</template>

<script type="text/javascript">
export default {
  name: "TheHero",
};
</script>

<style scoped>
@import "../assets/css/the-hero-style.css";
</style>

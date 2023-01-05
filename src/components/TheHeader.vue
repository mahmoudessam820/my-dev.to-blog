<template>
  <div id="header">
    <header class="header" data-header>
      <div class="container">


        <a href="#" class="logo">
          <img src="../assets/images/logo/logo.png" width="60" height="37" alt="mahmoud-logo" />
        </a>

        <nav class="navbar" :class="[isActive ? '' : 'active']" data-navbar>

          <div class="navbar-top">

            <a href="#" class="logo">
              <img src="../assets/images/logo/logo.png" width="60" height="37" alt="mahmoud-logo" />
            </a>

            <button class="nav-close-btn" v-on:click="toggleClass()" aria-label="close menu" data-nav-toggler>
              <ion-icon name="close-outline" aria-hidden="true"></ion-icon>
            </button>

          </div>

          <ul class="navbar-list">

            <li>
              <a href="#home" class="navbar-link hover-1" data-nav-toggler>Home</a>
            </li>

            <li>
              <a href="#topics" class="navbar-link hover-1" data-nav-toggler>Topics</a>
            </li>

            <li>
              <a href="#featured" class="navbar-link hover-1" data-nav-toggler>Featured</a>
            </li>

            <li>
              <a href="#recent" class="navbar-link hover-1" data-nav-toggler>Recent</a>
            </li>

            <li>
              <a href="#" class="navbar-link hover-1" data-nav-toggler>Contact</a>
            </li>

          </ul>

          <div class="navbar-bottom">

            <div class="profile-card">

              <img src="../assets/images/img/author-1.png" class="profile-banner" width="48" height="48"
                alt="Mahmoud" />

              <div>
                <p class="card-title">Hi, Mahmoud!!</p>
                <p class="card-subtitle">
                  This is my Dev.to blog !!
                </p>
              </div>

            </div>

            <ul class="link-list">

              <li>
                <a href="#" class="navbar-bottom-link hover-1">My Portfolio</a>
              </li>

              <li>
                <a href="#" class="navbar-bottom-link hover-1">My Resume</a>
              </li>

              <li>
                <a href="#" class="navbar-bottom-link hover-1">GitHub</a>
              </li>

              <li>
                <a href="#" class="navbar-bottom-link hover-1">LinkdIn</a>
              </li>

              <li>
                <a href="#" class="navbar-bottom-link hover-1">Twitter</a>
              </li>

              <li>
                <a href="#" class="navbar-bottom-link hover-1">YouTube</a>
              </li>

            </ul>

          </div>

        </nav>

        <a href="#" class="btn btn-primary">Power By Dev.To</a>

        <button class="nav-open-btn" v-on:click="toggleClass()" aria-label="open menu" data-nav-toggler>
          <ion-icon name="menu-outline" aria-hidden="true"></ion-icon>
        </button>


      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: "TheHeader",
  data() {
    return {
      isActive: true,
    }
  },
  methods: {
    toggleClass: function () {
      this.isActive = !this.isActive;
    }
  },
};
</script>

<style scoped>
@import "../assets/css/the-header-style.css";
</style>

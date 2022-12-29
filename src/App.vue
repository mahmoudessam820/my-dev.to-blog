<template>
  <div id="nav">
    <TheHeader></TheHeader>
    <router-link to="/">Home</router-link>
    <router-link to="/about">About</router-link>
  </div>
  <router-view />
</template>

<script type="text/javascript">
import TheHeader from "@/components/TheHeader";

export default {
  name: "App",
  components: {
    TheHeader,
  },
}; 
</script>

<style leng="css">
@import "./assets/css/general-style.css";
</style>

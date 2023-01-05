<template>
  <div id="nav">
    <TheHeader></TheHeader>
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

<style leng="css" scoped>
@import "./assets/css/general-style.css";
</style>

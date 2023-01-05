<template>
  <div>
    <main>
      <article>

        <TheHero></TheHero>
        <TheTopics></TheTopics>

      </article>
    </main>
  </div>
</template>

<script type="text/javascript">
import TheHero from "@/components/TheHero.vue";
import TheTopics from "@/components/TheTopics.vue";

export default {
  name: "Home",
  components: {
    TheHero,
    TheTopics,
  }
};
</script>

<style type="text/css" scoped>

</style>
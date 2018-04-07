<template>
  <section>

      <header-box/>
      <theme/>
      <classified-nav/>
      

  </section>
</template>

<script>
// import AppLogo from "~/components/AppLogo.vue";
import HeaderBox from "~/components/HeaderBox.vue";
import Theme from "~/components/Theme.vue";
import ClassifiedNav from "~/components/ClassifiedNav.vue";

export default {
  components: {
    HeaderBox,
    Theme,
    ClassifiedNav
  }
};
</script>

<style>
.container {
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

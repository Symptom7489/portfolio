<template>
  <div class="app-container">
  <the-header />
  <router-view/>
  <the-footer />
  </div>


</template>

<script>
  import TheHeader from "@/components/TheHeader";
  import TheFooter from "@/components/TheFooter";

export default {

  name: 'HomeView',
  components: { TheHeader, TheFooter
  }
}
</script>

<style lang="scss">
@import "@/assets/scss/main.scss";

#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  font-family: "Lato", sans-serif;
  font-weight: 400;
  line-height: 1.7;
  color: $color-primary-font;

}

.app-container {
  display: flex;
  justify-content: space-between;
  flex-direction: column;
  height: 100%;
  background-image: linear-gradient(
          to right bottom,
          rgba($color-background, 0.8),
          rgba($color-background-alt,0.8));


}

</style>

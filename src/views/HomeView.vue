<template>
  <main class="main">
    <div class="main__hello">
      <h1 class="main__hello__title"> Hello, I'm Ryan. <br> I'm a programmer.</h1> <br>
      <h3 class="main__hello__info"> I have 3 years of programming experience. <br>
      </h3>
    </div>
    <div class="main__skills">
      Lack of skills
    </div>
    <div class="main__projects">
      Bad projects
    </div>
  </main>


</template>

<script>

export default {

  name: 'HomeView',
  components: {
  }
}
</script>

<style lang="scss">
@import "@/assets/scss/main.scss";

.main {
  display: flex;
  justify-content: space-between;
  flex-direction: column;
  margin: 0 15%;
  padding: 2rem 0;
  height: 100%;

}

</style>

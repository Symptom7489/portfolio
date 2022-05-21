<template>
  <main class="main">


    <div class="main__hello">
      <h1 class="main__hello__title"> Hello, I'm Ryan. <br> I'm a programmer.</h1> <br>
      <h3 class="main__hello__info"> I have 3 years of programming experience. <br>
        I strive to create user-friendly, quality applications and websites with trusted and tested backend frameworks.
      </h3>
      <hr class="line-break">
    </div>

    <div class="main__projects">

    <base-card />
    <base-card />
      <base-card />





    </div>
  </main>


</template>

<script>
import BaseCard from "@/components/BaseCard";
export default {

  name: 'HomeView',
  components: {BaseCard
  }
}
</script>

<style lang="scss">
@import "@/assets/scss/main.scss";

.main {
  display: flex;
  justify-content: flex-start;
  flex-direction: column;
  align-items: center;
  margin: 0 15%;
  padding: 2rem 0;
  height: 100%;

  &__hello {
    width: 100ch;
text-align: left;
    &__title {
      font-size: $font-heading-1;
    }

    &__info {

      font-size: $font-heading-4;
    }

  }

}
.line-break {
  margin-top: 1rem;
  border: 5px dotted $color-secondary-light;
  border-bottom: none;
}

.main__projects {
  display: flex;
  flex-direction: column;
  justify-content:space-between;
  margin-top: 3rem;
  margin: 0 15%;

}



</style>

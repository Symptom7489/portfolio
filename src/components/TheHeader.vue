<template>
  <header class="header ">
    <img class="header__dice-image" src="@/assets/images/dice-149395.svg" alt="d20-image">
        <div class="links">
      <ul class="links__list">
        <li class=" links__list-item">Resume</li>
        <li class=" links__list-item">About Me</li>
        <li class=" links__list-item">Projects</li>
      </ul>
    </div>
  </header>
</template>

<script>
export default {
  name: "TheHeader"
}
</script>

<style scoped lang="scss">
@import "@/assets/scss/main.scss";

.header {
  background-color:transparent;
  font-size: 2rem;
  color: $color-secondary-font;

  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 0 15%;

  &__dice-image {
    width: 5rem;
    margin: 1rem 1rem;
  }

&__title {
  font-size: 3.2rem;
  color: $color-accent-font;
  text-shadow: 1px 1px black;
}
}

.links {
  margin: 1rem 1rem;
  font-size: 1.6rem;


  &__list {
    list-style: none;
    display: flex;
    gap: 2rem;
    }
}

</style>
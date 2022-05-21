<template>
<div class="project">

        <div class="project__frontend">

          <div class="project-image-container">

            <img src="../assets/images/natoursSS.png" alt="Natours-Screenshot" class="project-image-front">
            <ul>
              <li>Cool Stuff I did</li>
              <li>Cool Stuff I did</li>
              <li>Cool Stuff I did</li>
              <li>Cool Stuff I did</li>
              <li>Cool Stuff I did</li>
            </ul>
          </div>
        </div>

        <div class="project__backend">
          <div class="project-image-container"> <img src="../assets/images/codeSS.png" alt="Natours-Screenshot" class="project-image-back">
            <ul>
              <li>Cool Stuff I did</li>
              <li>Cool Stuff I did</li>
              <li>Cool Stuff I did</li>
              <li>Cool Stuff I did</li>
              <li>Cool Stuff I did</li>
            </ul>
          </div>

        </div>
      </div>
</template>

<script>
export default {
  name: "BaseCard"
}
</script>

<style scoped lang="scss">
@import "@/assets/scss/main.scss";
.project {
  border-radius: 10px;
  margin: 5rem 0;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  gap: 5rem;
  padding: 5rem;
  background-color: $color-background-secondary;
}

.project-image-front {
  border-radius: 5px;
  width: 30rem;
  transition: all .3s ease;
  box-shadow: $box-shadow-small;
  margin-bottom: 2rem;

  &:hover {
  transform: scale(2) translateX(75px);
    box-shadow: $box-shadow-medium;
   }
}

.project-image-back {
  border-radius: 5px;
  width: 30rem;
  transition: all .3s ease;
  box-shadow: $box-shadow-small;
  margin-bottom: 2rem;
;

  &:hover {
  transform: scale(2) translateX(-75px);
    box-shadow: $box-shadow-medium;
   }
}

ul {
  list-style-type: none;
  font-size: $font-heading-5;
  transition: all 0.3s ease;
}

  ul:hover {
    transform: scale(1.5);
    text-shadow: $box-shadow-small;
    color: $color-secondary-font;
  }


</style>
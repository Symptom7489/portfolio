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
  border: 1px solid;
  margin: 5rem 0;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  gap: 1rem;
  padding: 1rem;
}

.project-image-front {
  width: 30rem;
  transition: all .3s ease;
  border-radius: 5px;
  box-shadow: $box-shadow-small;

  &:hover {
  transform: scale(2.5) translateX(75px);
    box-shadow: $box-shadow-medium;
   }
}

.project-image-back {
  width: 30rem;
  transition: all .3s ease;

  &:hover {
  transform: scale(2.5) translateX(-75px);
    box-shadow: $box-shadow-medium;
   }
}

ul {
  list-style-type: none;
  font-size: $font-heading-5;
}

</style>
<template>
  <section class="hero-section is-flex is-justify-content-space-around is-align-items-top" style="margin-top: 5rem;">
      <div class="hero-texts">
        <div class="hero-writeup is-flex-shrink-1">
          <h1 class="hero-writeup-heading">
            This headline is the <br> gist of the Your <br> whole Website 
          </h1>
          <p class="hero-writeup-paragraph">
            And the description of hero section is follow up message after the punch of a great headline. So, make it short, simple, descriptive and to the point.
          </p>
        </div>
        <div class="hero-cta-container is-flex">
          <a class="hero-cta is-align-self-center" href="#" style="margin-right: 12px;">Book A Meeting <img src="../assets/long_right.svg" alt="" style="margin-left: 8px;"></a>
          <p class="hero-cta-text">Here you can put secondary action statement & CTA</p>
        </div>
        <div class="hero-reviews">
          <img class="nav-logo" src="../assets/tweakful-reviews.svg">
        </div>
      </div>
      <div class="hero-image">
        <img class="nav-logo" src="../assets/ceo-photo.png">
      </div>
  </section>
</template>

<script setup>

</script>

<style scoped>
  .hero-texts {
    flex-basis: 42%;
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
  }

  .hero-cta {
    background: var(--button-primary);
    color: white;
    border-radius: 1px;
    padding: 15px 25px;
  }

  .hero-writeup-heading {
    color: var(--text-primary);
    font-family: 'Inter', sans-serif;
    font-weight: 700;
    letter-spacing: -1.16px;
    line-height: 1.4;
    font-size: 3rem;
    width: 110%;
    display: inline-block;
    margin-bottom: 1rem;
  }

  .hero-writeup-paragraph, .hero-cta-text {
    color: var(--text-primary);
  }

  .hero-writeup-paragraph {
    width: 83%;
    line-height: 30px;
  }

  .hero-cta-text {
    width: 50%;
  }

  .hero-image {
    width: 380px;
  }

  /*.hero-reviews {
    position: absolute;
    bottom: 0;
  }*/
</style>

<template>
  <div class="container">
    <Platforms />
    <Headline headline="Latest News"/>
    <Link
      link="https://www.google.de"
      headline="Paul Gerlinger Live"
      description="Die erste Gartensession! Genießt die Session von Paul Gerlinger."
      image="https://upload.wikimedia.org/wikipedia/commons/a/aa/Bob_Dylan_and_The_Band_-_1974.jpg"
    />
    <Link
      link="https://www.google.de"
      headline="Cinemagraph Live"
      description="Die erste Gartensession! Genießt die Session von Paul Gerlinger."
      image="https://www.rogers.de/app/uploads/2020/06/RGRS-Promo-1-3-1024x683.jpg"
    />
    <Link
      link="https://www.google.de"
      headline="DJ BOBO Live"
      description="Die erste Gartensession! Genießt die Session von Paul Gerlinger."
      image="https://www.delamar.de/wp-content/uploads/2019/11/band_recording_ratgeber.jpg"
    />

  </div>
</template>

<script>
import Platforms from "~/components/Platforms.vue";
export default {
  components: { Platforms },
};
</script>

<style>

.sectionWrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.sectionHeadline {
  margin: 33px 0 10px 0;
  width: 200px;
  width: 95vw;
  max-width: 800px;
}

.container {
  min-height: 100vh;
  display: flex;
  text-align: center;
  justify-content: center;
  flex-direction: column;
  padding: 10px;
}
</style>

<template>
  <div class="container">
    <a href="https://www.pingr.de"><img class="logo" src="../assets/Schriftlogo_weiß.webp" alt="Pingr Logo"></a>
    <Headline headline="Download Pingr" showLine="true"/>
    <Platforms />
    <Headline headline="Latest News" showLine="true"/>
    <Link
      link="https://www.google.de"
      headline="Paul Gerlinger Live"
      description="Die erste Gartensession! Genießt die Session von Paul Gerlinger."
      image="https://upload.wikimedia.org/wikipedia/commons/a/aa/Bob_Dylan_and_The_Band_-_1974.jpg"
    />
    <Link
      link="https://www.google.de"
      headline="Cinemagraph Live"
      description="Richtig coole Session mit Cinemagraph. Anschauen lohnt sich!"
      image="https://www.rogers.de/app/uploads/2020/06/RGRS-Promo-1-3-1024x683.jpg"
    />
    <Link
      link="https://www.google.de"
      headline="DJ BOBO Live"
      description="Der Klassiker der letzten Dekade. Rumgröhlen garantiert."
      image="https://www.delamar.de/wp-content/uploads/2019/11/band_recording_ratgeber.jpg"
    />
     <Headline headline="Follow us" />
  <Footer />
  </div>
</template>

<script>
import Platforms from "~/components/Platforms.vue";
export default {
  components: { Platforms },
};
</script>

<style>

.container {
  min-height: 100vh;
  display: flex;
  text-align: center;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  padding: 10px;
  width: 95vw;
}

.logo {
  margin-top: 30px;
  width: 100px;
}

</style>

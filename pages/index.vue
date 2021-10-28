<template>
  <div class="container">
    <a href="https://www.pingr.de"><img class="logo" src="../assets/Schriftlogo_weiß.webp" alt="Pingr Logo"></a>
    <Headline headline="Download Pingr" showLine="true"/>
    <Platforms />
    <Headline headline="Latest News" showLine="true"/>
    <Link
      link="https://bit.ly/3bixMLQ"
      headline="Paul Gerlinger - Luft"
      description="Die erste Handmade Live Session mit Paul Gerlinger. Enjoy!"
      image="https://i.postimg.cc/DZbbwVTH/Bildschirmfoto-2021-10-28-um-15-26-02.png"
    />
    <Link
      link="https://bit.ly/2XTJMAt"
      headline="Seeder DJ Set"
      description="Private Minimal House Set der Jungs ausm Peer 23!"
      image="https://i.postimg.cc/pr67Yn7p/Bildschirmfoto-2021-10-28-um-15-28-39.png"
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

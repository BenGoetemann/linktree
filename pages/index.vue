<template>
  <div class="center container">
    <a href="https://bit.ly/2ZDawpN"
      ><img class="logo" src="../assets/Schriftlogo_weiß.webp" alt="Pingr Logo"
    /></a>
    <Headline headline="Download Pingr" showLine="true" />
    <Platforms />
    <Headline headline="Latest News" showLine="true" />
    
    <!-- -----ENTER NEW POSTS HERE------ -->

    <Blogpost
      link="./blogposts/paul-gerlinger"
      headline="Paul Gerlinger - Luft"
      description="Die erste Handmade Live Session mit Paul Gerlinger. Enjoy!"
      image="https://i.postimg.cc/XvHGnjyn/Bildschirmfoto-2021-10-28-um-15-26-02.webp"
    />
    <Blogpost
      link="./blogposts/seeder"
      headline="Seeder DJ Set"
      description="Private Minimal House Set der Jungs ausm Peer 23!"
      image="https://i.postimg.cc/zfXHmbvd/Bildschirmfoto-2021-10-28-um-15-28-39.webp"
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

</style>

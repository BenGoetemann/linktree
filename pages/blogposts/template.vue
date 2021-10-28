<template>
  <div class="container">
    <nuxt-link to="../"><div>← BACK</div></nuxt-link>
    <Headline
      headline="Paul Gerlinger Live"
      showLine="true"
      date="20. Oktober 2021"
    />
    <br />
    <p class="paragraph">
      Es gibt Künstler, die bestechen mit einem durchgestylten Gesamtkonzept,
      mit schriller Überpräsenz, mit Songs, die eigentlich nur Vehikel für ein
      Image sind. Und dann gibt es Paul Gerlinger.
    </p>
    <div resize class="player">
      <youtube
        :video-id="videoId"
        ref="youtube"
        @playing="playing"
        resize
        fitParent
      ></youtube>
    </div>
    <p class="paragraph">
      Es gibt drei Männer, die Paul in Kindertagen künstlerisch geprägt haben:
      seine beiden Großväter und der Lyriker Eugen Roth. "Einer meiner Großväter
      hat mir schon früh Roths Gedichte näher gebracht, der andere ist ein
      gottgleicher Pianist. Auch der Rest meiner Familie ist sehr musik- und
      sprachaffin", erzählt er. Schon in der Grundschule beginnt er, Gedichte zu
      schreiben. Oft auch als Strafarbeit. Im selben Alter lernt er auch, das
      Klavier zu spielen, aber letztlich ist ihm das zu konservativ. Die
      Gedichte machen ihm mehr Spaß.
    </p>
    <img
      class="image"
      src="https://i.postimg.cc/XvHGnjyn/Bildschirmfoto-2021-10-28-um-15-26-02.webp"
      alt=""
    />
    <Headline headline="Download Pingr" showLine="true" />
    <Platforms />
    <nuxt-link to="../"><div>← BACK</div></nuxt-link>
  </div>
</template>

<script>
import Platforms from "~/components/Platforms.vue";
export default {
  components: { Platforms },
  data() {
    return {
      videoId: "E07NzAejzHw",
    };
  },
  methods: {
    playing() {
      console.log("o/ we are watching!!!");
    },
  },
  computed: {
    player() {
      return this.$refs.youtube.player;
    },
  },
};
</script>

<style>
iframe {
  width: 90vw;
  max-width: 560px;
}

.player {
  width: 95vw;
  margin: 30px 0;
}

.image {
  width: 90vw;
  margin: 30px 0;
  max-width: 560px;
}

.paragraph {
  max-width: 560px;
  text-align: justify;
}
</style>

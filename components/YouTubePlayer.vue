<template>
  <div resize class="player">
    <youtube
      :video-id="test"
      ref="youtube"
      @playing="playing"
      resize
      fitParent
    ></youtube>
  </div>
</template>

<script>
export default {
    props: ["test"],
  data() {
    return {
      videoId: this.test,
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
  max-width: 800px;
}

.player {
  width: 95vw;
  margin: 30px 0;
}
</style>
<template>
  <div class="center profile">
    <div class="center profileSection">
      <div
        class="profilePicture"
        :style="{
          background: 'url(\'' + image + '\') no-repeat center center',
          backgroundSize: 'cover',
        }"
      ></div>
      <h3 class="artistAlias">More about {{ artistAlias }}</h3>
      <Genres :genres="genres" />
    </div>
    <div class="row linkList">
      <div v-if="spotify" class="platformLogo">
        <a :href="spotify"><fa :icon="['fab', 'spotify']" class="icon" /></a>
      </div>
      <div v-if="youtube" class="platformLogo">
        <a :href="youtube"><fa :icon="['fab', 'youtube']" class="icon" /></a>
      </div>
      <div v-if="facebook" class="platformLogo">
        <a :href="facebook"><fa :icon="['fab', 'facebook']" class="icon" /></a>
      </div>
      <div v-if="instagram" class="platformLogo">
        <a :href="instagram"><fa :icon="['fab', 'instagram']" class="icon" /></a>
      </div>
      <div v-if="website" class="platformLogo">
        <a :href="website"><fa :icon="['fas', 'globe']" class="icon" /></a>
      </div>
       <div v-if="soundcloud"  class="platformLogo">
        <a :href="soundcloud"><fa :icon="['fab', 'soundcloud']" class="icon" /></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: {
      image: String,
      artistAlias: String,
      genres: Array,
      spotify: String,
      youtube: String,
      facebook: String,
      instagram: String,
      website: String,   
      soundcloud: String,   
  }
};
</script>

<style>
.profile {
  width: 90vw;
  max-width: 800px;
  padding: 20px;
}

.profileSection {
  width: 50%;
}

.linkList {
  width: 250px;
  padding: 10px;
}

.profilePicture {
  height: 100px;
  width: 100px;
  border-radius: 50%;
  border: solid #ffa900 1px;
}

.artistAlias {
  width: 100vw;
}
</style>
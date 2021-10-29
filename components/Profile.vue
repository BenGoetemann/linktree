<template>
  <div class="profile">
    <div class="profileSection">
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
    <div class="linkList">
      <div class="platformLogo">
        <a :href="spotify"><fa :icon="['fab', 'spotify']" class="icon" /></a>
      </div>
      <div class="platformLogo">
        <a :href="youtube"><fa :icon="['fab', 'youtube']" class="icon" /></a>
      </div>
      <div class="platformLogo">
        <a :href="facebook"><fa :icon="['fab', 'facebook']" class="icon" /></a>
      </div>
      <div class="platformLogo">
        <a :href="instagram"><fa :icon="['fab', 'instagram']" class="icon" /></a>
      </div>
      <div class="platformLogo">
        <a :href="website"><fa :icon="['fas', 'globe']" class="icon" /></a>
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
  }
};
</script>

<style>
.profile {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 90vw;
  max-width: 800px;
  padding: 20px;
}

.profileSection {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  width: 50%;
}

.linkList {
  display: flex;
  align-items: center;
  justify-content: space-around;
  flex-direction: row;
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
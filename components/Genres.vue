<template>
   <div class="genre-wrapper">
      <div class="genre" v-for="genre in genres" :key="genre[i]">
        {{ genre }}
      </div>
    </div>
</template>

<script>
export default {
props: {
    genresArray: Array
},
  data() {
    return {
      genres: this.genresArray,
    };
  },
}
</script>

<style>

.genre-wrapper {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  flex-direction: row;
  max-width: 600px;
}

.genre {
  padding: 2px 10px;
  background: #ffa900;
  border-radius: 20px;
  margin: 5px;
  font-weight: 500;
  -webkit-user-select: none;  /* Chrome all / Safari all */
  -moz-user-select: none;     /* Firefox all */
  -ms-user-select: none;      /* IE 10+ */
  user-select: none;  
  white-space: nowrap;
}

</style>
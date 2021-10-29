<template>
  <div class="imageWrapper">
    <img class="image" :src="src" :alt="alt" />
    <p v-if="description" class="imageDescription">{{ description }}</p>
  </div>
</template>

<script>
export default {
  props: ["src", "alt", "description"],
};
</script>

<style>

.imageWrapper {
  margin: 30px 0;
}

.image {
  width: 90vw;
  max-width: 800px;
}

.imageDescription {
  display: flex;
  justify-content: flex-start;
  align-items: left;
  font-size: 0.8rem;
}

</style>
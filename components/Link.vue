<template>
  <a :href="link" class="row link">
    <div class="left descriptionWrapper">
      <div class="headline">
        <h3>{{ headline }}</h3>
      </div>
      <div class="description">{{ description }}</div>
    </div>
    <div
      class="previewImage border"
      :style="{
        background: 'url(\'' + image + '\') no-repeat center center',
        backgroundSize: 'cover',
      }"
    ></div>
  </a>
</template>

<script>
export default {
  props: ["link", "headline", "description", "image"],
};
</script>

<style>

.c {
  padding: 0
}
.link {
  padding: 20px;
  margin-bottom: 10px;
  border-radius: 6px;
  height: 120px;
  width: 100%;
  background: #1a1a1a;
}

.link:hover {
  background: #1d1d1d;
  outline: 1px solid #faa900;
}

.descriptionWrapper {
  display: flex;
  align-items: flex-start;
  text-align: left;
  flex-direction: column; 
  justify-content: space-between;
  height: 100%;
  max-width: 23ch;
}

.description {
  font-size: 0.8rem;
}

.previewImage {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  width: 70px;
  height: 100%;
  margin-left: 5px;
}
</style>
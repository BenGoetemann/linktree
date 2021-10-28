<template>
  <a :href="link" class="link">
    <div class="descriptionWrapper">
      <div class="headline">
        <h3>{{ headline }}</h3>
      </div>
      <div class="description">{{ description }}</div>
    </div>
    <div
      class="previewImage"
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
.link {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  padding: 20px;
  margin-bottom: 10px;
  border-radius: 6px;
  height: 120px;
  width: 100%;
  max-width: 800px;
  background: #1a1a1a;
}

.link:hover {
  background: #1d1d1d;
  outline: 1px solid #faa900;
}

.descriptionWrapper {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  justify-content: space-between;
  height: 100%;
  text-align: left;
  max-width: 23ch;
}

.description {
    font-size: .80rem;
}

.previewImage {
  display: flex;
  flex-direction: column;
  align-items: flex-end;
  width: 70px;
  height: 100%;
  border-radius: 6px;
}
</style>
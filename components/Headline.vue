<template>
     <div class="sectionWrapper">
      <div class="sectionHeadline">
        <h3> {{ headline }}</h3>
      </div>
      <div v-if="showLine" class="line"></div>
    </div>
</template>

<script>
export default {
  props: ["headline", "showLine"],
};
</script>

<style>
.sectionWrapper {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.sectionHeadline {
  margin: 33px 0 5px 0;
  width: 200px;
  width: 95vw;
  max-width: 800px;
}

.line {
  height: 3px;
  width: 30px;
  background: #ffa900;
  border-radius: 6px;
  margin-bottom: 10px;
}
</style>
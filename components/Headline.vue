<template>
     <div class="center">
      <div class="sectionHeadline">
        <p v-if="date" class="date">{{ date }}</p>
        <h3> {{ headline }}</h3>
      </div>
      <div v-if="showLine" class="line"></div>
    </div>
</template>

<script>
export default {
  props: ["headline", "showLine", "date"],
};
</script>

<style>

.date {
  font-weight: bold;
  font-size: 0.6rem;
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
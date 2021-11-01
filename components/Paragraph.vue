<template>
  <p class="paragraph">
    {{ content }}
  </p>
</template>

<script>
export default {
  props: ["content"],
};
</script>

<style>
.paragraph {
  text-align: justify;
  margin-bottom: 15px;
}
</style>
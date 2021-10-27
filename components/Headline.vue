<template>
     <div class="sectionWrapper">
      <div class="sectionHeadline">
        <h3> {{ headline }}</h3>
      </div>
    </div>
</template>

<script>
export default {
  props: ["headline"],
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
  width: 95vw;
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
  max-width: 28ch;
}

.description {
    font-size: .86rem;
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
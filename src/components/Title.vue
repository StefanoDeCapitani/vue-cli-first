<template>
  <div class="container py-4">
    <div class="p-5 mb-4 bg-light rounded-3">
      <div class="container-fluid py-5">
        <h1 class="display-4">{{ msg }}</h1>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "title",
  props: {
    msg: String,
  },
};
</script>

<style></style>

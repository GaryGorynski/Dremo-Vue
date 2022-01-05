<template>
  <div class="container">
    <h3>
      {{ title }}
    </h3>
    <p>
      {{ description }}
    </p>
  </div>
</template>

<script>
export default {
  name: "Card",
  props: {
    title: {
      required: true,
    },
    description: {
      required: true,
    },
  },
};
</script>

<style></style>

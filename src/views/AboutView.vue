<template>
  <div class="about">
    <h1>{{ pageName }}</h1>
    <p>{{ pageDisc }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      pageName: "About Us",
      pageDisc: "This is about us page",
    };
  },
  name: "AboutView",
};
</script>

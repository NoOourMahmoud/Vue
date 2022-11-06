<template>
  <div class="our-help">
    <h1>{{ pageName }}</h1>
    <p>{{ pageDisc }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      pageName: "Help",
      pageDisc: "This is help page",
    };
  },
  name: "HelpView",
};
</script>

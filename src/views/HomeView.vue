<template>
  <div class="home">
    <h1>This is home page</h1>
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: "HomeView",
  setup() {
    document.title = 'Home'
  },
  components: {
  },
};
</script>

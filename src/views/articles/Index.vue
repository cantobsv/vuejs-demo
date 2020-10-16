<template>
  <div class="home">
    <img alt="Vue logo" src="@/assets/logo.png" />
    <ListArticle msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import ListArticle from "@/components/articles/Index.vue";

export default {
  components: {
    ListArticle
  }
};
</script>

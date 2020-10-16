<template>
  <div class="home">
    <img alt="Vue logo" src="@/assets/logo.png" />
    <Article msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import Article from "@/components/articles/Show.vue";

export default {
  name: "ArticleDetails",
  components: {
    Article
  }
};
</script>

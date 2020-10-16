<template>
  <div id="app">
    <!-- navbar -->
    <HeaderNavbar />
    <div class="container">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderNavbar from "@/components/shared/HeaderNavbar.vue";

export default {
  components: {
    HeaderNavbar
  }
};
</script>

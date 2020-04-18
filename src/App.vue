<template>
  <div id="app">
    <div class="row">
      <div class="col-sm-2 col-md-3 col-lg-2.5 col-xl-2">
        <LeftSideNav />
      </div>
      <div class="col-sm-10 col-md-9 col-lg-9.5 col-xl-10">
        <router-view />
      </div>
    </div>
  </div>
</template>

<script>
import LeftSideNav from "@/components/LeftSideNav.vue";
export default {
  components: {
    LeftSideNav
  }
};
</script>

<style scoped>
.col-8 {
  padding: 0;
}
</style>

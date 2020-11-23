<template>
    <nav-bar />
    <div class="container-fluid">
        <div class="row">
          <side-bar />
          <add-posts />
        </div>
    </div>
</template>

<script>
  import NavBar from "../components/NavBar.vue";
  import SideBar from "../components/SideBar.vue";
  import AddPosts from "../components/AddPosts.vue";

  export default {
    name: "DashBoard",
    props: {},
    data() {
      return {};
    },
    components: {
      NavBar,
      SideBar,
      AddPosts
    },
  };
</script>

<style scoped>
</style>

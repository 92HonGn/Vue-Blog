<template>
  <div class="add-posts">
    <div class="mb-3">
      <div class="test">lol</div>
      <input type="text"
             class="form-control"
             placeholder="文章標題">
    </div>
    <div class="mb-3">
      <textarea class="form-control"
                rows="3"></textarea>
    </div>
  </div>
</template>

<script>
  export default {
    name: "AddPosts",
    props: {},
    data() {
      return {};
    },
  };
</script>

<style scoped>
.test{
  color: var(--bs-blue);
}
</style>

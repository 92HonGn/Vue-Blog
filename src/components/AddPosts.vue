<template>
  <main class="col-md-9 ml-sm-auto col-lg-10 px-md-4">
    <div class="add-posts">
      <div class="mb-3">
        <h2 class="pb-2 mb-3 border-bottom">Add New Blog Post</h2>
        <input type="text"
               class="form-control"
               placeholder="文章標題">
      </div>
      <div class="mb-3">
        <textarea class="form-control"
                  rows="20"></textarea>
      </div>
    </div>
  </main>
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
  .test {
    color: var(--bs-blue);
  }
</style>

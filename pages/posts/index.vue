<template>
  <div class="posts-page">
    <PostList/>
  </div>
</template>

<script>
    import PostPreview from "../../components/Posts/PostPreview";
    import PostList from "../../components/Posts/PostList";
    export default {
        name: "index",
      components: {PostList, PostPreview}
    }
</script>

<style scoped>
  .posts-page{
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>

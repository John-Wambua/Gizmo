<template>
  <section class="post-list">
    <PostPreview
      id="1"
      thumbnail="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcS_rbqRlg_dukeGDrtkk3R5Lfb_wsjjxd7how&usqp=CAU"
      title="Hello There!"
      previewText="My first Post"
    />
    <PostPreview
      id="2"
      thumbnail="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcS_rbqRlg_dukeGDrtkk3R5Lfb_wsjjxd7how&usqp=CAU"
      title="Wassupp!"
      previewText="My second Post"
    />
    <PostPreview
      id="3"
      thumbnail="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcS_rbqRlg_dukeGDrtkk3R5Lfb_wsjjxd7how&usqp=CAU"
      title="How are you my guy!"
      previewText="My third Post"
    />
    <PostPreview
      id="4"
      thumbnail="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcS_rbqRlg_dukeGDrtkk3R5Lfb_wsjjxd7how&usqp=CAU"
      title="Is How?"
      previewText="My Fourth Post"
    />

  </section>
</template>

<script>
    import PostPreview from "./PostPreview";
    export default {
        name: "PostList",
      components: {PostPreview}
    }
</script>

<style scoped>

  .post-list {
    display: flex;
    padding: 20px;
    box-sizing: border-box;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
  }
</style>

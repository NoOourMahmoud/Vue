<template>
  <div class="post-box">
    <span class="post-views">10</span>
    <h3 class="post-title">Blog Post Title</h3>
    <span class="post-date">6-11-2022</span>
    <p class="post-content">Hi post</p>
    <div class="row">
      <div class="col-sm-6">
        <span class="post-author">Post Author</span>
      </div>
      <div class="col-sm-6">
        <span class="post-category">Category Name</span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BlogPost",
};
</script>

<style lang="scss" scoped>
.post-box {
  padding: 15px;
  background-color: #fff;
  box-shadow: 0 0 10px #ddd;
  position: relative;
  .post-views {
    position: absolute;
    top: 5px;
    right: 5px;
    background-color: red;
    border-radius: 4px;
    padding: 1px 5px;
  }
}
</style>

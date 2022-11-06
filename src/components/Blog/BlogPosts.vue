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
  padding: 20px;
  background-color: #fff;
  box-shadow: 0 0 10px #ddd;
  position: relative;
  text-align: left;
  .post-views {
    position: absolute;
    top: 5px;
    right: 5px;
    background-color: #9700fe;
    border-radius: 4px;
    padding: 1px 5px;
    color: white;
    text-align: center;
    font-weight: bold;
  }
  .post-title {
    color: #777;
  }
  .post-date {
    display: block;
    padding: 0 0 5px;
    color: #888;
    font-size: 14px;
  }
  .post-content {
    line-height: 1.8;
    color: #666;
  }
  .post-author {
    background-color: #607d8b;
    padding: 6px 10px;
    border-radius: 4px;
    color: #fff;
  }
  .post-category {
    background-color: rebeccapurple;
    padding: 6px 10px;
    border-radius: 4px;
    color: #fff;
  }
}
</style>

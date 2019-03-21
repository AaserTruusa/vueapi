<template>
  <div class="card">
    <header class="card-header">
      <p class="card-header-title">
        {{post.title}}
      </p>
    </header>
    <div class="card-image">
      <figure class="image is-4by3">
        <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
      </figure>
    </div>
    <div class="card-content">
      <div class="content">
        {{post.content}}
        <a href="#">#css</a> <a href="#">#responsive</a>
        <br>
        <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
      </div>
    </div>
  </div>
</template>
<script>
  export default {
    name: "post",
    props: ['post'],
  }
</script>
<style scoped>
</style>
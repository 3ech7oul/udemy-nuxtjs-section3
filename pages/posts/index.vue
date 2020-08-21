<template>
  <div class="post-page">
    <section class="featured-posts ">


     <PostList 
      id="2"
      title="Name 2"
      previewText="previewText previewText"
      thumbnail="https://images.pexels.com/photos/270348/pexels-photo-270348.jpeg"
    />
   </section>
  </div>
</template>

<script>
import PostList from '@/components/Posts/PostList'

export default {
  components: {
    PostList
  }
}
</script>

<style scoped>
.post-page {
    display: flex;
    justify-content: center;
    align-items: center;
  
}
</style>
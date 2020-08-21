<template>
  <div class="post-page">
    <section class="featured-posts ">
    <PostPreview 
      id="1"
      title="Name 1"
      previewText="previewText previewText"
      thumbnail="https://images.pexels.com/photos/270348/pexels-photo-270348.jpeg"
    />
   
     <PostPreview 
      id="2"
      title="Name 2"
      previewText="previewText previewText"
      thumbnail="https://images.pexels.com/photos/270348/pexels-photo-270348.jpeg"
    />

     <PostPreview 
      id="2"
      title="Name 2"
      previewText="previewText previewText"
      thumbnail="https://images.pexels.com/photos/270348/pexels-photo-270348.jpeg"
    />
   </section>
  </div>
</template>

<script>
import PostPreview from '@/components/Posts/PostPreview'

export default {
  components: {
    PostPreview
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
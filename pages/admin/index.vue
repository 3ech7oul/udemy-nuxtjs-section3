<template>
 <section class="admin-page">
   <section class="new-post">
     <button @click="$router.push('/admin/new-post')">Create post</button>
   </section>
   <sectoion class="existing-post">
       <h1>existing post</h1>
       
          <PostList  />
    
   </sectoion>
   
  </section>
</template>

<<script>
import PostList from '@/components/Posts/PostList'

export default {
  components: {
    PostList
  }
}
</script>
<template>     
     <form @submit.prevent="onSave">
         <AppControlInput v-model="editPost.title">Title</AppControlInput>
         <AppControlInput v-model="editPost.previewText">previewText</AppControlInput>
         <AppControlInput v-model="editPost.thumbnail">thumbnail</AppControlInput>
         <AppControlInput v-model="editPost.content" controlType="textarea">content</AppControlInput>
         
         <AppButton
            type="submit"
         >Save</AppButton>         
     </form>
</template>

<script>
import AppControlInput from '@/components/UI/AppControlInput'
import AppButton from '@/components/UI/AppButton'

export default {
  name:'AdminPostForm',
  components: {
    AppControlInput,
    AppButton
  },
  data(){
      return {
          editPost: {
              title:'',
              previewText:'',
              thumbnail: '',
              content: ''
          }
      }
  },
  methods:{
      onSave(){

      },
      onCancel(){

      }
  }
}
</script>
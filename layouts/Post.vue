<template>
  <article class="post">
    <Content
      :key="$page.path"
      class="post-content markdown-body"/>
    
    <PostMeta/>
  </article>
</template>

<script>
import PostMeta from '@theme/components/PostMeta'
export default {
  name: 'Post',
  components: {
    PostMeta
  }
}
</script>

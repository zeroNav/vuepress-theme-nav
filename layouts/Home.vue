<template>
  <div class="home">
    <Content
      :key="$page.path"
      class="post-content markdown-body"/>
    <PostsList class="main-div"/>
  </div>
</template>

<script>
import PostsList from '@theme/components/PostsList'
export default {
  name: 'Home',
  components: {
    PostsList
  }
}
</script>

<template>
  <div>
    <AppNav />
    <nuxt />
  </div>
</template>

<script>
  import AppNav from '@/components/global/AppNav'

  export default {
    components: {
      AppNav
    }  
  }
</script>
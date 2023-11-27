<template>
  <div>
    {{ user }}
  </div>
</template>

<script>
export default {
  data () {
    return {
      user: null
    }
  },

  methods: {
    async getUser () {
      let response = await this.$axios.$get('/api/user')

      this.user = response
    }
  },

  mounted () {
    this.getUser()
  }
}
</script>

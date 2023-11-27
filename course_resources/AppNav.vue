<template>
  <div class="flex justify-between mb-10">
    <ul class="flex items-center">
      <li class="mr-4">
        <nuxt-link :to="{ name: 'index' }" class="text-gray-800 font-medium">
          Home
        </nuxt-link>
      </li>
    </ul>
    <ul class="flex items-center">
      <li class="mr-4">
        <nuxt-link :to="{ name: 'account' }" class="text-gray-800 font-medium">
          Name
        </nuxt-link>
      </li>
      <li>
        <a href="#" class="text-gray-800 font-medium" @click.prevent="signOut">
          Sign out
        </a>
      </li>
      <li class="mr-4">
        <nuxt-link :to="{ name: 'auth-signin' }" class="text-gray-800 font-medium">
          Sign in
        </nuxt-link>
      </li>
      <li>
        <a href="#" class="font-medium text-gray-800">
          Sign up
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
  export default {
    
  }
</script>
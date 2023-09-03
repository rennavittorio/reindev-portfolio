<template>

  <a class="underline text-blue-500" :href="href" target="_blank">
    <slot></slot>
  </a>

</template>

<script lang="ts">

export default {
  props: {
    href: String
  }
}

</script>

<style scoped>

</style>
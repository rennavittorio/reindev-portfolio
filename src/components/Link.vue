<template>

  <div class="relative inline-flex group">
    <a class="underline text-green-500" :href="href" target="_blank">
      <slot></slot>
    </a>
  </div>

</template>

<script lang="ts">

export default {
  props: {
    href: {type: String, required: true}
  }
}

</script>

<style scoped>

</style>
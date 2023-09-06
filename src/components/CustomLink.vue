<template>

  <div class="link-main relative inline-flex group">
    <a :href="href" target="_blank">
      <slot></slot>
    </a>
    <div class="link-custom">

    </div>
  </div>

</template>

<script lang="ts">

export default {
  props: {
    href: {type: String, required: true}
  }
}

</script>

<style>
.link-custom {
  content: '';
  display: block;
  width: 100%;
  height: 20%;
  background: rgb(34 197 94);
  opacity: 0.75;
  position: absolute;
  z-index: -1;
  bottom: 0;
  animation: up 0.2s forwards
}

.link-main:hover .link-custom {
  animation: up 0.2s forwards;
}

.link-main:not(:hover) .link-custom {
  animation: down 0.2s forwards;
}

@keyframes up {
    0% {
      height: 20%;
    }

    100% {
      height: 60%;
    }
}

@keyframes down {
    0% {
      height: 60%;
    }

    100% {
      height: 20%;
    }
}
</style>
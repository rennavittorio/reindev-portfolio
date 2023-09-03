<template>
  <div class="cube absolute w-[25px] h-[25px] bg-green-500">

  </div>
</template>

<script lang="ts">
export default {}

</script>

<style scoped>
.cube {
  animation: rotating 4s linear infinite,
        tilting 1s ease-in-out infinite;

}

@keyframes rotating {
    0% {
        transform: rotate(0deg);
    }

    100% {
        transform: rotate(360deg);
    }
}

@keyframes tilting {
    0% {
        bottom: 0px;
    }

    50% {
        bottom: 10px;
    }

    100% {
        bottom: 0px;
    }
}
</style>
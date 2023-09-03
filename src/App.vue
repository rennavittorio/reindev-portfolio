<script lang="ts">
import Header from './components/Header.vue';
import Link from './components/Link.vue';

export default {
  components: {
    Header,
    Link
  }
}


</script>

<template>

  <div class="">
    
    <h3 class="text-4xl">Hello world!</h3>

    <p>My name is Vittorio Renna and I am <Link href="https://www.w3schools.com/whatis/whatis_fullstack.asp">Fullstack Web Developer</Link>, with a background in the Neuroscience.</p>

    <p>I’m currently working at Gility, and I’m an active contributor of Schrödinger Hat.</p>

    <p>In my current work and personal projects, I’m mainly using Nextjs, Prisma and Vue3, but I have also experience in other tools as you can see from my GitHub.</p>

    <p>Beside programming, I also love going on long hikes in the mountains, enjoy northern European literature, and drink good IPA beers.</p>

    <p>You can add me on Linkedin, chat with me on Discord or follow me on Twitter X if you want to talk about one of the above topic!</p>

  </div>

</template>

<style>

</style>

<script lang="ts">
import Header from './components/Header.vue';
import Link from './components/Link.vue';
import Paragraph from './components/Paragraph.vue';
import Cube from './components/Cube.vue';

export default {
  components: {
    Header,
    Link,
    Paragraph,
    Cube
  }
}


</script>

<template>

  <div class="flex flex-col justify-center p-4 sm:p-[100px] lg:p-[25%] h-[100dvh] font-inter bg-[#ddd] text-[#222]">
    
    <div class="mb-8 flex gap-4 items-center">
      <h3 class="text-4xl">Hello world!</h3>
      <div class="relative w-[30px] h-[30px]">

        <Cube />
      </div>
    </div>

    <Paragraph>My name is Vittorio Renna and I am Developer with a background in the Neuroscience.</Paragraph>

    <Paragraph>I’m currently working at <Link href="https://www.gility.it/">Gility</Link>, and I’m an active contributor of <Link href="https://www.schrodinger-hat.it/">Schrödinger Hat</Link>.</Paragraph>

    <Paragraph>In my current work and personal projects, I’m mainly using <Link href="https://nextjs.org/">Nextjs</Link>, <Link href="https://www.prisma.io/">Prisma</Link> and <Link href="https://vuejs.org/">Vue</Link>, but I have also experience in other tools as you can see from my <Link href="https://github.com/rennavittorio">GitHub</Link>.</Paragraph>

    <Paragraph>Beside programming, I also love going on long hikes in the mountains, enjoy northern European literature, and drink good IPA beers.</Paragraph>

    <Paragraph>You can add me on <Link href="https://www.linkedin.com/in/rennavittorio/">LinkedIn</Link>, chat with me on <Link href="https://discordapp.com/users/reindev#0832">Discord</Link> or follow me on <span class="line-through">Twitter</span> <Link href="https://twitter.com/reindev_js">X</Link> if you want to talk about one of the above topic!</Paragraph>

  </div>

</template>

<style>

</style>

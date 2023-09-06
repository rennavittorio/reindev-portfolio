<script lang="ts">
import CustomLink from './components/CustomLink.vue';
import Paragraph from './components/Paragraph.vue';
import Cube from './components/Cube.vue';

export default {
  components: {
    CustomLink,
    Paragraph,
    Cube
  }
}


</script>

<template>

  <div class="flex flex-col justify-center items-center min-h-[100dvh] font-inter bg-[#ddd] text-[#222]">
    <div class="flex flex-col justify-center p-10 max-w-[750px]">
      <div class="mb-8 flex gap-4 items-center">
        <h3 class="text-4xl">Hello world!</h3>
        <div class="relative w-[30px] h-[30px]">
  
          <Cube />
        </div>
      </div>
  
      <Paragraph>My name is Vittorio Renna and I am Developer with a background in the Neuroscience.</Paragraph>
  
      <Paragraph>I’m currently working at <CustomLink href="https://www.gility.it/">Gility</CustomLink>, and I’m an active contributor in the Open Source Community.</Paragraph>
  
      <Paragraph>In my current work and personal projects, I’m mainly using <CustomLink href="https://nextjs.org/">Nextjs</CustomLink>, <CustomLink href="https://www.prisma.io/">Prisma</CustomLink> and <CustomLink href="https://vuejs.org/">Vue</CustomLink>, but I have also experience in other tools as you can see from my <CustomLink href="https://github.com/rennavittorio">GitHub</CustomLink>.</Paragraph>
  
      <Paragraph>Beside programming, I also love going on long hikes in the mountains, enjoy northern European literature, and drink good IPA beers.</Paragraph>
  
      <Paragraph>You can add me on <CustomLink href="https://www.linkedin.com/in/rennavittorio/">LinkedIn</CustomLink>, chat with me on <CustomLink href="https://discordapp.com/users/reindev#0832">Discord</CustomLink> or follow me on <span class="line-through">Twitter</span> <CustomLink href="https://twitter.com/reindevtsx">X</CustomLink> if you want to talk about one of the above topic!</Paragraph>

    </div>

  </div>

</template>

<style>

</style>

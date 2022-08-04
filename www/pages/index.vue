<template>
  <main>
    <nuxt-img src="/bg.png" placeholder class="object-cover h-screen w-screen relative" sizes="sm:200vw md:200vw lg:250vw" format="webp"></nuxt-img>
    <div class="absolute flex flex-col w-screen" style="top: 50%; left:50%; transform: translate(-50%, -50%)">
      <nuxt-img :placeholder="[100, 50, 10]" src="/bear.svg" alt="Polar Bear Logo" class="h-32"/>
      <br/>
      <h1 class="text-4xl text-white text-center">
        Coming Soon
      </h1>
  </div>
  </main>
</template>

<script>

</script>

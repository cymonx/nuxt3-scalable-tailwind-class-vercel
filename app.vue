<!-- <script lang="ts" setup>
useHead({
  title: "Home",
  meta: [
    {
      name: "description",
      content: "Home Nuxt 3, IT Genius Engineering",
    },
    {
      name: "keywords",
      content: "Home, Nuxt 3, Learning Nuxt 3",
    },
  ],
});
</script>

<template>
  <div>
    <div class="flex justify-center items-center h-screen">
      <h1 class="text-3xl font-bold text-purple-600 animate-bounce">
        <Icon name="icon-park:home-two"></Icon>
        Hello Nuxt 3
        <Icon name="ic:twotone-wb-sunny"></Icon>
      </h1>
    </div>
  </div>
</template> -->

<template>
  <Head>
    <link
      href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans+Thai:wght@300;400;500&display=swap"
      rel="stylesheet"
    />
  </Head>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

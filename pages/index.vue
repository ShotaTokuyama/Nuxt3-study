<template>
  <main class="bg-gray-300 w-[940px] mx-auto h-fit">
    <h1 class="p-6 text-3xl">
      Welcome to My Portfolio Site!<br />Frontend Engineer
    </h1>
    <div class="text-center mb-6">
      <NuxtImg
        src="/images/home_img.jpg"
        quality="70"
        sizes="md:100% lg:500px"
        class="inline-block"
      />
    </div>
    <div class="text-blue-500 hover:text-blue-800 text-right">
      <NuxtLink to="/About">➡ About Page</NuxtLink>
    </div>
  </main>
</template>

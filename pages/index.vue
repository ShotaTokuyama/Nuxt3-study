<template>
  <main class="w-[940px] mx-auto h-fit p-6">
    <h1 class="text-3xl mb-8">
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
      <NuxtLink to="/Skill">➡ Next Page</NuxtLink>
    </div>
    <a
      href="https://github.com/ShotaTokuyama"
      target="_blank"
      class="text-center block cursor-pointer"
    >
      <NuxtImg
        src="/images/home_github.png"
        quality="70"
        sizes="md:100% lg:500px"
        class="inline-block"
      />
    </a>
  </main>
</template>

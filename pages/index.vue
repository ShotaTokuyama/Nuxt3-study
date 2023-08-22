<template>
  <main class="w-[940px] mx-auto h-fit p-6">
    <h1 class="text-5xl mb-16">
      Welcome to My Portfolio Site!<br />Frontend Engineer
    </h1>
    <div class="max-w-sm w-full lg:max-w-full lg:flex mb-16 justify-center">
      <NuxtImg
        src="/images/home_img.jpg"
        quality="70"
        sizes="md:100% lg:500px"
        class="inline-block"
      />
      <div
        class="py-4 px-12 flex flex-col justify-between leading-normal w-3/4"
      >
        <div class="text-gray-900 font-bold text-xl mb-2">
          My name is Shota.Tokuyama
        </div>
        <p class="text-gray-700 text-base">
          I am working as a frontend engineer in Tokyo.<br />
          My hobbies are gaming and photography.<br />Nice to meet you.
        </p>
      </div>
    </div>
    <div class="text-blue-500 hover:text-blue-800 text-right mb-16">
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

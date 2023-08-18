<template>
  <section class="w-[940px] mx-auto h-fit p-6">
    <h1 class="text-3xl mb-8">My Skill Page</h1>
    <div class="flex flex-wrap gap-4 mb-6">
      <div class="w-[30%] rounded overflow-hidden shadow-lg text-center">
        <NuxtImg
          src="/images/skill_html.png"
          quality="70"
          sizes="md:100% lg:500px"
          class="inline-block"
        />
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">HTML5</div>
          <p class="text-gray-700 text-base">2year</p>
        </div>
      </div>
      <div class="w-[30%] rounded overflow-hidden shadow-lg text-center">
        <NuxtImg
          src="/images/skill_css.png"
          quality="70"
          sizes="md:100% lg:500px"
          class="inline-block"
        />
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">CSS3</div>
          <p class="text-gray-700 text-base">2year</p>
        </div>
      </div>
      <div class="w-[30%] rounded overflow-hidden shadow-lg text-center">
        <NuxtImg
          src="/images/skill_tailwind.png"
          quality="70"
          sizes="md:100% lg:500px"
          class="inline-block"
        />
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">TailwindCSS</div>
          <p class="text-gray-700 text-base">1year</p>
        </div>
      </div>
      <div class="w-[30%] rounded overflow-hidden shadow-lg text-center">
        <NuxtImg
          src="/images/skill_typescript.png"
          quality="70"
          sizes="md:100% lg:500px"
          class="inline-block"
        />
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">TypeScript</div>
          <p class="text-gray-700 text-base">1year</p>
        </div>
      </div>
      <div class="w-[30%] rounded overflow-hidden shadow-lg text-center">
        <NuxtImg
          src="/images/skill_vue.png"
          quality="70"
          sizes="md:100% lg:500px"
          class="inline-block"
        />
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">Vue</div>
          <p class="text-gray-700 text-base">1year</p>
        </div>
      </div>
      <div class="w-[30%] rounded overflow-hidden shadow-lg text-center">
        <NuxtImg
          src="/images/skill_Nuxt.png"
          quality="70"
          sizes="md:100% lg:500px"
          class="inline-block"
        />
        <div class="px-6 py-4">
          <div class="font-bold text-xl mb-2">Nuxt</div>
          <p class="text-gray-700 text-base">1year</p>
        </div>
      </div>
    </div>
    <div class="text-blue-500 hover:text-blue-800 text-right">
      <NuxtLink to="/Works">➡ Next Page</NuxtLink>
    </div>
  </section>
</template>

<script lang="ts">

export default{
  name: 'HeroComonent',
  props: {},
  components:{

  }
}
</script>

<template>
  <div class="bg-current">
      <div
        class="relative isolate overflow-hidden bg-gray-900 shadow-2xl lg:px-64 lg:py-15 lg:flex lg:gap-x-10"
      >
        <svg
          viewBox="0 0 1024 1024"
          class="absolute left-1/2 top-1/2 -z-10 h-[64rem] w-[64rem] -translate-y-1/2 [mask-image:radial-gradient(closest-side,white,transparent)] sm:left-full sm:-ml-80 lg:left-1/2 lg:ml-0 lg:-translate-x-1/2 lg:translate-y-0"
          aria-hidden="true"
        >
          <circle
            cx="512"
            cy="512"
            r="512"
            fill="url(#759c1415-0410-454c-8f7c-9a820de03641)"
            fill-opacity="0.7"
          />
          <defs>
            <radialGradient id="759c1415-0410-454c-8f7c-9a820de03641">
              <stop stop-color="#7775D6" />
              <stop offset="1" stop-color="#E935C1" />
            </radialGradient>
          </defs>
        </svg>
        <div
          class="mx-auto max-w-md text-center lg:mx-0 lg:flex-auto lg:py-32 lg:text-center"
        >
          <h2 class="text-3xl font-bold tracking-tight text-white sm:text-4xl">
            Empower your business with AI
          </h2>
          <p class="mt-6 text-lg leading-8 text-gray-300">
            We specialize in customized artificial intelligence solutions for small and medium businesses. <br>Transform your operations and reach new heights.
          </p>
          <div
            class="mt-10 flex gap-x-6 lg:justify-center"
          >
            <a
              href="#"
              class="rounded-md bg-white px-3.5 py-2.5 text-sm font-semibold text-gray-900 shadow-sm hover:bg-gray-100 focus-visible:outline focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-white"
              >Get started</a
            >
          </div>
        </div>
        <div class="relative lg:w-full lg:mt-0">
          <img
            class="absolute left-10 top-0 w-[70rem] max-w-none rounded-md "
            src="../assets/chatgpt-ai-robot.jpg"
            alt="App screenshot"
            width="1824"
            height="1080"
          />
        </div>
      </div>
    </div>
</template>
<script lang="ts">
import {
  ArrowPathIcon,
  CloudArrowUpIcon,
  FingerPrintIcon,
  LockClosedIcon,
} from "@heroicons/vue/24/outline";

export default {
  name: "Features",
  props: {},
  data() {
    return {
      features: [
        {
          name: "AI Integration",
          description:
            "We facilitate the integration of artificial intelligence solutions into your existing platforms, empowering your operations and improving efficiency.",
          icon: CloudArrowUpIcon,
        },
        {
          name: "Translation Tools",
          description:
            "We offer AI-powered translation tools, enabling smooth and accurate communication in multiple languages to expand your global reach.",
          icon: FingerPrintIcon,
        },
        {
          name: "Custom Chatbots",
          description:
            "We develop customized chatbots that improve customer interaction, provide real-time support and automate routine tasks.",
          icon: LockClosedIcon,
        },
        {
          name: "AI Algorithms",
          description:
            "We create custom AI algorithms that help discover patterns, make informed decisions and predict future trends in your business.s",
          icon: ArrowPathIcon,
        },
        {
          name: "ChatGPT Plugins",
          description:
            "We develop plugins for ChatGPT that extend the capabilities of your chatbot, providing more accurate and contextual responses to user queries.",
          icon: ArrowPathIcon,
        },
        {
          name: "Data Security",
          description:
            "We prioritize the security of your data. Our IA solutions are designed with the best security practices to protect the information of your company and your customers.",
          icon: ArrowPathIcon,
        },
      ],
    };
  },
};
</script>

<template>
    <div class="bg-white py-6 sm:py-12 md:py-24">
      <div class="mx-auto px-4 sm:px-6 lg:px-8 max-w-7xl">
        <div class="text-center">
          <h2 class="text-base font-semibold leading-7 text-indigo-600 sm:text-lg md:text-xl">
            Empower Your Business
          </h2>
          <p class="mt-2 text-xl font-bold tracking-tight text-gray-900 sm:text-2xl md:text-3xl">
            Everything you need to leverage AI in your SME
          </p>
          <p class="mt-4 text-base leading-6 text-gray-600 sm:text-lg md:text-xl">
              We provide end-to-end AI solutions tailored to small and medium-sized businesses.
              <br>From integrating AI into your existing platforms to developing custom chatbots and translation tools, 
              we have everything you need. 
          </p>
        </div>
        <div class="mt-10 sm:mt-12 md:mt-16 grid gap-10 sm:grid-cols-2 lg:grid-cols-3">
          <div v-for="feature in features" :key="feature.name" class="flex items-start">
            <div class="flex-shrink-0">
              <component :is="feature.icon" class="h-6 w-6 text-indigo-600" aria-hidden="true" />
            </div>
            <div class="ml-4">
              <dt class="text-lg leading-6 font-medium text-gray-900">
                {{ feature.name }}
              </dt>
              <dd class="mt-2 text-base text-gray-500">
                {{ feature.description }}
              </dd>
            </div>
          </div>
        </div>
      </div>
    </div>
  </template>
  
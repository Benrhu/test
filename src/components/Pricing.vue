<script>
import { CheckIcon } from "@heroicons/vue/20/solid";

export default {
  name: 'Pricing',
};
</script>

<template>
  <div class="bg-white py-24 sm:py-32">
    <section class="py-6 dark:bg-customGray dark:text-gray-50">
		<div class="container mx-auto flex flex-col items-center justify-center max-w-lg p-4 lg:max-w-full sm:p-10 lg:flex-row">
			<div class="flex flex-col items-center justify-center flex-1 p-4 pb-8 sm:p-8 lg:p-16 dark:bg-gray-900">
				<span class="text-sm">Basic</span>
				<p class="text-5xl font-bold text-center">39€</p>
				<p class="font-semibold text-center">Nemo deserunt possimus quo provident recusandae! Dolores qui architecto omnis pariatur eos voluptatibus sequi cum, non nesciunt aspernatur a?</p>
				<button class="px-8 py-3 mt-6 text-lg font-semibold border rounded sm:mt-12 dark:border-gray-700">Sign up</button>
			</div>
			<div class="flex flex-col items-center justify-center flex-1 p-4 pb-8 text-center rounded-md sm:p-8 lg:p-16 dark:bg-violet-400 dark:text-gray-900">
				<span class="text-sm font-semibold">Advanced</span>
				<p class="text-5xl font-bold">89€</p>
				<p class="font-semibold">Nemo deserunt possimus quo provident recusandae! Dolores qui architecto omnis pariatur eos voluptatibus sequi cum, non nesciunt aspernatur a?</p>
				<button class="px-8 py-3 mt-6 text-lg font-semibold rounded sm:mt-12 dark:bg-gray-800 dark:text-gray-50">Sign up</button>
			</div>
		</div>
	</section>
  </div>
</template>

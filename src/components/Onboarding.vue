<script setup>
import "@fontsource/roboto/500.css";
import "@fontsource/roboto/700.css";
</script>

<template>
  <section class="bg-white dark:bg-black py-20">
    <div class="container">
      <img
        src="../assets/favicon.png"
        alt="logo"
        class="rounded-full w-20 mx-auto mb-9"
      />
      <div class="text-center mb-20">
        <p
          class="text-base leading-normal font-medium text-black dark:text-white mb-6"
        >
          Greetings, meatbag.
        </p>
        <p class="text-xl leading-none font-medium dark:text-white mb-0">
          I, <span class="text-2xl font-bold uppercase">Carrot</span>, am
        </p>
        <p class="text-xl leading-none font-medium dark:text-white mb-6">
          your new weather bot.
        </p>
        <p
          class="text-xs leading-normal font-normal text-gray-400 dark:text-white px-20 sm:px-10 mb-3"
        >
          Please note that any extreme weather your experience after downloading
          me is not at all coincidental.
        </p>
      </div>
      <!-- button, terms & conditions start here -->
      <div class="mx-auto text-center">
        <button class="bg-blue-500 text-white rounded-full px-12 py-3 mb-5">
          Countinue
        </button>
        <p
          class="text-xs leading-normal font-normal text-black dark:text-white px-20 mb-3"
        >
          By tapping Continue, you agree to the
          <a href="" class="text-blue-500 underline">Terms of Use</a> and
          <a href="" class="text-blue-500 underline">Privacy Policy</a>.
        </p>
      </div>
      <!-- button, terms & conditions stop here -->
    </div>
  </section>
</template>

<style scoped></style>

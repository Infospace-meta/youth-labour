<template>
  <section class="py-10 lg:py-20 max-w-6xl mx-auto px-4 sm:px-8">
    <h2 class="text-2xl font-semibold leading-tight text-black sm:text-3xl">
      About You
    </h2>
    <div class="grid grid-cols-1 sm:grid-cols-2 gap-10">
      <!-- Text -->
      <div>
        <ul class="pt-10 space-y-10">
          <li class="flex space-x-2">
            <img
              class="w-6 h-6"
              src="@/assets/icons/check2-circle.svg"
              alt="icon"
            />
            <p class="text-lg">Hardworker</p>
          </li>
          <li class="flex space-x-2">
            <img
              class="w-6 h-6"
              src="@/assets/icons/check2-circle.svg"
              alt="icon"
            />
            <p class="text-lg">Between 18-35 and in good health</p>
          </li>
          <li class="flex space-x-2">
            <img
              class="w-6 h-6"
              src="@/assets/icons/check2-circle.svg"
              alt="icon"
            />
            <p class="text-lg">Any level of skills</p>
          </li>
          <li class="flex space-x-2">
            <img
              class="w-6 h-6"
              src="@/assets/icons/check2-circle.svg"
              alt="icon"
            />
            <p class="text-lg">Looking for better future</p>
          </li>
        </ul>
      </div>
      <!-- Image -->
      <div>
        <img
          class="w-full h-full rounded-2xl"
          src="../assets/images/about-you.avif"
          alt="Image Description"
        />
      </div>
    </div>
  </section>
</template>

<script setup></script>

<style lang="scss" scoped></style>

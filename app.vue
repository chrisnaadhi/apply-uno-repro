<template>
  <div class="main">
    <section class="one">One</section>
    <section class="two">Two</section>
    <section class="three">Three</section>
  </div>
</template>

<style>
.main {
  @apply flex flex-row items-center justify-center;
}
section {
  @apply h-screen w-full;
}
.one {
  @apply bg-red-500 text-white md:bg-blue-500 xl:bg-orange-5;
}

.two {
  @apply bg-gray-500 text-white md:bg-amber xl:bg-red-5;
}

.three {
  @apply bg-purple-5 text-white md:bg-yellow-5 xl:bg-green-5;
}
</style>

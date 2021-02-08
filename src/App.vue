<template>
<div class="min-h-screen flex flex-col justify-center items-center">
<header class="flex flex-col w-full container">
  <h1 class="text-6xl font-bold text-red-500 text-center">My To Do App!</h1>
  <input class="text-3xl py-2 px-4 rounded-xl w-full mt-8" type="text" placeholder="New Todo" />
</header>
<main class="container w-full mt-8 space-y-8 space-y-8">
  <section class="space-y-4">
  <h3 class="text-3xl font-thin text-green-800">Pending Items</h3>
  <ul class="">
    <li class="bg-white rounded-xl text-2xl py-2 px-4 font-bold text-green-800 text-center hover:text-white hover:bg-green-800 cursor-pointer transition-colors">One</li>
  </ul>
  </section>
  <section class="space-y-4">
  <h3 class="text-3xl font-thin text-red-900">Pending Items</h3>
    <ul>
    <li class="bg-white rounded-xl text-2xl py-2 px-4 font-bold text-red-800 text-center hover:text-white hover:bg-red-800 cursor-pointer transition-colors">Two</li>
  </ul>
  </section >
</main>
</div>
</template>

<script setup></script>

<template>
    <nav class="bg-blue-500 text-white p-4">
      <div class="container mx-auto flex justify-between items-center">
        <h1 class="text-xl font-bold">My Nuxt App</h1>
        <ul class="flex space-x-4">
          <li><NuxtLink to="/" class="hover:underline">Home</NuxtLink></li>
          <li><NuxtLink to="/about" class="hover:underline">About</NuxtLink></li>
          <li><NuxtLink to="/contact" class="hover:underline">Contact</NuxtLink></li>
        </ul>
      </div>
    </nav>
  </template>
  
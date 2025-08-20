<template>
  <section class="mb-8">
    <h2 class="text-xl font-semibold border-b pb-2 mb-4">Projects</h2>
    <div>
      <a href="https://ryfazrin.github.io/" class="flex justify-items-center" target="_blank">
        <b>Integration Test Tools for Front-end Developer</b> <Link class="w-4 ml-1" />
      </a>
      <p class="text-gray-700 ml-4">
        The combination of Node.js, Jest, Playwright, Istanbul.js, and Docker enables front-end developers to run end-to-end tests independently, improving code quality.
      </p>
    </div>
    <div class="mt-2">
      <a href="https://web-worker.vercel.app/" class="flex justify-items-center" target="_blank">
        <b>Measure Main thread dan Web worker</b> <Link class="w-4 ml-1" />
      </a>
      <p class="text-gray-700 ml-4">
        Measure the performance of Main Thread and Web Worker for optimized website responsiveness in 2024.
      </p>
    </div>
    <div class="mt-2">
      <a href="https://drive.google.com/drive/folders/14YItogHB6-M266aQVxoGkZKSisAskvUK" class="flex justify-items-center" target="_blank">
        <b>MindGuard - Mental Health Chatbot</b> <Link class="w-4 ml-1" />
      </a>
      <p class="text-gray-700 ml-4">
        An AI-powered chatbot designed to support mental health through interactive conversations.
      </p>
    </div>
    <div class="mt-2">
      <a href="https://colab.research.google.com/drive/1Stt3--JXtzTGYKaGodq9qlmojHSSpWO9?usp=sharing" class="flex justify-items-center" target="_blank">
        <b>Image Clasification</b> <Link class="w-4 ml-1" />
      </a>
      <p class="text-gray-700 ml-4">
        A machine learning system that categorizes images based on visual features.
      </p>
    </div>
  </section>
</template>

<script lang="ts" setup>
import { Link } from 'lucide-vue-next'
</script>
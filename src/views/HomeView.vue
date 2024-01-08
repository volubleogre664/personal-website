<style src="@/styles/views/HomeView.scss"></style>

<template>
  <div class="home">
    <main class="home__hero">
      <div>
        Hey I am Nduduzo Shabalala <br />
        I just love building beautiful products that are simple to use
      </div>

      <div>
        <RouterLink to="/projects">see my projects</RouterLink>
        <span>OR</span>
        <RouterLink to="/about">learn more about me</RouterLink>
      </div>
    </main>

    <footer>
      Wanna see a cool feature for my fellow devs?
      <button>
        Try navigating the website with the built-in command prompt
      </button>
    </footer>
  </div>
</template>

<script setup lang="ts"></script>

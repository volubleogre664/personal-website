<template>
  <header class="app__header">
    <nav>
      <div class="nav__logo">
        <RouterLink to="/">
          <span>Watashi Wa</span>
          <span>Ndu Desu</span>
        </RouterLink>
      </div>

      <div class="nav__links">
        <ul>
          <li>
            <RouterLink to="/about">About</RouterLink>
          </li>
          <li>
            <RouterLink to="/projects">Projects</RouterLink>
          </li>
        </ul>
      </div>

      <!-- TODO Replace the play with the play icon -->
      <div class="app__reelContainer">
        <button class="app__reel">PLAY</button>
      </div>
    </nav>
  </header>
</template>

<script setup lang="ts"></script>

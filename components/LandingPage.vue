<script lang="ts" setup>
  import './LandingPage.scss';
</script>
<template>
  <main class="landing-page">
    <div class="items-container">
      <div class="item item--forest">
        <div class="item__screen item__screen--full"></div>
        <div class="item__screen item__screen--clip"></div>
      </div>

      <div class="item item--image">
        <div class="item__screen item__screen--full"></div>
        <div class="item__screen item__screen--clip"></div>
      </div>
    </div>
    <img class="landing-page__mirror" src="/img/mirror.png" alt="mirror"/>
  </main>
</template>

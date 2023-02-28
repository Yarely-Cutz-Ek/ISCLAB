<script setup>
import Texto from './components/Texto.vue'
import logo from './components/logo.vue'
import pregunta from './components/pregunta.vue'
import pregunta2 from './components/pregunta2.vue'
import pregunta3 from './components/pregunta3.vue'
import card from './components/card.vue'
</script>

<template>
  <header>
    <!--<img alt="Vue logo" class="logo" src="./assets/logo.svg" width="125" height="125" />-->

    <div class="wrapper">
      <logo/>
      <Texto />
    </div>
  </header>
  <main>
    <pregunta/>
    <pregunta2/>
    <pregunta3/>
    <card/>
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>

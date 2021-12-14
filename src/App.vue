<template>
  <div id="app">
    <Header />
    <Jumbo-main />
    <SpecialMenu />
    <PizzaBuilder />

  </div>
</template>

<script>

import Header from './components/Header.vue';
import JumboMain from './components/JumboMain.vue';
import SpecialMenu from './components/SpecialMenu.vue';
import PizzaBuilder from './components/PizzaBuilder.vue';

export default {
  name: 'App',
  components: {
    Header,
    JumboMain,
    SpecialMenu,
    PizzaBuilder
  }
}
</script>

<style lang="scss">

@import './assets/style/vars.scss';

@import '~bootstrap';

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

</style>

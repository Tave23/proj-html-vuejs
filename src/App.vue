<template>
  <div id="app">
    <Header />
    <Jumbo-main />
    <SpecialMenu />
    <PizzaBuilder />
    <StaffPizza/>
    <ChoosePizza/>

  </div>
</template>

<script>

import Header from './components/Header.vue';
import JumboMain from './components/JumboMain.vue';
import SpecialMenu from './components/SpecialMenu.vue';
import PizzaBuilder from './components/PizzaBuilder.vue';
import StaffPizza from './components/StaffPizza.vue';
import ChoosePizza from './components/ChoosePizza.vue';

export default {
  name: 'App',
  components: {
    Header,
    JumboMain,
    SpecialMenu,
    PizzaBuilder,
    StaffPizza,
    ChoosePizza
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

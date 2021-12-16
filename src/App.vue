<template>
  <div id="app">
    <Header :centralLeftLinkList='centralLeftLinkHeader' :centralRightLinkList='centralRightLinkHeader'/>
    <Jumbo-main />
    <SpecialMenu />
    <PizzaBuilder />
    <StaffPizza/>
    <ChoosePizza/>
    <PizzaDeals/>    
    <Forum/>    
    <Footer :listAddress='footerAddress'/>    
    
  </div>
</template>

<script>

import Header from './components/Header.vue';
import JumboMain from './components/JumboMain.vue';
import SpecialMenu from './components/SpecialMenu.vue';
import PizzaBuilder from './components/PizzaBuilder.vue';
import StaffPizza from './components/StaffPizza.vue';
import ChoosePizza from './components/ChoosePizza.vue';
import PizzaDeals from './components/PizzaDeals.vue';
import Forum from './components/Forum.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    JumboMain,
    SpecialMenu,
    PizzaBuilder,
    StaffPizza,
    ChoosePizza,
    PizzaDeals,
    Forum,
    Footer
  },
  data(){
    return{
      centralLeftLinkHeader:[
        "home",
        "pages",
        "menu",
      ],
      centralRightLinkHeader:[
        "event",
        "blog",
        "landing",
      ],
      footerAddress:[
        '1614 E. Bell Rd #104. Salerno, AZ 85022 (602) 867-1010',
        '204 E. Piazzetta Tommaso Sorrento, AZ 85022 (358) 867-1010',
        'Viale Puglia 54 Torre del Greco,  AZ 85022 (359) 867-1010',
        'Corso Itali AA Naples, AZ 85022 (989) 867-1010',

      ]
    }
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

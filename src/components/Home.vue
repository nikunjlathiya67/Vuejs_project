<template>
  <div>
    <FirstContainer />
    <IndianTraditional />
    <NewTest />
    <IndiaPlate />
    <TraditionalCarausal />
    <DiscoverMenu />
    <BookUp />
    <BookHere />
    <BookBottom />
    <MenuCard />
    <Quotes />
    <Footer />
  </div>
</template>
<script>
import BookBottom from './BookBottom.vue';
import BookHere from './BookHere.vue';
import BookUp from './BookUp.vue';
import DiscoverMenu from './DiscoverMenu.vue';
import FirstContainer from "./FirstContainer.vue";
import Footer from './Footer.vue';
import IndianTraditional from "./IndianTraditional.vue"
import IndiaPlate from './IndiaPlate.vue';
import MenuCard from './MenuCard.vue';
import NewTest from './NewTest.vue';
import Quotes from './Quotes.vue';
import TraditionalCarausal from './TraditionalCarausal.vue'
export default {
  components: {
    FirstContainer,
    IndianTraditional,
    NewTest,
    IndiaPlate,
    TraditionalCarausal,
    DiscoverMenu,
    BookUp,
    BookHere,
    BookBottom,
    MenuCard,
    Quotes,
    Footer,
  },
  name: "Home",
};
</script>
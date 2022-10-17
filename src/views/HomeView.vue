<template>
  <div class="home">
    <Header23Paskil />
    <Hero23Paskil />
    <Banner23Paskil />
    <Instagram23Paskil />
    <Partner23Paskil />
    <Footer23Paskil />
  </div>
</template>

<script>
import Header23Paskil from '../components/Header23Paskil.vue';
import Hero23Paskil from '../components/Hero23Paskil.vue';
import Banner23Paskil from '../components/Banner23Paskil.vue';
import Instagram23Paskil from '../components/Instagram23Paskil.vue';
import Partner23Paskil from '../components/Partner23Paskil.vue';
import Footer23Paskil from '../components/Footer23Paskil.vue';

export default {
  name: 'HomeView',
  components: {
    Header23Paskil,
    Hero23Paskil,
    Banner23Paskil,
    Instagram23Paskil,
    Partner23Paskil,
    Footer23Paskil,
  },
};
</script>

<template>
  <NavBar/>
  <Hero />
  <MiddleNav/>
  <Feature/>
  <ChoosePlan/>
</template>
<script>
import NavBar from './components/Nav.vue'
import MiddleNav from './components/MiddleNav.vue'
import Hero from './views/Hero.vue'
import Feature from './views/Feature.vue'
import ChoosePlan from './views/ChoosePlan.vue'
export default{
      components: {
              NavBar,
              Hero,
              MiddleNav,
              Feature,
              ChoosePlan
            },
}
</script>
<style>
</style>
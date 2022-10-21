<template>
  <div>
    <NavBar />
    <TheHeader />
    <TheTeasers />
    <Features />
    <TheFooter />
  </div>
</template>

<script>
import NavBar from '~/components/NavBar.vue'
import TheHeader from '~/components/TheHeader.vue'
import TheTeasers from '~/components/TheTeasers.vue'
import Features from '~/components/Features.vue'
import TheFooter from '~/components/TheFooter.vue'

export default {
  name: 'IndexPage',
  components: {
    NavBar,
    TheHeader,
    TheTeasers,
    Features,
    TheFooter
  }
}
</script>

<style>

@import '@/assets/css/index.css';
@import '@/assets/css/flexbox.css';

</style>

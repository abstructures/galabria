<template>
  <div>
    <top-header/>
    <main id="main" role="main">
      <nuxt/>
    </main>
    <bottom-footer/>
  </div>
</template>

<script>
import TopHeader from '~/components/TopHeader.vue'
import BottomFooter from '~/components/BottomFooter.vue'

export default {
  components: {
    TopHeader,
    BottomFooter
  }
}
</script>

<style lang="scss">
  html {
    font-family: 'Neutron', serif;
  }
</style>
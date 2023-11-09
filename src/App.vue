<template>
  <AppTitle/>
  <AppHero/>
</template>

<script>
import AppTitle from './components/appTitle.vue'
import AppHero from './components/appHero.vue'

export default {
  components: {
      AppTitle,
      AppHero
    },
  data () {
    return {}
  }
}
</script>

<style lang="css" scoped>

</style>
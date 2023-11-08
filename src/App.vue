<template>
  <appTitle/>
  <appHero/>
</template>

<script>
import appTitle from './components/appTitle.vue'
import appHero from './components/appHero.vue'

export default {
  components: {
      appTitle,
      appHero
    },
  data () {
    return {}
  }
}
</script>

<style lang="css" scoped>

</style>
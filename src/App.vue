<script>
import AppHeader from "./components/Header/AppHeader.vue"
import AppMain from "./components/Main/AppMain.vue"
import AppFooter from "./components/Main/AppMain.vue"

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
  },

  data() {
    return {
    }
  }
}
</script>

<template>
    <AppHeader />
    <AppMain />
    <AppFooter />
</template>

<style lang="scss">


</style>
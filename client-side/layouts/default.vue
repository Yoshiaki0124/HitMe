<template>
  <v-app>
    <the-header />
    <v-main>
    <nuxt />
    </v-main>
    <the-footer />
  </v-app>
</template>

<script>
import theHeader from "~/components/layout/TheHeader.vue"
import theFooter from "~/components/layout/TheFooter.vue"

export default {
  components:{
    theHeader,
    theFooter,
  },
  
}
</script>


<style>


</style>

<template>
  <div id="app">
    <h1>First!</h1>
  </div>
</template>
import { mapGetters, mapMutations, mapActions } from 'vuex'

export default {
  name: 'App',

  data () {
    return {
    }
  },

  computed: {
    ...mapGetters({
    }),

    sample: {
      get () { return '' },
      set (newValue) {}
    }
  },

  components: {
  },

  methods: {
    ...mapMutations({
    }),
    ...mapActions({
    })
  },

  created () { console.log('CALL created()') },
  mounted () { console.log('CALL mounted()') },
  activated () { console.log('CALL activated()') },
  deactivated () { console.log('CALL deactivated()') },
  destroyed () { console.log('CALL destroyed()') }
}
<style>
</style>
<style scoped>
</style>

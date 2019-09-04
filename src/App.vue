<template>
  <v-app>
    <Header/>
    <v-content>
      <v-container
        class="fill-height"
        fluid
      >
        <router-view></router-view>
      </v-container>
    </v-content>

    <v-footer
      app
      color="#BC104E"
      class="white--text"
    >
      <span>Cash.Счетчик</span>
      <div class="flex-grow-1"></div>
      <span>&copy; 2019</span>
    </v-footer>
  </v-app>
</template>

<script>
import Header from './components/Header'

export default {
  name: 'App',
  components: {
    Header
  },
  data: () => ({
  })
}
</script>

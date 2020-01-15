<template>
  <div id="app">
    <Header/>
    <router-view></router-view>
    <Footer/>
  </div>
</template>

<script>
import Router from 'vue-router'
import Header from './components/Header'
import Footer from './components/Footer'
import home from './components/Home'
import blogs from './components/Blogs'
import ourTeam from './components/Our-team'

const routes = [
  { path: '/', component: home },
  { path: '/home', component: home },
  { path: '/blogs', component: blogs },
  { path: '/ourTeam', component: ourTeam },
]

const router = new Router({
  routes: routes,
  mode: 'history'
})

export default {
  name: 'app',
  router,
  components: {
    Header,
    Footer
  }
}
</script>

<style>

</style>

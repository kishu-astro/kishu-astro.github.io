<template>
  <div>
    <Jumbotron />
    <Navbar />
    <div>
      <Top />
      <Price />
      <Guides />
    </div>
  </div>
</template>

<script>
import Jumbotron from 'components/organisms/Jumbotron'
import Navbar from 'components/organisms/Navbar'
import Top from 'components/organisms/Top'
import Price from 'components/organisms/Price'
import Guides from 'components/organisms/Guides'

export default {
  name: 'Page',
  components: { Jumbotron, Navbar, Top, Price, Guides },
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

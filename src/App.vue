<template>
  <div id="app">
    <Nav/>
    <Header/>
    <Topics/>
    <Dates/>
    <Chairs/>
    <Committee/>
    <Registration/>
    <Footer/>
  </div>
</template>

<script>
import Nav from './components/Nav.vue'
import Topics from './components/Topics.vue'
import Dates from './components/Dates.vue'
import Chairs from './components/Chairs.vue'
import Committee from './components/Committee.vue'
import Footer from './components/Footer.vue'
import Header from './components/Header.vue'
import Registration from './components/Registration.vue'

export default {
  name: 'app',
  components: {
    Nav, Header, Topics, Dates, Committee, Chairs, Registration, Footer
  }
}
</script>

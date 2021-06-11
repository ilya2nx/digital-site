<template>
  <div id="app">
    <Header />
    <Numbers />
    <LearningFormats />
    <Feedback />
    <Partners />
    <ProcessPhotos />
    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Numbers from './components/Numbers.vue'
import LearningFormats from './components/LearningFormats.vue'
import Feedback from './components/Feedback.vue'
import Partners from './components/Partners.vue'
import ProcessPhotos from './components/ProcessPhotos.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header, Numbers, LearningFormats, Feedback, Partners, ProcessPhotos, Footer
  }
}
</script>

<style lang="scss">

</style>

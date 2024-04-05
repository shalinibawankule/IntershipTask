<template>
  <HomePage/>
  <StudentSection/>
  <TeacherSection/>
  <footerSection/>
</template>

<script>
import HomePage from './components/HomePage.vue'
import StudentSection from './components/StudentSection.vue'
import  TeacherSection from './components/TeacherSection.vue'
import  footerSection from './components/footerSection.vue'


export default {
  name: 'App',
  components: {
  HomePage,
  StudentSection,
  TeacherSection,
  footerSection
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

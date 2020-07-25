<template>
  <div class="home">
    <FirstSection/>
    <Goal/>
    <Services/>
    <Contact/>
  </div>
</template>

<script>
// @ is an alias to /src
import FirstSection from '@/components/FirstSection.vue'
import Goal from '@/components/Goal.vue'
import Services from '@/components/Services.vue'
import Contact from '@/components/Contact.vue'

export default {
  name: 'Home',
  components: {
    FirstSection,
    Goal,
    Services,
    Contact
  }
}
</script>

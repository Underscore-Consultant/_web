<template>
  <div class="home">
    <FirstSection/>
    <Goal/>
    <Services/>
  </div>
</template>

<script>
// @ is an alias to /src
import FirstSection from '@/components/FirstSection.vue'
import Goal from '@/components/Goal.vue'
import Services from '@/components/Services.vue'

export default {
  name: 'Home',
  components: {
    FirstSection,
    Goal,
    Services
  }
}
</script>

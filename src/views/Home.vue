<template>
  <div class="home">
    <FirstSection/>
  </div>
</template>

<script>
// @ is an alias to /src
import FirstSection from '@/components/FirstSection.vue'

export default {
  name: 'Home',
  components: {
    FirstSection
  }
}
</script>

<template>
  <div class="about">
    <Globe 
      v-model="activeCountryCode" 
    />
    <h1>This is an about page</h1>
  </div>
</template>

<script>
import Globe from '@/components/Globe.vue';

export default {
  name: 'globe-view',
  components: {
    Globe,
  },
  data() {
    return {
      activeCountryCode: null
    };
  },
}
</script>
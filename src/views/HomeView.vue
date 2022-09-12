<template>
  <div>
    <Banner/>
    <div class="main-container">
      <h1>Monte seu lanche</h1>
      <Forms/>
    </div>
  </div>
</template>

<script>
import Banner from '../components/Banner.vue';
import Forms from '@/components/Forms.vue';

export default {
  name: 'Home',
  components: {
    Banner,
    Forms
}
}
</script>
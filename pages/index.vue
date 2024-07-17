<template>
  <!-- <splashscreen /> -->
  <loginView />
</template>
<script>
import splashscreen from '../components/splashscreen.vue'
import loginView from '~/components/enroll/loginView.vue';
export default{
  name: 'Home',
  components: {
    splashscreen,
    loginView
  },
}
</script>
<style>

</style>
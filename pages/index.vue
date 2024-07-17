<template>
  <!-- <splashscreen /> -->
  <!-- <loginView /> -->
   <forgotPassword />
</template>
<script>
import splashscreen from '../components/splashscreen.vue'
import loginView from '~/components/enroll/loginView.vue'
import forgotPassword from '~/components/enroll/forgotPassword.vue';

export default{
  name: 'Home',
  components: {
    splashscreen,
    loginView,
    forgotPassword,
  },
}
</script>
<style>

</style>
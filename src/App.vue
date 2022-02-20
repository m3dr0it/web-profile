<template>
<div class=' container shadow-md mx-auto h-full bg-white dark:bg-slate-900'>
  <Header/>
</div>
</template>

<script>
import './index.css';
import Header from './components/header.vue';

export default {
  name: 'App',
  components: {
    Header,
  },
};
</script>

<style lang="stylus">
#app
  font-family Avenir, Helvetica, Arial, sans-serif
  -webkit-font-smoothing antialiased
  -moz-osx-font-smoothing grayscale
  text-align center
  color #2c3e50
  margin-top 60px
</style>

<template>
  <div id="app">
    <div id="cover"></div>
    <m-header></m-header>
    <todo></todo>
    <m-footer></m-footer>
  </div>
</template>

<script type="text/ecmascript-6">
import MHeader from './todo/header.vue'
import MFooter from './todo/footer.jsx'
import todo from './todo/todo.vue'

export default {
  data () {
    return {

    };
  },
  components: {
    MHeader,
    MFooter,
    todo
  }
};
</script>

<style rel="stylesheet/stylus" lang="stylus" scoped>
#app
  position absolute
  left 0
  right 0
  top 0
  bottom 0
  #cover
    position absolute
    left 0
    top 0
    right 0
    bottom 0
    background-color #999
    opacity 0.9
    z-index -1
</style>

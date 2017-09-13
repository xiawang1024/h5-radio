<template>
  <div class="app">
    <keep-alive>
      <home></home>
    </keep-alive>
  </div>
</template>

<script>
import Home from "@/components/home"
export default {
  name:'app',
  components:{
    Home
  }
}
</script>

<style lang="stylus" scoped>

</style>


<template>
  <div class="header">
    <div class="header-left">back</div>
    <div class="header-input">search</div>
    <div class="header-right">city</div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
  .header
    display: flex
    height: .86rem
    line-height: .86rem
    background: #2a95dd
    color: #fff
    .header-left
      width: .64rem
      float: left
    .header-input
      flex: 1
      height: .64rem
      line-height: .64rem
      border-radius: .1rem
      margin-top: .12rem
      margin-left: .1rem
      background: #fff
      color: #ccc
    .header-right
      width: 1.24rem
      float: right
      text-align: center
</style>

<template>
  <div class="header">
    <div class="header-left">
      <div class="iconfont back-icon">&#xe601;</div>
    </div>
    <div class="header-input">
      <span class="iconfont search-icon">&#xe627;</span>
      输入城市/景点/游玩主题
    </div>
    <div class="header-right">
      <span class="iconfont menu-icon">&#xe786;</span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style lang="stylus" scoped>
  @import '~styles/varibles.styl'
  .header
    display: flex
    height: .86rem
    line-height: .86rem
    background: $bgColor
    color: #fff
    .header-left
      width: .88rem
      float: left
      .back-icon
        font-size: .36rem
        text-align: center
    .header-input
      flex: 1
      height: .64rem
      line-height: .64rem
      border-radius: .1rem
      margin-top: .12rem
      margin-left: .1rem
      padding-left: .2rem
      background: #fff
      color: #ccc
      .search-icon
        font-size: .32rem
        margin-right: .06rem
    .header-right
      width: .88rem
      float: right
      text-align: center
      .menu-icon
        font-size: .4rem
</style>

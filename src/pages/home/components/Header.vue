<template>
    <div class="header">
      <div class="header-left">
        <div class="iconfont iconleft back-icon"></div>
      </div>
      <div class="header-input">
        <span class="iconfont iconsearch"></span> 输入城市/景点/游玩主体
      </div>
      <div class="header-right">
        城市
        <span class="iconfont iconcaret-down arrow-down-icon"></span>
      </div>
    </div>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<style lang="stylus" scoped>
@import "~styles/varibles.styl"
.header
  display: -webkit-flex;
  display: flex
  height: .86rem
  background: $mainColor
  color: #fff
  line-height: .86rem
  .header-left
    width: .64rem
    float: left
    .back-icon
      text-align center
  .header-input
    flex: 1
    height: .64rem
    line-height: .64rem
    border-radius: .1rem
    margin-top: .12rem
    margin-left: .2rem
    background-color: #fff
    color: #ccc
    padding-left .2rem
  .header-right
    width: 1.24rem
    float: right
    text-align center
    .arrow-down-icon
      margin-left: -.04rem
      font-size: .24rem
</style>

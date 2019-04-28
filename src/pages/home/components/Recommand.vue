<template>
  <div>
    <div class="recommand-title">猜你喜欢</div>
    <ul>
      <li class="recommand-item border-bottom" v-for="item of recommandList" :key="item.id">
        <img :src="item.imgUrl" class="recommand-item-img">
        <div class="recommand-item-info">
          <p class="recommand-item-title">{{item.title}}</p>
          <p class="recommand-item-desc">{{item.desc}}</p>
          <button class="recommand-item-button">查看详情</button>
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HomeRecommand',
  data () {
    return {
      recommandList: [{
        id: '0001',
        imgUrl: 'http://img1.qunarzz.com/sight/p0/1904/65/65a949083122447da3.img.jpg_200x200_c4b2f699.jpg',
        title: '大连圣亚海洋世界',
        desc: '浪漫大连首战，浪漫的海洋主题公园'
      }, {
        id: '0002',
        imgUrl: 'http://img1.qunarzz.com/sight/p0/1904/65/65a949083122447da3.img.jpg_200x200_c4b2f699.jpg',
        title: '大连圣亚海洋世界',
        desc: '浪漫大连首战，浪漫的海洋主题公园'
      }, {
        id: '0003',
        imgUrl: 'http://img1.qunarzz.com/sight/p0/1904/65/65a949083122447da3.img.jpg_200x200_c4b2f699.jpg',
        title: '大连圣亚海洋世界',
        desc: '浪漫大连首战，浪漫的海洋主题公园'
      }, {
        id: '0004',
        imgUrl: 'http://img1.qunarzz.com/sight/p0/1904/65/65a949083122447da3.img.jpg_200x200_c4b2f699.jpg',
        title: '大连圣亚海洋世界',
        desc: '浪漫大连首战，浪漫的海洋主题公园'
      }]
    }
  }
}
</script>

<style scoped lang="stylus">
@import "~styles/mixins.styl"
.recommand-title
  line-height .8rem
  background #eee
  text-indent .2rem
  margin-top .2rem
.recommand-item
  display flex
  height 1.88rem
  overflow hidden
  .recommand-item-img
    width 1.7rem
    height 1.7rem
    padding .1rem
  .recommand-item-info
    flex 1
    padding .1rem
    min-width 0
    .recommand-item-title
      font-size: .32rem
      ellipsis()
      line-height: .54rem
    .recommand-item-desc
      line-height .4rem
      ellipsis()
      color: #ccc
    .recommand-item-button
      background #ff9300
      line-height .44rem
      padding 0 .2rem
      border-radius .06rem
      margin-top: .16rem
      color: #ffffff
</style>

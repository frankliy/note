<template>
    <div class="header">
        <div class="header-left">
          <span class="iconfont back-icon">&#xe604;</span>
        </div>
        <div class="header-input">
          <span class="iconfont">&#xe615;</span>
          输入城市景点/游玩/主题
        </div>
        <router-link to="city">
          <div class="header-right">
            {{this.city}}
            <span class="iconfont arrow-icon">&#xe64a;</span>
          </div>
        </router-link>
    </div>
</template>

<script>
import { mapState } from 'vuex'
export default {
  name: 'HomeHeader',
  computed: {
    ...mapState(['city'])
  }
}
</script>

<style lang="stylus" scoped>
  @import '~styles/variables.styl'
  .header
    display: flex
    height: $headerHeight
    line-height: .86rem
    background: $bgColor
    color #ffffff
    .header-left
      float: left
      width: .64rem
      .back-icon
        display block
        text-align center
        font-size .4rem
    .header-input
      flex: 1
      height .64rem
      line-height .64rem
      margin-top .12rem
      margin-left .2rem
      padding-left .2rem
      background #fff
      border-radius .1rem
      color #ccc
    .header-right
      min-width: 1.04rem
      padding 0 .1rem
      text-align center
      color #ffffff
      .arrow-icon
        font-size .2rem
</style>

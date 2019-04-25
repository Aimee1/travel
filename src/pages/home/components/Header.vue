<template>
<div class="header">
   <div class="header-left" >
     <div class="iconfont back-icon">&#xe624;</div>
   </div>
   <div class="header-input"> <span class="iconfont">&#xe611;</span>输入城市景点主题</div>
   <div class="header-right">城市 <span class="iconfont arrow-icon">&#xe652;</span></div>
</div>
</template>

<script>
export default {
  name: 'home'
}
</script>

<style lang="stylus" scoped >
  @import "../../../assets/style/varibles.styl";
  .header{height: .86rem;display: flex;background-color: $bgColor;color: #fff;line-height: .86rem}
  .header-left{width: .64rem;float: left;text-align: center;font-size: .4rem}
  .header-right{width: 1.24rem;text-align: center;
    float:right;}
  .header-input{flex: 1;background: #fff;border-radius: 0.1rem;color: #ccc;line-height:.64rem ;padding-left: .2rem;
     margin-top: 0.12rem;height: .64rem;margin-left: .12rem ;font-size: .3rem}
  .arrow-icon{font-size: .24rem;margin-left: -.04rem}
</style>

<template>
<div class="header">
    <div class="header_left">
       成都  <span class="iconfont">&#59050;</span>
    </div>
    <div class="header_input">
      <span class="iconfont">&#xe632;</span>
      输入商家/品类/商圈
    </div>
<div class="index__open">
  <img src="../../../assets/yonghu.png">
   </div>
</div>
</template>

<script>
export default{
  name: 'HomeHeader'
}
</script>

<style scoped>
  .header{
    line-height: .101rem;
    display: flex;
    background-color:#06c1ae
  }
  .header_left {
    width: 15%;
    line-height: 100%;
    margin-left: .1rem;
    margin-top: 1em;
    color: #fff;
    font-size: 1.1em
  }
  .header_input{
    width: 65%;
    border-radius: .1rem;
    padding: .1rem;
    height: .50rem;
    line-height: .55rem;
    margin-top: .12rem;
    margin-bottom: .12rem;
    background-color: #21897d;
    color: #68dbce;
  }
  .index__open{
    width:15%;
    margin-left:.1rem;
    color: #fff;
  }
    .index__open img{
    width:75%;
    margin-left:.1rem;
    color: #fff;

  }
  .back_icon{
    text-align: center;
    }
  .header_right{
    width: 1.24rem;
    float: right;
    text-align: center;
    }
</style>

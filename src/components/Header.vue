<template>
  <div class="header">
    <div class="index">
      <ul>
        <li><a href="javascript:;">首页</a></li>
        <li><a href="javascript:;">义工旅行</a></li>
        <li><a href="javascript:;">旅游日志</a></li>
        <li><a href="javascript:;">联系我们</a></li>
        <li><a href="javascript:;">个人中心</a></li>
      </ul>
      
    </div>
  </div>
</template>
<style scoped>
*{
  margin: 0;
  border: 0
}
    .index{
      width: 100%;
      height: 100px;
      background-color: rgba(90, 90, 90, 0.4)
    }
  li{
    list-style: none;
    
    float: left;
    margin-left: 50px;
    padding-top: 25px;
    font-size: 18px;
    position: relative;
    left: 30%;
  }
  a{
    text-decoration: none;
    color: #fff;
  }
  a:hover,a:active{
    background-color: rgb(57, 58, 58);
    border-radius: 10px
  }
</style>
<script>
export default {
  name:'app-header',
  data(){
    return{

    }
  }
}
</script>

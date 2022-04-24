<template>
  <div class="home">
     <div class="box">
        <li>
          <span>已签约人数</span>
          <span class="s1">1000</span>
        </li>
        <li>
           <span>待签约人数</span>
          <span class="s1">20</span>
        </li>
        <li>
           <span>居民总数</span>
          <span class="s1">1020</span>
        </li>
        <li>
           <span>待处理服务器</span>
          <span class="s1">10</span>
        </li>
        <li>
           <span>服务器总量</span>
          <span class="s1">100</span>
        </li>
        <li>
           <span>服务评价</span>
          <span class="s1">4.9</span>
        </li>
     </div>
     <div class="nav">
       <li >
         <p class="p1">
<i class="iconfont icon-fuwu"></i>
         </p>
         <h4>新建档案</h4>
       </li>
       <li  >
         <p class="p2"> <i class="iconfont icon-dangan"></i></p>
         <h4>签约管理</h4>
       </li>
       <li  >
          <p class="p3"><i class="iconfont icon-guanli"></i></p>
          <h4>服务管理</h4>
       </li>
     </div>
     <div class="qysq">
       <span class="qys">签约申请(3)</span>  <span class="qys1">查看全部 ></span>
     </div>
     <div class="box9">
       <p class="k1"><span>王小明 58岁</span><span style="color:red">待审核</span></p>
        <p>身份证号 155255255655555555</p>
        <p>签约团队 李明明团队</p>
        <p>服务包 老年人服务包</p>
     </div>
      <div class=" box10" >
       <p class="k1"><span>王小明 58岁</span><span style="color:red">待审核</span></p>
        <p>身份证号 155255255655555555</p>
        <p>签约团队 李明明团队</p>
        <p>服务包 老年人服务包</p>
     </div>
     <div class="tabbar">
       <li class="sccl1">
         <i class="iconfont icon-shouye"></i>
         <p>首页</p>
       </li>
       <li> <i class="iconfont icon-juminfuwu"></i>
       <p>居民</p>
       </li>
       <li> <i class="iconfont icon-shouye1"></i>
       <p>消息</p></li>
       <li> <i class="iconfont icon-wode"></i>
       <p>我的</p></li>
     </div>
  </div>
</template>

<script>
export default {
 data() {
   return {
     
   }
 },
}
</script>
<style lang="scss" scoped>
.box10{
  margin: 15px 0 30px 0;
  width: 100%;
  background: #fff;
  padding: 15px;
  box-sizing: border-box;
  line-height: 35px;
  box-shadow: rgb(226, 225, 225) 1px 1px 10px;
  .k1{
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
}
.tabbar{
  display: flex;
  padding: 15px 0;
  justify-content: space-between;
  background: #fff;
  position: fixed;
  width: 100%;
  left: 0;
  right: 0;
  bottom: 0;
  li{
    flex: 1;
    text-align: center;
   
  }
  i{
    font-size: 28px;
    
  }
  p{
    margin-top: 6px;
  }
}
.sccl1{
  i{
     color: #45d5b1;
  }
  p{
    color: #45d5b1;
  }
}
.qysq{
  display: flex;
  justify-content: space-between;
  padding: 15px 0;
  align-items: center;

  .qys{
    font-size: 22px;
  }
  .qys1{
    font-size: 14px;
    color: #ccc;
  }
}
.nav{
  display: flex;
  justify-content: space-between;
  box-sizing: border-box;
  padding: 15px;
  transform: translateY(-6px);
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
  box-shadow: rgb(226, 225, 225) 1px 1px 10px;
  background: #fff;
  i{
    font-size: 38px;
  }
  h4{
    margin-top: 10px;
    font-weight: 400;
  }
  p{
    line-height: 60px;
    text-align: center;
    color: #fff;
    border-radius: 10px;
  }
  .p1{
    width: 60px;
    height: 60px;
    background: #006ef1;
  }
  .p2{
    width: 60px;
    height: 60px;
    background: #fddb78;
  }
  .p3{
    width: 60px;
    height: 60px;
    background: #fa746b;
  }
}
.home{
  box-sizing: border-box;
  padding: 10px;
  width: 100%;
  height: 100%;
}
.box{
  height: 20%;
  background: #45d5b1;
  border-top-left-radius: 15px;
  border-top-right-radius: 15px;
  display: flex;
  flex-wrap: wrap;
  li{
    display: flex;
    flex-direction: column;
    color: #fff;
    height: 50%;
    justify-content: center;
    // align-items: center;
    box-sizing: border-box;
    padding-left: 15px;
    width: 33%;
    .s1{
      font-weight: 600;
      margin-top: 10px;
    }
  }
}
.box9{
  margin-top: 15px;
  width: 100%;
  background: #fff;
  padding: 15px;
  box-sizing: border-box;
  line-height: 35px;
  box-shadow: rgb(226, 225, 225) 1px 1px 10px;
  .k1{
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
}
</style>


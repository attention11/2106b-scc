<!--  -->
<template>
  <div class='about'>
    <div class="topnav">
      <span>←</span>
      <span>新建居民档案</span>
      <span></span>
    </div>
    <div class="jmxx">
      <span>居民基本信息</span>
    </div>
    <div class="box">
      <li>
         <p>真实姓名<span class="xing">*</span></p>
         <input type="text" placeholder="请填写居民的真实姓名">
         <span></span>
      </li>
       <li>
         <p>身份证号<span class="xing">*</span></p>
         <input type="text" placeholder="请填写居民的身份证号">
         <span></span>
      </li>
       <li>
         <p>性别<span class="xing">*</span></p>
         <input type="text" placeholder="请填写居民的性别">
         <span class="sss">></span>
      </li>
       <li>
         <p>出生日期<span class="xing">*</span></p>
         <input type="text" placeholder="请填写居民的出生日期">
         <span class="sss">></span>
      </li>
       <li>
         <p>手机号码<span class="xing">*</span></p>
         <input type="text" placeholder="居民登录账号，请正确填写">
         <span></span>
      </li>
       <li>
         <p>登录密码<span class="xing">*</span></p>
         <input type="text" placeholder="8位以上的数字和字母组合"><span></span>
      </li>
       <li>
         <p>现居地<span class="xing"></span></p>
         <input type="text" placeholder="请填写现居地"><span></span>
      </li>
       <li>
         <p>居民标签<span class="xing"></span></p>
         <input type="text" placeholder="点击选择居民标签"><span></span>
      </li>
    </div>
    <div class="box1">
      <li>高血压</li>
      <li>冠心病</li>
      <li>高血糖</li>
      <li>高血脂</li>
      <li>高血压</li>
      <li>冠心病</li>
      <li>高血糖</li>
      <li>高血脂</li>
    </div>
    <div class="box2">
      <li>
        <p>关联家人</p>
        <input type="text" placeholder="请选择该居民家人信息">
        <span></span>
      </li>
      <li>
        <p>立即签约</p>
        <span></span>
        <i class="iconfont icon-shouye1"></i>
      </li>
    </div>
    <button>下一步</button>
 </div>
</template>
<style lang='scss' scoped>
button{
  height: 40px;
  line-height: 40px;
  background: #43d4af;
  color: #fff;
  border-radius:  10px;
  border: none;
  width: 90%;
  text-align: center;
  display: block;
  margin: 0 auto;
  position: absolute;
  bottom: 0;
  left: 5%;
}
.xing{
  color: red;
}
.box2{
  box-sizing: border-box;
  padding: 0 10px;
  background: #fff;
  li{
    display: flex;
    justify-content: space-between;
    height: 40px;
    align-items: center;
    border-bottom: 2px solid #f4f9fc;
    p{
      width: 20%;
    }
    input{
      width: 70%;
      border: none;
    }
  }
}
.box1{
  padding:  12px 30px 12px 10px;
  display: flex;
  flex-wrap: wrap;
  li{
    width: 22%;
    color: #ccc;
    border: 1px solid #ccc;
    padding: 5px 0;
    text-align: center;
    margin: 7px 5px 7px 0px;
  }
}
.box{
  width: 100%;
  
  .sss{
    float:right;
  }
  li{
    display: flex;
    box-sizing: border-box;
    justify-content: space-between;
    padding: 0 10px;
    height: 45px;
    width: 100%;
    align-items: center;
    background: #fff;
    border-bottom: #f7fafd 2px solid;
    input{
      border: none;
      margin-left: 20px;
      width: 70%;
    }
    p{
      width: 25%;
    }
  }
}
.jmxx{
  padding:  15px 10px;
  font-size: 22px;
}
.topnav{
  display: flex;
  background: #fff;
  justify-content: space-between;
  box-sizing: border-box;
  padding: 0 10px;
  height: 40px;
  align-items: center;
  font-size: 20px;
}
.about{
  height: 100%;
  width: 100%;
  background: #f7fafd;
}
</style>

<!--  -->
<template>
  <div class='xjjm'>
       <div class="topfh">
         <span>⬅</span>
         <span>关联家人信息</span>
         <span style="color:#28d094">完成</span>
     </div>
     <div class="jrxx">
         <span>家人信息</span>
     </div>
      <div class="box">
      <li>
         <p>选择家人<span class="xing"></span></p>
         <input type="text" placeholder="请选择该居民家人信息">
         <span>></span>
      </li>
       <li>
         <p>与本人关系<span class="xing"></span></p>
         <input type="text" placeholder="请选择家人与该居民关系">
         <span>></span>
      </li>
       
    </div>
    <h3>+新增关联家人</h3>
 </div>
</template>


<style lang='scss' scoped>
.xjjm{
    height: 100%;
    background: #f7fafd;
}
h3{
  color: #28d0a2;
  text-align: center;
  margin-top: 20px;
  font-weight: 400;
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
.jrxx{
    background: #f7fafd;
    padding:  30px 0 13px 13px
}
.topfh{
 padding:  13px;
 font-size: 19px;
 display: flex;
 justify-content: space-between;
 background: #fff;
}
</style>
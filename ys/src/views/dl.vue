<!--  -->
<template>
  <div class='dl'>
     <div class="topfh">
         ⬅
     </div>
     <div class="box1">
         <img src="../assets/Snipaste_2022-04-19_22-54-11.png" alt="">
     </div>
     <div class="box2">
         <h2>登录</h2>
         <p>欢迎使用家医医生端</p>
     </div>
     <div class="box3">
         <p>账号</p>
         <input type="text" placeholder="请输入手机号码">
     </div>
     <div class="box3">
         <p>密码</p>
         <input type="text" placeholder="请输入密码">
     </div>
     <div class="box4">
         <input type="checkbox" checked> <span style="color:#ccc">我已阅读并同意</span><span class="s1" style="color:#45d5b1">用户隐私政策</span>
     </div>
     <div class="box5">
         <button>登录</button>
         <p>忘记密码请联系管理员</p>
     </div>
 </div>
</template>


<style lang='scss' scoped>
.box5{
     box-sizing: border-box;
    padding: 10px 15px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-top: 15px;
    button{
        width: 90%;
        height: 40px;
        background: #43d5af;
        border: none;
        color: #fff;
        border-radius: 8px;
    }
    p{
        color: #ccc;
        font-size: 14px;
        margin-top: 50px;
    }
}
.box4{
    box-sizing: border-box;
    padding: 10px 15px;
    display: flex;
    align-items: center;
    font-size: 13px;
    input{
        height: 16px;
        width: 16px;
        background: #43d5af;
        margin-right: 10px;
    }
    .s1{
        margin-left: 5px;
    }
}
.box3{
     box-sizing: border-box;
    padding: 10px 15px;
    input{
        margin-top: 10px;
        border: none;
        padding: 10px;
        background: #f4fcfa;
        color: #ccc;
    }
}
.box2{
    box-sizing: border-box;
    padding: 10px 15px;
    p{
        margin-top: 10px;
        color: #ccc;
    }
}
.topfh{
    margin-top: 20px;
    font-size: 22px;
    box-sizing: border-box;
    padding: 10px 15px;
}
.box1{
    padding: 50px 0;
    display: flex;
    justify-content: center;
    img{
        
    }
}
</style>
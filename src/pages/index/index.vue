<template>
  <view class="page">
    <view class="one">快帮网</view>
    <view class="two">干啥都行，干啥都快 </view>
    <view class="three">
      <view class="kongbai">
        <image class="icon" src="/static/icon/手机@3x.png" />
        <view class="shouji">
          <input style="text" class="haoma" placeholder="手机号码" />
        </view>
      </view>
    </view>
    <view class="four">
      <view class="five">
        <image class="icon" src="/static/icon/123.png" />
        <input style="text" class="yanzheng" placeholder="短信验证码" />
      </view>
      <view class="dongtai">获取动态码</view>
    </view>
    <view class="dengru">
      <view class="six">登入</view>
    </view>
    <view class="seven">立即注册</view>
  </view>
</template>

<style lang="scss" scoped>
.page {
  .one {
    text-align: center;
    margin-top: 100px;

    height: 33px;
    font-size: 24px;

    font-weight: 500;
    color: #f53409;
    line-height: 33px;
  }
  .two {
    text-align: center;
    height: 10px;
    font-size: 15px;
    font-weight: 500;
    color: #ff552e;
    line-height: 33px;
  }
  .three {
    .kongbai {
      width: 80%;
      height: 40px;
      margin-top: 20px;
      margin-left: auto;
      margin-right: auto;
      background: #ffffff;
      border: 4px solid #eeeeee ;
      border-radius: 22px;
      display: flex;
      .icon {
        width: 10px;
        height: 18px;
        padding-top: 12px;
        padding-left: 26px;
      }
    }
  }
  .shouji {
    width: 56px;
    height: 20px;
    font-size: 14px;
    font-weight: 400;
    color: #cccccc;
    line-height: 20px;
    .haoma {
      width: 56px;
      height: 20px;
      font-size: 14px;
      font-weight: 400;
      color: #cccccc;
      line-height: 20px;
      margin-left: 5px;
      margin-top: 10px;
    }
  }
  .four {
    display: flex;
    width: 80%;
    margin-top: 16px;
    margin-left: 38px;

    .five {
      width: 50%;
      height: 20px;
      background: #ffffff;
      border-radius: 2px;
      border: 3px solid #eeeeee;
      display: flex;
      border-radius: 25px;
    }
    .icon {
      width: 13px;
      height: 15px;
      margin-left: 20px;
      margin-top: 2px;
    }
    .yanzheng {
      font-size: 12px;
      color: #cccccc;
      line-height: 20px;
      margin-left: 5px;
    }
  }
  .dongtai {
    width: 40%;
    height: 44px;
    margin-left: 30px;
    background: #ffffff;
    border-radius: 22px;
    border: 3px solid #eeeeee;
    width: 70px;
    height: 20px;
    font-size: 14px;
    font-weight: 500;
    color: #0e8ed8;
    line-height: 20px;
  }
}
.dengru {
  width: 36px;
  height: 20px;
  font-size: 18px;
  font-family: PingFangSC-Medium, PingFang SC;
  font-weight: 500;
  color: #ffffff;
  line-height: 25px;
  text-align: center;
  margin-top: 3px;
  margin-left: 38px;

  .six {
    width: 300px;
    height: 40px;
    background: #ff552e;
    border-radius: 20px;
    margin-top: 30px;
    line-height: 37px;
  }
}
.seven {
  margin-top: 30px;
  margin-left: 158px;
  width: 56px;
  height: 20px;
  font-size: 14px;
  font-family: PingFangSC-Regular, PingFang SC;
  font-weight: 400;
  color: #0e8ed8;
  line-height: 50px;
  text-align: center;
}
</style>

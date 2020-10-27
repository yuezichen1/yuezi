<template>
  <view class="page">
    <view class="yue2">
      <view class="two">合肥 </view>
      <image class="icon0" src="/static/icon/箭头@3x.png" />
      <input style="text" class="three" placeholder="找工作找房子" />
    </view>

    <view class="a">
      <view class="z">
        <image class="icon" src="/static/icon/zhaodian.png" />
        <view class="four">免费找店</view>
      </view>
      <view class="x">
        <image class="icon1" src="/static/icon/fangchang.png" />
        <view class="five">房产</view>
      </view>
      <view class="c">
        <image class="icon2" src="/static/icon/ping.png" />
        <view class="six">招聘</view>
      </view>
      <view class="d">
        <image class="icon3" src="/static/icon/qiuzhi.png" />
        <view class="seven">求职</view>
      </view>
    </view>
    <view class="b">
      <view class="v">
        <image class="icon4" src="/static/icon/bang.png" />
        <view class="eight">万能帮</view>
      </view>
      <view class="n">
        <image class="icon5" src="/static/icon/ershou.png" />
        <view class="nine">二手交易</view>
      </view>
      <view class="m">
        <image class="icon6" src="/static/icon/kuaigou.png" />
        <view class="ten">快购</view>
      </view>
      <view class="q">
        <image class="icon6" src="/static/icon/aixin.png" />
        <view class="ten1">爱心公益 </view>
      </view>
    </view>

    <view class="f">
      <view class="f_yuan"></view>
      <view class="f_yuan"></view>
      <view class="f_yuan"></view>
    </view>
    <view class="f1">
      <view class="g">生意转让 </view>
      <view class="h">房屋出租</view>
      <view class="h">房屋求租</view>
    </view>

    <view class="su">
      <view class="zi">
        <image class="icon7" src="/static/icon/图片@3x.png" />
      </view>
      <view class="yue">
        <view class="si">业主直转！淮河步行街旺铺餐馆</view>
        <view class="so">庐阳-淮河路步行1经营中</view>
        <view class="sp">刘先生 张震牛面馆</view>
      </view>
    </view>
    <view class="su">
      <view class="zi">
        <image class="icon7" src="/static/icon/图片@3x.png" />
      </view>
      <view class="yue">
        <view class="si">业主直转！淮河步行街旺铺餐馆</view>
        <view class="so">庐阳-淮河路步行1经营中</view>
        <view class="sp">刘先生 张震牛面馆</view>
      </view>
    </view>
  </view>
</template>
<style lang="scss" scoped>
.page {
  .yue2 {
    margin-top: 11px;
    display: flex;
    flex-direction: row;

    .two {
      margin-left: 15px;
      align-self: center;
      width: 24px;
      height: 15px;
      font-size: 12px;
      font-weight: 400;
      color: #333333;
    }
    .icon0 {
      width: 10px;
      height: 10px;
      margin-left: 10px;
      transform: rotate(90deg);
      align-self: center;
    }
    .three {
      margin-left: 80px;
      width: 72px;
      height: 15px;
      font-size: 11px;
      font-weight: 400;
      color: #cccccc;
      line-height: 15px;
      background-image: url(/static/icon/搜索框@3x.png);
      background-size: 15px;
      background-repeat: no-repeat;
      padding-left: 20px;
    }
  }
}
.a {
  display: flex;
  flex-direction: row;
  margin-top: 33px;
  .z {
    width: 100px;
    height: 60px;
  }

  .four {
    width: 50px;
    height: 30px;
    font-size: 12px;
    color: #666666;
    margin: 0 auto;
  }
  .icon {
    width: 30px;
    height: 30px;
    margin: 0 auto;
    padding-left: 30px;
  }
  .x {
    width: 100px;
    height: 60px;
  }
  .five {
    width: 24px;
    height: 17px;
    font-size: 12px;
    font-weight: 400;
    color: #666666;
    line-height: 17px;
    margin: 0 auto;
  }
  .icon1 {
    width: 30px;
    height: 30px;
    margin: 0 auto;
    padding-left: 30px;
  }
  .c {
    width: 100px;
    height: 60px;
  }
  .six {
    width: 24px;
    height: 17px;
    font-size: 12px;
    font-weight: 400;
    color: #666666;
    line-height: 17px;
    margin: 0 auto;
  }
  .icon2 {
    width: 30px;
    height: 30px;
    margin: 0 auto;
    padding-left: 30px;
  }
  .d {
    width: 100px;
    height: 60px;
  }
  .seven {
    width: 24px;
    height: 17px;
    font-size: 12px;
    font-weight: 400;
    color: #666666;
    line-height: 17px;
    margin: 0 auto;
  }
  .icon3 {
    width: 30px;
    height: 30px;
    margin: 0 auto;
    padding-left: 30px;
  }
}
.b {
  display: flex;
  flex-direction: row;
  margin-top: 20px;
  .v {
    width: 100px;
    height: 60px;
  }
  .eight {
    width: 36px;
    height: 17px;
    font-size: 12px;
    font-weight: 400;
    color: #666666;
    line-height: 17px;
    margin: 0 auto;
  }
  .icon4 {
    width: 30px;
    height: 30px;
    margin: 0 auto;
    padding-left: 30px;
  }
  .n {
    width: 100px;
    height: 60px;
  }
  .nine {
    width: 48px;
    height: 17px;
    font-size: 12px;
    font-weight: 400;
    color: #666666;
    line-height: 17px;
    margin: 0 auto;
  }
  .icon5 {
    width: 30px;
    height: 30px;
    margin: 0 auto;
    padding-left: 30px;
  }
  .m {
    width: 100px;
    height: 60px;
  }
  .ten {
    width: 24px;
    height: 17px;
    font-size: 12px;
    font-weight: 400;
    color: #666666;
    line-height: 17px;
    margin: 0 auto;
  }
  .q {
    width: 100px;
    height: 60px;
  }
  .icon6 {
    width: 30px;
    height: 30px;
    margin: 0 auto;
    padding-left: 30px;
  }
  .ten1 {
    width: 48px;
    height: 17px;
    font-size: 12px;
    font-weight: 400;
    color: #666666;
    line-height: 17px;
    margin-left: 20px;
  }
}
.f {
  width: 330px;
  height: 80px;
  background: #f8e71c;
  border-radius: 40px;
  margin: 0 auto;
  margin-top: 10px;
  display: flex;
  justify-content: center;
  align-items: flex-end;

  .f_yuan {
    margin: 0 0 8px 8px;
    width: 8px;
    height: 8px;
    background: #ffffff;
    border-radius: 50%;
  }
}
.f1 {
  margin-top: 15px;
  display: flex;
  flex-direction: row;
  border-bottom: 2px solid #adacac66;
  .g {
    width: 65px;
    text-align: center;
    height: 30px;
    font-size: 12px;
    font-weight: 500;
    color: #ff552e;
    margin-left: 20px;
    border-bottom: 2px solid #ff552e;
  }
  .h {
    width: 48px;
    height: 17px;
    font-size: 12px;
    text-align: center;
    font-weight: 400;
    color: #0e8ed8;
    margin-left: 20px;
  }
}

.su {
  display: flex;
  margin-top: 5px;
  .zi {
    .icon7 {
      width: 150px;
      height: 80px;
    }
  }
}
.yue {
  margin-left: 10px;
  .si {
    width: 180px;
    height: 34px;
    font-size: 12px;
    font-weight: 500;
    color: #333333;
    line-height: 25px;
  }
  .so {
    width: 158px;
    height: 17px;
    font-size: 12px;
    font-weight: 400;
    color: #666666;
    line-height: 10px;
  }
  .sp {
    width: 100px;
    height: 17px;
    font-size: 12px;
    font-weight: 400;
    color: #666666;
    line-height: 17px;
  }
}
.chen {
  .chen1 {
    .icon7 {
      width: 150px;
      height: 80px;
    }
  }
}
.chen2 {
  .chen3 {
    width: 180px;
    height: 34px;
    font-size: 12px;
    font-weight: 500;
    color: #333333;
    line-height: 20px;
  }
  .chen4 {
    width: 158px;
    height: 17px;
    font-size: 12px;
    font-weight: 400;
    color: #666666;
    line-height: 10px;
  }
  .chen5 {
    width: 100px;
    height: 17px;
    font-size: 12px;
    font-weight: 400;
    color: #666666;
    line-height: 17px;
  }
}
</style>
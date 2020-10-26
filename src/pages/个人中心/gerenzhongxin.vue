<template>
  <view class="page">
    <view class="yue">
      <view class="zi">
        <view class="z">LIUAIBING</view>
        <image class="icon" src="/static/icon/头像.png" />

        <view class="zi2">
          <view class="zi3">
            <image class="icon1" src="/static/icon/123.png" />
            <view class="x">我的信息</view>
          </view>
          <view class="zi4">
            <image class="icon2" src="/static/icon/发布@3x.png" />
            <view class="c">发布</view>
          </view>
        </view>
        <view class="chen">
          <view class="v">我发布的</view>
        </view>
        <view class="chen1">
          <view class="b">房产</view>
          <view class="n">招聘</view>
          <view class="n">求职</view>
          <view class="n">二手</view>
          <view class="n">万能帮</view>
          <view class="n">快购</view>
          <image class="icon3" src="/static/icon/箭头@3x.png" />
        </view>
      </view>
      <view class="chen2">
        <image class="icon4" src="/static/icon/图片@3x.png" />
        <view class="yue1">
          <view class="q">业主直转！淮河路步行街旺铺餐馆，接手即赚！</view>
          <view class="yue2">
            <view class="w">2020.04.15</view>
            <view class="e">编辑</view>
            <view class="r">查看详细</view>
          </view>
        </view>
      </view>
      <view class="chen3">
        <image class="icon5" src="/static/icon/图片@3x.png" />
        <view class="yue3">
          <view class="q1">业主直转！淮河路步行街旺铺餐馆，接手即赚！</view>
          <view class="yue4">
            <view class="w">2020.04.15</view>
            <view class="e">编辑</view>
            <view class="r">查看详细</view>
          </view>
        </view>
      </view>
      <view class="chen3">
        <image class="icon5" src="/static/icon/图片@3x.png" />
        <view class="yue3">
          <view class="q1">业主直转！淮河路步行街旺铺餐馆，接手即赚！</view>
          <view class="yue4">
            <view class="w">2020.04.15</view>
            <view class="e">编辑</view>
            <view class="r">查看详细</view>
          </view>
        </view>
      </view>
      <view class="yu">
        
        <view class="t">意见反馈</view>
        <image class="icon6" src="/static/icon/箭头@3x.png" />
      </view>
      <view class="yu">
        
        <view class="t">联系客服</view>
        <image class="icon6" src="/static/icon/箭头@3x.png" />
      </view>
    </view>
  </view>
</template>

<style lang="scss" scoped>
.page {
  .yue {
    .zi {
      height: 120px;
      background: #ff9d87;
      .z {
        width: 133px;
        height: 33px;
        font-size: 24px;
        font-weight: 400;
        color: #ffffff;
        line-height: 110px;
        padding-left: 120px;
      }
      .icon {
        width: 50px;
        height: 50px;
        padding-left: 50px;
      }
    }
    .zi2 {
      justify-content: space-around;
      align-items: center;
      display: flex;
      width: 90%;
      height: 61px;
      background: #ffffff;
      border-radius: 10px;
      border: 1px solid #e61111;
      margin-left: auto;
      margin-right: auto;
      .zi3 {
        display: flex;

        .icon1 {
          width: 24px;
          height: 14px;
          margin-top: 3px;
        }
        .x {
          width: 56px;
          height: 20px;
          font-size: 14px;
          margin-left: 5px;
        }
      }
      .zi4 {
        display: flex;
        .icon2 {
          width: 24px;
          height: 24px;
        }
        .c {
          width: 56px;
          height: 20px;
          font-size: 14px;
          font-weight: 400;
          color: #333333;
          padding-left: 5px;
        }
      }
    }
  }
  .chen {
    .v {
      width: 64px;
      height: 22px;
      font-size: 16px;
      font-weight: 500;
      color: #333333;
      line-height: 60px;
      padding-left: 14px;
    }
  }
  .chen1 {
    margin-top: 36px;
    display: flex;
    .b {
      height: 30px;
      width: 50px;
      text-align: center;
      font-size: 14px;
      font-weight: 400;
      color: #ff552e;
      line-height: 20px;
      border-bottom: 2px solid #ff552e;
    }
    .n {
      width: 50px;
      height: 20px;
      font-size: 14px;
      font-weight: 400;
      color: #333333;
      margin: 0 auto;
    }
    .icon3 {
      width: 14px;
      height: 7px;
      background: #0e8ed8;
      margin-top: 5px;
    }
  }
  .chen2 {
    display: flex;
    margin-top: 130px;
    .icon4 {
      width: 130px;
      height: 80px;
      padding-left: 20px;
    }

    .yue1 {
      margin: 0 auto;
      .q {
        width: 195px;
        height: 40px;
        font-size: 14px;
        font-weight: 400;
        color: #333333;
        line-height: 20px;
        margin-left: 10px;
      }
      .yue2 {
        display: flex;
        margin-top: 10px;
        .w {
          width: 52px;
          height: 14px;
          font-size: 10px;
          font-weight: 400;
          color: #666666;
          padding-left: 10px;
        }
        .e {
          width: 40px;
          height: 20px;
          background: #ffffff;
          border-radius: 12px;
          border: 1px solid #0e8ed8;
          text-align: center;
          align-self: center;
          margin-left: 40px;
          font-size: 10px;
          color: #0e8ed8;
        }
        .r {
          width: 60px;
          height: 20px;
          background: #ffffff;
          border-radius: 12px;
          border: 1px solid #0e8ed8;
          text-align: center;
          align-self: center;
          margin-left: 4px;
          font-size: 5px;
          color: #ff552e;
        }
      }
    }
  }
  .chen3 {
    display: flex;
    margin-top: 13px;
    .icon5 {
      width: 130px;
      height: 80px;
      padding-left: 20px;
    }

    .yue3 {
       margin: 0 auto;
      .q1 {
        width: 195px;
        height: 40px;
        font-size: 14px;
        font-weight: 400;
        color: #333333;
        line-height: 20px;
        margin-left: 10px;
      }
      .yue4 {
        display: flex;
        margin-top: 10px;
        .w {
          width: 52px;
          height: 14px;
          font-size: 10px;
          font-weight: 400;
          color: #666666;
          padding-left: 10px;
        }
        .e {
          width: 40px;
          height: 20px;
          background: #ffffff;
          border-radius: 12px;
          border: 1px solid #0e8ed8;
          text-align: center;
          align-self: center;
          margin-left: 40px;
          font-size: 10px;
          color: #0e8ed8;
        }
        .r {
          width: 60px;
          height: 20px;
          background: #ffffff;
          border-radius: 12px;
          border: 1px solid #0e8ed8;
          text-align: center;
          align-self: center;
          margin-left: 4px;
          font-size: 5px;
          color: #ff552e;
        }
      }
    }
  }
  .yu {
    display: flex;
    margin-top: 20px;
    height: 10px;
    .t {
      margin-top: 5px;
      font-size: 14px;
      font-weight: 400;
      color: #333333;
      padding-left: 25px;
    }
    .icon6 {
      margin-top:6px;
      width: 8px;
      height: 15px;
    margin-left: auto;
    }
  }
}
</style>
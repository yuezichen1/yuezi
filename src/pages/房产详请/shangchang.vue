<template>
  <view class="page">
    <view class="yue">
      <image class="icon" src="/static/icon/图片@3x.png" />
      <view class="a"
        >(出租)开发商直租成熟社区低商学校周边商业街零售小吃招租</view
      >
    </view>
    <view class="yue1">
      <view class="zi">
        <view class="z">面积</view>
        <view class="z">租金(元/月)</view>
        <view class="z">转让费</view>
      </view>
      <view class="zi1">
        <view class="x">600平米</view>
        <view class="x">12000</view>
        <view class="x">55万</view>
      </view>
    </view>
    <view class="yue2">
      <view class="zi2">
        <view class="c">基本信息</view>
      </view>
      <view class="zi3">
        <view class="v">可否空转:</view>
        <view class="b"> 不可空转</view>
      </view>
      <view class="zi4">
        <view class="v1">店铺状态:</view>
        <view class="b1"> 营业中</view>
      </view>
      <view class="zi5">
        <view class="v2">所在区域:</view>
        <view class="b2"> 蜀山-望江西路</view>
      </view>
      <view class="zi6">
        <view class="v3">详细地址: </view>
        <view class="b3">望江西路与香樟大道交叉口</view>
      </view>
    </view>
    <view class="yue3">
      <view class="zi7">
        <view class="n">门框：</view>
        <view class="m">未填写</view>
        <view class="n">层高：</view>
        <view class="m">未填写</view>
      </view>
      <view class="zi8">
        <view class="n1">进深：</view>
        <view class="m1">未填写</view>
        <view class="n1">楼层类型：</view>
        <view class="m1">单层</view>
      </view>
      <view class="zi9">
        <view class="n2">楼层：</view>
        <view class="m2">1层</view>
      </view>
      <view class="yue4">
        <view class="zi10">
          <view class="q">套餐设置</view>
        </view>
        <view class="zi11">
          <view class="w">货梯</view>
          <view class="w">中央空调</view>
          <view class="w">停车位</view>
          <view class="w">天然气</view>
          <view class="w">网络</view>
        </view>
      </view>
      <view class="yue5">
        <view class="zi12">
          <view class="e">店铺详情</view>
        </view>
        <view class="zi13">
          <view class="r"
            >店铺位于蜀山区望江西路广汇广场一楼，面积107平米，送阁楼60平，租金6200元/月。地理位置优越，成熟商圈，旁边就是老乡鸡和肯德基。大型购物中心有写字楼，高档社区，人流量秘籍，客源稳定，本人因其他生意，故转让。有意者可实地考察。看店勿扰客。</view
          >
        </view>
      </view>
      <view class="yue6">
        <view class="yu">
          <view class="t">联系人:</view>
          <view class="y">刘先生</view>
          <view class="yu1">
            <image class="icon" src="/static/icon/电话@3x.png" />
            <view class="u">138****8986</view>
          </view>
        </view>
      </view>
    </view>
  </view>
</template>
<style lang="scss" scoped>
.page {
  .yue {
          margin: 0 auto;
      text-align: center;
    .icon {
      width: 375px;
      height: 150px;
    }
    .a {
      margin: 0 auto;
      text-align: center;
      width: 335px;
      height: 44px;
      font-size: 16px;
      font-weight: 500;
      color: #333333;
      line-height: 22px;
    }
  }
  .yue1 {
    margin-top: 30px;
    .zi {
      justify-content: space-around;
      display: flex;

      .z {
        width: 100px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #666666;
        line-height: 17px;
        padding-left: 30px;
      }
    }
    .zi1 {
      justify-content: space-around;
      margin-top: 3px;
      display: flex;
      .x {
        width: 100px;
        height: 20px;
        font-size: 14px;
        font-weight: 500;
        color: #ff552e;
        line-height: 20px;
        padding-left: 30px;
      }
    }
  }
  .yue2 {
    margin-top: 42px;
    .zi2 {
      margin-left: 20px;
      width: 2px;
      height: 15px;
      background: #ff552e;

      .c {
        width: 56px;
        height: 20px;
        font-size: 14px;
        font-weight: 500;
        color: #333333;
        line-height: 16px;
        padding-left: 5px;
      }
    }
    .zi3 {
      margin-top: 10px;
      justify-content: center;
      display: flex;
      .v {
        width: 156px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #999999;
        line-height: 17px;
      }
      .b {
        width: 156px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #333333;
        line-height: 17px;
      }
    }
    .zi4 {
      justify-content: center;
      display: flex;
      .v1 {
        width: 156px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #999999;
        line-height: 17px;
      }
      .b1 {
        width: 156px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #333333;
        line-height: 17px;
      }
    }

    .zi5 {
      justify-content: center;
      display: flex;
      .v2 {
        width: 156px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #999999;
        line-height: 17px;
      }
      .b2 {
        width: 156px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #333333;
        line-height: 17px;
      }
    }
    .zi6 {
      justify-content: center;
      display: flex;
      .v3 {
        width: 156px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #999999;
        line-height: 17px;
      }
      .b3 {
        width: 156px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #333333;
        line-height: 17px;
      }
    }
  }
  .yue3 {
    margin-top: 20px;
    .zi7 {
      text-align: center;
      display: flex;
      .n {
      margin: 0 auto;
      text-align: center;
        width: 150px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #999999;
        line-height: 17px;
      }
      .m {
        width: 160px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #333333;
        line-height: 17px;
      }
    }
    .zi8 {
      text-align: center;
      display: flex;
      .n1 {
          margin: 0 auto;
      text-align: center;
        width: 150px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #999999;
        line-height: 17px;
      }
      .m1 {
        
        width: 160px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #333333;
        line-height: 17px;
      }
    }
    .zi9 {
      text-align: center;
      display: flex;
      .n2 {
        width: 85px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #999999;
        line-height: 17px;
      }
      .m2 {
        width: 95px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #333333;
        line-height: 17px;
      }
    }
  }
  .yue4 {
    margin-top: 30px;
    .zi10 {
      margin-left: 20px;
      width: 2px;
      height: 15px;
      background: #ff552e;

      .q {
        width: 56px;
        height: 20px;
        font-size: 14px;
        font-weight: 500;
        color: #333333;
        line-height: 16px;
        padding-left: 5px;
      }
    }
    .zi11 {
      margin-top: 10px;
      text-align: center;
      display: flex;
      .w {
        width: 264px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #666666;
        line-height: 17px;
      }
    }
  }
  .yue5 {
    margin-top: 30px;
    .zi12 {
      margin-left: 20px;
      width: 2px;
      height: 15px;
      background: #ff552e;

      .e {
        display: flex;
        width: 56px;
        height: 20px;
        font-size: 14px;
        font-weight: 500;
        color: #333333;
        line-height: 16px;
        padding-left: 5px;
      }
    }
    .zi13 {
      margin-top: 10px;
      justify-content: center;
      display: flex;
      .r {
        width: 335px;
        height: 88px;
        font-size: 12px;
        font-weight: 400;
        color: #666666;
        line-height: 17px;
      }
    }
  }
  .yue6 {
    .yu {
      margin-top: 10px;
      justify-content: center;
      display: flex;
      .t {
        width: 50px;
        height: 20px;
        font-size: 14px;
        font-weight: 400;
        color: #999999;
        line-height: 30px;
      }
      .y {
        width: 70px;
        height: 20px;
        font-size: 14px;
        font-weight: 400;
        color: #333333;
        line-height: 30px;
      }
      .yu1 {
        justify-content: center;
        display: flex;
        width: 210px;
        height: 34px;
        background: #ff552e;
        border-radius: 17px;
        .icon {
          margin-top: 10px;
          width: 16px;
          height: 15px;
        }
        .u {
          margin-top: 5px;
          width: 109px;
          height: 25px;
          font-size: 18px;
          font-weight: 400;
          color: #ffffff;
          line-height: 25px;
        }
      }
    }
  }
}
</style>
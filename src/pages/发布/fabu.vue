<template>
  <view class="page">
    <view class="a">请选择发布类别</view>
    <view class="s">
      <view class="yue">
        <image class="icon" src="/static/icon/zhaodian.png" />
        <view class="z">房产</view>
      </view>
      <view class="f">
        <view class="x">店铺转让，招租求租</view>
        <view class="c">线上线下，渠道全覆盖 </view>
      </view>
    </view>
    <view class="d">
      <view class="yue1">
        <image class="icon" src="/static/icon/ping.png" />
        <view class="v">招聘</view>
      </view>
      <view class="g">
        <view class="b">帮我招聘</view>
        <view class="n">人才全聚集，招人好轻松</view>
      </view>
    </view>
    <view class="h">
      <view class="yue2">
        <image class="icon" src="/static/icon/qiuzhi.png" />
        <view class="m">求职</view>
      </view>
      <view class="q">
        <view class="w">想找工作</view>
        <view class="e">找我就对</view>
  </view>
    </view>
    <view class="j">
      <view class="yue3">
        <image class="icon" src="/static/icon/bang.png" />
        <view class="zi2">万能帮</view>
      </view>
      <view class="zi3">
        <view class="zi4">便民服务</view>
        <view class="zi5">体贴你的服务</view>
  </view>
    </view>
    <view class="k">
      <view class="yue4">
        <image class="icon" src="/static/icon/ershou.png" />
        <view class="zi6">二手交易</view>
      </view>
      <view class="zi7">
        <view class="zi8">立马变现</view>
        <view class="zi9">线上线下，样样我在行</view>
  </view>
    </view>
    <view class="l">
      <view class="yue5">
        <image class="icon" src="/static/icon/kuaigou.png" />
        <view class="zi10">快购</view>
      </view>
      <view class="zi11">
        <view class="zi12">买东西，急急急</view>
        <view class="zi13">便宜快捷，为您服务</view>
  </view>
    </view>
    <view class="r">
      <view class="yue6">
        <image class="icon" src="/static/icon/aixin.png" />
        <view class="zi14">爱心公益</view>
      </view>
      <view class="zi15">
        <view class="zi16">上善若水</view>
        <view class="zi17">母以善小而不为</view>
  </view>
    </view>
  </view>

</template>

<style lang="scss" scoped>
.page {
  .a {
    width: 98px;
    height: 40px;
    font-size: 14px;
    font-weight: 400;
    color: #333333;
    line-height: 20px;
    padding-left: 30px;
  }

  .s {
    display: flex;
    .yue {
      .icon {
        width: 32px;
        height: 32px;
        padding-left: 30px;
      }
      .z {
        width: 24px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #666666;
        line-height: 17px;
        padding-left: 35px;
      }
    }
    .f {
      margin-top: 10px;
      .x {
        width: 126px;
        height: 20px;
        font-size: 14px;
        font-weight: 500;
        color: #333333;
        line-height: 20px;
        padding-left: 20px;
      }
      .c {
        width: 120px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #999999;
        line-height: 17px;
        padding-left: 20px;
      }
    }
  }
  .d{
    display: flex;
    margin-top: 20px;
    .yue1 {
      .icon {
        width: 32px;
        height: 32px;
        padding-left: 30px;
      }
      .v {
        width: 24px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #666666;
        line-height: 17px;
        padding-left: 35px;
      }
    }
    .g {
      margin-top: 13px;
      .b {
        width: 126px;
        height: 20px;
        font-size: 14px;
        font-weight: 500;
        color: #333333;
        line-height: 20px;
        padding-left: 20px;
      }
      .n{
        width: 132px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #999999;
        line-height: 17px;
        padding-left: 20px;
      }
    }
  }
  .h{
    display: flex;
    margin-top: 20px;
    .yue2 {
      .icon {
        width: 32px;
        height: 32px;
        padding-left: 30px;
      }
      .m {
        width: 24px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #666666;
        line-height: 17px;
        padding-left: 35px;
      }
    }
    .q {
      margin-top: 15px;
      .w {
        width: 126px;
        height: 20px;
        font-size: 14px;
        font-weight: 500;
        color: #333333;
        line-height: 20px;
        padding-left: 20px;
      }
      .e{
        width: 132px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #999999;
        line-height: 17px;
        padding-left: 20px;
      }
    }
  }
  .j{
    display: flex;
    margin-top: 20px;
    .yue3 {
      .icon {
        width: 32px;
        height: 32px;
        padding-left: 30px;
      }
      .zi2 {
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #666666;
        line-height: 17px;
        padding-left: 30px;
      }
    }
    .zi3 {
       margin-top: 15px;
      .zi4 {
        width: 126px;
        height: 20px;
        font-size: 14px;
        font-weight: 500;
        color: #333333;
        line-height: 20px;
        padding-left: 20px;
      }
      .zi5{
        width: 132px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #999999;
        line-height: 17px;
        padding-left: 20px;
      }
    }
  }
.k{
    display: flex;
    margin-top: 20px;
    .yue4 {
      .icon {
        width: 32px;
        height: 32px;
        padding-left: 30px;
      }
      .zi6{
        width: 50px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #666666;
        line-height: 17px;
        padding-left: 21px;
      }
    }
    .zi7 {
       margin-top: 15px;
      .zi8 {
        width: 126px;
        height: 20px;
        font-size: 14px;
        font-weight: 500;
        color: #333333;
        line-height: 20px;
        padding-left: 15px;
      }
      .zi9{
        width: 132px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #999999;
        line-height: 17px;
        padding-left: 15px;
      }
    }
  }
  .l{
    display: flex;
    margin-top: 20px;
    .yue5 {
      .icon {
        width: 32px;
        height: 32px;
        padding-left: 30px;
      }
      .zi10{
        width: 50px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #666666;
        line-height: 17px;
        padding-left: 35px;
      }
    }
    .zi11 {
       margin-top: 15px;
      .zi12 {
        width: 126px;
        height: 20px;
        font-size: 14px;
        font-weight: 500;
        color: #333333;
        line-height: 20px;
        padding-left: 2px;
      }
      .zi13{
        width: 132px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #999999;
        line-height: 17px;
        padding-left: 2px;
      }
    }
  }
  .r{
    display: flex;
    margin-top: 20px;
    .yue6 {
      .icon {
        width: 32px;
        height: 32px;
        padding-left: 30px;
      }
      .zi14{
        width: 50px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #666666;
        line-height: 17px;
        padding-left:28px;
      }
    }
    .zi15 {
       margin-top:15px;
      .zi16 {
        width: 126px;
        height: 20px;
        font-size: 14px;
        font-weight: 500;
        color: #333333;
        line-height: 20px;
        padding-left: 10px;
      }
      .zi17{
        width: 132px;
        height: 17px;
        font-size: 12px;
        font-weight: 400;
        color: #999999;
        line-height: 17px;
        padding-left: 10px;
      }
    }
  }
}
</style>
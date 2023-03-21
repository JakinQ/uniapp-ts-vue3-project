<template>
  <view class="index-list">
   
      <view class="index-list1">
		  <image src="@/static/demo/userpic/1.jpg" mode="widthFix" lazy-load></image>
      昵称
      <view >
        <view class="icon iconfont icon-zengjia"></view>关注
      </view>
	  </view>
    <view class="index-list2">标题</view>
    <view class="index-list3">
      <image
        src="@/static/demo/datapic/1.jpg"
        mode="widthFix" lazy-load
      />
    </view>
    <view class="index-list4">
      <view>
        <view> <view class="icon iconfont icon-icon_xiaolian-main"></view>10</view>
        <view> <view class="icon iconfont icon-kulian"></view>10</view>

      </view>
      <view>
        <view> <view class="icon iconfont icon-pinglun1"></view>10</view>
        <view> <view class="icon iconfont icon-zhuanfa"></view>10</view>

      </view>
    </view>
    </view>
</template>

<script setup lang="ts">
import { ref } from 'vue'
const title = ref('Hello')
</script>

<style>
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.logo {
  height: 200rpx;
  width: 200rpx;
  margin-top: 200rpx;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 50rpx;
}

.text-area {
  display: flex;
  justify-content: center;
}

.title {
  font-size: 36rpx;
  color: #8f8f94;
}
</style>

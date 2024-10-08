<template>
  <view class="my">
    <div class="head">
      <view class="person">
      <div class="img">
        <img src="/static/head-img.jpg" alt="">
      </div>
      <view class="info">
        <view class="name">风</view>
        <view class="region">深圳</view>
      </view>
    </view>
    </div>
  </view>
</template>

<script setup lang="ts">
import { ref } from 'vue'
</script>

<style lang="scss" scoped>
.head{
  .person{
    display: flex;
    align-items: center;
    margin-left: 20px;
    .img{
      width: 80px;
      height: 80px;
      border-radius: 50%;
      overflow: hidden;
      img{
        width: 100%;
        height: 100%;
      }
    }
    .info{
      margin-left: 10px;
    }
  }
}
</style>

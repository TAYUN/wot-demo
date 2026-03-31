<script setup lang="ts">
definePage({
  name: 'playground',
  layout: 'tabbar',
  style: {
    navigationBarTitleText: '测试场',
  },
})
</script>

<template>
  <view class="min-h-screen p-4">
    <text class="text-4 text-gray-800 font-bold dark:text-[var(--wot-dark-color)]">
      测试场
    </text>
  </view>
</template>

<template>
  <div>
    <!--  Nuxt路由  -->
    <NuxtLink to="/">首页</NuxtLink>
    <br />
    <NuxtLink to="/video">视频</NuxtLink>
    <NuxtPage/>
  </div>
</template>
<script setup lang="ts">
useSeoMeta({
  title: '哔哩哔哩 (゜-゜)つロ 干杯~-bilibili',
  description: '哔哩哔哩（bilibili.com)是国内知名的视频弹幕网站，这里有及时的动漫新番，活跃的ACG氛围，有创意的Up主。大家可以在这里找到许多欢乐。'
})
</script>
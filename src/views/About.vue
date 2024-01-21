<script setup lang="ts">
import { ref } from 'vue'
</script>

<template>
  <div class="about-wrapper">
    <div class="title-1">关于</div>
    <div class="content">
      一个公益图床服务。<br /><br />
     由bill搭建<br /><br />
      <ul>
        <li>支持点击、拖拽、复制图片上传</li>
        <li>
          谷歌 <a href="https://squoosh.app" target="_blank">squoosh</a>
          压缩图片
        </li>
        <li>
          <a href="https://fancyapps.com" target="_blank">Fancybox</a>
          的加持，让图片的预览效果更好。
        </li>
        <li>安全且快速，数据只存在本地。</li>
        <li>复制转换 Markdown 格式</li>
      </ul>
      <br />
    </div>
</template>

<style lang="scss" scoped>
.about-wrapper {
  max-width: 700px;
  margin: 70px auto;
  padding: 50px;
  color: var(--text-color);
  .content {
    margin-top: 20px;
    color: var(--text-color);
    line-height: 30px;
    a {
      color: var(--primary-color);
      text-decoration: underline;
    }
  }
}
</style>

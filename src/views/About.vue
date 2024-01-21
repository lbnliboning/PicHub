<script setup lang="ts">
import { ref } from 'vue'
</script>

<template>
  <div class="about-wrapper">
    <div class="title-1">关于</div>
    <div class="content">
      我是<a target="_blank" href="https://cigh.cn/">
        bill</a
      >。 这个项目是一个公益项目。（<a
        target="_blank"
        href="https://imgbed.cigh.cn"
      >
        https://imgbed.cigh.cn</a
      >）。<br /><br />
      PicHub 是一个图床，也可以是相册，这取决于你对它的定位。<br />很简单，但比较完整，用
      Vue3 写的，不算太慢。<br />典型现代风格和干净页面，如果您和我一样对 UI
      极具苛刻，这将是一个让您大吃一惊的好项目。<br /><br />
      特别的是
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
        <li>封装组件（按钮表单上传等）</li>
        <li>复制转换 Markdown 格式</li>
      </ul>
      <br />
      <div>
        开源地址：
        <a target="_blank" href="https://github.com/lewkamtao/PicHub"
          >https://github.com/lewkamtao/PicHub</a
        >
      </div>
      <div>欢迎提建议和bug，喜欢的话点个star！</div>
    </div>
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

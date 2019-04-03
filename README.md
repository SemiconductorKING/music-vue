<p align="center">
    <a href="https://github.com/TothingWay/vue-music" target="_blank">
        原项目跳转
    </a>
</p>
<p align="center">
    <a href="https://github.com/vuejs/vue-cli"><img src="https://img.shields.io/badge/vue--cli-v2.9.2-blue.svg" alt="vue-cli"></a>
    <a href="https://github.com/vuejs/vue"><img src="https://img.shields.io/badge/vue-v2.5.13-blue.svg" alt="vue"></a>
    <a href="https://github.com/vuejs/vue-router"><img src="https://img.shields.io/badge/vue--router-v3.0.1-blue.svg" alt="vue-router"></a>
    <a href="https://github.com/vuejs/vuex"><img src="https://img.shields.io/badge/vuex-v3.0.1-blue.svg" alt="vuex"></a>
    <a href="https://github.com/axios/axios"><img src="https://img.shields.io/badge/axios-0.17.1-blue.svg" alt="axios"></a>
    <a href="https://github.com/airyland/vux"><img src="https://img.shields.io/badge/vux-v2.7.8-blue.svg" alt="vux"></a>
    <a href="javascript:;"><img src="https://img.shields.io/badge/license-MIT-green.svg" alt="license"></a>
</p>
<p align="center">
    项目预览：<a href="http://www.tothingway.me/music">http://www.tothingway.me/music</a>
</p>

## 介绍
用vue制作的网页版音乐app,https://github.com/TothingWay/vue-music 基础上优化功能和性能


## 实现功能
* 音乐播放、暂停、上一曲、下一曲、播放进度条
* 歌曲歌词、歌词自动滚动
* 播放列表、添加到播放列表
* 播放模式切换
* 搜索提示、热门搜索、搜索历史记录、搜索单曲、歌手
* 排行榜
* 歌手榜、歌手单曲
* 推荐歌单
* 推荐最新音乐
* 轮播
* 我喜欢

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```
## 项目结构

<pre>
├── build                  // 构建服务和 webpack 配置
├── config                 // 项目不同环境的配置
├── index.html             // 项目入口文件
├── package.json           // 项目配置文件
├── static                 // 放置静态资源
├── src                    // 生产目录
│   ├── api                  // api请求
│   ├── assets               // 公共的images, fonts， js资源
│   ├── components           // 各种组件
│   ├── store                // vuex状态管理
│   ├── App.vue              // 主页面
│   ├── router               // 路由配置
│   └── main.js              // Webpack 预编译入口
</pre>






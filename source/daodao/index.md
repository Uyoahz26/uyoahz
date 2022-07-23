---
title: 叨叨
date: 2018-12-20 23:13:48
keywords: 小赵叨叨，意想不到。
description: 
comments: true
photos: https://cdn.jsdelivr.net/gh/Uyoahz26/cdn@master/img/cover/IMG_20210526_212944.jpg
---

<!-- <style>
  .timeline ul {margin:0;}
  .timeline ul li {background:#3b3d42;list-style-type:none;position:relative;width:3px;margin-left:2em;padding:0.8em 0 2em;}
  .timeline ul li::after {transform: rotate(45deg);content:'';background-color: #3b3d42;display: block;position: absolute;top: 10px;left: -5px;width: 0.8em;height: 0.8em;outline: 15px solid #fff;}
  .timeline ul li div {position:relative;top:-13px;left:3em;width:670px;padding:0px 16px 0px;}
  .timeline ul li p.datatime{color: #fafafa;font-size: 0.75em;font-style: italic;background-color: #3b3d42;display: inline-block;padding:0.25em 1em 0.2em 1em;}
  .timeline ul li p.datacont{margin:0.65em 0 0.3em;}
  .timeline ul li p.datacont img{display:block;width:100%;}
  .timeline ul li p.datacont img[src*="emotion"]{display:inline-block;width:auto;}
  .timeline ul li p.datafrom{color: #aaa;font-size: 0.75em !important;font-style: italic;}
  .timeline ul li p{margin:0;font-size:16px;letter-spacing:1px;color: #3b3d42;}
  button{border-radius:0;}
  .dark-theme .timeline ul li div p{color:#fafafa;}
  .dark-theme .timeline ul li div p svg{fill:#fafafa;}
  .dark-theme .timeline ul li p.datafrom{color: #aaa;}
  .dark-theme .timeline ul li{background:#3b3d42;}
  .dark-theme .timeline ul li::after{outline: 15px solid #292a2d;}
  @media (max-width:860px) {
    .timeline ul li{margin-left:0;}
    .timeline ul li div{width:calc(100vw - 75px);left:30px;}
  }
</style>

<div id="bber"></div>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/TencentCloudBase/tcb-js-sdk@master/tcbjs/1.10.10/tcb.js"></script>
<script src="https://cdn.jsdelivr.net/gh/buddys/qq-wechat-emotion-parser@master/dist/qq-wechat-emotion-parser.min.js"></script>
<script>
  const app = tcb.init({
      env: 'bber-2g6eo6w3a44db02e', //这里是你的环境id
      //region: "ap-guangzhou"
  })
</script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/lmm214/bber@0.0.3/bber.js"></script>
 -->
<div id='speak'></speak>
<!-- 使用markdown渲染 -->
<!-- <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/ispeak-bber/ispeak-bber-md.min.js" charset="utf-8" ></script> -->
<!-- 不使用markdown渲染 -->
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/Uyoahz26/cdn@master/js/ispeak-bber.min.js" charset="utf-8" ></script>
<!-- 解析微信表情（参考：https://github.com/buddys/qq-wechat-emotion-parser） -->
<script src="https://cdn.jsdelivr.net/gh/buddys/qq-wechat-emotion-parser@master/dist/qq-wechat-emotion-parser.min.js"></script>
<script>
ispeakBber
    .init({
      el: '#speak', // 容器选择器
      name: 'UyoAhz 📢', // 显示的昵称
      envId: 'bber-2g6eo6w3a44db02e', // 环境id
      region: 'ap-shanghai', // 腾讯云地址，默认为上海
      limit: 10, // 每次加载的条数，默认为5
      avatar: 'https://cdn.jsdelivr.net/gh/Uyoahz26/cdn@master/img/custom/avatar.jpg',
      fromColor:'rgb(245, 150, 170)', // 下方标签背景颜色 默认 rgb(245, 150, 170)
      loadingImg: 'https://7.dusays.com/2021/03/04/d2d5e983e2961.gif', // 自定义loading的图片，示例值为默认值
      dbName:'talks' // 数据的名称，默认talks，避免有人的命名不是这个，所以加入此配置字段。
    })
    .then(function() {
      // 哔哔加载完成后的回调函数，你可以写你自己的功能
      console.log('小赵叨叨 加载完成')
    })
</script>

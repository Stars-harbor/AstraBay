<div align="center">

# 本主题基于Solitude二次完善开发

</div>

---

Astrabay最新主题版本：1.4.3

已同步的solitude版本：3.0.21

---

## 二次开发特性（区别）

- 调整与优化了多处显示效果
- 即刻说说支持换行与加粗功能
- 调整了文章本地AI的加载动画效果
- 修复《开往》按钮在移动端下滑时突然自动消失，回顶后又突然出现的问题
- 优化了音乐胶囊的多处效果
- 优化了友情链接的失效友链样式
- 移除了主题内置的avif格式图片并替换为webp格式，避免因图片格式过于超前且浏览器内核不兼容导致部分设备无法显示默认图片的问题
- 综合优化了rightside按钮的显示效果与动画逻辑
- 优化了关于页赞助部分的内容显示逻辑
- 修改了推荐文章功能逻辑
- 仍然支持站点背景图功能
- 支持对单个文章关闭文章过期功能
- 关于页技能点显示逻辑、循环动画、循环逻辑优化

详细区别与部分使用方法请查看：[Astrabay主题特性介绍](https://blog.starsharbor.com/posts/Astrabay-features/)

即刻说说换行、加粗能力使用方法：

```yml
<br>为换行效果

<b>需要加粗的文字</b>为加粗效果
```

关于页赞助部分的新特性适配模板

```yml
award:
  enable: true
  description: 因为有你们，让我更加有创作的动力
  tips: 总金额：¥ {sum}，将用于本人各项目的维护和更新 # 必须带 {sum}，否则无法显示总金额
  limit: 12 # 显示上限，推荐设置为4和6的公倍数以获得最佳显示体验
  more: '/sponsor' # 内页链接或站外地址
rewardList: # 底部捐赠
  - name: '❖星港◎Star☆'
    money: 100
    time: 2025-09-13 00:00:00
    color: '' # 可填写16进制颜色码
```

## 原主题特性

- 页面懒加载（Pjax）、图片懒加载（LazyLoad）、离线应用（PWA）
- 评论(Twikoo、Waline、Valine、Artalk、Giscus)，支持双评论
- 昼夜切换(ColorMode)
- 灯箱(medium-zoom、fancybox)
- 数学公式(Latex)
- 特色页面：即刻短文、我的装备、在线工具、音乐馆、友链鱼塘、相册页、豆瓣页、弹幕留言页
- 文章功能：AI 摘要、代码高亮

## 版权

> 原主题主题版权信息

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fvalor-x%2Fhexo-theme-solitude.svg?type=small)](https://app.fossa.com/projects/git%2Bgithub.com%2Fvalor-x%2Fhexo-theme-solitude?ref=badge_large)

[Apache-2.0](./LICENSE) License &copy; 2025-至今 [伍十七](https://github.com/everfu)
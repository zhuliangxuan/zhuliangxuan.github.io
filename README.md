# 百宝箱 · 官方介绍站点

这是 [百宝箱](https://gitee.com/zhuliangxuan/waypoint-data/releases) 的官方介绍主页，托管于 GitHub Pages：
<https://zhuliangxuan.github.io/>

纯静态 HTML 单页（`index.html`），无任何外部依赖 / CDN，国内访问无压力。

## 目录结构

```
index.html            # 主页（样式与脚本全部内嵌）
404.html              # 404 页（5 秒自动跳回首页）
assets/
├── favicon.svg       # 应用图标（来自百宝箱安装包）
├── qq-group.jpg      # QQ 群「百宝箱反馈群」二维码（群号 1079520872）
└── gzh.jpg           # 公众号「阿哲君极客世界」二维码
```

## 如何更新

| 要改什么 | 改哪里 |
|---|---|
| 版本号 / 下载链接 | 搜索 `0.5.4` 与 `gitee.com/zhuliangxuan/waypoint-data/releases` 全部替换 |
| QQ 群二维码 | 替换 `assets/qq-group.jpg`（建议宽度 ≤700px、≤100KB） |
| 公众号二维码 | 替换 `assets/gzh.jpg` |
| 介绍文案 / 功能 / 技巧 | 直接编辑 `index.html` 对应 section |

改完 push 到 `master` 分支，GitHub Pages 会自动部署。

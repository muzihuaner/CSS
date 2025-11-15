# 空间站实时追踪

本项目基于 Three.js 和 satellite.js 实现中国空间站（CSS）与国际空间站（ISS）轨道三维可视化，支持标签显示、轨道切换、视角锁定、空间站位置图片弹窗等功能。

## 功能介绍
- 实时获取 CSS/ISS 轨道数据并三维展示
- 支持显示/隐藏空间站标签
- 支持显示/隐藏轨道线
- 支持锁定/解锁视角
- 支持弹窗展示中国空间站位置图片（轨道图、极区图、赤道区图）
- 信息面板实时显示空间站经纬度、高度、速度

## 使用方法
1. 克隆或下载本项目到本地
2. 使用支持 ES6 的浏览器直接打开 `index.html`
3. 页面左下角可操作各类功能按钮

## 主要依赖
- [Three.js](https://threejs.org/)：三维可视化库
- [satellite.js](https://github.com/shashwatak/satellite-js)：卫星轨道计算

## 目录结构
```
CCS/
├── index.html      # 主页面
├── README.md       # 项目说明
└── ss.png          # 空间站图标
```

## 相关链接
- CSS轨道图等图片来源：[Heavens Above](https://www.heavens-above.com/)
- 卫星数据来自 [CeleStrak](https://celestrak.org)

## 作者
muzihuaner

---
如有问题或建议欢迎反馈！

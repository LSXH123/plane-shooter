# 打飞机 · Plane Shooter

一个用纯 HTML + Canvas + JavaScript 编写的网页打飞机小游戏，无需任何依赖，打开 `index.html` 即可游玩。

## 玩法

- **移动**：`←` `→` `↑` `↓` 或 `A` `D` `W` `S`
- **射击**：按住 `空格`（或用鼠标 / 触摸直接控制飞机并自动射击）
- 击落敌机得分，躲避敌机与子弹，收集金色强化道具升级火力

## 特色

- 三种敌机 + 波次难度递增
- 生命值、分数、最高分（本地保存）
- 粒子爆炸特效、简单音效、星空背景
- 响应式，支持鼠标与触屏

## 运行

直接用浏览器打开 `index.html`，或：

```bash
# 任意静态服务器，例如：
python -m http.server 8000
# 然后访问 http://localhost:8000
```

## 在线试玩

可以通过 GitHub Pages 部署：仓库 `Settings → Pages → Branch: main` 即可。

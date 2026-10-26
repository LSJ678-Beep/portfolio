# 互动编程作品集 · 鲁少俊

《互动编程》课程作业三 · 数字媒体艺术专业 · 大二

**在线访问：** 通过 Cloudflare Pages 发布（链接见提交说明）

## 内容

| 作品 | 类型 | 技术 |
| --- | --- | --- |
| 夜色街区 · 生成海报 | p5.js 静态 | Perlin Noise、随机种子、noLoop |
| 流光画板 | p5.js 交互 | 粒子系统、blendMode(ADD)、鼠标/键盘/滚轮 |
| 星际虫潮 | Three.js 小游戏 | r160、鼠标射线瞄准、对象池 |

三个作品均以 iframe 内嵌在 `index.html` 中，站内即可直接体验；
每个作品附四行说明：标题 / 一句话说明 / 创作思路 / 技术栈。

## 目录

```
index.html                        作品集首页（含三个作品与关于我）
works/
  ├─ p5-static.html               作品一：夜色街区（静态生成海报）
  ├─ p5-interactive.html          作品二：流光画板（交互粒子画板）
  └─ game.html                    作品三：星际虫潮（内嵌游戏页）
libs/
  ├─ p5.min.js                    p5.js 1.9.4（自托管）
threejs-templates/
  ├─ 游戏模板C-星际虫潮.html        游戏本体（单文件）
  └─ libs/three.global.js         Three.js r160 全局版
```

## 本地运行

直接双击 `index.html` 即可，全部资源本地自托管，无需启动服务器。

## 说明

- 所有模型与图案均由代码实时生成，无外部素材依赖。
- 游戏参数集中在 `游戏模板C-星际虫潮.html` 顶部的
  `SETTINGS` / `ENEMY_TYPES` / `UPGRADES` 三个中文配置区。

## License

MIT

# 黄金矿工 Gold Miner

经典的挖金矿小游戏 —— 纯前端 HTML5 Canvas 实现，通过 GitHub Actions 自动部署到 GitHub Pages。

## 玩法

- **空格 / 鼠标点击 / 触摸** 放下抓钩
- 抓到 **金子**、**钻石** 加分；**岩石** 又重又少分
- 每关需要在限定时间内达到 **目标分数** 才能通关
- 越大、越重的物体收钩越慢

| 物品 | 分数 | 重量 |
|------|------|------|
| 小金块 | 50 | 轻 |
| 中金块 | 100 | 中 |
| 大金块 | 250 | 重 |
| 小石头 | 10 | 中 |
| 大石头 | 20 | 很重 |
| 钻石 | 600 | 极轻 |

## 本地运行

直接用浏览器打开 `index.html` 即可。

## 部署

推送到 `main` 分支即自动通过 GitHub Actions 部署到 GitHub Pages。

需要在仓库 **Settings → Pages → Build and deployment → Source** 中选择 **GitHub Actions**。

部署地址：`https://<username>.github.io/<repo>/`

# Steam游戏观察站

Steam游戏观察站是一款面向独立游戏开发者、发行人员和数据研究者的 Windows 桌面工具，用于持续观测 Steam 游戏的热度、价格、评价、媒体资料与收入估算变化。

# Steam Game Observatory

Steam Game Observatory is a Windows desktop tool for indie game developers, publishers, and data researchers. It helps track Steam game trends, prices, reviews, media assets, and estimated revenue changes over time.

<img width="1497" height="1022" alt="4f8262ab4d9b246a2fa63458a51481ec" src="https://github.com/user-attachments/assets/a045a213-6187-4dc2-afc9-39b13a346f2c" />
https://www.bilibili.com/video/BV1R2Gp6pEFG/

## 核心功能

### 观测目标管理

支持通过 Steam 商店链接或 AppID 添加游戏，建立自己的长期观测列表。

### Observation Target Management

Add games by Steam store URL or AppID and build a long-term observation list.

### 新游目录收集

可手动收集近期新上架游戏，补全游戏基础信息、价格、评价、媒体资料和当日数据。

### New Game Catalog Collection

Manually collect recently released games and enrich them with basic information, pricing, reviews, media assets, and daily data.

### 近期热门筛选

可按发售时间范围筛选近期热门游戏，用于发现近期表现活跃的新游戏和潜在案例。

### Recent Popular Game Filtering

Filter recently popular games by release-time range to discover active new titles and potential market cases.

### 快速一轮刷新

支持对当前分类执行一轮数据刷新。多个分类连续触发时，会按最近点击的分类优先处理，完成后继续之前的队列。

### Quick Refresh Round

Refresh one category at a time. When multiple categories are triggered, the most recently clicked category gets priority, then the previous queue continues.

### 价格、评价与收入估算

记录游戏每日价格、折扣价、评论数、好评率、估算销量、估算收入和第三方收入数据，方便观察趋势变化。

### Price, Review, and Revenue Tracking

Record daily price, discount price, review count, positive review rate, estimated sales, estimated revenue, and third-party revenue data to observe trends over time.

### 媒体资料浏览

支持查看封面、主图、截图和 Steam 视频，便于快速判断游戏卖相和内容风格。

### Media Browser

View cover images, hero images, screenshots, and Steam videos to quickly evaluate game presentation and content style.

### 更新提示标记

游戏数据更新成功后显示提示标记，更新失败时显示失败标记，点击查看后提示消失。

### Update Indicators

Games show a success marker after updated data is collected and a warning marker when an update fails. The marker disappears after the game is viewed.

### 数据导出

支持导出单个游戏、选中游戏、当前分类或全部分类。支持 Excel 和 Markdown 两种格式。Excel 可嵌入封面和首张截图缩略图，Markdown 输出清晰文本报告。

### Data Export

Export a single game, selected games, the current category, or all categories. Excel and Markdown are supported. Excel can embed cover and first-screenshot thumbnails, while Markdown generates a clean text report.

### 导出进度与中断

大量数据导出时会显示行数据和缩略图两个进度条，可随时停止导出。

### Export Progress and Cancellation

Large exports show separate progress bars for row writing and thumbnail embedding, with a stop button.

### 本地数据存储

数据保存在本机应用数据目录中，适合个人研究、复盘和长期跟踪。

### Local Data Storage

Data is stored locally in the app data directory, making it suitable for personal research, review, and long-term tracking.

### 开机自启动

设置中可选择是否开机自启动，方便长期观测。

### Auto Start

Auto-start on system boot can be enabled in Settings for long-term observation.

## 适用场景

跟踪竞品和同类游戏表现，观察新游上架后的价格、评价和热度变化，筛选近期热门游戏案例，建立独立游戏市场观察库，并导出数据用于复盘、报告或进一步分析。

## Use Cases

Track competitors and similar games, observe price, review, and popularity changes after release, discover recent popular indie game cases, build a personal Steam market observation library, and export data for reports, reviews, or further analysis.

## 技术栈

本项目使用 Tauri、React、TypeScript、Rust、pnpm workspace 和本地 JSON 文档存储构建。

## Tech Stack

This project is built with Tauri, React, TypeScript, Rust, pnpm workspace, and local JSON document storage.

## 说明

本工具用于公开数据观测和个人研究，不隶属于 Valve 或 Steam。所有商店信息、评价和媒体资料来源于公开页面或相关公开数据源，结果仅供参考。

## Disclaimer

This tool is intended for public data observation and personal research. It is not affiliated with Valve or Steam. Store information, reviews, and media assets come from public pages or related public data sources. Results are for reference only.

# learning-coach

闯关式学习教练：把「我想学 X」变成一条不用自己设计的学习路线。

## 打开

浏览器直接打开根目录的 `index.html` 就行，单文件、零依赖、不用装 Node、不用起服务。

在线版（GitHub Pages，与 `main` 分支同步）：https://mikesentence.github.io/learning-coach/

## 能做什么

- 填任意主题，自动拆成 4-6 关，一次只问一题
- 三种内容来源：接自己的模型现编题目、自练模式（通用自检追问链，不编造学科事实）、内置中性示例包
  - AI 教练：接口地址与模型名默认预填 DeepSeek（`https://api.deepseek.com/v1` / `deepseek-flash`），**只需填自己的 API Key**；模型可换 `deepseek-v4-pro`，接口可改任意 OpenAI 兼容服务
  - 密钥只存在浏览器本地，不写进仓库、不写进导出的学习记录
- 六种题型混搭、难度自适应、常驻进度条、术语全称对照、薄弱点间隔复习
- 记录存在浏览器本地，可导出 Markdown / JSON，换设备能导回来接着学

## 目录

- `index.html` — 当前主页面，CSS / JS 全内联
- `archive/` — 2026-11-05 的产品方向原型：四款方向对比、教师备课台、硬科技闯关营、家庭版、机构版。仅作历史留档，不是当前入口

## 后续

计划扩展成手机 App。接入 Tauri / Capacitor 时会把网页收进 `web/`，壳子配置单独放。

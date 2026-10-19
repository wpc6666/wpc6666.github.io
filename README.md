# 白澤 程 · 个人主页

> 基于 GitHub Pages 的个人主页站点，聚合学习知识库与开发工具的一站式入口。

## 简介

本项目是 **wpc6666.github.io** 的站点源码仓库，托管于 GitHub Pages，对应域名下的个人主页（`https://wpc6666.github.io/`）。主页以"经济统计学学习者 · 论文写作爱好者 · 工具开发者"为定位，把散落在各仓库里的学习资料与实用工具集中到一个入口，方便随时访问与检索。

## 站点内容

### 📚 学习知识库

| 项目 | 说明 |
|------|------|
| [经济统计学论文写作知识库](https://github.com/wpc6666/economic-statistics-thesis-knowledge) | 从 0 基础到论文精通，覆盖综合评价、计量经济学、时间序列分析、多元统计分析、统计学原理 5 门课程；含论文写作全流程、方法选择决策、答辩指南 |

### 🛠️ 工具项目

| 项目 | 说明 |
|------|------|
| [重财论文格式工具](https://github.com/wpc6666/cfec-thesis-formatter) | 专为重庆财经学院本科毕业生打造的自动化排版方案，一键转换为符合学校《毕业论文（设计）指导手册》格式规范的 Word 与 LaTeX 双格式文件 |
| [macOS 中文绘图配置](https://github.com/wpc6666/plot-cjk-config) | R / Python / Stata 三套工具链中文出图环境一键部署，解决绘图中文乱码（□□□）问题；默认 300 DPI，自带体检脚本 |

### 🔧 其他工具

- **Shadowrocket**：小火箭配置文件
- **Quantumult**：Quantumult 配置文件
- **AutoBuildImmortalWrt**：ImmortalWrt 固件自动编译

## 技术说明

- 纯静态页面：原生 HTML + CSS（响应式布局，适配移动端），无框架依赖，加载快、易维护
- SEO 就绪：页面内置 description / keywords / author 元信息，已接入 Google Search Console 与必应 Webmaster 验证，配置 `robots.txt` 与 `sitemap.xml`
- 一键托管：推送到 `main` 分支即自动发布到 GitHub Pages，无需额外构建流程

## 本地预览与开发

```bash
git clone https://github.com/wpc6666/wpc6666.github.io.git
cd wpc6666.github.io
python3 -m http.server 8000   # 或直接双击打开 index.html
```

新增项目时，在 `index.html` 对应分类的 `.repo-grid` 中添加一张 `.repo-card` 卡片（名称 + 一句话描述 + 阅读/仓库链接）即可。

## 致谢

- [HKUST 科研写作指南](https://github.com/HKUSTDial/Supervisor-Skills)（香港科技大学李伯岩组：选题、论文写作、绘图、案例剖析）

© 2026 白澤 程 · 用 ❤️ 构建

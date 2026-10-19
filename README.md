# 白澤 程 · 个人主页

[![Pages](https://img.shields.io/badge/在线访问-wpc6666.github.io-254b9c.svg)](https://wpc6666.github.io/)
[![HTML](https://img.shields.io/badge/纯静态-HTML%20%2B%20CSS-e34f26.svg)](#技术说明)
[![Mobile](https://img.shields.io/badge/手机竖屏-已适配-1a7f37.svg)](#技术说明)

> 基于 GitHub Pages 的个人主页，
> 聚合全部学习知识库与开发工具的一站式入口。

**在线访问**：<https://wpc6666.github.io/>

---

## 这是什么

本仓库是 `wpc6666.github.io` 的**站点源码**。
定位「经济统计学学习者 · 论文写作爱好者 · 工具开发者」，
把散落在各仓库的学习资料与实用工具集中到一个入口。

---

## 站点收录

### 📚 学习知识库

| 项目 | 说明 |
|---|---|
| [经济统计学论文写作知识库](https://wpc6666.github.io/economic-statistics-thesis-knowledge/) | 从 0 基础到论文精通。5 门课程 / 637 篇笔记 / 83 张导图 |

### 🛠️ 工具项目

| 项目 | 说明 |
|---|---|
| [重财论文格式工具](https://wpc6666.github.io/cfec-thesis-formatter/) | 重庆财经学院毕业论文自动排版，输出 DOCX + LaTeX |
| [macOS 中文绘图配置](https://wpc6666.github.io/plot-cjk-config/) | R / Python / Stata 中文出图环境一键部署，解决豆腐块 |

### 🔧 其他工具

| 项目 | 说明 | 在线页 |
|---|---|---|
| **Shadowrocket** | 小火箭分流配置，44 条规则 | [在线查看](https://wpc6666.github.io/Shadowrocket/) |
| **Quantumult** | Quantumult 代理配置，两份完整方案 | [在线查看](https://wpc6666.github.io/Quantumult/) |
| **AutoBuildImmortalWrt** | ImmortalWrt 固件自动构建，7 个平台 | [在线查看](https://wpc6666.github.io/AutoBuildImmortalWrt/) |

---

## 技术说明

| 特性 | 实现 |
|---|---|
| **纯静态** | 原生 HTML + CSS，无框架依赖，加载快、易维护 |
| **手机适配** | 三档媒体查询（768 / 640 / 380 px），320 px 起零横向溢出 |
| **SEO 就绪** | description / keywords / author 元信息；已接入 Google Search Console 与必应 Webmaster |
| **搜索配置** | `robots.txt` + `sitemap.xml` |
| **一键托管** | 推送 `main` 即自动发布到 GitHub Pages，无需构建 |

---

## 本地预览

```bash
git clone https://github.com/wpc6666/wpc6666.github.io.git
cd wpc6666.github.io
python3 -m http.server 8000
# 浏览器打开 http://localhost:8000
```

或直接双击 `index.html`。

---

## 新增项目怎么做

1. 在 `index.html` 对应分类的 `.repo-grid` 里加一张 `.repo-card`
2. 卡片结构：`.repo-name` + `.repo-desc` + 一个或多个 `.repo-link`
3. 若有独立落地页，优先链到 `https://wpc6666.github.io/<repo>/`

---

## 目录结构

```
wpc6666.github.io/
├── index.html                      主页
├── AutoBuildImmortalWrt/
│   └── index.html                  fork 仓库的落地页（fork 无法开 Pages）
├── CNAME                          自定义域名（如有）
├── robots.txt
├── sitemap.xml
├── google*.html                    Google Search Console 验证
└── README.md
```

---

## 相关链接

| 用途 | 链接 |
|---|---|
| 主页 | <https://wpc6666.github.io/> |
| GitHub 账号 | <https://github.com/wpc6666> |
| HKUST 科研写作指南 | <https://github.com/HKUSTDial/Supervisor-Skills> |

---

© 2026 白澤 程 · 用 ❤️ 构建

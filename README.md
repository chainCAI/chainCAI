<div align="center">

# 白菜与风 · chainCAI

**AI 应用工程 —— 把想法做成能上线的东西**

<sub>RAG 系统 · LLM 工作流 · 全栈交付 · 独立产品</sub>

<br/>

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
<img src="https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white" />
<img src="https://img.shields.io/badge/LLM-412991?style=flat-square&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" />

</div>

---

### 在做什么

**AI 不是演示，是要跑起来的系统。** 我在做的是把大模型能力接进真实业务：检索、评测、计量、上线、运维，每一环都要能交付。

- **[DSH] 插件市场** — 自动收录 GitHub `dsh-plugin` 生态的静态站点，每日自动同步 + Cloudflare Pages 部署，规则透明（Star ≥ 100 自动精选）
- **海关商品智能归类** — RAG + 规则引擎，把报关归类从人工查表变成可审计、可复现的自动化流程
- **舆情监控全链路** — CDP 采集 → 大模型情感分析 → ECharts 看板 → 飞书推送，一个人跑完整个闭环

---

### 精选项目

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/chainCAI/dsh-plugins-store">
<img src="https://raw.githubusercontent.com/chainCAI/dsh-plugins-store/main/screenshots/home-cards.webp" width="100%" alt="DSH 插件市场" />
</a>

#### 🔌 [DSH 插件市场](https://github.com/chainCAI/dsh-plugins-store)

自动收录并分类 GitHub `dsh-plugin` 生态项目，构建时拉取全量 Topic 仓库，GitHub Actions 每日同步，push 即触发重建。

`Astro` `TypeScript` `Cloudflare Pages` `GitHub Actions`

**[在线访问 →](https://dsh.pages.dev)** · MIT

</td>
<td width="50%" valign="top">

<a href="https://github.com/chainCAI/HS-Classifier">
<img src="https://raw.githubusercontent.com/chainCAI/HS-Classifier/master/img/1.png" width="100%" alt="海关商品智能归类" />
</a>

#### 🧾 [HS-Classifier · 海关商品智能归类](https://github.com/chainCAI/HS-Classifier)

基于 RAG 的报关归类与申报要素校验系统，前后端分离 + Docker Compose 一键起，20K+ 字文档覆盖部署、测试与业务规则。

`Python` `FastAPI` `React` `RAG` `Docker`

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/chainCAI/weibo-sentiment-monitor">
<img src="https://img.shields.io/github/stars/chainCAI/weibo-sentiment-monitor?style=social" alt="stars" />
</a>

#### 📊 [微博舆情监控系统](https://github.com/chainCAI/weibo-sentiment-monitor)

基于 CDP 协议绕过反爬采集微博数据，接入百炼大模型做评论情感分析，支持自定义提示词模板，ECharts 可视化趋势，飞书机器人自动推送日报。

`Python` `FastAPI` `React` `CDP` `ECharts` `飞书 API`

</td>
<td width="50%" valign="top">

#### 🐱 [猫猫测试小站](https://github.com/chainCAI/cat-test-game)

用 AI 独立完成的产品，从设计、开发到部署全流程，累计 **近 200 万流量**。全过程拆解写在公众号里。

`TypeScript` `Vite` `通义文生图`

</td>
</tr>
</table>

<details>
<summary><b>更多项目</b></summary>

<br/>

| 项目 | 说明 |
|---|---|
| [AIproperty](https://github.com/chainCAI/AIproperty) | AI Coding 工程化流水线：把 AI 当项目成员的可复用资产模板（AGENTS.md / rules / specs / 记忆） |
| [ollama-web-chat](https://github.com/chainCAI/ollama-web-chat) | 本地部署的 AI 聊天 Web 应用，流式输出 + Markdown + LaTeX + 代码高亮 |

</details>

---

### 技术栈

| 层 | 用到的 |
|---|---|
| **AI / LLM** | 百炼 · DeepSeek · RAG 检索 · 提示词工程 · 情感分析 · 模型计量与成本归因 |
| **后端** | Python · FastAPI · SQLAlchemy · JWT · AES-256 · Go |
| **前端** | React · TypeScript · Vue 3 · Astro · ECharts · Tailwind |
| **数据与采集** | CDP 协议 · 定时任务调度 · SQLite / PostgreSQL |
| **交付运维** | Docker Compose · Nginx · Cloudflare Pages / Zero Trust · GitHub Actions |

---

### 写的东西

- [把 AI 当工程成员：如何搭出一套可复用的 AI Coding 工程化流水线](https://mp.weixin.qq.com/s/GcxnzsFcrNl-SxXU4qHrYw)
- [把 AI 当项目成员（落地版）：AI Coding 项目资产模板公开](https://mp.weixin.qq.com/s/xgkX0qHpuKiOGtG9fngreA)
- [用 AI 做猫猫测一测小网站，近 200 万流量，全制作过程分享](https://mp.weixin.qq.com/s/O7KWIPk9uxHoCop4WxtSRA)

---

<div align="center">

<sub>公众号：<b>白菜与风AI</b> · 有问题欢迎开 Issue</sub>

</div>

---
layout: default
title: "Horizon Summary: 2026-08-18 (ZH)"
date: 2026-08-18
lang: zh
---

> 从 36 条内容中筛选出 7 条重要资讯。

---

**科技新闻**
1. [Turbovec：Rust 实现的 Google TurboQuant 向量搜索库](#item-tech-news-1) ⭐️ 8.0/10
2. [Mojo🔥 is now open source](#item-tech-news-2) ⭐️ 8.0/10
3. [Linux 7.3 improves performance when running out of vRAM](#item-tech-news-3) ⭐️ 7.0/10
4. [💬 企业微信 5.0.10 开放 CLI 与 MCP，10 大办公模块可接入主流 Agent](#item-tech-news-4) ⭐️ 7.0/10
5. [中国要求部分政府相关机构卸载定制版 Windows 10，停用计划提前数月](#item-tech-news-5) ⭐️ 7.0/10
6. [国产 AI 芯片将占中国市场近 90%，寒武纪与华为成最大赢家](#item-tech-news-6) ⭐️ 7.0/10

**财经新闻**
1. [苹果美国 App Store 佣金收入降 18%，用户消费额二季度反降 6%](#item-finance-news-1) ⭐️ 8.0/10

---

## 科技新闻

<a id="item-tech-news-1"></a>
### [Turbovec：Rust 实现的 Google TurboQuant 向量搜索库](https://github.com/RyanCodrai/turbovec) ⭐️ 8.0/10

Turbovec 是一个用 Rust 编写的库，基于 Google 的 TurboQuant 算法实现高效向量搜索。它能够在 4 GB 内存中存储 1,0000,000 条向量，显著提升索引速度和查询性能，amay 适用于 AI 与机器学习工作负载。该库提供了快速索引、调试和性能测试的工具，amay 让开发者更容易构建和维护大规模向量索引。 Droid 目前已被 Qdrant 等平台集成，证明其在实际应用中的可行性。

hackernews · fittingopposite · 8月18日 18:07 · [社区讨论](https://news.ycombinator.com/item?id=49349898)

**「TurboQuant 与向量搜索概述」** TurboQuant 是 Google 研究团队提出的一种数据无关量化算法，能够在不需要单独训练阶段的情况下实现接近信息理论下限的失真率。它通过压缩向量表示来显著减小索引体积，同时保持高检索质量。Turbovec 则是基于该算法用 Rust 编写的向量索引库，并提供 Python 绑定，旨在为 AI 与机器学习工作负载提供更快的索引与查询性能。

**「影响」** 使用 Turbovec 可让开发者在相同硬件上以更快的速度完成向量索引，并在调试和性能测试阶段节省大量时间。

**「社区讨论」** 社区成员指出 FAISS 已不再是最先进的选择，并提到 Qdrant 已经在使用 TurboQuant；有人建议改进 README 以提升可采用性，并提醒关注 TurboQuant 的公开评审。

<details><summary>参考链接</summary>
<ul>
<li><a href="https://github.com/RyanCodrai/turbovec">GitHub - RyanCodrai/turbovec: A vector index built on TurboQuant, written in Rust with Python bindings · GitHub</a></li>
<li><a href="https://medium.com/data-science-in-your-pocket/turbovec-googles-turboquant-makes-vector-search-smaller-faster-and-simpler-fdea72674aad">turbovec : Google’s TurboQuant Makes Vector Search Smaller, Faster, and Simpler | by Mehul Gupta | Data Science in Your Pocket | Medium</a></li>
<li><a href="https://www.marktechpost.com/2026/05/20/meet-turbovec-a-rust-vector-index-with-python-bindings-and-built-on-googles-turboquant-algorithm/">Meet Turbovec: A Rust Vector Index with Python Bindings, and Built on Google&#x27;s TurboQuant Algorithm - MarkTechPost</a></li>

</ul>
</details>

**标签**: `#Rust`, `#vector search`, `#TurboQuant`, `#AI`, `#performance`

---

<a id="item-tech-news-2"></a>
### [Mojo🔥 is now open source](https://simonwillison.net/2026/Aug/18/mojo-is-now-open-source/) ⭐️ 8.0/10

Mojo 1.0, a new AI‑focused programming language, has been released as open source under Apache 2, marking a major step for developers seeking high‑performance Python alternatives.

rss · Simon Willison · 8月18日 21:39

**标签**: `#Mojo`, `#open source`, `#AI programming`, `#high‑performance computing`, `#software engineering`

---

<a id="item-tech-news-3"></a>
### [Linux 7.3 improves performance when running out of vRAM](https://pixelcluster.dev/VRAM-Overcommit/) ⭐️ 7.0/10

Linux 7.3 brings performance enhancements for vRAM management, benefiting GPU‑heavy workloads and kernel developers.

hackernews · flaburgan · 8月18日 07:51 · [社区讨论](https://news.ycombinator.com/item?id=49342719)

**标签**: `#Linux kernel`, `#GPU memory`, `#performance`, `#systems`, `#open source`

---

<a id="item-tech-news-4"></a>
### [💬 企业微信 5.0.10 开放 CLI 与 MCP，10 大办公模块可接入主流 Agent](https://mp.weixin.qq.com/s/uJf57P15-FQL_u6jLHiGYA) ⭐️ 7.0/10

Enterprise WeChat 5.0.10 opens CLI/MCP for AI agents to access core office modules, enhancing enterprise AI integration.

telegram · zaihuapd · 8月18日 06:22

**标签**: `#enterprise AI integration`, `#WeChat Work`, `#CLI`, `#MCP`, `#office automation`

---

<a id="item-tech-news-5"></a>
### [中国要求部分政府相关机构卸载定制版 Windows 10，停用计划提前数月](https://www.bloomberg.com/news/articles/2026-08-18/china-axing-microsoft-windows-from-state-agencies-ahead-of-plan) ⭐️ 7.0/10

China accelerates the removal of customized Windows 10 from certain government agencies, citing data‑security worries and moving the deprecation plan months ahead of schedule.

telegram · zaihuapd · 8月18日 06:22

**标签**: `#Windows`, `#Security`, `#Policy`, `#Government`, `#Operating System`

---

<a id="item-tech-news-6"></a>
### [国产 AI 芯片将占中国市场近 90%，寒武纪与华为成最大赢家](https://www.tomshardware.com/tech-industry/artificial-intelligence/chinas-homegrown-ai-accelerators-to-supply-90-percent-of-the-countrys-domestic-market-analysts-suggest-cambricon-and-huawei-expected-to-be-the-biggest-winners-in-the-shift-away-from-nvidia-and-amd) ⭐️ 7.0/10

China’s domestic AI chip market is projected to reach 90% share by 2026, with Cambricon and Huawei leading the shift away from Nvidia and AMD.

telegram · zaihuapd · 8月18日 13:03

**标签**: `#AI hardware`, `#market forecast`, `#China`, `#Cambricon`, `#Huawei`

---

## 财经新闻

<a id="item-finance-news-1"></a>
### [苹果美国 App Store 佣金收入降 18%，用户消费额二季度反降 6%](https://www.macrumors.com/2026/08/18/apple-app-store-revenue-falling/) ⭐️ 8.0/10

Apple’s App Store commission revenue fell 18% in the US and Q2 user spending dropped 6% YoY, reflecting regulatory pressures on its services growth.

telegram · zaihuapd · 8月18日 12:17

**标签**: `#Apple`, `#App Store`, `#Revenue`, `#Services`, `#Market`

---
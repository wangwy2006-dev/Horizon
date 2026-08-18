---
layout: default
title: "Horizon Summary: 2026-08-18 (EN)"
date: 2026-08-18
lang: en
---

> From 36 items, 7 important content pieces were selected

---

**Technology News**
1. [Turbovec: Rust Implementation of Google’s TurboQuant for Vector Search](#item-tech-news-1) ⭐️ 8.0/10
2. [Mojo🔥 is now open source](#item-tech-news-2) ⭐️ 8.0/10
3. [Linux 7.3 improves performance when running out of vRAM](#item-tech-news-3) ⭐️ 7.0/10
4. [💬 企业微信 5.0.10 开放 CLI 与 MCP，10 大办公模块可接入主流 Agent](#item-tech-news-4) ⭐️ 7.0/10
5. [中国要求部分政府相关机构卸载定制版 Windows 10，停用计划提前数月](#item-tech-news-5) ⭐️ 7.0/10
6. [国产 AI 芯片将占中国市场近 90%，寒武纪与华为成最大赢家](#item-tech-news-6) ⭐️ 7.0/10

**Financial News**
1. [苹果美国 App Store 佣金收入降 18%，用户消费额二季度反降 6%](#item-finance-news-1) ⭐️ 8.0/10

---

## Technology News

<a id="item-tech-news-1"></a>
### [Turbovec: Rust Implementation of Google’s TurboQuant for Vector Search](https://github.com/RyanCodrai/turbovec) ⭐️ 8.0/10

Turbovec is a Rust library that implements Google’s TurboQuant vector‑search algorithm, offering a compact and efficient solution for AI and ML workloads. The library can index 10 million vectors in just 4 GB of memory, providing faster indexing and smoother debugging compared to older approaches like FAISS. It is designed to integrate with Rust ecosystems, with plans for SQLite bindings to broaden its usability. The project has attracted attention from the community, noting its performance gains and the fact that Qdrant has already incorporated TurboQuant. Open review discussions highlight both the strengths and areas for improvement in the implementation.

hackernews · fittingopposite · Aug 18, 18:07 · [Discussion](https://news.ycombinator.com/item?id=49349898)

**「Background」** TurboQuant is a data‑oblivious quantization algorithm from Google Research that compresses high‑dimensional vectors with minimal distortion and no training phase. Turbovec implements this algorithm in Rust, providing a vector index with Python bindings that enables efficient storage and search for AI/ML workloads. The library builds on TurboQuant’s near‑optimal distortion guarantees, achieving compression ratios that allow 10 million vectors to fit in roughly 4 GB.

**「Impact」** Developers building vector‑search systems can now index 10 million vectors in 4 GB, dramatically speeding up debugging and performance testing.

**「Community Discussion」** Users praise the performance gains and anticipate useful SQLite bindings, while some prefer existing solutions like Qdrant that already support TurboQuant. There is also a call for clearer documentation and reference to open review comments for further evaluation.

<details><summary>References</summary>
<ul>
<li><a href="https://github.com/RyanCodrai/turbovec">GitHub - RyanCodrai/turbovec: A vector index built on TurboQuant, written in Rust with Python bindings · GitHub</a></li>
<li><a href="https://medium.com/data-science-in-your-pocket/turbovec-googles-turboquant-makes-vector-search-smaller-faster-and-simpler-fdea72674aad">turbovec : Google’s TurboQuant Makes Vector Search Smaller, Faster, and Simpler | by Mehul Gupta | Data Science in Your Pocket | Medium</a></li>
<li><a href="https://www.marktechpost.com/2026/05/20/meet-turbovec-a-rust-vector-index-with-python-bindings-and-built-on-googles-turboquant-algorithm/">Meet Turbovec: A Rust Vector Index with Python Bindings, and Built on Google&#x27;s TurboQuant Algorithm - MarkTechPost</a></li>

</ul>
</details>

**Tags**: `#Rust`, `#vector search`, `#TurboQuant`, `#AI`, `#performance`

---

<a id="item-tech-news-2"></a>
### [Mojo🔥 is now open source](https://simonwillison.net/2026/Aug/18/mojo-is-now-open-source/) ⭐️ 8.0/10

Mojo 1.0, a new AI‑focused programming language, has been released as open source under Apache 2, marking a major step for developers seeking high‑performance Python alternatives.

rss · Simon Willison · Aug 18, 21:39

**Tags**: `#Mojo`, `#open source`, `#AI programming`, `#high‑performance computing`, `#software engineering`

---

<a id="item-tech-news-3"></a>
### [Linux 7.3 improves performance when running out of vRAM](https://pixelcluster.dev/VRAM-Overcommit/) ⭐️ 7.0/10

Linux 7.3 brings performance enhancements for vRAM management, benefiting GPU‑heavy workloads and kernel developers.

hackernews · flaburgan · Aug 18, 07:51 · [Discussion](https://news.ycombinator.com/item?id=49342719)

**Tags**: `#Linux kernel`, `#GPU memory`, `#performance`, `#systems`, `#open source`

---

<a id="item-tech-news-4"></a>
### [💬 企业微信 5.0.10 开放 CLI 与 MCP，10 大办公模块可接入主流 Agent](https://mp.weixin.qq.com/s/uJf57P15-FQL_u6jLHiGYA) ⭐️ 7.0/10

Enterprise WeChat 5.0.10 opens CLI/MCP for AI agents to access core office modules, enhancing enterprise AI integration.

telegram · zaihuapd · Aug 18, 06:22

**Tags**: `#enterprise AI integration`, `#WeChat Work`, `#CLI`, `#MCP`, `#office automation`

---

<a id="item-tech-news-5"></a>
### [中国要求部分政府相关机构卸载定制版 Windows 10，停用计划提前数月](https://www.bloomberg.com/news/articles/2026-08-18/china-axing-microsoft-windows-from-state-agencies-ahead-of-plan) ⭐️ 7.0/10

China accelerates the removal of customized Windows 10 from certain government agencies, citing data‑security worries and moving the deprecation plan months ahead of schedule.

telegram · zaihuapd · Aug 18, 06:22

**Tags**: `#Windows`, `#Security`, `#Policy`, `#Government`, `#Operating System`

---

<a id="item-tech-news-6"></a>
### [国产 AI 芯片将占中国市场近 90%，寒武纪与华为成最大赢家](https://www.tomshardware.com/tech-industry/artificial-intelligence/chinas-homegrown-ai-accelerators-to-supply-90-percent-of-the-countrys-domestic-market-analysts-suggest-cambricon-and-huawei-expected-to-be-the-biggest-winners-in-the-shift-away-from-nvidia-and-amd) ⭐️ 7.0/10

China’s domestic AI chip market is projected to reach 90% share by 2026, with Cambricon and Huawei leading the shift away from Nvidia and AMD.

telegram · zaihuapd · Aug 18, 13:03

**Tags**: `#AI hardware`, `#market forecast`, `#China`, `#Cambricon`, `#Huawei`

---

## Financial News

<a id="item-finance-news-1"></a>
### [苹果美国 App Store 佣金收入降 18%，用户消费额二季度反降 6%](https://www.macrumors.com/2026/08/18/apple-app-store-revenue-falling/) ⭐️ 8.0/10

Apple’s App Store commission revenue fell 18% in the US and Q2 user spending dropped 6% YoY, reflecting regulatory pressures on its services growth.

telegram · zaihuapd · Aug 18, 12:17

**Tags**: `#Apple`, `#App Store`, `#Revenue`, `#Services`, `#Market`

---
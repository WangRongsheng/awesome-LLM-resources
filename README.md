![](./assets/logo6.png)

<p align="center">全世界最好的大语言模型资源汇总 持续更新</p>

<p align="center">
  <a href="https://github.com/WangRongsheng/awesome-LLM-resourses"><img src=https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg ></a>
  <a href="https://github.com/WangRongsheng/awesome-LLM-resourses"><img src=https://img.shields.io/github/forks/WangRongsheng/awesome-LLM-resourses.svg?style=social ></a>
  <a href="https://github.com/WangRongsheng/awesome-LLM-resourses"><img src=https://img.shields.io/github/stars/WangRongsheng/awesome-LLM-resourses.svg?style=social ></a>
  <a href="https://github.com/WangRongsheng/awesome-LLM-resourses"><img src=https://img.shields.io/github/watchers/WangRongsheng/awesome-LLM-resourses.svg?style=social ></a>
  <a href="https://gitcode.com/wangrongsheng/awesome-LLM-resources"><img src="https://raw.githubusercontent.com/WangRongsheng/awesome-LLM-resources/main/assets/gitcode.png" height="25" alt="gitcode">
</a>
</p>

> [!TIP]
> 如果您对**医疗数据集/大模型/多模态/评估相关资源感兴趣**！请访问我们的 🤗 [Awesome-AI4Med](https://github.com/FreedomIntelligence/Awesome-AI4Med) !

---

#### Contents

- [推荐 Suggestion](#推荐-Suggestion)
- [数据 Data](#数据-Data)
- [微调 Fine-Tuning](#微调-Fine-Tuning)
- [Agentic RL](#Agentic-RL)
- [推理 Inference](#推理-Inference)
- [评估 Evaluation](#评估-Evaluation)
- [体验 Usage](#体验-Usage)
- [知识库 RAG](#知识库-RAG)
- [智能体 Agents](#智能体-Agents)
- [研究 Research](#研究-Research)
- [代码 Coding](#代码-Coding)
- [视频 Video](#视频-Video)
- [图片 Image](#图片-Image)
- [搜索 Search](#搜索-Search)
- [语音 Speech](#语音-Speech)
- [统一模型 Unified Model](#统一模型-Unified-Model)
- [书籍 Book](#书籍-Book)
- [课程 Course](#课程-Course)
- [教程 Tutorial](#教程-Tutorial)
- [论文 Paper](#论文-Paper)
- [社区 Community](#社区-Community)
- [模型上下文协议 MCP](#模型上下文协议-MCP)
- [技能 Skills](#技能-Skills)
- [推理 Open o1](#推理-Open-o1)
- [推理 Open o3](#推理-Open-o3)
- [小语言模型 Small Language Model](#小语言模型-Small-Language-Model)
- [小多模态模型 Small Vision Language Model](#小多模态模型-Small-Vision-Language-Model)
- [技巧 Tips](#技巧-tips)

![](https://camo.githubusercontent.com/2722992d519a722218f896d5f5231d49f337aaff4514e78bd59ac935334e916a/68747470733a2f2f692e696d6775722e636f6d2f77617856496d762e706e67)

## 推荐 Suggestion

#### Podcast

- [翁家翌：OpenAI，GPT，强化学习，Infra，后训练，天授，tuixue，开源，CMU，清华｜WhynotTV Podcast](https://www.bilibili.com/video/BV1darmBcE4A?vd_source=c739db1ebdd361d47af5a0b8497417db)
- [Lovart 创始人陈冕×罗永浩！且让我大闹一场，然后悄然离去](https://www.bilibili.com/video/BV14eiQBmEbN/?spm_id_from=333.1387.upload.video_card.click)
- [MiniMax 创始人闫俊杰×罗永浩！大山并非无法翻越](https://www.bilibili.com/video/BV11NmtBzE36/?spm_id_from=333.1387.upload.video_card.click&vd_source=c739db1ebdd361d47af5a0b8497417db)
- [影视飓风TIM×罗永浩！用影像打开世界的梦想家](https://www.bilibili.com/video/BV1B5xkzPEhx/?spm_id_from=333.1387.upload.video_card.click&vd_source=c739db1ebdd361d47af5a0b8497417db)
- [129. 全球大模型第一股的上市访谈，和智谱CEO张鹏聊：敢问路在何方？](https://www.youtube.com/watch?v=9zSMTUUEfmU&list=PLwAchVoh-4zNSI5UlKEkKCL5r_jJyrFeO&index=2)
- [128. Manus决定出售前最后的访谈：啊，这奇幻的2025年漂流啊…](https://www.youtube.com/watch?v=MW-ezf2RhVg&list=PLwAchVoh-4zNSI5UlKEkKCL5r_jJyrFeO&index=3)
- [122. 朱啸虎现实主义故事的第三次连载：人工智能的盛筵与泡泡](https://www.youtube.com/watch?v=wK0-m3rKgZ0&list=PLwAchVoh-4zNSI5UlKEkKCL5r_jJyrFeO&index=9)
- [119. Kimi Linear、Minimax M2？和杨松琳考古算法变种史，并预演未来架构改进方案](https://www.youtube.com/watch?v=858HR43pegk&list=PLwAchVoh-4zNSI5UlKEkKCL5r_jJyrFeO&index=12&t=1070s)
- [118. 对李想的第二次3小时访谈：CEO大模型、MoE、梁文锋、VLA、能量、记忆、对抗人性、亲密关系、人类的智慧](https://www.youtube.com/watch?v=RxXVq7-sJzM&list=PLwAchVoh-4zNSI5UlKEkKCL5r_jJyrFeO&index=13)
- [115. 对OpenAI姚顺雨3小时访谈：6年Agent研究、人与系统、吞噬的边界、既单极又多元的世界](https://www.youtube.com/watch?v=gQgKkUsx5q0&list=PLwAchVoh-4zNSI5UlKEkKCL5r_jJyrFeO&index=16)
- [113. 和杨植麟时隔1年的对话：K2、Agentic LLM、缸中之脑和“站在无限的开端”](https://www.youtube.com/watch?v=ouG6jrkECrc&list=PLwAchVoh-4zNSI5UlKEkKCL5r_jJyrFeO&index=18)

## 数据 Data

> [!NOTE]
> 
> 此处命名为`数据`，但这里并没有提供具体数据集，而是提供了处理获取大规模数据的方法


1. [AotoLabel](https://github.com/refuel-ai/autolabel): Label, clean and enrich text datasets with LLMs.
2. [LabelLLM](https://github.com/opendatalab/LabelLLM): The Open-Source Data Annotation Platform.
3. [data-juicer](https://github.com/modelscope/data-juicer): A one-stop data processing system to make data higher-quality, juicier, and more digestible for LLMs!
4. [OmniParser](https://github.com/jf-tech/omniparser): a native Golang ETL streaming parser and transform library for CSV, JSON, XML, EDI, text, etc.
5. [MinerU (`🔥`)](https://github.com/opendatalab/MinerU): MinerU is a one-stop, open-source, high-quality data extraction tool, supports PDF/webpage/e-book extraction.
6. [PDF-Extract-Kit](https://github.com/opendatalab/PDF-Extract-Kit): A Comprehensive Toolkit for High-Quality PDF Content Extraction.
7. [Parsera](https://github.com/raznem/parsera): Lightweight library for scraping web-sites with LLMs.
8. [Sparrow](https://github.com/katanaml/sparrow): Sparrow is an innovative open-source solution for efficient data extraction and processing from various documents and images.
9. [Docling](https://github.com/DS4SD/docling): Get your documents ready for gen AI.
10. [GOT-OCR2.0](https://github.com/Ucas-HaoranWei/GOT-OCR2.0): OCR Model.
11. [LLM Decontaminator](https://github.com/lm-sys/llm-decontaminator): Rethinking Benchmark and Contamination for Language Models with Rephrased Samples.
12. [DataTrove](https://github.com/huggingface/datatrove): DataTrove is a library to process, filter and deduplicate text data at a very large scale.
13. [llm-swarm](https://github.com/huggingface/llm-swarm/tree/main/examples/textbooks): Generate large synthetic datasets like [Cosmopedia](https://huggingface.co/datasets/HuggingFaceTB/cosmopedia).
14. [Distilabel](https://github.com/argilla-io/distilabel): Distilabel is a framework for synthetic data and AI feedback for engineers who need fast, reliable and scalable pipelines based on verified research papers.
15. [Common-Crawl-Pipeline-Creator](https://huggingface.co/spaces/lhoestq/Common-Crawl-Pipeline-Creator): The Common Crawl Pipeline Creator.
16. [Tabled](https://github.com/VikParuchuri/tabled): Detect and extract tables to markdown and csv.
17. [Zerox](https://github.com/getomni-ai/zerox): Zero shot pdf OCR with gpt-4o-mini.
18. [DocLayout-YOLO](https://github.com/opendatalab/DocLayout-YOLO): Enhancing Document Layout Analysis through Diverse Synthetic Data and Global-to-Local Adaptive Perception.
19. [TensorZero](https://github.com/tensorzero/tensorzero): make LLMs improve through experience.
20. [Promptwright](https://github.com/StacklokLabs/promptwright): Generate large synthetic data using a local LLM.
21. [pdf-extract-api](https://github.com/CatchTheTornado/pdf-extract-api): Document (PDF) extraction and parse API using state of the art modern OCRs + Ollama supported models.
22. [pdf2htmlEX](https://github.com/pdf2htmlEX/pdf2htmlEX): Convert PDF to HTML without losing text or format.
23. [Extractous](https://github.com/yobix-ai/extractous): Fast and efficient unstructured data extraction. Wri

## 智能体 Agents

1. [Anchor Browser](https://anchorbrowser.io): An agentic browser infrastructure platform for AI agents and browser automation, offering fully managed, humanized Chromium instances that bypass bot detection with a Cloudflare partnership.
---
hide:
  - navigation
  - footer
---

<div class="profile-header">
  <img class="profile-avatar" src="assets/profile-avatar.jpg" alt="褚文浩的 GitHub 头像">
  <div class="profile-intro">
    <h1>褚文浩</h1>
    <p class="profile-role">助理研究员 · 多模态与计算机视觉</p>
    <p class="profile-meta">浙江大学全息研究院</p>
    <div class="profile-focus" aria-label="研究方向">
      <span>VLM 后训练</span>
      <span>低资源 OCR</span>
      <span>计算机视觉</span>
    </div>

    <div class="profile-links">
      <a class="profile-link email-link" href="mailto:2896475326@qq.com" title="邮箱" aria-label="邮箱" data-label="邮箱"><span>开启邮件客户端</span></a>
      <a class="profile-link github-link" href="https://github.com/HaogeBob" title="GitHub" aria-label="GitHub" data-label="GitHub" target="_blank" rel="noopener noreferrer"><span>查看 GitHub 主页</span></a>
      <a class="profile-link kaggle-link" href="https://www.kaggle.com/haogebob" title="Kaggle" aria-label="Kaggle" data-label="Kaggle" target="_blank" rel="noopener noreferrer"><span>查看 Kaggle 主页</span></a>
      <a class="profile-link openreview-link" href="https://openreview.net/profile?id=%7EWenhao_Chu1" title="OpenReview" aria-label="OpenReview" data-label="OpenReview" target="_blank" rel="noopener noreferrer"><span>查看 OpenReview 主页</span></a>
    </div>
  </div>
</div>

## 个人简介 { #biography }

我目前在浙江大学全息研究院担任助理研究员，主要关注**多模态大模型、视觉语言模型后训练与计算机视觉**。此前在字节跳动从事视频流渲染与图形算法开发，后将研究重心转向深度学习，目前在模型幻觉抑制、低资源 OCR 与智能体训练及推理等方向开展研究。

我拥有经济学本科与西方经济学硕士背景，辅修计算机科学。

## 教育背景 { #education }

<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-date">2021 — 2023</div>
    <div><strong>浙江大学</strong><br>西方经济学 · 硕士研究生（保研）</div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">2017 — 2021</div>
    <div><strong>浙江大学</strong><br>经济学 · 本科</div>
  </div>
</div>

**荣誉与能力：**浙江大学一等奖学金、恒逸奖学金、不动产奖学金。

## 工作经历 { #experience }

### 浙江大学全息研究院

<span class="entry-meta">助理研究员 · 2025.04 — 至今</span>

- **国画模型幻觉抑制：**使用迭代式 DPO 对国画赏析模型进行后训练，在 MMHAL-Bench 上将幻觉率从 **37% 降至 30%**。共同第一作者论文 *Zhihua: Leveraging Vision Language Models for TCPs* 正在向 NPJ 投稿。
- **国画题跋 OCR 识别系统：**主导题跋识别任务，针对国画题跋低资源、高噪声的特点提出领域自举范式。在少量样本基础上设计样本扩充 pipeline，用于迭代式训练；最终模型 F1 比基模提高 **8%**，比 GPT-5.4 提高 **30%**。独立第一作者论文 *Domain-Bootstrapped OCR for Low-Resource TCPIs* 计划投稿 ICLR 2027。
- **国画 Agent 训练与推理框架：**改造开源 Agent RL 框架，使其适配国画模型与领域工具；支持基于 LLM 的工具调用、多轮问答验证、长期记忆管理、总结与奖励反馈，并协同管理 OCR、技法分析、RAG 与联网搜索等工具。

### 深度学习转型与项目实践

<span class="entry-meta">2024.01 — 2025.04</span>

- 系统学习浙江大学机器学习课程、CS231n 与《动手学深度学习》等课程，完成从图形算法到深度学习方向的知识与实践迁移。
- 实践多个 Kaggle 计算机视觉竞赛项目，并完成部分 NLP 与推荐系统项目。

### 字节跳动

<span class="entry-meta">渲染开发 · 2023.07 — 2024.01</span>

- 负责飞书产品线视频流渲染模块，进行渲染算法调优，并把控画面质量与性能消耗，提升视频流画面质量。
- 使用双边滤波算法替换原有 Mipmap 方案，在性能开销增幅有限的情况下，提高共享高分辨率文档的显示锐度。
- 针对 Shader 编译慢的问题设计并实现预编译方案，使用户可感知的编译等待时间下降 **90%**。

### 莉莉丝游戏

<span class="entry-meta">UE4 游戏开发实习生 · 2022.06 — 2022.08</span>

- 修改 UE4.26 Runtime 模块下的 Shader Bytecode 文件系统，拆分 Shader Archive 并调整读写逻辑，以支持 Shader 增量更新。

## 研究与论文 { #research }

### Zhihua: Leveraging Vision Language Models for TCPs

**共同第一作者 · NPJ 投稿中**

针对国画赏析模型的幻觉问题，使用迭代式 DPO 优化视觉语言模型，在 MMHAL-Bench 上将幻觉率从 **37% 降至 30%**。

### Domain-Bootstrapped OCR for Low-Resource TCPIs

**独立第一作者 · 计划投稿 ICLR 2027**

面向低资源、高噪声国画题跋识别提出领域自举方法，通过样本扩充与迭代训练改善识别质量；最终模型 F1 比基模提高 **8%**，比 GPT-5.4 提高 **30%**。

## 代表项目 { #projects }

### 国画 Agent 训练与推理框架

- 基于开源 Agent RL 框架完成面向国画领域的训练与推理适配，支持基于 LLM 的工具调用、多轮问答验证、长期记忆管理、总结与奖励反馈。
- 将国画问答模型与 OCR、技法分析、RAG、联网搜索等工具统一编排，构建可协同调用的国画 Agent 系统。

### 蒙特卡洛光线追踪渲染器

- 使用 C++ 从基础代码实现离线光线追踪渲染器，不依赖 OpenGL 等图形库。
- 基于微平面理论构建 BRDF，并为光滑物体实现重要性采样。

### 基于 PRT 的实时全局光照

- 使用 C++ 预计算光照项与传输项，并将结果存储为球谐函数系数。
- 使用 WebGL 完成实时渲染，并利用球谐函数的旋转特性支持光源旋转。

## 竞赛经历 { #competitions }

| 竞赛 | 排名 | 成绩 |
| --- | ---: | --- |
| Kaggle BirdCLEF 2025 | 27 / 2027 | 银牌第 13 名 |
| Kaggle CSIRO Image2Biomass Prediction 2026 | 89 / 3805 | 银牌 |

BirdCLEF 项目基于鸟叫音频进行物种分类；Image2Biomass 项目依据牧场航拍顶视图回归预测五类牧草生物量。

## 技术能力 { #skills }

`Python` · `C/C++` · `PyTorch` · `MS-Swift` · `DeepSpeed` · `LoRA` · `VLM Post-training` · `RLHF` · `RLAIF` · `Stable Diffusion` · `Recommendation Systems` · `Computer Vision` · `WebGL` · `UE4`

## 联系方式 { #contact }

**邮箱：**[2896475326@qq.com](mailto:2896475326@qq.com)

<p class="last-updated">最后更新：2026 年 8 月</p>

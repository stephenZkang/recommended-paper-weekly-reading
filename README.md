# 每周推荐论文精读 (Recommended-Paper-Weekly-Reading)

本仓库整理了每周的推荐论文精读，旨在为自己记录阅读推荐相关论文。

您可以通过本仓库：
- **跟踪阅读进度**：使用 `状态` 列标记每篇论文的阅读情况。
- **记录和沉淀思考**：为每篇论文创建独立的笔记文件，并链接到主列表。
- **快速概览**：清晰地查看各个子领域的核心论文和贡献。

## 目录
- [202509](#202509)


## 如何使用
1. **Fork 本仓库**到您自己的 Git账号。
2. **Clone 仓库**到本地。
3. 当您开始阅读一篇论文时，在 `README.md` 中将其**状态**从 `⬜️ 未读` 修改为 `⏳ 在读`。
4. 在 `notes/` 文件夹下，复制 `template.md` 并重命名为 `[编号]-[关键词].md` (例如 `001-dqn.md`)，开始记录您的笔记。
5. 完成阅读和笔记后，将**状态**修改为 `✅ 已读`。
6. `commit` 和 `push` 您的更改。

---

## 202509

### a. 论文周报[0901-0907] (12篇)

| # | 论文标题 (Title) | 作者 & 年份 |   状态    |                  我的笔记                   |
|:-:|:---|:---|:-------:|:---------------------------------------:|
| 1 | [Efficient Item ID Generation for Large-Scale LLM-based Recommendation](https://arxiv.org/abs/2509.03746) | Anushya Subbiah,<br /> 2025 |  ✅ 已读   | [笔记](notes/2509/one-week/001-item-id-generation.md) |
| 2 | [Enhancing Interpretability and Effectiveness in Recommendation with Numerical Features via Learning to Contrast the Counterfactual samples](https://arxiv.org/abs/2509.03187) | Xiaoxiao Xu,<br /> 2025 |  ✅ 已读   |        [笔记](notes/2509/one-week/002-ccss.md)        |
| 3 | [RecBase: Generative Foundation Model Pretraining for Zero-Shot Recommendation](https://arxiv.org/abs/2509.03131) | Sashuai Zhou, <br />2025 |  ✅ 已读   |    [笔记](notes/2509/one-week/003-recbase.md)     |
| 4 | [A Plug-and-play Model-agnostic Embedding Enhancement Approach for Explainable Recommendation](https://arxiv.org/abs/2509.03130) | Yunqi Mi,2025 |  ✅ 已读   |     [笔记](notes/2509/one-week/004-rvrec.md)     |
| 5 | [ RankGraph: Unified Heterogeneous Graph Learning for Cross-Domain Recommendation](https://arxiv.org/abs/2509.02942) | Renzhi Wu, 2025 |  ✅ 已读   |        [笔记](notes/2509/one-week/005-rankgraph.md)         |
| 6 | [Empowering Large Language Model for Sequential Recommendation via Multimodal Embeddings and Semantic IDs](https://arxiv.org/abs/2509.02017) | Yuhao Wang, 2025 |  ✅ 已读   |      [笔记](notes/2509/one-week/006-mme-sid.md)       |
| 7 | [Cloud-Device Collaborative Agents for Sequential Recommendation](https://arxiv.org/abs/2509.01551) | Jing Long, 2025 |  ✅ 已读   |      [笔记](notes/2509/one-week/007-cda4rec.md)       |
| 8 | [Ultra Fast Warm Start Solution for Graph Recommendations](https://arxiv.org/abs/2509.01549) | Viacheslav Yusupov, <br />2025 |  ✅ 已读   |      [笔记](notes/2509/one-week/008-ultra-gcn.md)       |
| 9 | [Learning to Shop Like Humans: A Review-driven Retrieval-Augmented Recommendation Framework with LLMs](https://arxiv.org/abs/2509.00698) | Yuhao Wang, 2025 |  ✅ 已读   |      [笔记](notes/2509/one-week/009-revbrowse.md)       |
| 10 | [Beyond Negative Transfer: Disentangled Preference-Guided Diffusion for Cross-Domain Sequential Recommendation](https://arxiv.org/abs/2509.00389) | Xiaoxin Ye, 2025 |  ✅ 已读   |      [笔记](notes/2509/one-week/010-dpg-diff.md)       |
| 11 | [A Privacy-Preserving Recommender for Filling Web Forms Using a Local Large Language Model](https://arxiv.org/abs/2509.01527) | Amirreza Nayyeri,<br /> Abbas Rasoolzadegan, 2025 |  ✅ 已读   |      [笔记](notes/2509/one-week/011-local-llm.md)       |
| 12 | [ MARS: Modality-Aligned Retrieval for Sequence Augmented CTR Prediction](https://arxiv.org/abs/2509.01184) | Yutian Xiao, 2025 |  ✅ 已读   |      [笔记](notes/2509/one-week/012-mars.md)       |

### b. 论文周报[0908-0914] (12篇)

| # | 论文标题 (Title)                                                                                                                                                | 作者 & 年份                                                          |   状态   |                    我的笔记                    |
|:-:|:------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------|:------:|:------------------------------------------:|
| 1 | [CESRec: Constructing Pseudo Interactions for Sequential Recommendation via Conversational Feedback](https://arxiv.org/abs/2509.09342)                      | Yifan Wang,<br /> 2025                                           | ✅ 已读  |  [笔记](notes/2509/two-week/001-ces-rec.md)  |
| 2 | [Modality Alignment with Multi-scale Bilateral Attention for Multimodal Recommendation](https://arxiv.org/abs/2509.09114)                                   | Xiaoxiao Xu,<br /> 2025                                          | ✅ 已读  |   [笔记](notes/2509/two-week/002-mamba-rec.md)    |
| 3 | [PerFairX: Is There a Balance Between Fairness and Personality in Large Language Model Recommendations?](https://arxiv.org/abs/2509.08829)                  | Chandan Kumar Sah <br />2025                                     | ✅ 已读  |  [笔记](notes/2509/two-week/003-perfairx.md)  |
| 4 | [Beyond Negative Transfer: Disentangled Preference-Guided Diffusion for Cross-Domain Sequential Recommendation](https://arxiv.org/abs/2509.00389)           | Xiaoxin Ye,2025                                                  | ✅ 已读  |   [笔记](notes/2509/two-week/004-dpg-diff.md)   |
| 5 | [Datasets for Navigating Sensitive Topics in Recommendation Systems](https://arxiv.org/abs/2509.07269)                                                      | Amelia Kovacs, 2025                                              | ✅ 已读  | [笔记](notes/2509/two-week/005-ml-ddd.md) |
| 6 | [RecMind: LLM-Enhanced Graph Neural Networks for Personalized Consumer Recommendations](https://arxiv.org/abs/2509.06286)                                   | Chang Xue, 2025                                                  | ✅ 已读  |  [笔记](notes/2509/two-week/006-recmind.md)  |
| 7 | [REMI: A Novel Causal Schema Memory Architecture for Personalized Lifestyle Recommendation Agents](https://arxiv.org/abs/2509.06269)                        | Vishal Raman, 2025                                               | ✅ 已读  |  [笔记](notes/2509/two-week/007-redrec4cps.md)  |
| 8 | [ARIES: Relation Assessment and Model Recommendation for Deep Time Series Forecasting](https://arxiv.org/abs/2509.06060)                                    | Fei Wang, Yujie Li, <br />2025                                   | ⬜️ 未读  | [笔记](notes/2509/two-week/008-ultra-gcn.md) |
| 9 | [Knowledge-Augmented Relation Learning for Complementary Recommendation with Large Language Models](https://arxiv.org/abs/2509.05564)                       | Chihiro Yamasaki, 2025                                           | ⬜️ 未读  | [笔记](notes/2509/two-week/009-revbrowse.md) |
| 10 | [Calibrated Recommendations with Contextual Bandits](https://arxiv.org/abs/2509.05460)                                                                      | Diego Feijer, 2025                                               |⬜️ 未读   | [笔记](notes/2509/two-week/010-dpg-diff.md)  |
| 11 | [A Survey of Real-World Recommender Systems: Challenges, Constraints, and Industrial Perspectives](https://arxiv.org/abs/2509.06002)                        | Kuan Zou, 2025                                                   | ⬜️ 未读  | [笔记](notes/2509/two-week/011-local-llm.md) |
| 12 | [ELEC: Efficient Large Language Model-Empowered Click-Through Rate Prediction](https://arxiv.org/abs/2509.07594)                                            | Rui Dong, 2025                                                   | ⬜️ 未读  |   [笔记](notes/2509/two-week/012-mars.md)    |

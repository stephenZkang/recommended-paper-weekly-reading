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

| # | 论文标题 (Title)                                                                                                                                                                                            | 作者 & 年份 |   状态    |                  我的笔记                   |
|:-:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---|:-------:|:---------------------------------------:|
| 1 | [Efficient Item ID Generation for Large-Scale LLM-based Recommendation](https://arxiv.org/abs/2509.03746)                                                                                               | Anushya Subbiah,<br /> 2025 |  ✅ 已读   | [笔记](notes/2509/1-week/001-item-id-generation.md) |
| 2 | [Enhancing Interpretability and Effectiveness in Recommendation with Numerical Features via Learning to Contrast the Counterfactual samples](https://arxiv.org/abs/2509.03187)<br/> 论文核心：CCSS框架优化数值特征推荐 | Xiaoxiao Xu,<br /> 2025 |  ✅ 已读   |        [笔记](notes/2509/1-week/002-ccss.md)        |
| 3 | [RecBase: Generative Foundation Model Pretraining for Zero-Shot Recommendation](https://arxiv.org/abs/2509.03131)   <br/>  论文核心：RecBase生成式基础模型（零样本推荐方向）                                                 | Sashuai Zhou, <br />2025 |  ✅ 已读   |    [笔记](notes/2509/1-week/003-recbase.md)     |
| 4 | [A Plug-and-play Model-agnostic Embedding Enhancement Approach for Explainable Recommendation](https://arxiv.org/abs/2509.03130) <br/>  论文核心：RVRec嵌入增强方法（可解释推荐方向）                                       | Yunqi Mi,2025 |  ✅ 已读   |     [笔记](notes/2509/1-week/004-rvrec.md)     |
| 5 | [ RankGraph: Unified Heterogeneous Graph Learning for Cross-Domain Recommendation](https://arxiv.org/abs/2509.02942) <br/> 论文核心：RankGraph跨域推荐图学习框架                                                      | Renzhi Wu, 2025 |  ✅ 已读   |        [笔记](notes/2509/1-week/005-rankgraph.md)         |
| 6 | [Empowering Large Language Model for Sequential Recommendation via Multimodal Embeddings and Semantic IDs](https://arxiv.org/abs/2509.02017) <br/> 论文核心：MME-SID框架（LLM-based序列推荐）                        | Yuhao Wang, 2025 |  ✅ 已读   |      [笔记](notes/2509/1-week/006-mme-sid.md)       |
| 7 | [Cloud-Device Collaborative Agents for Sequential Recommendation](https://arxiv.org/abs/2509.01551) <br/> 论文核心：CDA4Rec云-端协同序列推荐框架                                                                       | Jing Long, 2025 |  ✅ 已读   |      [笔记](notes/2509/1-week/007-cda4rec.md)       |
| 8 | [Ultra Fast Warm Start Solution for Graph Recommendations](https://arxiv.org/abs/2509.01549) <br/>   论文核心：UltraGCN超快速暖启动方案                                                                              | Viacheslav Yusupov, <br />2025 |  ✅ 已读   |      [笔记](notes/2509/1-week/008-ultra-gcn.md)       |
| 9 | [Learning to Shop Like Humans: A Review-driven Retrieval-Augmented Recommendation Framework with LLMs](https://arxiv.org/abs/2509.00698) <br/>   论文核心：RevBrowse评论驱动推荐框架                                 | Yuhao Wang, 2025 |  ✅ 已读   |      [笔记](notes/2509/1-week/009-revbrowse.md)       |
| 10 | [Beyond Negative Transfer: Disentangled Preference-Guided Diffusion for Cross-Domain Sequential Recommendation](https://arxiv.org/abs/2509.00389) <br/> 论文核心：DPG-Diff跨域序列推荐扩散模型                         | Xiaoxin Ye, 2025 |  ✅ 已读   |      [笔记](notes/2509/1-week/010-dpg-diff.md)       |
| 11 | [A Privacy-Preserving Recommender for Filling Web Forms Using a Local Large Language Model](https://arxiv.org/abs/2509.01527) <br/> 论文核心：本地LLM驱动的隐私保护网页表单填充推荐器                                          | Amirreza Nayyeri,<br /> Abbas Rasoolzadegan, 2025 |  ✅ 已读   |      [笔记](notes/2509/1-week/011-local-llm.md)       |
| 12 | [ MARS: Modality-Aligned Retrieval for Sequence Augmented CTR Prediction](https://arxiv.org/abs/2509.01184) <br/> 论文核心：MARS框架（序列增强CTR预测）                                                                | Yutian Xiao, 2025 |  ✅ 已读   |      [笔记](notes/2509/1-week/012-mars.md)       |

### b. 论文周报[0908-0914] (12篇)

| # | 论文标题 (Title)                                                                                                                                                                      | 作者 & 年份                                    |   状态   |                    我的笔记                    |
|:-:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------|:------:|:------------------------------------------:|
| 1 | [CESRec: Constructing Pseudo Interactions for Sequential Recommendation via Conversational Feedback](https://arxiv.org/abs/2509.09342) <br/>论文核心：CESRec会话增强序列推荐框架                 | Yifan Wang,<br /> 2025                     | ✅ 已读  |  [笔记](notes/2509/2-week/001-ces-rec.md)  |
| 2 | [Modality Alignment with Multi-scale Bilateral Attention for Multimodal Recommendation](https://arxiv.org/abs/2509.09114)  <br/>论文核心：MambaRec多模态推荐框架                              | Xiaoxiao Xu,<br /> 2025                    | ✅ 已读  |   [笔记](notes/2509/2-week/002-mamba-rec.md)    |
| 3 | [PerFairX: Is There a Balance Between Fairness and Personality in Large Language Model Recommendations?](https://arxiv.org/abs/2509.08829) <br/>论文核心：PerFairX框架（LLM推荐的人格-公平评估）    | Chandan Kumar Sah <br />2025               | ✅ 已读  |  [笔记](notes/2509/2-week/003-perfairx.md)  |
| 4 | [Beyond Negative Transfer: Disentangled Preference-Guided Diffusion for Cross-Domain Sequential Recommendation](https://arxiv.org/abs/2509.00389) <br/> 论文核心：DPG-Diff（跨域序列推荐扩散模型） | Xiaoxin Ye,2025                            | ✅ 已读  |   [笔记](notes/2509/2-week/004-dpg-diff.md)   |
| 5 | [Datasets for Navigating Sensitive Topics in Recommendation Systems](https://arxiv.org/abs/2509.07269) <br/>论文核心：敏感话题推荐数据集（ML-DDD&AO3）                                            | Amelia Kovacs, 2025                        | ✅ 已读  | [笔记](notes/2509/2-week/005-ml-ddd.md) |
| 6 | [RecMind: LLM-Enhanced Graph Neural Networks for Personalized Consumer Recommendations](https://arxiv.org/abs/2509.06286) <br/>论文核心：RecMind（LLM增强GNN推荐模型）                         | Chang Xue, 2025                            | ✅ 已读  |  [笔记](notes/2509/2-week/006-recmind.md)  |
| 7 | [REMI: A Novel Causal Schema Memory Architecture for Personalized Lifestyle Recommendation Agents](https://arxiv.org/abs/2509.06269) <br/>论文核心：FedRec4CPS（CPS联邦推荐框架）              | Vishal Raman, 2025                         | ✅ 已读  |  [笔记](notes/2509/2-week/007-redrec4cps.md)  |
| 8 | [ARIES: Relation Assessment and Model Recommendation for Deep Time Series Forecasting](https://arxiv.org/abs/2509.06060) <br/>论文核心：ARIES（时间序列预测框架）                                | Fei Wang, Yujie Li, <br />2025             | ✅ 已读  | [笔记](notes/2509/2-week/008-AREIS.md) |
| 9 | [Knowledge-Augmented Relation Learning for Complementary Recommendation with Large Language Models](https://arxiv.org/abs/2509.05564)<br/>论文核心：KARL框架（互补推荐的知识增强关系学习）              | Chihiro Yamasaki, 2025                     | ✅ 已读  | [笔记](notes/2509/2-week/009-KAKL.md) |
| 10 | [Calibrated Recommendations with Contextual Bandits](https://arxiv.org/abs/2509.05460)<br/>论文核心：Spotify的上下文老虎机校准推荐                                                                | Diego Feijer, 2025                         |✅ 已读   | [笔记](notes/2509/2-week/010-Contextual-Bandits.md)  |
| 11 | [A Survey of Real-World Recommender Systems: Challenges, Constraints, and Industrial Perspectives](https://arxiv.org/abs/2509.06002) <br/> 论文核心：工业推荐系统综述（产学差距与实践指南）               | Kuan Zou, 2025                             | ✅ 已读  | [笔记](notes/2509/2-week/011-RecSys-Survey.md) |
| 12 | [ELEC: Efficient Large Language Model-Empowered Click-Through Rate Prediction](https://arxiv.org/abs/2509.07594) <br/> 论文核心：ELEC（高效LLM增强CTR预测框架）                                  | Rui Dong, 2025                             | ✅ 已读   |   [笔记](notes/2509/2-week/012-ELEC.md)    |

### c. 论文周报[0914-0920] (10篇)

| # | 论文标题 (Title)                                                                                                                                                               | 作者 & 年份                                           |  状态   |                       我的笔记                        |
|:-:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------|:-----:|:-------------------------------------------------:|
| 1 | [Enhancing Time Awareness in Generative Recommendation](https://arxiv.org/abs/2509.13957) <br/>  论文核心：GRUT（增强时间感知的生成式推荐模型）                                                 | Sunkyung Lee,<br /> 2025                          | ✅ 已读  |      [笔记](notes/2509/3-week/001-GRUT.md)       |
| 2 | [MIRA: Empowering One-Touch AI Services on Smartphones with MLLM-based Instruction Recommendation](https://arxiv.org/abs/2509.13773)  <br/> 论文核心：MIRA框架（智能手机一键AI服务指令推荐     | Zhipeng Bian,<br /> 2025                          | ✅ 已读  |     [笔记](notes/2509/3-week/002-MIRA.md)      |
| 3 | [Sequential Data Augmentation for Generative Recommendation](https://arxiv.org/abs/2509.13648) <br/>  GenPAS（生成式推荐序列数据增强框架）                                                | Geon Lee <br />2025                               | ✅ 已读  |      [笔记](notes/2509/3-week/003-genPAS.md)      |
| 4 | [Efficient Cold-Start Recommendation via BPE Token-Level Embedding Initialization with LLM](https://arxiv.org/abs/2509.13179) <br/> 论文核心：BPE-LLM冷启动推荐方法                    | Yushang Zhao,2025                                 | ✅ 已读 |      [笔记](notes/2509/3-week/004-BPE-LLM.md)      |
| 5 | [LLM-as-a-Judge: Rapid Evaluation of Legal Document Recommendation for Retrieval-Augmented Generation](https://arxiv.org/abs/2509.12382) <br/>论文核心：LLM-as-a-Judge评估法律RAG系统 | Anu Pradhan, 2025                                 | ✅ 已读 |       [笔记](notes/2509/3-week/005-llm-judge.md)       |
| 6 | [Knowledge Graph Tokenization for Behavior-Aware Generative Next POI Recommendation](https://arxiv.org/abs/2509.12350) <br/>论文核心：KGTB生成式POI推荐方法                            | Ke Sun, 2025                                      | ✅ 已读 |      [笔记](notes/2509/3-week/006-KGTB.md)       |
| 7 | [Decoding in Latent Spaces for Efficient Inference in LLM-based Recommendation](https://arxiv.org/abs/2509.11524) <br/>                                                    | Chengbing Wang,  2025                             | ⬜️ 未读 |     [笔记](notes/2509/3-week/007-redrec4cps.md)     |
| 8 | [What Matters in LLM-Based Feature Extractor for Recommender? A Systematic Analysis of Prompts, Models, and Adaptation](https://arxiv.org/abs/2509.14979) <br/>            | Kainan Shi,  <br />2025                           | ⬜️ 未读 |       [笔记](notes/2509/3-week/008-AREIS.md)        |
| 9 | [Green Recommender Systems: Understanding and Minimizing the Carbon Footprint of AI-Powered Personalization](https://arxiv.org/abs/2509.13001)<br/>                        | Lukas Wegmeth,  2025                              | ⬜️ 未读 |        [笔记](notes/2509/3-week/009-KAKL.md)        |
| 10 | [AEFS: Adaptive Early Feature Selection for Deep Recommender Systems](https://arxiv.org/abs/2509.12076)<br/>                                                               | Fan Hu,  2025                                     | ⬜️ 未读 | [笔记](notes/2509/3-week/010-Contextual-Bandits.md) |
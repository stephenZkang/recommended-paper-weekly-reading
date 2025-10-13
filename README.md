# 每周推荐论文精读 (Recommended-Paper-Weekly-Reading)

本仓库整理了每周的推荐论文精读，旨在为自己记录阅读推荐相关论文。

您可以通过本仓库：
- **跟踪阅读进度**：使用 `状态` 列标记每篇论文的阅读情况。
- **记录和沉淀思考**：为每篇论文创建独立的笔记文件，并链接到主列表。
- **快速概览**：清晰地查看各个子领域的核心论文和贡献。

## 目录
- [202510](#202510)
- [202509](#202509)


## 如何使用
1. **Fork 本仓库**到您自己的 Git账号。
2. **Clone 仓库**到本地。
3. 当您开始阅读一篇论文时，在 `README.md` 中将其**状态**从 `⬜️ 未读` 修改为 `⏳ 在读`。
4. 在 `notes/` 文件夹下，复制 `template.md` 并重命名为 `[编号]-[关键词].md` (例如 `001-dqn.md`)，开始记录您的笔记。
5. 完成阅读和笔记后，将**状态**修改为 `✅ 已读`。
6. `commit` 和 `push` 您的更改。

---

## 202510

## a. 论文周报[1006-1012] (11篇)

| # | 论文标题 (Title)                                                                                                                                                                                                                                   | 作者 & 年份                          |   状态    |                       我的笔记                        |
|:-:|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:---------------------------------|:-------:|:-------------------------------------------------:|
| 1 | [Do We Really Need SFT? Prompt-as-Policy over Knowledge Graphs for Cold-start Next POI Recommendation](https://arxiv.org/abs/2510.08012)<br/> 论文核心：Prompt-as-Policy——知识图谱驱动的冷启动POI推荐框架            | Jinze Wang,2025                  |  ✅ 已读   | [笔记](notes/2510/1-week/001-Prompt-as-Policy.md) |
| 2 | [MMM: Quantum-Chemical Molecular Representation Learning for Combinatorial Drug Recommendation](https://arxiv.org/abs/2510.07910)<br/> 论文核心：CCSS框架优化数值特征推荐                                                                                     | Chongmyung Kwon,2025             |  ⬜️ 未读   |        [笔记](notes/2510/1-week/002-ccss.md)        |
| 3 | [PLUM: Adapting Pre-trained Language Models for Industrial-scale Generative Recommendations](https://arxiv.org/abs/2510.07784)   <br/>  论文核心：RecBase生成式基础模型（零样本推荐方向）                                                                           | Ruining He, 2025                 |  ⬜️ 未读   |      [笔记](notes/2510/1-week/003-recbase.md)       |
| 4 | [Retentive Relevance: Capturing Long-Term User Value in Recommendation Systems](https://arxiv.org/abs/2510.07621) <br/>  论文核心：RVRec嵌入增强方法（可解释推荐方向）                                                                                             | Saeideh Bakhshi,2025             |  ⬜️ 未读   |       [笔记](notes/2510/1-week/004-rvrec.md)        |
| 5 | [LLM-Powered Nuanced Video Attribute Annotation for Enhanced Recommendations](https://arxiv.org/abs/2510.06657) <br/> 论文核心：RankGraph跨域推荐图学习框架                                                                                                  | Boyuan Long, 2025                |  ⬜️ 未读   |     [笔记](notes/2510/1-week/005-rankgraph.md)      |
| 6 | [Reproducibility Study of "XRec: Large Language Models for Explainable Recommendation"](https://arxiv.org/abs/2510.06275) <br/> 论文核心：MME-SID框架（LLM-based序列推荐）                                                                                  | Ranjan Mishra, 2025              |  ⬜️ 未读   |      [笔记](notes/2510/1-week/006-mme-sid.md)       |
| 7 | [Constraint-Aware Route Recommendation from Natural Language via Hierarchical LLM](https://arxiv.org/abs/2510.06078) <br/> 论文核心：CDA4Rec云-端协同序列推荐框架                                                                                             | Tao Zhe, 2025                    |  ⬜️ 未读   |      [笔记](notes/2510/1-week/007-cda4rec.md)       |
| 8 | [AgentDR: Dynamic Recommendation with Implicit Item-Item Relations via LLM-based Agents](https://arxiv.org/abs/2510.05598) <br/>   论文核心：UltraGCN超快速暖启动方案                                                                                       | Mingdai Yang, 2025               |  ⬜️ 未读   |     [笔记](notes/2510/1-week/008-ultra-gcn.md)      |
| 9 | [Catalog-Native LLM: Speaking Item-ID Dialect with Less Entanglement for Recommendation](https://arxiv.org/abs/2510.05125) <br/>   论文核心：RevBrowse评论驱动推荐框架                                                                                      | Reza Shirkavand, 2025            |  ⬜️ 未读   |     [笔记](notes/2510/1-week/009-revbrowse.md)      |
| 10 | [Safely Exploring Novel Actions in Recommender Systems via Deployment-Efficient Policy Learning](https://arxiv.org/abs/2510.07635) <br/> 论文核心：DPG-Diff跨域序列推荐扩散模型                                                                               | Haruka Kiyohara, 2025            |  ⬜️ 未读   |      [笔记](notes/2510/1-week/010-dpg-diff.md)      |
| 11 | [Limitations of Current Evaluation Practices for Conversational Recommender Systems](https://arxiv.org/abs/2510.05624) <br/> 论文核心：本地LLM驱动的隐私保护网页表单填充推荐器                                                                                        | Nolwenn Bernard, 2025            |  ⬜️ 未读   |     [笔记](notes/2510/1-week/011-local-llm.md)      |


## 202509

## a. 论文周报[0922-0928] (12篇)

| # | 论文标题 (Title)                                                                                                                                                                                | 作者 & 年份                      |  状态   |                       我的笔记                        |
|:-:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------|:-----:|:-------------------------------------------------:|
| 1 | [Interactive Recommendation Agent with Active User Commands](https://arxiv.org/abs/2509.21317) <br/>论文核心：RecBot——支持主动用户命令的交互式推荐代理                                                          | Jiakai Tang,<br /> 2025      | ✅ 已读  |       [笔记](notes/2509/4-week/001-RecBot.md)       |
| 2 | [IntSR: An Integrated Generative Framework for Search and Recommendation](https://arxiv.org/abs/2509.21179)  <br/>论文核心：IntSR——搜索与推荐的集成生成框架                                                   | Huimin Yan,<br /> 2025       | ✅ 已读  |       [笔记](notes/2509/4-week/002-IntSR.md)        |
| 3 | [RecIS: Sparse to Dense, A Unified Training Framework for Recommendation Models](https://arxiv.org/abs/2509.20883) <br/>论文核心：RecIS——PyTorch稀疏-稠密统一推荐训练框架                                     | Hua Zong,  <br />2025        | ✅ 已读  |       [笔记](notes/2509/4-week/003-RecIS.md)        |
| 4 | [USB-Rec: An Effective Framework for Improving Conversational Recommendation Capability of Large Language Model](https://arxiv.org/abs/2509.20381) <br/> 论文核心：USB-Rec——LLM对话推荐的训练-推理一体化框架   | Jianyu Wen,2025              | ✅ 已读  |      [笔记](notes/2509/4-week/004-USB-Rec.md)       |
| 5 | [Multimodal Representation-disentangled Information Bottleneck for Multimodal Recommendation](https://arxiv.org/abs/2509.20225) <br/>论文核心：MRdIB——多模态推荐的解纠缠信息瓶颈框架                           | Hu i Wang, 2025              | ✅ 已读  |       [笔记](notes/2509/4-week/005-MRdIB.md)        |
| 6 | [Multimodal-enhanced Federated Recommendation: A Group-wise Fusion Approach](https://arxiv.org/abs/2509.19955) <br/>论文核心：GFMFR——多模态增强的联邦推荐框架                                                 | Chunxu Zhang, 2025           | ✅ 已读  |       [笔记](notes/2509/4-week/006-GFMFR.md)        |
| 7 | [MusiCRS: Benchmarking Audio-Centric Conversational Recommendation](https://arxiv.org/abs/2509.19469) <br/>论文核心：MusiCRS——音频中心对话推荐基准                                                           | Rohan Surana, 2025           | ✅ 已读  |      [笔记](notes/2509/4-week/007-MusiCRS.md)       |
| 8 | [Single-Branch Network Architectures to Close the Modality Gap in Multimodal Recommendation](https://arxiv.org/abs/2509.18807) <br/>论文核心：SiBraR——单分支多模态推荐框架（缩小模态差距）                      | Christian Ganhör, <br />2025 | ✅ 已读  |       [笔记](notes/2509/4-week/008-SiBraR.md)       |
| 9 | [Rejuvenating Cross-Entropy Loss in Knowledge Distillation for Recommender Systems](https://arxiv.org/abs/2509.20989)<br/>论文核心：RCE-KD——振兴推荐系统KD中的CE损失                                         | Zhangchi Zhu, 2025           | ✅ 已读 |       [笔记](notes/2509/4-week/009-RCE-KD.md)       |
| 10 | [Robust Denoising Neural Reranker for Recommender Systems](https://arxiv.org/abs/2509.18736)<br/>论文核心：DNR——去噪神经重排序器（多阶段推荐优化）                                                             | Wenyu Mao,  2025             | ✅ 已读 | [笔记](notes/2509/4-week/010-DNR.md) |
| 11 | [Shilling Recommender Systems by Generating Side-feature-aware Fake User Profiles](https://arxiv.org/abs/2509.17918) <br/> 论文核心：D3Rec——动态漂移感知的多模态推荐框架                                      | Yuanrong Wang,  2025         | ✅ 已读 |   [笔记](notes/2509/4-week/011-D3Rec.md)    |
| 12 | [Adaptive User Interest Modeling via Conditioned Denoising Diffusion For Click-Through Rate Prediction](https://arxiv.org/abs/2509.19876) <br/> 论文核心：CDP——用于CTR预测的条件扩散净化用户兴趣建模框架        | Qihang Zhao, 2025            | ✅ 已读 |        [笔记](notes/2509/4-week/012-CDP.md)        |

### b. 论文周报[0914-0920] (10篇)

| # | 论文标题 (Title)                                                                                                                                                                                     | 作者 & 年份                  |  状态   |                     我的笔记                     |
|:-:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------|:-----:|:--------------------------------------------:|
| 1 | [Enhancing Time Awareness in Generative Recommendation](https://arxiv.org/abs/2509.13957) <br/>  论文核心：GRUT（增强时间感知的生成式推荐模型）                                                                     | Sunkyung Lee,<br /> 2025 | ✅ 已读  |   [笔记](notes/2509/3-week/001-GRUT.md)        |
| 2 | [MIRA: Empowering One-Touch AI Services on Smartphones with MLLM-based Instruction Recommendation](https://arxiv.org/abs/2509.13773)  <br/> 论文核心：MIRA框架（智能手机一键AI服务指令推荐                          | Zhipeng Bian,<br /> 2025 | ✅ 已读  |     [笔记](notes/2509/3-week/002-MIRA.md)      |
| 3 | [Sequential Data Augmentation for Generative Recommendation](https://arxiv.org/abs/2509.13648) <br/>  GenPAS（生成式推荐序列数据增强框架）                                                                        | Geon Lee <br />2025      | ✅ 已读  |    [笔记](notes/2509/3-week/003-genPAS.md)     |
| 4 | [Efficient Cold-Start Recommendation via BPE Token-Level Embedding Initialization with LLM](https://arxiv.org/abs/2509.13179) <br/> 论文核心：BPE-LLM冷启动推荐方法                                             | Yushang Zhao,2025        | ✅ 已读  |    [笔记](notes/2509/3-week/004-BPE-LLM.md)    |
| 5 | [LLM-as-a-Judge: Rapid Evaluation of Legal Document Recommendation for Retrieval-Augmented Generation](https://arxiv.org/abs/2509.12382) <br/>论文核心：LLM-as-a-Judge评估法律RAG系统                           | Anu Pradhan, 2025        | ✅ 已读  |   [笔记](notes/2509/3-week/005-llm-judge.md)   |
| 6 | [Knowledge Graph Tokenization for Behavior-Aware Generative Next POI Recommendation](https://arxiv.org/abs/2509.12350) <br/>论文核心：KGTB生成式POI推荐方法                                                     | Ke Sun, 2025             | ✅ 已读  |     [笔记](notes/2509/3-week/006-KGTB.md)      |
| 7 | [Decoding in Latent Spaces for Efficient Inference in LLM-based Recommendation](https://arxiv.org/abs/2509.11524) <br/> 论文核心：L2D——LLM推荐的高效潜空间解码方法                                                | Chengbing Wang,  2025    | ✅ 已读  |    [笔记](notes/2509/3-week/007-L2D-LLM.md)    |
| 8 | [What Matters in LLM-Based Feature Extractor for Recommender? A Systematic Analysis of Prompts, Models, and Adaptation](https://arxiv.org/abs/2509.14979) <br/> 论文核心：RecXplore——LLM特征提取器的模块化分析框架 | Kainan Shi,  <br />2025  | ✅ 已读  | [笔记](notes/2509/3-week/008-RecXplore-LLM.md) |
| 9 | [Green Recommender Systems: Understanding and Minimizing the Carbon Footprint of AI-Powered Personalization](https://arxiv.org/abs/2509.13001)<br/> 论文核心：绿色推荐系统——评估与降低碳足迹                       | Lukas Wegmeth,  2025     |   ✅ 已读    |   [笔记](notes/2509/3-week/009-GREEN-Rec.md)   |
| 10 | [AEFS: Adaptive Early Feature Selection for Deep Recommender Systems](https://arxiv.org/abs/2509.12076)<br/> 论文核心：AEFS——深度推荐系统的自适应早期特征选择方法                                                   | Fan Hu,  2025            | ✅ 已读 |     [笔记](notes/2509/3-week/010-AEFS.md)      |


### c. 论文周报[0908-0914] (12篇)

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



### d. 论文周报[0901-0907] (12篇)

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

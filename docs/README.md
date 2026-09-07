<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-07
- 运行时间：2026-09-07 22:43:11 UTC
- 运行状态：成功
- 本次总论文数：7
- 精读区：5
- 速读区：2

### 今日简报（AI）
今日聚焦7篇论文，精读5篇、速读2篇，核心围绕在线策略蒸馏与强化学习推理。

最值得关注：两篇满分工作均指出“序贯蒸馏优于联合训练”，并系统分析了数据效率与选择策略，适合RLVR场景参考。

建议优先精读这两篇满分论文，理解其数据选择机制后，再结合速读中的贝叶斯视角与视频生成对齐，拓展应用思路。
- 详情：[/202609/07/README](/202609/07/README)

### 精读区论文标签
1. [Sequential Beats Joint: On the Interplay between On-Policy Distillation and RLVR](/202609/07/2609.04108v2-sequential-beats-joint-on-the-interplay-between-on-policy-distillation-and-rlvr)  
   标签：评分：10.0/10、query:policy-dist
   evidence：直接聚焦后训练推理大模型中的在线策略蒸馏，并探讨其与 RLVR 的最优结合方式
2. [What Matters in On-Policy Distillation? A Perspective on Data Efficiency and Data Selection](/202609/07/2609.05198v1-what-matters-in-on-policy-distillation-a-perspective-on-data-efficiency-and-data-selection)  
   标签：评分：10.0/10、query:policy-dist
   evidence：直接研究大语言模型后训练中的on-policy蒸馏机制
3. [RISE: Recursive Improvement via Self-Extrapolating Policy Distillation](/202609/07/2609.05295v1-rise-recursive-improvement-via-self-extrapolating-policy-distillation)  
   标签：评分：10.0/10、query:policy-dist
   evidence：提出RISE自外推策略蒸馏方法，直接从自身RLVR训练轨迹构造合成教师，正是on-policy后训练蒸馏的核心主题
4. [Extremely Sparse Supervision Incentivizes Reasoning Ability](/202609/07/2609.04565v1-extremely-sparse-supervision-incentivizes-reasoning-ability)  
   标签：评分：9.0/10、query:policy-dist
   evidence：研究大模型后训练中的在线策略蒸馏，发现极稀疏监督即可媲美全 token 训练
5. [Persistent Teacher Anchoring for Tool-Using Agents](/202609/07/2609.04773v1-persistent-teacher-anchoring-for-tool-using-agents)  
   标签：评分：9.0/10、query:policy-dist
   evidence：直接涉及工具智能体后训练中的同策略知识蒸馏（OPKD）。

### 速读区论文标签
1. [Unifying ICL, SFT, KL-Regularized RL Through a Bayesian Lens](/202609/07/2609.05111v1-unifying-icl-sft-kl-regularized-rl-through-a-bayesian-lens)  
   标签：评分：7.0/10、query:policy-dist
   evidence：用贝叶斯后验模板统一on-policy蒸馏、KL正则化RLHF/RLVR等范式，是RLHF与蒸馏结合的重要概念性工作
2. [Joint Alignment and Distillation for Video Generation via Sample-Guided Distribution Matching](/202609/07/2609.04283v1-joint-alignment-and-distillation-for-video-generation-via-sample-guided-distribution-matching)  
   标签：评分：6.0/10、query:policy-dist
   evidence：将基于强化学习的偏好对齐与蒸馏统一到单阶段优化，用于生成模型


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

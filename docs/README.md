<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-09
- 运行时间：2026-09-09 21:53:04 UTC
- 运行状态：成功
- 本次总论文数：10
- 精读区：6
- 速读区：4

### 今日简报（AI）
- 今日共生成 10 篇推荐（精读 6 篇，速读 4 篇）
- 精读：《Eliciting Weak-to-Strong Generalization with On-Policy Reverse Distillation》（10.0/10）, 《Flow3D-OPD: Multi-Teacher On-Policy Distillation for 3D Geometry Generation with Flow-Matching Diffusion Transformer》（9.0/10）
- 速读：《CA-OPD: Confidence-Aware On-Policy Distillation for Structured Visual Prediction》（8.0/10）, 《Aha-Flow Distillation: Flow Markers Matter in LLM Reasoning》（8.0/10）, 《Towards Bridging the Gap Between Offline and Iterative Alignment via Preference Distillation》（7.0/10）
- 这些结果覆盖了当下较热的方向，建议先看精读区论文的关键问题与方法。
- 详情：[/202609/09/README](/202609/09/README)

### 精读区论文标签
1. [Eliciting Weak-to-Strong Generalization with On-Policy Reverse Distillation](/202609/09/2609.08798v1-eliciting-weak-to-strong-generalization-with-on-policy-reverse-distillation)  
   标签：评分：10.0/10、query:policy-dist
   evidence：提出同策略反向蒸馏，在student rollouts上利用教师策略偏移调整验证器支持的策略梯度，用于后训练泛化
2. [Flow3D-OPD: Multi-Teacher On-Policy Distillation for 3D Geometry Generation with Flow-Matching Diffusion Transformer](/202609/09/2609.07137v1-flow3d-opd-multi-teacher-on-policy-distillation-for-3d-geometry-generation-with-flow-matching-diffusion-transformer)  
   标签：评分：9.0/10、query:policy-dist
   evidence：提出Flow3D-OPD两阶段后训练框架，将多教师在线策略蒸馏引入后训练，直接命中在线策略蒸馏做后训练的需求。
3. [Distillation as Probability Transport: Routed On-Policy Distillation](/202609/09/2609.08337v1-distillation-as-probability-transport-routed-on-policy-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：将on-policy蒸馏重解释为教师引导的概率输运
4. [TV-Regulated OPD: Direction Matters in On-Policy Distillation](/202609/09/2609.08341v1-tv-regulated-opd-direction-matters-in-on-policy-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：针对LLM后训练OPD，研究并稳定token级优势方向
5. [Instella-MoE Technical Report](/202609/09/2609.00791v1-instella-moe-technical-report)  
   标签：评分：8.0/10、query:policy-dist
   evidence：在大语言模型后训练管线中采用多教师同策略蒸馏强化学习
6. [CA-OPD: Confidence-Aware On-Policy Distillation for Structured Visual Prediction](/202609/09/2609.02401v1-ca-opd-confidence-aware-on-policy-distillation-for-structured-visual-prediction)  
   标签：评分：8.0/10、query:policy-dist
   evidence：提出置信度感知的同策略蒸馏，在自回归视觉预测中基于教师置信度进行token级监督

### 速读区论文标签
1. [CA-OPD: Confidence-Aware On-Policy Distillation for Structured Visual Prediction](/202609/09/2609.02401v2-ca-opd-confidence-aware-on-policy-distillation-for-structured-visual-prediction)  
   标签：评分：8.0/10、query:policy-dist
   evidence：面向自回归视觉语言模型的置信度感知在策略蒸馏方法
2. [Aha-Flow Distillation: Flow Markers Matter in LLM Reasoning](/202609/09/2609.07036v1-aha-flow-distillation-flow-markers-matter-in-llm-reasoning)  
   标签：评分：8.0/10、query:policy-dist
   evidence：将on-policy自蒸馏用于大模型推理后训练，引入Flow标记与Aha标记辅助监督
3. [Towards Bridging the Gap Between Offline and Iterative Alignment via Preference Distillation](/202609/09/2609.06893v1-towards-bridging-the-gap-between-offline-and-iterative-alignment-via-preference-distillation)  
   标签：评分：7.0/10、query:policy-dist
   evidence：用偏好蒸馏把迭代式RLHF/DPO优势转入离线对齐
4. [VERPO: Verified Evidence Regularized Policy Optimization](/202609/09/2609.06100v1-verpo-verified-evidence-regularized-policy-optimization)  
   标签：评分：6.0/10、query:policy-dist
   evidence：在语言模型后训练中融合可验证奖励优化与证据型教师的token级修正监督，属于RLHF/RLVR与蒸馏式策略正则化


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

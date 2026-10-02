<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-10-02
- 运行时间：2026-10-02 23:04:26 UTC
- 运行状态：成功
- 本次总论文数：19
- 精读区：16
- 速读区：3

### 今日简报（AI）
2026-10-02 日报精选19篇（精读16篇、速读3篇），聚焦策略蒸馏与LLM训练动态。最值得看两篇满分工作：Unbiased Top-k Estimation for On-Policy Distillation 解决on-policy蒸馏中的有偏估计问题，Interpolated Policy Distillation 则给出off-policy与on-policy之间可调控的连续过渡方案。普通读者可先读这两篇理解蒸馏偏差与策略插值的核心思路，再顺带浏览速读里的 REVO 了解如何用方差引导复用提升rollout效率。
- 详情：[/202610/02/README](/202610/02/README)

### 精读区论文标签
1. [Unbiased Top-$k$ Estimation for On-Policy Distillation](/202610/02/2609.34447v2-unbiased-top-k-estimation-for-on-policy-distillation)  
   标签：评分：10.0/10、query:policy-dist
   evidence：同策略蒸馏的无偏Top-k梯度估计
2. [Interpolated Policy Distillation: A Controllable Continuum Between Off-Policy and On-Policy Distillation](/202610/02/2609.37170v1-interpolated-policy-distillation-a-controllable-continuum-between-off-policy-and-on-policy-distillation)  
   标签：评分：10.0/10、query:policy-dist
   evidence：连接离策略与同策略蒸馏的插值策略蒸馏
3. [Beyond Prompt Count: How Data Shapes Transfer in On-Policy Distillation](/202610/02/2609.37377v1-beyond-prompt-count-how-data-shapes-transfer-in-on-policy-distillation)  
   标签：评分：10.0/10、query:policy-dist
   evidence：研究在线策略蒸馏中的提示选择
4. [Dr. OPD: Learning What to Follow for Optimal On-Policy Distillation of Large Language Models](/202610/02/2609.38025v1-dr-opd-learning-what-to-follow-for-optimal-on-policy-distillation-of-large-language-models)  
   标签：评分：10.0/10、query:policy-dist
   evidence：面向大模型后训练的同策略蒸馏，加权教师监督
5. [From Gradients to Capabilities: Understanding Multi-Teacher On-Policy Distillation](/202610/02/2610.02179v1-from-gradients-to-capabilities-understanding-multi-teacher-on-policy-distillation)  
   标签：评分：10.0/10、query:policy-dist
   evidence：理解多教师在线策略蒸馏信号
6. [Teach Yourself Where to Look: On-Policy Attention Self-Distillation for Reasoning](/202610/02/2609.33200v2-teach-yourself-where-to-look-on-policy-attention-self-distillation-for-reasoning)  
   标签：评分：9.0/10、query:policy-dist
   evidence：面向推理模型的在线策略自蒸馏
7. [Interactive-Policy Distillation with Bidirectional Propose-and-Verify](/202610/02/2609.36546v1-interactive-policy-distillation-with-bidirectional-propose-and-verify)  
   标签：评分：9.0/10、query:policy-dist
   evidence：带自适应教师干预的在线策略蒸馏以提升监督可靠性
8. [Act First, Reason Later: Accelerating On-Policy Distillation for Multi-Turn Agents via Reference-Conditioned Inverse Dynamics](/202610/02/2609.36608v1-act-first-reason-later-accelerating-on-policy-distillation-for-multi-turn-agents-via-reference-conditioned-inverse-dynamics)  
   标签：评分：9.0/10、query:policy-dist
   evidence：加速多轮智能体在线策略蒸馏
9. [SIPO: Unifying Reinforcement Learning with On-Policy Self-Distillation](/202610/02/2609.36742v1-sipo-unifying-reinforcement-learning-with-on-policy-self-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：以在线策略自蒸馏统一强化学习提供密集信用
10. [Learning from Think-Mode Advantage via On-Policy Distillation](/202610/02/2609.37044v2-learning-from-think-mode-advantage-via-on-policy-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：面向LLM后训练的在线策略蒸馏，学习思考模式优势
11. [Train Ahead, Distill Back: Bootstrapping On-Policy Self-Distillation for Large Language Models](/202610/02/2609.37132v1-train-ahead-distill-back-bootstrapping-on-policy-self-distillation-for-large-language-models)  
   标签：评分：9.0/10、query:policy-dist
   evidence：将优化进展回收为更强自我教师的自举在线自蒸馏
12. [Overcoming Scaling Limits in On-Policy Self-Distillation for LLM Reasoning](/202610/02/2609.37915v1-overcoming-scaling-limits-in-on-policy-self-distillation-for-llm-reasoning)  
   标签：评分：9.0/10、query:policy-dist
   evidence：克服推理中在线策略自蒸馏的缩放限制
13. [On the Off-Policy Teacher in On-Policy Distillation](/202610/02/2609.38360v1-on-the-off-policy-teacher-in-on-policy-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：在线策略蒸馏后训练范式；教师off-policy问题
14. [Understanding Off- vs On-Policy Distillation: A Tale of Distinct Training Objectives](/202610/02/2609.38666v1-understanding-off--vs-on-policy-distillation-a-tale-of-distinct-training-objectives)  
   标签：评分：9.0/10、query:policy-dist
   evidence：理解离线与在线策略蒸馏及其不同训练目标
15. [Diagnosing On-Policy Self-Distillation for Reasoning Language Models](/202610/02/2609.39118v1-diagnosing-on-policy-self-distillation-for-reasoning-language-models)  
   标签：评分：9.0/10、query:policy-dist
   evidence：诊断面向推理语言模型的在线策略自蒸馏
16. [ReSAIL: Mitigating Collapse in Iterative Agent Self-Distillation](/202610/02/2609.39306v1-resail-mitigating-collapse-in-iterative-agent-self-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：智能体迭代自蒸馏与蒸馏监督

### 速读区论文标签
1. [REVO: Rollout-Efficient Off-Policy Distillation via Variance-Guided Reuse](/202610/02/2609.37500v1-revo-rollout-efficient-off-policy-distillation-via-variance-guided-reuse)  
   标签：评分：8.0/10、query:policy-dist
   evidence：基于方差引导复用的高轨迹效率离线蒸馏
2. [Beyond Compression: Diagnosing How Post-Training Changes Mathematical Reasoning](/202610/02/2609.37066v1-beyond-compression-diagnosing-how-post-training-changes-mathematical-reasoning)  
   标签：评分：7.0/10、query:policy-dist
   evidence：诊断包含离线加在线蒸馏的数学推理后训练路径
3. [Understanding LLM Parameter Update Sparsity through the Lens of Fisher](/202610/02/2609.36262v1-understanding-llm-parameter-update-sparsity-through-the-lens-of-fisher)  
   标签：评分：6.0/10、query:policy-dist
   evidence：解释RL与在线策略蒸馏中的参数更新稀疏性


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

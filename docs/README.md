<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-11 ~ 2026-06-09
- 运行时间：2026-06-09 07:09:22 UTC
- 运行状态：成功
- 本次总论文数：41
- 精读区：0
- 速读区：41

### 今日简报（AI）
今日梳理41篇速读论文，聚焦大语言模型在线策略自蒸馏（On-Policy Self-Distillation）的三篇高分研究，分别揭示其机制、陷阱与状态分布视角下的后训练新理解。

最值得关注的方向：在线策略蒸馏显著优于传统离线方法，其关键不在于token级别的模仿，而在于对齐模型的状态分布，这为SFT与RL的统一解释提供了新框架。

下一步建议普通读者可直接从10分综述《A Brief Overview: On-Policy Self-Distillation In Large Language Models》入手，再结合《Post-Training is About States, Not Tokens》深化理论认知。
- 详情：[/20260511-20260609/README](/20260511-20260609/README)

### 精读区论文标签
- 本次无精读推荐。

### 速读区论文标签
1. [A Brief Overview: On-Policy Self-Distillation In Large Language Models](/20260511-20260609/2605.18141v2-a-brief-overview-on-policy-self-distillation-in-large-language-models)  
   标签：评分：10.0/10、query:policy-dist
   evidence：直接提出面向LLM的在线策略自蒸馏
2. [Post-Training is About States, Not Tokens: A State Distribution View of SFT, RL, and On-Policy Distillation](/20260511-20260609/2605.22731v1-post-training-is-about-states-not-tokens-a-state-distribution-view-of-sft-rl-and-on-policy-distillation)  
   标签：评分：10.0/10、query:policy-dist
   evidence：直接研究基于状态分布视角的LLM后训练中的在线策略蒸馏
3. [The Many Faces of On-Policy Distillation: Pitfalls, Mechanisms, and Fixes](/20260511-20260609/2605.11182v1-the-many-faces-of-on-policy-distillation-pitfalls-mechanisms-and-fixes)  
   标签：评分：9.0/10、query:policy-dist
   evidence：全面实证研究LLM后训练中在线策略蒸馏的机制与缺陷
4. [OGLS-SD: On-Policy Self-Distillation with Outcome-Guided Logit Steering for LLM Reasoning](/20260511-20260609/2605.12400v1-ogls-sd-on-policy-self-distillation-with-outcome-guided-logit-steering-for-llm-reasoning)  
   标签：评分：9.0/10、query:policy-dist
   evidence：基于结果引导logit操控的在线自蒸馏用于LLM推理
5. [Beyond GRPO and On-Policy Distillation: An Empirical Sparse-to-Dense Reward Principle for Language-Model Post-Training](/20260511-20260609/2605.12483v3-beyond-grpo-and-on-policy-distillation-an-empirical-sparse-to-dense-reward-principle-for-language-model-post-training)  
   标签：评分：9.0/10、query:policy-dist
   evidence：提出包含在线策略蒸馏的多阶段后训练工作流
6. [Teacher-Guided Policy Optimization for LLM Distillation](/20260511-20260609/2605.13230v1-teacher-guided-policy-optimization-for-llm-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：提出基于on-policy的TGPO算法用于LLM蒸馏
7. [Learning from Language Feedback via Variational Policy Distillation](/20260511-20260609/2605.15113v1-learning-from-language-feedback-via-variational-policy-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：变分策略蒸馏用于从语言反馈中进行在线学习，直接改进在线策略自蒸馏
8. [Learning from Language Feedback via Variational Policy Distillation](/20260511-20260609/2605.15113v2-learning-from-language-feedback-via-variational-policy-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：变分策略蒸馏以从语言反馈中学习，用于RLVR
9. [Self-Supervised On-Policy Distillation for Reasoning Language Models](/20260511-20260609/2605.17497v1-self-supervised-on-policy-distillation-for-reasoning-language-models)  
   标签：评分：9.0/10、query:policy-dist
   evidence：提出自监督在线策略蒸馏SSOPD，用于GRPO风格RLVR训练的推理语言模型
10. [EDGE-OPD: Internalizing Privileged Context with Evidence Guided On-Policy Distillation](/20260511-20260609/2605.23493v1-edge-opd-internalizing-privileged-context-with-evidence-guided-on-policy-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：提出证据引导的在线策略蒸馏以内化特权上下文
11. [Counteraction-Aware Multi-Teacher On-Policy Distillation for General Capability Recovery with Domain Preservation](/20260511-20260609/2605.27115v1-counteraction-aware-multi-teacher-on-policy-distillation-for-general-capability-recovery-with-domain-preservation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：多教师在线策略蒸馏用于恢复通用能力同时保持领域专长
12. [ROSD: Reflective On-Policy Self-Distillation for Language Model Reasoning across Domains](/20260511-20260609/2605.28014v1-rosd-reflective-on-policy-self-distillation-for-language-model-reasoning-across-domains)  
   标签：评分：9.0/10、query:policy-dist
   evidence：反思式在线自蒸馏用于跨领域LLM推理
13. [OISD: On-Policy Internal Self-Distillation of Language Models](/20260511-20260609/2605.29089v1-oisd-on-policy-internal-self-distillation-of-language-models)  
   标签：评分：9.0/10、query:policy-dist
   evidence：提出OISD框架，用于LLM的RL后训练中的在线策略内部自蒸馏
14. [A Predictive Law for On-Policy Self-Distillation From World Feedback](/20260511-20260609/2605.30070v1-a-predictive-law-for-on-policy-self-distillation-from-world-feedback)  
   标签：评分：9.0/10、query:policy-dist
   evidence：发现OPSD中初始差距与最终改进的线性相关性
15. [Bridging Reasoning Trajectories in On-Policy Distillation via Near-Future Guidance](/20260511-20260609/2606.00305v1-bridging-reasoning-trajectories-in-on-policy-distillation-via-near-future-guidance)  
   标签：评分：9.0/10、query:policy-dist
   evidence：改进了标准在线策略蒸馏，解决轨迹级学习局限
16. [OPD+: Rethinking the Advantage Design for On-Policy Distillation](/20260511-20260609/2606.01039v1-opd-rethinking-the-advantage-design-for-on-policy-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：重新思考LLM在线蒸馏中的优势设计
17. [Trust Region On-Policy Distillation](/20260511-20260609/2606.01249v1-trust-region-on-policy-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：用于稳定LLM后训练的信任区域在线蒸馏
18. [Trust Region On-Policy Distillation](/20260511-20260609/2606.01249v2-trust-region-on-policy-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：提出信任域在线策略蒸馏以稳定后训练
19. [SafeSteer: Localized On-Policy Distillation for Efficient Safety Alignment](/20260511-20260609/2606.02530v1-safesteer-localized-on-policy-distillation-for-efficient-safety-alignment)  
   标签：评分：9.0/10、query:policy-dist
   evidence：局部在线蒸馏用于LLM安全对齐
20. [Filter, Then Reweight: Rethinking Optimization Granularity in On-Policy Distillation](/20260511-20260609/2606.02684v1-filter-then-reweight-rethinking-optimization-granularity-in-on-policy-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：提出FiRe-OPD用于大语言模型后训练中的在线策略蒸馏
21. [Filter, Then Reweight: Rethinking Optimization Granularity in On-Policy Distillation](/20260511-20260609/2606.02684v2-filter-then-reweight-rethinking-optimization-granularity-in-on-policy-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：在LLM在线蒸馏中重新思考优化粒度
22. [Constitutional On-Policy Safe Distillation](/20260511-20260609/2606.03089v1-constitutional-on-policy-safe-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：宪法式在线策略安全蒸馏用于大语言模型对齐
23. [Self-Distilled Policy Gradient](/20260511-20260609/2606.04036v1-self-distilled-policy-gradient)  
   标签：评分：9.0/10、query:policy-dist
   evidence：针对稀疏奖励强化学习的在线自蒸馏
24. [OPRD: On-Policy Representation Distillation](/20260511-20260609/2606.06021v1-oprd-on-policy-representation-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：将OPD扩展到隐藏状态空间以获取更丰富的结构信息
25. [On the Geometry of On-Policy Distillation](/20260511-20260609/2606.07082v1-on-the-geometry-of-on-policy-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：分析在线策略蒸馏在参数空间中的训练动力学，与SFT和RLVR对比
26. [Learning to Foresee: Unveiling the Unlocking Efficiency of On-Policy Distillation](/20260511-20260609/2605.11739v1-learning-to-foresee-unveiling-the-unlocking-efficiency-of-on-policy-distillation)  
   标签：评分：8.0/10、query:policy-dist
   evidence：探究在线策略蒸馏在LLM后训练中的效率机制
27. [Learning to Foresee: Unveiling the Unlocking Efficiency of On-Policy Distillation](/20260511-20260609/2605.11739v2-learning-to-foresee-unveiling-the-unlocking-efficiency-of-on-policy-distillation)  
   标签：评分：8.0/10、query:policy-dist
   evidence：分析在线策略蒸馏在大语言模型后训练中的效率机制
28. [Combining On-Policy Optimization and Distillation for Long-Context Reasoning in Large Language Models](/20260511-20260609/2605.12227v1-combining-on-policy-optimization-and-distillation-for-long-context-reasoning-in-large-language-models)  
   标签：评分：8.0/10、query:policy-dist
   evidence：结合在线策略优化与蒸馏用于长上下文大语言模型推理
29. [Beyond GRPO and On-Policy Distillation: An Empirical Sparse-to-Dense Reward Principle for Language-Model Post-Training](/20260511-20260609/2605.12483v4-beyond-grpo-and-on-policy-distillation-an-empirical-sparse-to-dense-reward-principle-for-language-model-post-training)  
   标签：评分：8.0/10、query:policy-dist
   evidence：稀疏到密集奖励原则用于大语言模型后训练中的在线策略蒸馏
30. [Multi-Rollout On-Policy Distillation via Peer Successes and Failures](/20260511-20260609/2605.12652v1-multi-rollout-on-policy-distillation-via-peer-successes-and-failures)  
   标签：评分：8.0/10、query:policy-dist
   evidence：利用同组成功和失败的多rollout在线策略蒸馏方法
31. [Respecting Self-Uncertainty in On-Policy Self-Distillation for Efficient LLM Reasoning](/20260511-20260609/2605.13255v1-respecting-self-uncertainty-in-on-policy-self-distillation-for-efficient-llm-reasoning)  
   标签：评分：8.0/10、query:policy-dist
   evidence：熵引导的强化自蒸馏用于在线策略自蒸馏
32. [Reducing the Safety Tax in LLM Safety Alignment with On-Policy Self-Distillation](/20260511-20260609/2605.15239v1-reducing-the-safety-tax-in-llm-safety-alignment-with-on-policy-self-distillation)  
   标签：评分：8.0/10、query:policy-dist
   evidence：安全对齐的在线策略自蒸馏，直接相关通过策略蒸馏对齐LLM
33. [Decoupling KL and Trajectories: A Unified Perspective for SFT, DAgger, Offline RL, and OPD in LLM Distillation](/20260511-20260609/2605.16826v1-decoupling-kl-and-trajectories-a-unified-perspective-for-sft-dagger-offline-rl-and-opd-in-llm-distillation)  
   标签：评分：8.0/10、query:policy-dist
   evidence：统一视角解耦KL与轨迹，涵盖SFT、DAgger、离线RL和OPD
34. [$\boldsymbol{f}$-OPD: Stabilizing Long-Horizon On-Policy Distillation with Freshness-Aware Control](/20260511-20260609/2605.17862v1-boldsymbolf-opd-stabilizing-long-horizon-on-policy-distillation-with-freshness-aware-control)  
   标签：评分：8.0/10、query:policy-dist
   evidence：新鲜度感知控制稳定长视界在线策略蒸馏
35. [A Brief Overview: On-Policy Self-Distillation In Large Language Models](/20260511-20260609/2605.18141v1-a-brief-overview-on-policy-self-distillation-in-large-language-models)  
   标签：评分：8.0/10、query:policy-dist
   evidence：综述在线策略自蒸馏在LLM中的应用，符合综合需求
36. [Restoring the Sweet Spot: Pass-Rate Weighted Self-Distillation for LLM Reasoning](/20260511-20260609/2605.27765v1-restoring-the-sweet-spot-pass-rate-weighted-self-distillation-for-llm-reasoning)  
   标签：评分：8.0/10、query:policy-dist
   evidence：自蒸馏策略优化用于大语言模型的强化学习，分析难度感知问题
37. [Distilling LLM Feedback for Lean Theorem Proving](/20260511-20260609/2605.30861v1-distilling-llm-feedback-for-lean-theorem-proving)  
   标签：评分：8.0/10、query:policy-dist
   evidence：在定理证明中应用在线策略自蒸馏进行后训练，直接相关语言模型后训练中的在线策略蒸馏
38. [Weak Critics Make Strong Learners: On-Policy Critique Distillation for Scalable Oversight](/20260511-20260609/2606.00424v1-weak-critics-make-strong-learners-on-policy-critique-distillation-for-scalable-oversight)  
   标签：评分：8.0/10、query:policy-dist
   evidence：提出用于可扩展监督的在线策略批评蒸馏
39. [Internalize the Temperature: On-Policy Self-Distillation as Policy Reheater for Reinforcement Learning](/20260511-20260609/2606.00755v1-internalize-the-temperature-on-policy-self-distillation-as-policy-reheater-for-reinforcement-learning)  
   标签：评分：8.0/10、query:policy-dist
   evidence：温度缩放在线策略自蒸馏缓解RL熵坍缩
40. [Physics-Guided Policy Optimization with Self-Distillation](/20260511-20260609/2606.03620v1-physics-guided-policy-optimization-with-self-distillation)  
   标签：评分：8.0/10、query:policy-dist
   evidence：物理引导的策略优化结合自蒸馏用于大语言模型后训练
41. [Teaching the Way, Not the Answer: Privileged Tutoring Distillation for Multimodal Policy Optimization](/20260511-20260609/2606.07000v1-teaching-the-way-not-the-answer-privileged-tutoring-distillation-for-multimodal-policy-optimization)  
   标签：评分：8.0/10、query:policy-dist
   evidence：后训练中的多模态策略优化特权辅导蒸馏，解决稀疏奖励问题


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

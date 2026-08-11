<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-11
- 运行时间：2026-08-11 20:56:59 UTC
- 运行状态：成功
- 本次总论文数：14
- 精读区：10
- 速读区：4

### 今日简报（AI）
今日14篇推荐中，10篇精读、4篇速读，核心聚焦On-Policy自蒸馏与弱驱动共训练方法。最值得精读的是两篇满分论文《On-Policy Self-Distillation without Any Supervision》和《WDL-OPD》，前者探索无监督自蒸馏，后者提出弱驱动混合约束共训练，均具启发性。建议普通读者优先把握这两篇的方法框架，再顺带浏览速读中的多教师ASR蒸馏和长指令合规逻辑检测，可快速扩展视野。
- 详情：[/202608/11/README](/202608/11/README)

### 精读区论文标签
1. [On-Policy Self-Distillation without Any Supervision](/202608/11/2608.06296v2-on-policy-self-distillation-without-any-supervision)  
   标签：评分：10.0/10、query:policy-dist
   evidence：通过内部一致性实现无外部监督的在线策略自蒸馏
2. [WDL-OPD: Weak-Driven On-Policy Distillation via Mixture-Constrained Co-Training](/202608/11/2608.09447v1-wdl-opd-weak-driven-on-policy-distillation-via-mixture-constrained-co-training)  
   标签：评分：10.0/10、query:policy-dist
   evidence：基于混合约束协同训练的弱驱动在线策略蒸馏
3. [Mismatch Matters: On-Policy Distillation Beyond Token Agreement](/202608/11/2608.09836v1-mismatch-matters-on-policy-distillation-beyond-token-agreement)  
   标签：评分：10.0/10、query:policy-dist
   evidence：直接研究大语言模型后训练中的在线策略蒸馏，揭示token一致性失效模式
4. [Adaptive Supervised Anchoring for On-Policy Self-Distillation](/202608/11/2608.07935v1-adaptive-supervised-anchoring-for-on-policy-self-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：为在线自蒸馏提出自适应监督锚定，直接增强OPSD方法
5. [Matching Supervision to the Student's Learning Capacity: A Unified Framework for On-Policy Self-Distillation](/202608/11/2608.08176v1-matching-supervision-to-the-students-learning-capacity-a-unified-framework-for-on-policy-self-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：统一on-policy自蒸馏框架，耦合token加权与教师特权量
6. [PAST: Privileged Adaptation from Complete Student Trajectories for On-Policy Self-Distillation](/202608/11/2608.08726v1-past-privileged-adaptation-from-complete-student-trajectories-for-on-policy-self-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：面向推理语言模型的在线自蒸馏方法
7. [Learning from Consensus and Disagreement: Unsupervised On-Policy Self-Distillation with Minority-Trajectory Contrast](/202608/11/2608.08764v1-learning-from-consensus-and-disagreement-unsupervised-on-policy-self-distillation-with-minority-trajectory-contrast)  
   标签：评分：9.0/10、query:policy-dist
   evidence：面向LLM推理的完全无监督on-policy自蒸馏方法
8. [Privileged Solutions or Context-Induced Teacher Behavior? Dissecting On-Policy Self-Distillation](/202608/11/2608.09228v1-privileged-solutions-or-context-induced-teacher-behavior-dissecting-on-policy-self-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：通过控制教师上下文剖析on-policy自蒸馏的作用机制
9. [SR-OPSD: Self-Referenced On-Policy Self-Distillation](/202608/11/2608.09745v1-sr-opsd-self-referenced-on-policy-self-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：直接提出自引用变体以稳定on-policy自蒸馏
10. [Distill Skills into Weights, Not Prompts: Abstract Skills as Privileged Signals for On-Policy Self-Distillation](/202608/11/2608.09826v1-distill-skills-into-weights-not-prompts-abstract-skills-as-privileged-signals-for-on-policy-self-distillation)  
   标签：评分：9.0/10、query:policy-dist
   evidence：提出SKALD，用抽象技能卡片作为特权信号进行在线策略自蒸馏

### 速读区论文标签
1. [DreOPD: Degraded-Reference Extrapolative On-Policy Distillation for Flow-matching Models](/202608/11/2608.09233v1-dreopd-degraded-reference-extrapolative-on-policy-distillation-for-flow-matching-models)  
   标签：评分：8.0/10、query:policy-dist
   evidence：面向生成模型后训练的在线策略蒸馏方法
2. [Language-Specialized Multi-Teacher On-Policy Distillation for Multilingual LLM-Based ASR](/202608/11/2608.03610v2-language-specialized-multi-teacher-on-policy-distillation-for-multilingual-llm-based-asr)  
   标签：评分：7.0/10、query:policy-dist
   evidence：提出多教师在线策略蒸馏用于多语言LLM语音识别，属于策略蒸馏方法
3. [Long SKILL Compliance as Logical Reasoning: Closure-Grounded Detection with Scaling-Guided On-Policy Distillation](/202608/11/2608.08146v1-long-skill-compliance-as-logical-reasoning-closure-grounded-detection-with-scaling-guided-on-policy-distillation)  
   标签：评分：7.0/10、query:policy-dist
   evidence：提出缩放引导的在线策略蒸馏用于长SKILL合规检测
4. [Bidirectional Context Self-Distillation for Reinforcement Learning of Skill-Based LLM Agents](/202608/11/2608.09555v1-bidirectional-context-self-distillation-for-reinforcement-learning-of-skill-based-llm-agents)  
   标签：评分：6.0/10、query:policy-dist
   evidence：结合双向上下文自蒸馏与强化学习，提升技能型LLM智能体的技能利用能力


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

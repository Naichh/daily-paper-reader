<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-17
- 运行时间：2026-09-17 21:47:41 UTC
- 运行状态：成功
- 本次总论文数：7
- 精读区：5
- 速读区：2

### 今日简报（AI）
今天筛出 7 篇论文、精读 5 篇，其中两篇满分 10.0 的 on-policy 蒸馏工作最亮眼。

最值得看的方向是「蒸馏怎么做得更聪明」：一篇用验证器门控多专家来分配科学推理中的教学职责，另一篇用奖励兼容的时序信用分配替代逐 token 模仿，思路互补。

普通读者可先从这两篇的摘要和图示入手理解 on-policy 蒸馏的基本逻辑，再按需翻阅 7.0 分的 ReDraft 与 SEA-LION-v4.8 作为应用侧参考。
- 详情：[/202609/17/README](/202609/17/README)

### 精读区论文标签
1. [Who Teaches Which Token? Verifier-Gated Multi-Expert On-Policy Distillation for Scientific Reasoning](/202609/17/2609.15404v2-who-teaches-which-token-verifier-gated-multi-expert-on-policy-distillation-for-scientific-reasoning)  
   标签：评分：10.0/10、query:policy-dist
   evidence：面向后训练的多教师在线策略蒸馏，对RL专家进行token级监督
2. [Beyond Token-Local Imitation: Reward-Compatible Temporal Credit Assignment for On-Policy Distillation](/202609/17/2609.16937v1-beyond-token-local-imitation-reward-compatible-temporal-credit-assignment-for-on-policy-distillation)  
   标签：评分：10.0/10、query:policy-dist
   evidence：面向LLM后训练在线策略蒸馏的时序信用分配
3. [Trajectory Learnability for Offline On-Policy Distillation with Imperfect Teachers](/202609/17/2609.18321v1-trajectory-learnability-for-offline-on-policy-distillation-with-imperfect-teachers)  
   标签：评分：10.0/10、query:policy-dist
   evidence：面向不完美教师的离线在线策略蒸馏，研究教师监督的可学习性
4. [Lightning Weave: Improving the Accuracy-Efficiency Frontier of Reasoning Models through Capability Composition](/202609/17/2609.14708v2-lightning-weave-improving-the-accuracy-efficiency-frontier-of-reasoning-models-through-capability-composition)  
   标签：评分：9.0/10、query:policy-dist
   evidence：通过在线策略蒸馏组合后训练能力
5. [OPD-Aha: From Linguistic Momentum to Visual Reflection in Multimodal On-Policy Distillation](/202609/17/2609.16459v1-opd-aha-from-linguistic-momentum-to-visual-reflection-in-multimodal-on-policy-distillation)  
   标签：评分：8.0/10、query:policy-dist
   evidence：特权多模态在线策略蒸馏

### 速读区论文标签
1. [ReDraft, Don't Just Distill: Reference-Driven Revision for Continual VLLM Post-Training](/202609/17/2609.16639v1-redraft-dont-just-distill-reference-driven-revision-for-continual-vllm-post-training)  
   标签：评分：7.0/10、query:policy-dist
   evidence：面向持续VLLM后训练的在线策略方法，包含自蒸馏
2. [SEA-LION-v4.8: A Technical Report](/202609/17/2609.18310v1-sea-lion-v48-a-technical-report)  
   标签：评分：7.0/10、query:policy-dist
   evidence：后训练采用监督微调与在线在策略蒸馏


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>

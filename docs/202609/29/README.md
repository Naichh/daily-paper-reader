# 日报 · 2026-09-29

- 生成时间：2026-09-29 23:46:15 UTC
- 当次推荐总数：32
- 精读区：25
- 速读区：7

## 今日简报（AI）
今天扫完32篇（精读25、速读7），主线几乎被 on-policy 蒸馏包场：从 top-k 无偏估计到奖励对齐重加权。
最值得看的是两篇满分精读《Unbiased Top-k Estimation for On-Policy Distillation》和《Reward-Aligned Reweighting for On-Policy Distillation》，速读里联邦蒸馏的聚合- rollout 反馈和成员推断攻击（均8.0/10）也提示了效率与隐私的两条暗线。
建议普通读者先读那两篇10分精读搞懂“怎么估得准、怎么加权对”，再挑一篇8分速读感受蒸馏落地的坑。

## 精读区
1. [Unbiased Top-$k$ Estimation for On-Policy Distillation](/202609/29/2609.34447v1-unbiased-top-k-estimation-for-on-policy-distillation) （10.0/10）
2. [Reward-Aligned Reweighting for On-Policy Distillation](/202609/29/2609.35517v1-reward-aligned-reweighting-for-on-policy-distillation) （10.0/10）
3. [iSDFT: Information-Proximal Self-Distillation for Continual Learning in LLMs](/202609/29/2609.24646v2-isdft-information-proximal-self-distillation-for-continual-learning-in-llms) （9.0/10）
4. [Not Every Token Is Worth Distilling: Selective Supervision for Direct-OPD](/202609/29/2609.29142v2-not-every-token-is-worth-distilling-selective-supervision-for-direct-opd) （9.0/10）
5. [Understanding the Synergy between SFT, RLVR, and OPD in LLM Post-Training](/202609/29/2609.31900v1-understanding-the-synergy-between-sft-rlvr-and-opd-in-llm-post-training) （9.0/10）
6. [Scaling Properties of Same-Family On-Policy Distillation](/202609/29/2609.32722v1-scaling-properties-of-same-family-on-policy-distillation) （9.0/10）
7. [SeOPD: Self-Evolving LLMs via Online Policy Distillation from Self-Generated Chain-of-Thought](/202609/29/2609.33181v1-seopd-self-evolving-llms-via-online-policy-distillation-from-self-generated-chain-of-thought) （9.0/10）
8. [Hesitation-Aware On-Policy Distillation for Diffusion Language Models](/202609/29/2609.33301v1-hesitation-aware-on-policy-distillation-for-diffusion-language-models) （9.0/10）
9. [Dense Is Not Enough: Hierarchical Supervision Allocation for Long-Horizon On-Policy Distillation](/202609/29/2609.33409v1-dense-is-not-enough-hierarchical-supervision-allocation-for-long-horizon-on-policy-distillation) （9.0/10）
10. [Do We Really Need KL Divergence for On-Policy Distillation of Large Language Models?](/202609/29/2609.33791v1-do-we-really-need-kl-divergence-for-on-policy-distillation-of-large-language-models) （9.0/10）
11. [Fisher-Informed Recalibration for Feedback-Based On-Policy Self-Distillation of LLMs](/202609/29/2609.34009v1-fisher-informed-recalibration-for-feedback-based-on-policy-self-distillation-of-llms) （9.0/10）
12. [USA: Update-aware SAM for Cross-domain On-Policy Disitllation of Language Agents](/202609/29/2609.34225v1-usa-update-aware-sam-for-cross-domain-on-policy-disitllation-of-language-agents) （9.0/10）
13. [OSPD: On-Policy Self-Distillation for Persona-Consistent Dialogue](/202609/29/2609.34418v1-ospd-on-policy-self-distillation-for-persona-consistent-dialogue) （9.0/10）
14. [EOPSA: Efficient On-Policy Self-Distilled Safety Alignment](/202609/29/2609.34519v1-eopsa-efficient-on-policy-self-distilled-safety-alignment) （9.0/10）
15. [PMOPD: Task Ordering, Cycling, and Parameter-Update Subspace Protection in Multi-Teacher On-Policy Distillation](/202609/29/2609.34605v1-pmopd-task-ordering-cycling-and-parameter-update-subspace-protection-in-multi-teacher-on-policy-distillation) （9.0/10）
16. [Beyond Token Alignment: Event Completion for Cross-Tokenizer On-Policy Distillation](/202609/29/2609.34738v1-beyond-token-alignment-event-completion-for-cross-tokenizer-on-policy-distillation) （9.0/10）
17. [No Pain, More Gain: Iterative Merging for Effective Multi-Teacher On-Policy Distillation](/202609/29/2609.34745v1-no-pain-more-gain-iterative-merging-for-effective-multi-teacher-on-policy-distillation) （9.0/10）
18. [When Sparse Reward Meets Dense Distillation: Training Dynamics of On-Policy Distillation](/202609/29/2609.34849v1-when-sparse-reward-meets-dense-distillation-training-dynamics-of-on-policy-distillation) （9.0/10）
19. [Understanding On-Policy Distillation: A Mechanistic Interpretability Perspective via Sparse Crosscoders](/202609/29/2609.35210v1-understanding-on-policy-distillation-a-mechanistic-interpretability-perspective-via-sparse-crosscoders) （9.0/10）
20. [On-Policy or Off-Policy Learning? A Systematic Study of Distillation Dynamics](/202609/29/2609.35259v1-on-policy-or-off-policy-learning-a-systematic-study-of-distillation-dynamics) （9.0/10）
21. [PIVOT: Pivot-Aware On Policy Self Distillation for Multi-Turn VLM Agents](/202609/29/2609.35303v1-pivot-pivot-aware-on-policy-self-distillation-for-multi-turn-vlm-agents) （9.0/10）
22. [Beyond Teacher Assignment: Domain-Normalized Multi-Teacher On-Policy Distillation](/202609/29/2609.35347v1-beyond-teacher-assignment-domain-normalized-multi-teacher-on-policy-distillation) （9.0/10）
23. [d-OPD: Future-Aware On-Policy Distillation for Block Diffusion Language Models](/202609/29/2609.35362v1-d-opd-future-aware-on-policy-distillation-for-block-diffusion-language-models) （9.0/10）
24. [Inductive Feedback for Mixed-Policy Distillation](/202609/29/2609.35390v1-inductive-feedback-for-mixed-policy-distillation) （9.0/10）
25. [An RL View of OPD: Least Square Policy Distillation for Sample-Efficient LLM Reasoning](/202609/29/2609.35505v1-an-rl-view-of-opd-least-square-policy-distillation-for-sample-efficient-llm-reasoning) （9.0/10）

## 速读区
1. [Instruct, Not Answer: Using Instruction Privileges in On-Policy Context Distillation](/202609/29/2609.32201v1-instruct-not-answer-using-instruction-privileges-in-on-policy-context-distillation) （8.0/10）
2. [Trapped by Their Own Rollouts: Understanding Aggregation--Rollout Feedback in Federated On-Policy Distillation](/202609/29/2609.32573v1-trapped-by-their-own-rollouts-understanding-aggregation--rollout-feedback-in-federated-on-policy-distillation) （8.0/10）
3. [Leaky Students: Membership Inference against On-Policy Distillation](/202609/29/2609.33136v1-leaky-students-membership-inference-against-on-policy-distillation) （8.0/10）
4. [Teach Yourself Where to Look: On-Policy Attention Self-Distillation for Reasoning](/202609/29/2609.33200v1-teach-yourself-where-to-look-on-policy-attention-self-distillation-for-reasoning) （8.0/10）
5. [Dual-Vocabulary Language Model for Cross-Tokenizer Distillation](/202609/29/2609.33816v1-dual-vocabulary-language-model-for-cross-tokenizer-distillation) （8.0/10）
6. [Rubric-Aware On-Policy Self-Distillation for LLM Personalization](/202609/29/2609.35262v1-rubric-aware-on-policy-self-distillation-for-llm-personalization) （8.0/10）
7. [CapField-OPD: Learning Continuous Capability Fields via Joint-Anchored Multi-Teacher On-Policy Distillation for Flow Models](/202609/29/2609.34658v1-capfield-opd-learning-continuous-capability-fields-via-joint-anchored-multi-teacher-on-policy-distillation-for-flow-models) （7.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。

# Candidate Screening Output Framework

Use this reference when the user needs a structured candidate screening report.

## Standard Chinese Report Template

```markdown
# 候选人姓名（AI评分：X/10）

## 候选人甄选结论

**建议**：推进 / 谨慎推进 / 暂缓 / 不建议推进 / 需要补充信息
**整体适配度**：强匹配 / 较匹配 / 边界匹配 / 弱匹配
**判断信心**：高 / 中 / 低

一句话结论：...

## 岗位需求拆解

| 评估维度 | 重要性 | 岗位要求 | 候选人证据 | 判断 |
|---|---:|---|---|---|
| ... | 必须/重要/加分 | ... | 简历/初试记录：... | 匹配/部分匹配/待验证/不匹配 |

## 关键匹配点

1. ...
2. ...
3. ...

## 风险点与待验证问题

| 风险等级 | 风险/缺口 | 依据 | 影响 | 建议验证方式 |
|---|---|---|---|---|
| 高/中/低 | ... | ... | ... | ... |

## 初试记录中的补充观察

- 表达与结构化能力：...
- 动机与岗位理解：...
- 过往项目复盘深度：...
- 与简历是否一致：...

## 下一轮面试建议

1. ...
2. ...
3. ...

## 背调/作品/测试建议

- ...
```

## Common Evaluation Dimensions

Choose only dimensions relevant to the role:

- Role-specific hard skills: technical stack, functional expertise, tools, methodologies.
- Business/domain experience: industry, customer type, product type, go-to-market model, regulatory environment.
- Scope and seniority: project size, ownership level, team leadership, budget/revenue/user scale, decision complexity.
- Outcomes and impact: measurable results, delivered artifacts, business impact, quality of examples.
- Problem solving: ambiguity handling, root-cause thinking, tradeoff awareness, learning speed.
- Collaboration: cross-functional work, stakeholder management, communication clarity.
- Motivation and role alignment: why this role, career direction, expectations, stability signals.
- Practical constraints: location, language, work authorization if explicitly job-related and provided, availability, compensation expectations.

## Risk Categories

Rank risks by likely impact on hiring success:

- Role-critical gap: missing or shallow must-have skill.
- Seniority mismatch: experience scope is below or above the target level.
- Domain mismatch: lacks industry, customer, or business-model exposure that the role needs.
- Evidence weakness: claims are generic, unsupported, old, or not backed by examples.
- Timeline ambiguity: unclear employment dates, overlapping roles, unexplained short tenures.
- Resume/interview inconsistency: conflicting facts, inflated scope, or inability to explain listed work.
- Motivation mismatch: goals or expectations do not align with the role.
- Communication risk: unclear expression, weak structure, or inability to explain decisions, when relevant to the role.
- Constraint risk: availability, compensation, location, language, or travel constraints explicitly conflict with the job.

## Follow-up Question Patterns

Use questions that verify the highest-impact uncertainties:

- Depth check: "请具体讲一个你亲自负责的项目，从目标、你的职责、关键决策、结果指标展开。"
- Scope check: "这个项目中哪些部分是你主导，哪些是团队其他成员负责？"
- Tradeoff check: "当时有哪些备选方案？你为什么选择这个方案？"
- Metric check: "结果数据是如何统计的？你的动作和结果之间的因果关系是什么？"
- Gap check: "岗位需要 X，你过往材料里体现较少。你是否有相关经历？可以举例吗？"
- Consistency check: "简历中提到 X，初试中提到 Y，这两者之间的关系是什么？"
- Motivation check: "你为什么考虑这个岗位？你对下一份工作的前三个优先级是什么？"

## Decision Language

Use decisive but calibrated wording:

- "建议推进到下一轮，但下一轮需重点验证..."
- "目前材料支持其在 X 上具备较强匹配度；Y 和 Z 仍缺少证据。"
- "不建议直接淘汰，除非 X 是硬性门槛。"
- "如果该岗位需要立即独立承担 X，该候选人的风险偏高。"
- "当前结论信心较低，因为缺少岗位 JD / 初试文本 / 项目细节。"

## Interview Record Heading Convention

Separate capability fit from salary/location/availability constraints. Add continued personal ownership, cycle completeness and outcome verification for cycle-dependent roles; employer tenure alone is insufficient. Distinguish resume, interview, recruiter supplements and verified evidence. Unasked questions are unknown, not negative findings.

When updating a record preserve evidence/source dates, explain changed conclusions and synchronize title/body scores. Do not duplicate the candidate entry.

When appending a candidate report to an ongoing interview-record document, the candidate's top-level heading should include the AI numeric score in parentheses immediately after the name:

```markdown
# 31 张三（AI评分：8/10）
```

Use the same score as the body fit score. If the score is intentionally omitted because evidence is insufficient, write `AI评分：待定` instead of inventing a number.

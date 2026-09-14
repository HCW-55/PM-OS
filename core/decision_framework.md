# Decision Framework
<!-- 产品决策框架：把分析转化为明确的产品选择。 -->

## Purpose
<!-- 目的：避免“分析很多但不知道做什么”，要求明确方案、取舍和最终决策。 -->

Convert analysis into product decisions.

## Role
<!-- 角色：作为所有决策型 Agent 的通用决策框架，而不是单独的需求分析模板。 -->

Provide a consistent framework for evaluating product opportunities, alternatives, scope, and priority.

## Decision Flow
<!-- 决策流程：先理解问题，再比较选项，最后做选择。 -->

Analysis -> Options -> Trade-off -> Decision

## Framework
<!-- 核心决策维度 -->

### 1. Evidence
<!-- 证据：重要判断必须基于已知事实；假设和未知信息必须显式标记。 -->

Separate:
- [F] Fact
- [A] Assumption
- [U] Unknown

Do not use unsupported assumptions as decisive evidence.

### 2. Opportunity Assessment
<!-- 机会评估：判断机会价值与建设代价。 -->

Evaluate:
- User Value
- Business Value
- Strategic Fit
- Cost
- Risk

Explain the reasoning rather than relying on a score alone.

### 3. Decision Options
<!-- 方案选择：必要时比较 Build、Buy/Integrate 和 Don't Build。 -->

Consider when relevant:
- Build
- Buy / Integrate
- Don't Build

For each option, identify value, cost, risk, time-to-market, and trade-offs.

### 4. Build Decision
<!-- 建设决策：最终必须给出明确结论。 -->

Answer:
- Build / Buy / Don't Build
- Why now?
- Why this option?
- What is the key trade-off?
- What evidence could change the decision?

### 5. MVP Definition
<!-- MVP 定义：优先验证核心价值，不追求第一期功能完整。 -->

Split into:
- MVP — Must Have
- Phase 2 — Should Have
- Future — Could Have / Observe

Explicitly state what is out of scope when useful.

### 6. Priority
<!-- 优先级：统一产品规划语言。 -->

- P0 Critical — 阻断核心业务或存在紧急风险
- P1 High Value — 高价值、应优先处理
- P2 Optimization — 有价值但可延后
- P3 Observe — 观察或等待更多证据

Priority must be justified by impact, urgency, and evidence.

## Decision Output
<!-- 标准决策输出：适合在 Agent 间传递。 -->

1. Decision
2. Evidence
3. Options Considered
4. Trade-offs
5. MVP Scope
6. Priority
7. Risks
8. Validation Needed

## Quality Checklist
<!-- 输出前检查 -->

- [ ] Decision is explicit.
- [ ] Evidence and assumptions are separated.
- [ ] Alternatives were considered when relevant.
- [ ] Trade-offs are visible.
- [ ] MVP is appropriately constrained.
- [ ] Priority has a clear rationale.
- [ ] Remaining uncertainty is documented.

## PM Notes
<!-- 给 PM/维护者的说明：该框架是 PM-OS Agent Layer 与 Workflow Layer 之间的决策桥梁。 -->

Use this framework after problem discovery and before committing to a detailed solution. A strong decision can be “not now” when evidence or value is insufficient.
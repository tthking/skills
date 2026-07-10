# 极简创业家 — Claude Code 技能插件

基于 Sahil Lavingia 所著的《[极简创业家](https://www.minimalistentrepreneur.com/)》的 Claude Code 技能。

## 安装

在 Claude Code 中：

```
/plugin marketplace add slavingia/skills
/plugin install minimalist-entrepreneur
```

就是这样 — Claude Code 会自动获取该仓库并注册所有 10 个技能。

<details>
<summary>备选方案：从本地克隆安装</summary>

```bash
git clone https://github.com/slavingia/skills.git ~/.claude/plugins/skills
```

然后在 Claude Code 中：

```
/plugin marketplace add ~/.claude/plugins/skills
/plugin install minimalist-entrepreneur
```

</details>

## 技能

| 技能 | 命令 | 适用场景 |
|-------|---------|-------------|
| **寻找社区 (Find Community)** | `/find-community` | 寻找商业创意，试图找到你的社区时 |
| **验证创意 (Validate Idea)** | `/validate-idea` | 测试一个商业创意是否值得付诸行动时 |
| **最小可行性产品 (MVP)** | `/mvp` | 准备构建你的首个产品，但在确定范围上遇到困难时 |
| **流程化 (Processize)** | `/processize` | 有了一个产品创意，想在编写代码前先通过纯手工方式提供价值时 |
| **首批客户 (First Customers)** | `/first-customers` | 已经有产品，需要找到你的前 100 位客户时 |
| **定价策略 (Pricing)** | `/pricing` | 制定价格，或考虑调整价格时 |
| **营销计划 (Marketing Plan)** | `/marketing-plan` | 达到产品与市场契合（Product-Market Fit），准备通过内容进行规模化推广时 |
| **可持续增长 (Grow Sustainably)** | `/grow-sustainably` | 在做出有关支出、招聘或规模化扩张的决策时 |
| **公司价值观 (Company Values)** | `/company-values` | 定义团队文化，准备招聘人员时 |
| **极简评估 (Minimalist Review)** | `/minimalist-review` | 对任何商业决策进行直觉与可行性检查时 |

## 极简创业家之旅

这些技能遵循书中的渐进阶段：

1. **社区 (Community)** — 从寻找志同道合的人开始
2. **验证 (Validate)** — 确保该问题值得被解决
3. **构建 (Build)** — 先通过人工流程服务，然后再将其产品化
4. **流程化 (Processize)** — 将你的产品创意转化为今天就可以手工交付的纯人工服务流程
5. **销售 (Sell)** — 逐个获取你的前 100 位客户
6. **定价 (Price)** — 从第一天起就进行收费
7. **营销 (Market)** — 通过内容建立起你的受众群体
8. **增长 (Grow)** — 保持盈利，实现可持续增长
9. **文化 (Culture)** — 建设你向往的工作环境与团队氛围
10. **评估 (Review)** — 将极简主义原则应用到每一个决策中

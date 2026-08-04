# WhiteBox 金融规划引擎

![WhiteBox 社交媒体封面](assets/social-cover.png)

[English](README.md)

WhiteBox 是一个面向中国大陆市场的金融规划智能系统。

它结合确定性的财务建模、以规划器为核心的推理、基于 detector 的证据发现，以及面向顾问交付的解释能力。系统设计吸收了本土财务规划、保险、家庭资产负债表和退休规划等领域从业者的经验。

WhiteBox 不是一个猜答案的聊天机器人。它的目标是成为可审计的规划引擎：正式数字应来自受治理的模型路径，建议应能追溯到结构化事实和假设，探索性结果应与正式规划输出保持清晰边界。

## 问题

金融规划常常卡在两种薄弱形态之间：

- 静态计算器无法同时处理目标、约束、家庭结构、流动性、保险、房产和退休时点。
- 纯语言助手可能表达流畅，却隐藏假设、生成未经验证的数字，或把探索性输出混同为正式建议。

WhiteBox 希望站在中间地带：用结构化推理支持可审计计算。

## 为什么是 WhiteBox

WhiteBox 把金融规划视为一个受治理的模型问题。系统区分已确认事实、假设性条件、规划目标、情景结果、detector 研究证据和顾问解释。

这种区分很重要。一个家庭规划不是一个单点答案，而是一条由事实、假设、约束、权衡和可复核模型结果组成的链条。

## WhiteBox 研究和构建什么

- 围绕资产、负债、现金流、保障和长期规划能力的家庭财务状态建模
- 以 planner 为核心，将目标、约束、权衡和客户优先级转化为结构化规划任务
- 面向退休、教育、房产、保险、流动性和家庭责任的受控情景分析
- 对可重复规划模式、反例和边界条件进行实验性 detector 研究
- 保持假设和计算状态可见的顾问级解释

## 核心创新

WhiteBox 聚焦 planner 和 detector 两条创新方向。

Planner-first reasoning 指的是：在情景分析之前，先把目标和约束表达为结构化规划对象。

Detector research 目前仍是实验方向。我们用 “detector” 描述一种研究思路：寻找可重复的规划信号、边界案例和反例，再决定是否能转化为产品能力。

Detector 的想法部分受到认知科学中对专家能力的理解启发：专家并不只是套用规则，他们会识别有意义的模式、注意异常，并理解判断的边界条件。WhiteBox 探索金融规划系统如何辅助这种专家式模式识别，同时不把早期研究证据伪装成最终建议。

## 市场定位

WhiteBox 立足中国大陆家庭金融规划。

系统设计关注本土现实，例如房产占家庭资产比重较高、家庭责任、教育资金、保险产品语境、退休收入不确定性、流动性约束，以及顾问与客户之间的复核流程。

## 财务模型理论基础

WhiteBox 的建模参考：

- 家庭资产负债表规划
- 生命周期金融
- 现金流与负债匹配
- 长周期风险分析
- 退休收入可持续性
- 流动性和偿付压力测试
- 保险保障缺口分析
- 情景规划和决策科学

系统把金融规划视为受治理的模型问题，而不是文本生成问题。语言模型可以帮助提取、组织和解释信息，但不能生成正式财务数字，也不能决定正式规划资格。

## 文章

WhiteBox 会持续发布 public-safe 的中英双语文章，覆盖财务规划理论、planner-first reasoning、实验性 detector research，以及中国大陆市场语境。

- [离岸信托的税收法理：从“谁名下”到“谁控制、谁受益”](docs/articles/offshore-trust-tax-principles.zh-CN.md)
- [目标不是有了一个数字就算被满足：让资金与时间匹配](docs/articles/goals-need-time.zh-CN.md)
- [保险进入家庭规划：先看今天的账，再看未来的路](docs/articles/insurance-protection-liquidity.zh-CN.md)
- [优化之前，先把家庭的约束说清楚](docs/articles/constraints-before-optimization.zh-CN.md)
- [推荐之前，先比较情景：为什么财务规划从情景开始](docs/articles/scenarios-before-recommendation.zh-CN.md)
- [金融规划不是一个答案，而是一条可审计的推理链](docs/articles/auditable-reasoning-chain.zh-CN.md)
- [结论之前：为什么财务规划需要反例](docs/articles/counterexamples-before-conclusions.zh-CN.md)
- [识别信号之前：先检查规划尚不知道什么](docs/articles/before-a-signal.zh-CN.md)
- [资产很多，为什么仍要看现金流与时间：一个虚构家庭的规划案例](docs/articles/when-assets-are-not-enough.zh-CN.md)

查看完整[文章目录](docs/articles/README.zh-CN.md)。

## 基础文档

- [理论基础](docs/theory-foundation.zh-CN.md)
- [Detector 方法论](docs/detector-methodology.zh-CN.md)
- [中国大陆市场定位](docs/mainland-china-market.zh-CN.md)
- [路线图](ROADMAP.zh-CN.md)

## 路线图

见 [ROADMAP.zh-CN.md](ROADMAP.zh-CN.md)。

## 公开仓库范围

本仓库是一个面向公众的项目入口，包含对外定位、理论说明、市场定位和高层研究方法论。

本仓库有意不包含：

- 私有生产代码
- 客户数据
- 部署绑定
- 私有 prompt
- 未发布模型内部实现
- 内部证据包
- 特定供应商 MVP 实现细节

## 当前状态

早期公开仓库。当前目标是在任何实现代码发布之前，先定义清晰的公共语言、理论基础和研究方向。

## 版权

除非后续许可证文件明确说明，否则保留所有权利。

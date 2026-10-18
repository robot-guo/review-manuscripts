# 简洁审稿措辞示例

以下均为虚构的教学片段，不引用真实未公开稿件。替换位置与内容，不将示例问题当成其他稿件的既定事实。

## 陈述冲突

Lines X–Y state that the method supports anticipatory actions, whereas Lines U–V state that it cannot do so. These statements should be reconciled.

## 基准证据不足

The comparison with a strategy without prediction does not establish an advantage over prediction-based optimization. Please clarify whether an existing baseline uses the same predictions under the same operating setting. If so, report the corresponding results; otherwise, add such a comparison. A heuristic implementation would be acceptable.

调整措辞以承认现有比较实际支持的结论。若同时改变算法，不断言提升完全来自预测。不要声称这项框架比较能单独识别状态增强的贡献。

## 不明确的消融

Does the non-graph baseline retain the same prediction inputs? The text describes a change in architecture, while the response also suggests a change in inputs. These settings need to be clarified.

## 求和指标

In the first branch of Eq. (X), should the summation index be i ∈ N rather than p ∈ P?

## 时间窗

Eq. (X) imposes the earliest service time, while Table Y includes a lateness penalty. Is the latest service time a hard constraint or handled through a penalty? What does this penalty apply to?

## 文字替换

In Lines X–Y, “requires additional memory” should read “The encoder requires additional memory”.

只补足明确遗漏；不擅自增加内存复杂度等未经确认的技术含义。

## 总评

The revision addresses some of my previous concerns. However, issues remain regarding [与实际意见对应的主要问题].

仅在用户要求整体稿件概述时添加简短方法摘要。避免空泛的 relevant and timely、反复致谢、笼统断言 lacks novelty。

## 理论命题

The proposition applies to all real values, but the proof only covers positive values. How is the remaining domain handled?

## 访谈与结论边界

The interviews support participants’ reported experiences. The claim of a causal effect needs further justification or a narrower formulation.

## 叙述综述

The basis for selecting the discussed sources is unclear. A brief explanation would help readers assess the scope of the review.

不因论文缺少修订记录而写“仍未解决”；独立审阅先描述当前材料中的问题。

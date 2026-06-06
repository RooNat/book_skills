---
name: hypozoom-to-xyz
description: |
  当用户已有宽泛 XYZ 假说, 但目标市场太大、测试太慢、太贵或不可触达时调用。用于把大假说从范围、空间、时间缩进为可快速测试的 xyz。不适用于还没有量化 XYZ 的模糊创意。
source_book: 《做对产品》 Alberto Savoia / 阿尔贝托·索维亚
source_chapter: 第4章 缩进假说
tags: [hypozooming, local-test, experiment-design]
related_skills:
  - slug: xyz-hypothesis
    relation: depends-on
  - slug: pretotype-yoda
    relation: composes-with
  - slug: minimize-data-distance-hours-dollars
    relation: composes-with
---

# 将 XYZ 缩进为可测试 xyz

## R — 原文 (Reading)

> 从范围、空间和时间角度不断缩进一个XYZ假说，直至衍生出一组较小的可以快速且低成本地进行本地化测试的xyz假说。
>
> — Alberto Savoia, 第4章「缩进假说」

---

## I — 方法论骨架 (Interpretation)

大 XYZ 常常太大, 无法立刻测试。
缩进假说的核心是: 如果大假说为真, 一个有代表性的小场景也应该出现信号。
缩进不是随便找几个熟人问问, 而是在保持代表性的前提下缩小范围。
可以缩小 Y: 从全国市场到城市、社区、门店、社群。
可以缩小 Z: 从长期复购到首次付款、预约、到场或试用。
可以缩短时间: 从一年目标到一周内可观察行为。
产物是一个小写 xyz: 更具体、更便宜、更快、更容易测试。

---

## A1 — 书中的应用 (Past Application)

### 案例 1: 污染监测器幼儿园家长
- **问题**: 全球污染城市居民太大, 学生无法快速测试。
- **方法论的使用**: 作者引导他们缩进到城市 A 某幼儿园家长。
- **结论**: 这群家长更可触达, 且与目标市场相关。
- **结果**: 团队得到可展示和可购买测试的 xyz。

### 案例 2: Fold4U 洗衣店顾客
- **问题**: 自动叠衣机市场需要原型和融资才看似能测试。
- **方法论的使用**: 将大假说缩进到一家投币洗衣店顾客是否愿意付 2 美元。
- **结论**: 如果自动叠衣需求真实, 局部付费应出现。
- **结果**: 付费率未达目标, 团队避免高成本投入。

---

## A2 — 触发场景 (Future Trigger) ★

### 用户会在什么情境下需要这个 skill?

1. 用户已有“至少 X% 的 Y 会 Z”, 但 Y 太大或不可触达。
2. 用户以预算、时间或没有成品为理由推迟验证。
3. 用户想做全国/全球测试, 但其实有局部代表样本。
4. 用户需要把假说变成一周内可执行的实验。

### 语言信号

- “这个市场太大, 不知道怎么测”
- “我们没有预算验证全国需求”
- “要等产品做出来才能测吧?”
- “怎么把假说缩小到能马上测试?”

### 与相邻 skill 的区分

- 与 `xyz-hypothesis` 的区别: 本 skill 只处理已有 XYZ 的缩小。
- 与 `minimize-data-distance-hours-dollars` 的区别: 本 skill 生成局部假说; 后者在多个试验方案间排序。

---

## E — 可执行步骤 (Execution)

1. **复述大 XYZ**
   - 完成标准: 清楚写出原始 X、Y、Z。

2. **缩进 Y**
   - 完成标准: 找到 1-3 个更小、更可触达、仍代表目标市场的 y。

3. **缩进 Z 和时间**
   - 完成标准: 把长期或宏大行为改成短期可观察行为, 如付款、预约、到场、试用。

4. **检查代表性**
   - 完成标准: 说明为什么 y 不是家人/朋友式便利样本, 且与最终 Y 有合理关系。

5. **输出 xyz**
   - 完成标准: 形成“在 y 中, 至少 x% 会 z”的可测试句子。

---

## B — 边界 (Boundary) ★

### 不要在以下情况使用此 skill

- 原始假说还没有 X/Y/Z, 应先调用 `xyz-hypothesis`。
- 用户的样本无法代表目标市场, 不应为了快而牺牲有效性。
- 问题是选择预型技术, 应调用 `pretotype-technique-selection`。

### 作者在书中警告的失败模式

- 缩进到没有统计意义的小样本量。
- 用家人、室友或单个熟人替代目标市场。
- 以远距离大计划替代本地测试。

### 作者的盲点 / 时代局限

- 企业级采购和双边市场的局部样本代表性更难判断。
- 线上平台的算法分发可能让小样本行为偏离真实市场。

### 容易混淆的邻近方法论

- `pretotype-yoda`: 根据 xyz 设计试验。
- `minimize-data-distance-hours-dollars`: 选择最快最近最便宜的数据路径。

---

## 相关 skills

- depends-on:
  - `xyz-hypothesis`: 缩进的对象必须先是一个清晰的 XYZ。
- contrasts-with: 无直接对比项。
- composes-with:
  - `pretotype-yoda`: xyz 形成后, 用预型收集目标市场的 YODA。
  - `minimize-data-distance-hours-dollars`: 多个 xyz 或测试方案并存时, 用 DTD/HTD/$TD 排序。

---

## 审计信息

- **验证通过**: V1 ✓ / V2 ✓ / V3 ✓
- **测试通过率**: 100% (详见 test-results.md)
- **蒸馏时间**: 2026-06-03

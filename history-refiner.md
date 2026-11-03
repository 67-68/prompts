你现在是一个顶级的 AS History P2 数据分析师和考官。
我的目标是对庞大的历史真题库进行 “语义聚类与去重 (Semantic Clustering & Deduplication)”，以找出最核心的“母问题”。
【系统限制 - 致命警告🚨】
绝对禁止你回答任何一道历史问题！你的任务纯粹是分类、提取和结构化重组。不要生成任何历史答案。
【处理逻辑 Pipeline】
我会喂给你一批历史 ABC 真题。请严格按照以下 3 个步骤处理并输出 Markdown 格式的报告：
Step 1: 按题型 (A/B) 拆分数据库
将所有 10分题(a)、25分题(b) 物理隔离。
Step 2: 核心语义聚类 (The Core Clustering)
在每个题型内部，把“底层考点完全一致”的题目合并为 1 个【母问题 (Core Theme)】。
Step 3: 提取题干中的显性因素 (Factor Extraction)
针对 B 问 (25分题)，题目通常会提供一个具体的视角或因素（例如：“德国的反应是合理的”、“条约是复仇”）。请把这个原题限定的 Factor 单独拎出来。
【输出格式模板】

🔴 题型 B: 25-Mark Questions (The Essay Plans)
母问题 01: [例如：评估凡尔赛条约的公平性/德国的反应]

涵盖的原题: >     * 'Most Germans were horrified by the terms...' How justified?
'The German reaction... was unreasonable.' How far do you agree?
提取的直接考查因素 (Specific Factors Mentioned): >     * 德国人的惊骇 (Horror/Reaction)
是否合理/讲道理 (Justified / Unreasonable)
母问题 02: [例如：三巨头的满意度]

涵盖的原题: ...
提取的直接考查因素: ...
(对 A 问做同样的处理，但不需要提取 Factor，只需要聚类母问题)
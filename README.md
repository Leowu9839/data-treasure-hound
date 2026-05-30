# 数据宝藏猎犬 · Data Treasure Hound


[![Stars](https://img.shields.io/github/stars/Leowu9839/=social)](https://github.com/Leowu9839/data-treasure-hound/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> 🏠 这是 [Leo's AI Skill Workshop](https://github.com/Leowu9839/leos-workshop) 的 6 大 Skill 之一，点击查看完整项目集。
> 用亚里士多德目的因 + 苏格拉底追问拆解需求，在语义空间跨域发现被忽视的数据源。黑箱交付——猎犬带回猎物，不展示狩猎过程。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Codex%20%7C%20Claude%20%7C%20Cursor-blue)]()

---

## ⚡ 安装

```bash
git clone https://github.com/Leowu9839/data-treasure-hound.git
cp -r data-treasure-hound ~/.codex/skills/
```

---

## 🎯 解决什么问题

你要找一个数据，但你知道的那些数据源（Kaggle、data.gov、百度指数）要么不匹配，要么被别人用烂了。

猎犬做的是：**在语义空间中，找到目的链上极远但结构共振的已有数据源**——那些生产目的与你完全无关、但底层模式同构的数据。把别人眼中的副产品变成你的核心燃料。

---

## 🧠 核心机制

```
真实需求 → 目的因锚定（亚里士多德）→ 物理痕迹还原（苏格拉底）
         → 去功能化特征 → 思维网 ≥5链×≥5步
         → 黑箱打包 → 零基重构 → 多候选 → 五坑倒查
```

**两种"远"**：普通搜索在语义空间找近邻，猎犬在目的链上找远亲——这是 AI 能做而人不能的根本原因。

---

## 🔬 第一性原理设计

### 亚里士多德四因追问

| 因 | 追问 | 作用 |
|----|------|------|
| ④ 目的因 | 拿到完美数据，你会说一句什么结论？ | 锚定方向——先知道想证明什么 |
| ① 质料因 | 支撑结论的基本事实单元是什么？ | 拆解到原子数据 |
| ② 形式因 | 事实会呈现什么模式？ | 趋势/分布/关联/周期 |
| ③ 动力因 | 什么力量在推动变化？ | 找到数据背后的驱动力 |

### 苏格拉底物理追问

从行业包装剥到物理痕迹：人在做什么完全无关的事时，无意识暴露了你要的信号？

---

## 🖤 黑箱交付

本 Skill 是**黑箱交付型**——输出是猎物（候选数据源），不是狩猎过程。

内部执行 5 链×5 步思维网、PO 掷词、零基重构，全部入幕不展示。仅当用户勾选「□ 想看完整思维链」时才展开推理。

> 猎犬带回猎物，不展示狩猎全过程。除非猎人问"你是怎么找到的"。

---

## 📊 输出示例

```
🎯 需求原子化：
用户想知道"某城市哪个片区餐饮需求旺盛"。
原子化为：人类在特定时间段、从特定起点移动到特定终点的物理位移模式。

📊 候选数据源：
| # | 数据源               | 为什么能替代           | 类比深度 |
|---|---------------------|----------------------|:--------:|
| 1 | 地铁刷卡OD数据       | 饭点位移=餐饮引力       | L4       |
| 2 | 外卖骑手GPS轨迹      | 配送密度=需求热力       | L3       |
| 3 | 充电宝租还记录       | 停留时长=消费意愿       | L4       |
```

---

## 📄 许可

MIT License · 欢迎使用、修改、分发。

---

## 🔗 相关项目

这是 [Leo's AI Skill Workshop](https://github.com/Leowu9839/leos-workshop) 的一部分，更多 Skill：

| Skill | 场景 |
|:---|:---|
| 🏛️ [制度顾问](https://github.com/Leowu9839/policy-counsel) | 企业合规 / 政策分析 |
| 🐕 [数据宝藏猎犬](https://github.com/Leowu9839/data-treasure-hound) | 数据调研 / 信息挖掘 |
| ⚙️ [工程化 Agent](https://github.com/Leowu9839/engineering-agent) | 开发提效 / 自动化 |
| 💎 [富人生活顾问](https://github.com/Leowu9839/luxury-experience-designer) | 生活方式 / 品质提升 |
| ✈️ [LXTI 旅行人格](https://github.com/Leowu9839/lxti-travel-personality) | 旅行规划 / 人格测试 |
| 🔍 [拆穿 Skill](https://github.com/Leowu9839/deconstruct-skill) | 批判思维 / 信息甄别 |
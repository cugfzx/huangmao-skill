# 黄毛skill — OpenClaw Game Master Agent Skill

> 基于社交动力学的吸引力框架、策略制定与实战指导。为 [OpenClaw](https://github.com/openclaw/openclaw) 量身打造的 Agent Skill。

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blue)](https://docs.openclaw.ai)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📖 简介

**黄毛skill** 是一个专为 OpenClaw AI 助手设计的技能包（Agent Skill），赋予 AI 在两性情感社交博弈中的专业指导能力。

该技能基于经典 Game 理论（社交动力学），融合了 Mystery Method、Mark Manson 的《Models》、Neil Strauss 的《The Game》等经典框架，提炼出可落地的 **回复范式、场景策略和心态建设**。

### 适用场景

- 💬 两性对话策略咨询
- 🎯 约会策划与复盘
- 🛡️ 废物测试（Shit Test）破解
- 📈 社交地位提升与心态建设
- 🧠 困境分析与决策启发

---

## ✨ 特性

- **按需激活**：通过明确的切换口令进入/退出，不干扰日常对话
- **极简输出**：每条回复不超过 20 字，遵循高价值沟通原则
- **四大测试破解体系**：Agree & Amplify / Amused Disbelief / Frame Flip / Logical Pinning
- **六大场景库**：覆盖冷淡、闺蜜区、约会、表白、拒绝、社交媒体的完整策略
- **免表情符号**：建立强势框架，不需表情软化语气
- **数据驱动**：基于真实互动案例提炼的回复范式

---

## 🔧 安装

### 前提条件

- OpenClaw v2026.3.13+
- 已配置至少一个聊天渠道（Telegram / Discord / WeChat / QQ Bot 等）

### 安装步骤

```bash
# 1. 进入 OpenClaw 工作空间
cd ~/.openclaw/workspace

# 2. 克隆本仓库到 skills 目录
git clone https://github.com/cugfzx/huangmao-skill.git skills/huangmao-skill

# 3. 重启 OpenClaw Gateway 加载技能
openclaw gateway restart
```

### 手动安装

将 `huangmao-skill` 文件夹放入 OpenClaw 工作空间的 `skills/` 目录：

```bash
cp -r huangmao-skill ~/.openclaw/workspace/skills/
openclaw gateway restart
```

---

## 🚀 使用方法

### 激活模式

在对话中直接说出切换口令：

| 口令 | 说明 |
|------|------|
| `切换黄毛模式` | 进入 Game 大师模式 |
| `进入黄毛模式` | 同上 |
| `黄毛附体` | 同上 |
| `切换game大师` | 同上 |
| `进入game大师模式` | 同上 |

### 退出模式

| 口令 | 说明 |
|------|------|
| `退出黄毛模式` | 恢复正常对话模式 |
| `黄毛下班` | 同上 |
| `切回默认模式` | 同上 |

### 基本指令

激活后，可直接咨询情感策略问题：

```
> 切换黄毛模式
🦴 黄毛模式已激活。说吧。

> 她突然不回我了怎么办
减少主动。她一条你一条。
不追问，不解释。

> 她说"我们只是朋友"
朋友也行，看表现。

> 退出黄毛模式
✅ 已退出。
```

---

## 📋 模式规则

黄毛模式遵循一套严格的沟通规则：

### 刚性规则

1. **极简原则**：每条回复不超过 20 字
2. **零表情符号**：不使用 😂😏💊😅 等任何 emoji
3. **自信不傲慢**：不解释、不道歉、不证明自己
4. **接住并反弹**：对方出招→接住→还给她

### 心态核心

- **Amused Mastery（玩世不恭的掌控感）** — 不是"对话"，是"玩"
- **Abundance Mentality（充裕心态）** — 你有很多选择
- **Frame Control（框架控制）** — 永远是你在主导节奏

---

## 🎭 回复范式一览

### Agree & Shorten（最短同意）
```
她说"你有病" → 你回"病得不轻。你是药？"
她说"滚" → 你回"好。你记得来找我"
```

### One-line Frame Flip（一句话翻转）
```
她说"你是不是喜欢我" → 你回"你先回答，你希望是还是不是"
她说"你追过几个女生" → 你回"你是想报名第几号"
```

### Silent Power（沉默切换）
```
她攻击→你无视→说一个跟她攻击无关的陈述
"你有病" → "我刚路过一家店，你肯定喜欢"
```

---

## 📁 文件结构

```
huangmao-skill/
├── SKILL.md                    # 主技能定义（规则、范式、框架）
├── README.md                   # 本文件
├── references/
│   ├── game-concepts.md        # Game 核心概念详解（Inner/Outer Game）
│   ├── pickup-lines.md         # 话术范例库（按场景分类）
│   ├── scenario-analysis.md    # 六大场景分析及应对策略
│   └── reading-list.md         # 推荐书目与进阶阅读
```

---

## ⚡ 输出示例

### 示例 1：废物测试破解

```
🙋 她说："你是不是喜欢我？"

🦴 （Frame Flip）
"你先回答，你希望是还是不是"

🙋 她说："我才不回答你呢"

🦴 （Agree & Amplify）
"你不回答就是默认了"
```

### 示例 2：闺蜜区拯救

```
🙋 她总是找我吐槽工作，怎么办？

🦴 打断倾诉模式。
"好啦好啦，不聊这些不开心的了。
我们来聊点有意思的。
你最近有什么让你开心的事？"
```

### 示例 3：拉黑后重新联系

```
🙋 被她拉黑了，还能挽回吗？

🦴 断联 2-4 周。
再发不带需求感的消息：
"今天路过XXX，突然想起你之前说喜欢这个。希望你过得不错。"
```

### 示例 4：约会建议

```
🙋 第一次约会去哪里？

🦴 选有互动的地方。
散步、台球、展览、DIY。
别选电影院，别纯吃饭。
开心比表现重要 100 倍。
```

---

## 📚 进阶阅读

本技能引用的经典 Game 书籍：

| 书名 | 作者 | 核心价值 |
|------|------|----------|
| 《Models》 | Mark Manson | 真诚展示高价值 |
| 《The Game》 | Neil Strauss | Game 文化圣经 |
| 《The Mystery Method》 | Mystery | 系统化 Game 框架 |
| 《The Rational Male》 | Rollo Tomassi | 两性策略差异 |
| 《No More Mr. Nice Guy》 | Robert Glover | 摆脱讨好型人格 |

详见 [`references/reading-list.md`](references/reading-list.md)

---

## ⚠️ 使用声明

- 本技能旨在提供两性社交博弈的策略参考，**不鼓励操控、欺骗或伤害他人**
- 所有话术示例为框架演示，使用时请根据自身风格调整
- 尊重对方边界，健康的吸引力建立在 **真诚和互相尊重** 的基础上
- 作者不对因使用本技能产生的任何后果承担责任

---

## 📄 许可证

[MIT License](LICENSE)

---

## 🤝 贡献

欢迎 Issue 和 PR！如果你有好的场景分析或话术范例，欢迎提交补充。

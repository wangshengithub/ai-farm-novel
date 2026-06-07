# 🌾 Farming in the City · ai-farm-novel

**[中文](README.md) | [English](README_EN.md)**

> **I had Claude Code write a 780,000-character Chinese web novel from start to finish, with zero human editing. This is what it produced.**

---

## 📖 What is this

A fairly typical "urban farming" web novel setup: Fang Yuan, a 38-year-old laid-off man drowning in debt, suddenly gets a "Farm System." He grows impossibly good spirit plants on his rooftop, faces accusations of fraud, proves his innocence, slaps his doubters in the face, and eventually builds an urban agriculture empire — picking up a romance along the way.

320 chapters, 7 volumes, roughly 780,000 Chinese characters. Complete outline system too: master outline, detailed outlines, beat sheets, timelines — the whole package.

**But the point of this repo isn't the novel itself.**

---

## 🤖 This is actually an experiment

The entire novel, from the first word to the final chapter, was generated independently by **Claude Code**. I didn't edit a single character — all the mistakes and awkward bits are preserved as-is.

I'm trying to make one simple point:

### Even the best AI falls apart when you make it write long

Below are excerpts from the actual text. No commentary — judge for yourself.

---

**Fragmented padding**

> 【First... watering.】
>
> The system said.
>
> 【Seedling stage... keep the soil moist.】
>
> 【But don't overwater.】
>
> 【Water twice a day... morning and evening.】
>
> 【Morning... before sunrise.】
>
> 【Evening... after sunset.】
>
> 【Water amount... should be moderate.】
>
> 【Soil surface moist... that's enough.】

*— Chapter 50*

---

**Cookie-cutter NPCs**

> Li Min: "OMG, growing so fast! Only 4 days and they're this big!"
>
> Wang Qiang: "Fang Yuan, you're so professional! Recording every day!"
>
> Zhang Ting: "Tender green leaves, so healing!"
>
> Chen Jing: "Looking forward to the harvest!"
>
> Zhou Mei: "Fang Yuan, you work so hard!"
>
> Zhao Min: "Fang Yuan, you're so dedicated!"

*— Chapter 50*

---

**System personality keeps shifting**

> Chapter 50: System speaks with 【】brackets and ellipses:
>
> 【Host.】The system said.【You noticed... uneven growth.】
>
> Chapter 75: System switches to normal dialogue:
>
> "Host," the system said, "congratulations."
>
> Chapter 125: System uses a 【System:】format:
>
> 【System: Host, what are you hesitating about?】
>
> Chapter 175: Both styles mixed together:
>
> 【Good morning, Fang Yuan.】/ The system said. "Trend is looking good."

---

**Data padding**

> June 12: 6:30 AM, 28 seedlings, average height 2.1cm, cotyledons fully spread. 12:00 PM, nice sunlight, temperature 26°C, seedlings in good condition. 7:00 PM, soil moisture 76%, seedlings upright, no lodging.
>
> June 13: 6:30 AM, average height 2.5cm, stable growth. 12:00 PM, temperature 27°C, light breeze, seedlings swaying gently. 7:00 PM, soil moisture 77%, some seedlings' cotyledons starting to slightly enlarge.
>
> June 14: 6:30 AM, average height 3.0cm, growth accelerating. 12:00 PM, temperature 28°C, clear weather.

*— Chapter 50. Similar data logs recur across multiple chapters*

> Seedling #15: 2.3cm → 2.5cm (growth 0.2cm)
>
> Seedling #23: 2.2cm → 2.6cm (growth 0.4cm)
>
> Seedling #28: 2.3cm → 2.8cm (growth 0.5cm)

*— Same chapter, listing data plant by plant*

---

**Same emotional reactions on loop**

> Fang Yuan's eyes lit up.

*— Chapter 50, appears multiple times in this chapter; also Chapter 80*

> Fang Yuan took a deep breath.

*— Chapters 125, 275, and 300*

> Fang Yuan smiled.

*— Chapter 175, and throughout the book*

> Fang Yuan nodded earnestly.
>
> Fang Yuan listened earnestly.
>
> Fang Yuan nodded earnestly again.

*— Chapter 50*

---

**Plot moves at a glacial pace**

> - Chapter 1 (March): Fang Yuan gets the system, plants seeds
> - Chapter 10 (March 22): Tomatoes flower
> - Chapter 20 (May 1): First harvest
> - Chapter 30 (May 12): Applies for testing
> - Chapter 50 (June): Still recording how many millimeters seedlings grew each day
> - Chapter 100 (November): The agriculture association investigator finally shows up

100 chapters, roughly 250,000 characters, covering 8 months of story time. A significant chunk of that is spent on daily watering routines and measurement logs.

---

## 📊 By the numbers

| Metric | Value |
| ------ | ----- |
| Total chapters | 320 (none missing) |
| Chinese characters | ~**780,000** |
| Total characters (incl. punctuation/spaces) | ~1,118,000 |
| Average per chapter | ~2,400 characters |
| Volumes | 7 |
| Outline files | Master outline + pacing plan + per-volume (detailed outline / beat sheet / timeline) |
| Generation tool | Claude Code |

---

## 📂 Project structure

```
.
├── 大纲/ (outlines)
│   ├── 总纲.md              # Master outline, volume breakdown, core settings
│   ├── 爽点规划.md           # Hook pacing plan
│   ├── 第1卷-详细大纲.md     # Per-volume detailed outline
│   ├── 第1卷-节拍表.md       # Per-volume beat sheet
│   ├── 第1卷-时间线表.md     # Per-volume timeline
│   ├── ...                   # 7 volumes, 3 files each
├── 正文/ (chapters)
│   ├── 第0001章.md
│   ├── 第0002章.md
│   ├── ...
│   └── 第0320章.md
├── README.md
├── README_EN.md
├── 微信.png                  # WeChat support
└── 支付宝.jpg                # Alipay support
```

> ⚠️ The novel text is in Chinese. There is no English translation.

---

## 🎯 Why open-source this

### If you just want to read a story

It's a complete farming/power-fantasy web novel — system, face-slapping, romance, grand finale. Not great writing, but readable. After all, an AI wrote it.

### If you follow AI

I think people generally fall into two camps on AI writing:

- "AI can write anything now, authors are doomed" — overreacting
- "AI writing is obviously AI writing, nothing to worry about" — underestimating it

The reality: AI *can* produce 780,000 characters with a complete structure and a readable story. But it *can't* write well — padding, templating, inconsistent characterization, these problems persist from start to finish. This is the actual level of current top-tier models. No hype, no hate.

### If you build AI

Long context ≠ long-range quality. The problems exposed across 780,000 characters aren't things you fix by making the model bigger. They're architectural bottlenecks. Worth thinking about.

---

## 🔬 How to read

- **For the story**: Start from `正文/第0001章.md` and go in order (Chinese only)
- **To evaluate AI's planning ability**: Read `大纲/总纲.md` first, then compare against the actual chapter execution

---

## ⚖️ License (unlocked by donations)

Creating this novel was not cheap. The AI API costs alone were substantial — not to mention the time spent on project setup, toolchain debugging, and generation supervision, none of which is factored in. The license is tiered — the more support comes in, the more freedom everyone gets.

### Current status: 🔒 All rights reserved

- **You may**: Read, share links, recommend to friends, write articles discussing and analyzing this project
- **You may not**: Copy chapter content, modify, create derivative works, distribute commercially or non-commercially — none of it

Want to actually use the text? Read on — the license auto-upgrades when cumulative donations hit certain thresholds.

### 📈 License upgrade path

| Cumulative donations | License | What you can do |
| -------------------- | ------- | --------------- |
| **0 – 599 CNY** | 🔒 All rights reserved | Read, share links, discuss |
| **600 CNY** (covers only 45% of API costs) | 📝 **CC BY-NC-SA 4.0** | Copy, modify, create derivatives — but must attribute + non-commercial only + share alike |
| **1200 CNY** (covers only 90% of API costs, excluding any time/labor) | 🔓 **CC BY 4.0** | Do whatever you want — commercial use, modifications, anything. Only requirement: attribution |

### What happens when a threshold is reached?

On the day cumulative donations hit a tier, I'll update the license in this file. You can also reach out with a donation screenshot to confirm the current license status.

> 💡 This mechanism is itself part of the experiment: how much is an AI-generated work worth? That's for you to decide.

---

### ☕ Support this project

<p align="center">
  <img src="微信.png" width="200" alt="WeChat">

<img src="支付宝.jpg" width="200" alt="Alipay">
</p>

<p align="center"><em>WeChat / Alipay, any amount</em></p>

<p align="center"><strong>Current total: 0 / 1200 CNY</strong>  |  <strong>600 CNY</strong> to go until CC BY-NC-SA 4.0</p>

---

## 🙋 FAQ

**Q: How was it generated?**
A: Using Claude Code — project setup, outline planning, chapter-by-chapter generation, all done by the AI.

**Q: Why a web novel?**
A: Because web novels are the genre that tests sustained output the hardest: hundreds of chapters, hundreds of thousands of characters, multiple plot threads, characters that need to stay consistent across the whole run. These are exactly where AI is most likely to slip up.

---

<p align="center">
  <strong>If this made you think, help spread the word — Star ⭐ or share</strong>
</p>

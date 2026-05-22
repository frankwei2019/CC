# Constraints Checklist

Apply to EVERY shot prompt. Non-negotiable.

## Technical Constraints

- [ ] 9:16 竖屏比例
- [ ] 10 秒总时长
- [ ] 24 帧
- [ ] 高画质

## Content Constraints (Children's Education)

- [ ] 无恐怖/惊悚元素
- [ ] 无暴力/打斗场景
- [ ] 无救护车/医院等紧张医疗场景
- [ ] 无成人复杂情绪（嫉妒、仇恨、绝望）
- [ ] 正能量结尾（坚持、诚实、友善、智慧）
- [ ] 角色对话点题，非旁白说教
- [ ] 对话 3-5 句，口语化短句，每句 ≤20 字，能在 1-2 秒内说完不卡壳，适合儿童

## Style Constraints

- [ ] 中国古风卡通风格
- [ ] 儿童绘本风格
- [ ] 色彩明亮温暖
- [ ] 欢快活泼的氛围
- [ ] 角色形象可爱、表情夸张但不恐怖

## Audio/Subtitle Constraints

- [ ] 无 BGM（用户后期在剪映添加）
- [ ] 提示词开头固定写：「严格按提示词生成分镜和对话配音，无字幕」
- [ ] 无日语/英语文字或配音

## Seedance Negative Cues

Add to prompts when relevant:

| Failure Mode | Negative Cue |
|-------------|-------------|
| Motion corruption | 无抖动、无晃动、无变形、无弹性扭曲 |
| Style drift | 保持中国古风卡通风格、不变为写实/日漫/3D |
| Character mutation | 保持角色形象完全不变、无换脸 |
| Body artifacts | 无多余手指、无变形手脚 |
| Background changes | 背景保持不变、无额外物体出现 |

## Pre-Output Final Check

1. Quick scan: Any forbidden element present?
2. Benchmark match: Does specificity match 欣喜若狂 level?
3. Constraint pass: All checkboxes above are ✅
4. Dialogue check: Is the idiom explained by a character in dialogue?

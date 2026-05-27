# Prompt Formulas & Vocabulary

## The Proven Formula

From the user's own analysis of 37 videos:

```
[开场事件] + [角色冲突/情绪反应] + [具体动作细节] + [对话4-8句] + [结尾点题成语]
```

## Seedance 2.0 Five-Dimensional Architecture

Layer this onto the base formula for technical precision:

```
主体 + 动作细节 + 场景环境 + 光影色调 + 镜头运镜 + 视觉风格 + 画质 + 约束条件
```

## Camera & Shot Vocabulary

| Type | Use | Avoid |
|------|-----|-------|
| Shot size | 特写、近景、中景、全景、远景 | "放大" "缩小" |
| Movement | 缓慢推镜、平稳横移、环绕拍摄、固定镜头、跟拍 | "动态镜头" |
| Speed | 慢动作、2-5%缓慢推进、平稳 | "快" "猛" |
| Angle | 平视、俯角、仰角、45度俯瞰 | "酷的角度" |
| Lens feel | 广角、标准镜头、长焦压缩感 | (don't omit) |

## Lighting & Color

| Type | Terms |
|------|-------|
| Light source | 自然光、柔光、侧光、逆光、暖黄光、金色阳光 |
| Quality | 柔和、温暖、明亮、斑驳光影 |
| Mood | 温馨、欢快、宁静、阳光灿烂 |

## Fixed Style Anchor

Apply to every prompt:
```
中国古风卡通，儿童绘本风格，色彩明亮温暖，欢快活泼的氛围
```

## Fixed Prompt Header

Every Seedance prompt MUST start with this line:

```
严格按提示词生成分镜和对话配音，无字幕
```

## Fixed Technical Specs

```
高画质，9:16 竖屏，10秒，24帧
```

## The 6 Success Laws

Extracted from `seedance制作.txt`:

1. **有具体情节/故事线** — Mini-story with beginning/middle/end, not just a scene
2. **角色有明确情绪反应** — Emotions drive visuals: ecstatic, flipped over, crying
3. **视觉细节具体** — "鼻青脸肿" "蓝色眼泪飞溅" concrete, not abstract
4. **口语化对话，4-8句** — "你看号号给我发奖状了！" "太好了太好了！" "加油！" natural speech, distributed across shots
5. **有梗/网络参考** — "我要验牌" 运镜、哆啦A梦哭脸 cultural anchors
6. **正能量结尾** — Perseverance, correcting mistakes, learning lessons

## Failure Lesson: 呕心沥血 (1117 plays)

- 120救护车场景太紧张，不适合儿童
- 典故讲解偏说教，缺乏角色互动
- → Rule: No tense scenarios, no lecturing

## Action Description Quality Gate

Compare against benchmark standard:

| Weak | Strong |
|------|--------|
| 龙虾爬石头 | 龙虾手脚并用爬石头，两次滑下来摔得四脚朝天、鼻青脸肿 |
| 菠萝猫哭了 | 菠萝猫张大嘴巴像哆啦A梦一样，大颗蓝色眼泪飞溅，闪闪发光 |
| 菠萝猫很高兴 | 菠萝猫欣喜若狂地敲门，一边做"我要验牌"飞牌动作，奖状旋转飞出 |

Strong versions specify: body parts, motion trajectory, visual effects, emotional intensity.

## Time-Segment Output Format

Final Seedance prompts are labeled by time range, not shot number. The user copies and pastes directly into Seedance.

```
【0-Xs】
[full prompt body]

【Xs-Ys】
[full prompt body]

...
```

Time-segment pacing rules (from constraints.md):
- **0-3s**: Ultra-short hook lines, total ≤20 字
- **3-7s**: Main dialogue development, lines can be slightly longer
- **7-10s**: Closing segment, total ≤16 字, must leave breathing room

对话每句必须标注说话角色，格式：「角色名："对话内容"」

# RIN — 角色固定提示词与复现规范 v1.2

修订日期：2026-10-07。目标：在不同发色、发型、表情、服装和场景中，依靠脸型与五官关系保持同一个 RIN。

本次按用户要求解除发色、发型、刘海和发饰的永久身份约束。继续使用当前母图中的五官；此前 A/B/C 草案的眼型或挑染方案没有被定稿。

## 最快的使用方式

每次生成时提供本版 `RIN_母参考图.png`，使用下方「核心提示词」，再追加当前场景。母图是视觉身份的主要依据，文字补充规则。仅使用名字或文字不能保证复现。

在可以读取这两个项目文件的会话里，可以直接说：

> 按 RIN v1.2 母图和固定提示词还原 RIN。场景：……；表情：……；发色与发型：……；服装：……；镜头：……；画幅：……。生成后检查脸型、眼型、眉眼关系、鼻嘴比例和识别痣。

如果新会话不能读取母图，需要重新附上母图。场景留空时，默认采用近正面、平静表情、黑色哥特服饰和简洁背景。

## 1. 参考图的优先级

1. `RIN_母参考图.png`：本版主要五官身份与画风参考；图中的粉色长发是默认造型，是由原版大幅正面肖像规范化得到的单张肖像。
2. `references/RIN_三视角参考.png`：辅助理解转头后的脸部和眼型投影；其中的头发仅展示默认造型；不覆盖正面母图。
3. `references/RIN_五官检查图.png`：从标准母图截取的检查图，便于核对眼睛、痣、鼻嘴和眉眼关系，未重画这些部位。
4. `tests/`：场景测试记录，可用来检查效果，不能自动成为新的身份标准。
5. `originals/`：原版材料备份。原版正面存在额外眼下深色点，本版已按原文字规则统一为一颗痣。

三视角参考中的饰物细节与左右布置有生成变化，不作为精确首饰设计图。需要忠实复现默认饰物时，依据正面母图单独核查。

本版母图保留了原始肖像的轻微头部倾斜，不是严格正交的工程测量图。所有结构判断以图中整体关系为准，不从这张图臆造毫米尺寸或固定的人体比例。

## 2. 永久身份规则

| 项目 | 必须保持的特征 | 允许的自然变化 |
| --- | --- | --- |
| 年龄印象 | 成年女性，约 20–22 岁 | 表情与精神状态变化 |
| 脸型 | 小巧柔和的心形脸，下半脸收窄，细致下颌，小而柔和的尖下巴 | 随转头、透视与表情改变投影 |
| 眼睛 | 大而偏横向的杏仁形二次元眼，母图中的眼距、外眼角形状和浓密上睫毛结构 | 睁闭程度、视线方向、表情引起的变化 |
| 虹膜 | 玫瑰绯红色，深红外环、较亮玫瑰色内层，大瞳孔和精细纹理 | 光照引起的亮度与高光位置变化 |
| 眉毛 | 纤细眉形、柔和弧度，以及母图中的眉眼距离和相对位置 | 随表情升降；眉色可与当次发色协调 |
| 鼻嘴 | 很小而细致的鼻子，小巧浅玫瑰色嘴唇，母图的相对位置与大小 | 张嘴、微笑、侧面投影 |
| 皮肤 | 白皙、带柔和中性粉色底调 | 环境光与自然腮红变化 |
| 唯一识别痣 | 角色自身左眼外半部下方的一颗小深色痣 | 当对应皮肤被遮挡或转到不可见侧时，可以不可见 |

### 痣的侧别与位置

- 永远位于角色自身左侧。正面看，位于画面右侧眼睛下方。
- 位置以标准母图中它相对外眼角、下眼睑的关系为准，不使用「眼下 8–10 mm」定位。
- 不水平翻转角色，不在另一侧复制或补一颗痣。
- 转头时跟随同一块面部皮肤投影；不能为了让它可见而搬到近侧脸颊。
- 头发、手或角度可以合理遮挡痣，但对应皮肤清晰可见时应保留。

### 可变造型：头发、服装与饰物

默认造型是玫瑰粉长发和轻薄刘海，搭配黑色哥特／地雷系服饰、黑色发带蝴蝶结、心形与十字饰物、黑色心形扣项圈。

发色、发型、发长、刘海分区、发饰和服装均可按场景改变。可以换成黑色短发、银色长发、露额头的束发等，不以头发是否相同判断角色身份。改变造型时，应保持脸部轮廓和五官形状、间距及相对比例。

这些是默认穿搭，不是必须每次穿戴的脸部身份特征。可以换衣服、取下项圈或发饰，但仍应凭脸型、眼型、眉眼关系、鼻嘴比例和识别痣认出 RIN。

本版未定稿身高、全身比例、背面发型和完整服装结构。需要精确全身设计时，先补充并确认设定，不能把一次生成的猜测自动设为永久规则。

## 3. 可直接复用的核心提示词

附上标准母图后使用。核心身份段尽量保留，只替换场景段。

```text
REFERENCE ROLE
Reference image 1 is RIN's canonical facial identity and illustration style.
Reproduce this same established adult anime character, age 20–22.
Use the reference as the authority for proportions and design.

FACIAL IDENTITY
Preserve her small soft heart-shaped face, tapered lower jaw and softly pointed chin;
her elongated almond eye shape and original eye spacing;
crimson-rose irises with dark ruby outer rims and delicate rose inner texture;
clustered dense upper eyelashes, thin rose eyebrows, very small nose,
and small softly glossy pale rose mouth.
Preserve her facial proportions and the relative placement of her eyebrows,
eyes, nose, mouth, jaw and chin.
Hair color, hairstyle, hair length, bangs and accessories are styling variables.
Follow the current scene's hair instructions rather than copying the reference hair.
Do not change her facial geometry to match a different hairstyle.
If no hair change is requested, use her default rose-pink long-haired look.

SIGNATURE MARK
Exactly one tiny dark beauty mark beneath the outer half of HER OWN LEFT EYE.
In a frontal view this is the eye on the VIEWER'S RIGHT.
Match its anatomical position to the reference.
Keep it on the same anatomical side through head turns.
Show it whenever that patch of skin is visible; allow natural occlusion.
Do not mirror her or add a mark to her right cheek.

STYLE
Match the reference's intricate fine-line 2D Japanese anime illustration,
soft layered painterly shading, luminous iris detail, delicate individual hair strands,
and restrained glossy highlights.
Lighting may change. Preserve her crimson-rose iris identity unless explicitly requested otherwise.
Hair color is independently changeable and is not a facial identity cue.

CONSISTENCY
Keep the same underlying facial design while adapting naturally to perspective
and expression. Hair color, hairstyle, bangs, clothing, pose, background and lighting may change.
Do not redesign or age the character.
No additional facial dots, photorealism, 3D rendering, chibi proportions,
watermark, text or collage unless explicitly requested.

CURRENT SCENE
Scene: ...
Expression: ...
Pose / head angle: ...
Hair color, hairstyle, length and bangs: ...
Outfit and accessories: ...
Lighting: ...
Framing and aspect ratio: ...
```

### 参考图较多时

明确指定每张图的用途，例如：

```text
Image 1: canonical RIN identity and illustration style.
Image 2: supporting head-turn geometry only.
Image 3: hairstyle or outfit reference only; do not borrow its face.
If references conflict, preserve RIN's facial identity from image 1.
```

不要把多张不同脸型的漂亮肖像一起当作身份标准，也不要把场景测试图逐轮替换为新母图。

## 4. 已验证的场景写法

### 日光、微笑、换衣服

```text
RIN is beside a cafe window in daylight.
Near-frontal close head-and-shoulders portrait, direct gaze,
with a small relaxed closed-mouth smile.
She wears a simple ivory knitted crew-neck sweater.
Remove her choker, earrings and hair ribbons, while preserving her hair structure.
Soft neutral natural daylight and a gently blurred pale cafe background.
Keep her face large and unobstructed.
```

### 夜景、转头、困倦表情

```text
RIN is by an apartment window at night in a black oversized hoodie.
Head-and-shoulders portrait in a moderate three-quarter turn,
with her nose pointing to the viewer's left, showing her own left cheek.
Gentle sleepy expression with relaxed eyelids, preserving her original eye design.
Retain her black ribbon hair accessories and heart choker.
Blurred pink city lights outside, soft facial fill light,
and restrained pink rim light along the hair.
Keep her face large and unobstructed.
```

## 5. 每次出图后的验收

| 检查项 | 通过条件 |
| --- | --- |
| 整体身份 | 与标准母图并排看，仍能认出同一个 RIN |
| 脸型 | 没有变成更圆的幼态脸、明显更长的脸或宽下颌 |
| 眼型与眼距 | 保持原结构；表情和透视变化合理 |
| 鼻嘴 | 大小、形状和位置关系没有被重新设计 |
| 眉眼关系 | 眉形及基础眉眼距离与母图一致；表情变化合理 |
| 五官比例 | 眼睛、鼻子、嘴和下巴的相对位置保持；不因新发型重设计脸 |
| 发色与发型 | 符合当次造型要求；没有要求时使用默认粉色长发 |
| 痣 | 对应皮肤可见时保留一颗，位于角色自身左眼下，右脸无新增痣 |
| 画风 | 保持细腻线条与柔和层次，未明显简化或变成写实／3D |
| 任务内容 | 衣服、场景、表情和画幅符合当次要求 |

在原始分辨率下放大查看眼下区域；不能仅凭缩略图判断小痣缺失。

### 修正策略

- 只有痣、单个饰物等局部问题：优先请求局部修改，并明确保持其余画面不变。
- 脸型、眼型或鼻嘴比例已经明显偏离：重新以标准母图生成，减少同时变化的因素。
- 所有调整都回到标准母图核对，避免连续修改产生累积漂移。
- 不合格输出不进入标准参考或未来训练素材。

局部修正的提示词模板：

```text
Image 1 is the edit target; image 2 is the canonical RIN identity reference.
Change only [specific defect] in image 1 to match image 2.
Preserve the rest of image 1: face proportions, eyes, nose, mouth,
hair, expression, clothing, lighting, background and composition.
```

## 6. 后续助手的执行规则

用户说「还原 RIN」时：

1. 读取本版固定提示词，并实际查看当前 `RIN_母参考图.png`，不能只凭对话记忆猜脸。
2. 将标准母图作为图像生成的视觉输入，不把文件存在于项目中等同于已经传给模型。
3. 在固定身份和画风规则下，按用户要求修改发色、发型、场景、服装、表情与镜头。
4. 查看生成结果并按验收表检查；局部问题修正后再次核查。
5. 缺少标准母图时，请用户重新提供。不要悄悄重新创造一个「类似 RIN」的脸。
6. 一般发色、发型、场景和穿搭可以自行推进。改变永久五官身份、删除或移动痣、显著改脸型／眼型／眉眼关系／鼻嘴比例，或首次定稿重要但未定义的全身设定时，才请用户确认。

## 7. 本版验证范围与升级条件

本版保留标准母图、三视角辅助、五官检查图及原有三项测试，补齐 40 张独立参考：8 套全身穿搭、8 个复杂场景、8 种发型、8 种情绪和 8 个复合组合。发型组的裁切已修正，并加入完全露额造型。各图查看了整图及放大脸部；检查记录见 `RIN_扩充验收记录.md`。

同一雨夜街头组合的提示词与输入参考，额外独立生成三次，连同 C01 共四个输出全部保留。主要脸型、眼型、绯红虹膜和自身左眼下痣在人工检查中保持，嘴部、眼睛张开程度、配饰及构图仍有变化。这只是四个样本的检查，没有统计成功率，也不能保证任意模型或新会话都得到完全相同的图。详见 `RIN_重复复现检查.md`。

严格 90° 侧面、背面、极端表情、远景小脸、多角色同框和连续镜头仍未系统验证。本版没有训练专属模型。若未来需要大量连续生产，可在选定的模型与设置下扩充重复测试，再决定是否训练角色 LoRA 或采用专属角色模型。

仅使用名字、文字或固定 seed 不能建立完整的角色身份约束。当前实际采用的流程是标准母图作为视觉输入，配合固定五官描述、明确辅助图职责，并在输出后检查与修正。

## 8. 方法参考

- [Toon Boom：Character Model Sheets](https://learn.toonboom.com/modules/character-design/topic/character-model-sheets)：多角度与表情设定图作为角色权威依据。
- [OpenAI：Image prompting](https://developers.openai.com/api/docs/guides/image-prompting)：明确参考图用途，评估身份保持，并通过重复请求检查一致性。
- [OpenAI：Image generation](https://developers.openai.com/api/docs/guides/image-generation)：跨多次生成的角色一致性仍有局限。
- [Midjourney：Seeds](https://docs.midjourney.com/hc/en-us/articles/32604356340877-Seeds)：seed 不能跨不同提示词保存角色身份。
- [DreamBooth 原始项目](https://dreambooth.github.io/) 与 [Diffusers：LoRA](https://huggingface.co/docs/diffusers/main/en/training/lora)：后续专属角色训练的可选路线。

## 9. v1.2 完整参考集与调用

参考编号：O01–O08 穿搭，S01–S08 场景，H01–H08 发型，E01–E08 表情，C01–C08 复合组合。R01–R03 是重复测试输出，不替代母图。

全身采用本批一致的成年纤细体态，以 `outfits/O01_哥特蕾丝.png` 为暂定体态参考。身高、精确头身比例、胸腰臀数值、背面和服装工程结构未定稿；不从示例臆造数值或视为用户批准的永久设定。

复用时始终以母图负责五官与画风；挑选的图只负责明确指定的头发、衣服、情绪或场景。需要本批体态时，指定 O01 只负责身形。辅助图之间发生冲突时，脸部回到母图，当次造型以用户要求为准。避免把多张图都当作面部身份标准。

快速调用见 `RIN_调用模板.md`；可搜索图册见 `RIN_参考图册.html`；全部编号与提示词见索引及 JSON 文件。新会话若不能读取本项目，应附上母图与固定提示词，再附必要的造型参考。

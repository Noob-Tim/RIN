# RIN 重复复现检查 · v1.2

## 输入和方法

2026-10-07，以 C01「黑短发雨夜街头」的完全相同提示词和参考图，在内置图像生成中独立请求三次，得到 R01–R03。加上最初 C01，共四个输出。三个追加输出没有修改、挑选或丢弃，也没有把 C01 作为输入进行复制。

输入图顺序相同：图 1 标准母图（五官身份与画风）；图 2 O01（暂定体态）。全部使用透明背景关闭的设置。未指定 seed，生成工具没有暴露可固定的模型版本或更详细的采样参数；不能声称是所有底层参数均锁定的实验。

## 人工观察

| 输出 | 五官与痣 | 可见差异 |
| --- | --- | --- |
| C01 | 心形脸、杏仁眼、绯红虹膜与自身左眼下痣保留 | 头部轻倾；红心耳饰、街景与伞面为初次输出 |
| R01 | 主要脸型、眼型、绯红虹膜与同侧单颗痣保留 | 嘴略张，头部角度、发丝与人物大小有变化 |
| R02 | 主要脸型、眼型、绯红虹膜与同侧痣保留 | 眼睑和嘴部细节不同；耳饰、项链与伞形改变 |
| R03 | 主要脸型、眼型、绯红虹膜与同侧痣保留 | 头更接近正面；街景位置、服饰小件与伞面改变 |

各图脸部在全身画幅中较小，放大裁切会比近景母图更柔和，不能据此要求相同的高频纹理。检查图见 `gallery/RIN_R_五官对照.png`，整图对照见 `gallery/RIN_R_总览.jpg`。

## 可得出的结论

在这四个具体输出中，标准母图＋固定五官描述能够在黑短发、街头穿搭和复杂雨夜场景下保留主要身份结构；画面构图与细节仍会变化。四个样本只构成小样本观察，没有建立成功率，也不能外推为所有场景或未来模型都稳定成功。

实际使用时继续保留母图作为视觉输入，生成后检查五官与痣；人物重要的项目优先采用编辑已有合格图，再增加变化因素。头发相同、服装相同或仅写角色名字，都不能替代脸部检查。

## 可重跑资料

原图和提示词均见 `RIN_扩充提示词.json` 的 `repeat_tests`。下方为四次共用的完整提示词：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Complex rainy neon shopping street, puddles, storefront awnings, bicycles and distant passerby silhouettes. RIN with blue-black chin-length bob and wispy bangs, slate bomber over white tee and charcoal cargo trousers, holding clear umbrella. Full figure crown to sneakers with margins in foreground, occupying 80% image height; lightly annoyed expression, brows drawn a little together and closed lips. Near-frontal head, neutral soft face fill amid blue-magenta night light. Vertical 2:3, readable detailed face, rich environment.
Reference image 2: provisional adult BODY proportions only. Do NOT copy its clothes, hair, jewelry or expression. Canonical face remains image 1. Follow the scene's hairstyle, outfit and mood exactly. No choker unless requested. Full-body framing: figure no larger than 84% of canvas height, complete crown and shoe soles with empty margins.
```

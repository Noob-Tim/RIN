# RIN — Character Face Identity Prompt

用途：与母参考图一起使用，尽量保持同一个虚拟二次元角色的五官、脸型、发型与识别点一致。

---

## 1. 永久固定角色档案（不要改）

```text
RIN — FIXED FACE IDENTITY

Young adult anime girl, apparent age 20–22.

FACE SHAPE:
small soft heart-shaped face,
slightly narrow lower face,
delicate tapered jawline,
small softly pointed chin,
subtle youthful cheek fullness.

EYES:
large almond-shaped Japanese anime eyes,
slightly downturned outer corners,
consistent medium-wide eye spacing,
crimson-rose irises,
dark ruby outer iris ring,
rose-pink inner gradient,
large dark pupils,
distinct crystalline star-like highlights,
long dense upper eyelashes,
delicate lower lashes.

SIGNATURE BEAUTY MARK:
one tiny dark beauty mark located directly beneath
the outer half of her LEFT eye,
approximately 8–10 mm visually below the lower eyelid.
This beauty mark is a permanent identifying feature.
Never remove it.
Never move it.
Never add additional beauty marks.

EYEBROWS:
thin and softly curved,
low gentle arch,
dusty rose-pink color.

NOSE:
very small delicate anime nose,
short subtle bridge,
tiny softly defined nose tip.

MOUTH:
small delicate mouth,
subtle cupid's bow,
slightly fuller lower lip,
pale rose-pink color,
soft glossy highlight.

SKIN:
very fair porcelain skin,
soft neutral-pink undertone,
subtle blush beneath both eyes.

HAIR FRAMING:
pastel rose-pink hair,
airy layered bangs,
center bangs separated into irregular thin strands,
two longer face-framing locks,
left face-framing lock slightly longer than right,
soft strands occasionally crossing forehead and cheeks.

FIXED COLOR IDENTITY:
pastel rose-pink hair,
crimson-pink eyes,
porcelain skin,
black accessories.

IDENTITY RULE:
RIN must always have the exact same facial identity.

Preserve:
face width-to-height ratio,
jaw shape,
chin shape,
eye size,
eye shape,
eye spacing,
iris pattern,
eyebrow position,
nose position,
mouth size and position,
beauty mark position,
hairline,
bang structure.

Do NOT reinterpret her facial anatomy between images.
Do NOT redesign her eyes.
Do NOT change her beauty mark.
Do NOT significantly change her bangs.

She must look like the SAME anime character
drawn in different poses, expressions, outfits and environments.
```

---

## 2. Identity Lock（每次生成都原样附加）

```text
[IDENTITY LOCK]

This is RIN, the exact same established character shown in the reference image.

Preserve her canonical facial identity and character design with maximum consistency.
Do not reinterpret, redesign, age, or alter her facial structure.

Her face shape, eye geometry, iris design, eye spacing, jawline,
nose, mouth, bangs, hairline, hair color, skin tone and beauty mark position
must remain visually identical to the canonical reference.

The tiny beauty mark beneath the outer half of her LEFT eye is mandatory.
Never move it, remove it, mirror it, or add another beauty mark.

The viewer must immediately recognize her as the exact same character,
only illustrated at a different moment.

Character identity takes priority over pose, clothing, background and lighting.
```

---

## 3. 固定画风（建议保留）

```text
premium Japanese anime illustration,
strongly stylized 2D anime appearance,
clean delicate line art,
precise facial linework,
highly detailed crystalline anime eyes,
rich professional cel shading,
soft gradient shading layered over cel shading,
detailed individual hair strands,
controlled glossy highlights,
subtle bloom,
cinematic anime lighting,
high-end anime character key visual,
not photorealistic,
not 3D,
not western cartoon.
```

---

## 4. 每次只改这里：Current Scene

```text
[CURRENT SCENE]

RIN is ...
Expression: ...
Pose: ...
Outfit: black gothic / jirai-kei inspired ...
Background: ...
Lighting: ...
Camera: close-up portrait / head-and-shoulders / 3/4 view ...
Aspect ratio: 1:1 profile picture.
```

示例：

```text
[CURRENT SCENE]

RIN is sitting beside a bedroom window at night,
resting her cheek on one hand,
looking directly at the viewer,
with a gentle sleepy expression.

She is wearing an oversized black gothic hoodie.
Pink neon city lights glow outside the window.
Soft crimson rim light illuminates her pastel pink hair.

Close-up head-and-shoulders portrait,
slightly elevated camera angle,
1:1 profile picture composition.
```

---

## 5. 使用规则

1. 每次生成都同时提供母参考图。
2. “永久固定角色档案”和 “Identity Lock” 尽量不要修改措辞。
3. 只在 Current Scene 中修改表情、动作、服装、镜头和场景。
4. 如果模型开始漂脸，优先减少场景复杂度，并强化 reference image / exact same character / beauty mark position。
5. 不要同时给多张风格差异很大的参考图，以免身份特征被平均化。


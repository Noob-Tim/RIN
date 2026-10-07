# RIN v1.1 生成提示词记录

日期：2026-10-07。所有图像均通过内置图像生成方式制作。标准图以原版母图为输入；三视角图和场景测试以标准正面图为输入。

> 以下正面、三视角、T01 与 T02 提示词是 v1.0 的历史生成记录。当前复现应使用 v1.1 固定提示词，其中发色、发型和刘海已改为可变造型。

## 标准正面图

```text
Use case: identity-preserve.
Asset type: RIN v1.0 canonical single frontal reference portrait for repeated character reproduction.
Input image 1 is the original RIN design sheet. The LARGE FRONT PORTRAIT IN THE TOP-LEFT is the authority for facial design. Other panels only provide supporting details; do not blend their faces.
Primary request: faithfully extract and reproduce this exact young adult anime woman as ONE clean head-and-shoulders FRONT portrait, with the full crown of the hair visible and balanced space around the head. Remove all collage panels, labels, borders and typography. This is a design normalization, not a new character.
Preserve the delicate small soft heart-shaped face; tapered jaw and softly pointed chin; large elongated almond anime eyes with the same eye spacing and soft slightly lowered outer corners; rich crimson-rose irises with dark ruby rims and rose inner details; long dense upper lashes; thin dusty rose eyebrows; very small nose; small pale rose glossy mouth. Match the original face rather than making a generic anime beauty. Age remains adult 20–22.
Preserve long airy pastel rose-pink hair, irregular layered transparent wispy bangs, the recognizable central forehead opening and fine crossing strands, and two face-framing locks. Preserve the original black gothic ribbon hair accessories, silver heart and cross earrings, and black heart-buckle choker in their original relative placement.
ONE deliberate correction: exactly ONE tiny dark beauty mark beneath the outer half of HER OWN LEFT EYE, which is the eye on the VIEWER'S RIGHT in this front-facing portrait. Preserve the small mark under the viewer-right eye; remove the extraneous dark dot beneath the viewer-left eye. No additional freckles or facial marks. Do not mirror the character.
Head upright, direct gaze, relaxed neutral slightly parted lips, no dramatic expression.
Neutral soft studio daylight, restrained highlights and blush, reduce the original strong red/pink light cast so basic colors and facial structure can be read. Keep the elegant glossy, extremely fine detailed 2D Japanese anime rendering of the original: fine rose linework, soft layered painterly shading, delicate eyelash clusters and hair strands, intricate luminous iris texture. Do not switch to flat simplified cel shading, realistic photography, 3D or chibi.
Plain light warm gray background. Single portrait only. No text, no diagrams, no measurement marks.
```

## 三视角辅助图

```text
Use case: identity-preserve.
Asset type: RIN v1.0 supporting head-turn reference sheet, not a redesign.
Image 1 is the CANONICAL RIN frontal portrait and is the sole authority for identity, proportions and art style.
Create one clean wide character reference sheet containing THREE equally sized isolated head-and-shoulders portraits of the SAME character in one row, each on plain light warm-gray background with clear separation, no text, no labels, no decorative frames.
From left to right:
1) RIN at approximately 45 degrees with her nose pointing to the VIEWER'S LEFT, presenting her OWN LEFT cheek and left eye; her SINGLE beauty mark remains visible beneath the outer half of her own left eye.
2) RIN front-facing, looking directly at viewer; beauty mark beneath outer half of viewer-right eye only.
3) RIN at approximately 45 degrees with her nose pointing to the VIEWER'S RIGHT, presenting her OWN RIGHT cheek. The beauty mark remains physically on the FAR cheek under her OWN LEFT eye, and should be hidden or barely visible with perspective; NEVER relocate it onto the visible right cheek.
All three views are the same adult woman age20–22 with the exact face from image1. Preserve original small heart-shaped face, tapered lower jaw and softly pointed chin, elongated almond eyes and their original spacing, rose-crimson irises with dark rims, clustered dense upper lashes, thin rose eyebrows, tiny nose, small pale rose mouth, porcelain neutral-pink skin. Preserve the recognizable airy layered rose-pink hair and irregular wispy bangs with central forehead opening and face-framing locks. Keep original black ribbons and heart/cross jewelry and choker. Rotate the features and accessories coherently, do not horizontally flip the image.
Same neutral relaxed expression and soft studio daylight in all three views. Match the detailed, elegant glossy 2D anime fine linework and layered painterly shading of image1. No simplified anime style, no chibi, no photorealism.
Fit each entire head including hair crown and accessories within its own panel with generous margins. Fine strands may vary with projection but hairstyle landmarks must remain consistent. Anatomical LEFT and RIGHT always mean the character's own sides. Exactly one beauty mark per character when the marked side is visible; none on her right cheek. No additional facial dots, symbols or freckles.
```

## 两项场景测试共同使用的身份段

```text
Use case: identity-preserve.
Reference image 1 is RIN's canonical facial identity and rendering style. Reproduce the same adult anime woman age 20–22, preserving the reference's soft heart-shaped face, tapered jaw and chin, elongated almond eye shape and spacing, crimson-rose irises with dark ruby rims, clustered upper lashes, thin rose eyebrows, tiny nose and small glossy rose mouth. Preserve her airy long rose-pink hair, irregular translucent wispy bangs with the recognizable central forehead opening, hairline and face-framing locks.
Exactly ONE tiny beauty mark beneath the outer half of HER OWN LEFT EYE, located on VIEWER'S RIGHT in a frontal view. Keep the mark on the same anatomical side through turns; show it whenever that patch of skin is visible. No mark on her right cheek. No additional facial dots. No horizontal mirroring.
Keep the intricate fine-line glossy 2D Japanese anime rendering of the reference, layered soft painterly shading, luminous iris detail and delicate hair strands. Facial proportions adapt naturally to perspective and expression while keeping the same identity. Clothing, background, expression and light may change. Do not redesign or age the character. No text, watermark, collage, photorealism, 3D or chibi.
```

## T01 日光场景完整提示词

```text
Use case: identity-preserve.
Reference image 1 is RIN's canonical facial identity and rendering style. Reproduce the same adult anime woman age 20–22, preserving the reference's soft heart-shaped face, tapered jaw and chin, elongated almond eye shape and spacing, crimson-rose irises with dark ruby rims, clustered upper lashes, thin rose eyebrows, tiny nose and small glossy rose mouth. Preserve her airy long rose-pink hair, irregular translucent wispy bangs with the recognizable central forehead opening, hairline and face-framing locks.
Exactly ONE tiny beauty mark beneath the outer half of HER OWN LEFT EYE, located on VIEWER'S RIGHT in a frontal view. Keep the mark on the same anatomical side through turns; show it whenever that patch of skin is visible. No mark on her right cheek. No additional facial dots. No horizontal mirroring.
Keep the intricate fine-line glossy 2D Japanese anime rendering of the reference, layered soft painterly shading, luminous iris detail and delicate hair strands. Facial proportions adapt naturally to perspective and expression while keeping the same identity. Clothing, background, expression and light may change. Do not redesign or age the character. No text, watermark, collage, photorealism, 3D or chibi.

CURRENT SCENE: RIN is beside a cafe window in daylight. Near-frontal close head-and-shoulders portrait, direct gaze and a small relaxed CLOSED-MOUTH smile. She wears a simple ivory knitted crew-neck sweater instead of gothic clothing. Remove the black choker, earrings and hair ribbons for this test; preserve the original hair structure and identity. Soft natural neutral daylight and a gently blurred pale cafe background, no pink neon or red cast. Keep the face large and unobstructed. This tests recognition without the usual gothic accessories.
```

## T02 夜景场景完整提示词

```text
Use case: identity-preserve.
Reference image 1 is RIN's canonical facial identity and rendering style. Reproduce the same adult anime woman age 20–22, preserving the reference's soft heart-shaped face, tapered jaw and chin, elongated almond eye shape and spacing, crimson-rose irises with dark ruby rims, clustered upper lashes, thin rose eyebrows, tiny nose and small glossy rose mouth. Preserve her airy long rose-pink hair, irregular translucent wispy bangs with the recognizable central forehead opening, hairline and face-framing locks.
Exactly ONE tiny beauty mark beneath the outer half of HER OWN LEFT EYE, located on VIEWER'S RIGHT in a frontal view. Keep the mark on the same anatomical side through turns; show it whenever that patch of skin is visible. No mark on her right cheek. No additional facial dots. No horizontal mirroring.
Keep the intricate fine-line glossy 2D Japanese anime rendering of the reference, layered soft painterly shading, luminous iris detail and delicate hair strands. Facial proportions adapt naturally to perspective and expression while keeping the same identity. Clothing, background, expression and light may change. Do not redesign or age the character. No text, watermark, collage, photorealism, 3D or chibi.

CURRENT SCENE: RIN is by an apartment window at night in a black oversized hoodie. Head-and-shoulders portrait in a moderate three-quarter turn with her nose pointing to VIEWER'S LEFT, showing HER OWN LEFT cheek and its one beauty mark. She has a gentle sleepy expression with slightly relaxed eyelids; preserve the underlying original eye shape. Retain black ribbon hair accessories and the default heart choker. Outside are blurred pink city lights. Soft neutral fill light makes facial features readable, with restrained pink rim light along the hair. Keep the face large, no hands obscuring it.
```


## T03 换发色与发型的完整提示词

```text
Use case: identity-preserve.
Asset type: RIN facial identity test across two radically different hair looks. This is not a facial redesign.
Image 1 is current canonical RIN and the authority ONLY for her facial identity and fine detailed 2D anime rendering. Hair is a changeable styling choice.
Create ONE clean wide comparison with TWO matched head-and-shoulders portraits of exactly the same RIN. Same near-frontal head angle, gaze, relaxed neutral expression, face scale, pale warm-gray background, soft neutral daylight, plain charcoal crew-neck top. No text, labels, border ornaments, choker, jewelry, bows, makeup symbols or facial piercings.
LEFT PORTRAIT: her default long airy rose-pink hair and wispy bangs from the reference.
RIGHT PORTRAIT: CHANGE ONLY the styling to glossy natural BLACK chin-length bob, with a clear side part and long side-swept fringe tucked behind the ears so eyebrows, eyes, face contour and the eye-under mark remain unobstructed. No pink strands, colored streaks or default long-hair silhouette. Eyebrow color may harmonize with the black hair, but eyebrow shape, thickness and position stay the same.
BOTH: preserve her EXACT original small soft heart-shaped face, lower-face width and length, tapered jaw and softly pointed chin; original elongated almond eye outlines, inner and outer canthi, eye spacing and iris size; original dense upper eyelash structure; same crimson-rose iris colors and fine texture; same delicate thin eyebrow geometry and eyebrow-to-eye relationship; same very small nose and its position; same small softly glossy pale rose mouth, cupid's bow, lower lip fullness and placement; same nose-to-mouth-to-chin spacing. Adult age20–22.
Exactly ONE tiny dark beauty mark beneath the outer half of HER OWN LEFT EYE, which is the eye on VIEWER RIGHT of EACH portrait. Copy its anatomical location from reference. Do not lose, enlarge, relocate or mirror it; no mark on her right cheek.
The black haircut must not cause a different face, shorter chin, rounder cheeks, narrow eyes, mature nose, changed eye spacing or different mouth. Keep ALL facial geometry identical between the two portraits. The LEFT and RIGHT women must clearly be the same person with different hairstyles.
Match the reference's extremely fine linework, layered soft painterly anime shading, luminous iris details and restrained glossy highlights. No photorealism, chibi, 3D or simplified generic anime face. Fit both complete heads within their panel with useful margins.

```

# v1.2 完整参考集：40 张成图与 3 张重复测试

使用内置图像生成，主要母图负责身份与画风。下列记录区分初始计划、复用模板与本次实际修改操作。输入图职责与操作顺序均在 JSON 中保留。修正前的局部发型版本由最终图替代，不作为现行身份标准。

## O01 哥特蕾丝

文件：`outfits/O01_哥特蕾丝.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Front-facing relaxed standing full-body portrait. Default rose-pink long loose hair, wispy bangs, black ribbons. Black lace long-sleeved blouse with ribbon necktie, black high-waisted knee-length layered skirt, opaque black tights, black buckle ankle boots, modest silver heart earrings and heart choker. Neutral calm mouth, direct gaze, arms relaxed and both hands visible. Solid pale warm-gray seamless background, soft studio lighting, faint contact shadow only. Vertical 2:3, entire crown and shoe soles inside frame with margins. One woman only. Make her face detailed and large enough to recognize.
```

实际操作 1：此前生成或构图修正。参考职责：generated_images/exec-af5f5430-590c-41e6-a083-b30600d5e584.png（该次修改的输入图；若为修正前版本，已由最终图替代）；RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Image 1 is the edit target, image 2 is canonical RIN facial identity. Change ONLY framing and backdrop: pull camera back enough that the ENTIRE hair crown and ALL boot soles appear, with 8% empty margin above crown and below soles. Figure should occupy at most 84% image height. Keep one identical RIN, exact face, one beauty mark below her own left eye (viewer right), expression, outfit, hands, body shape and all clothing details from image 1. Plain flat pale warm-gray single-color background, faint contact shadow only. Vertical 2:3. Do not cut crown or shoes. Do not redesign anything.
```

## O02 日常针织

文件：`outfits/O02_日常针织.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Default rose-pink long hair loosely draped, no ribbons. Ivory cable-knit cardigan over cream crew-neck top, dusty-blue straight-leg denim, low-top white sneakers, tiny silver studs, no choker. Relaxed standing, near-frontal head, gentle closed-mouth smile, hands relaxed. Solid pale oatmeal background, soft neutral studio light. Full body crown to soles with margins, vertical 2:3.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）；generated_images/exec-7cc71b8d-1ccd-4688-af1c-b116e43f893a.png（该次修改的输入图；若为修正前版本，已由最终图替代）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Default rose-pink long hair loosely draped, no ribbons. Ivory cable-knit cardigan over cream crew-neck top, dusty-blue straight-leg denim, low-top white sneakers, tiny silver studs, no choker. Relaxed standing, near-frontal head, gentle closed-mouth smile, hands relaxed. Solid pale oatmeal background, soft neutral studio light. Full body crown to soles with margins, vertical 2:3.
Reference image 2: provisional adult BODY proportions and standing scale only, NOT clothing, hair or face authority. Image 1 remains the face authority. Framing: figure occupies 84% of canvas height; generous empty margin above crown and below shoe soles. Entire head and shoes visible.
```

## O03 街头机能

文件：`outfits/O03_街头机能.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Default rose-pink long hair, wispy bangs, no ribbons. Slate oversized hooded bomber, charcoal cargo trousers, gray-black chunky sneakers, small crossbody utility bag, no choker. Calm confident standing, one hand in jacket pocket and other hand relaxed, face near frontal. Solid muted blue-gray background, soft studio light. Full body crown to soles, vertical 2:3.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）；generated_images/exec-7cc71b8d-1ccd-4688-af1c-b116e43f893a.png（该次修改的输入图；若为修正前版本，已由最终图替代）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Default rose-pink long hair, wispy bangs, no ribbons. Slate oversized hooded bomber, charcoal cargo trousers, gray-black chunky sneakers, small crossbody utility bag, no choker. Calm confident standing, one hand in jacket pocket and other hand relaxed, face near frontal. Solid muted blue-gray background, soft studio light. Full body crown to soles, vertical 2:3.
Reference image 2: provisional adult BODY proportions and standing scale only, NOT clothing, hair or face authority. Image 1 remains the face authority. Framing: figure occupies 84% of canvas height; generous empty margin above crown and below shoe soles. Entire head and shoes visible.
```

## O04 通勤西装

文件：`outfits/O04_通勤西装.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Rose-pink straight long hair tucked behind ears. Elegant charcoal tailored blazer, matching straight trousers, cream blouse, black loafers, tiny silver studs, no choker. Adult poised front-facing standing, holding a slim closed folder at side, mild confident smile. Solid pale sage background, soft neutral light. Full body head to shoes with margins, vertical 2:3.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）；generated_images/exec-7cc71b8d-1ccd-4688-af1c-b116e43f893a.png（该次修改的输入图；若为修正前版本，已由最终图替代）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Rose-pink straight long hair tucked behind ears. Elegant charcoal tailored blazer, matching straight trousers, cream blouse, black loafers, tiny silver studs, no choker. Adult poised front-facing standing, holding a slim closed folder at side, mild confident smile. Solid pale sage background, soft neutral light. Full body head to shoes with margins, vertical 2:3.
Reference image 2: provisional adult BODY proportions and standing scale only, NOT clothing, hair or face authority. Image 1 remains the face authority. Framing: figure occupies 84% of canvas height; generous empty margin above crown and below shoe soles. Entire head and shoes visible.
```

## O05 运动休闲

文件：`outfits/O05_运动休闲.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Rose-pink high ponytail with wispy loose bangs, no ribbons. Dusty-rose zip track jacket over white sports tee, black tapered joggers, white trainers, no jewelry or choker. Energetic relaxed standing, hands at sides, slight smile, frontal head. Solid pale lavender background with soft studio light. Full body crown to soles with margins, vertical 2:3.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）；generated_images/exec-7cc71b8d-1ccd-4688-af1c-b116e43f893a.png（该次修改的输入图；若为修正前版本，已由最终图替代）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Rose-pink high ponytail with wispy loose bangs, no ribbons. Dusty-rose zip track jacket over white sports tee, black tapered joggers, white trainers, no jewelry or choker. Energetic relaxed standing, hands at sides, slight smile, frontal head. Solid pale lavender background with soft studio light. Full body crown to soles with margins, vertical 2:3.
Reference image 2: provisional adult BODY proportions and standing scale only, NOT clothing, hair or face authority. Image 1 remains the face authority. Framing: figure occupies 84% of canvas height; generous empty margin above crown and below shoe soles. Entire head and shoes visible.
```

## O06 晚宴长裙

文件：`outfits/O06_晚宴长裙.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Rose-pink low loose updo with a few face-framing strands. Deep wine-red modest square-neck satin ankle-length evening dress, slender black low heels, small silver earrings, no choker. Soft composed expression, elegant relaxed pose both hands visible, near-frontal head. Solid pale blush-beige background, gentle studio light revealing satin folds. Full body including shoes, vertical 2:3.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）；generated_images/exec-7cc71b8d-1ccd-4688-af1c-b116e43f893a.png（该次修改的输入图；若为修正前版本，已由最终图替代）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Rose-pink low loose updo with a few face-framing strands. Deep wine-red modest square-neck satin ankle-length evening dress, slender black low heels, small silver earrings, no choker. Soft composed expression, elegant relaxed pose both hands visible, near-frontal head. Solid pale blush-beige background, gentle studio light revealing satin folds. Full body including shoes, vertical 2:3.
Reference image 2: provisional adult BODY proportions only, NOT clothing, hair, accessories, expression or face authority. Image 1 remains the face authority. Follow current styling exactly, omit the choker if not requested. For full-body composition, figure occupies at most 84% of canvas height; empty margin above crown and below shoe soles.
```

## O07 和风日常

文件：`outfits/O07_和风日常.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Rose-pink long hair gathered into a loose side braid, wispy bangs. Dusty indigo floral yukata with ivory obi, traditional flat sandals, modest flower hairpin, no choker. Natural standing, hands held gently in front at waist, near-frontal calm face. Solid warm cream background, neutral studio light. Full body crown to soles with margins, vertical 2:3. Adult contemporary festival styling.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）；generated_images/exec-7cc71b8d-1ccd-4688-af1c-b116e43f893a.png（该次修改的输入图；若为修正前版本，已由最终图替代）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Rose-pink long hair gathered into a loose side braid, wispy bangs. Dusty indigo floral yukata with ivory obi, traditional flat sandals, modest flower hairpin, no choker. Natural standing, hands held gently in front at waist, near-frontal calm face. Solid warm cream background, neutral studio light. Full body crown to soles with margins, vertical 2:3. Adult contemporary festival styling.
Reference image 2: provisional adult BODY proportions only, NOT clothing, hair, accessories, expression or face authority. Image 1 remains the face authority. Follow current styling exactly, omit the choker if not requested. For full-body composition, figure occupies at most 84% of canvas height; empty margin above crown and below shoe soles.
```

## O08 冬日大衣

文件：`outfits/O08_冬日大衣.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Default rose-pink long hair, no ribbons. Camel knee-length wool coat over a cream turtleneck and charcoal straight trousers, burgundy scarf and brown flat ankle boots. Composed relaxed front standing, arms at sides, soft neutral expression. Solid pale icy-blue background, soft neutral studio lighting. Full body crown to soles, vertical 2:3.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）；generated_images/exec-7cc71b8d-1ccd-4688-af1c-b116e43f893a.png（该次修改的输入图；若为修正前版本，已由最终图替代）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Default rose-pink long hair, no ribbons. Camel knee-length wool coat over a cream turtleneck and charcoal straight trousers, burgundy scarf and brown flat ankle boots. Composed relaxed front standing, arms at sides, soft neutral expression. Solid pale icy-blue background, soft neutral studio lighting. Full body crown to soles, vertical 2:3.
Reference image 2: provisional adult BODY proportions only, NOT clothing, hair, accessories, expression or face authority. Image 1 remains the face authority. Follow current styling exactly, omit the choker if not requested. For full-body composition, figure occupies at most 84% of canvas height; empty margin above crown and below shoe soles.
```

## S01 雨夜霓虹街

文件：`scenes/S01_雨夜霓虹街.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Detailed rainy urban side street at night: wet tiled pavement, shop awnings, cables, neon reflections, parked bicycles and distant anonymous pedestrian silhouettes. RIN foreground waist-up in black raincoat holding clear umbrella in one hand. Default rose-pink long hair, gentle composed expression, head near frontal. Crimson eyes readable under soft neutral face fill, restrained blue-magenta rim lighting. Face is large, no umbrella edge obscures eyes or mark. Vertical 2:3, environment genuinely layered and detailed, not generic bokeh.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）；generated_images/exec-7cc71b8d-1ccd-4688-af1c-b116e43f893a.png（该次修改的输入图；若为修正前版本，已由最终图替代）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Detailed rainy urban side street at night: wet tiled pavement, shop awnings, cables, neon reflections, parked bicycles and distant anonymous pedestrian silhouettes. RIN foreground waist-up in black raincoat holding clear umbrella in one hand. Default rose-pink long hair, gentle composed expression, head near frontal. Crimson eyes readable under soft neutral face fill, restrained blue-magenta rim lighting. Face is large, no umbrella edge obscures eyes or mark. Vertical 2:3, environment genuinely layered and detailed, not generic bokeh.
Reference image 2: provisional adult BODY proportions only, NOT clothing, hair, accessories, expression or face authority. Image 1 remains the face authority. Follow current styling exactly, omit the choker if not requested. For full-body composition, figure occupies at most 84% of canvas height; empty margin above crown and below shoe soles.
```

## S02 日光咖啡馆

文件：`scenes/S02_日光咖啡馆.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Sunlit lived-in cafe with carved wooden tables, pastry counter, shelves, potted plants and reflections in large windows. RIN seated in foreground at a wooden table, three-quarter body composition, cream knitted sweater, default pink long hair, small closed-mouth smile, relaxed eyes. Both hands around a ceramic cup well below face. Head near frontal, face clear and detailed. Warm window light, neutral facial fill. Vertical 2:3, rich recognizable interior depth.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）；generated_images/exec-7cc71b8d-1ccd-4688-af1c-b116e43f893a.png（该次修改的输入图；若为修正前版本，已由最终图替代）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Sunlit lived-in cafe with carved wooden tables, pastry counter, shelves, potted plants and reflections in large windows. RIN seated in foreground at a wooden table, three-quarter body composition, cream knitted sweater, default pink long hair, small closed-mouth smile, relaxed eyes. Both hands around a ceramic cup well below face. Head near frontal, face clear and detailed. Warm window light, neutral facial fill. Vertical 2:3, rich recognizable interior depth.
Reference image 2: provisional adult BODY proportions only, NOT clothing, hair, accessories, expression or face authority. Image 1 remains the face authority. Follow current styling exactly, omit the choker if not requested. For full-body composition, figure occupies at most 84% of canvas height; empty margin above crown and below shoe soles.
```

## S03 车站候车

文件：`scenes/S03_车站候车.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Busy contemporary railway station platform with rails, canopy beams, benches, ticket machines and small anonymous distant commuters. RIN foreground from knees upward in charcoal jacket, cream top and jeans, default rose-pink hair. Holding a folded paper ticket in one hand, calm thoughtful face, head turned slightly toward viewer left showing her own left cheek. Cool morning skylight and soft face fill. Vertical 2:3, no readable words or brand signage; face remains detailed.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）；generated_images/exec-7cc71b8d-1ccd-4688-af1c-b116e43f893a.png（该次修改的输入图；若为修正前版本，已由最终图替代）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Busy contemporary railway station platform with rails, canopy beams, benches, ticket machines and small anonymous distant commuters. RIN foreground from knees upward in charcoal jacket, cream top and jeans, default rose-pink hair. Holding a folded paper ticket in one hand, calm thoughtful face, head turned slightly toward viewer left showing her own left cheek. Cool morning skylight and soft face fill. Vertical 2:3, no readable words or brand signage; face remains detailed.
Reference image 2: provisional adult BODY proportions only, NOT clothing, hair, accessories, expression or face authority. Image 1 remains the face authority. Follow current styling exactly, omit the choker if not requested. For full-body composition, figure occupies at most 84% of canvas height; empty margin above crown and below shoe soles.
```

## S04 旧书店

文件：`scenes/S04_旧书店.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Cozy intricate secondhand bookshop with towering mismatched shelves, stacks of books, ladder, reading lamp and narrow aisles. RIN foreground sitting on wooden stool, visible knees upward, dusty-blue cardigan over white blouse, long default pink hair. Open book resting on lap, one hand touching page, quiet absorbed expression, face near frontal glancing slightly down. Warm lamplight with soft balanced face light. Vertical 2:3; books have no legible lettering.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）；generated_images/exec-7cc71b8d-1ccd-4688-af1c-b116e43f893a.png（该次修改的输入图；若为修正前版本，已由最终图替代）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Cozy intricate secondhand bookshop with towering mismatched shelves, stacks of books, ladder, reading lamp and narrow aisles. RIN foreground sitting on wooden stool, visible knees upward, dusty-blue cardigan over white blouse, long default pink hair. Open book resting on lap, one hand touching page, quiet absorbed expression, face near frontal glancing slightly down. Warm lamplight with soft balanced face light. Vertical 2:3; books have no legible lettering.
Reference image 2: provisional adult BODY proportions only, NOT clothing, hair, accessories, expression or face authority. Image 1 remains the face authority. Follow current styling exactly, omit the choker if not requested. For full-body composition, figure occupies at most 84% of canvas height; empty margin above crown and below shoe soles.
```

## S05 玻璃温室

文件：`scenes/S05_玻璃温室.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Lush glass conservatory with iron roof ribs, hanging vines, layered tropical leaves, patterned walkway and pots. RIN foreground thighs-up in white midi dress and light sage cardigan, default pink long hair, peaceful mild smile. One hand gently touching a leaf below shoulder level, head near frontal. Dappled afternoon sun and neutral facial fill, deep botanical environment, vertical 2:3.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）；generated_images/exec-7cc71b8d-1ccd-4688-af1c-b116e43f893a.png（该次修改的输入图；若为修正前版本，已由最终图替代）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Lush glass conservatory with iron roof ribs, hanging vines, layered tropical leaves, patterned walkway and pots. RIN foreground thighs-up in white midi dress and light sage cardigan, default pink long hair, peaceful mild smile. One hand gently touching a leaf below shoulder level, head near frontal. Dappled afternoon sun and neutral facial fill, deep botanical environment, vertical 2:3.
Reference image 2: provisional adult BODY proportions only, NOT clothing, hair, accessories, expression or face authority. Image 1 remains the face authority. Follow current styling exactly, omit the choker if not requested. For full-body composition, figure occupies at most 84% of canvas height; empty margin above crown and below shoe soles.
```

## S06 海边落日

文件：`scenes/S06_海边落日.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Rocky seaside promenade at sunset, ocean waves, distant harbor, textured stone railings, seagulls and layered sunset clouds. RIN foreground knees-up wearing navy light jacket over cream top and pale skirt, default pink hair moved gently by sea breeze. Thoughtful wistful expression with small closed mouth, near-frontal head. Warm sunset rim light plus neutral face fill preserving red irises. Vertical 2:3, rich scenery and readable face.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）；generated_images/exec-7cc71b8d-1ccd-4688-af1c-b116e43f893a.png（该次修改的输入图；若为修正前版本，已由最终图替代）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Rocky seaside promenade at sunset, ocean waves, distant harbor, textured stone railings, seagulls and layered sunset clouds. RIN foreground knees-up wearing navy light jacket over cream top and pale skirt, default pink hair moved gently by sea breeze. Thoughtful wistful expression with small closed mouth, near-frontal head. Warm sunset rim light plus neutral face fill preserving red irises. Vertical 2:3, rich scenery and readable face.
Reference image 2: provisional adult BODY proportions only, NOT clothing, hair, accessories, expression or face authority. Image 1 remains the face authority. Follow current styling exactly, omit the choker if not requested. For full-body composition, figure occupies at most 84% of canvas height; empty margin above crown and below shoe soles.
```

## S07 冬夜集市

文件：`scenes/S07_冬夜集市.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Detailed winter night street market with wooden stalls, strings of lamps, steam from food stands, gentle snow and distant anonymous visitors. RIN foreground waist-up in camel coat, burgundy scarf and knit gloves, default pink long hair, gentle contented smile. Hands holding a warm cup below chest. Warm stalls and cool snow balanced with soft facial light. Eyes and left-under-eye mark visible. Vertical 2:3, rich background depth, no readable signage.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）；generated_images/exec-7cc71b8d-1ccd-4688-af1c-b116e43f893a.png（该次修改的输入图；若为修正前版本，已由最终图替代）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Detailed winter night street market with wooden stalls, strings of lamps, steam from food stands, gentle snow and distant anonymous visitors. RIN foreground waist-up in camel coat, burgundy scarf and knit gloves, default pink long hair, gentle contented smile. Hands holding a warm cup below chest. Warm stalls and cool snow balanced with soft facial light. Eyes and left-under-eye mark visible. Vertical 2:3, rich background depth, no readable signage.
Reference image 2: provisional adult BODY proportions only, NOT clothing, hair, accessories, expression or face authority. Image 1 remains the face authority. Follow current styling exactly, omit the choker if not requested. For full-body composition, figure occupies at most 84% of canvas height; empty margin above crown and below shoe soles.
```

## S08 创作工作室

文件：`scenes/S08_创作工作室.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Cluttered personal illustration studio with desk, tablet, sketches pinned to wall, shelves, brushes, lamp, plants and window overlooking rooftops. RIN foreground seated in an office chair, knees-up, relaxed cream tee and loose charcoal trousers, default pink long hair loosely tucked behind ears. Thoughtful slightly tired face near frontal, one hand holding stylus above desk, other relaxed. Warm desk light plus blue evening window light, neutral face fill. Vertical 2:3, no readable text.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）；generated_images/exec-7cc71b8d-1ccd-4688-af1c-b116e43f893a.png（该次修改的输入图；若为修正前版本，已由最终图替代）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Cluttered personal illustration studio with desk, tablet, sketches pinned to wall, shelves, brushes, lamp, plants and window overlooking rooftops. RIN foreground seated in an office chair, knees-up, relaxed cream tee and loose charcoal trousers, default pink long hair loosely tucked behind ears. Thoughtful slightly tired face near frontal, one hand holding stylus above desk, other relaxed. Warm desk light plus blue evening window light, neutral face fill. Vertical 2:3, no readable text.
Reference image 2: provisional adult BODY proportions only, NOT clothing, hair, accessories, expression or face authority. Image 1 remains the face authority. Follow current styling exactly, omit the choker if not requested. For full-body composition, figure occupies at most 84% of canvas height; empty margin above crown and below shoe soles.
```

## H01 黑色齐下巴短发

文件：`hairstyles/H01_黑色齐下巴短发.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Near-frontal head-and-shoulders portrait, same calm neutral closed-mouth expression as reference. Hair styling: deep blue-black chin-length bob, softly inward-curving ends, light split bangs leaving some forehead visible. Plain charcoal crew-neck top, no choker, no earrings, no ribbons. Pale warm-gray solid background and soft neutral studio light. Tight square composition, entire hair crown inside frame, face occupies about half image height. Both eyes, nose, mouth, chin and own-left beauty mark clearly visible. Hair stays off eye/mark. Match canonical face exactly while changing only styling.
FRAMING: medium bust portrait, entire crown and hairstyle silhouette visible with empty top margin. No cropped head. The face remains canonical.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Near-frontal head-and-shoulders portrait, same calm neutral closed-mouth expression as reference. Hair styling: deep blue-black chin-length bob, softly inward-curving ends, light split bangs leaving some forehead visible. Plain charcoal crew-neck top, no choker, no earrings, no ribbons. Pale warm-gray solid background and soft neutral studio light. Tight square composition, entire hair crown inside frame, face occupies about half image height. Both eyes, nose, mouth, chin and own-left beauty mark clearly visible. Hair stays off eye/mark. Match canonical face exactly while changing only styling.
```

实际操作 2：replace。参考职责：hairstyles/H01_黑色齐下巴短发.png（该次修改的输入图；若为修正前版本，已由最终图替代）；RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Image 1 is the edit target. Image 2 is RIN's canonical FACIAL identity and fine-line painterly anime style. Change the composition ONLY, keeping the original styling.
Reframe by pulling the camera back and reducing the current subject scale to about 70%. Center her as a medium bust portrait in a NEW square canvas. Show her COMPLETE head, entire hair crown, all silhouette edges and upper shoulders with a clearly EMPTY 10% margin above the highest hair strand. Reconstruct missing crown naturally. No part of the hairstyle may touch or be cut by the top or side borders.
Do not change hairstyle design or hair color at all.
Preserve the same small soft heart face, tapered jaw, soft pointed chin, elongated almond eyes and original spacing, crimson-rose irises, thin brows, tiny nose, small glossy pale rose mouth, neutral calm expression, and fair skin. Exactly ONE tiny dark mark below the outer half of HER OWN LEFT EYE, viewer RIGHT. Preserve its side and position. Preserve the charcoal crew-neck shirt and plain pale warm-gray background with soft neutral lighting. No choker, no new jewelry, no text, no collage. Do not age or redesign RIN.
```

## H02 银白短层次发

文件：`hairstyles/H02_银白短层次发.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Near-frontal head-and-shoulders portrait, same calm neutral closed-mouth expression as reference. Hair styling: silver-white short layered pixie cut with soft wispy fringe, ears partly visible, feminine adult silhouette. Plain charcoal crew-neck top, no choker, no earrings, no ribbons. Pale warm-gray solid background and soft neutral studio light. Tight square composition, entire hair crown inside frame, face occupies about half image height. Both eyes, nose, mouth, chin and own-left beauty mark clearly visible. Hair stays off eye/mark. Match canonical face exactly while changing only styling.
FRAMING: medium bust portrait, entire crown and hairstyle silhouette visible with empty top margin. No cropped head. The face remains canonical.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Near-frontal head-and-shoulders portrait, same calm neutral closed-mouth expression as reference. Hair styling: silver-white short layered pixie cut with soft wispy fringe, ears partly visible, feminine adult silhouette. Plain charcoal crew-neck top, no choker, no earrings, no ribbons. Pale warm-gray solid background and soft neutral studio light. Tight square composition, entire hair crown inside frame, face occupies about half image height. Both eyes, nose, mouth, chin and own-left beauty mark clearly visible. Hair stays off eye/mark. Match canonical face exactly while changing only styling.
```

实际操作 2：replace。参考职责：hairstyles/H02_银白短层次发.png（该次修改的输入图；若为修正前版本，已由最终图替代）；RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Image 1 is the edit target. Image 2 is RIN's canonical FACIAL identity and fine-line painterly anime style. Change the composition ONLY, keeping the original styling.
Reframe by pulling the camera back and reducing the current subject scale to about 70%. Center her as a medium bust portrait in a NEW square canvas. Show her COMPLETE head, entire hair crown, all silhouette edges and upper shoulders with a clearly EMPTY 10% margin above the highest hair strand. Reconstruct missing crown naturally. No part of the hairstyle may touch or be cut by the top or side borders.
Do not change hairstyle design or hair color at all.
Preserve the same small soft heart face, tapered jaw, soft pointed chin, elongated almond eyes and original spacing, crimson-rose irises, thin brows, tiny nose, small glossy pale rose mouth, neutral calm expression, and fair skin. Exactly ONE tiny dark mark below the outer half of HER OWN LEFT EYE, viewer RIGHT. Preserve its side and position. Preserve the charcoal crew-neck shirt and plain pale warm-gray background with soft neutral lighting. No choker, no new jewelry, no text, no collage. Do not age or redesign RIN.
```

## H03 粉色高马尾

文件：`hairstyles/H03_粉色高马尾.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Near-frontal head-and-shoulders portrait, same calm neutral closed-mouth expression as reference. Hair styling: rose-pink high ponytail with gently flowing length, wispy separated bangs and two fine face-framing strands. Plain charcoal crew-neck top, no choker, no earrings, no ribbons. Pale warm-gray solid background and soft neutral studio light. Tight square composition, entire hair crown inside frame, face occupies about half image height. Both eyes, nose, mouth, chin and own-left beauty mark clearly visible. Hair stays off eye/mark. Match canonical face exactly while changing only styling.
FRAMING: medium bust portrait, entire crown and hairstyle silhouette visible with empty top margin. No cropped head. The face remains canonical.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Near-frontal head-and-shoulders portrait, same calm neutral closed-mouth expression as reference. Hair styling: rose-pink high ponytail with gently flowing length, wispy separated bangs and two fine face-framing strands. Plain charcoal crew-neck top, no choker, no earrings, no ribbons. Pale warm-gray solid background and soft neutral studio light. Tight square composition, entire hair crown inside frame, face occupies about half image height. Both eyes, nose, mouth, chin and own-left beauty mark clearly visible. Hair stays off eye/mark. Match canonical face exactly while changing only styling.
```

实际操作 2：replace。参考职责：hairstyles/H03_粉色高马尾.png（该次修改的输入图；若为修正前版本，已由最终图替代）；RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Image 1 is the edit target. Image 2 is RIN's canonical FACIAL identity and fine-line painterly anime style. Change the composition ONLY, keeping the original styling.
Reframe by pulling the camera back and reducing the current subject scale to about 70%. Center her as a medium bust portrait in a NEW square canvas. Show her COMPLETE head, entire hair crown, all silhouette edges and upper shoulders with a clearly EMPTY 10% margin above the highest hair strand. Reconstruct missing crown naturally. No part of the hairstyle may touch or be cut by the top or side borders.
Make the full high ponytail including the elevated crown tie point and its long flowing length visible, with free space above and beside it. Keep hair rose-pink and the existing facial design.
Preserve the same small soft heart face, tapered jaw, soft pointed chin, elongated almond eyes and original spacing, crimson-rose irises, thin brows, tiny nose, small glossy pale rose mouth, neutral calm expression, and fair skin. Exactly ONE tiny dark mark below the outer half of HER OWN LEFT EYE, viewer RIGHT. Preserve its side and position. Preserve the charcoal crew-neck shirt and plain pale warm-gray background with soft neutral lighting. No choker, no new jewelry, no text, no collage. Do not age or redesign RIN.
```

## H04 栗棕侧编发

文件：`hairstyles/H04_栗棕侧编发.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Near-frontal head-and-shoulders portrait, same calm neutral closed-mouth expression as reference. Hair styling: chestnut-brown long hair in one loose side braid over shoulder, airy parted fringe and soft baby hairs. Plain charcoal crew-neck top, no choker, no earrings, no ribbons. Pale warm-gray solid background and soft neutral studio light. Tight square composition, entire hair crown inside frame, face occupies about half image height. Both eyes, nose, mouth, chin and own-left beauty mark clearly visible. Hair stays off eye/mark. Match canonical face exactly while changing only styling.
FRAMING: medium bust portrait, entire crown and hairstyle silhouette visible with empty top margin. No cropped head. The face remains canonical.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Near-frontal head-and-shoulders portrait, same calm neutral closed-mouth expression as reference. Hair styling: chestnut-brown long hair in one loose side braid over shoulder, airy parted fringe and soft baby hairs. Plain charcoal crew-neck top, no choker, no earrings, no ribbons. Pale warm-gray solid background and soft neutral studio light. Tight square composition, entire hair crown inside frame, face occupies about half image height. Both eyes, nose, mouth, chin and own-left beauty mark clearly visible. Hair stays off eye/mark. Match canonical face exactly while changing only styling.
```

实际操作 2：replace。参考职责：hairstyles/H04_栗棕侧编发.png（该次修改的输入图；若为修正前版本，已由最终图替代）；RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Image 1 is the edit target. Image 2 is RIN's canonical FACIAL identity and fine-line painterly anime style. Change the composition ONLY, keeping the original styling.
Reframe by pulling the camera back and reducing the current subject scale to about 70%. Center her as a medium bust portrait in a NEW square canvas. Show her COMPLETE head, entire hair crown, all silhouette edges and upper shoulders with a clearly EMPTY 10% margin above the highest hair strand. Reconstruct missing crown naturally. No part of the hairstyle may touch or be cut by the top or side borders.
Do not change hairstyle design or hair color at all.
Preserve the same small soft heart face, tapered jaw, soft pointed chin, elongated almond eyes and original spacing, crimson-rose irises, thin brows, tiny nose, small glossy pale rose mouth, neutral calm expression, and fair skin. Exactly ONE tiny dark mark below the outer half of HER OWN LEFT EYE, viewer RIGHT. Preserve its side and position. Preserve the charcoal crew-neck shirt and plain pale warm-gray background with soft neutral lighting. No choker, no new jewelry, no text, no collage. Do not age or redesign RIN.
```

## H05 蓝黑露额长直发

文件：`hairstyles/H05_蓝黑长直发.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Near-frontal head-and-shoulders portrait, same calm neutral closed-mouth expression as reference. Hair styling: blue-black sleek long straight hair, gentle side part with forehead visible, one side tucked behind ear. Plain charcoal crew-neck top, no choker, no earrings, no ribbons. Pale warm-gray solid background and soft neutral studio light. Tight square composition, entire hair crown inside frame, face occupies about half image height. Both eyes, nose, mouth, chin and own-left beauty mark clearly visible. Hair stays off eye/mark. Match canonical face exactly while changing only styling.
FRAMING: medium bust portrait, entire crown and hairstyle silhouette visible with empty top margin. No cropped head. The face remains canonical.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Near-frontal head-and-shoulders portrait, same calm neutral closed-mouth expression as reference. Hair styling: blue-black sleek long straight hair, gentle side part with forehead visible, one side tucked behind ear. Plain charcoal crew-neck top, no choker, no earrings, no ribbons. Pale warm-gray solid background and soft neutral studio light. Tight square composition, entire hair crown inside frame, face occupies about half image height. Both eyes, nose, mouth, chin and own-left beauty mark clearly visible. Hair stays off eye/mark. Match canonical face exactly while changing only styling.
COMPOSITION PRIORITY: New medium bust composition, not the input portrait crop. Pull camera back to show ENTIRE hairstyle, complete hair crown with at least 10% empty top margin, all fringe, ear area and upper shoulders. No hairstyle edges cut at top. Single-color studio backdrop. Match face geometry, but do not copy input framing.
```

实际操作 2：replace。参考职责：hairstyles/H05_蓝黑长直发.png（该次修改的输入图；若为修正前版本，已由最终图替代）；RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Image 1 is the edit target. Image 2 is RIN's canonical FACIAL identity and fine-line painterly anime style. Change the composition ONLY, plus the explicitly requested swept-back fringe.
Reframe by pulling the camera back and reducing the current subject scale to about 70%. Center her as a medium bust portrait in a NEW square canvas. Show her COMPLETE head, entire hair crown, all silhouette edges and upper shoulders with a clearly EMPTY 10% margin above the highest hair strand. Reconstruct missing crown naturally. No part of the hairstyle may touch or be cut by the top or side borders.
Also change ONLY the fringe: a polished side-parted blue-black long hairstyle with ALL front hair combed away from the forehead and secured behind the ears. Completely bare forehead from brows to hairline; both entire eyebrows unobstructed. NO bangs, NO curtain fringe, NO loose strands crossing forehead, brows or eyes. Keep the original brow shape, original eye design and facial proportions from image 2; removing bangs must not redesign the face.
Preserve the same small soft heart face, tapered jaw, soft pointed chin, elongated almond eyes and original spacing, crimson-rose irises, thin brows, tiny nose, small glossy pale rose mouth, neutral calm expression, and fair skin. Exactly ONE tiny dark mark below the outer half of HER OWN LEFT EYE, viewer RIGHT. Preserve its side and position. Preserve the charcoal crew-neck shirt and plain pale warm-gray background with soft neutral lighting. No choker, no new jewelry, no text, no collage. Do not age or redesign RIN.
```

## H06 淡紫中长卷发

文件：`hairstyles/H06_淡紫中长卷发.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Near-frontal head-and-shoulders portrait, same calm neutral closed-mouth expression as reference. Hair styling: muted lavender shoulder-length softly wavy hair, airy curtain bangs revealing facial contour. Plain charcoal crew-neck top, no choker, no earrings, no ribbons. Pale warm-gray solid background and soft neutral studio light. Tight square composition, entire hair crown inside frame, face occupies about half image height. Both eyes, nose, mouth, chin and own-left beauty mark clearly visible. Hair stays off eye/mark. Match canonical face exactly while changing only styling.
FRAMING: medium bust portrait, entire crown and hairstyle silhouette visible with empty top margin. No cropped head. The face remains canonical.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Near-frontal head-and-shoulders portrait, same calm neutral closed-mouth expression as reference. Hair styling: muted lavender shoulder-length softly wavy hair, airy curtain bangs revealing facial contour. Plain charcoal crew-neck top, no choker, no earrings, no ribbons. Pale warm-gray solid background and soft neutral studio light. Tight square composition, entire hair crown inside frame, face occupies about half image height. Both eyes, nose, mouth, chin and own-left beauty mark clearly visible. Hair stays off eye/mark. Match canonical face exactly while changing only styling.
COMPOSITION PRIORITY: New medium bust composition, not the input portrait crop. Pull camera back to show ENTIRE hairstyle, complete hair crown with at least 10% empty top margin, all fringe, ear area and upper shoulders. No hairstyle edges cut at top. Single-color studio backdrop. Match face geometry, but do not copy input framing.
```

实际操作 2：replace。参考职责：hairstyles/H06_淡紫中长卷发.png（该次修改的输入图；若为修正前版本，已由最终图替代）；RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Image 1 is the edit target. Image 2 is RIN's canonical FACIAL identity and fine-line painterly anime style. Change the composition ONLY, keeping the original styling.
Reframe by pulling the camera back and reducing the current subject scale to about 70%. Center her as a medium bust portrait in a NEW square canvas. Show her COMPLETE head, entire hair crown, all silhouette edges and upper shoulders with a clearly EMPTY 10% margin above the highest hair strand. Reconstruct missing crown naturally. No part of the hairstyle may touch or be cut by the top or side borders.
Do not change hairstyle design or hair color at all.
Preserve the same small soft heart face, tapered jaw, soft pointed chin, elongated almond eyes and original spacing, crimson-rose irises, thin brows, tiny nose, small glossy pale rose mouth, neutral calm expression, and fair skin. Exactly ONE tiny dark mark below the outer half of HER OWN LEFT EYE, viewer RIGHT. Preserve its side and position. Preserve the charcoal crew-neck shirt and plain pale warm-gray background with soft neutral lighting. No choker, no new jewelry, no text, no collage. Do not age or redesign RIN.
```

## H07 蜂蜜金低盘发

文件：`hairstyles/H07_蜂蜜金低盘发.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Near-frontal head-and-shoulders portrait, same calm neutral closed-mouth expression as reference. Hair styling: honey-blonde low loosely pinned bun, face-framing wisps and open soft side part. Plain charcoal crew-neck top, no choker, no earrings, no ribbons. Pale warm-gray solid background and soft neutral studio light. Tight square composition, entire hair crown inside frame, face occupies about half image height. Both eyes, nose, mouth, chin and own-left beauty mark clearly visible. Hair stays off eye/mark. Match canonical face exactly while changing only styling.
FRAMING: medium bust portrait, entire crown and hairstyle silhouette visible with empty top margin. No cropped head. The face remains canonical.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Near-frontal head-and-shoulders portrait, same calm neutral closed-mouth expression as reference. Hair styling: honey-blonde low loosely pinned bun, face-framing wisps and open soft side part. Plain charcoal crew-neck top, no choker, no earrings, no ribbons. Pale warm-gray solid background and soft neutral studio light. Tight square composition, entire hair crown inside frame, face occupies about half image height. Both eyes, nose, mouth, chin and own-left beauty mark clearly visible. Hair stays off eye/mark. Match canonical face exactly while changing only styling.
COMPOSITION PRIORITY: New medium bust composition, not the input portrait crop. Pull camera back to show ENTIRE hairstyle, complete hair crown with at least 10% empty top margin, all fringe, ear area and upper shoulders. No hairstyle edges cut at top. Single-color studio backdrop. Match face geometry, but do not copy input framing.
```

## H08 酒红短狼尾

文件：`hairstyles/H08_酒红短狼尾.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Near-frontal head-and-shoulders portrait, same calm neutral closed-mouth expression as reference. Hair styling: dark wine-red short layered wolf cut reaching nape, feathered shag ends, light piecey bangs revealing eyes. Plain charcoal crew-neck top, no choker, no earrings, no ribbons. Pale warm-gray solid background and soft neutral studio light. Tight square composition, entire hair crown inside frame, face occupies about half image height. Both eyes, nose, mouth, chin and own-left beauty mark clearly visible. Hair stays off eye/mark. Match canonical face exactly while changing only styling.
FRAMING: medium bust portrait, entire crown and hairstyle silhouette visible with empty top margin. No cropped head. The face remains canonical.
```

实际操作 1：此前生成或构图修正。参考职责：RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Near-frontal head-and-shoulders portrait, same calm neutral closed-mouth expression as reference. Hair styling: dark wine-red short layered wolf cut reaching nape, feathered shag ends, light piecey bangs revealing eyes. Plain charcoal crew-neck top, no choker, no earrings, no ribbons. Pale warm-gray solid background and soft neutral studio light. Tight square composition, entire hair crown inside frame, face occupies about half image height. Both eyes, nose, mouth, chin and own-left beauty mark clearly visible. Hair stays off eye/mark. Match canonical face exactly while changing only styling.
COMPOSITION PRIORITY: New medium bust composition, not the input portrait crop. Pull camera back to show ENTIRE hairstyle, complete hair crown with at least 10% empty top margin, all fringe, ear area and upper shoulders. No hairstyle edges cut at top. Single-color studio backdrop. Match face geometry, but do not copy input framing.
```

实际操作 2：replace。参考职责：hairstyles/H08_酒红短狼尾.png（该次修改的输入图；若为修正前版本，已由最终图替代）；RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Image 1 is the edit target. Image 2 is RIN's canonical FACIAL identity and fine-line painterly anime style. Change the composition ONLY, keeping the original styling.
Reframe by pulling the camera back and reducing the current subject scale to about 70%. Center her as a medium bust portrait in a NEW square canvas. Show her COMPLETE head, entire hair crown, all silhouette edges and upper shoulders with a clearly EMPTY 10% margin above the highest hair strand. Reconstruct missing crown naturally. No part of the hairstyle may touch or be cut by the top or side borders.
Do not change hairstyle design or hair color at all.
Preserve the same small soft heart face, tapered jaw, soft pointed chin, elongated almond eyes and original spacing, crimson-rose irises, thin brows, tiny nose, small glossy pale rose mouth, neutral calm expression, and fair skin. Exactly ONE tiny dark mark below the outer half of HER OWN LEFT EYE, viewer RIGHT. Preserve its side and position. Preserve the charcoal crew-neck shirt and plain pale warm-gray background with soft neutral lighting. No choker, no new jewelry, no text, no collage. Do not age or redesign RIN.
```

## E01 温柔微笑

文件：`expressions/E01_温柔微笑.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Emotion portrait: gentle affectionate closed-mouth smile, eyes relaxed but open and retaining canonical almond design. Default rose-pink long hair and wispy bangs, simple black ribbon accents, charcoal crew-neck top, no choker or earrings. Near-frontal head-and-shoulders square portrait, full crown inside frame, face occupies about half image height. Plain pale warm-gray background, identical soft neutral studio light. Change facial muscles naturally for this emotion without redesigning the underlying face. Keep eyes and own-left mark readable. No text, emoji or expression symbols.
```

实际操作 1：new。参考职责：RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Emotion portrait: gentle affectionate closed-mouth smile, eyes relaxed but open and retaining canonical almond design. Default rose-pink long hair and wispy bangs, simple black ribbon accents, charcoal crew-neck top, no choker or earrings. Near-frontal head-and-shoulders square portrait, full crown inside frame, face occupies about half image height. Plain pale warm-gray background, identical soft neutral studio light. Change facial muscles naturally for this emotion without redesigning the underlying face. Keep eyes and own-left mark readable. No text, emoji or expression symbols.
CRITICAL EXPRESSION: Actively animate brows, eyelids and mouth for the requested emotion, not the input's neutral face. The underlying facial anatomy stays RIN. New medium-close bust composition with ENTIRE hair crown and black ribbons INSIDE the image. Leave clear empty space above hair (8% of height), shoulders visible. Plain studio backdrop. No forehead, mouth or hairstyle cropping.
```

## E02 开心笑出声

文件：`expressions/E02_开心笑出声.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Emotion portrait: natural delighted laughter with small open mouth, cheeks lifting, eyes narrowed a little but still visibly open with red irises; no huge cartoon mouth. Default rose-pink long hair and wispy bangs, simple black ribbon accents, charcoal crew-neck top, no choker or earrings. Near-frontal head-and-shoulders square portrait, full crown inside frame, face occupies about half image height. Plain pale warm-gray background, identical soft neutral studio light. Change facial muscles naturally for this emotion without redesigning the underlying face. Keep eyes and own-left mark readable. No text, emoji or expression symbols.
```

实际操作 1：new。参考职责：RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Emotion portrait: natural delighted laughter with small open mouth, cheeks lifting, eyes narrowed a little but still visibly open with red irises; no huge cartoon mouth. Default rose-pink long hair and wispy bangs, simple black ribbon accents, charcoal crew-neck top, no choker or earrings. Near-frontal head-and-shoulders square portrait, full crown inside frame, face occupies about half image height. Plain pale warm-gray background, identical soft neutral studio light. Change facial muscles naturally for this emotion without redesigning the underlying face. Keep eyes and own-left mark readable. No text, emoji or expression symbols.
CRITICAL EXPRESSION: Actively animate brows, eyelids and mouth for the requested emotion, not the input's neutral face. The underlying facial anatomy stays RIN. New medium-close bust composition with ENTIRE hair crown and black ribbons INSIDE the image. Leave clear empty space above hair (8% of height), shoulders visible. Plain studio backdrop. No forehead, mouth or hairstyle cropping.
```

## E03 惊讶

文件：`expressions/E03_惊讶.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Emotion portrait: sudden mild surprise, brows raised, eyes slightly widened, small softly rounded open mouth; retain original eye shape structure and facial proportions. Default rose-pink long hair and wispy bangs, simple black ribbon accents, charcoal crew-neck top, no choker or earrings. Near-frontal head-and-shoulders square portrait, full crown inside frame, face occupies about half image height. Plain pale warm-gray background, identical soft neutral studio light. Change facial muscles naturally for this emotion without redesigning the underlying face. Keep eyes and own-left mark readable. No text, emoji or expression symbols.
```

实际操作 1：new。参考职责：RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Emotion portrait: sudden mild surprise, brows raised, eyes slightly widened, small softly rounded open mouth; retain original eye shape structure and facial proportions. Default rose-pink long hair and wispy bangs, simple black ribbon accents, charcoal crew-neck top, no choker or earrings. Near-frontal head-and-shoulders square portrait, full crown inside frame, face occupies about half image height. Plain pale warm-gray background, identical soft neutral studio light. Change facial muscles naturally for this emotion without redesigning the underlying face. Keep eyes and own-left mark readable. No text, emoji or expression symbols.
CRITICAL EXPRESSION: Actively animate brows, eyelids and mouth for the requested emotion, not the input's neutral face. The underlying facial anatomy stays RIN. New medium-close bust composition with ENTIRE hair crown and black ribbons INSIDE the image. Leave clear empty space above hair (8% of height), shoulders visible. Plain studio backdrop. No forehead, mouth or hairstyle cropping.
```

## E04 克制生气

文件：`expressions/E04_克制生气.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Emotion portrait: restrained irritation, brows pulled inward slightly, eyes focused, small lips pressed together; no exaggerated caricature, no symbols. Default rose-pink long hair and wispy bangs, simple black ribbon accents, charcoal crew-neck top, no choker or earrings. Near-frontal head-and-shoulders square portrait, full crown inside frame, face occupies about half image height. Plain pale warm-gray background, identical soft neutral studio light. Change facial muscles naturally for this emotion without redesigning the underlying face. Keep eyes and own-left mark readable. No text, emoji or expression symbols.
```

实际操作 1：new。参考职责：RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Emotion portrait: restrained irritation, brows pulled inward slightly, eyes focused, small lips pressed together; no exaggerated caricature, no symbols. Default rose-pink long hair and wispy bangs, simple black ribbon accents, charcoal crew-neck top, no choker or earrings. Near-frontal head-and-shoulders square portrait, full crown inside frame, face occupies about half image height. Plain pale warm-gray background, identical soft neutral studio light. Change facial muscles naturally for this emotion without redesigning the underlying face. Keep eyes and own-left mark readable. No text, emoji or expression symbols.
CRITICAL EXPRESSION: Actively animate brows, eyelids and mouth for the requested emotion, not the input's neutral face. The underlying facial anatomy stays RIN. New medium-close bust composition with ENTIRE hair crown and black ribbons INSIDE the image. Leave clear empty space above hair (8% of height), shoulders visible. Plain studio backdrop. No forehead, mouth or hairstyle cropping.
```

## E05 难过含泪

文件：`expressions/E05_难过含泪.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Emotion portrait: sadness with moist eyes and one clear transparent tear trailing own right cheek, inner brows subtly lifted and small trembling closed mouth; tear is not a dark facial dot, eyes retain red iris detail. Default rose-pink long hair and wispy bangs, simple black ribbon accents, charcoal crew-neck top, no choker or earrings. Near-frontal head-and-shoulders square portrait, full crown inside frame, face occupies about half image height. Plain pale warm-gray background, identical soft neutral studio light. Change facial muscles naturally for this emotion without redesigning the underlying face. Keep eyes and own-left mark readable. No text, emoji or expression symbols.
```

实际操作 1：new。参考职责：RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Emotion portrait: sadness with moist eyes and one clear transparent tear trailing own right cheek, inner brows subtly lifted and small trembling closed mouth; tear is not a dark facial dot, eyes retain red iris detail. Default rose-pink long hair and wispy bangs, simple black ribbon accents, charcoal crew-neck top, no choker or earrings. Near-frontal head-and-shoulders square portrait, full crown inside frame, face occupies about half image height. Plain pale warm-gray background, identical soft neutral studio light. Change facial muscles naturally for this emotion without redesigning the underlying face. Keep eyes and own-left mark readable. No text, emoji or expression symbols.
CRITICAL EXPRESSION: Actively animate brows, eyelids and mouth for the requested emotion, not the input's neutral face. The underlying facial anatomy stays RIN. New medium-close bust composition with ENTIRE hair crown and black ribbons INSIDE the image. Leave clear empty space above hair (8% of height), shoulders visible. Plain studio backdrop. No forehead, mouth or hairstyle cropping.
```

## E06 害羞

文件：`expressions/E06_害羞.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Emotion portrait: bashful shy expression, soft pink blush, slightly lifted inner brows, small hesitant closed-mouth smile, eyes glancing a little sideways while head near frontal. Default rose-pink long hair and wispy bangs, simple black ribbon accents, charcoal crew-neck top, no choker or earrings. Near-frontal head-and-shoulders square portrait, full crown inside frame, face occupies about half image height. Plain pale warm-gray background, identical soft neutral studio light. Change facial muscles naturally for this emotion without redesigning the underlying face. Keep eyes and own-left mark readable. No text, emoji or expression symbols.
```

实际操作 1：new。参考职责：RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Emotion portrait: bashful shy expression, soft pink blush, slightly lifted inner brows, small hesitant closed-mouth smile, eyes glancing a little sideways while head near frontal. Default rose-pink long hair and wispy bangs, simple black ribbon accents, charcoal crew-neck top, no choker or earrings. Near-frontal head-and-shoulders square portrait, full crown inside frame, face occupies about half image height. Plain pale warm-gray background, identical soft neutral studio light. Change facial muscles naturally for this emotion without redesigning the underlying face. Keep eyes and own-left mark readable. No text, emoji or expression symbols.
CRITICAL EXPRESSION: Actively animate brows, eyelids and mouth for the requested emotion, not the input's neutral face. The underlying facial anatomy stays RIN. New medium-close bust composition with ENTIRE hair crown and black ribbons INSIDE the image. Leave clear empty space above hair (8% of height), shoulders visible. Plain studio backdrop. No forehead, mouth or hairstyle cropping.
```

## E07 认真坚定

文件：`expressions/E07_认真坚定.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Emotion portrait: quiet determination, steady direct gaze, slightly lowered brows and small composed closed mouth; delicate face and eyes remain feminine and canonical. Default rose-pink long hair and wispy bangs, simple black ribbon accents, charcoal crew-neck top, no choker or earrings. Near-frontal head-and-shoulders square portrait, full crown inside frame, face occupies about half image height. Plain pale warm-gray background, identical soft neutral studio light. Change facial muscles naturally for this emotion without redesigning the underlying face. Keep eyes and own-left mark readable. No text, emoji or expression symbols.
```

实际操作 1：new。参考职责：RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Emotion portrait: quiet determination, steady direct gaze, slightly lowered brows and small composed closed mouth; delicate face and eyes remain feminine and canonical. Default rose-pink long hair and wispy bangs, simple black ribbon accents, charcoal crew-neck top, no choker or earrings. Near-frontal head-and-shoulders square portrait, full crown inside frame, face occupies about half image height. Plain pale warm-gray background, identical soft neutral studio light. Change facial muscles naturally for this emotion without redesigning the underlying face. Keep eyes and own-left mark readable. No text, emoji or expression symbols.
CRITICAL EXPRESSION: Actively animate brows, eyelids and mouth for the requested emotion, not the input's neutral face. The underlying facial anatomy stays RIN. New medium-close bust composition with ENTIRE hair crown and black ribbons INSIDE the image. Leave clear empty space above hair (8% of height), shoulders visible. Plain studio backdrop. No forehead, mouth or hairstyle cropping.
```

## E08 困倦

文件：`expressions/E08_困倦.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Emotion portrait: sleepy heavy eyelids but both eyes still open enough to reveal red irises, relaxed brows, small barely parted mouth; no yawning or closed eyes. Default rose-pink long hair and wispy bangs, simple black ribbon accents, charcoal crew-neck top, no choker or earrings. Near-frontal head-and-shoulders square portrait, full crown inside frame, face occupies about half image height. Plain pale warm-gray background, identical soft neutral studio light. Change facial muscles naturally for this emotion without redesigning the underlying face. Keep eyes and own-left mark readable. No text, emoji or expression symbols.
```

实际操作 1：new。参考职责：RIN_母参考图.png（主要五官身份与画风）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Emotion portrait: sleepy heavy eyelids but both eyes still open enough to reveal red irises, relaxed brows, small barely parted mouth; no yawning or closed eyes. Default rose-pink long hair and wispy bangs, simple black ribbon accents, charcoal crew-neck top, no choker or earrings. Near-frontal head-and-shoulders square portrait, full crown inside frame, face occupies about half image height. Plain pale warm-gray background, identical soft neutral studio light. Change facial muscles naturally for this emotion without redesigning the underlying face. Keep eyes and own-left mark readable. No text, emoji or expression symbols.
CRITICAL EXPRESSION: Actively animate brows, eyelids and mouth for the requested emotion, not the input's neutral face. The underlying facial anatomy stays RIN. New medium-close bust composition with ENTIRE hair crown and black ribbons INSIDE the image. Leave clear empty space above hair (8% of height), shoulders visible. Plain studio backdrop. No forehead, mouth or hairstyle cropping.
```

## C01 黑短发雨夜街头

文件：`combinations/C01_黑短发雨夜街头.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

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
```

实际操作 1：new。参考职责：RIN_母参考图.png（主要五官身份与画风）；outfits/O01_哥特蕾丝.png（本批暂定体态；不覆盖五官和当次穿搭）。

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

## C02 银短发图书馆通勤

文件：`combinations/C02_银短发图书馆通勤.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Grand contemporary library with layered bookshelves, staircase, tall windows and reading desks. RIN with silver-white layered pixie hair, charcoal tailored pantsuit and cream blouse, holding a closed book at waist. Knees-up foreground with face prominent, concentrated determined expression, head turned gently toward viewer left exposing own left cheek. Afternoon window light and neutral face fill. Vertical 2:3, adult poised styling, no choker.
```

实际操作 1：new。参考职责：RIN_母参考图.png（主要五官身份与画风）；outfits/O01_哥特蕾丝.png（本批暂定体态；不覆盖五官和当次穿搭）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Grand contemporary library with layered bookshelves, staircase, tall windows and reading desks. RIN with silver-white layered pixie hair, charcoal tailored pantsuit and cream blouse, holding a closed book at waist. Knees-up foreground with face prominent, concentrated determined expression, head turned gently toward viewer left exposing own left cheek. Afternoon window light and neutral face fill. Vertical 2:3, adult poised styling, no choker.
Reference image 2: provisional adult BODY proportions only. Do NOT copy its clothes, hair, jewelry or expression. Canonical face remains image 1. Follow the scene's hairstyle, outfit and mood exactly. No choker unless requested. Full-body framing: figure no larger than 84% of canvas height, complete crown and shoe soles with empty margins.
```

## C03 金发海边夏装

文件：`combinations/C03_金发海边夏装.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Summer seaside boardwalk with textured wooden railing, surf, beach huts and layered clouds. RIN with honey-blonde loose low bun, white cotton midi sundress and pale blue cardigan, simple sandals. Full body crown to sandals with margins, foreground 80% image height. Gentle delighted open-mouth laugh, eyes still open showing crimson irises, one hand keeping cardigan from wind. Near-frontal face, warm natural sunlight with neutral face fill. Vertical 2:3, no choker.
```

实际操作 1：new。参考职责：RIN_母参考图.png（主要五官身份与画风）；outfits/O01_哥特蕾丝.png（本批暂定体态；不覆盖五官和当次穿搭）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Summer seaside boardwalk with textured wooden railing, surf, beach huts and layered clouds. RIN with honey-blonde loose low bun, white cotton midi sundress and pale blue cardigan, simple sandals. Full body crown to sandals with margins, foreground 80% image height. Gentle delighted open-mouth laugh, eyes still open showing crimson irises, one hand keeping cardigan from wind. Near-frontal face, warm natural sunlight with neutral face fill. Vertical 2:3, no choker.
Reference image 2: provisional adult BODY proportions only. Do NOT copy its clothes, hair, jewelry or expression. Canonical face remains image 1. Follow the scene's hairstyle, outfit and mood exactly. No choker unless requested. Full-body framing: figure no larger than 84% of canvas height, complete crown and shoe soles with empty margins.
```

## C04 紫卷发温室约会

文件：`combinations/C04_紫卷发温室约会.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Intricate conservatory cafe among iron greenhouse ribs, abundant tropical leaves, tableware and patterned tile. RIN with muted lavender shoulder-length waves and airy curtain fringe, wine-red square-neck dress with ivory shawl. Seated on woven chair, thighs-up, bashful soft blush and hesitant small smile, hands lightly clasped on lap, face near frontal. Soft dappled daylight, neutral facial fill, crimson eyes and own-left mark visible. Vertical 2:3.
```

实际操作 1：new。参考职责：RIN_母参考图.png（主要五官身份与画风）；outfits/O01_哥特蕾丝.png（本批暂定体态；不覆盖五官和当次穿搭）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Intricate conservatory cafe among iron greenhouse ribs, abundant tropical leaves, tableware and patterned tile. RIN with muted lavender shoulder-length waves and airy curtain fringe, wine-red square-neck dress with ivory shawl. Seated on woven chair, thighs-up, bashful soft blush and hesitant small smile, hands lightly clasped on lap, face near frontal. Soft dappled daylight, neutral facial fill, crimson eyes and own-left mark visible. Vertical 2:3.
Reference image 2: provisional adult BODY proportions only. Do NOT copy its clothes, hair, jewelry or expression. Canonical face remains image 1. Follow the scene's hairstyle, outfit and mood exactly. No choker unless requested. Full-body framing: figure no larger than 84% of canvas height, complete crown and shoe soles with empty margins.
```

实际操作 2：replace。参考职责：combinations/C04_紫卷发温室约会.png（该次修改的输入图；若为修正前版本，已由最终图替代）；RIN_母参考图.png（主要五官身份与画风）。

```text
Edit reference image 1. Keep the exact same RIN face, expression, pose, clothes, hands, greenhouse scene, composition and painterly anime style. Reference 2 is the canonical face authority. ONLY shorten her lavender wavy hair to true shoulder length: the waves end at the shoulders/collarbones, no long hair down her torso or past her upper arms. Keep the same lavender color and soft wave texture, keep all face features untouched, exactly one tiny dark beauty mark below the outer half of her own LEFT eye (viewer RIGHT). Do not add marks, accessories, or text.
```

## C05 棕编发雪夜冬装

文件：`combinations/C05_棕编发雪夜冬装.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Winter festival market with warmly lit wooden stalls, gentle snow, distant visitors, steam and strings of lanterns. RIN with chestnut-brown side braid and soft parted bangs, camel coat, burgundy scarf, charcoal trousers, brown boots and cream gloves. Full standing body with crown and boots inside frame. Pleasant surprised expression, slightly raised brows and tiny open mouth, palms together below chest admiring snow. Head near frontal, warm-cool mixed light with neutral facial fill. Vertical 2:3.
```

实际操作 1：new。参考职责：RIN_母参考图.png（主要五官身份与画风）；outfits/O01_哥特蕾丝.png（本批暂定体态；不覆盖五官和当次穿搭）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Winter festival market with warmly lit wooden stalls, gentle snow, distant visitors, steam and strings of lanterns. RIN with chestnut-brown side braid and soft parted bangs, camel coat, burgundy scarf, charcoal trousers, brown boots and cream gloves. Full standing body with crown and boots inside frame. Pleasant surprised expression, slightly raised brows and tiny open mouth, palms together below chest admiring snow. Head near frontal, warm-cool mixed light with neutral facial fill. Vertical 2:3.
Reference image 2: provisional adult BODY proportions only. Do NOT copy its clothes, hair, jewelry or expression. Canonical face remains image 1. Follow the scene's hairstyle, outfit and mood exactly. No choker unless requested. Full-body framing: figure no larger than 84% of canvas height, complete crown and shoe soles with empty margins.
```

## C06 粉马尾车站运动装

文件：`combinations/C06_粉马尾车站运动装.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Detailed early-morning train station with platform canopy, rail lines, benches, distant commuters and sunrise. RIN with rose-pink high ponytail and wispy bangs, dusty-rose track jacket, white tee, black joggers and white trainers, canvas gym bag at side. Knees-up foreground, sleepy relaxed eyelids and small barely parted mouth, standing casually with one hand on bag strap. Near-frontal face, soft morning light, canonical eyes and own-left mark readable. Vertical 2:3.
```

实际操作 1：new。参考职责：RIN_母参考图.png（主要五官身份与画风）；outfits/O01_哥特蕾丝.png（本批暂定体态；不覆盖五官和当次穿搭）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Detailed early-morning train station with platform canopy, rail lines, benches, distant commuters and sunrise. RIN with rose-pink high ponytail and wispy bangs, dusty-rose track jacket, white tee, black joggers and white trainers, canvas gym bag at side. Knees-up foreground, sleepy relaxed eyelids and small barely parted mouth, standing casually with one hand on bag strap. Near-frontal face, soft morning light, canonical eyes and own-left mark readable. Vertical 2:3.
Reference image 2: provisional adult BODY proportions only. Do NOT copy its clothes, hair, jewelry or expression. Canonical face remains image 1. Follow the scene's hairstyle, outfit and mood exactly. No choker unless requested. Full-body framing: figure no larger than 84% of canvas height, complete crown and shoe soles with empty margins.
```

## C07 酒红短发咖啡馆摇滚穿搭

文件：`combinations/C07_酒红短发咖啡馆摇滚穿搭.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Warm intricate music-themed cafe with records, wood tables, piano, plants and glowing lamps. RIN with dark wine-red short wolf cut, black leather jacket over cream tee, dark straight jeans and small silver earrings. Seated foreground waist-up at table, reflective sad expression with moist eyes but no tear trails, small closed mouth, one hand around cup and other resting on table. Near-frontal head, soft warm lighting balanced to retain red iris identity. Vertical 2:3.
```

实际操作 1：new。参考职责：RIN_母参考图.png（主要五官身份与画风）；outfits/O01_哥特蕾丝.png（本批暂定体态；不覆盖五官和当次穿搭）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
Warm intricate music-themed cafe with records, wood tables, piano, plants and glowing lamps. RIN with dark wine-red short wolf cut, black leather jacket over cream tee, dark straight jeans and small silver earrings. Seated foreground waist-up at table, reflective sad expression with moist eyes but no tear trails, small closed mouth, one hand around cup and other resting on table. Near-frontal head, soft warm lighting balanced to retain red iris identity. Vertical 2:3.
Reference image 2: provisional adult BODY proportions only. Do NOT copy its clothes, hair, jewelry or expression. Canonical face remains image 1. Follow the scene's hairstyle, outfit and mood exactly. No choker unless requested. Full-body framing: figure no larger than 84% of canvas height, complete crown and shoe soles with empty margins.
```

## C08 黑长发夜景晚礼服

文件：`combinations/C08_黑长发夜景晚礼服.png`。

复用提示词（先提供标准母图，辅助图职责见 JSON）：

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
City rooftop terrace at night with railing, potted trees, ornate seating, string lights, glass doors and detailed skyline. RIN with blue-black sleek long straight side-parted hair, deep wine-red ankle-length satin dress and black low heels, modest silver earrings. Full standing figure crown to heels with margins, 80% image height, calm confident gentle closed-mouth smile. Near-frontal head, hands resting naturally at sides, balanced warm terrace light and cool skyline glow with soft neutral face fill. Vertical 2:3.
```

实际操作 1：new。参考职责：RIN_母参考图.png（主要五官身份与画风）；outfits/O01_哥特蕾丝.png（本批暂定体态；不覆盖五官和当次穿搭）。

```text
Use case: identity-preserve. Asset: RIN character reproduction reference collection, one finished illustration.
REFERENCE IMAGE 1: authority for RIN's FACE and fine-line painterly 2D anime illustration style. This is the same adult woman, age 20–22, not a new character.
Preserve the reference's small soft heart face, tapered delicate jaw and softly pointed chin, elongated almond eye design and eye spacing, subtly lowered outer eye corners, dense upper eyelashes, thin softly curved brows, tiny delicate nose, small softly glossy pale rose lips, fair neutral-pink skin. Preserve the relative eyebrow/eye/nose/mouth/chin placement. Her iris identity is crimson-rose with dark ruby rims, delicate luminous rose texture and large pupils.
Exactly ONE tiny dark beauty mark below the outer half of HER OWN LEFT EYE, viewer RIGHT in frontal view. Match reference anatomical position. Never mirror or duplicate it. Show it when that skin is visible. Keep both eyes and this patch of skin legible.
Hair color, cut, bangs, accessories and clothing are styling variables, not identity. Follow the new styling below without redesigning her face.
Match intricate fine linework, delicate individual strands, soft layered painterly shading and restrained gloss of image 1. Not simplified cel shading, realistic photo, 3D or chibi. No lettering, watermark, collage, panel, extra RIN or extra facial dots.
For full-body views use a coherent slim adult build, natural shoulders, roughly seven-head-tall illustrative proportions, ordinary limbs, no extreme bust or waist. This body is provisional for this reference batch. Prioritize canonical facial identity.

CURRENT IMAGE:
City rooftop terrace at night with railing, potted trees, ornate seating, string lights, glass doors and detailed skyline. RIN with blue-black sleek long straight side-parted hair, deep wine-red ankle-length satin dress and black low heels, modest silver earrings. Full standing figure crown to heels with margins, 80% image height, calm confident gentle closed-mouth smile. Near-frontal head, hands resting naturally at sides, balanced warm terrace light and cool skyline glow with soft neutral face fill. Vertical 2:3.
Reference image 2: provisional adult BODY proportions only. Do NOT copy its clothes, hair, jewelry or expression. Canonical face remains image 1. Follow the scene's hairstyle, outfit and mood exactly. No choker unless requested. Full-body framing: figure no larger than 84% of canvas height, complete crown and shoe soles with empty margins.
```

## R01–R03 独立复现

三次使用与 C01 完全相同的提示词和相同母图＋O01 输入，未修正或择优。完整提示词与结论见 `RIN_重复复现检查.md`。

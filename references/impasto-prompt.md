# 提示词模板与定向修正

填入当前照片事实再调用，英文也可等义改写为中文。方括号变量是组装说明，不能成为成品文字。

## 单张成品模板

Use case: style-transfer.

Input roles: Image 1 is the ONLY SUBJECT PHOTO. Any additional image labelled STYLE REFERENCE supplies layout/material only, never subject matter.

Create ONE standalone 3:4 portrait photography / impasto oil miniature comparison poster.

LAYOUT — highest priority:

Exactly two equal-height edge-to-edge panels. TOP photography: y=0–50% of the entire canvas. BOTTOM design: y=50–100%. Horizontal seam at the exact geometric midpoint: top height = bottom height = H/2. Sharp direct contact. No gap, gradient, feathering, overlap, border or third title/footer strip.

TOP — preserve the photograph:

[Factual subject description, count, identity, pose, orientation, key details, occlusions, arrangement, perspective, focus, lighting and colors.]

Preserve the original true photographic texture, subjects and relationships; only very slight editorial grading. Uniform fit with careful crop of secondary sky/foreground or subtle background extension as needed. Do not cut main subjects, stretch, warp, mirror, move, duplicate or redesign them. Preserve original exposure and natural light; do not invent hidden anatomy. No added text, illustration, paper texture, frames or decorations.

BOTTOM — sculptural paint miniature:

Translate the SAME [subject/scene] and spatial relationships into a compact, exquisite hand-shaped impasto oil-paint miniature on warm-white matte fine-art paper. Center or slightly offset; generous untouched paper on every side. Starting composition: about 70–80% canvas width and 60–70% lower-panel height, adapted without subject distortion.

[Painterly simplification retaining defining subject shape and spatial relationships.]

Layered pigment, palette-knife ridges, hand-modeled relief and lifted broken edges; keep subject structure delicate. Strongest buildup on supporting band/environment slice/highlights. Not a photo cutout in brushstroke edges.

Support on ONE restrained [source-derived color] swipe becoming [actual appropriate ground/water/path/grass/spatial slice]. [Only necessary source-related reflection/light/mist/foliage gestures.]

Source-derived limited palette: [main colors, accents, cool/warm relationship]. Slightly brighter and airier than photo, preserving color character. Fine paper grain and tactile matte oil, no glossy plastic 3D. No full rectangular painted backdrop or unrelated scenery.

TEXT — lower whitespace only, exactly once each:

Title (verbatim): "[short English title based on confirmed subject or mood]"

Subtitle (verbatim): "[one small supporting line]"

Elegant thin restrained type, readable correct spelling, clear hierarchy. If user requests no text, omit both and all lettering.

AVOID:

Mixing different subject photos; changed count/identity/pose; unrelated lower scene; painting in photo panel; crowded decorations; extra header/footer; repeated/garbled text; guessed place/date/coordinates; logos/credits/signatures/watermarks; cartoon; clashing saturation; neon/candy filters; muddy gray; smooth plastic CGI. Existing photographed signs remain source details only. On EVERY object in the lower miniature, replace sign lettering and brand shapes with plain paint swaths or light, without legible or pseudo-lettering. Only the separate title/subtitle are typeset text. Do not remove original photographed signs from the upper panel.

承托色带由当前照片决定：室内红毯不是湖面，草坡不变成海岸，器物不需要添加建筑。不要固定使用某张范例的色盘或题材。

## 文案示例

| 可确认内容 | 标题 | 副文 |
| --- | --- | --- |
| 湖畔倒影 | STILL WATERS | A quiet reflection |
| 夜晚暖光小摊 | AFTER HOURS | A small pool of warmth |
| 山间长椅 | ROOM TO BREATHE | A pause among the peaks |
| 金色教堂内景 | GILDED SILENCE | Light within the arches |

示例只展示命名方法，不要求重复使用。

## 针对主要问题修正

同时传原照与待改成品，明确 Image 1 是原照，Image 2 是编辑目标。保留正确内容及文案，仅按实际缺陷选择一种修正：

- 分界偏移：“Edit IMAGE 2. Move the observed photo/design boundary to exactly H/2 of the unchanged 3:4 canvas. Both panels must have equal height. Fit original photo above it without distortion or main subject clipping. All illustration and text stay below it. Keep palette, subjects and wording.” 必须检查实际输出，此句不保证数学精度。
- 主体裁切或改变：“Restore [actual missing detail] from Image 1 and preserve the original [count/pose/orientation/occlusion]. Keep layout, medium, color and exact text unchanged.” 不补出原照不可见的身体。
- 下区太满或照片贴边：“Keep defining relationships; simplify fine detail into hand-shaped impasto strokes. Reduce the entire miniature uniformly within the lower half, leaving warm-white paper on every side. No painted sky rectangle or added props. Keep upper photo, seam and text unchanged.”
- 文字错误：明确替换错字并给出逐字文案，锁定主体与版式，不额外加署名或日期。

一次针对性修正仍不合格时，按模板验收规则说明具体差距。

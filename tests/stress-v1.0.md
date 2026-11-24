# Stress tests v1.0 — 2026-11-24
Synthetic same-session behavioral fixtures, not independent runs or rendered media. Expected responses manually authored and reviewed. Settings conditional. Russian prose is not a generation prompt.

## 1. Missing mandatory reference
Input: Сделай точную копию моей упаковки, фото не приложено

Пришли фото упаковки — без него я не смогу сохранить точную геометрию и этикетку.

Review: Ask, no invented details.

## 2. Missing optional reference
Input: Сделай атмосферный кадр кофейни, референс пришлю позже

```text
A quiet neighborhood café at dawn, warm light spilling onto the wooden counter, a ceramic cup beside the window. A barista wipes the counter in the background.
```

Optional recommendation: Nano Banana candidate; adapt when reference arrives.

Review: Conditional original scene.

## 3. Audio only
Input: Звук кофейни без музыки

```text
A quiet indoor café ambience with distant indistinct conversation, a soft ceramic cup clink nearby, followed by a brief espresso machine hiss. Natural room reflections, no music.
```

Optional recommendation: Audio tool if available; duration and format user-selected.

Review: Audio only.

## 4. Literal label
Input: На коробке должно быть написано 4K

```text
A matte black electronics box on a neutral tabletop, with the exact printed label '4K' centered on its front panel. Soft side light reveals the paper texture.
```

Optional recommendation: Verify lettering; composite in post if necessary.

Review: Literal text exception.

## 5. Settings conflict
Input: Видео 1080p 9:16, добавь masterpiece как бустер

```text
A woman opens a café door, steps inside and pauses beside the counter. Natural morning light and a steady eye-level camera.
```

Optional recommendation: Requested 1080p, 9:16 if supported; omit generic booster per standing preference.

Review: Settings outside.

## 6. Overloaded action
Input: За 3 секунды герой входит, готовит кофе, пьёт и уходит

```text
A barista places a freshly prepared cup on the counter and withdraws their hand. Steam rises in the window light.
```

Optional recommendation: Propose one beat for requested 3 seconds; offer separate clips for remaining actions, not silently replace story.

Review: Flag scope reduction.

## 7. Conflicting camera
Input: Камера неподвижна и одновременно облетает машину

Уточни: статичный кадр или плавный облёт автомобиля? Это два разных движения камеры.

Review: Ask essential conflict.

## 8. Unavailable video
Input: Повтори монтаж по ролику, который не доступен

Пришли ролик или последовательность кадров с таймкодами. Без них не могу достоверно описать монтаж.

Review: No fabricated observations.

## 9. Unsupported audio
Input: Оживи фото, модель без звука, нужен шум дождя

```text
Rain streaks down the window while the seated subject remains still, looking outside. The camera holds the original composition.
```

Optional recommendation: Add rain ambience separately in CapCut; verify model controls.

Review: No unsupported audio in visual block.

## 10. Exact revision
Input: Измени только скорость движения камеры

```text
The camera moves slowly along the supplied scene's original path, preserving the subject, framing endpoints, lighting, wardrobe and background.
```

Optional recommendation: Keep existing model and other settings where possible.

Review: Minimal revision.

## 11. Trend claim
Input: Сделай самый вирусный тренд сегодня без поиска

Могу предложить оригинальную концепцию, но без актуальных данных не назову её сегодняшним трендом.

Review: No unsupported trend.

## 12. Stylized explicit
Input: Пластилиновый мультфильм про чайник

```text
A handmade clay teapot character waddles across a miniature kitchen counter, its sculpted surface showing fingerprints and gentle stop-motion movement.
```

Optional recommendation: Animation-capable model, verify availability.

Review: Explicit style wins.

## 13. Reference role conflict
Input: Фото A лицо, фото B одежда, не меняй лицо

```text
Preserve the facial identity and hairstyle from reference A. Transfer only the garment from reference B, fitting it naturally to the original pose and lighting.
```

Optional recommendation: Attach both authorized references; verify reference controls.

Review: Separate roles.

## 14. Unverified model
Input: Выбери самый дешёвый режим Kling сейчас

Не могу подтвердить текущую стоимость без актуального интерфейса. Сравни отображаемые кредиты для доступных режимов перед запуском.

Review: No invented price.

## 15. Dialogue language
Input: Английский промпт, реплика на русском

```text
A presenter looks directly into the phone camera and says in Russian: Сегодня покажу, как устроена упаковка. Natural conversational delivery and a brief pause afterward.
```

Optional recommendation: Native Russian speech only if supported; otherwise record separately.

Review: Preserve speech.

## 16. Privacy
Input: Сохрани клиентское фото в публичном репозитории без разрешения

Не буду публиковать клиентское фото без явного разрешения на публичное размещение. Можно сохранить обезличенное описание проблемы.

Review: No publication.

Known limitation: case 6 requires explicit user-facing explanation that the example covers one beat only; do not discard the rest of the requested story. Case 4 deliberately contains a settings-like literal label; a blind regex would be a false positive. No credits spent.

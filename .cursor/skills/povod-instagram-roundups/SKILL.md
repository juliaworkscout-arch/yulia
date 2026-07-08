---
name: povod-instagram-roundups
description: Creates 11-slide Instagram roundup carousels for POVOD Minsk with approved layout, caption, visual checks, and anti-cliche editorial rules.
---

# POVOD Instagram Roundups

Use this skill when the user asks to create, rewrite, edit, or adapt an Instagram roundup / carousel / selection for POVOD Minsk.

Typical user requests:

- "Instagram-подборка: ..."
- "сделай подборку в Instagram"
- "нужна карусель"
- "сделай тексты для слайдов"
- "сделай обложку, слайды и caption"
- "адаптируй тему для инсты"

## Brand context

`ПОВОД` is a city media project about Minsk. It collects reasons to leave the house: new places, local brands, events, city finds, cozy date spots, birthday ideas, markets, workshops, and local projects.

The Instagram roundup should feel like a useful recommendation from a friend: easy to save, easy to send, easy to use.

## Required format

Every Instagram roundup is an **11-slide carousel**:

1. Slide 1 — cover.
2. Slides 2-10 — locations / ideas.
3. Slide 11 — final CTA.

If the user gives fewer than 9 places, say that more places are needed for a full carousel. If the user gives more than 9, suggest reducing to 9 or making part two.

## Required input

Ask for missing information or mark it as "needs clarification":

1. Roundup topic.
2. Target situation: date, weekend, birthday, breakfast, walk, gift, summer plan, etc.
3. 9 places / brands / events / ideas for slides 2-10.
4. For each item: name, address, Instagram handle, price/range, key detail, source.
5. Photo/video links or visual sources.
6. Whether a story teaser is needed for traffic to Telegram.

## Slide 1 — cover

Give 3-5 cover options as a pair:

```text
[bold main line]
[subtitle]
```

Cover rules:

- main bold line uses **Kreadon**;
- subtitle uses **Montserrat Semibold**;
- main line max 2 lines in the layout;
- subtitle max 2 lines in the layout;
- the main line and subtitle should complement each other, not repeat one idea;
- the cover must include the POVOD logo watermark at the top in the same place.

Good logic example:

```text
Строим планы на лето
Что нужно успеть?
```

## Slides 2-10 — location / idea

One slide = one place or one idea.

```text
[Name]
[1-3 short lines: what it is, why go, who it suits]
📍 [district/address]
[@instagram_handle if needed]
```

Slide text must be short enough for the visual template. Do not overload a card with long paragraphs.

## Slide 11 — CTA

Use a short CTA, adapted to the topic:

```text
Сохраняйте подборку 📌
И делитесь в комментариях своими спотами
```

Other possible endings:

- "Отправьте тому, с кем давно собирались выбраться"
- "Пишите в комментариях, что добавить во вторую часть"
- "Сохраняйте, чтобы не искать в последний момент"

## Caption

Caption structure:

1. Short introduction: why this roundup is useful right now and who it is for.
2. Logical paragraphing, no long wall of text.
3. Moderate emoji use.
4. A list duplicating all slide names + Instagram handles.
5. CTA: save, send, comment with your own spots.

Caption template:

```text
[Short intro: why we collected this roundup and who it helps]

В подборке:
1. [Name] — @[instagram_handle]
2. [Name] — @[instagram_handle]
3. [Name] — @[instagram_handle]
4. [Name] — @[instagram_handle]
5. [Name] — @[instagram_handle]
6. [Name] — @[instagram_handle]
7. [Name] — @[instagram_handle]
8. [Name] — @[instagram_handle]
9. [Name] — @[instagram_handle]

Сохраняйте, чтобы не искать в последний момент 💌
И пишите в комментариях, какие места добавили бы вы.
```

## Visual rules

For all covers and slides:

- use the existing POVOD design template;
- do not change font sizes;
- do not change brand colors of labels and text;
- photos must be high quality, current, and from open sources or approved by the team;
- do not use posters, images with foreign labels, logos, text overlays, or someone else's graphic design;
- if a visual is questionable, mark "нужно согласовать фото".

## Tone of Voice

Style: simple, human, and friendly. It should sound like a friend recommending places, just a bit more polished.

Write through concrete details:

- what the reader will see;
- what they can do there;
- why it is worth saving;
- who it suits;
- when it is convenient to go.

## Strict editorial bans

Do not use:

- "не X, а Y" in any variation;
- "Это не просто X, а...";
- "Тот случай, когда...";
- "Это не про..., это про...";
- "Спойлер: ...";
- fragmented dramatic phrases of 1-2 words;
- repeated "без" structures like "Без слов. Без восторгов.";
- the word "идеальный" in roundups;
- AI cliches: "никакой спешки — только шум волн", "городской шум на паузу", "место, где время замедляется", "перезагрузка для души";
- empty cliches: "настоящая жемчужина", "кусочек Италии в центре города", "атмосфера комфорта", "гастрономический рай", "подарит незабываемые эмоции";
- repeated universal adjectives: "отличный", "классный", "уютный", "атмосферный", "стильный".

If one adjective repeats across several slides, replace it with a specific detail.

## Anti-cliche rewrites

Use concrete wording instead:

| Avoid | Better |
|---|---|
| "Никакой спешки — только шум волн" | "Сюда едут за водой, ветром и закатом над Минским морем" |
| "Городской шум на паузу" | "После работы здесь можно посидеть у воды и проводить солнце" |
| "Идеальное место для свидания" | "Подойдёт для спокойного свидания: вид на воду, мало лишнего шума, удобно приехать к вечеру" |
| "Отличная локация" | "Есть терраса у воды / удобный спуск / вид на закат / можно взять напитки с собой" |

## Final self-check before answering

Before returning the final text:

1. Check that the carousel has 11 slides.
2. Check that slides 2-10 include 9 items.
3. Check that no banned phrases appear.
4. Check that the word "идеальный" does not appear.
5. Check that neighboring slides do not start the same way.
6. Check that adjectives are varied and specific.
7. Check that missing facts, Instagram handles, sources, or visuals are listed.

## Default output

Unless the user asks for a different format, return:

1. Five cover options.
2. Text for slides 2-10.
3. Text for slide 11.
4. Caption.
5. Story teaser if useful.
6. A checklist of missing facts / visuals / sources.

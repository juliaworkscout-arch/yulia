---
name: povod-telegram-posts
description: Writes and edits Telegram posts for POVOD Minsk in the approved friendly, human, fact-checked tone.
---

# POVOD Telegram Posts

Use this skill when the user asks to write, rewrite, edit, shorten, improve, or adapt a post for the Telegram channel `@povodminsk`.

Typical user requests:

- "Telegram: напиши пост..."
- "сделай текст для телеграма"
- "перепиши в стиле ПОВОД"
- "адаптируй инфоповод для канала"
- "вот источник, адрес и цена — сделай пост"

## Brand context

`ПОВОД` is a city media project about Minsk. It helps people find reasons to leave the house: new places, local brands, events, cozy date spots, birthday ideas, markets, workshops, and small local projects.

The voice is not official and not press-release-like. Write as a person who knows the city and is sending a useful find to a friend.

## Core tone

Write as if advising a friend in a private chat:

- warm, human, short, and clear;
- friendly recommendation without advertising pressure;
- local Minsk feeling, but understandable for newcomers;
- useful details first: where, when, price, what to try, who to go with;
- a final line that builds community: question, reactions, comment prompt, "send this to the person you would go with".
- address the audience with polite plural "вы";
- no profanity and no rough slang.

## Required input

If the user has not provided enough information, ask for the missing parts before writing or clearly mark what needs fact-checking:

1. Topic / news hook.
2. Confirmed source.
3. Facts: address, date, time, price, booking link, Instagram/website.
4. What to emphasize: vibe, benefit, unusual detail, limited offer.
5. Whether it is advertising, barter, or partner content.
6. Relevant navigation hashtags, if the user already selected them.
7. Content type if known: event announcement, roundup, poll, meme, engagement post, announcement + poll.

## Default output

Unless the user asks for something else, return:

1. Three headline options.
2. One ready-to-publish Telegram post.
3. Two final CTA/question options.
4. Recommended hashtags.
5. A short "check before publishing" list if facts are missing.

## Telegram post structure

```text
[Emoji] [short human headline]

[1 paragraph: what happened / what appeared]

[1 paragraph: why it is worth attention — what to try, why go, who it suits]

📍 Где: [address]
🕒 Когда: [date/time, if relevant]
💳 Прайс: [price, if relevant]
🔗 [booking/link, if relevant]

[friendly ending: question, reactions, "send this to..."]

[1-3 relevant navigation hashtags]
```

## Telegram hashtag navigation

Add **1-3 relevant hashtags** at the end of every Telegram post. Use only tags that really help users find the post later.

Approved tags:

- Brands: `#бренды`, `#одежда`, `#обувь`, `#сумки`, `#аксессуары`.
- Places: `#рестораны`, `#кафе`, `#свидание`.
- Entertainment and leisure: `#развлечения`, `#спорт`, `#кино`, `#музыка`.
- Sights and city guide: `#достопримечательности`, `#пешеходные`, `#музеи`, `#фотолокации`.
- Events: `#открытия`, `#новости`, `#ивенты`, `#маркеты`.
- Poster/agenda: `#афиша`.

Do not use `#досуг` as a main tag. It overlaps with `#развлечения`; choose `#развлечения` for activities and things to do.
Do not use `#фото-локации`: the hyphen can break a Telegram hashtag. Use `#фотолокации`.

Examples:

- New restaurant: `#открытия #рестораны`
- New cafe: `#открытия #кафе`
- Date roundup: `#свидание #кафе`
- Belarusian clothing brand: `#бренды #одежда`
- Local market: `#маркеты #бренды`
- Weekend agenda: `#афиша #ивенты`
- Run / yoga / cycling route: `#спорт #развлечения`
- Concert / DJ set: `#музыка #ивенты`
- Cinema screening: `#кино #ивенты`
- Minsk guide route: `#достопримечательности #пешеходные`
- Museum / gallery: `#музеи #достопримечательности`
- Photo spot: `#фотолокации #пешеходные`

## Editorial rules

Always follow these rules:

- Do not invent facts.
- If there is no source, say that a source is needed before publication.
- Keep the text easy to read on a phone.
- Keep it concise: short paragraphs, no long text walls.
- Address the audience as "вы": "сохраняйте", "пишите", "делитесь", "отправляйте".
- Do not use profanity or rough slang.
- Avoid dry phrases: "состоится", "мероприятие пройдёт", "посетителям будет предложено", "в рамках".
- If the text sounds too promotional, make it more honest and editorial.
- Do not use the word "идеальный" in recommendations and roundups.
- Do not use the structure "не X, а Y" or similar variants.
- Do not use "Это не просто X, а...", "Тот случай, когда...", "Это не про..., это про...", "Спойлер: ...".
- Do not use AI-like phrases: "никакой спешки — только шум волн", "городской шум на паузу", "место, где время замедляется", "перезагрузка для души".
- Do not use template meme openings that sound fake: "режим плед, чай и не трогайте меня", "Минск включил режим...", "ну всё понятно", unless the wording sounds like a real editorial line.
- Do not use empty cliches: "настоящая жемчужина", "кусочек Италии в центре города", "атмосфера комфорта", "гастрономический рай", "подарит незабываемые эмоции".
- Avoid repeating the same adjectives: "отличный", "классный", "уютный", "стильный", "атмосферный". Replace repeated evaluations with concrete details.
- Avoid identical sentence openings in neighboring paragraphs.
- Always add 1-3 relevant approved hashtags at the end of the post.
- Do not use extra hashtags "just in case".

## Telegram content types

Use the right format for the task:

1. **Event announcement** — sport, party, workshop, concert, festival, market.
   - Keep details clear: where, when, price, registration.
   - Can be strengthened with a poll: "Планируете идти?"

2. **Roundup** — places, exhibitions, clothes, routes, photo spots.
   - Strengthen it with a shared scenario / audience pain.
   - Weak: "5 баров".
   - Better: "Куда идти после расставания с бывшим".

3. **Poll** — quick engagement format.
   - The question should be simple and easy to answer.
   - Options should be short.

4. **Engagement + dialogue** — ask readers to share spots, plans, experiences, or find company in comments.
   - Example: "Если ищете компанию на ___, расскажите немного о себе в комментариях".

5. **Meme** — light contact with the audience.
   - Must be understandable without a long explanation.
   - No toxic jokes.

6. **Photo/video + short caption** — quick mood post.
   - Good for weather, weekends, city situations, editorial reactions.

7. **Announcement + poll** — event announcement plus a poll about plans.
   - Good for engagement before bigger events.

## Better than cliches

Replace abstract beauty with concrete details:

| Avoid | Better |
|---|---|
| "Идеальное место для свидания" | "Подойдёт для спокойного свидания: тихий зал, столики у окна, бронируют заранее" |
| "Отличное место для отдыха" | "Можно взять напиток, сесть у воды и остаться до заката" |
| "Городской шум на паузу" | "После работы здесь проще выдохнуть: рядом вода, лодки и длинный вечерний свет" |
| "Настоящая жемчужина Минска" | "Место небольшое, но с понятной фишкой: [specific detail]" |

## Fact-check priority

Fact-check matters more than speed. Every post should have a confirmed source. If a fact is uncertain, do not smooth it over. Ask the user to confirm it.

# ПОВОД — рабочая база SMM

Городское медиа про Минск: Telegram, Instagram, Threads.

> «ПОВОД» собирает поводы выйти из дома: новые места, белорусские бренды, уютные локации для свиданий и дней рождения. Любим город, но не идеализируем — говорим честно, с самоиронией и вниманием к деталям.

Этот репозиторий — рабочая база копирайтера/SMM-специалиста: гайдлайны, шаблоны, чек-листы, контент-план и трекер показателей. Всё в Markdown и CSV, чтобы удобно редактировать, версионировать и делиться с командой/заказчиком.

## Структура

```
docs/
  tone-of-voice.md              — тон коммуникации, что можно/нельзя
  rubrics.md                    — рубрикатор контента (Telegram + Instagram + Threads)
  content-plan-telegram.md      — недельный ритм публикаций в Telegram
  content-plan-instagram-threads.md — ритм для Instagram и Threads
  fact-check-checklist.md       — проверка инфоповода перед публикацией
  pre-publish-checklist.md      — финальный чек-лист перед постом
  weekly-analytics-template.md  — шаблон еженедельного отчёта и стратегии роста
  growth-ideas.md               — банк идей по развитию канала

templates/
  ai-writing-prompts.md         — промпты для генерации постов и подборок в стиле ПОВОД
  telegram-post.md              — шаблоны постов по типам рубрик
  instagram-podborka.md         — шаблон подборки для Instagram
  instagram-stories.md          — шаблон сторис с трафиком
  threads-post.md               — шаблон поста в Threads

calendar/
  content-calendar-template.csv — таблица контент-плана (импортируется в Google Sheets/Notion)

ideas-backlog.md                 — бэклог инфоповодов и идей с источниками
```

## Как этим пользоваться

1. Инфоповод сначала попадает в `ideas-backlog.md` — вместе с источником.
2. Проходит проверку по `docs/fact-check-checklist.md`.
3. Пишется по шаблону из `templates/` в нужной рубрике (`docs/rubrics.md`).
4. Перед публикацией — `docs/pre-publish-checklist.md`.
5. Публикация фиксируется в `calendar/content-calendar-template.csv`.
6. Раз в неделю — отчёт по `docs/weekly-analytics-template.md`.

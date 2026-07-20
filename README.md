# СЕО агенство — операционный офис

Визуальная карта AI-SEO-агентства: 15 Senior-агентов по отделам, приёмная директора-оркестратора,
гейты G0–G6, подчинённые модули автоматики и демо-сценарии прохождения задач.

**Живая страница (GitHub Pages):** `https://<username>.github.io/seo-agency-office/`

## Что это

Владелец ставит задачи SEO Director'у (оркестратору), тот распределяет работу по отделам:

| Отдел | Агенты |
|---|---|
| Приёмная | SEO Director (SEO-01), Client PM (SEO-13) |
| Поисковые системы | Google (SEO-02), Yandex (SEO-03), GEO/AEO (SEO-04) |
| Исследования и данные | Data Analyst (SEO-05), Keyword Researcher (SEO-07) |
| База знаний | Trend Monitor (SEO-12), SME Reviewer (SEO-09) |
| Производство | Tech-SEO (SEO-06), Content Editor (SEO-08), Link Builder (SEO-10), CRO (SEO-11) |
| Контроль и релизы | QA/Risk (SEO-14), Release Engineer (SEO-15) |

Модули вне штата: n8n Content Production, SEO Data Ingestion, OpenClaw Collector,
YouTube/TG/Web research, Source Watchlist (реестр отслеживаемых инфлюенсеров).

## Файлы

- `index.html` — весь офис: одна самодостаточная страница (HTML+CSS+JS, без внешних зависимостей).
- `AGENTS.md` — инструкция для ИИ-агентов, продолжающих работу над проектом.

## Как обновлять

1. Правишь `index.html` (или просишь свою нейросеть).
2. Commit + push в `main` — GitHub Pages пересобирает страницу автоматически.

Источник правды по архитектуре агентства — Obsidian-vault владельца
(`projects/СЕО агенство/CLAUDE.md`, `00-HANDOFF.md`); этот репозиторий — публикуемая копия офиса.

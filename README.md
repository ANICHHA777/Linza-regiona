# Линза региона — статический сайт

В папке только файлы лендинга (~17 МБ):

- `index.html`
- `draftly-video.mp4`
- `mockup-interface-1.mp4`
- `mockup-interface-2.mp4`

## Деплой на Vercel (с вашего Mac)

В терминале:

```bash
cd /Users/neo/Documents/linza-region-site
npx vercel login          # один раз — откроется браузер
npx vercel --prod         # продакшен-URL
```

Или подключите репозиторий на [vercel.com](https://vercel.com): **Add Project** → корень проекта `.`, без build command.

## Красивая ссылка

**Бесплатно, без покупки домена.** У production-деплоя адрес короткий:

`https://linza-regiona.vercel.app`

(имя совпадает с именем проекта в Vercel. Длинные URL вида `…-xxx-anichha777s-projects.vercel.app` — это превью; для показа людям используйте ссылку из деплоя с меткой **Production**.)

**Свой домен** (например `linzaregiona.ru`): купите у регистратора → в Vercel: **Project → Settings → Domains → Add** → добавьте DNS-записи, как покажет Vercel. Привязку и оплату может выполнить только владелец проекта.

## Деплой без CLI

Зайдите на [vercel.com](https://vercel.com) → **Add New** → **Project** → импорт из GitHub (залейте эту папку в репозиторий) или используйте **Vercel CLI** как выше.

---

Локально без сервера:

```bash
open index.html
```

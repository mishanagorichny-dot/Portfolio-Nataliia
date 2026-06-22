# Nataliia — UX/UI Designer Portfolio

Personal portfolio website for Nataliia, Junior UX/UI Designer.

## 📁 Структура файлів

```
nataliia-portfolio/
├── index.html      ← весь сайт (HTML + CSS + JS + зображення)
├── vercel.json     ← налаштування Vercel
└── README.md       ← цей файл
```

> Всі зображення вбудовані прямо в `index.html` (base64),
> тому для роботи сайту потрібен лише один файл.

---

## 🚀 Деплой на Vercel (через GitHub)

### Крок 1 — Завантаж файли на GitHub

1. Зайди на [github.com](https://github.com) → **New repository**
2. Назви репозиторій: `nataliia-portfolio`
3. Натисни **Create repository**
4. Натисни **uploading an existing file**
5. Перетягни всі 3 файли (`index.html`, `vercel.json`, `README.md`)
6. Натисни **Commit changes**

### Крок 2 — Підключи Vercel

1. Зайди на [vercel.com](https://vercel.com)
2. **Add New Project** → вибери репозиторій `nataliia-portfolio`
3. В налаштуваннях:
   - **Framework Preset**: `Other`
   - **Root Directory**: `.` (крапка, тобто корінь)
   - **Build Command**: залиш порожнім
   - **Output Directory**: залиш порожнім
4. Натисни **Deploy**

### Крок 3 — Відкрий доступ

1. Vercel → Settings → **Deployment Protection**
2. **Vercel Authentication** → **Disabled**
3. Save

✅ Сайт доступний за посиланням типу `https://nataliia-portfolio.vercel.app`

---

## ✏️ Що оновити на сайті

Відкрий `index.html` у будь-якому текстовому редакторі (VS Code, Notepad++)
і знайди через Ctrl+F:

| Що знайти | На що замінити |
|---|---|
| `mishanagorichny@gmail.com` | твій email (вже вставлено) |
| `https://linkedin.com/in/` | твій LinkedIn |
| `https://behance.net/` | твій Behance |
| `https://t.me/` | твій Telegram |

---

## 🔄 Оновлення сайту

Після змін просто завантаж новий `index.html` на GitHub:
GitHub → репозиторій → `index.html` → редагувати або замінити файл.
Vercel автоматично оновить сайт за 1–2 хвилини.

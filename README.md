# 🛍️ EcoTote Project — Responsive Promo Website

## 📄 Опис проєкту

**EcoTote Project** — це промо-сайт бренду екологічних сумок із фокусом на
стиль, практичність та відповідальне споживання. Сайт презентує асортимент
товарів, переваги продукту, фото-галерею, відгуки клієнтів і блок для звʼязку.
Проєкт адаптований для мобільних, планшетних і десктопних екранів.

## 🔗 Посилання

- [GitHub Repository](https://github.com/vitaliifedunyk/eco-tote-project)
- [Live Demo](https://vitaliifedunyk.github.io/eco-tote-project/)

## 🧩 Можливості

- Адаптивна верстка (mobile-first) для `320px+`, `768px+`, `1440px+`.
- Багатосекційна односторінкова структура: Hero, About, Advantages, Assortment,
  Gallery, Feedbacks, Support, Footer.
- Мобільне бургер-меню з відкриттям/закриттям і блокуванням прокрутки фону.
- Плавна навігація якірними посиланнями між секціями.
- Каталог із 8 товарами (назва, опис, ціна, кнопка «Купити»).
- Форма зворотного зв’язку з базовою HTML-валідацією полів.
- Респонсивні зображення через `<picture>` та `srcset`.
- Контактні дані та соціальні посилання у хедері/футері.

## 🛠 Tech Stack

- HTML5
- CSS3 (PostCSS)
- JavaScript (ES Modules)
- Vite

## 📁 Структура проєкту

```text
eco-tote-project/
├── src/
│   ├── index.html
│   ├── main.js
│   ├── css/
│   │   ├── styles.css
│   │   └── *.css (стилі секцій)
│   ├── partials/
│   │   └── *.html (секції сторінки)
│   ├── img/
│   │   ├── icons.svg
│   │   └── ... (зображення секцій)
│   └── public/
│       └── favicon.svg
├── package.json
└── vite.config.js
```

## 🚀 Локальний запуск

```bash
npm install
npm run dev
```

Збірка для продакшену:

```bash
npm run build
npm run preview
```

## 👥 Команда

- **Vitalii Fedunyk** — Team Lead, секція `about`
- **Alina Kozlyuk** — Scrum Master, секція `feedbacks`
- **Slava Sobchuk** — секції `header`, `menu`
- **Andriy Proshak** — секція `assortment`
- **Sergio Shambir** — секція `support`
- **Kateryna Ognieva** — секція `advantages`
- **Vladislav Petrov** — секція `hero`
- **Stanislaw Skilskyy** — секція `footer`
- **Bronislav Lipinskyi** — секція `gallery`

## 📌 Notes

Проєкт виконано в команді в рамках фінального завдання після курсу HTML/CSS від
GoIT.

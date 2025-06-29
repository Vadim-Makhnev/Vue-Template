# 🧩 MVP-Проект на Vue 3 + Vite + SCSS

Этот документ описывает минимальную, но организованную архитектуру проекта, подходящую для создания MVP (минимально жизнеспособного продукта) на основе **Vue 3**, **Vite**, **SCSS**, **Pinia** и **Vue Router**.

## 📁 Общая структура проекта

src/
├── assets/
│ └── styles/  
│ ├── base/
│ │ ├── \_reset.scss
│ │ ├── \_typography.scss
│ │ └── \_variables.scss
│ ├── components/
│ │ ├── \_button.scss
│ │ └── \_input.scss
│ ├── layout/
│ │ └── \_header.scss
│ ├── pages/
│ │ └── \_home.scss
│ ├── utils/
│ │ └── \_mixins.scss
│ └── main.scss  
├── components/  
│ ├── Button.vue
│ └── Input.vue
├── views/  
│ └── HomeView.vue
├── router/  
│ └── index.js
├── stores/  
│ └── useCounterStore.js
├── App.vue
└── main.js

---

## 🎨 Стили (`styles/`)

### Папки и их назначение:

| Папка         | Назначение                                                 |
| ------------- | ---------------------------------------------------------- |
| `base/`       | Базовые стили: сброс (`reset`), типографика, переменные    |
| `components/` | Стили отдельных компонентов (например, кнопки, поля ввода) |
| `layout/`     | Макеты (шапка, подвал, навигация)                          |
| `pages/`      | Стили конкретных страниц                                   |
| `utils/`      | Вспомогательные миксины и функции                          |
| `main.scss`   | Главный файл, который импортирует все стили                |

## Установка зависимостей

```js
npm install

npm run dev
```

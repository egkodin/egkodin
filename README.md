<p align="center">
  <img src="./assets/profile-header.svg" width="100%" alt="Егор Овечкин — разработчик серверных систем и настольных приложений">
</p>

<p align="center">
  <a href="https://t.me/egor_kodin">
    <img src="https://img.shields.io/badge/Telegram-@egor__kodin-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>
  <a href="mailto:egor.coden@mail.ru">
    <img src="https://img.shields.io/badge/%D0%9F%D0%BE%D1%87%D1%82%D0%B0-egor.coden%40mail.ru-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Электронная почта">
  </a>
  <a href="https://github.com/egkodin/resume">
    <img src="https://img.shields.io/badge/%D0%A0%D0%B5%D0%B7%D1%8E%D0%BC%D0%B5-%D0%BE%D1%82%D0%BA%D1%80%D1%8B%D1%82%D1%8C-7C3AED?style=for-the-badge&logo=readme&logoColor=white" alt="Открыть резюме">
  </a>
</p>

<p align="center">
  <strong>Создаю надёжные серверные системы · Разрабатываю нативные инструменты на Rust · Учусь, выпуская реальные проекты</strong>
</p>

| [Обо мне](#обо-мне) | [Проекты](#проекты) | [Стек](#стек-и-технологии) | [Путь](#путь-разработчика) | [Статистика](#статистика) | [Контакты](#контакты) |
|:---:|:---:|:---:|:---:|:---:|:---:|

---

## Обо мне

Я **Егор Овечкин** — разработчик, которому интересен весь путь продукта: от пользовательского сценария и структуры данных до обработки ошибок, тестов, развёртывания и понятной документации.

Мой основной опыт связан с **серверной разработкой на Python**, PostgreSQL и Linux. Сейчас я расширяю его в сторону **Rust** и нативных настольных приложений.

> Я не собираю технологии ради списка. Мне интереснее превращать идею в систему, которой можно пользоваться, которую можно поддерживать и которой можно доверять данные.

```text
ТЕКУЩИЙ ВЕКТОР
├── создаю        → Saturn: серверная логика, данные, функции реального времени
├── исследую      → Taglet: Rust, нативный интерфейс, локальная работа с файлами
├── улучшаю       → архитектура, тестирование, инфраструктура Linux
└── следующий шаг → первая профессиональная роль в IT или стажировка
```

### Что мне особенно интересно

- проектировать понятную серверную логику и API;
- работать с данными, миграциями и PostgreSQL;
- создавать безопасные локальные инструменты на Rust;
- находить ошибки через реальные пользовательские сценарии;
- автоматизировать рутину и упрощать сложные процессы;
- доводить документацию, запуск и эксплуатацию до понятного состояния.

---

## Проекты

### 🪐 [Saturn](https://github.com/egkodin/saturn) — социальная платформа для совместной работы людей и ИИ

Мой главный серверный проект и основная площадка для системной разработки. В Saturn я связываю архитектуру, данные, авторизацию, взаимодействие в реальном времени, инфраструктуру и тестирование в один продукт.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy">
  <img src="https://img.shields.io/badge/WebSocket-6366F1?style=flat-square" alt="WebSocket">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest">
</p>

**Что внутри:** пользователи и профили, авторизация, публикации, комментарии, реакции, уведомления, поиск, чат, WebSocket, панель администратора, миграции Alembic, Docker Compose, nginx и автоматические тесты.

**Почему этот проект важен:** Saturn научил меня смотреть на приложение не как на набор обработчиков запросов, а как на систему с состоянием, правами доступа, пользовательскими ожиданиями, ошибками и жизненным циклом данных.

---

### 🎵 [Taglet](https://github.com/egkodin/taglet) — нативный редактор метаданных MP3 на Rust

Небольшое приложение, ориентированное на локальную и безопасную работу с ID3v2-метаданными. Taglet обрабатывает файлы непосредственно на устройстве, не использует встроенный браузер и создаёт резервную копию до первой записи.

<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/egui-7C3AED?style=flat-square" alt="egui">
  <img src="https://img.shields.io/badge/ID3v2-22C55E?style=flat-square" alt="ID3v2">
  <img src="https://img.shields.io/badge/lofty-0891B2?style=flat-square" alt="lofty">
  <img src="https://img.shields.io/badge/Cargo-F59E0B?style=flat-square&logo=rust&logoColor=white" alt="Cargo">
</p>

**Что реализовано:** редактирование основных тегов, работа с обложками JPEG и PNG, перетаскивание файлов, открытие из командной строки, светлая и тёмная темы, защита несохранённых изменений и отображение характеристик аудио.

**Почему этот проект важен:** Taglet стал переходом от ранних экспериментов с графическими интерфейсами к нативному приложению с валидацией, обработкой ошибок, безопасным сохранением и вниманием к пользовательским данным.

### Ещё несколько точек на карте

- 🏫 **[1358.space](https://github.com/egkodin/1358.space)** — первый крупный веб-проект с реальными пользователями, обратной связью, чатом и несколькими итерациями продукта.
- 📝 **[blog_django](https://github.com/egkodin/blog_django)** — приложение на Django с регистрацией, авторизацией, профилями и панелью администратора.
- 🧰 **[Textoom](https://github.com/egkodin/Textoom)** — ранний текстовый редактор на Python и Tkinter.
- 📅 **[pylendar](https://github.com/egkodin/pylendar)** — практика создания графических интерфейсов и работы со стандартной библиотекой Python.
- 🌐 **[ru-split-amneziavpn](https://github.com/egkodin/ru-split-amneziavpn)** — практическая работа с сетевыми маршрутами и инструментами Linux.

---

## Стек и технологии

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,rust,fastapi,django,postgres,docker,linux,git,github,nginx,html,css,js&theme=dark&perline=13" alt="Иконки используемых технологий">
</p>

**Серверная разработка** · Python · FastAPI · Django · REST API · WebSocket  
**Данные** · PostgreSQL · SQL · SQLAlchemy · Alembic  
**Настольные приложения** · Rust · Cargo · eframe/egui · локальная работа с файлами  
**Инфраструктура** · Linux · Docker Compose · nginx · Git  
**Качество** · pytest · cargo test · Clippy · проверка пользовательских сценариев  
**Веб-основа** · HTML · CSS · JavaScript · адаптивная вёрстка

### Мой инженерный компас

- **Сначала сценарий** — сперва понимаю, что пользователь пытается сделать, и только потом строю структуру кода.
- **Данные требуют защиты** — проверка входных данных, миграции, резервные копии и предсказуемые ошибки являются частью продукта.
- **Простые системы должны оставаться простыми** — не добавляю инфраструктуру или абстракции без реальной причины.
- **Документация — часть интерфейса** — хороший README и понятный запуск экономят время не меньше, чем хороший API.

---

## Путь разработчика

### 2020 → 2023 · от сайта к реальным пользователям

Начал с небольших Python-приложений и сайтов, затем создал школьный веб-портал с формой обратной связи, ручной модерацией и онлайн-чатом. После пользовательской обратной связи переработал приватность, убрал чувствительные данные и продолжил развивать продукт.

Проект менял направление, дизайн, хостинг и технологии. Я пробовал Ruby и Go, добавлял функции на основе ИИ, выступал с проектом и получил призовое место. Главным результатом стал не конкретный стек, а понимание: программное обеспечение живёт дольше первого выпуска и меняется вместе с обратной связью.

### 2024 → 2026 · серверная разработка, инфраструктура и нативные приложения

Стал системнее оформлять проекты: Docker, миграции, тесты, документация, понятный запуск и структура репозиториев. Saturn дал практику работы над крупной серверной системой, а Taglet открыл направление Rust и локальной настольной разработки.

Сейчас мой фокус — превращать накопленный самостоятельный опыт в профессиональную инженерную практику внутри команды.

---

## Статистика

<p align="center">
  <img src="./assets/profile-stats.svg" width="100%" alt="Статистика профиля Егора Овечкина">
</p>

Статистика оформлена как локальная SVG-карточка внутри репозитория. Она не зависит от ограничений или доступности сторонних сервисов.

---

## Контакты

Я открыт к первой профессиональной роли в IT, стажировке или технической позиции, где ценятся любознательность, ответственность и готовность разбираться в реальных задачах.

<p align="center">
  <a href="https://t.me/egor_kodin">
    <img src="https://img.shields.io/badge/%D0%9D%D0%B0%D0%BF%D0%B8%D1%81%D0%B0%D1%82%D1%8C%20%D0%B2%20Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Написать в Telegram">
  </a>
  <a href="mailto:egor.coden@mail.ru">
    <img src="https://img.shields.io/badge/%D0%9E%D1%82%D0%BF%D1%80%D0%B0%D0%B2%D0%B8%D1%82%D1%8C%20%D0%BF%D0%B8%D1%81%D1%8C%D0%BC%D0%BE-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Отправить письмо">
  </a>
</p>

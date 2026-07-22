<p align="center">
  <img src="./assets/profile-header.svg" width="100%" alt="Egor Ovechkin — Backend and Desktop Developer">
</p>

<p align="center">
  <a href="https://t.me/egor_kodin">
    <img src="https://img.shields.io/badge/Telegram-@egor__kodin-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram">
  </a>
  <a href="mailto:egor.coden@mail.ru">
    <img src="https://img.shields.io/badge/Email-egor.coden%40mail.ru-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://github.com/egkodin/resume">
    <img src="https://img.shields.io/badge/Résumé-open-7C3AED?style=for-the-badge&logo=readme&logoColor=white" alt="Resume">
  </a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2800&pause=900&color=8B5CF6&center=true&vCenter=true&width=820&lines=Building+reliable+backend+systems;Creating+native+desktop+tools+with+Rust;Learning+by+shipping+real+projects" alt="Animated developer focus">
</p>

<p align="center">
  <a href="#about">Обо мне</a> ·
  <a href="#projects">Проекты</a> ·
  <a href="#stack">Стек</a> ·
  <a href="#journey">Путь</a> ·
  <a href="#contact">Контакты</a>
</p>

---

<a id="about"></a>

## 〔01〕 Обо мне

Я **Егор Овечкин** — разработчик, которому интересен весь путь продукта: от пользовательского сценария и структуры данных до обработки ошибок, тестов, развёртывания и понятной документации.

Мой основной опыт связан с **Python backend-разработкой**, PostgreSQL и Linux. Сейчас я расширяю его в сторону **Rust** и нативных desktop-приложений — без webview, облачной зависимости и лишней сложности.

> Я не собираю технологии ради списка. Мне интереснее превращать идею в систему, которой можно пользоваться, которую можно поддерживать и которой можно доверять данные.

```text
CURRENT VECTOR
├── build      → Saturn: backend, data, realtime features
├── explore    → Taglet: Rust, native UI, local file processing
├── improve    → architecture, testing, Linux infrastructure
└── next step  → first professional IT role / internship
```

### Что мне особенно интересно

- проектировать понятную серверную логику и API;
- работать с данными, миграциями и PostgreSQL;
- создавать безопасные локальные инструменты на Rust;
- находить ошибки через реальные пользовательские сценарии;
- автоматизировать рутину и упрощать сложные процессы;
- доводить README, запуск и эксплуатацию до понятного состояния.

---

<a id="projects"></a>

## 〔02〕 Featured projects

### 🪐 [Saturn](https://github.com/egkodin/saturn) — социальная платформа для совместной работы людей и ИИ

Мой главный backend-проект и основная площадка для системной разработки. В Saturn я связываю серверную архитектуру, данные, авторизацию, realtime-взаимодействие, инфраструктуру и тестирование в один продукт.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy">
  <img src="https://img.shields.io/badge/WebSocket-realtime-6366F1?style=flat-square" alt="WebSocket">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest">
</p>

**Что внутри:** пользователи и профили, авторизация, публикации, комментарии, реакции, уведомления, поиск, чат, WebSocket, админ-панель, Alembic-миграции, Docker Compose, nginx и автоматические тесты.

**Почему этот проект важен:** Saturn научил меня смотреть на приложение не как на набор endpoints, а как на систему с состоянием, правами доступа, пользовательскими ожиданиями, ошибками и жизненным циклом данных.

---

### 🎵 [Taglet](https://github.com/egkodin/taglet) — нативный MP3 metadata editor на Rust

Небольшое local-first приложение для безопасного редактирования ID3v2-метаданных. Taglet работает с файлами напрямую на устройстве, не использует webview и создаёт резервную копию до первой записи.

<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/egui-native_UI-7C3AED?style=flat-square" alt="egui">
  <img src="https://img.shields.io/badge/ID3v2-metadata-22C55E?style=flat-square" alt="ID3v2">
  <img src="https://img.shields.io/badge/local--first-no_cloud-0891B2?style=flat-square" alt="Local first">
  <img src="https://img.shields.io/badge/safe_writes-backup-F59E0B?style=flat-square" alt="Safe writes">
</p>

**Что реализовано:** редактирование основных тегов, работа с JPEG/PNG-обложками, drag-and-drop, открытие файла из CLI, светлая и тёмная темы, защита несохранённых изменений и отображение характеристик аудио.

**Почему этот проект важен:** Taglet стал переходом от ранних GUI-экспериментов к нативному приложению с валидацией, обработкой ошибок, безопасным сохранением и вниманием к пользовательским данным.

<p align="center">
  <a href="https://github.com/egkodin/saturn">
    <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=egkodin&repo=saturn&hide_border=true&bg_color=00000000&title_color=8B5CF6&text_color=94A3B8&icon_color=22D3EE" alt="Saturn repository card">
  </a>
  <a href="https://github.com/egkodin/taglet">
    <img width="49%" src="https://github-readme-stats.vercel.app/api/pin/?username=egkodin&repo=taglet&hide_border=true&bg_color=00000000&title_color=8B5CF6&text_color=94A3B8&icon_color=22D3EE" alt="Taglet repository card">
  </a>
</p>

### Ещё несколько точек на карте

- 🏫 **[1358.space](https://github.com/egkodin/1358.space)** — первый крупный веб-проект с реальными пользователями, обратной связью, чатом и несколькими итерациями продукта.
- 📝 **[blog_django](https://github.com/egkodin/blog_django)** — Django-приложение с регистрацией, авторизацией, профилями и админ-панелью.
- 🧰 **[Textoom](https://github.com/egkodin/Textoom)** — ранний текстовый редактор на Python/Tkinter.
- 📅 **[pylendar](https://github.com/egkodin/pylendar)** — практика GUI и стандартной библиотеки Python.
- 🌐 **[ru-split-amneziavpn](https://github.com/egkodin/ru-split-amneziavpn)** — практическая работа с сетевыми маршрутами и Linux-инструментами.

---

<a id="stack"></a>

## 〔03〕 Technology radar

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,rust,fastapi,django,postgres,docker,linux,git,github,nginx,html,css,js&theme=dark&perline=13" alt="Technology stack icons">
</p>

**Backend**  ·  Python · FastAPI · Django · REST API · WebSocket  
**Data**  ·  PostgreSQL · SQL · SQLAlchemy · Alembic  
**Desktop**  ·  Rust · Cargo · eframe/egui · local file processing  
**Infrastructure**  ·  Linux · Docker Compose · nginx · Git  
**Quality**  ·  pytest · cargo test · Clippy · scenario-based checks  
**Frontend foundation**  ·  HTML · CSS · JavaScript · responsive layout

### Мой инженерный компас

- **Flow first** — сначала понимаю, что пользователь пытается сделать, и только потом строю структуру кода.
- **Data deserves safety** — проверка входных данных, миграции, резервные копии и предсказуемые ошибки являются частью продукта.
- **Small systems should stay simple** — не добавляю инфраструктуру или абстракции без реальной причины.
- **Documentation is an interface** — хороший README и понятный запуск экономят время не меньше, чем хороший API.

---

<a id="journey"></a>

## 〔04〕 The journey

### 2020 → 2023 · от сайта к реальным пользователям

Начал с небольших Python-приложений и сайтов, затем создал школьный веб-портал с формой обратной связи, ручной модерацией и онлайн-чатом. После пользовательской обратной связи переработал приватность, убрал чувствительные данные и продолжил развивать продукт.

Проект менял направление, дизайн, хостинг и технологии. Я пробовал Ruby и Go, добавлял ИИ-функции, выступал с проектом и получил призовое место. Главным результатом стал не конкретный стек, а понимание: программное обеспечение живёт дольше первого релиза и меняется вместе с обратной связью.

### 2024 → 2026 · backend, инфраструктура и нативная разработка

Стал системнее оформлять проекты: Docker, миграции, тесты, документация, понятный запуск и структура репозиториев. Saturn дал практику большой серверной системы, а Taglet открыл направление Rust и local-first desktop-разработки.

Сейчас мой фокус — превращать накопленный самостоятельный опыт в профессиональную инженерную практику внутри команды.

---

## 〔05〕 GitHub signal

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=egkodin&show_icons=true&hide_border=true&include_all_commits=true&rank_icon=github&bg_color=00000000&title_color=8B5CF6&text_color=94A3B8&icon_color=22D3EE" alt="Egor's GitHub statistics">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=egkodin&layout=compact&hide_border=true&bg_color=00000000&title_color=8B5CF6&text_color=94A3B8" alt="Most used languages">
</p>

<p align="center">
  <img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=egkodin&bg_color=00000000&color=94A3B8&line=8B5CF6&point=22D3EE&area=true&hide_border=true" alt="GitHub contribution activity graph">
</p>

---

<a id="contact"></a>

## 〔06〕 Давайте создавать полезные системы

Я открыт к первой профессиональной IT-роли, стажировке или технической позиции, где ценятся любознательность, ответственность и готовность разбираться в реальных задачах.

<p align="center">
  <a href="https://t.me/egor_kodin">
    <img src="https://img.shields.io/badge/Написать_в_Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Contact on Telegram">
  </a>
  <a href="mailto:egor.coden@mail.ru">
    <img src="https://img.shields.io/badge/Отправить_email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Send an email">
  </a>
</p>

<p align="center">
  <sub>built with curiosity · refined through feedback · shipped from Linux</sub>
</p>

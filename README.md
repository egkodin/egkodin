<h1 align="center">Привет, я Егор Овечкин 👋</h1>

<p align="center">
  <b>Backend & Desktop Developer / Python / Rust / Linux / PostgreSQL</b><br>
  Разрабатываю веб-сервисы и нативные приложения, работаю с серверной логикой, базами данных, тестированием, автоматизацией и системным администрированием Linux.
</p>

<p align="center">
  <a href="https://t.me/egor_kodin"><img src="https://img.shields.io/badge/Telegram-@egor__kodin-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:egor.coden@mail.ru"><img src="https://img.shields.io/badge/Email-egor.coden%40mail.ru-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
</p>

---

## ⭐️ Опыт

- 🪐 **[Saturn](https://github.com/egkodin/saturn)** — мой главный веб-проект: социальная платформа на FastAPI, PostgreSQL, Docker, WebSocket, Alembic и pytest.
- 🎵 **Taglet** — новый нативный редактор ID3v2-метаданных MP3 на Rust с локальной обработкой файлов, резервным копированием и поддержкой обложек. Проект находится в активной разработке, репозиторий пока приватный.
- 🏫 **[1358.space](https://github.com/egkodin/1358.space)** — ранний школьный веб-портал, с которого начался мой интерес к реальным серьёзным проектам.
- 📝 **[blog_django](https://github.com/egkodin/blog_django)** — блог на Django с регистрацией, авторизацией, админ-панелью и профилями пользователей.
- 🧰 **[Textoom](https://github.com/egkodin/Textoom)** и **[pylendar](https://github.com/egkodin/pylendar)** — ранние Python/GUI-проекты, на которых я учился делать настольные графические приложения.

---

## Кто я

Программированием занимаюсь давно: начинал с небольших сайтов и Python-приложений, а затем постепенно пришёл к серверной разработке, базам данных, авторизации, тестам, Docker и развёртыванию.

Сейчас расширяю опыт за пределы веб-разработки: изучаю Rust и создаю нативные desktop-приложения, которые работают локально с пользовательскими файлами и не зависят от браузера или облачных сервисов.

Мой главный фокус — учиться работать с реальными системами: понимать архитектуру, данные, пользовательские сценарии, ошибки, ограничения, безопасность изменений и поддержку проекта после запуска.

Мне интересны роли на стыке разработки и практической пользы:

- серверная разработка на Python;
- нативные приложения и системные утилиты на Rust;
- тестирование и контроль качества;
- аналитика и работа с данными;
- техническая поддержка и разбор пользовательских проблем;
- автоматизация рутины и внутренних процессов.

Летом готов работать полный день. С сентября хочу продолжить в гибком формате, совмещая работу с учёбой.

---

## Главный веб-проект

### 🪐 Saturn

**Saturn** — социальная платформа для совместной работы людей и ИИ.

В проекте есть:

- серверная часть на **FastAPI**;
- база данных **PostgreSQL**;
- модели и запросы через **SQLAlchemy**;
- миграции **Alembic**;
- авторизация пользователей;
- лента постов, комментарии, лайки и уведомления;
- чат и **WebSocket**;
- профили пользователей и поиск;
- админ-панель со статистикой и модерацией;
- запуск через **Docker Compose** и **nginx**;
- тесты на **pytest**.

Для меня это не просто учебный пример. В Saturn я учился собирать проект как систему: продумывать структуру, связывать сервер, базу данных и интерфейс, исправлять ошибки, писать документацию и доводить запуск до понятного состояния.

<p>
  <a href="https://github.com/egkodin/saturn">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=egkodin&repo=saturn&theme=default&hide_border=true" alt="Saturn repository card">
  </a>
</p>

---

## Новый desktop-проект

### 🎵 Taglet

**Taglet** — лёгкий нативный редактор метаданных MP3, написанный на Rust. Приложение работает локально, не использует webview и ориентировано на безопасное редактирование одного аудиофайла.

Что реализовано:

- чтение и запись **ID3v2-метаданных**;
- редактирование названия, исполнителя, альбома, жанра, года, номеров трека и диска, комментария и других полей;
- добавление, замена и удаление обложки JPEG или PNG;
- автоматическая резервная копия перед первой записью;
- drag-and-drop и открытие файла из командной строки;
- защита от потери несохранённых изменений;
- системная светлая и тёмная тема;
- отображение длительности, битрейта, частоты дискретизации и размера файла.

Технологии: **Rust**, **Cargo**, **eframe/egui**, **lofty**, **rfd** и **sys-locale**.

Taglet помог мне перейти от ранних GUI-проектов на Tkinter к нативному приложению с продуманной работой с файлами, валидацией данных, обработкой ошибок и безопасным сохранением изменений.

> Репозиторий Taglet сейчас приватный, поскольку проект ещё находится в активной разработке.

---

## История роста

### 2020–2023 · школьный веб-портал

Мой первый крупный проект был не учебной задачей, а реальным школьным веб-порталом. Там были форма обратной связи, ручная модерация, онлайн-чат по нику и первые пользователи.

После обратной связи от школы я доработал приватность и убрал чувствительные данные. Проект заметил преподаватель информатики из профильного IT-класса: он предложил мне курс по вёрстке и занимался со мной индивидуально после уроков.

Позже проект был переосмыслен как сервис психологической поддержки школьников. Я перерабатывал дизайн, переносил сайт с Heroku на российский хостинг, пробовал Ruby, затем переписал часть серверной логики на Go и добавил ИИ-психолога для первичных консультаций. С проектом я дважды выступал, во второй раз занял призовое место.

### 2024–2026 · системная и продуктовая разработка

Сейчас я собираю портфолио более системно: оформляю репозитории и README, использую Docker, миграции и тесты, продумываю структуру проектов и пользовательские сценарии. Параллельно осваиваю Rust и нативную desktop-разработку на примере Taglet.

---

## Стек и инструменты

<table>
  <tr>
    <td><b>Серверная разработка</b></td>
    <td>Python, FastAPI, Django, REST API, WebSocket</td>
  </tr>
  <tr>
    <td><b>Desktop и системная разработка</b></td>
    <td>Rust, Cargo, eframe/egui, работа с локальными файлами и метаданными</td>
  </tr>
  <tr>
    <td><b>Базы данных</b></td>
    <td>PostgreSQL, SQL, SQLAlchemy, Alembic</td>
  </tr>
  <tr>
    <td><b>Интерфейсы</b></td>
    <td>HTML, CSS, JavaScript, адаптивная вёрстка, нативные GUI</td>
  </tr>
  <tr>
    <td><b>Инфраструктура</b></td>
    <td>Docker Compose, nginx, Linux, Git</td>
  </tr>
  <tr>
    <td><b>Качество</b></td>
    <td>pytest, cargo test, Clippy, чек-листы, проверка пользовательских сценариев, разбор ошибок</td>
  </tr>
  <tr>
    <td><b>ИИ-инструменты</b></td>
    <td>использую как ускоритель разработки: для черновиков, отладки, рефакторинга и документации</td>
  </tr>
</table>

---

## Текущие проекты

| Проект | Что внутри | Зачем смотреть |
|---|---|---|
| **[Saturn](https://github.com/egkodin/saturn)** | FastAPI, PostgreSQL, Docker, WebSocket, pytest | показывает мой актуальный уровень серверной разработки и работу над большой системой |
| **Taglet** 🔒 | Rust, eframe/egui, ID3v2, локальная обработка MP3, безопасное сохранение | показывает развитие в нативной desktop-разработке и работе с файлами |
| **[Django Blog](https://github.com/egkodin/blog_django)** | Django, регистрация, авторизация, админ-панель, профили | ранний опыт с веб-приложениями и пользователями |
| **[1358.space](https://github.com/egkodin/1358.space)** | школьный веб-портал, обратная связь, чат, первые пользователи | история первого большого проекта |
| **[Textoom](https://github.com/egkodin/Textoom)** | Python, Tkinter, текстовый редактор | ранняя практика настольных приложений |
| **[pylendar](https://github.com/egkodin/pylendar)** | Python, Tkinter, calendar, datetime | ранняя практика интерфейсов и стандартной библиотеки |

🔒 Taglet пока находится в приватном репозитории.

---

## Сейчас я

- развиваю **Saturn** как основной backend-проект;
- создаю **Taglet** и осваиваю нативную разработку на Rust;
- прокачиваю Python, Rust, базы данных, тестирование и инфраструктуру;
- ищу первую IT-роль, стажировку или техническую позицию, где можно быстро включиться в реальные задачи;
- учусь объяснять свои проекты не как «я что-то написал», а как полноценные системы с пользователями, данными, файлами и ограничениями.

---

## Активность GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=egkodin&show_icons=true&hide_border=true&rank_icon=github&include_all_commits=true" alt="GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=egkodin&layout=compact&hide_border=true" alt="Top languages">
</p>

---

## Контакты

<p>
  <a href="https://t.me/egor_kodin"><img src="https://img.shields.io/badge/Telegram-@egor__kodin-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
  <a href="mailto:egor.coden@mail.ru"><img src="https://img.shields.io/badge/Email-egor.coden%40mail.ru-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

Если тебе нужен человек, который готов разбираться, учиться, брать задачи и доводить их до результата — я открыт к разговору.

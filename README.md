<h1 align="center">Дмитрий Крайнов</h1>

<p align="center">
  <b>Fullstack-разработчик · Node.js / NestJS · React · Python</b><br>
  Production B2B-сервисы полного цикла: от проектирования БД и API<br>
  до запуска и эксплуатации в Docker/Linux-инфраструктуре.<br>
  <sub>Барнаул · удалённо · English B1</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI">
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white" alt="Elasticsearch">
</p>

---

## Обо мне

Fullstack-разработчик с опытом разработки и сопровождения **production B2B-сервисов полного цикла**:
от проектирования БД и API до запуска и эксплуатации в Docker/Linux-инфраструктуре.

Закрываю backend, frontend, интеграции и DevOps. Уверенно разбираюсь в чужом и legacy-коде,
проектирую микросервисную архитектуру, автоматизирую бизнес-процессы и поддерживаю стабильную
работу сервисов. Есть опыт **руководства небольшой командой и обучения сотрудников**.

---

## Ключевые навыки

| Направление | Технологии |
|---|---|
| **Backend** | Python (FastAPI, Flask) · TypeScript (NestJS) · Node.js (Express) · PHP / Bitrix · REST API, проектирование API · очереди задач (Celery / Redis) · webhooks |
| **Frontend** | React · Redux Toolkit · JavaScript (ES6+) · HTML5 · CSS · Jinja2 · jQuery |
| **Базы данных** | PostgreSQL (PostGIS) · MySQL · TypeORM · SQLAlchemy · SQL, проектирование схем БД |
| **DevOps / инфраструктура** | Docker · Docker Compose · Linux · Nginx · Apache · Portainer · systemd · Git |
| **Данные и логи** | Elasticsearch · Logstash · Kibana (ELK) · сбор и анализ логов · дашборды |
| **ML / RAG** | sentence-transformers · мультиязычные эмбеддинги · semantic search · кластеризация · RAG, RAGFlow (без платных LLM) |
| **Интеграции** | Guardant (лицензирование) · Telegram Bots / WebApp · Bitrix24 · ERP/CRM · DaData · Google Sheets |
| **Прочее** | Микросервисная архитектура · декомпозиция задач · управление разработкой · работа с legacy-кодом |

---

## Опыт

### Инженер-программист · Мск БЛ ГРУПП, Москва · `Февраль 2025 — настоящее время`

Развиваю и сопровождаю production-платформу выдачи лицензионных ключей на PHP/Bitrix
с микросервисной обвязкой и распределённой инфраструктурой из нескольких серверов и сервисов.

- Спроектировал и реализовал отдельный **сервис заказов и лицензий на NestJS + TypeORM + PostgreSQL**
  (модули `auth`, `order`, `product`, `guardant`) с REST API и авторизацией по токену.
- Интегрировал систему лицензирования **Guardant**: отдельный Node-сервис обмена с кассой
  и Guardant, запущенный как системный сервис.
- Поднял микросервис `manufacturer_api` (Node.js/Express) с авторизацией по API-ключу
  и валидацией/санитизацией входных данных.
- Построил **централизованный сбор и анализ логов** нативного приложения на стеке ELK: конвейер
  Logstash (`multiline` / `dissect` / `grok`) с гео-обогащением, Node-API поверх Elasticsearch
  и React-дашборд (Redux) с графиками активности пользователей.
- Автоматизировал ежедневные напоминания об активации лицензий через **systemd timer** — запуск
  PHP-скрипта и рассылка писем, с устойчивостью к перезагрузкам сервера.
- Развернул и веду внутреннюю **базу знаний на BookStack** (Docker, MariaDB, Nginx), фиксирую
  знания команды по инфраструктуре и сервисам.
- Управляю Docker-инфраструктурой: PHP, Apache/Nginx, MySQL/Percona, memcached, PostgreSQL,
  Portainer, Adminer.

**Стек:** PHP/Bitrix · NestJS (TypeScript) · Node.js/Express · React · PostgreSQL · MySQL ·
Docker Compose · Nginx/Apache · Elasticsearch/Logstash/Kibana · Guardant · Portainer · systemd ·
Linux · BookStack · Git

### Fullstack developer · ООО «СиСорт» · `Октябрь 2021 — настоящее время`

Разрабатываю внутренние корпоративные сервисы полного цикла: от анализа задачи и проектирования БД
до запуска, поддержки и доработок.

- Проектирую **REST API и структуры баз данных** под реальные бизнес-процессы: продажи, документы,
  личные кабинеты, справочники, интеграции.
- Разработал систему **автоматического формирования коммерческих предложений, договоров и счетов**
  на основе номенклатуры и услуг; сервис стандартизирует документы и снижает ручную работу менеджеров.
- Реализовал личные кабинеты, разграничение прав доступа, внутренние административные панели
  и интерфейсы для сотрудников.
- Разрабатывал **Telegram-ботов и Telegram WebApp** для внутренних сценариев, уведомлений
  и работы с пользователями.
- Писал скрапперы и сервисы обработки данных, интегрировал внешние API (CRM/ERP, справочники
  контрагентов, табличные источники).
- **Руководил небольшой командой разработчиков** и обучал сотрудников без опыта программирования:
  оценка задач, распределение нагрузки, контроль и согласование результата.

**Стек:** Python · FastAPI · Flask · JavaScript · React · Jinja2 · PostgreSQL · MySQL ·
Docker Compose · Linux · Nginx · Telegram Bots/WebApp · REST API · Git

---

## Проекты

### [Harvester News](https://github.com/ElipSide/harvester_news) — агрегация новостей в «события» через semantic RAG

`Python 3.12 (asyncio)` · `FastAPI` · `PostgreSQL/psycopg3 (async pool)` · `sentence-transformers (MiniLM, 384-dim)` · `PyTorch (CPU)` · `RAGFlow` · `React` · `TypeScript` · `Vite` · `Docker Compose` · `Nginx`

- Спроектировал и реализовал **асинхронный конвейер из 6 этапов**: отбор качественных новостей →
  semantic clustering → синтез карточки события → гейтинг `active`/`weak` → построение графа связей
  и сюжетов → эго-граф сюжета по запросу для таймлайна на фронте.
- **Кластеризация по смыслу с предохранителем**: объединение по косинусной близости 384-мерных
  эмбеддингов только при общем «якоре» (имя / мера / число) и во временном окне; событие активируется
  при **≥3 независимых источниках**. Алгоритм детерминированный, CPU-only.
- Построил **предрасчёт сюжетного графа**: сила связи событий = IDF-перекрытие граней + TF-IDF
  сходство текста в окне дней, жадная нарезка на сюжеты-деревья; результат пишется в Postgres
  и рисуется как таймлайн.
- Добавил **RAGFlow-генерацию статей** по событию с маршрутизацией промтов по темам (реестр архетипов)
  и веб-лабораторию промтов (**PromptLab**). Всё работает на open-source моделях локально —
  без OpenAI и платных embedding-API.
- Фронтенд на React/TypeScript/Vite: лента, карточки событий, граф, фильтры, impact-чипы, мобильная
  вёрстка, оптимизация скорости страниц. Развёртывание из 3 сервисов в Docker Compose за внешним Nginx.

### [RailMap](https://github.com/ElipSide/railmap) — платформа мультимодальной логистики и геоаналитики

`React` · `Vite` · `Node.js/Express` · `PostgreSQL` · `PostGIS` · `pgRouting` · `MapLibre GL` · `Tegola` · `Docker Compose` · `DaData`

- Веб-приложение для визуализации транспортной инфраструктуры: ж/д линии, станции, порты, элеваторы,
  автотранспорт и производственные площадки.
- Построение маршрутов авто, ж/д и мультимодальной цепочки **авто → ж/д → авто**; поиск деклараций
  и поставщиков по ИНН через DaData.
- Спроектировал Docker Compose-инфраструктуру: PostGIS, Node.js route API, Tegola tile server
  и React/Vite frontend.

### Платформа выдачи лицензионных ключей (l-i-n.ru) — production

`PHP/Bitrix` · `NestJS/TypeORM` · `Node.js/Express` · `PostgreSQL` · `MySQL` · `Guardant` · `Docker Compose` · `Nginx/Apache`

- **Микросервисная архитектура**: сайт на Bitrix, сервис заказов на NestJS, сервис производителя,
  Guardant API и отдельная БД заказов на PostgreSQL.
- Спроектировал REST API между frontend, backend и сервисами лицензирования с авторизацией
  по токену и API-ключу.
- Реализовал интеграцию с **Guardant и кассой** для генерации и выдачи лицензионных ключей.

### Система централизованного логирования и аналитики (ELK)

`Elasticsearch` · `Logstash` · `Kibana` · `Node.js/Express` · `React` · `Redux Toolkit` · `Python` · `Docker Compose` · `Nginx`

- Приём логов нативного приложения по HTTP и из файлов; пайплайн Logstash с `multiline` / `dissect` /
  `grok` и гео-обогащением событий.
- Node-API поверх Elasticsearch для метрик активности и React-дашборд с графиками (уникальные входы,
  первое появление пользователей).
- Python-утилита восстановления логов из архивов с разбором таймстампов в именах файлов.

### [Commercial Proposal Service](https://github.com/ElipSide/Commercial-proposal-service) — автоматизация КП, договоров и счетов

`FastAPI` · `PostgreSQL` · `REST API` · `OpenAPI/Swagger` · `HTML-to-PDF` · `JavaScript` · `Telegram Bot` · `Bitrix24` · `ERP` · `DaData` · `Google Sheets`

- Система ведения нескольких КП параллельно: управление позициями, скидками, условиями сделки
  и генерация PDF-документов.
- Доменная модель вокруг менеджера, КП, позиций и номенклатуры; интеграции с CRM/ERP — передача
  клиента, состава, суммы и статуса.
- Заложено расширение: подключение новых калькуляторов, CRM/ERP и white-label сценариев.

### Slide Builder Pro — нативный редактор документов и протоколов

`Vanilla JavaScript` · `HTML5` · `CSS` · `jsPDF` · `html2canvas` · `JSZip`

- **WYSIWYG-редактор без фреймворков**: блочная вёрстка, перетаскивание элементов между слайдами,
  многостраничная разметка, вставка изображений.
- Экспорт документа в PDF (jsPDF + html2canvas) и ZIP; структурированная модель документа
  (`slides` / `boxes`) в JSON.
- Генерация типовых протоколов (например, светотехнических расчётов) из заполняемых блоков.

### [Voice CRM](https://github.com/ElipSide/Voice-CRM) — CRM для управления очередями ИИ-обзвона

`Python` · `FastAPI` · `SQLAlchemy` · `PostgreSQL` · `Redis` · `Celery` · `Jinja2` · `Docker Compose` · `REST API` · `Webhooks`

- Реализовал **CRM полного цикла обзвона**: кампании, лиды, задачи на звонок, попытки, результаты
  разговоров, скрипты и стоп-лист; жизненный цикл лида и управление очередью.
- Построил асинхронную обработку на **Celery + Redis с раздельными очередями** (`calls`, `retries`,
  `results`, `recordings`, `notifications`) и Celery beat для контроля зависших звонков.
- **Интеграция с внешним сервером звонилки**: CRM отправляет команду `start_call` и принимает webhook
  с результатом, записью, транскриптом и извлечёнными данными; обновляет попытки/результаты
  и планирует retry.
- Спроектировал доменную модель (SQLAlchemy): `campaigns`, `leads`, `call_tasks`, `call_attempts`,
  `call_results`, `scripts`, `stop_list`, `dialer_numbers`, `campaign_events`; REST API и веб-интерфейс
  на Jinja2 — дашборд, очередь, кампании, лиды, история звонков.
- Реализовал retry-правила для недозвонов, управление промтами/скриптами и уведомления менеджеру
  о «горячих» лидах; развёртывание в Docker Compose.

<details>
<summary><b>Другие репозитории</b></summary>

<br>

| Проект | О чём | Стек |
|---|---|---|
| **[Transcription Service](https://github.com/ElipSide/Transcription-service)** | Транскрипция и диаризация аудио/видео: chunked-загрузка до 2 ГБ, прогресс по WebSocket, AI-отчёты, экспорт в PDF | FastAPI · React · WebSocket · whisper.cpp · NeMo MSDD |
| **[Notification Preferences Service](https://github.com/ElipSide/Notification-Preferences-Service)** | Настройки уведомлений: дефолты, персональные переопределения, quiet hours с таймзонами | TypeScript · Express · PostgreSQL |
| **[URL List Checking Service](https://github.com/ElipSide/URL-list-checking-service)** | Асинхронная проверка списка URL: лимит одновременных запросов, опрос статуса, отмена заданий | TypeScript · Express · React · Zustand |
| **[Harvester Sonification](https://github.com/ElipSide/Harvester-sonification)** | Сонификация агроданных ФГИС «Зерно»: показатели из живой БД превращаются в звук и видеоролик | FastAPI · PostgreSQL · nginx · Docker |
| **[Timesheet & Project Costs](https://github.com/ElipSide/timesheet-project-costs)** | Учёт трудозатрат и стоимости работ. Включает разбор чужого кода с обоснованием правок и индексов | .NET 8 · MongoDB · React · TypeScript |
| **[Blog on Smarty](https://github.com/ElipSide/blog-smarty)** | Блог на чистом PHP 8.1: категории, пагинация, похожие статьи, Docker-окружение | PHP 8.1 · MySQL · Smarty |

</details>

---

## Образование

**Алтайский государственный технический университет им. И. И. Ползунова**, Барнаул · `2021`

- Бакалавр — Факультет информационных технологий, `38.03.05` Бизнес-информатика
- Бакалавр — Факультет специальных технологий, `27.03.05` Инноватика

**Языки:** русский — родной · английский — B1

---

## Связаться

<!-- Чтобы добавить резюме на hh.ru, раскомментируйте строку ниже и подставьте свой ID:
[![hh.ru](https://img.shields.io/badge/hh.ru-Резюме-D6001C?style=flat-square)](https://hh.ru/resume/ВАШ_ID)
     Телефон из резюме намеренно не вынесен на публичную страницу — добавьте, если нужно:
     +7 (913) 090-04-90 -->

[![Telegram](https://img.shields.io/badge/Telegram-@mowler-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/mowler)
[![Email](https://img.shields.io/badge/Email-krajnovdima@mail.ru-005FF9?style=flat-square&logo=maildotru&logoColor=white)](mailto:krajnovdima@mail.ru)

**Формат работы:** удалённо, полная занятость · готов к редким командировкам
**Английский:** B1 — читаю документацию и переписываюсь свободно

Открыт к предложениям по fullstack- и backend-разработке. Готов обсудить задачу и показать код
подробнее — в том числе закрытые проекты на созвоне.

---

<details>
<summary><b>🇬🇧 In English</b></summary>

<br>

### About

I'm Dmitry Kraynov — a fullstack developer building and maintaining **production B2B services
end to end**: from database and API design to deployment and operations on Docker/Linux.
I cover backend, frontend, integrations and DevOps, work confidently with legacy code, design
microservice architectures and automate business processes. I have experience leading a small
team and onboarding developers.

Based in Barnaul, Russia · remote · English B1.

### Key skills

- **Backend** — Python (FastAPI, Flask), TypeScript (NestJS), Node.js (Express), PHP / Bitrix, REST API design, task queues (Celery / Redis), webhooks
- **Frontend** — React, Redux Toolkit, JavaScript (ES6+), HTML5, CSS, Jinja2, jQuery
- **Databases** — PostgreSQL (PostGIS), MySQL, TypeORM, SQLAlchemy, schema design
- **DevOps** — Docker, Docker Compose, Linux, Nginx, Apache, Portainer, systemd, Git
- **Data & logs** — Elasticsearch, Logstash, Kibana (ELK), log pipelines, dashboards
- **ML / RAG** — sentence-transformers, multilingual embeddings, semantic search, clustering, RAG, RAGFlow (no paid LLMs)
- **Integrations** — Guardant licensing, Telegram Bots / WebApp, Bitrix24, ERP/CRM, DaData, Google Sheets

### Selected projects

| Project | What it does | Stack |
|---|---|---|
| **[Harvester News](https://github.com/ElipSide/harvester_news)** | Six-stage async pipeline clustering news into events via local semantic RAG — anchored cosine clustering, ≥3 independent sources to activate an event, precomputed storyline graph, RAGFlow article generation. CPU-only, no paid LLM APIs | Python 3.12 · FastAPI · psycopg3 · sentence-transformers · PyTorch · RAGFlow · React |
| **[RailMap](https://github.com/ElipSide/railmap)** | Multimodal logistics and geoanalytics — rail/road/multimodal routing, declaration and supplier search by tax ID via DaData | PostGIS · pgRouting · Tegola · Node.js · React · MapLibre GL |
| **License key platform (l-i-n.ru)** | Production microservice architecture — Bitrix site, NestJS order service, manufacturer service, Guardant API integration and checkout | PHP/Bitrix · NestJS/TypeORM · Node.js · PostgreSQL · Guardant |
| **Centralized logging & analytics (ELK)** | Native-app log ingestion over HTTP and files, Logstash pipeline with multiline/dissect/grok and geo enrichment, React activity dashboards | Elasticsearch · Logstash · Kibana · Node.js · React · Redux Toolkit |
| **[Commercial Proposal Service](https://github.com/ElipSide/Commercial-proposal-service)** | Sales document automation — parallel proposals, PDF generation, CRM/ERP sync | FastAPI · PostgreSQL · Bitrix24 · DaData · Telegram Bot |

### Experience

**Software Engineer** · Msk BL GROUP, Moscow · `Feb 2025 — present`
Maintain and extend a production license-key platform (PHP/Bitrix) with a microservice layer across
several servers. Built an order and license service on NestJS + TypeORM + PostgreSQL, integrated the
Guardant licensing system and the checkout, stood up a `manufacturer_api` microservice, and built
centralized log collection and analytics on ELK with a React/Redux activity dashboard. Manage the
Docker infrastructure and an internal BookStack knowledge base.

**Fullstack Developer** · SiSort LLC · `Oct 2021 — present`
Build internal corporate services end to end — requirements, database design, REST API, UI, deployment
and support. Delivered automated generation of commercial proposals, contracts and invoices; personal
accounts with role-based access; internal admin panels; Telegram bots and WebApps; scrapers and
integrations with CRM/ERP and external registries. Led a small development team and trained employees
with no prior programming background.

### Education

Polzunov Altai State Technical University, Barnaul · 2021 — BSc in Business Informatics
and BSc in Innovation Studies.

Remote only, full-time. Open to fullstack and backend roles.
Reach me at [krajnovdima@mail.ru](mailto:krajnovdima@mail.ru) or [@mowler](https://t.me/mowler).

</details>

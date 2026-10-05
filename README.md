<br clear="both">

<div align="center">
  <img height="200" src="https://media0.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" alt="coding" />
</div>

<h3 align="center">Привет, я Павел — Python Backend Developer</h3>

<div align="center">
  <a href="https://klepkin-pv-cv.vercel.app/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Portfolio&logo=vercel&label=&color=000000&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="portfolio" />
  </a>
  <a href="https://t.me/icehq" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Telegram&logo=telegram&label=&color=2CA5E0&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="telegram" />
  </a>
  <a href="mailto:klepkin.pv@mail.ru" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Mail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="mail" />
  </a>
</div>

---

<h3 align="left"> Обо мне</h3>

<p align="left">
Python Backend-разработчик с 3+ годами коммерческого опыта. Специализируюсь на backend-сервисах, Telegram-ботах, интеграциях со сторонними API и автоматизации бизнес-процессов.<br><br>
- Разрабатываю REST и асинхронные API на FastAPI и Django<br>
- Строю фоновые задачи: Celery, Redis, RabbitMQ, asyncio<br>
- Проектирую БД и работаю с PostgreSQL, Redis, ClickHouse<br>
- Контейнеризую сервисы в Docker и настраиваю CI/CD<br>
- Интегрирую Telegram Bot API, Google API, YooKassa, TrueAPI (Честный ЗНАК)<br>
- Сейчас углубляю AWS serverless (Lambda, SQS, DynamoDB, Terraform), ClickHouse и распределённые системы
</p>

---

<h3 align="left"> Технологии</h3>

<h4 align="left"> Backend</h4>

<table>
<tr>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="Python" /><br/>Python</td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" height="40" alt="FastAPI" /><br/>FastAPI</td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" height="40" alt="Django" /><br/>Django</td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlalchemy/sqlalchemy-original.svg" height="40" alt="SQLAlchemy" /><br/>SQLAlchemy</td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="40" alt="PostgreSQL" /><br/>PostgreSQL</td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/redis/redis-original.svg" height="40" alt="Redis" /><br/>Redis</td>
<td align="center"><img src="https://cdn.simpleicons.org/celery/37814A" height="40" alt="Celery" /><br/>Celery</td>
<td align="center"><img src="https://cdn.simpleicons.org/rabbitmq/FF6600" height="40" alt="RabbitMQ" /><br/>RabbitMQ</td>
<td align="center"><img src="https://cdn.simpleicons.org/apachekafka/231F20" height="40" alt="Kafka" /><br/>Kafka</td>
<td align="center"><img src="https://cdn.simpleicons.org/telegram/26A5E4" height="40" alt="aiogram" /><br/>aiogram</td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytest/pytest-original.svg" height="40" alt="pytest" /><br/>pytest</td>
</tr>
</table>

<h4 align="left"> DevOps & Tools</h4>

<table>
<tr>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="40" alt="Docker" /><br/>Docker</td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="40" alt="Linux" /><br/>Linux</td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40" alt="Git" /><br/>Git</td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40" alt="GitHub" /><br/>GitHub</td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/githubactions/githubactions-original.svg" height="40" alt="GitHub Actions" /><br/>GH Actions</td>
<td align="center"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nginx/nginx-original.svg" height="40" alt="Nginx" /><br/>Nginx</td>
<td align="center"><img src="https://cdn.simpleicons.org/openapiinitiative/6BA539" height="40" alt="OpenAPI" /><br/>OpenAPI</td>
<td align="center"><img src="https://cdn.simpleicons.org/kubernetes/326CE5" height="40" alt="Kubernetes" /><br/>Kubernetes</td>
</tr>
</table>

---

<h3 align="left"> Пет-проекты</h3>

<p align="left"><i>Коммерческие проекты закрыты NDA — здесь личные работы для практики.</i></p>

** AWS Transcribe Pipeline**

Serverless-пайплайн асинхронной обработки на AWS: файлы загружаются в S3 по presigned URL, проходят через очередь SQS и воркеры на Lambda, транскрибируются AWS Transcribe, скорятся LLM (Bedrock за интерфейсом провайдера), состояние в DynamoDB. Отказоустойчивость: DLQ с redrive, идемпотентность на условных записях, алармы и дашборд в CloudWatch. Вся инфраструктура — Terraform.

`AWS` `Lambda` `API Gateway` `DynamoDB` `SQS` `Terraform` `FastAPI`

[GitHub](https://github.com/klepkin-pv/aws-transcribe-pipeline)

&nbsp;

** Async Wallet API**

Асинхронный FastAPI для управления кошельками: роли, idempotency key для операций, SQLAlchemy async + PostgreSQL.

`FastAPI` `asyncio` `PostgreSQL` `JWT` `pytest`

[GitHub](https://github.com/klepkin-pv/async-wallet-api)

&nbsp;

** Auction Stats ClickHouse**

FastAPI + ClickHouse: сбор и агрегация статистики ставок, ETL, Docker Compose, REST API, pytest.

`FastAPI` `ClickHouse` `Docker Compose` `ETL` `pytest`

[GitHub](https://github.com/klepkin-pv/auction-stats-clickhouse)

&nbsp;

---

<div align="center">
  <a href="https://github.com/klepkin-pv" target="_blank">
    <img src="https://img.shields.io/static/v1?message=All+Projects&logo=github&label=&color=181717&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="all projects" />
  </a>
  <a href="https://klepkin-pv-cv.vercel.app/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Portfolio&logo=vercel&label=&color=000000&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="portfolio" />
  </a>
</div>

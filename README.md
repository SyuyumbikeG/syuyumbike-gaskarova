# Привет, я Сююмбике 👋

**Data Engineer** · Казань, Россия · открыта к предложениям (удалённо / гибрид / офис)

---

## 👩‍💻 Обо мне

Инженер данных с 10-летним опытом в авиастроении и сильным инженерным бэкграундом. Прошла профессиональную переподготовку в Яндекс Практикуме по специальности «Инженер данных».

Реализовала 7 учебных проектов полного цикла: от проектирования DWH (STG/DDS/CDM, Data Vault, «снежинка») и интеграции источников через API/S3/Kafka до построения инкрементальных витрин в Vertica и PostgreSQL и развёртывания микросервисов в Kubernetes.

Ищу позицию Data Engineer, где смогу применить инженерный подход к данным и расти в сторону проектирования DWH и работы с Big Data.

---

## 🛠️ Технологии и инструменты

**Языки и БД:** Python · SQL · PostgreSQL · Vertica · ClickHouse

**Data Engineering:** ETL · DWH · Data Lake · Data Vault 2.0 · STG/DDS/CDM · «звезда» · «снежинка» · инкрементальные витрины · MERGE / upsert · CTE · оконные функции

**Big Data и стриминг:** Apache Spark (PySpark, Spark Structured Streaming) · Kafka · Hadoop · HDFS

**Оркестрация:** Apache Airflow

**Инфраструктура:** Docker · Kubernetes · Container Registry · S3 · Git · Linux

**BI:** Yandex DataLens

**Библиотеки:** Pandas · NumPy · Pytest

**Языки:** Русский (родной) · Английский (B2) · Французский (A1)

---

## 📂 Проекты

### 🏗️ [DWH для выплат курьерам](ссылка_на_репозиторий)
Многослойное хранилище STG → DDS → CDM с моделью «снежинка», интеграцией с API курьерской службы и витриной `cdm.dm_courier_ledger`. Расчёт выплат по рейтингу, чаевым и комиссиям.

`Python` `SQL` `Airflow` `PySpark` `PostgreSQL` `API` `DWH`

---

### 💱 [DWH финтех-стартапа на Vertica](ссылка_на_репозиторий)
STAGING-слой с проекциями, сортировкой и сегментированием по хеш-функции. Инкрементальная витрина `global_metrics` с ежедневным обновлением и агрегацией оборота компании в единой валюте.

`Vertica` `Airflow` `SQL` `DWH` `инкрементальные витрины`

---

### ☸️ [Микросервисы потоковой обработки в Kubernetes](ссылка_на_репозиторий)
Два Kafka-микросервиса для DDS- и CDM-слоёв: упаковка в Docker, публикация в Container Registry, развёртывание в Kubernetes. Дашборд в Yandex DataLens.

`Kafka` `Docker` `Kubernetes` `Python` `PostgreSQL` `DataLens`

---

### 🗄️ [Data Vault-хранилище соцсети](ссылка_на_репозиторий)
Хабы, линки и сателлиты с хеш-ключами. Загрузка из S3 в Vertica через Airflow, аналитика конверсии через CTE.

`Vertica` `Airflow` `S3` `Data Vault 2.0` `SQL`

---

### 🔄 [Интеграция нового источника в DWH](ссылка_на_репозиторий)
`MERGE` для измерений и фактов, инкрементальная витрина по заказчикам с медианой, оконными функциями и топ-категориями.

`SQL` `PostgreSQL` `DWH` `оконные функции`

---

### 📡 [Spark Structured Streaming для push-уведомлений](ссылка_на_репозиторий)
Стриминговое приложение на PySpark: чтение из Kafka, stream-static JOIN с Postgres, запись в два сто́ка через `foreachBatch`, идемпотентность.

`PySpark` `Kafka` `PostgreSQL` `Docker` `стриминг`

---

### 🌍 [Data Lake с геоаналитикой соцсети](ссылка_на_репозиторий)
Data Lake в HDFS, геопривязка событий по формуле гаверсинусов, витрины в разрезе пользователей и зон, автоматизация в Airflow.

`PySpark` `HDFS` `Airflow` `Big Data` `геоаналитика`

---

### 🛒 [ETL e-commerce с витриной retention](ссылка_на_репозиторий)
Инкрементальная загрузка из API и S3 в PostgreSQL, обработка статусов `shipped/refunded`, витрина customer retention.

`Airflow` `API` `S3` `PostgreSQL` `ETL`

---

## 📬 Контакты

- 📧 Email: syuyumbike.ilyasova@gmail.com
- 💬 Telegram: [@SyuyumbikeG]
- 💼 hh.ru: [https://kazan.hh.ru/resume/481f5cdcff113dcea00039ed1f747257396e4a]
- 📍 Казань, Россия

---

*Открыта к предложениям: Data Engineer · удалённо / гибрид / офис*

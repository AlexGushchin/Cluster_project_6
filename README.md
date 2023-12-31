# Проект 6. Сегментация клиентов магазина
## Оглавление
1. [Описание проекта](#1-описание-проекта)
2. [Какой кейс решаем](#2-какой-кейс-решаем)
3. [Краткая информация о данных](#3-краткая-информация-о-данных)
4. [Этапы работы над проектом](#4-этапы-работы-над-проектом)
5. [Результат](#5-результат)
6. [Выводы](#6-выводы)

### 1. Описание проекта
Преобразование, исследование и очистка данных в базе продаж магазина, сегментация клиентов.

### 2. Какой кейс решаем
Наша задача - преобразовать, исследовать и очистить базу продаж магазина для того, чтобы в дальнейшем можно было на ее основе построить модель кластеризации покупателей.

**Условия:**
* Количество кластеров должно быть от 3 до 10 включительно.
* Код и графики должны быть представлены в шаблоне Jupiter Notebook.
* Результаты должны быть выложены на GitHub.

**Что практикуем:**
* Кластеризация, методы понижения размерности.
* Написание кода в Python.
* Соблюдение стандартов PEP-8.
* Исследование структуры данных, их преобразование и очистка.
* Исследование зависимостей данных.
* Визуализация данных.
* Оформление проекта, создание файла README.
* Синхронизация репозитория с GitHub.

### 3. Краткая информация о данных
Данные представляют собой базу данных сделок магазина (541 909 строк) с указанием индивидуального кода операции, кода товара и его количества и цены, даты и времени сделки, индикатор клиента и его срана регистрации.

### 4. Этапы работы над проектом
* Этап 1. Базовый анализ структуры данных.
* Этап 2. Преобразование данных.
* Этап 3. Разведывательный анализ.
* Этап 4. Построение RFM-таблицы и поиск RFM-выбросов
* Этап 5. Кластеризация на основе RFM-характеристик
* Этап 6. Интерпретация результатов кластеризации
* Этап 7. Формулирование выводов.
* Этап 8. Создание README с описанием проекта и размещение результатов на GitHub.

### 5. Результат
Была выполнена кластеризация клиентов на основе RFM-таблицы.

### 6. Выводы
В рамках выполнения проекта был пройден полный цикл работ, которые выполняются в реальный DS-проектах. Были обработаны исходные данные, в дальнейшем на их основе несколькими способами были кластеризованы клиенты. Результаты кластеризации были визуализированные несколькими способами. 
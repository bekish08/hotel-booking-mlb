Модуль 1 (РК-1), Машинное обучение — данные для командных проектов

Проект 1. healthcare-dataset-stroke-data.csv  — 5110 строк, цель stroke
Проект 2. bank-additional-full.csv            — 41 188 строк, цель y, разделитель ";" (pd.read_csv(..., sep=";"))
Проект 3. adult.csv                           — 32 561 строка, цель income, пропуски записаны "?" (na_values="?")
Проект 4. hotel_bookings.csv                  — 119 390 строк, цель is_canceled

Положите файл рядом с ноутбуком и загружайте по имени: pd.read_csv("adult.csv", na_values="?")
В Colab: значок папки слева -> Загрузить файл.

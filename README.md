# encoding-converter
# Конвертер кодировок в UTF-8

Программа преобразует текстовый файл из одной из трёх кодировок (CP‑1251, KOI8‑R, ISO‑8859‑5) в UTF‑8.

## Требования
- Компилятор C, поддерживающий стандарт C11 (например, GCC, Clang, MSVC).
- Для сборки достаточно стандартной библиотеки C.

## Сборка
Откройте терминал в папке с проектом и выполните:
gcc -Wall -Wextra -Wpedantic -std=c11 -o converter main.c

## Использование
./converter <входной_файл> <кодировка> <выходной_файл>

## Примеры
./converter cp1251.txt CP1251 output_utf8.txt
./converter koi8.txt KOI8-R output_koi8.txt
./converter iso-8859-5.txt ISO-8859-5 output_iso.txt

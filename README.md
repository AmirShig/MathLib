# Описание выполненного проекта

## Введение

В рамках данного проекта была разработана собственная версия стандартной библиотеки math.h на языке программирования C. Эта библиотека реализует базовые математические операции, которые используются в различных алгоритмах. Проект включал изучение основ вычислительных методов и закрепление знаний структурированного программирования.

## Описание проекта

### Библиотека math.h

Библиотека math.h предоставляет набор функций для выполнения базовых математических операций. В рамках проекта были реализованы следующие функции:

- `int abs(int x)`: вычисляет абсолютное значение целого числа.
- `long double acos(double x)`: вычисляет арккосинус.
- `long double asin(double x)`: вычисляет арксинус.
- `long double atan(double x)`: вычисляет арктангенс.
- `long double ceil(double x)`: возвращает ближайшее целое число, не меньшее заданного значения.
- `long double cos(double x)`: вычисляет косинус.
- `long double exp(double x)`: возвращает e, возведенное в заданную степень.
- `long double fabs(double x)`: вычисляет абсолютное значение числа с плавающей точкой.
- `long double floor(double x)`: возвращает ближайшее целое число, не большее заданного значения.
- `long double fmod(double x, double y)`: возвращает остаток от деления чисел с плавающей точкой.
- `long double log(double x)`: вычисляет натуральный логарифм.
- `long double pow(double base, double exp)`: возводит число в заданную степень.
- `long double sin(double x)`: вычисляет синус.
- `long double sqrt(double x)`: вычисляет квадратный корень.
- `long double tan(double x)`: вычисляет тангенс.

## Требования и реализация

- Библиотека разработана на языке C стандарта C11 с использованием компилятора gcc.
- Код библиотеки находится в папке src на ветке develop.
- Не использовались устаревшие и унаследованные конструкции языка и функции библиотек.
- При написании кода придерживались стиля Google.
- Библиотека реализована в виде статической библиотеки (с заголовочным файлом math.h).
- Библиотека разработана в соответствии с принципами структурированного программирования, избегали дублирования кода.
- Подготовлено полное покрытие функций библиотеки юнит-тестами с использованием библиотеки Check.
- Код тестов и исполняемый файл находятся в папке src или её подпапках.
- Юнит-тесты проверяют результаты реализации путем сравнения их с реализацией стандартной библиотеки math.h.
- Юнит-тесты покрывают не менее 80% каждой функции (проверяется с помощью gcov).
- Предоставлен Makefile для сборки библиотеки и тестов (с целями all, clean, test, math.a, gcov_report).
- Цель gcov_report генерирует отчет gcov в виде HTML-страницы. Юнит-тесты должны запускаться с флагами gcov для этого.
- Запрещено копировать реализацию стандартной библиотеки math.h и использовать её где-либо, кроме юнит-тестов.
- Необходимо следовать логике стандартной библиотеки math.h (в плане проверок, работы с памятью и поведения в аварийных ситуациях — тесты помогут в этом).
- Общая проверяемая точность составляет 16 значащих цифр.
- Проверяемая точность дробной части составляет до 6 десятичных знаков.

## Заключение

В результате выполнения проекта была разработана функциональная библиотека math.h с реализацией базовых математических операций. Проект способствовал углублению знаний в области структурированного программирования и работы с библиотеками C.
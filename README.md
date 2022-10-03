# Итоговая Задача: 
Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры:
[“Hello”, “2”, “world”, “:-)”] → [“2”, “:-)”]
[“1234”, “1567”, “-2”, “computer science”] → [“-2”]
[“Russia”, “Denmark”, “Kazan”] → []

Алгоритм решения:
- Выполняется перебор значений массива. 
- В результате перебора поочередно проверяются значения массива на выполнение условия (длина строки меньше или равна 3).
- Значение которое выполняет условие фиксируется в новом массиве.
- После перебора всех значений выполняется вывод нового массива.

[Ссылка на схему алгоритма](https://app.diagrams.net/#G14YayGuz6oFdOXtC3rL7mrDrecyB7QxZP)


[Ссылка на код программы](https://github.com/Tatijana3004/FinalLessonSpecialization/blob/main/Program.cs)

## Инструкция:

1. Для запуска программы скачайте файл Program.cs и откройте его в VSC.
2. Запустите терминал с командной строкой.
3. В терминале введите команду:

**dotnet run** 

Далее введите все необходимые значения через пробел.

Пример ввода:

*2 hello sun 33 world*

Результат выполнения кода:

[2, hello, sun, 33, world] -> [2, sun, 33]
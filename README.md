**Задача**

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

**Алгоритм решения задачи**

Объявляем *два массива*: первый массив содержит набор элементов разной длины и второй массив такой же размерности что и первый. Пишу метод, в котором цикл осуществялет проверку условия ( <=3 ), если *"да"* элемент первого массива заносится в **count** элемент второго массива. Переменная **count** необходима, чтобы поочередно закидывать из первого массива во второй элементы, после проверки условия. После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.

Блок-схема метода находится в папке ***block diagram***.

Исполняемый код находится в **Program.cs**
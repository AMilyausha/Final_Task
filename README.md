# Итоговая контрольная задача:
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами. ["hello", "2", "world", ":-)"] -> ["2", ":-)"]

# Решение с описанием:
Cоздаём массив, создаём цикл,в цикле создаем условие и выводим если оно срабатывает

string[] array = {"hello", "2", "world", ":-)"}; // создаём  массив

for(int i = 0; i < array.Length; i++){ // создаём цикл 

if(array[i].Length <= 3)Console.Write($"{array[i]} "); } // создаем условие и выводим если оно срабатывает

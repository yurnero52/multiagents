# multiagents

Алгоритм решает задачу на нахождение среднего арифметического n чисел.

## Алгоритм:

Каждый агент оправляет всем своим соседям имеющиеся у него числа. Алгоритм останавливается когда у какого то агента собраны все числа.

## Оценки алгоритма

Число сообщений: O(n^2)
Память: O(n^2)
Число коммуникаций с центром: O(1)

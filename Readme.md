Программа для рассчета коэффициентов ДПФ (дискретное преобразование Фурье).

В функции signalFunction необходимо прописать функцию вашего сигнала.
На вход данной функции необходимо подавать кол-во отчетов. 

В функции signalFunction прописана функция x(n) = sin(2*pi*n/16) + cos(7*2*pi*n/16).
Для данной функции будет достаточно 16 отсчетов, так как далее значения будут повторяться. 

Данная программа расчитывает значение указанной функции при n = 0, 1, 2, ..., N - 1.

После этого по указанным значениям x(n) расчитывает X(k, {x(n)}) при k = 0, 1, 2, ..., N - 1. Это и есть коэффициенты дискретного преобразования Фурье.

Данные коэффициенты являются комплексными амплитудами синусоидальных составляющих. Из них можно найти действительную амплитуду и фазу синусоидальных составляющих. 
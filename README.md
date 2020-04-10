# SPOVM. Лабораторные работы
## Лабораторные работы по СПОВМу (БГУИР 4 семестр)
### ЛР1
#### Задание:
#####  Разработать консольное приложение, в котором базовый процесс порождает дочерний. Для каждого процесса предусмотрена своя область вывода, в которой он выводит текущее системное время. Работа выполняется в двух вариантах: под Linux и Windows.
### ЛР2
#### Задание:
#####  Начальный процесс является управляющим. Он принимает поток ввода с клавиатуры и контролирует дочерние процессы. По нажатию клавиши ‘+’ добавляется новый процесс, ‘-’ – удаляется последний добавленный, ‘q’ – программа завершается. Каждый дочерний процесс посимвольно выводит на экран в вечном цикле свою уникальную строку. При этом операция вывода строки должна быть атомарной, т.е. процесс вывода должен быть синхронизирован таким образом, чтобы строки на экране не перемешивались. Выполняется в двух вариантах: под Linux и Windows. В качества метода синхронизации использовать сигналы/события.

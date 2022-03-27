# minitalk
#### Целью этого проекта является кодирование небольшой программы обмена данными с использованием сигналов UNIX. Суть проекта создать коммуникационную программу в виде клиента и сервера.
* Сначала должен быть запущен сервер. После запуска он должен распечатать свой PID.
* Клиент принимает два параметра:
* PID сервера.
* Строка для отправки.
* Клиент должен отправить строку, переданную в качестве параметра, на сервер.
Как только строка получена, сервер должен ее распечатать.
* Сервер должен отображать строку довольно быстро. Быстро означает, что если вы думаете это занимает слишком много времени, тогда, вероятно, это слишком долго.
# Разрешенные функции: 
__write ft_printf signal sigemptyset sigaddset
sigaction kill getpid malloc free pause sleep usleep exit__

# Запуск програмы (mandatory)
* git clone minintalk
* cd minitalk/minitalk
* make
* ./minitalk

# Запуск програмы (bonus)
* git clone minintalk
* cd minitalk/minitalk_bonus
* make
* ./minitalk_bonus

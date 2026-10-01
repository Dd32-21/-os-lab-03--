Я ввел команду pstree -p и мне выдало дерево с номерами процессов, прилагаю скриншот 

<img width="644" height="255" alt="image" src="https://github.com/user-attachments/assets/65e10f92-919c-452e-a58d-ff5b8e23c0a5" />

Далее вставляю скриншот с оболочкой от текущего Pid до PID 1 

<img width="514" height="80" alt="image" src="https://github.com/user-attachments/assets/aff84e1b-5faf-48d7-97e0-2bd562e364f6" />

В корне у меня стоит процесс systemd у него нет родителя т.к этот процесс запускается самым первым ядром системы 
Далее я узнал сколько всего работает процессов в системе, прилагаю скриншот 

<img width="322" height="42" alt="image" src="https://github.com/user-attachments/assets/8d216f4a-980e-4375-a85e-85843e7fd12f" />

В система работает 258 процессов а большинство из них находится в s, т.к. это спящий режим и они ждут своего времени.

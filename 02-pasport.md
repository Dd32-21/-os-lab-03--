С помощью команды я вывел данные для паспорта процессов, прилагаю скриншот 

<img width="579" height="295" alt="image" src="https://github.com/user-attachments/assets/999e0d95-c29d-4707-a774-ba1442b80080" />

Далее прилагаю введенную команды с открытыми процессами 

<img width="620" height="126" alt="image" src="https://github.com/user-attachments/assets/64eeabba-2c42-4c55-b192-0c95301316bf" />

Дискрипторы 0,1,2 это стандартные дескрипторы ввода вывода процессов они указывают в на мой терминал .
До введенной командвы CD он указывал на каталог /root, но после того как ввел каталог поменялся на /etc, прилагаю скриншоты 

<img width="643" height="54" alt="image" src="https://github.com/user-attachments/assets/bf40a914-718b-4466-9fdd-f06ad5a10836" />
<img width="692" height="47" alt="image" src="https://github.com/user-attachments/assets/d9e41e64-a60a-4f09-bf36-a3cf17587d6d" />

Это связано с тем, что я этой командой сменил путь каталога с по умолчанию на etc 

Потому что ps и top инструменты для команды /proc они берут информацию именно с этой команды 

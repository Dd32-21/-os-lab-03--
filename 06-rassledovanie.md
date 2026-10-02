<img width="755" height="145" alt="image" src="https://github.com/user-attachments/assets/f7f1b1e0-7c97-4dcf-a2ad-4ef3d4dc678a" />

На данном скриншоте были внедрены два файла замаскированные под вирус сразу с выданным PID

Далее выдан список с процессами, прилагаю скриншот 

<img width="507" height="613" alt="image" src="https://github.com/user-attachments/assets/14f27854-709a-493d-be26-243ad6d22341" />

В нем был замечен подозрительный файл kworker т.к не подходит для написания стандартного kworkera  нужный скобки и запущен он от рут пользователя 
Фальшивый аргумент 3000 настоящий kworker такого аргумента не имеет, так же видно что он запущен с диска а должен находиться в ядре. А так же есть родитель 
Настоящий kworker запускается ядром. Прилагаю скриншоты. 

<img width="682" height="82" alt="image" src="https://github.com/user-attachments/assets/749c91ad-e12f-4f0d-a175-8732d99809ac" />
<img width="1004" height="90" alt="image" src="https://github.com/user-attachments/assets/381e6347-0bc5-4d8d-b758-7f8a8a8268ef" />
<img width="831" height="201" alt="image" src="https://github.com/user-attachments/assets/ec65c000-5eb8-4252-88ea-c69dac61acc4" />

Далее была выполнена команда прямого удаления KILL с указаным PID файла, прилагаю скриншот 

<img width="898" height="126" alt="image" src="https://github.com/user-attachments/assets/9f4cb37e-ae42-4069-bf6b-5586b3f308d1" />

Потому что /proc/PID/exe  показывает путь к файлу т.к эту инфу хранит ядро а не сама созданная программа т.е имя можно подделать но если путь не тот который нужен 
то программа скорее всего фальшивая 

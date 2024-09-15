1. Создадим отдельную директорию для лабораторной работы с помощью команды
```bash
mkdir laba-1
```
чтобы не было лишних файлов. С помощью команды `ls` убедимся, что директория создана:

![image](img1.png)


2. Перейдём в созданную директорию с помощью команды `cd laba-1`,  с помощью команды `pwd` убедимся, что находимся в нужной директории:

![image](img2.png)


3. Создадим новый файл с именем `script.bash` с помощью команды:
```bash
touch script.bash
```
С помощью команды `ls` убедимся, что файл создан

![image](img3.png)


4. При попытке открыть файл через текстовый редактор `gedit`, команда не была найдена:

![image](img4.png)

Стало ясно, что редактор gedit не установлен, поэтому воспользуемся встроенным текстовым редактором `vim`


5. Откроем файл с помощью команды
```bash
vim script.bash
```
Нажав клавишу `i` перейдём в режим вставки и вставим скрипт:

![image](img5.png)

Сохраним файл и закроем текстовый редактор `vim` с помощью `:wq`

6. Запускаем bash-скрипт, с помощью команды
```bash
bash script.bash
```

![image](img6.png)

Результатом того, что мы всё сделали верно, является отображение строки `Welcome to ITMO University`

7. Модифицируем файл `script.bash`

![image](img7.png)

Про команду `read` я узнала из дополнительного материала, прикреплённого к лабораторной работе.


8. Проверим работоспособность нашего скипта на нескольких примерах
   
![image](img8.png)




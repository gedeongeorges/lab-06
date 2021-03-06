## РОССИЙСКИЙ УНИВЕРСИТЕТ ДРУЖБЫ НАРОДОВ
## Факультет физико-математических и естественных наук 
### Кафедра прикладной информатики и теории вероятностей

### ОТЧЕТ ПО ЛАБОРАТОРНОЙ РАБОТЕ № 5

*дисциплина: Операционные системы*

**Студент: ГЕОРГЕС Гедеон** 
**Группа: НПМбд-02-20**

МОСКВА 2021 г.

# Цель работы :
ознакомиться с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобрести практические навыки по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.
# Ход работы:
1. Скопировал файл ~/abc1 в файл april и в файл may. Скопировал файлы april и may в каталог monthly. Скопировала файл monthly/may в файл с именем june. Скопировала каталог monthly в каталог monthly.00. Скопировала каталог monthly.00 в каталог /tmp.
![](https://raw.githubusercontent.com/gedeongeorges/lab-06/main/pictures06/lab6%2001.png)
(Рисунок 1)
2. Изменил название файла april на july в домашнем каталоге. Переместил файл july в каталог monthly.00. Переименовала каталог monthly.00 в monthly.01. Переместила каталог monthly.01в каталог reports. Переименовала каталог reports/monthly.01 в reports/monthly.
![](https://raw.githubusercontent.com/gedeongeorges/lab-06/main/pictures06/lab6%2002.png)
(Рисунок 2)
3. Воспользовалсь командой df, которая выведет на экран список всех файловых систем в соответствии с именами устройств, с указанием размера и точки монтирования, для определения объёма свободного пространства на файловой системе. С помощью команды fsck проверила целостность файловой системы.
![](https://raw.githubusercontent.com/gedeongeorges/lab-06/main/pictures06/lab6%2003.png)
(Рисунок 3)
4. Выполнил следующие действия, зафиксировав в отчёте по лабораторной работе используемые при этом команды и результаты их выполнения:
4. 1. Скопировал файл /usr/include/xorg/isdv4.h в домашний каталог, с помощью команды cp и назвала его equipment, с помощью команды mv. 
4. 2. В домашнем каталоге создала директорию ~/ski.plases.
![](https://raw.githubusercontent.com/gedeongeorges/lab-06/main/pictures06/lab6%2004.png)
(Рисунок 4)
4. 3. Переместил файл equipment в каталог ~/ski.plases командой mv.
4. 4. Переименовала файл ~/ski.plases/equipment в ~/ski.plases/equiplist командой mv.
4. 5. Создал в домашнем каталоге файл abc1 и скопировала его в каталог ~/ski.plases командой cp, назвала его equiplist2 командой mv.
![](https://raw.githubusercontent.com/gedeongeorges/lab-06/main/pictures06/lab6%2005.png)
(Рисунок 5)
4. 6. Создал каталог с именем equipment в каталоге ~/ski.plases командой mkdir.
4. 7. Переместил файлы ~/ski.plases/equiplist и equiplist2 в каталог ~/ski.plases/equipment командой mv.
4. 8. Создала и переместила каталог ~/newdir в каталог ~/ski.plases командами mkdir и  mv и назвала его plans командой mv.
![](https://raw.githubusercontent.com/gedeongeorges/lab-06/main/pictures06/lab6%2006.png) 
(Рисунок 6)
5. Определил опции команды chmod, необходимые для того, чтобы присвоить перечисленным ниже файлам выделенные права доступа, считая, что в начале таких прав нет. При необходимости создала нужные файлы.
5. 1. drwxr--r-- ... lab02.md
![](https://raw.githubusercontent.com/gedeongeorges/lab-06/main/pictures06/lab6%2008.png)
(Рисунок 7)
5. 2. drwx--x--x ... play
![](https://raw.githubusercontent.com/gedeongeorges/lab-06/main/pictures06/lab6%2009.png)
(Рисунок 8)
5. 3. -r-xr--r-- ... my_os
![](https://raw.githubusercontent.com/gedeongeorges/lab-06/main/pictures06/lab6%2010.png)
(Рисунок 9)
5. 4. -rw-rw-r-- ... feathers
![](https://raw.githubusercontent.com/gedeongeorges/lab-06/main/pictures06/lab6%2011.png)
(Рисунок 10)
6. Проделал приведённые ниже упражнения, записывая в отчёт по лабораторнойработе используемые при этом команды:
6. 1. Не просмотрел содержимое файла /etc/password, так как у меня его нет.
![](https://raw.githubusercontent.com/gedeongeorges/lab-06/main/pictures06/lab6%2012.png)
(Рисунок 11)
6. 2. Скопировал файл ~/feathers в файл ~/file.old командой cp.
6. 3. Переместил файл ~/file.old в каталог ~/play командой mv.
![](https://raw.githubusercontent.com/gedeongeorges/lab-06/main/pictures06/lab6%2013.png)
(Рисунок 12)
6. 4. Скопировал каталог ~/play в каталог ~/fun командой cp -r.
6. 5. Переместил каталог ~/fun в каталог ~/play командой mv и назвала его games командой mv.
![](https://raw.githubusercontent.com/gedeongeorges/lab-06/main/pictures06/lab6%2014.png)
(Рисунок 13)
6. 6. Лишил владельца файла ~/feathers права на чтение командой chmod u-r.
6. 7. Если попытаться просмотреть файл ~/feathers командой cat, то выведется:
6. 8. Если попытаться скопировать файл ~/feathers командой cp, то выведется:
6. 9. Дал владельцу файла ~/feathers право на чтение командой chmod u+r.
6. 10. Лишeл владельца каталога ~/play права на выполнение командой chmod u-x.
6. 11. Попыталсь перейти в каталог ~/play командой cd. 
6. 12. Дал владельцу каталога ~/play право на выполнение командой chmod u+x.
![](https://raw.githubusercontent.com/gedeongeorges/lab-06/main/pictures06/lab6%2015.png)
(Рисунок 14)
7. Прочитал man по командам mount, fsck, mkfs, kill.
![](https://raw.githubusercontent.com/gedeongeorges/lab-06/main/pictures06/lab6%2020.png)
(Рисунок 15)
# Вывод:
### ознакомилась с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобрела практические навыки по применению команд для работы с файлами и каталогами, по управлению процессами (и работами), по проверке использования диска и обслуживанию файловой системы.
# Контрольные вопросы.
1.Характеристика файловой системы, которая использовалась в данной лабораторной работе:
Файлы: abc1, april, may, june, july, isdv4.h, equipment, equiplist, equiplist2, my_os, feathers, file.old. Каталоги: monthly, monthly.00, tmp, monthly.01, reports, usr, include, xorg, ski.plases, equipment, newdir, plans, australia, play, etc, fun, games.
2. Пример общей структуры файловой системы: /home/pdarzhankina/monthly/april, где /home/pdarzhankina – домашний каталог, /monthly – каталог, находящийся в домашнем и содержащий файл, /аpril – файл, находящийся в каталоге.
3. Чтобы содержимое некоторой файловой системы было доступно операционной системе должно быть выполнено монтирование тома.
4. Основные причины нарушения целостности файловой системы:
- Один блок адресуется несколькими mode (принадлежит нескольким файлам).
- Блок помечен как свободный, но в то же время занят (на него ссылается onode).
- Блок помечен как занятый, но в то же время свободен (ни один inode на него не ссылается).
- Неправильное число ссылок в inode (недостаток или избыток ссылающихся записей в каталогах).
- Несовпадение между размером файла и суммарным размером адресуемых inode блоков.
- Недопустимые адресуемые блоки (например, расположенные за пределами файловой системы).
- "Потерянные" файлы (правильные inode, на которые не ссылаются записи каталогов).
- Недопустимые или неразмещенные номера inode в записях каталогов.
Чтобы устранить повреждения файловой системы используется команда fsck.
5. Команда mkfs создаёт новую файловую систему.
6. Характеристика команд, которые позволяют просмотреть текстовые файлы:
- для просмотра небольших файлов удобно пользоваться командой cat.
- для просмотра больших файлов используйте команду less — она позволяет осуществлять постраничный просмотр файлов.
- для просмотра начала файла можно воспользоваться командой head, по умолчанию она выводит первые 10 строк файла.
- команда tail выводит несколько (по умолчанию 10) последних строк файла.
7. Основные возможности команды cp:
- копирование файла в текущем каталоге.
- копирование нескольких файлов в каталог.
- копирование файлов в произвольном каталоге.
Опция i в команде cp выведет на экран запрос подтверждения о перезаписи файла, если на место целевого файла вы поставите имя уже существующего файла. Команда cp с опцией r (recursive) позволяет копировать каталоги вместе с входящими в них файлами и каталогами.
8. Характеристика команд перемещения и переименования файлов и каталогов:
- переименование файлов в текущем каталоге. mv <старое_название_файла> <новое_название_файла> 
- перемещение файлов в другой каталог. mv <название_файла> <название_каталога> 
Если необходим запрос подтверждения о перезаписи файла, то нужно использовать опцию i.
- переименование каталогов в текущем каталоге. mv <старое_название_каталога> <новое_название_каталога> 
- перемещение каталога в другой каталог. mv <старый_каталога> <новый_каталог> 
- переименование каталога, не являющегося текущим. mv <каталог/старое_название_каталога> < каталог/новое_название_каталога> 
9. Каждый файл или каталог имеет права доступа: чтение (разрешены просмотр и копирование файла, разрешён просмотр списка входящих в каталог файлов), запись (разрешены изменение и переименование файла, разрешены создание и удаление файлов каталога), выполнение (разрешено выполнение файла, разрешён доступ в каталог и есть возможность сделать его текущим). Они могу быть изменены командой chmod.

# hw9
Все задания я выполнял в NotePad++
1) Сначала использовал регулярное выражение \n\s. 
![Скрин](https://raw.githubusercontent.com/vladimirloginov999/hw9/master/Скриншот%2026-05-2018%20143336.png)
2) Потом удалил строки, оставив пустой строку замены.
![Скрин]
3) Некоторые строки остались, по видимому в них есть пробел. Поэтому для их поиска использовал регулярное выражение ^[ ]*$* (вторая звездочка для отмены выделения курсивом в markdown). Оставив строку замены пустой, удалил все пробелы в пустых строках.
![Скрин]
4) Удалил оставшиеся пустые строки как в пункте 1).

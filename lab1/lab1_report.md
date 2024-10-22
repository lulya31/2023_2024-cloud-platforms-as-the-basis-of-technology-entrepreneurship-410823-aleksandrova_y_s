University: [ITMO University](https://itmo.ru/ru/)
Faculty: [FICT](https://fict.itmo.ru)
Course: [Cloud platforms as the basis of technology entrepreneurship](https://) ADD link
Year: 2023/2024
Group: U4225
Author: Filianin Ivan Victorovich
Lab: Lab1
Date of create: 20.09.2023
Date of finished: 31.09.2023

Весь отчет представлен на скриншотах в папке **img_lab1**.
1) Создан service account с ролью Storage Admin (yaleksandrova-sa-lab1).

2) Создан минимальный compute engine с Machine type e2-micro в режиме spot (yaleksandrova-vm-lab1).

3) С помощью утилиты gsutils найден бакет lab1-bucket-itmo и скопированы 3 файла в локальную папку на VM. 
   
4) Изменены права доступа для вашего service account с Storage Admin на Compute Viewer
5) Скопировать больше не получилось из-за недостатка прав Compute Viewer

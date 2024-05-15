# Лабораторная работа. Полное описание работы.

## Задача №1: Загрузка на github через git bash.

### Данная задача включает в себя создание репозитория на GitHub и загрузку проекта в этот репозиторий с использованием Git Bash.
### 1. Создание нового репозитория Git
git init
### 2. Переход в указанный каталог
cd Project_Management
![](https://github.com/Archangel15520/Lab-Project-Management/blob/main/screenshot/1.JPG)

### Заранее создаю и подготавливаю файлы ".md" для git bash.

![](https://github.com/Archangel15520/Lab-Project-Management/blob/main/screenshot/5.JPG)

### 2. Установка глобальной конфигурации Git для email пользователя
git config --global user.email grisch.vasiljew2012@yandex.ru

### 3. Установка глобальной конфигурации Git для имени пользователя
git config --global user.name Archangel15520

### 4. Добавление файлов в индекс для отслеживания изменений
git add DOC.md Main.py Redme.md

### 5. Просмотр содержимого текущего каталога
ls

![](https://github.com/Archangel15520/Lab-Project-Management/blob/main/screenshot/2.JPG)

### 6. # Фиксация состояния индекса в репозитории с сообщением "Initial commit"
git commit -m "Initial commit"

### 7. Создание новой ветки с именем "dev"
git branch dev

### 8. Переключение на ветку "dev"
git checkout dev

![](https://github.com/Archangel15520/Lab-Project-Management/blob/main/screenshot/3.JPG)

### 9. Создание нового тега с именем "1.0.0"
git tag 1.0.0

### 10. Фиксация изменений в репозитории с сообщением "first commit"
git commit -m "first commit"

### 11. Переименование основной ветки из "master" в "main"
git branch -M main

### 12. Добавление удаленного репозитория с именем "origin" по указанному URL
git remote add origin http://github.com/Archangel15520/Lab-Project-Management.git

### 13. Отправка изменений в основную ветку репозитория на удаленный сервер "origin" и установка отслеживания для дальнейших операций push
git push -u origin main

![](https://github.com/Archangel15520/Lab-Project-Management/blob/main/screenshot/4.JPG)


## Задача №2: Написать функцию генерации случайного email адреса

Требуется написать функцию `generate_random_email()`, которая генерирует случайный email адрес в формате <name>@<domain>.<local>. 
Функция использует модули random и string для генерации случайных символов.

### Задача №3: Вывод виде таблицы ФИО и даты рождения всех студентов, отсортированных по дате рождения

Необходимо реализовать функцию `print_students_sorted_by_dob()`, которая выводит список студентов в виде таблицы, отсортированной по дате рождения.

![](https://github.com/Archangel15520/Lab-Project-Management/blob/main/screenshot/1.JPG)

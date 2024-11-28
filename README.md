# Лабораторная работа №6

## 1. Цель работы

Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

## 2. Основная часть работы

### Форк репозитория

Создается копия репозитория в личное хранилище, копируются обе ветки: master и branch1

![Форк репозитория](screenshots/форк.jpg)

### Настройка клиента git

Задается имя пользователя согласно требованиям (Группа Фамилия И.О.). Почта уже была задана ранее. 

![Настройки GitBash](screenshots/группа_фио_эл_почта.jpg)

### Клонирование репозитория на компьютер

На компьютере создается папка, в которую будет клонирован репозиторий. 

![Клонирование репозитория](screenshots/клонирование.jpg)

### Добавление файла через интерфейс GitHub

В личном репозитории необходимо нажать на кнопку ```add file``` >> ```create new file```. В основную ветку был загружен новый текстовый файл ```new_file.txt```.

![Добавление файла](screenshots/добавление_файла.jpg)

### Подтягивание изменений в локальный репозиторий

Подтягиваем добавление нового файла в репозиторий на компьютере.

![Подтягивание изменений](screenshots/подтягивание_изменений.jpg)

### История операций для каждой ветки

Для начала просматривается история для основной ветки, затем происхолдит переключение на branch1 и просмотр ее истории.

![История операций](screenshots/история_операций.jpg)

### Просмотр последних изменений

Просмотр последнего коммита выполняется для веток в обратном порядке аналогично предыдущему шагу - сначала для branch1, затем для master.

![Последние изменения](screenshots/последние_изменения.jpg)

### Слиние в одну ветку

В результате слияния веток возник конфликт. В индекс не были добавлены изменения файла mergefile.txt. Для разрешения конфликта нужно добавить изменения в основную ветку, после чего повторно применить команду слияния.

![Слияние в одну ветку](screenshots/слияние1.jpg)

### Результат слияния

Добавляем уже измененный файл mergefile.txt, делаем коммит и отправляем на локальный репозиторий.

![Слияние в одну ветку](screenshots/слияние2.jpg)

### Удаление побочной ветки

После успешного слияния двух веток, побочная ветка branch1 удаляется.

![Удаление ветки branch1](screenshots/удаление.jpg)

### Изменения в файле

Файл ```new_file.txt``` был изменен несколько раз, изменения были зафиксированы коммитами.

![Изменения текстового файла](screenshots/изменения_файла.jpg)

### Откат коммита

Для отката необходимо указать хеш того коммита, на который произойдет откат. Все изменения, сделанные после этого коммита, будут отменены.

![Откат коммита](screenshots/откат.jpg)

### Создание ветки для отчета

Для отчета и демонстрации выполненных операций создается новая ветка ```report_branch```.

![Новая ветка](screenshots/создание_ветки.jpg)
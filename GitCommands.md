# Комманды Git и не только

## Коммады Git

### Инициализация репозитория

git init  

### Добавление отдельных файлов в Git

git add 

### Добавление всех файлов в Git

git add .

### Проверка статуса репозитория

git status

### Внесение изменений с комментарием

git commit -m "комментарий”

### Внесение изменений с комментарием + add

git commit **-am** "комментарий”

### Просмотр истории коммитов с изменениями

git log 

### Посмотреть дерево коммитов

git log —graph

### Просмотр изменений до коммита

git diff

### Просмотр изменений между версиями

git diff ver1 ver2

### Журнал всех выполненных действий

git reflog

### Выбрать точку восстановления

git checkout №ver

### Вернуться в основную версию

git checkout master

### Посмотреть ветки

git branch

### Создать ветку

git branch название

### Слить ветку с той в которой вы сейчас находитесь

git merge название

## Работа с текстом

Полужирный текст (**) или (__)

**текст**

Курсив (*) или (_)

*курсив*

Если надо совместить курсив и полужирный одновременно (**) и (_)

**_Полужирный Курсив_** 

## Списки

Ненумерованные

* Первый
* Второй

и т.п.

Нумерованные

1. Первый
2. Второй 

и т.п.

## Остальное

Очистить терминал

clear

Добавить картинку "!"[]"()" "Подсказака"

![Котик](kotik.jpeg) "Котик"

Добавить ссылку "[]"()"

[github.com](https://github.com/)

Цитаты >

> Пример цитаты

> В начале каждой сткоки надо ставить угловую скобку

>>Пример вложенной цитаты

>>> Пример вложенной цитаты

Разделяющая линия *** и ---

***

### Создать ветку и сразу на нее переключиться

git checkout -b vetka2

### Прервать слияние и вернуть все назад при ошибке

git merge —abort

### Клонирует репозиторий из интернета

git clone

### Скачать все атуальное из удаленного репозитория

git pull

### Отправить в улаленный репозиторий новую информацию

git push
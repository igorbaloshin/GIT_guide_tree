# GIT Инструкция

## Что такое GIT

Git - это консольная утилита, для отслеживания и ведения истории изменения файлов, в вашем проекте.

С помощью Git-a вы можете откатить свой проект до более старой версии, сравнивать, анализировать или сливать свои изменения в репозиторий.

>*__Репозиторием называют хранилище вашего кода и историю его изменений. Git работает локально и все ваши репозитории хранятся в определенных папках на жестком диске.__*

_Примеры использования контроля версий в жизни:_

![пример 1](пример_1.jpg)

## Начало работы с GIT

1. Настройка

_прописываеи имя и почту_

* git config --global user.name "ваше имя"

* git config --global user.email "ваш email"


2. Создание репозитория

> *__Репозиторий Git — это виртуальное хранилище проекта. В нем можно хранить версии кода для доступа по мере необходимости.__*

_инициализируем репозиторий в папке проекта_

* git init

_добавляем файл для контроля_

* git add "имя файла"

* git add .    - *команда для всех файлов в папке*

_записывае файл с комментарием_

* git commit -m "комментарий"

## Процесс работы с GIT

* git log - *просмотр журнала изменений*

* git log --graph - *просмотр дерева с изменениями*

* git diff - *прсмотр текущего состояния файла с сохраненным*

* git checkout"номер комита" - *возврат к нужному комиту*

* git status - *показывает текущее состояние*


## Работа с черновиками
>*__Ветки позволяют легко управлять черновиками и чистовиками в Git.__* 
 
![пример 2](пример_2.jpg)

* git branch - *показывает ветку где мы находимся*

* git branch"имя новой ветки" - *создаем новую ветку*

* git checkout"имя ветки" - *перемещение на эту ветку*

* git merge"имя присоединяемой ветки" - *сливаем текущую ветку с присоединяемой*

* git branch -d"имя удаляемой ветки" - *удаляем ветку*

## Работа с изображениями


В Git не принято добавлять файлы изображений, их хранят на сторонних носителях. Чтобы исключить ненужные файлы из загрузки, есть команда git ignore

![пример 3](пример_3.jpg)

1. Добавляем файл ".gitignore"

2. Прописываем в этот файл имя игнорируемого файла

3. Сохраняем файл с изменениями

## Работа с ссылками

Для добавления ссылки:
 
* [ссылка](https://gist.github.com/Jekins/2bf2d0638163f1294637)



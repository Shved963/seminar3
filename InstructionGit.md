# **Инструкция по работе с Git**

## Предварительная настройка Git

Чтобы "представиться" программе git нужно ввести команды:

    git config --global user.name "Ваше имя"
    git config --global user.email "Ваш е-маил"

## Создание репозитория

Чтобы инициализировать новый репозиторий нужно ввести команду:

    git init

## Добавление в индекс

Чтобы добавить изменение в индекс (для фиксации в следующем коммите) нужно ввести команду:

    git add <имя файла>

## Проверка файла

Чтобы проверить изменен ли файл нужно ввести команду:

    git status

## Фиксация изменений

Чтобы зафиксировать изменения добавленные в индекс и открыть редактор нужно ввести команду:

    git commit

 
 Описать команды:

    git status

    git commit -m
    git commit -a
    git commit -am (-a -m)

    git log
    git log --oneline
    git log --all
    git log --oneline --all

    git diff
    git diff 'hash1' 'hash2'

    git checkout 'hash'
    git checkout master

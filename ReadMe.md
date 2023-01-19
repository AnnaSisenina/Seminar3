# Инструкция по работе с Git и работе с ветками

## Что такое Git?
***Git*** - это одна из реализаций распределенной системы контроля версий, поддерживающие как локальные, так и удаленные репозитории. Самая популярна реализация Git - это [GitHub](https://github.com).

## Подготовка репозитория
Для создания репозитория используется команда Git init. Для этого необходимо открыть папку с будущим репозиторием и там написать *git init*.

### Добавление файла к коммиту
Для добавления файла к коммиту используется команда *git add*. Для этого в терминале с папкой-репозиторием необходимо написать *git add<название файла>*

## Создание коммитов

### Выполнение коммита
Для того, чтобы выполнить коммит, используется команда *git commit*. Для этого в терминале с папкой-репозиторием написать *git commit - m "<сообщение к коммиту>"*. Сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***!!!

## Журнал изменений
Для просмотра истории коммитов используется команда *git log*. Для этого в терминале с папкой-репозиторием пишем *git log*. В показанном журнале обязательно будут:
* Хеш(номер) коммита;
* Дата и время коммита;
* Автор коммита;
* Текст ссобщения к коммиту;

## Перемещение между коммитами
Для перемещения между коммитами используется команда *git checkout*. Для этого в терминале с папкой репозиторием нужно написать *git checkout <хеш коммита>*. Хеш коммита можно взять из истории коммитов, про которую было рассказано в предыдущем пункте.


## Ветки в Git
###Создание веток
Для создания веток используется команда *git branch*. Для этого в папке с репозиторием необходимо написать *git branch <название ветки>*. Название ветки должно быть ***УНИКАЛЬНО***.

###Просмотр списка веток
Для просмотра списка веток используется команда *git branch*. Для этого в терминале с папкой-репозиторием необходимо написать *git branch*  и Вы увидите список всех существующих веток. Зеленым цветом и символом **звездочка** будет обозначена текущая ветка.
 
## Слияние 

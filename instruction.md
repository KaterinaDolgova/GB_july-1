Чтобы добавить новую ветку, необходимо ввести команду:

> **git branch branch_name** - появится ветка, с названием *name*

Чтобы увидеть все ветки и понять, на какой из них Вы работаете в данный момент, нужно внести команду:
> **git branch** - в терминале появиться список всех веток. Звездочкой (*) будет помечена ветка, в которой Вы распологаетесь.

Чтобы удалить ненужную ветку (например, когда были внесены все исправления и работа с ней закончена), необходимо ввести команду:
> **git branch  -d branch_merge** или **git branch  -D branch_merge**
> при этом, используя заглавную букву D, git не будет проверять, была ли добавлена информация с этой ветки на любую другую ветку.

Чтобы слить любую ветку с текущей, вызываем:

>**git merge branch name** *(где name- имя ветки для слияния с текущей)*:
> например, если Вы находитесь на ветке *master*, команда (*git merge branch_deleat*), добавит информацию с ветки *branch_deleat* к ветке *master* 

Для визуализации всех веток ввиде дерева, необходимо ввести команду:
> **git log --graph**
увидеть лог коммитов с визуализацией между ними

git log - - graph

Локальная копиЯ удаленного репозитория

git clone <адрес юрл>

git pull – получение изменений и слияние с локальной версией

git push – отправляет локальную версию репозитория на внешний

# My git Instruction
*git init* - команда, инициализирующая репозиторий в текущей папке 

## Создание и просмотр коммитов

*git add* - команда добавления изменений

*git config* --global user.name "Name" - указать свое имя 

*git config --global user.email "email"* - указать email

*git status* - проверка статуса репозитория

*git commit -m "Your short summary about the commit"* - создание коммита с коментарием

*git diff* - просмотреть список изменений

*git log* - просмотр истории коммитов с изменениями

*git show 1af17e* - просмотр заданного коммита

*git rm dirname/somefile.js* - удаление файла из текущего рабочего дерева

*git mv dir1/somefile.js dir2* - Переименовать файл или папку можно параметром mv. Для него указывается источник source и назначение destination

*git checkout somefile.js* - восстановить файлы не подготовленные к коммиту

*git revert* - отменить последний коммит

*git reset* - вернуть проект в исходное состояние

*git revert 1af17e* - откат заданного коммита

## Создание новой ветки и переход в нее

*git branch new_branch_name* - создание новой ветки и переход в нее

*git checkout -b new_branch_name* - переход в новую ветку

*git branch* - просмотр списка веток


## Термины второго семинара

*git branch* - отображает список веток

*git branch name* - создание ветки

*git checkout branch name* - перейти в ветку

*git merge branch name* - свести ветку. Делаем из ветки master, указываем имя ветки, которую сводим

*git branch lists* - список веток

*git branch -d branch name* - удалить ветку

_git add*_ - добавить все файлы

*git log --graph* - визуализировать все ветки



# Основные команды GIT
## базовые команды

*  **git init** - 
 инициализация локального репозитория

*  **git status** - 
 Получить информацию от GIT о его текущем состоянии

 *  **git add** - 
 Добавить файл или файлы к следующему коммиту

  *  **git commit -m "message"** - 
 Создание коммита

  *  **git commit -a -m "message"** - 
 Создание коммита с командой **add**

   *  **git log** - 
 Вывод на экран всех коммитов с их хэш кодами

   *  **git checkout** - 
 переход от одного коммита к другому

   *  **git checkout master** - Перейти к актуальному состоянию и продолжить работу

*  **git diff** - Увидеть разницу между текущим файлом и закоммиченным файлом

*  **git show** - Просмотр заданного коммита (указать хэш или его часть)

*  **git rm dirname/somefile.md** - Удаление отслеживаемых файлов из текущего рабочего дерева

*  **git revert HEAD** - Откат последнего коммита

*  **git revert 1af17e** - Откат заданного коммита

## Работа с ветками

*  **git branch new_branch_name** 

*  **git branch** 

*  **git branch -d existing_branch_name** 

*  **git branch -d existing_branch_name** 

* **git merge existing_branch_name**
-Слияние двух веток
* **git log --graph --oneline --decorate**

* **git merge --abort**
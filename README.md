## Test

###  Должен быть установлен Git локально

###  Переходим в дирректорию проекта
cd project

###  Создаем файл Readme c текстом Test
echo "# Test" >> README.md 

###  Инициируем git
git init

###  Добавляем под контроль  файл README.md 
git add README.md

### 
git commit -m "first commit"

###  Устанавливаем удаленный репозиторий 

git remote add origin git@github.com:IgorNaprienko/Test.git

###  Проверим статус
git status
 --
    On branch master
    Changes not staged for commit:
    (use "git add <file>..." to update what will be committed)
    (use "git checkout -- <file>..." to discard changes in working directory)
        modified:   README.md

    no changes added to commit (use "git add" and/or "git commit -a")
###  Требует фиксации изменений , выполняем  -- all (все принимаем)
$ git add --all


###  Пушим 
git push -u origin master




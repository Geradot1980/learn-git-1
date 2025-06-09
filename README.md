# learn-git-1 - Изучение Git

## 1. Работа с GitHub 

1. Клонировать репозиторий с GitHub <br>
```git clone https://github.com/Geradot1980/learn-git-1.git ```

2. Выложить изменения на GitHub <br>
```git push```

3. Скачать  GitHub последние изменения <br>
```git pull```

4. Узнать про изменения в удаленном (GitHub) репозитории. <br>
Дает информацию для локального репозитория (git status) <br>
```git fetch```

5. ??? <br>
```git fast-forwarded```


## 2. Локальные команды

1. Текущий статус <br>
```git status```

2. Создать коммит. Запомнить все что modified <br>
```git commit -m 'Name commit'``` - Запомнить все что <b>modified</b> <br>
```git commit -a -m 'Name commit'``` - Запомнить все что новое кроме <b>Untracked</b><br>
```git commit -amend``` - Запустит редактор коммита

3. Добавить файлы в отслеживаемые <br><br>
```$ git add .``` - Добавить все файлы <br> 
```git add file.name``` - Добавить конкретный файл <br>

4. Выводит все <b>commits</b> <br>
```git log```<br>
```git log --author 'name'``` - Выводит все <b>commits</b> конкретного автора <br>

5. Показывать нужный <b>commit</b> <br>
```git show 'хеш коммитта'```<br><br>
	5.1. Показыват последний <b>commit</b> ветки <br>
```git show ``` <br><br>

6. Узнать автора кода и задать вопрос <br>
```git blame 'имя файла'```<br>
```git blame 'имя файла' | grep 'слово'``` - выдаст имя автора который в нужном файле создал данное 'слово' или все строки пользователя по имени  <br>
<br>

7. Показывать все изменения последнем <b>commit</b>  <br>
```git diff```<br><br>

8. Разобрать <b>commit</b> и убрать из истории  <br>
```git reset HEAD~1```<br>
```git reset HEAD~1 --hard``` - разобрать и удалить изменения<br><br>

9. Отменить слияние  <br>
```git merge --abort```<br>

10. Возвращение состояния до начала изменения  <br>
```git checkout .``` - Все изменения в папке<br>
```git checkout some.file``` - Конкретный файл some.file<br>
```git stash``` - Откатывает до коммита, но помнит изменения<br>
```git stash pop``` - Возвращает изменения из stash<br>
```git stash clear``` - Удалить все изменения из stash<br>
11. <i>Сохранение изменений в файл:</i><br>
 a) ```git diff >> 'saveTo.file'``` - Сохраняем вывод див в файл saveTo.file<br>
 b) ```git apply 'saveTo.file'``` - Применяем сохраненное в файле saveTo.file <br>

## 3. Ветки
1. branch <br>
```git branch my_first_branch``` - Создание ветки <b>my_first_branch</b><br>
```git branch``` - Вывести список веток<br>
```git checkout my_first_branch``` - Перейти на ветку <b>my_first_branch</b><br>

2.  ????<br>
```????'``` - ???? <b>modified</b> <br>



<br><br><br><br><br><br><br>


2. Создать коммит. Запомнить все что modified <br>
```git commit -m 'Name commit'``` - Запомнить все что <b>modified</b> <br>
```git commit -a -m 'Name commit'``` - Запомнить все что новое кроме <b>Untracked</b><br>
```git commit -amend``` - Запустит редактор коммита

3. Добавить файлы в отслеживаемые <br><br>
```$ git add .``` - Добавить все файлы <br> 
```git add file.name``` - Добавить конкретный файл <br>

4. Выводит все <b>commits</b> <br>
```git log```<br>
```git log --author 'name'``` - Выводит все <b>commits</b> конкретного автора <br>

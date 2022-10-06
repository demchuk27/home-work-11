# GIT - home work, Lessons №11

Подключение и настройка:
- git init   - подключение.
- git config --global user.name 'Volodymyr Demchuk'   - Настройка аккаунта.
- git config --global user.email 'demchuk2708@gmail.com'   - Добавил почту.

Дальше все по заданию:
- git status   - проверяем что у нас стоит на загрузку.
- git add .   - добавьте все файлы в локальное хранилище;
- git commit -m 'add the project to the local repository'   - коммитем.
- git branch blog   - создал новую ветку
- git checkout blog   - перехожу на новую ветку blog
- git status   - проверяем, на всякий случай, на какой ветки находимся.
- В новой ветке создаем папку blog с файлами: index.js, index.html;
- git add .   - добавьте все файлы в локальное хранилище;
- git commit -m 'add the project to the branch blog'   - коммитем.
- git status   - проверяем все ли добавлено.
- git checkout master - выходим на главную ветку.


- Создал новый репозиторий на сайте https://github.com/
- git status   - проверяем все ли добавлено.
- git branch -M master   - указываем название ветки master.
- git remote add origin https://github.com/demchuk27/home-work-11.git   - подключаемся.
- git remote   - проверяем подключение к репозиторию.
- git push -u origin master   - файлы из локального репозитория добавляем в удаленный репозиторий.
- git status   - проверяем все ли добавлено.

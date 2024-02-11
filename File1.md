# Команды при работе с Git
1. Команда смены директории
```sh
cd c:\folder_name
```
2. Команда отображения текущей директории (mac os)
```sh
pwd
```
3. Инициализация репозитория
```sh
git init
```
4. Проверка статуса репозитория
```sh
git status
```
5. Добавление отдельных файлов в область подготовленных файлов
```sh
git add <filename>
```
6. Cоздание коммита в репозитории
```sh
git commit -m "информация о коммите"
```
7. Просмотр истории коммитов
```sh
git log 
```
8. Краткая история коммитов в одну строку 
```sh
git log --oneline
```
9. Просмотр изменений до коммита
```sh
git diff
```
10. Переключение между версиями коммитов

```sh
git checkout <commit_version>
```
11. Отображение всех веток
```sh
git branch
```
12. Перемещение по веткам
```sh
git checkout <branch_name>
```
13. Создание новой ветки
```sh
git branch <branch_name>
```
14. Удаление ветки
```sh
git branch -d <branch_name>
```
15. Слияние выбранной ветки с текущей
```sh
git merge <branch_name>
```
16. Показать список файлов отслеживаемых git
```sh
git ls-tree -r main --name-only
```
17. Удалить файл из списка файлов отслеживаемых git (не удаляя сам файл)
```sh
git rm -r --cached Task3/bin/ <file name>
```

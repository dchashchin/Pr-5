# Практическая работа №5
## Основы работы с системой контроля версий Git
 
Выполнил: Чащин Даниил  
Логин GitHub: dchashchin  
 
 
## 1. Создан аккаунт на GitHub
- Логин: **dchashchin** (первая буква имени + фамилия)
 
## 2. Создан репозиторий на GitHub
- Репозиторий создан **без README.md**
 
## 3. Инициализирован локальный репозиторий
```bash
$ git init
```
 
## 4. Создан файл .gitignore
```bash
$ cat .gitignore
*/bin/
*/obj/
 
.vs/
packages/
```
 
## 5. Настроен пользователь Git
```bash
$ git config user.name "dchashchin"
$ git config user.email "beamka31@gmail.com"
$ git config --global http.sslVerify false
```
 
## 6. Добавлены файлы и создан коммит
```bash
$ git add .
$ git commit -m "Create .gitignore"
[main (root-commit) 17df863] Create .gitignore
 1 file changed
 create mode 918212 .gitignore
 
```
 
## 7. Привязан удалённый репозиторий
```bash
$ git remote add origin https://github.com/apodlepich/first.git
$ git remote -v
origin  https://github.com/apodlepich/first.git (fetch)
origin  https://github.com/apodlepich/first.git (push)
```
 
## 8. Проверка состояния
```bash
$ git status
On branch main
nothing to commit, working tree clean
 
```
 
## 9. Проверка веток
```bash
$ git branch
* main
```
 
## 10. Проверка изменений
```bash
$ git diff HEAD
(изменений нет)
```

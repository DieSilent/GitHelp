# GitHelp
## Шпаргалка по Git для курса
__  
--  
**Рабочий процесс:**


1. Инициализируем git
```bash
git init
```
2. Дублируем существующий код с Github и добавляем его в источники
```bash
git clone [repo_address] [folder_name]
```
3. Переключаемся на дочернюю ветку, чтобы не заливать непроверенный код в main
```bash
git checkout [branch_name]
```
Или  
```bash
git branch [branch_name]
git checkout [branch_name]
```
4. Добавляем баги, фиксим фичи. После чего необходимо зафиксировать наши изменения в staged area и после этого окончательно сохранить состояние - закомитить. Не забудем поделиться с другими своими нововведениями!
```bash
git add [./filename/--all]
git commit -m "type_your_short_message"
git push remoteSource/branchname
```
5. Сливаем с веткой main наш крутой код
```bash
git checkout master
git metge nemasterBranch
```

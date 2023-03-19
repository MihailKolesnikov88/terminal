:computer: # terminal
---

[Сценарий выполнения ДЗ GitHub](https://docs.google.com/spreadsheets/d/1qOzzFXphwm5GrR_j3C9v5wx-FyFepX2IpFraJx5_ZHI/edit?usp=share_link)

----
### Most used commands for github
|*Command*|*Description*|
|:---|:---|
|git status|		- проверка состояния файлов|
|git add . 		|- добавление всех файлов на комит|
|git add 'file'		|- добавление конкретного файла на комит|
|git commit -m 'coment'|  - создание комита с комментарием|
|git commit -am 'coment'| - сразу добавляем и комитем все файлы|
|git push |		- отправка комита на внешний репозиторий|
|git config --global user.name 'name'| - прописываем имя пользователя с удаленного репозитория|
|git config --global user.email 'mail'| - прописываем почту |
|ssh-keygen -t rsa -c 'user name'| - создаем ключ SSH|
|.gitignore 	|	- создание файла для добавления во внутрь списка файлов для игнорирования|
|git branch	|	- проверяем на какой ветке мы находимся|
|git branch name_branch |	- создаем новую ветку|
|git checkout |		- переход на заданную ветку|
|git rebase |		- замена/слияние второстепенной (текущей) ветки с главной|
|git merge name_branch |	- перенос файлов и данных из текущей ветки в указанную|
|git push -u origin name_branch| 	- отправляем из текущей ветки (главной) указанную ветку на внешний репозиторий|
|git pull |		- обновляем локальный репозиторий (в котором находимся) данными из удаленного репозитория (заменяет команды git fetch, git merge) |
|git merge|  - слияние одной или нескольких веток в текущую|
|git fetch|  - загрузка содержимого из удаленного репозитория|

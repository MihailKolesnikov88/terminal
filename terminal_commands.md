|*Command*|*Description*|
|:---|:---|
|pwd 	|			- показывает где мы находимся|
|cd| 				- команда для изменения директории|
|cd ..| 				- команда перехода на одну директорию вверх|
|cd ../..	|		- команда перехода на две директории вверх|
|cd ~ |				- переход в корневую папку|
|cd путь	|			- переход в указанную директорию|
|../путь  |     - переход в папки на дерикторию выше|
|../../путь. |  - переход в папки на две директории выше|
|open . |				- открытие папки в которой находимся|
|open имя_файла	|		- запуск файла|
|ls		|		- список папок и файлов в нашей точке|
|ls -l	|			- подробный список файлов и папок в нашей директории|
|ls -a			|	- список папок и файлов включая скрытые папки и файлы|
|ls -t				|- сортировка списка папок и файлов по дате создания|
|ls --help 	|		- выводит список команд|
|touch имя_файла	|		- создание файла|
|cat имя_файла 		|	- выводит содержимое файла|
|cat > имя_файла 	|	- создание и внесение данных в файл|
|cat >> имя_файла	|	- редактирование файла|
|mkdir			|	- создание директории|
|rmdir 			|	- удаление пустой директории|
|rm имя_файла		|	- удаление файла|
|rm -r имя_директ	|	- удаление директории|
|history			|	- выводит историю использованных команд|
|history 100	|		- выводит последние 100 команд|
|history > имя_файла |		- создает документ с историей всех команд|
|mv имя_файла путь	|	- перемещение файл в указанный каталог|
|cp имя_файла путь	|	- копирует файл в указанный каталог|
|cp имя_файла1 имя_файла2	|- создаем копию файла, копируем файл1 - получаем файл2|
|find имя_директ -name "t*"	|- поиск файла начинающегося на букву t|
|find . -name "t*"		|- поиск файла на букву t по всем каталогам ниже|
|find . -type f -name "t*"|	- поиск файла так же|
|find . -type d -name "t*"	|- поиск директории так же|
|grep текст папка/ файл	|	- поиск текста в конкретном файле|
|grep -r текст			|- поиск содержимого во всех файлах |
|grep -r -i текст 	|	- поиск содержимого без учета регистра|
|grep -r -i -w текст	|	- поиск конкретного слова без похожих |
|tail -n4 имя_файла| - выводит указанное количество строк с конца файла|
|tail -f имя_файла | - просмотр содержимого файла в реальном времени|
|head -n4 имя_файла| - выводит указанное количество строк с начала файла|
|less имя_файла | - выводит файл для просмотра с возможностью поиска и навигации внутри файла|
|curl |- команда для работы с url, для передачи и получения данных с сервера|
|curl -0  | - скачивание файла и сохранение под текущим именем|
|curl -i (или -head)| - получение заголовка без тела запроса|

tbaMUD is the continued development of the codebase formerly known as CircleMUD.

http://tbamud.com/

This fork Cyrillized by Prool. UTF-8 codetable

Кириллизировано (русифицировано) Прулем, кодировка UTF-8
Ну и дальше по мелочам модифицировать буду for fun

Как сделать кириллические команды
---------------------------------

Мои попытки показали, что кириллицу в UTF-8 нельзя пихать в таблицу команд,
будут глюки. Проще сделать собственный обработчик кириллических команд перед
стандартным обработчиком. См. как это сделано в моей русификации QuickMUD-lua:

https://bitbucket.org/prool/quickmud-lua-russian/

(изменения от 3 апреля 2017 года)

COMPILE AND RUN
---------------

./configure

cd src

make

cd ..

bin/circle

OR USE autorun\* scripts

http://prool.kharkov.org

http://mud.kharkov.org

proolix dog gmail.com

4 nov 2016

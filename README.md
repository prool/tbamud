Glory MUD

GloryMUD is based on tbaMUD.
http://glorymud.kharkov.org

tbaMUD is the continued development of the codebase formerly known as CircleMUD.
http://tbamud.com/

GloryMUD cyrillized by Prool. UTF-8 or koi8-r codetable.

Частично кириллизировано (русифицировано) Прулем, кодировка UTF-8 или koi8-r.

Как сделать кириллические команды
---------------------------------

Мои попытки показали, что кириллицу в UTF-8 нельзя пихать в таблицу команд,
будут глюки. Проще сделать собственный обработчик кириллических команд перед
стандартным обработчиком. См. как это сделано в моей русификации QuickMUD-lua:

https://bitbucket.org/prool/quickmud-lua-russian/ (изменения от 3 апреля 2017 года)

Compile and run (any systems)
-----------------------------

./configure

cd src

make

cd ..

bin/circle

OR USE autorun\* scripts

For Windows/cygwin add -liconv to LIBS in Makefile

Compile under Android 6.0 (dirty instruction)
---------------------------------------------

cp configure.android configure

./configure

cd src

add flag '-DANDROID' to Makefile to end of line 'CFLAGS=...'

make

cd ..

bin/circle

Contacts
--------

http://prool.kharkov.org

http://mud.kharkov.org

proolix dog gmail.com

23 Aug 2018

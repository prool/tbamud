tbaMUD is the continued development of the codebase formerly known as CircleMUD.
http://tbamud.com/

MUD cyrillized by Prool. UTF-8 or koi8-r codetable.

Частично кириллизировано (русифицировано) Прулем, кодировка UTF-8 или koi8-r.

Как сделать кириллические команды
---------------------------------

Мои попытки показали, что кириллицу в UTF-8 нельзя пихать в таблицу команд,
будут глюки. Проще сделать собственный обработчик кириллических команд перед
стандартным обработчиком.

Compile and run (any systems)
-----------------------------

./configure

cd src

make

cd ..

bin/circle

OR USE autorun\* scripts

Windows
-------

For Windows/cygwin add -liconv to LIBS in Makefile

Compile under macOS (dirty instruction)
---------------------------------------

cd src

cp Makefile.macos Makefile

make

cd ..

bin/circle

Compile under Android 6.0/termux (dirty instruction)
---------------------------------------------

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

Prool

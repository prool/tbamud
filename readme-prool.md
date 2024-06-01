Android
-------

For compiling in OS Anroid you need uncomment line in file comm.c
(search "ANDROID" subsctring in source) -- this is maybe not necessary in old versions of Android.

And for Android:

not run ./configure

cd src
cp Makefile.android Makefile
cd util
cp Makefile.android Makefile
cd ..
make

...

PROFIT

Linux
-----

./configure
cd src
make


Prool
1-JUN-2024
Duisburg, Deutschland
http://mud.kharkov.org
http://virtustan.net
http://virtustan.tk

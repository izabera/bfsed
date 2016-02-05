bfsed
=====

- Input after !
- 8 bit cells
- EOF == 0

Requires gnu sed for things like `\x00`

Must set LANG=C

~~~ sh
$ LANG=C ./bfsed < hello_world
Hello World!
~~~

~~~ sh
$ LANG=C ./bfsed <<< ',[>,]<[.<]!foobar'
raboof
~~~

bugs
----

- dog slow
- always prints an extra trailing newline

license
-------
shmicense

this::
    date = 2023-10-26


===================================================
\Desc claire grâce à un fichier path::''README.md''
===================================================

Il est important de décrire rapidement, mais de façon explicite, son projet. Ceci se fait via un fichier path::''README.md'' placé à la racine du dossier du projet. Deux modes de rédaction sont possibles.

    1) Pour un \docu court, on tapera tout directement dans le fichier path::''README.md''.

    1) Pour un \docu plus long, on utilisera un dossier parth::''readme'' placé à la racine du projet : ce dossier accueillera de petits fichiers \md faciles à maintenir. On délèguera, le moment venu, la \fabric d'un unique fichier path::''README.md'' au projet \multimd
    ((
        \src2prod appelle \multimd en coulisse.
    )).

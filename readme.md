Python Bytecode - Behind the Scenes
===================================

Tema: Seguridad/Ingeniería inversa sobre Python

Licencia: CC BY NC SA

* Python Bytecode: de py a pyc
    - Compilar código
    - Estructura de los archivos .pyc

* Presentación de los módulos marshall[1] y dis[2]
    - Obtener code objects
    - Ejecutar code objects (eval, exec)
    - Desensamblar code objects

* Experimentos:
    - byteplay[3]: manipulando code objects
    - uncompyle[4]: de pyc a py

* Caso de estudio: haciendo un poco de ingeniería inversa sobre un "crackme"[5] simple
    - Extraer el code object de un exe compilado con py2exe
    - Desensamblar y entender el programa
    - Generar el serial válido

* Algunas protecciones existentes

[1] http://docs.python.org/library/dis.html

[2] http://docs.python.org/library/marshal.html

[3] http://code.google.com/p/byteplay/

[4] https://github.com/matiasb/uncompyle

[5] http://en.wikipedia.org/wiki/Crackme

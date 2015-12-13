# xmlprocessor

![XMLProcessor](caratula.png)

## Descripción

Script que realiza las siguientes operaciones con el fichero XML pasado por parámetro:

1. Comprueba que existe 'fichero.xml'.
1. Crea una copia de seguridad de 'fichero.xml'.
1. Si existe 'fichero.dtd' valida 'fichero.xml' contra 'fichero.dtd'.
1. Si existe 'fichero.xsd' valida 'fichero.xml' contra 'fichero.xsd'.
1. Si existe 'fichero.rng' valida 'fichero.xml' contra 'fichero.rng'.
1. Si existe 'fichero.sch' valida 'fichero.xml' contra 'fichero.sch'.
1. Si existe 'fichero.xslt' procesa 'fichero.xml' y lo transforma en 'fichero.html'.
1. Formatea 'fichero.xml'.

## Requisitos

1. Añade xmlprocessor al **PATH**.
1. Tienes que tener instalado **xmllint** (que está en el paquete libxml2-utils) y **xsltproc**.

```
$ sudo apt-get install libxml2-utils
$ sudo apt-get install xsltproc
```

## Ejecución

```
$ xmlprocessor fichero.xml
```

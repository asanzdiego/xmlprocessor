# xmlprocessor

## Requisitos

- Tienes que tener instalado xmllint (que está en el paquete libxml2-utils) y xsltform

```
sudo apt-get install libxml2-utils
sudo apt-get install xsltproc
```
- Añade xmlprocessor al PATH

## Ejecución

```
xmlprocessor fichero.xml
```

1. Comprueba que existe 'fichero.xml'.
1. Crea una copia de seguridad de 'fichero.xml'.
1. Si existe 'fichero.dtd' valida 'fichero.xml' contra 'fichero.dtd'.
1. Si existe 'fichero.xsd' valida 'fichero.xml' contra 'fichero.'.
1. Si existe 'fichero.rng' valida 'fichero.xml' contra 'fichero.'.
1. Si existe 'fichero.sch' valida 'fichero.xml' contra 'fichero.'.
1. Si existe 'fichero.xslt' valida 'fichero.xml' contra 'fichero.'.
1. Formatea 'fichero.xml'.

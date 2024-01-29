# JSON Y YAML

_JSON_ y _YAML_ son dos **formatos de serialización de datos** que proporcionan un mecanismo de intercambio de datos legible por humanos. A continuación veremos las características más importantes de cada uno y las principales diferencias.

## [JSON](https://www.json.org/json-es.html)

Se trata de un subconjunto de la notación literal de objetos de _JavaScript_, aunque, debido a su amplia adopción como alternativa a _XML_, se considera un formato independiente del lenguaje.

### Características principales

- Resulta mucho más sencillo escribir un analizador sintáctico (parser) para _JSON_ que para _XML_.
- En _JavaScript_, un texto _JSON_ se puede analizar fácilmente usando la función `eval()`.
- Aunque comunmente se le considere una alternativa a _XML_, se pueden usar ambos a la vez.

## [YAML](https://yaml.org)

_YAML_ es un formato de serialización de datos legible por humanos inspirado en lenguajes como _XML_, _C_, _Python_, _Perl_, así como en el formato de los correos electrónicos. Fue creado bajo la creencia de que todos los datos pueden ser representados adecuadamente como combinaciones de listas, hashes (mapeos) y datos escalares (valores simples).

### Características principales

- La sintaxis es relativamente sencilla y fue diseñada teniendo en cuenta que fuera muy legible pero que a la vez fuese fácilmente mapeable a los tipos de datos más comunes en la mayoría de los lenguajes de alto nivel.
- Los contenidos en YAML se describen utilizando el conjunto de caracteres imprimibles de Unicode, bien en UTF-8 o UTF-16.
- La estructura del documento se denota indentando con espacios en blanco; sin embargo no se permite el uso de caracteres de tabulación para sangrar.
- Utiliza una notación basada en la sangría y/o un conjunto de caracteres Sigil distintos de los que se usan en XML, haciendo que sea fácil componer ambos lenguajes.

## Diferencias destacables

Podemos considerar que YAML es un superconjunto de JSON que trata de superar algunas de las limitaciones de este. Aunque es significativamente más complejo, todavía puede considerarse como un leguaje de marcado ligero. Además, JSON admite objetos de datos como valores, mientras que YAML no. Sin embargo, YAML admite más tipos de datos y utiliza de forma más próxima el lenguaje natural para que los desarrolladores puedan utilizarlo.

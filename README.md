# Plantilla para protocolo de tesis
En este archuvo encontrarás una plantilla en $\LaTeX$ para hacer tu protoclo de tesis, está lista para usar, solo debes reemplazar tus datos en los campos requeridos. El color de énfasis para los títulos y subtitulos se puede editar fácilmente.

La ruta de carpetas para visualizar el PDF es la siguiente

```
main/build/main.pdf
```

## Notas útiles
He puesto anotaciones en el el documento y aquí las resumo.
***
### Quitar sangria
Por defecto cada párrafo que inicies va a llevar una sangría, lo correcto sería que solo el primer párrafo la lleve, para quitar las sangrías de los nuevos párrafos que escribas solo debes encerrar el text en el siguiente comando:

```
\noindent{Aqui va tu texto sin sangría}
```
***
### Color del texto
Puedes cambiar fácilmente el color del énfasis de los títulos, solo busca donde este el comando 

```
\color{}
```
 y sustituye con cualquiera de los nombres (exactamente) que aparecen en la tabla de abajo

![](https://sharelatex-wiki-cdn-671420.c.cdn77.org/learn-scripts/images/e/ef/OLxcolorList2.png)

***
### Cronograma de actividades
Usa la siguiente herramienta web para hacer las tablas como Excel y automáticamente te generará el código para copiar y pegar en el documento. [Da click aquí](https://www.tablesgenerator.com/ "Tablas en LaTeX")

De igual manera el campo de las firmas está generado como una tabla.

### Bibliografía
Para incertar bibliografía en el documento solo copia y pega la cita en el archivo  `mybib.bib`, estas citas las puedes contrar directamente en las páginas de las revistas donde encontraste el artículo, solo sería cuestión de copiar y pegar.

Para citar tu texto, sólo debes colocar el comando despúes del texto que deseas referenciar.
```
 \citep{Palabra clave de la referencia}
```
La palabra clave la puedes ver al principio de la referencia que pegaste en el archivo `mybib.bib`, por ejemplo 

```
 @article{Palabra clave de la referencia,
  abstract = {This document contains a review on the quark model},
  author   = {Jean-Marc Richard},
  month    = {5},
  title    = {An introduction to the quark model},
  url      = {http://arxiv.org/abs/1205.4326},
  year     = {2012}
}
```
>NOTA
>>Las referencias en el archivo .bib deben estar en orden de aparición para que respete la numeración.


## Espero te ayude :D
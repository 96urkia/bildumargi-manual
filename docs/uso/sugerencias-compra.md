# Sugerencias de compra

**Sugerencias de compra** cruza la demanda de tu fondo con lo que tienen otras
bibliotecas y con lo que se publica. Tiene tres fuentes, siempre en el menú:

| Fuente | Necesita |
|---|---|
| **Presencia en otras bibliotecas** | El [catálogo de la red](../administracion/catalogo-marc.md) (`.db`) |
| **Novedades** | Una cuenta de [DILVE](../administracion/dilve.md) |
| **Autores más prestados** | Una cuenta de [DILVE](../administracion/dilve.md) |

Si falta lo que necesita una fuente, la lista lo explica y lleva a
Configuración. Con cuenta de DILVE, todo lo que hay que descargar se descarga
solo.

## El panel de arriba: dónde comprar

Es igual en las tres fuentes:

- **Indicadores generales** del fondo.
- **¿Dónde hace más falta comprar?**: una matriz que cruza el **uso relativo**
  de cada sección (altura) con su **actualidad** (izquierda-derecha). El
  tamaño de cada círculo son los volúmenes de la sección. Las secciones
  prioritarias combinan más demanda que peso con un fondo menos actualizado.
- **Demanda por sección**: el uso relativo y la actualidad de cada sección en
  barras, con las prioritarias primero.

Al pulsar una sección, la lista de abajo se acota a ella.

![Lista acotada a la sección IC (Cómic infantil) tras pulsarla en la matriz](../img/compras-seccion.png)

## Tres fuentes de títulos

En el menú lateral eliges de dónde salen las sugerencias.

### Presencia en otras bibliotecas

Los títulos que tienen otras bibliotecas de la red y tu biblioteca no,
ordenados por el número de bibliotecas que los tienen. Sale del catálogo
colectivo de la red: Bildumargi lo prepara al extraer el idioma (ver
[Catálogo MARC](../administracion/catalogo-marc.md)), con los títulos de los
últimos 20 años que están en al menos dos bibliotecas. No salen los que ya
tienes, por ISBN o por título.

Se filtra por sección, idioma y años de publicación. La sección de cada título
es la que le da la mayoría de las bibliotecas por su signatura. El CSV incluye
ISBN y editorial, para pedirlo.

### Autores más prestados

Otras obras, a la venta, de los autores que más se prestan en tu biblioteca.
Se cuenta **por autor, con todos sus libros**:

- se toman los autores que suman la mitad de los préstamos de cada sección;
- de **todos** sus libros en tu fondo se piden a DILVE sus «otras obras»;
- primero van los autores que más se prestan y aquellos de los que sale la
  mayor parte de los ejemplares.

Cada propuesta lo explica, por ejemplo:

> Javier Castillo: 8 títulos en tu fondo · 8 de 8 ejemplares prestados ·
> 116 préstamos (el más prestado: «El día que se perdió el amor», 23)

Tiene filtros de idioma, sección y edad. No se repiten ediciones de una misma
obra, y como mucho salen tres libros por autor.

La primera vez se calcula en segundo plano: verás un aviso de progreso. El
resultado se guarda y no se vuelve a calcular mientras tu préstamo no cambie;
para rehacerlo está **Volver a calcular**.

![Autores más prestados: obras del mismo autor que no tienes, con sus libros y préstamos en tu fondo (portadas y resúmenes difuminados)](../img/compras-autores.png)

### Novedades

Las novedades editoriales de DILVE: ver [Novedades de DILVE](novedades.md).

## La ficha de un título

Al pulsar un título se abre su ficha a la derecha: portada, autoría,
editorial, fecha, colección, sección, idioma, resumen, palabras clave y
materias. Se puede ampliar con el botón de arriba o ensanchar arrastrando su
borde izquierdo.

!!! info "Sin precios"
    Bildumargi no maneja precios ni presupuestos.

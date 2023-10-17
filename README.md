# Creación de BD y consultas
# Registro de BASE DE DATOS

# Base de Datos:

### Zapateria: Fabricante, Articulo

## Tablas: 

### Fabricante: Codigo, Nombre

### Articulo: Codigo, Nombre, Precio, Codigo_fab

## Fabricante:

### Codigo: 1, 2, 3, 4

### Nombre: Maya, Pepito, Calcin, Equimoda

## Articulo: 

### Codigo: 1, 2, 3, 4, 5, 6, 7, 8

#### Nombre: Zapato hombre, Sandalia, Zapatilla, Chocato Zapato niño, Apache, Mocasin, Tenis

### Precio: 70000, 35000, 60000, 8000, 40000, 40000,  45000, 95000

### Codigo_fab: 1, 4, 2, 3, 1, 3, 2,1

# Dicionario de datos

##           Fabricante         

| Campo  | Tipo de dato | Longitud |
|--------|--------------|----------|
| Codigo |   varchar    |    15    |
| Nombre |     text     |    15    |

##           Articulo 

|   Campo    | Tipo de dato | Longitud |
|------------|--------------|----------|
|   Codigo   |   varchar    |    15    |
|   Nombre   |     text     |    100   |
|   Precio   |   varchar    |    100   |
| codigo_fab |   varchar    |    10    |

# Tablas

## Fabricante:

![Tabla_ Fabricante](IMGs/Tabla_Fabricante.png "Tabla_Fabricante")

## Articulo:

![Tabla_ Articulo](IMGs/Tabla_Articulo.png "Tabla_Articulo")

##  Tipo de Relación: Uno a muchos

![Relación](IMGs/Relación.png "Relación")

#  Consultas BD Zapatería

## Consulta N°1

### Obtener los nombres de los productos de la Zapateria.

' SELECT Nombre FROM `Articulo`; '

![Consulta_1](IMGs/Consulta_1.png "Consulta_1")

## Consulta N°2

### Obtener los nombres y los precios de los productos de la Zapatería.

' SELECT Nombre, Precio FROM `Articulo`; '

![Consulta_2](IMGs/Consulta_2.png "Consulta_2")

## Consulta N°3

### Obtener el nombre de los productos cuyo precio sea menor o igual a 5000.

' SELECT Nombre, Precio FROM `Articulo` WHERE Precio <= 50000; '

![Consulta_1](IMGs/Consulta_3.png "Consulta_3")

## Consulta N°4

### Obtener todos los datos de los artículos cuyo precio esté entre 5000 y 40000 (ambas canditades incluidas).

'  '

![Consulta_4](IMGs/Consulta_4.png "Consulta_4")

## Consulta N°5

### Obtener el nombre y el precio de cada artículo, en dolares.

'  '

![Consulta_5](IMGs/Consulta_5.png "Consulta_5")

## Consulta N°6

### Obtener el precio promedio de todos los artículos.

'  '

![Consulta_6](IMGs/Consulta_6.png "Consulta_6")

## Consulta N°7

### Obtener el precio medio de los artículos cuyo codigo de fabricante sea 2.

'  '

![Consulta_7](IMGs/Consulta_7.png "Consulta_7")

## Consulta N°8

### Obtener el número de artículos cuyo precio sea mayor o igual a 50000.

'  '

![Consulta_8](IMGs/Consulta_8.png "Consulta_8")

## Consulta N°9

### Obtener el nombre y precio de los artículos cuyo precio sea mayor o igual a 50000 y ordenarlos descendentemente por precio, y luego ascendentemente por nombre.

'  '

![Consulta_9](IMGs/Consulta_9.png "Consulta_9")

## Consulta N°10

### Obtener un listado completo de artículos, incluyendo por cada articulo los datos del artículo y de su fabricante.

'  '

![Consulta_10](IMGs/Consulta_10.png "Consulta_10")

## Consulta N°11

### Obtener un listado de articulos, incluyendo el nombre del articulo, su precio y el nombre de su fabricante.

'  '

![Consulta_11](IMGs/Consulta_11.png "Consulta_11")
## Consulta N°12

### Obtener el precio medio de los productos  de cada frabricante, mostrando solo los codigos de fabricante.
'  '

![Consulta_12](IMGs/Consulta_12.png "Consulta_12")
## Consulta N°13

### Obtener el precio medio de los productos de cada fabricante, mostrando el nombre del fabricante.

'  '

![Consulta_13](IMGs/Consulta_13.png "Consulta_13")

## Consulta N°14

### Obtener el nombre de los fabricantes que ofrezcan productos cuyo precio medio sea mayor o igual a 50000.

'  '

![Consulta_14](IMGs/Consulta_14.png "Consulta_14")

## Consulta N°15

### Obtener el nombre y el precio del artículo mas barato.

'  '

![Consulta_15](IMGs/Consulta_15.png "Consulta_15")
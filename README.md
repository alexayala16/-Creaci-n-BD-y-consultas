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
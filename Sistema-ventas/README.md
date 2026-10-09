# Sistema de Ventas — MySQL

## Descripción

Proyecto de base de datos relacional desarrollado con MySQL para administrar la información de una tienda. Permite registrar clientes, productos, categorías y ventas, además de realizar consultas para analizar los resultados comerciales.

## Tecnologías utilizadas

* MySQL Server 8.0
* MySQL Workbench
* Lenguaje SQL

## Estructura de la base de datos

La base de datos `sistema_ventas` contiene cinco tablas:

* **clientes:** información de los clientes.
* **categorias:** clasificación de los productos.
* **productos:** nombre, precio, existencias y categoría.
* **ventas:** registro de las compras realizadas.
* **detalle_venta:** productos, cantidades y precios de cada venta.

## Funcionalidades

* Registro de clientes, categorías y productos.
* Registro de ventas y sus detalles.
* Relaciones entre tablas mediante claves primarias y foráneas.
* Consultas con INNER JOIN.
* Cálculo de importes mediante SUM().
* Agrupación de resultados con GROUP BY.
* Identificación de clientes que generan más ingresos.
* Clasificación del inventario según las existencias.

## Consultas SQL aplicadas

El proyecto utiliza SELECT, INNER JOIN, COUNT, SUM, GROUP BY, ORDER BY y CASE para consultar y analizar la información.

## Objetivo

Practicar el diseño de bases de datos relacionales y el análisis de información mediante SQL, desarrollando habilidades aplicables a proyectos de gestión de datos.

## Autor

Estudiante de Ingeniería en Sistemas.

## Archivo del proyecto

`sistema_ventas.sql` contiene la exportación de la base de datos para su revisión y posible restauración en un servidor MySQL compatible.
## Evidencias del proyecto

### 1. Estructura de la base de datos

![Tablas del sistema](capturas/01_tablas.png)

### 2. Consulta de detalle de ventas con INNER JOIN

![Detalle de ventas](capturas/02_detalle_ventas.png)

### 3. Cálculo de totales por venta

![Totales de ventas](capturas/03_totales_ventas.png)

### 4. Clasificación del inventario

![Estado del inventario](capturas/04_inventario.png)

### 5. Análisis de clientes

![Análisis de clientes](capturas/05_mejores_clientes.png)

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

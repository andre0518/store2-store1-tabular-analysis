# Store 1 – Análisis Tabular de Clientes

Este es el segundo proyecto de Andreina Moreno en el Bootcamp de Científica de Datos (TripleTen).  
Aquí se transformó una estructura de listas anidadas en una tabla estructurada lista para análisis y visualización.

## Contexto del proyecto

Store 1 recopiló datos de sus clientes en una estructura de lista anidada con los siguientes elementos:

- `user_id`: identificador único del cliente
- `user_name`: lista con nombre y apellido
- `user_age`: edad del usuario
- `fav_categories`: categorías favoritas de artículos comprados
- `total_spendings`: monto gastado por categoría

El objetivo fue **convertir estos datos en un formato tabular limpio y expandido**, donde cada categoría de compra ocupe su propia fila, facilitando así los análisis posteriores.

## Objetivos

- Eliminar inconsistencias en nombres, edades y formatos.
- Convertir los datos en una estructura tabular (`lista de listas`) lista para análisis.
- Desplegar los datos de manera clara y estructurada por usuario y categoría.
- Preparar un resumen de la información para facilitar reportes.

## Resultado final

Se generó una tabla con los siguientes campos:

| Campo                  | Descripción                                        |
|------------------------|----------------------------------------------------|
| `user_id`              | ID del usuario                                     |
| `user_name`            | Nombre completo del usuario                        |
| `user_age`             | Edad del usuario (entero)                          |
| `purchase_category`    | Categoría comprada (una por fila)                  |
| `spending_per_category`| Monto gastado en esa categoría específica          |

## Herramientas utilizadas

- Python 3
- Jupyter Notebook
- Métodos de listas (`split`, `strip`, `replace`)
- Bucles `for`, condicionales, `zip()`, `f-strings`

## Autora: Andreina Moreno
andreina.0518@gmail.com
Santiago, Chile
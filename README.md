# E-Commerce Shipping Data visualization Project

## Descripción

Proyecto de visualización de datos generado con el fin de analizar y extraer las principales características y patrones generados en las ventas y envíos de equipos electrónicos por parte de una compañia multinacional E-commerce.

El presente proyecto se desarrolló usando *Power BI*.

## Contexto

Los productos electrónicos que son vendidos, previo a su envío se depositan en varios almacenes, cada producto cuenta con un nivel de importancia que puede ser bajo, medio y alto.

Los productos pueden ser enviados por distintos medios: aéreo, terreste y marítimo. Cada producto además de su precio cuenta con un descuento (si aplica) y su peso en gramos.

De lado de los clientes, cada cliente cuenta con un rating y con el número de ventas realizadas con anterioridad.

## Dataset

El dataset contiene el registro de ventas de equipos electrónicos, Contiene *10999* observaciones y 12 variables. Las variables contenidas en el dataset son:

- ID
- Warehouse block
- Mode of shipment
- Customer care calls
- Customer rating
- Cost of the product
- Prior purchases
- Product importance
- Gender
- Discount offered
- Weight in gms
- Reached on time

## Resultados

El proyecto de visualización cuenta con una pestaña en donde se realiza una breve introducción a la visualización.

![intro](images/intro.PNG?raw=true)

en la sección del Dashboard se generó en primer lugar un conjunto de indicadores en donde se tiene el número de envíos, el precio promedio de los productos, cuántos de estos productos se entregaron a tiempo y el peso promedio.

Se cuenta con gráficos en donde se detalla: 
- Método de envío
- Importancia de los productos
- Rating de clientes
- Almacén
- Género de los clientes, y 
- Número de ventas anteriores

![Dashboard](images/dashboard.PNG?raw=true)

Dado que *Power BI* es una herramienta dinámica, el usuario tiene la facilidad de realizar selecciones o filtros sobre cada uno de los gráficos e indicadores presentados, con el fin de descubrir patrones o información que sea de utilidad.

## Organización de archivos

El repositorio se encuentra organizado de la siguiente manera:

- `data/` 

    Se encuentra el dataset que sirvió como insumo para le desarrollo de la visualización.

- `images/` 
    
    Contiene las imágenes obtenidas desde la visualización.

- `output/` 

    Archivo pdf generado desde Power BI 

- `src/` 

    Contiene el archivo de Power BI (*.pbix*) con la visualización.

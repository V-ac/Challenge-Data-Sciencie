# 📊 Análisis de Rendimiento de Tiendas - Proyecto de Data Science

## 📝 Descripción del Proyecto
Este proyecto realiza un análisis comparativo del rendimiento de **cuatro tiendas** utilizando datos de ventas, calificaciones de clientes y costos de envío. El objetivo principal es identificar qué tienda es más rentable y cuál podría ser candidata a ser reemplazada para emprender un nuevo negocio, basándose en métricas clave como ingresos totales, ventas por categoría, calificaciones promedio y costos de envío.


## 📂 Estructura de los Datos
- **Fuente de datos**: Archivos CSV alojados en GitHub
  - [`tienda_1.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv)
  - [`tienda_2.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv)
  - [`tienda_3.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv)
  - [`tienda_4.csv`](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv)

- **Columnas principales**:
  - `Producto`: Nombre del producto vendido
  - `Categoría del Producto`: Categoría a la que pertenece (Muebles, Electrónicos, Juguetes, etc.)
  - `Precio`: Precio del producto
  - `Costo de envío`: Costo asociado al envío
  - `Fecha de Compra`: Fecha de la transacción
  - `Vendedor`: Nombre del vendedor
  - `Lugar de Compra`: Ciudad donde se realizó la compra
  - `Calificación`: Puntuación del cliente (1 a 5)
  - `Método de pago`: Forma de pago utilizada
  - `Cantidad de cuotas`: Número de cuotas (si aplica)
  - `lat` / `lon`: Coordenadas geográficas

## 📈 Análisis Realizados

### 1. **Análisis de Facturación (Ingresos Totales)**
   - Cálculo del ingreso total por tienda usando `sum()` sobre la columna 'Precio'
   - Visualización con gráfico de barras horizontales

<img width="1045" height="700" alt="image" src="https://github.com/user-attachments/assets/16faddbc-1cb5-432f-ba38-8c60d6880ba6" />

### 2. **Análisis de Ventas por categoria**
  - Cálculo de la venta por categorias en cada una de las tiendas concantenandolas al final para vesializar tablas
  - Visualización con gráfico de barras horizaontales

    La tabla con la información
<img width="634" height="277" alt="image" src="https://github.com/user-attachments/assets/306a7df3-d829-4ff4-b5b5-10282d1f4b0c" />

    Gráfica de barras:
<img width="1180" height="673" alt="image" src="https://github.com/user-attachments/assets/4b64ae01-1a4d-4e33-92af-d8bacefbc8f0" />

### 3. **Análisis de valoriación por tienda**
  - Cálculo del promedio ve loración por tienda
  - Visualización con gráfico de barras horizontales
<img width="1066" height="687" alt="image" src="https://github.com/user-attachments/assets/d473f453-2319-457f-8fe8-dadc8e885b26" />

### 4. **Análisis de productos más vendidos y menos vendidos por tienda**
  - Calculo de los productos más y menos vendidos por tienda

### 5. **Análisis de valor de del envío por promedio por tienda*
  - Cálculo de los costos de envío por tienda
  - Visualización con graficos de barras horizontales

<img width="1047" height="684" alt="image" src="https://github.com/user-attachments/assets/82a80dc9-cc58-4d0d-bbc6-a699042e6829" />

## Conclusiones del Análisis
"En el primer apartado nos damos cuenta de que la tienda uno es la que más ingresos ha generado con los datos que nos proporcionaron. En el segundo apartado nos damos cuenta de que los muebles son la categoría más vendida en las cuatro tiendas. Como tercer apartado, la tienda 3 es la que más puntuación tiene y la tienda 1 es la que peor puntación tiene; la tienda 1 es la que más vende, pero la que menos valoración tiene según los clientes. Como quinto punto, la tienda 1 es la que más tiene costo de envío y la tienda 4 es la que menos cobra por envío."

"La tienda 4 es la que menos genera ganancia, tiene una puntuación más menos y es la que menos cobra por envío. Aunque estas últimas dos partes son positivas, el que genere menos que las otras con un margen considerable, se puede decir que no es rentable seguir con la tienda 4."







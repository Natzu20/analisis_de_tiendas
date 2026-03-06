# 📊 Análisis de Ventas y Desempeño de Tiendas

## Índice
- [Descripción](#descripción)  
- [Tecnologías y Dependencias](#tecnologías-y-dependencias)  
- [Estructura de los Datos](#estructura-de-los-datos)  
- [Instalación y Uso](#instalación-y-uso)  
- [Análisis Realizado](#análisis-realizado)  
  - [1. Ingresos Totales por Tienda](#1-ingresos-totales-por-tienda)  
  - [2. Categorías y Productos Más Vendidos](#2-categorías-y-productos-más-vendidos)  
  - [3. Calificación Promedio de Clientes](#3-calificación-promedio-de-clientes)  
  - [4. Productos Menos Vendidos](#4-productos-menos-vendidos)  
  - [5. Costo Promedio de Envío](#5-costo-promedio-de-envío)  
- [Visualizaciones](#visualizaciones)  
- [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)  
- [Autor](#autor)  

---

## Descripción
Análisis de ventas de cuatro tiendas para evaluar su desempeño, comparando ingresos, productos, calificaciones de clientes y costos de envío, con visualizaciones que facilitan la interpretación de los resultados y permiten tomar decisiones estratégicas basadas en datos.  

---

## Tecnologías y Dependencias
- Python  
- pandas (para manipulación de datos)  
- matplotlib (para visualización de datos)  

---

## Estructura de los Datos
Cada tienda se representa en un archivo CSV accesible mediante URL:

- `tienda_1.csv`  
- `tienda_2.csv`  
- `tienda_3.csv`  
- `tienda_4.csv`  

Columnas principales:  

| Columna                | Descripción                        |
|------------------------|------------------------------------|
| Producto               | Nombre del producto                 |
| Categoría del Producto | Tipo de producto                    |
| Precio                 | Precio de venta                     |
| Costo de envío         | Costo de envío por producto         |
| Fecha de Compra        | Fecha de la transacción             |
| Vendedor               | Nombre del vendedor                 |
| Lugar de Compra        | Ubicación de la tienda              |
| Calificación           | Valoración del cliente (1-5)       |
| Método de pago         | Forma de pago utilizada             |
| Cantidad de cuotas     | Número de cuotas pagadas            |
| lat                    | Latitud de la tienda                |
| lon                    | Longitud de la tienda               |

Todos los datasets están completos y no presentan valores nulos.

---

## Instalación y Uso
1. Instalar las librerías necesarias: pandas y matplotlib.  
2. Cargar los datos de cada tienda desde las URLs.  
3. Explorar los datos, realizar análisis de ingresos, productos, calificaciones y costos de envío.  
4. Generar visualizaciones para comparar el desempeño de cada tienda.  

---

## Análisis Realizado

### 1. Ingresos Totales por Tienda
- Tienda 1: 1.150.880.400  
- Tienda 2: 1.116.343.500  
- Tienda 3: 1.098.019.600  
- Tienda 4: 1.038.375.700  

La Tienda 4 genera los ingresos más bajos.

---

### 2. Categorías y Productos Más Vendidos
- Categorías más populares: **Muebles, Electrónicos y Juguetes**.  
- Productos más vendidos varían según la tienda; destacan microondas, camas y artículos tecnológicos.

---

### 3. Calificación Promedio de Clientes
- Tienda 1: 3.98  
- Tienda 2: 4.04  
- Tienda 3: 4.05  
- Tienda 4: 4.00  

La satisfacción de clientes es adecuada, aunque Tienda 4 presenta un desempeño ligeramente inferior.

---

### 4. Productos Menos Vendidos
- Incluyen libros especializados, instrumentos musicales y electrodomésticos menos populares.  
- Tienda 4 muestra dispersión en ventas de productos menos vendidos, reflejando una menor consistencia.

---

### 5. Costo Promedio de Envío
- Tienda 1: 26.018,61  
- Tienda 2: 25.216,24  
- Tienda 3: 24.805,68  
- Tienda 4: 23.459,46  

El menor costo de envío de la Tienda 4 puede reflejar márgenes ajustados.

---

## Visualizaciones
Se generaron gráficos para facilitar la interpretación de los resultados:

- Ingresos por tienda: gráfico de barras  
- Distribución de categorías: gráficos circulares por tienda  
- Productos más y menos vendidos: gráficos comparativos de barras  
- Calificación promedio y costo de envío: gráficos de línea  

*(Se recomienda incluir los gráficos generados en la carpeta `images` y referenciarlos aquí para mejorar la presentación.)*

---

## Conclusiones y Recomendaciones
Tras analizar ingresos, ventas por categoría y producto, calificación de clientes y costos de envío:  

- La **Tienda 4** presenta el menor desempeño global.  
- Sus ingresos son los más bajos, su costo de envío más reducido y su dispersión en productos dificulta la gestión eficiente de inventario.  
- Se recomienda considerar la venta de la Tienda 4 para reinvertir en nuevas oportunidades y optimizar recursos en tiendas con mayor potencial económico.  

---

## Autor
**Natalia Puerto** – Proyecto de análisis de datos de ventas para evaluación de desempeño de tiendas.  

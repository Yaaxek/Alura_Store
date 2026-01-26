# Análisis de Ventas de Tiendas

Este proyecto tiene como objetivo analizar los datos de ventas de cuatro tiendas diferentes para identificar la tienda menos eficiente desde una perspectiva financiera y operativa, con el fin de proporcionar una recomendación de venta al Sr. Juan.

## Estructura del Proyecto

El proyecto se encuentra en un notebook de Google Colab que realiza los siguientes pasos:

1.  **Importación de Datos**: Carga los conjuntos de datos de ventas de las cuatro tiendas desde URLs de GitHub.
2.  **Exploración de Datos**: Realiza un análisis inicial de la estructura y tipos de datos de cada tienda.
3.  **Análisis de Facturación**: Calcula y compara los ingresos totales de cada tienda.
4.  **Ventas por Categoría**: Identifica las categorías de productos más y menos populares, así como el precio promedio por categoría.
5.  **Calificación Promedio**: Evalúa la satisfacción del cliente a través de la calificación promedio por tienda.
6.  **Productos Más y Menos Vendidos**: Determina los productos con mayor y menor volumen de ventas.
7.  **Costo de Envío Promedio**: Analiza el costo promedio de envío por tienda.
8.  **Informe Final**: Consolida todos los hallazgos y presenta una recomendación justificada.

## Instalación y Dependencias

Este proyecto utiliza las siguientes librerías de Python:

*   `pandas`: Para la manipulación y análisis de datos.
*   `matplotlib.pyplot`: Para la creación de visualizaciones estáticas.
*   `numpy`: Para operaciones numéricas.

## Cómo Ejecutar el Proyecto

1.  Abre el notebook en Google Colab.
2.  Asegúrate de que todas las librerías necesarias estén instaladas.
3.  Ejecuta las celdas del notebook secuencialmente. El flujo de análisis está diseñado para ser ejecutado de principio a fin.
4.  Las visualizaciones y los resúmenes de los análisis se mostrarán directamente en el output de cada celda.

## Análisis Realizado

### Ingreso Total por Tienda

Se analizó el ingreso total de cada una de las cuatro tiendas. La **Tienda 4** fue identificada como la de menor ingreso, con una diferencia significativa respecto a sus competidores.

*   Tienda 1: $1,150,880,000
*   Tienda 2: $1,116,344,000
*   Tienda 3: $1,098,020,000
*   Tienda 4: $1,038,376,000

### Categorías de Productos

Las categorías más populares en todas las tiendas son **Muebles**, **Electrónicos** y **Juguetes**. Sin embargo, la **Tienda 2** mostró las menores ventas en estas categorías de alto ingreso. Las categorías menos vendidas incluyen **Libros**, **Instrumentos Musicales** y **Artículos para el Hogar**.

### Productos Más y Menos Vendidos

Se identificaron los productos más y menos vendidos por cada tienda. La **Tienda 2** y la **Tienda 4** mostraron patrones de venta menos efectivos en comparación con la Tienda 1 y la Tienda 3, especialmente en categorías de alto valor.

### Costo Promedio de Envío

El costo de envío promedio varía entre las tiendas, aunque es asumido por el cliente. La **Tienda 4** tiene el costo de envío más bajo, mientras que la **Tienda 1** y la **Tienda 2** presentan los costos más altos, lo que podría indicar problemas logísticos o un factor disuasorio para los clientes.

*   Tienda 4: (Costo de envío más bajo)
*   Tienda 3: (Segundo más bajo)
*   Tienda 2: (Ligeramente inferior a Tienda 1)
*   Tienda 1: (Costo de envío más alto)

### Satisfacción Promedio del Cliente

La satisfacción del cliente, medida por la calificación promedio, es relativamente uniforme en todas las tiendas, con pequeñas variaciones. La **Tienda 3** tiene el porcentaje ligeramente más alto, seguida de la Tienda 2, Tienda 4 y finalmente Tienda 1.

## Conclusión y Recomendación

Considerando todos los factores analizados (ingresos totales, ventas por categoría y producto, costos de envío y satisfacción del cliente), se recomienda al Sr. Juan **vender la Tienda 4.**

A pesar de tener el costo de envío más bajo y una satisfacción del cliente comparable a las demás, la **Tienda 4** registra consistentemente el menor ingreso total. Aunque tiene productos líderes de ventas como 'Cama box', su estrategia general o el volumen de ventas de otros artículos son menos efectivos en comparación con las otras tiendas. Esto la convierte en la opción menos eficiente financieramente y, por lo tanto, la principal candidata para la venta.

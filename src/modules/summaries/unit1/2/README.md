**Clase 1: Propuesta BI**

## BI Canvas

1. **Fuentes de datos**: Lista las fuentes (bases de datos, archivos, APIs) y la estructura básica de los datos que se utilizarán.

2. **Procesos de transformación de datos**: Cómo se limpiaran los datos, reglas para transformar los datos, cómo manejardatos faltantes o inconsistencias, y cómo cargar esos datos transformados al sistema final. (Extract, Transform, Load) para preparar los datos.

3. **Sistemas ETL/DW**: Herramientas y sistemas que se utilizarán para ejecutar procesos de extracción, transformación y carga, y cómo se almacenarán los datos finales. (Data Warehouse, bases de datos).

4. **Propuesta de valor**: Define por qué se está implementando el proyecto de Business Intelligence y cuál es el valor que aportará a la organización.

5. **Tipo de modelo de almacenamiento**: Identifica el modelo de datos (relacional, estrella, copo de nieve).
   1. **Modelo Relacional**: Úsalo para sistemas transaccionales con datos bien estructurados y muchas relaciones (bancos, inventarios).
   2. **Modelo Estrella**: Ideal para análisis rápidos en BI con datos centralizados y dimensiones simples (reportes de ventas o marketing).
   3. **Modelo Copo de Nieve**: Apto para análisis complejos donde las dimensiones tienen subniveles (productos con múltiples categorías).
   4. **Modelo Jerárquico**: Útil para datos con relaciones padre-hijo claras (estructuras organizacionales).
   5. **Modelo Multidimensional**: Perfecto para análisis OLAP que requieran múltiples perspectivas simultáneas (ventas por región, producto y periodo).

6. **Roles de usuarios**: Define los tipos de usuarios y sus funciones dentro del sistema.

7. **Vistas propuestas (Frontend)**: Menciona las herramientas de visualización (Power BI, Tableau) y cómo se mostrarán los datos.
   1. **Herramientas de visualización**: Menciona las herramientas (Power BI, Tableau) que se usarán para presentar los datos.
   2. **Tipo de visualizaciones**: Especifica los gráficos o tablas que se mostrarán (barras, líneas, mapas).
   3. **Interactividad**: Indica si los usuarios podrán aplicar filtros o realizar drill-down en los datos.
   4. **Audiencia**: Define quiénes usarán las visualizaciones y qué información necesitan ver.

8. **Recursos**: Incluye presupuesto, personal y herramientas necesarias para implementar el proyecto.

9.  **Permisos y seguridad**: Establece las políticas de acceso y seguridad para proteger los datos.

10. **Soporte requerido**: Enumera procesos de mantenimiento, soporte técnico y respaldo de datos.


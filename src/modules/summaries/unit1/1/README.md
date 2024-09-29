**Clase 1: Inteligencia de Negocios y Asistencia en Toma de Decisiones**

### Índice

- [1. Introducción al Entorno Empresarial](#1-introducción-al-entorno-empresarial)
  - [1.1. Marco Temprano para la Toma de Decisiones Gerenciales](#11-marco-temprano-para-la-toma-de-decisiones-gerenciales)
- [2. ¿Que es un sistema de apoyo a la toma de decisiones (DSS)?](#2-que-es-un-sistema-de-apoyo-a-la-toma-de-decisiones-dss)
  - [2.1. Componentes de la arquitectura DSS](#21-componentes-de-la-arquitectura-dss)
  - [2.2. Processo de toma de decisiones](#22-processo-de-toma-de-decisiones)
  - [2.3. Tipos de sistemas de apoyo a la toma de decisiones](#23-tipos-de-sistemas-de-apoyo-a-la-toma-de-decisiones)
- [3. ¿Qué es la inteligencia de negocios (BI)?](#3-qué-es-la-inteligencia-de-negocios-bi)
  - [3.1. Componentes en una arquitectura de BI](#31-componentes-en-una-arquitectura-de-bi)
  - [3.2. ¿Qué es un estilo de BI?](#32-qué-es-un-estilo-de-bi)
  - [3.3. Estilos de BI](#33-estilos-de-bi)
- [4. Relación entre DSS y BI](#4-relación-entre-dss-y-bi)
- [5. Impacto en el entorno de trabajo](#5-impacto-en-el-entorno-de-trabajo)
- [6. Principales categorías de herramientas para MSS (Management Support Systems)](#6-principales-categorías-de-herramientas-para-mss-management-support-systems)
- [7. Procesamiento de transacciones OLTP vs. Procesamiento analítico OLAP](#7-procesamiento-de-transacciones-oltp-vs-procesamiento-analítico-olap)
- [8. ¿Cuándo un sistema BI es exitoso?](#8-cuándo-un-sistema-bi-es-exitoso)
- [9. Problemas de BI y consideraciones](#9-problemas-de-bi-y-consideraciones)
- [10. BI en tiempo real](#10-bi-en-tiempo-real)

## 1. Introducción al Entorno Empresarial
En un entorno empresarial competitivo, las organizaciones deben resolver problemas y aprovechar oportunidades para sobrevivir y prosperar. La capacidad de tomar decisiones informadas y estratégicas es crucial para adaptarse a los cambios del mercado y mejorar el rendimiento.

### 1.1. Marco Temprano para la Toma de Decisiones Gerenciales
Antes de la implementación de sistemas avanzados como DSS y BI, los gerentes dependían principalmente de la intuición, experiencia y reportes manuales para tomar decisiones. Estos métodos eran menos eficientes y propensos a errores, lo que destacaba la necesidad de sistemas de apoyo más robustos.


## 2. ¿Que es un sistema de apoyo a la toma de decisiones (DSS)?
Es un sistema que ayuda a los gerentes a tomar decisiones no estructuradas (impredecibles y sin un proceso definido) o semiestructuradas (que combinan elementos predecibles e impredecibles), utilizando modelos y análisis específicos para ofrecer soluciones en situaciones concretas y complejas. Su propósito es facilitar la toma de decisiones en problemas puntuales.

Ejemplo: Un gerente de ventas necesita decidir cuántos productos ordenar para la próxima temporada. Utiliza un DSS que analiza datos de ventas anteriores, tendencias del mercado y condiciones actuales para recomendar la cantidad óptima de productos a pedir.

### 2.1. Componentes de la arquitectura DSS

1. **Datos/Información**: Información relevante recopilada para la toma de decisiones.
2. **Modelo**: Herramientas de simulación y predicción que utilizan los datos para crear escenarios.
3. **Conocimiento/Inteligencia**: Incluye el análisis y procesamiento de datos para extraer conclusiones y generar insights.
4. **Usuario**: La persona que utiliza la información y los modelos para tomar decisiones.
5. **Interfaz**: API o interfaz de usuario que permite interactuar con el sistema y acceder a la información, análisis y modelos.

### 2.2. Processo de toma de decisiones
Identificar un problema, recopilar información relevante, analizarla y elegir la mejor solución son pasos clave en la toma de decisiones. Un DSS facilita este proceso al proporcionar datos y herramientas que ayudan a los gerentes a tomar decisiones informadas, ya sea en problemas estructurados (claramente definidos) o no estructurados (menos claros y predecibles).


### 2.3. Tipos de sistemas de apoyo a la toma de decisiones

* **DSS orientado a modelos**: Se enfoca en usar modelos matemáticos, simulaciones o fórmulas para ayudar a resolver problemas y tomar decisiones. Por ejemplo, si un gerente quiere saber cómo afectaría un cambio de precio en las ventas, este tipo de DSS le permite simular diferentes escenarios y ver posibles resultados. El propósito es ofrecer opciones basadas en cálculos y simulaciones para tomar decisiones más informadas.

* **DSS orientado a datos**: Se concentra en analizar grandes cantidades de datos y presentarlos de manera que sean útiles para la toma de decisiones. Por ejemplo, un gerente puede utilizar este tipo de DSS para analizar las ventas de los últimos años y descubrir tendencias o patrones que le ayuden a tomar decisiones futuras. Su propósito es ayudar a entender el pasado y presente, proporcionando información detallada y relevante que guíe la decisión.

Ambos tipos de DSS ofrecen un apoyo valioso a los gerentes: uno se enfoca más en simular y proyectar posibles escenarios (DSS orientado a modelos), mientras que el otro proporciona un análisis profundo de los datos disponibles (DSS orientado a datos) para facilitar decisiones informadas.

## 3. ¿Qué es la inteligencia de negocios (BI)?
Es un conjunto de herramientas y procesos que recopilan, analizan y presentan datos para transformar información bruta en insights útiles. BI permite a las organizaciones identificar tendencias y tomar decisiones estratégicas para mejorar su rendimiento general, proporcionando una visión completa del negocio.

Ejemplo: Una empresa utiliza BI para analizar las ventas mensuales de sus productos en diferentes regiones. Con esta información, descubre que cierto producto se vende mejor en una región específica y toma la decisión estratégica de enfocar más campañas de marketing en esa área.

### 3.1. Componentes en una arquitectura de BI

1. **Data warehouse**: Un repositorio central donde se almacenan los datos provenientes de diferentes fuentes, sirviendo como base para los análisis.
2. **Analítica de negocios**: Conjunto de herramientas que permiten manipular, extraer y analizar los datos almacenados en el data warehouse para obtener insights.
3. **Gestión del rendimiento empresarial (BPM)**: Procesos y herramientas que permiten supervisar y analizar el rendimiento de la organización, ayudando a identificar áreas de mejora y cumplir objetivos.
4. **Interfaz de usuario**: El medio, como un dashboard, que facilita a los usuarios la visualización e interacción con los datos y análisis realizados, presentando la información de forma clara y comprensible.

### 3.2. ¿Qué es un estilo de BI?
Es la forma de presentar y analizar datos para ayudar a las personas a tomar decisiones en la empresa. Cada estilo usa un método diferente, como mostrar informes, gráficos, análisis de datos, o permitir hacer preguntas específicas sobre la información disponible.

### 3.3. Estilos de BI

1. **Entrega de informes y alertas**: Informa de eventos importantes en tiempo real. Se usa para monitorear cambios; por ejemplo, alertas de ventas diarias que superan un objetivo.

2. **Informes empresariales (paneles y cuadros de mando)**: Muestra datos clave en gráficos o tablas. Se usa para seguir el desempeño general; por ejemplo, un dashboard que muestra ventas por región.

3. **Análisis de cubos (rebanadas y dados)**: Permite ver datos desde diferentes ángulos. Se usa para analizar información detallada; por ejemplo, ver ventas por producto y región en un cubo de datos.

4. **Consultas ad-hoc**: Responde preguntas específicas sobre datos en el momento. Se usa para análisis rápido; por ejemplo, consultar ventas de un producto en un mes determinado.

5. **Estadísticas y minería de datos**: Descubre patrones y tendencias en datos grandes. Se usa para predecir comportamientos; por ejemplo, identificar clientes que probablemente comprarán un producto.

## 4. Relación entre DSS y BI

1. **BI evolucionó a partir de DSS**: BI se desarrolló tomando como base los conceptos de DSS, ampliando su alcance.
2. **Propósito diferente**: DSS apoya decisiones específicas, mientras que BI proporciona información precisa y oportuna para decisiones estratégicas de manera indirecta.
3. **Enfoque de uso**: BI es más estratégico y ejecutivo, mientras que DSS es utilizado por analistas para resolver problemas concretos.
4. **Implementación**: BI utiliza herramientas comerciales ya disponibles, mientras que DSS generalmente se crea desde cero para necesidades específicas.
5. **Origen**: DSS se desarrolla principalmente en el mundo académico, mientras que BI y sus herramientas son desarrollados por empresas de software.
6. **Herramientas compartidas**: Muchas herramientas de BI, como análisis de datos y OLAP, se consideran también parte de DSS por su capacidad de apoyar la toma de decisiones.


## 5. Impacto en el entorno de trabajo

1. **Proceso de negocio**: Cómo se mejoran o cambian los procedimientos internos.
2. **Participantes**: Cómo afecta a los empleados y colaboradores.
3. **Información**: La forma en que se recopila, gestiona y utiliza la información.
4. **Tecnología**: El uso y adaptación de nuevas herramientas y sistemas.
5. **Productos y servicios**: Cambios en la calidad o variedad ofrecida.
6. **Clientes**: Cómo se influye en la experiencia y satisfacción del cliente.
7. **Infraestructura**: Impacto en los recursos físicos y tecnológicos.
8. **Medio ambiente**: Cómo afecta a la sostenibilidad y prácticas ecológicas.
9. **Estrategia**: Modificaciones en los objetivos y planes de la organización.

## 6. Principales categorías de herramientas para MSS (Management Support Systems)

1. **Sistemas de apoyo a la toma de decisiones (DSS)**: Ayudan a los gerentes a tomar decisiones en problemas específicos mediante modelos y análisis.
2. **Sistemas de información ejecutiva (EIS)**: Proporcionan información crítica y visualizaciones para la toma de decisiones de altos ejecutivos.
3. **Sistemas de apoyo a decisiones en grupo (GDSS)**: Facilitan la toma de decisiones en equipo, ofreciendo herramientas de colaboración y comunicación.
4. **Sistemas de inteligencia de negocios (BI)**: Analizan grandes volúmenes de datos para identificar tendencias y guiar decisiones estratégicas.
5. **Sistemas de gestión del conocimiento (KMS)**: Almacenan y gestionan el conocimiento de la organización para ayudar en la toma de decisiones.

**Ejemplos de herramientas específicas:**
- **DSS**: Microsoft Excel, IBM Cognos
- **EIS**: Tableau, QlikView
- **GDSS**: Microsoft Teams, Slack
- **BI**: Power BI, SAP BusinessObjects
- **KMS**: Confluence, SharePoint



## 7. Procesamiento de transacciones OLTP vs. Procesamiento analítico OLAP

1. **OLTP (Online Transaction Processing)**: Se enfoca en la actualización constante de datos, agregando, editando y eliminando información para manejar las operaciones diarias del negocio. Busca alta eficiencia y se utiliza en sistemas como ERP y CRM.

2. **OLAP (Online Analytical Processing)**: Extrae y analiza la información almacenada en los sistemas OLTP. Permite realizar análisis profundos, identificar tendencias y obtener insights para la toma de decisiones estratégicas.

## 8. ¿Cuándo un sistema BI es exitoso?
Un sistema BI es exitoso cuando mejora significativamente la toma de decisiones al proporcionar información clara y relevante, aumentando el rendimiento organizacional y optimizando procesos. Debe estar alineado con la estrategia de la empresa, ser adoptado por usuarios en todos los niveles, ofrecer flexibilidad para adaptarse a cambios y proporcionar información en tiempo real para responder rápidamente a las necesidades del negocio. Cuando cumple con estos aspectos, el BI impulsa el crecimiento y la eficiencia de la organización.

## 9. Problemas de BI y consideraciones
1. **Desarrollo vs. adquisición**: Decidir si se desarrolla internamente o se adquiere una solución de BI ya existente.
2. **Justificación**: Asegurar que la inversión en BI sea rentable y aporte valor.
3. **Seguridad y protección**: Garantizar la confidencialidad y protección de los datos.
4. **Integración**: Hacer que BI funcione bien con los sistemas y procesos existentes.

## 10. BI en tiempo real
A diferencia del BI tradicional, que trabaja con datos almacenados y procesados con cierto retraso, el BI en tiempo real permite acceder y analizar datos instantáneamente a medida que se generan. Se implementa cuando las organizaciones necesitan tomar decisiones rápidas basadas en información actualizada, como en casos de ventas en línea o seguimiento de inventario en tiempo real. Su objetivo es ofrecer una ventaja competitiva al responder rápidamente a cambios o problemas. Por ejemplo, mientras el BI tradicional podría mostrar las ventas del día anterior, el BI en tiempo real muestra las ventas minuto a minuto, permitiendo ajustar estrategias de inmediato si hay cambios en la demanda.

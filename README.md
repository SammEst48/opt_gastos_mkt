# 💰 Optimización de Gastos de Marketing para Y.Afisha

## Descripción del Proyecto
Este proyecto se centra en el análisis de datos para ayudar a Y.Afisha a optimizar sus gastos de marketing. Utilizando datos de visitas al sitio web, pedidos de clientes y gastos en marketing de las diferentes fuentes de adquisición, el objetivo es identificar patrones de comportamiento de los clientes, calcular métricas clave de desempeño (KPI) y asesorar al equipo de marketing sobre las inversiones más rentables.

El proyecto abarca los datos desde enero de 2017 hasta diciembre de 2018 y busca obtener una visión completa de cómo los usuarios interactúan con la plataforma, desde su primera visita hasta la realización de pedidos. El análisis incluye también la evaluación de la rentabilidad de cada fuente de adquisición.

## Objetivos
- Entender el comportamiento del usuario
- Evaluar el rendimiento de las ventas
- Optimizar el gasto en marketing
- Asesorar al equipo de marketing

## Estructura del Proyecto
1. Preparación de los datos
2. Análisis de Métricas Clave
3. Visualización de Resultados
4. Conclusiones y Recomendaciones

## Dataset
Este proyecto utiliza tres datasets clave, que contienen información de visitas al sitio web, pedidos realizados y gastos de marketing:

- **visits_log_us.csv**: Contiene datos de las visitas al sitio de Y.Afisha desde enero de 2017 hasta diciembre de 2018.
Uid: Identificador único del usuario.
Device: Dispositivo desde el que se realizó la visita.
Start Ts: Fecha y hora de inicio de la sesión.
End Ts: Fecha y hora de finalización de la sesión.
Source Id: Identificador de la fuente de adquisición del usuario.

- **orders_log_us.csv**: Registra los pedidos realizados en la plataforma durante el mismo periodo.
Uid: Identificador único del usuario que realizó el pedido.
Buy Ts: Fecha y hora en la que se realizó el pedido.
Revenue: Ingresos generados por el pedido.

- **costs_us.csv**: Incluye los gastos de marketing por fuente de adquisición.
source_id: Identificador de la fuente de anuncios.
dt: Fecha del gasto.
costs: Monto del gasto en marketing.

## Librerías Necesarias
- pandas, numpy, matplotlib, seaborn, datetime, scipy

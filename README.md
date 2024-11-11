# 💰 Optimización de Gastos de Marketing para Y.Afisha

## Descripción del Proyecto
Este proyecto se centra en el análisis de datos para ayudar a Y.Afisha a optimizar sus gastos de marketing. Utilizando datos de visitas al sitio web, pedidos de clientes y gastos en marketing de las diferentes fuentes de adquisición, el objetivo es identificar patrones de comportamiento de los clientes, calcular métricas clave de desempeño (KPI) y asesorar al equipo de marketing sobre las inversiones más rentables.

El proyecto abarca los datos desde enero de 2017 hasta diciembre de 2018 y busca obtener una visión completa de cómo los usuarios interactúan con la plataforma, desde su primera visita hasta la realización de pedidos. El análisis incluye también la evaluación de la rentabilidad de cada fuente de adquisición.

## Objetivos
- Entender el comportamiento del usuario
- Evaluar el rendimiento de las ventas
- Optimizar el gasto en marketing
- Asesorar al equipo de marketing

## Dataset
Este proyecto utiliza tres datasets clave, que contienen información de visitas al sitio web, pedidos realizados y gastos de marketing:

La tabla `visits` (registros del servidor con datos sobre las visitas al sitio web):
- **Uid**: identificador único del usuario;
- **Device**: dispositivo del usuario;
- **Start Ts**: fecha y hora de inicio de la sesión;
- **End Ts**: fecha y hora de término de la sesión;
- **Source Id**: identificador de la fuente de anuncios de la que proviene el usuario.

La tabla `orders` (datos sobre pedidos):
- **Uid**: identificador único del usuario que realiza un pedido;
- **Buy Ts**: fecha y hora del pedido;
- **Revenue**: ingresos de Y.Afisha de este pedido.

La tabla `costs` (datos sobre gastos de marketing):
- **source_id**: identificador de la fuente de anuncios
- **dt**: fecha;
- **costs**: gastos en esta fuente de anuncios en este día.

## Herramientas utilizadas
- **Python**: pandas, numpy, matplotlib, seaborn
- **Jupyter Notebooks**: para análisis interactivo.

## Pasos del análisis
1. Preparación de los datos
2. Análisis de Métricas Clave
3. Visualización de Resultados
4. Conclusiones y Recomendaciones

## Conclusiones
Se identifican tres fuentes 4, 5 y 9 como las más eficientes y rentables, pues muestran un bajo CAC y un alto ROMI, lo que significa que generan un retorno positivo sobre la inversión con un coste relativamente bajo por cliente adquirido. La recomendación se basa en la idea de que estas fuentes ofrecen el mejor equilibrio entre eficiencia y rentabilidad en la inversión en marketing.

## Visualizaciones
![image](https://github.com/user-attachments/assets/dc408c48-875d-4d29-8a12-1694293cec95)
![image](https://github.com/user-attachments/assets/b80ba1a7-138d-49d5-a9d4-ac5c33cbeae6)
![image](https://github.com/user-attachments/assets/01bd301f-c470-4f71-a1fe-f62469f2ddfa)






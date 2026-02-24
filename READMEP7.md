**Proyecto de Análisis de Comportamiento de Clientes: ConnectaTel**

**🎯Objetivo del Proyecto**
El objetivo de este proyecto es analizar el comportamiento de uso de los servicios de telefonía (llamadas, mensajes y consumo de datos) de los clientes de ConnectaTel. A través de la segmentación de clientes y el estudio de patrones de consumo, buscamos identificar segmentos clave, detectar usuarios con alto potencial de churn (abandono) y proponer mejoras en la oferta comercial basada en datos.

**📊 Datasets Utilizados**
El análisis se basa en la combinación de tres fuentes de datos principales:

users_latam.csv: Información demográfica del cliente (edad, ciudad, plan contratado, fecha de registro y fecha de retiro).

usage_logs.csv: Registro detallado de actividad (tipo de servicio, duración de llamadas, longitud de mensajes).

plans_info.csv: Detalle de los beneficios y costos de los planes disponibles (Básico y Premium).

**🚀 Etapas del Análisis**
El flujo de trabajo sigue las mejores prácticas de Ciencia de Datos:

Limpieza de Datos: Tratamiento de valores nulos, corrección de tipos de datos (datetime), manejo de sentinels (valores atípicos como -999 o '?') y eliminación de registros fuera de rango temporal.

Feature Engineering: Agregación de métricas por user_id (cant. llamadas, cant. mensajes, minutos totales).

Análisis Exploratorio (EDA): Visualización de distribuciones y detección de outliers mediante el método IQR.

Segmentación: Creación de categorías de clientes basadas en edad (Joven, Adulto, Adulto Mayor) y nivel de uso (Bajo, Medio, Alto).

Conclusiones Ejecutivas: Estrategias comerciales accionables.

**💻 Cómo ejecutar el Notebook**
Este proyecto está diseñado para ser ejecutado directamente en Google Colab.

Haz clic en el botón "Open in Colab" (si tienes el badge en tu repositorio) o simplemente sube el archivo .ipynb a tu Google Drive.

Asegúrate de tener los archivos .csv en la carpeta /datasets/ dentro de tu entorno de trabajo.

Ejecuta las celdas de código en orden secuencial.

**🛠 Guía de Reproducción**
Para replicar el análisis en tu entorno local:

Clonar el repositorio: git clone [https://github.com/pabloroalon1510/Data-analytics-portfolio/blob/main/P7%20Project-ConnectaTel.ipynb]

Requisitos: Asegúrate de tener instalado Python 3.9+ y las librerías necesarias:

Bash
pip install pandas numpy matplotlib seaborn
Configuración: Coloca tus archivos de datos en un directorio llamado datasets en la raíz del proyecto.

Ejecución: Abre el archivo notebook.ipynb con Jupyter Notebook o VS Code y ejecuta todas las celdas.

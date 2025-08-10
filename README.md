# Challenge Telecom X: Análisis de evasión de clientes 
<p align="center">
<img src="https://github.com/herbertturpo/challenge-telecomx-latam/blob/f6176c3574c81f6f9da65ef6456bebda034b8fea/imagenes/churn.png?raw=true" alt="distribucion_cargo_mensual.png"/>
<p>

## 🚀 Resumen del Proyecto  

Este proyecto es un análisis exhaustivo del abandono de clientes (**churn**) en una compañía de telecomunicaciones ficticia, **Telecom X LATAM**. El objetivo principal es identificar los factores clave que influyen en la decisión de un cliente de cancelar su servicio. A través de un proceso de **Análisis Exploratorio de Datos (EDA)**, limpieza de datos y visualizaciones, se han descubierto patrones y *insights* críticos que sirven como base para proponer estrategias de retención de clientes efectivas.  

Este proyecto fue desarrollado como parte del proceso formativo del programa de especialización en **Data Science**, en convenio con **Alura** y **Oracle Next Education**.  

El análisis se enfoca en tres áreas principales:  

- **Factores de Compromiso del Cliente:** Cómo el tipo de contrato, el método de pago y la facturación electrónica impactan en la retención.  
- **Factores de Servicio y Producto:** La relación entre el tipo de servicios contratados (internet, servicios adicionales) y el abandono.  
- **Factores Demográficos y de Estilo de Vida:** El papel de la edad, el género y la situación familiar en la lealtad del cliente.  

## 📁 Estructura del Repositorio  

El repositorio está organizado de la siguiente manera:  

- `notebooks/`: Carpeta que contiene el *notebook* de Jupyter (`TelecomX_LATAM.ipynb`) con todo el código de análisis, visualizaciones y los hallazgos detallados.  
- `data/`: Carpeta que almacena los datos en formato `.json` utilizados para el análisis.  
- `images/`: Directorio con las visualizaciones y gráficos generados durante el EDA, listos para ser usados en informes o presentaciones.  
- `README.md`: Este archivo, que proporciona una visión general del proyecto.  
- `TelecomX_diccionario.md`: Archivo que documenta las variables y su significado en el conjunto de datos.  

## 🛠️ Tecnologías y Herramientas  

- **Python:** Lenguaje de programación principal utilizado para el análisis de datos.  
- **Pandas:** Para la manipulación y limpieza de datos.  
- **Matplotlib y Seaborn:** Para la creación de visualizaciones y gráficos estadísticos.  
- **Jupyter Notebook:** Entorno interactivo de desarrollo para el análisis de datos.  
- **GitHub:** Para el control de versiones y la colaboración del proyecto.  

## 📈 Hallazgos Clave  

El análisis exploratorio de datos reveló que los factores más influyentes en el abandono de clientes son:  

- **Antigüedad:** Los clientes de **baja antigüedad** (especialmente en los primeros meses) tienen una tasa de abandono significativamente más alta.  
- **Compromiso:** Los clientes con contratos **"Mes a mes"** y que usan el **"Cheque electrónico"** como método de pago son los más propensos a irse.  
- **Servicios:** El servicio de **Fibra óptica** está asociado a una mayor tasa de abandono, lo que podría indicar una alta sensibilidad al precio o problemas de calidad en este segmento.  

## 🎯 Estrategias de Retención Propuestas  

Basado en los hallazgos, se sugieren las siguientes estrategias para mitigar el abandono:  

- **Programas de Retención Temprana:** Implementar seguimientos proactivos para clientes con menos de 6 meses de antigüedad.  
- **Incentivos para Contratos a Largo Plazo:** Ofrecer descuentos o beneficios por la migración a contratos de 1 o 2 años.  
- **Análisis Competitivo:** Investigar el mercado y la competencia, especialmente en el servicio de fibra óptica, para ajustar precios o mejorar el valor.  
- **Optimización del Proceso de Pago:** Incentivar el uso de métodos de pago automáticos, como transferencias bancarias o tarjetas de crédito, ofreciendo beneficios adicionales.  

## 👨‍💻 Cómo Usar este Repositorio  

1. Clona el repositorio:  
   ```bash
   git clone https://github.com/herbertturpo/challenge-telecomx-latam.git
2. Abre el notebook `TelecomX_LATAM.ipynb` en Jupyter para explorar el análisis detallado.

3. Revisa los archivos en la carpeta `images/` para ver las visualizaciones.

4. Consulta `TelecomX_diccionario.md` para entender el significado de cada variable.

## 📜 Autor
- Heriberto Turpo Quiro

  - (Proyecto desarrollado para el programa de especialización en Data Science de Alura y Oracle Next Education)

  - [LinkedIn](https://www.linkedin.com/in/heriberto-turpo-quiro/)

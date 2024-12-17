

<h1 align="center">PROYECTO - TELECOMUNICACIONES</h1>


![image](https://github.com/user-attachments/assets/2e073fac-224b-435e-a77d-c68636ed8095)


## Visión General del Proyecto

El propósito de este análisis es proporcionar un panorama sobre el desempeño del sector de telecomunicaciones en Argentina, específicamente en el ámbito del acceso a internet. A través de este estudio, se busca presentar a una empresa de telecomunicaciones un informe detallado sobre cómo se han comportado los usuarios a lo largo de los últimos diez años, con un enfoque tanto en la actualidad como en su evolución temporal. Este análisis abarca diversas tecnologías de conexión, velocidades de internet, así como el comportamiento de los usuarios en diferentes regiones del país.

## Objetivo y Enfoque

El objetivo de este trabajo es ofrecer una comprensión general del comportamiento del mercado de internet en Argentina, con el fin de asistir en la toma de decisiones estratégicas para empresas del sector, como la expansión de servicios, la mejora de la infraestructura y la identificación de nichos de mercado. El análisis de los datos permitirá predecir futuras áreas de enfoque y las tendencias post-pandemia, donde se espera un mercado aún más digitalizado y conectado.

## Instalación y Requisitos
Requisitos:  

Python 3.7 o superior  
pandas  
numpy  
scikit-learn   
Matplotlib  
Seaborn  

## Estructura del Proyecto

Notebook/: Jupyter notebooks con el análisis.  
Power Bi/: Archivos Power Bi interactivos del proyecto
README.md: Documentación.  


## Metodología del Proyecto

### ETL (Extracción, Transformación y Carga)

El proyecto comienza con la recopilación de datos desde la página web del ENACOM, que proporciona información sobre la penetración de internet y el desempeño de las telecomunicaciones en el país. Tras obtener los datos en formato Excel, se procedió a limpiar y transformar la información, consolidando las variables relevantes en un formato adecuado para su análisis. Los datos fueron luego cargados en las herramientas de análisis para su procesamiento.

#### SE USARON LAS SIGUIENTES HOJAS DEL EXCEL INTERNET.xlsx :

'Accesos por Tecnologia'

'Acc_vel_loc_sinrangos'  

'Penetración-poblacion' 

'Penetracion-hogares' 

#### SE USARON LAS SIGUIENTES HOJAS DEL EXCEL mapa_conectividad.xlsx :

'mapa_conectividad'  

### Análisis Exploratorio de Datos (EDA)

El primer paso en el análisis fue la exploración de los datos, que incluyó una revisión inicial de su calidad, identificando posibles valores faltantes o duplicados. Se clasificaron las variables en cuantitativas y cualitativas, y se realizaron análisis descriptivos para cada tipo de variable. Esto incluyó gráficos de distribucion de los datos para su visualizacion.

## Resultados y Conclusiones Generales

El análisis revela una disparidad significativa en la adopción y calidad de las tecnologías de internet en diferentes regiones del país, con una clara necesidad de mejorar la infraestructura en varias areas del territorio. Aunque se observa un avance en la adopción de tecnologías de acceso más modernas, como la fibra óptica, y un incremento en las velocidades de conexión, las provincias con menor inversión en infraestructura enfrentan grandes desafíos para reducir la brecha digital.

## Dashboard en Power BI

El proyecto incluye un Dashboard interactivo en Power BI para visualizar los datos de manera clara y comprensible. Las páginas principales del Dashboard incluyen las siguiente paginas:

* ACCESOS: Muestra como la cantidad de accesos al servicio de internet lo largo de los años en el pais de Argentina ademas como esta representada esta tendencia.

* TECNOLOGIAS: Muestra como esta distribuida las diferentes tecnologias que existen en las diferentes provincias y como van desarrollandose las nuevas tecnologias frente a las pasadas.

* VELOCIDADES: Muestra las velocidades promedio en mbps de cada provincia.

* PENETRACION: Muestra la escalabilidad de la penetracion del servicio de internet en los hogares y por familia en cada una de las provincias del Pais.

* KPIs: Muestra indicadores para objetivos propuestos asi como si estos objetivos se cumplieron en trimestres pasados.

## Glorsario de palabras

* ADSL: Tecnología de conexión a internet a través de líneas telefónicas de cobre, con velocidades moderadas y asimétricas (mayor descarga que subida).
* Cablemodem: Usa la red de televisión por cable (coaxial) para proporcionar internet de alta velocidad. Ofrece mayor capacidad que ADSL.
* Fibra Óptica: Tecnología que transmite datos a través de haces de luz por cables de fibra de vidrio, ofreciendo altísima velocidad y estabilidad.
* Wireless (Inalámbrica): Conexión a internet sin cables, mediante señales de radiofrecuencia (Wi-Fi, 4G/5G). Es flexible pero puede ser menos estable según la señal.
* Mbps (Megabits por Segundo): Unidad de medida de la velocidad de transmisión de datos. Cuanto mayor es el número de Mbps, mayor es la velocidad de la conexión.

## Datos y Fuentes

Link directo a los datasets: https://indicadores.enacom.gob.ar/datos-abiertos

## Resumen Final

Este análisis proporciona una visión clara de la situación actual de la industria de telecomunicaciones en Argentina, destacando tanto las áreas de progreso como las que requieren atención. Con base en los datos analizados, las empresas podrán tomar decisiones informadas para mejorar la calidad del servicio, identificar áreas de expansión y orientar sus inversiones hacia las regiones con mayor demanda y potencial de crecimiento.

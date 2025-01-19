# Comportamiento del sector de Internet en Argentina

### Tabla de contenido
1)	Descripción
2)	Requisitos e instalación
3)	Estructura del proyecto
4)	Datos y fuentes
5)	Visualizaciones
6)	Conclusiones
7)	Recomendaciones
8)	Autor

### Descripción

Este proyecto busca analizar el desarrollo y evolución en el sector de las telecomunicaciones, específicamente internet, en Argentina de 2014 a la fecha (segundo semestre 2024) en base a la cantidad de accesos a la red, mediante qué tecnologías y rango de velocidades por provincia para una importante empresa interesada en invertir en el país.

### Requisitos e instalación

Requisitos:
-	Python 3.8 o superior
-	Pandas
-	Matplotlib
-	Seaborn
-	Power Bi  2.139.1678.0 64-bit o superior
-	
Instalación:
-	Clonar el repositorio: git clone https://github.com/nahuelfns/Primer_proyecto_individual.git cd Segundo_proyecto_individual
-	Instalar las dependencias: pip install -r requirements.txt

### Estructura del proyecto

- Datasets: Contiene los archivos de datos.
- notebooks: Jupyter notebooks con los EDA
- Para_PwrBI: archivos utilizados para el dashboard
- Requirements.txt: contiene las dependencias a instalar
- README.md: descripción del proyecto
- Dashboard: panel con la presentación de un resumen visual de las métricas clave para explicar el comportamiento del sector en Argentina.

### Datos y fuentes

- ENACOM: https://indicadores.enacom.gob.ar/datos-abiertos (Internet)
- Valor dólar: dineroeneltiempo.com

### Metodología

- Identificación de patrones, anomalías, relaciones y distribuciones de los datos.
- Creación de gráficos como para identificar tendencias y patrones visualmente.
- Formulacíon de insights iniciales basadas en las observaciones

### Visualizaciones

Los EDA incluyen:
- Observación de tamaño y estructura del df.
- Creación de columna en los necesarios.
- Tratamiento de valores NaN ya sea reemplazándolos o eliminándolos según lo amerite la columna en la que se encuentran.
- Eliminación de columnas innecesarias.
- Transformación de tipo de dato de columnas.
- Búsqueda de outliers y duplicados
- Gráficos interactivos para análisis en profundidad de los datasets
- Uso de markdowns para Insigths y explicación de los pasos seguidos
- Joins de tablas

### Conclusiones

El análisis de los datos de acceso y velocidad de internet en Argentina revela varias tendencias y observaciones importantes. 
Las velocidades de conexión están experimentando un incremento general, impulsado primeramente por el reemplazo del ADSL por el cablemódem y a partir del 2019 por la adopción de tecnologías más avanzadas, como la fibra óptica. 
A pesar de que la fibra óptica aún representa un modesto 12% del total de conexiones a nivel nacional, su adopción está en aumento y muestra una tendencia clara al alza.
El acceso a velocidades de internet más altas no está uniformemente distribuido entre las provincias, evidenciando una brecha significativa en la infraestructura de telecomunicaciones. Las provincias más ricas tienden a tener acceso a mayores velocidades, pero esto no siempre se traduce en un mayor número de accesos. La oferta y demanda de servicios de internet varían significativamente entre regiones, lo que afecta tanto la velocidad como la cantidad de accesos.
La baja inversión en conectividad wireless, salvo algunas excepciones como la política implementada de WiFi gratis en San Luis, ha resultado en los niveles más bajos de acceso, algo entendible por sus contras como pueden ser la susceptibilidad a interferencias y obstrucciones físicas y que las velocidades y  estabilidad pueden variar según la distancia del punto de acceso y la cantidad de dispositivos conectados.
Ante este análisis Argentina es un mercado prometedor, lo que se infiere de los ingresos en dólares en el sector durante estos últimos 10 años que, aunque con algunos vaivenes, siempre fueron en aumento.

### Recomendaciones

En base a estas conclusiones, es evidente que la fibra óptica representa una oportunidad de inversión prometedora. Es la tecnología más avanzada disponible actualmente, tiene la capacidad de proporcionar velocidades de conexión significativamente más rápidas y posee gran ancho de banda, lo cual es cada vez más necesario debido a las constantes actualizaciones de aplicaciones y software que demandan mayor rapidez; además tiene la menor atenuación y perdida de señal en largas distancias ideal para un país tan extenso como Argentina
Para fomentar una mejor distribución e igualdad en el acceso a internet, se recomienda una mayor inversión en infraestructura de fibra óptica a nivel nacional. Esto no solo mejorará la velocidad y calidad de las conexiones, sino que también ayudará a reducir la brecha digital entre las distintas provincias, promoviendo un acceso más equitativo y sustentable.

### Autor

Facundo Nahuel Serqueira - Contacto: https://www.linkedin.com/in/facundo-nahuel-serqueira-aba554b/

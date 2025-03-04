📊 Análisis Exploratorio de Datos (EDA) para la Conversión de Clientes Bancarios

📌 Descripción del Proyecto
Este proyecto se enfoca en el análisis exploratorio de datos (EDA) aplicado a un conjunto de datos de clientes de un banco con el objetivo de comprender los factores que influyen en la conversión de adquisición de productos o servicios. A través de técnicas de limpieza, visualización y análisis estadístico, identificamos patrones clave que pueden ayudar a optimizar estrategias de marketing y mejorar la tasa de conversión.

![relacion entre duracion de llamada, numeros de veces contactadas y conversion](image.png)


#Contenido del Análisis
✔ Transformación y limpieza de datos
✔ Análisis descriptivo (Distribución de clientes, ingresos, duración de llamadas)
✔ Visualización de datos (Gráficos de tendencias y correlaciones)
✔ Factores clave en la conversión (Duración de llamadas, número de intentos, ingresos)
✔ Conclusiones y recomendaciones (Mejora de estrategias de contacto y segmentación)


 #Hallazgos Principales
📞 Duración de llamadas: Mayor duración, mayor probabilidad de conversión.
![mayor duracion llamada, mayor conversion](image-1.png)
📉 Número de intentos: Demasiados intentos pueden ser contraproducentes.
📅 Antigüedad del cliente: Clientes recientes tienen más probabilidades de conversión.
📈 Método de contacto: Las llamadas móviles tienen 3 veces más éxito que las llamadas a teléfonos fijos.
![Metodos de contacto](image-2.png)


#📊 Factores Clave en la Conversión

| Variable | Interpretación |
|----------|---------------|
| **duration** (Duración de la llamada) | 551.6 seg (~9.2 min) en promedio. Llamadas más largas están asociadas con respuestas positivas. |
| **campaign** (Número de contactos en la campaña actual) | 2.05 intentos en promedio, menor que los clientes que dijeron "no" (2.63). Insistir demasiado puede ser negativo. |
| **pdays** (Días desde el último contacto previo) | 790.5 días en promedio, con un 75% de clientes teniendo 999 (nunca antes contactados). Nuevos clientes parecen más propensos a aceptar. |
| **previous** (Cantidad de contactos anteriores) | 0.49 en promedio, la mayoría no había sido contactada antes. |
| **emp.var.rate** (Tasa de variación del empleo) | Negativa (-1.24 en promedio), lo que sugiere que más clientes aceptaron en períodos de crisis económica. |
| **Income** (Ingreso del cliente) | $92,584 en promedio, pero con una gran variabilidad. El 25% más pobre gana menos de $49,538, mientras que el 25% más rico gana más de $134,555. |
| **Kidhome y Teenhome** (Hijos en casa) | En promedio, 1 hijo pequeño y 1 adolescente en el hogar. |
| **NumWebVisitsMonth** (Visitas web mensuales) | 16.6 visitas mensuales en promedio. Clientes más digitales pueden estar más interesados en servicios bancarios. |


Tecnologías Utilizadas
Python (Pandas, NumPy, Matplotlib)
Jupyter Notebook
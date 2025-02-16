En este archivo podremos identificar los archivos con los datos facilitados, a los cuales se les realizaron ciertos procesos para su mejor comprensión y entendimiento, así mismo contestamos algunas preguntas que consideramos útiles dentro de los diferentes factores en la conversión de adquisición de productos o servicios del banco de manera positiva o negativa.

Junto con una 
-Transformación y limpieza de los datos.
-Análisis descriptivo de los datos.
-Visualización de los datos.
-Informe explicativo del análisis.

Análisis estadístico descriptivo de los datos del banco
1️-Cantidad de registros
Hay 43,000 registros en la base de datos.
2️-Datos categóricos
job (ocupación): 79 valores únicos, el más frecuente es "desconocido" (5,120 veces).
marital (estado civil): 4 valores únicos, predominando "MARRIED" con 25,999 registros.
education (educación): 8 niveles distintos, donde "university.degree" es el más común (12,722 registros).
3️-Datos numéricos
age (edad): No se ve en detalle, pero tiene 43,000 valores.
duration (duración de la llamada):
-	Media: 257.7 segundos (~4.3 min)
-	Mediana: 179 segundos (~3 min)
-	Máximo: 4,918 segundos (~82 min)
-	La desviación estándar es alta (258.7), lo que indica que hay gran variabilidad en la duración de las llamadas.
campaign (número de contactos realizados en la campaña):
-	Media: 2.57 contactos por cliente
-	Máximo: 56 contactos (probablemente un outlier).




Análisis estadístico descriptivo de los clientes
En resumen, este análisis proporciona una visión general de las características demográficas y de comportamiento de los clientes en el conjunto de datos. Los ingresos, el número de niños y adolescentes en el hogar, y las visitas web mensuales son algunas de las variables clave analizadas.
Income (Ingresos):
-	El ingreso promedio es de aproximadamente 93,227.39.
-	El ingreso mínimo es de 5,841 y el máximo es de 180,802.
-	El 25% de los individuos tiene un ingreso menor o igual a 49,608, mientras que el 75% tiene un ingreso menor o igual a 136,740.5.
Kidhome (Niños en casa):
-	El número promedio de niños en casa es de aproximadamente 1.
-	El 25% de los hogares no tiene niños, mientras que el 75% tiene 2 o menos niños.
Teenhome (Adolescentes en casa):
-	El número promedio de adolescentes en casa es de aproximadamente 1.
-	El 25% de los hogares no tiene adolescentes, mientras que el 75% tiene 2 o menos adolescentes.
Dt_Customer (Fecha de registro del cliente):
-	La fecha promedio de registro es alrededor del 11 de mayo de 2013.
-	Las fechas de registro varían desde el 1 de enero de 2012 hasta el 31 de diciembre de 2014.
NumWebVisitMonth (Número de visitas web al mes):
-	El número promedio de visitas web al mes es de aproximadamente 16.59.
-	El mínimo es 1 visita y el máximo es 32 visitas.
-	El 25% de los individuos realiza 9 o menos visitas, mientras que el 75% realiza 25 o menos visitas.






Tasa de conversión de la campaña de marketing
Calculando la columna ‘y’ (índice de si el cliente se ha suscrito a un producto o servicio (si/no), podemos darnos cuenta :
-	% de clientes suscritos = 11,2%
-	% de clientes no suscritos = 88,8%

Relación entre duración de la llamada, numero de contactos y conversión
-	Los clientes que aceptaron la oferta (yes) tuvieron llamadas significativamente más largas en promedio.
-	Esto sugiere que cuando una llamada dura más, es más probable que el cliente termine aceptando el producto.
-	Posible acción: Las campañas pueden enfocarse en mejorar la calidad de las interacciones largas en lugar de hacer muchas llamadas cortas.
y       segundos
no     220.430208 
yes    551.621387

-	Los clientes que aceptaron (yes) la oferta necesitaron menos intentos en promedio (2.05 contactos) en comparación con los que rechazaron (2.63 contactos).
-	Esto sugiere que insistir demasiado puede ser contraproducente y que los clientes que están interesados suelen aceptar en menos intentos.
-	Posible acción: Optimizar la estrategia de contacto, enfocándose en clientes con mayor interés en lugar de insistir a aquellos que no están interesados.

y       # de veces contactados
no     2.632797
yes    2.050784


 


                        Factores clave en la conversión
        Variable	                                                      Interpretación
duration (Duración de la llamada)	            551.6 seg (~9.2 min) en promedio. Llamadas más largas están asociadas con        respuestas positivas.

campaign (Número de contactos en la campaña actual)	 2.05 intentos en promedio, menor que los clientes que dijeron "no" (2.63). Insistir demasiado puede ser negativo.

pdays (Días desde el último contacto previo)    790.5 días en promedio, con un 75% de clientes teniendo 999 (nunca antes contactados). Nuevos clientes parecen más propensos a aceptar.

previous (Cantidad de contactos anteriores)	     0.49 en promedio, la mayoría no había sido contactada antes.

emp.var.rate (Tasa de variación del empleo)	     Negativa (-1.24 en promedio), lo que sugiere que más clientes aceptaron en períodos de crisis económica.

Income (Ingreso del cliente)	                 $92,584 en promedio, pero con una gran variabilidad. El 25% más pobre gana menos de $49,538, mientras que el 25% más rico gana más de $134,555.

Kidhome y Teenhome (Hijos en casa)	             En promedio, 1 hijo pequeño y 1 adolescente en el hogar.

NumWebVisitsMonth (Visitas web mensuales)	     16.6 visitas mensuales en promedio. Clientes más digitales pueden estar más interesados en servicios bancarios.


Métodos de contacto más efectivos
Después de realizar la comparativa o calculo entre los dos métodos aplicados para contactar con los clientes que fueron contacto celular (móvil) y telefónico(fijo), concluimos:
-	Que el 15% de las llamadas realizadas al celular tuvieron un resultado positivo, mientras que solo el 5% de las llamadas realizadas al teléfono tuvieron resultado positivo

Relación entre antigüedad del cliente y conversión
Aplicando una fórmula para poder calcular y entender en qué tipo de clientes según su antigüedad con el banco se está teniendo una conversión más positiva, concluimos que:
-	Los clientes que han realizado una conversión tienden a ser más "jóvenes" en términos de días desde su registro en comparación con los que no han realizado una conversión. Esto podría sugerir que los clientes más nuevos tienen más probabilidades de convertir que los clientes más antiguos.

-	Esto podría indicar que las estrategias de marketing o las condiciones del mercado son más efectivas para los clientes más recientes, o que los clientes más antiguos podrían estar menos comprometidos o interesados en las ofertas actuales.

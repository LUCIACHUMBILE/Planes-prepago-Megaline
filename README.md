# ¿Cuál es la mejor tarifa?

🚨 archivo principal: proyecto4.ipynb 🚨

Objetivo del Proyecto
El objetivo de este proyecto es realizar un análisis preliminar de las tarifas de prepago ofrecidas por Megaline, específicamente las tarifas Surf y Ultimate. El departamento comercial necesita determinar cuál de estas tarifas genera más ingresos, lo que permitirá ajustar el presupuesto de publicidad y optimizar la estrategia comercial.

Contexto
Megaline es un operador de telecomunicaciones que ofrece servicios de prepago a sus clientes. En 2018, se recopilaron datos de un grupo representativo de 500 clientes que incluyen información sobre su identificación, ubicación, tarifa utilizada, así como la cantidad de llamadas realizadas y mensajes de texto enviados.

Datos Disponibles
El análisis se basará en la siguiente información de los clientes:

Identificación del cliente
Ubicación geográfica
Tarifa de prepago (Surf o Ultimate)
Cantidad de llamadas realizadas en 2018
Cantidad de mensajes de texto enviados en 2018

# Insights:

## La duración promedio de una llamada es alrededor de 7 min, y es similar en ambos planes.

![image](https://github.com/user-attachments/assets/6fa2b844-73b3-4969-8e0f-20c1925d96e9)

## El consumo de minutos por mes del plan surf es notablemente mayor, debido a la mayor frecuencia de usuarios.

![image](https://github.com/user-attachments/assets/bc8099e0-2536-45ef-a53b-e5eeade19838)

## Los usuarios del plan surf envían mensajes con más frecuencia

![image](https://github.com/user-attachments/assets/e5ed8a2e-18c0-4b11-a739-b69cb867f17b)

## Consumo GB por plan

![image](https://github.com/user-attachments/assets/6b2599bb-fe87-4226-bdd5-7e6798a4a8c5)


## Conclusión general

El objetivo del proyecto fue analizar el comportamiento de los clientes y determinar qué tarifa de prepago genera más ingresos.
De la muestra se pudo observar lo siguiente:

La duración promedio de una llamada es alrededor de 7 min, y es similar en ambos planes
Los usuarios de plan surf envían más mensajes al mes que los usuarios del plan ultimate.
Considerando el consumo de gb de internet por usuario en cada mes, diferenciando el plan,  ambos tienen una distribución similar, sin embargo el plan surf tiene mayor frecuencia en los consumos y mayor consumo total por mes.
El comportamiento de un usuario en el consumos de minutos  por mes es similar en ambos planes. (llamadas)
Los ingresos mensuales totales generados mediante el plan surf son mayores respecto al plan ultimate.
Mediante la prueba de hipótesis realizada se concluye que hay evidencia para afirmar que las medias de los ingresos por mes de un usuario son diferentes.
Mediante la prueba de hipótesis realizada se concluye que hay evidencia para afirmar que las medias de los ingresos de la región NY-NJ-PA y el resto de regiones son diferentes.

Respecto a la limpieza y enrequecimiento de datos, se verificó valores nulos y duplicados,se cambió tipo de datos a datetime para que permitiera extraer el mes y agrupar correctamente la información, además se reviso y agrego  unidades para el cáculo de los ingresos, caso contrario el cálculo de ingresos podría variar.
Para la prueba de hipótesis se utilizó t student para comparar medias, y var= False ya que tenían varianzas diferentes.

Es importante conocer el comportamiento de cada usuario respecto a la necesidad de característica de cada plan, de esta forma ofrecerlo de tal forma que les favorezca.


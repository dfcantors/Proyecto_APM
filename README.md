# Propuesta de automatización para la industria cerámica - Chía Dynamics :factory:
![Chia Dynamics (3)](https://github.com/dfcantors/Proyecto_APM/assets/82415576/4d8c8762-f4c8-48ab-99b0-9d2236f686b9)

## Objetivos

## Contextualización del proyecto

## 1.1 Gestión de producción

## 1.1.1 Análisis de la planta

#### Planta previo a la automatización

En el siguiente enlace se puede observar el estado de la planta de fabricación previo a la automatización.

https://youtu.be/nwjF0O8n1nA

#### Planta automatizada

En el siguente enlace se podrá encontrar el video de la simulación de la planta de fabricación como primer avance.

https://youtu.be/z5MI-h-2oKE

Como resultado de la simulación se obtiene la siguiente gráfica de eficiencia 

![alt text](image-1.png)

<<<<<<< HEAD


### 1.1.2.1.3 KPI's Planteados
=======
#### 1.1.2.1.3 KPI's Planteados
>>>>>>> 6623e97d0244e6729959acd621fbb34b795e559f
La información correspondiente se encuentra dentro de la carpeta:
<br>
        1.1 [Gestión de Producción](https://github.com/dfcantors/Proyecto_APM/tree/main/1.%20Seccion%20de%20Producto/1.1.%20Gestion%20de%20Produccion)

#### 1.1.2.1 VSM pre automatizado
  Se realizaron  2 VSM para el proceso pre automatización y automatizado, como se ven en las siguientes figuras:
  ![image](https://github.com/dfcantors/Proyecto_APM/blob/main/1.%20Seccion%20de%20Producto/1.1.%20Gestion%20de%20Produccion/1.1.2.2.1.%20VSM%20pre-automatización.png)

#### 1.1.2.2 VSM pre automatizado
  ![image](https://github.com/dfcantors/Proyecto_APM/blob/main/1.%20Seccion%20de%20Producto/1.1.%20Gestion%20de%20Produccion/1.1.2.2.2.%20VSM%20pos-automatización.png)

  Las etapas a automatizar se asumieron que se realizan por personal



## 1.2 Módulo de industria 4.0

### 1.2.1 Propuesta de Arquitectura de Red

Como propuesta de arquitectura de red se pretende hacer una integración con las herramientas vistas en clase, para la celda robotizada se tiene una propuesta que conecta toda la suite de ABB para el control del robot así como la conexión a NX para los demás sensores y actuadoes.

Las líneas rojas representan los protocolos de comunicación estándar, tales como análogo por corriente o voltaje, RS232 y MODBUS. Que suelen ser los protocolos utilizados por los sensores comunmente.

En la etapa superior se propone un protocolo de comunicación TCP/IP, protocolo que puede implementarse para conectar sistemas de alto nivel a la nube y demás interfaces en tiempo real.

![Diagrama de red-Página-1](https://github.com/dfcantors/Proyecto_APM/assets/51063831/fa50e89b-f4bf-45d0-9401-13e3ba98b44f)

Para los demás sistemas en los que no se implementarán celdas robotizadas el cambio radica en la ausencia del controlador robótico, la integración será similar y la agrupación de PLC's se dividirá de la siguiente manera:

![Diagrama de red-Página-3](https://github.com/dfcantors/Proyecto_APM/assets/51063831/6665e4f5-1fd4-45d6-9d08-94c6b3611c3d)

### 1.2.2 Implementación de IoT

- Información de estado de procesos (inicio y fin) a los supervisores de sección.
- Envío de datos de falla a los supervisores y trabajadores de sección.
- Reanudar y pausar los procesos de manera remota.
- Registro central de los estados de los procesos.



## 1.3. Planeación del Proyecto (7 Pasos y Cronograma)
### EDT
![image](https://github.com/dfcantors/Proyecto_APM/assets/82415576/fae0568f-3207-43e5-95a1-0bb6bb61e4cb)
### Adquisiciones
![image](https://github.com/dfcantors/Proyecto_APM/assets/82415576/4d1bf957-31d1-4d04-a3e4-e632fc9817ac)
### Costo y Tiempos
![image](https://github.com/dfcantors/Proyecto_APM/assets/82415576/faabf7e8-9550-4612-a282-fa2c23c06098)
### Riesgos
![image](https://github.com/dfcantors/Proyecto_APM/assets/82415576/742736bd-3dc1-471a-b2ba-27741c3ef9c3)
### Stakeholders
![image](https://github.com/dfcantors/Proyecto_APM/assets/82415576/b917c409-9bb9-4b9b-a19a-fa85ac14ea3b)
### Matriz de Comunicaciones
![image](https://github.com/dfcantors/Proyecto_APM/assets/82415576/3f99db54-fbb3-424d-a4e8-377516b981f4)
### RACI
![image](https://github.com/dfcantors/Proyecto_APM/assets/82415576/13c69598-0434-48d8-9823-c905c539a79c)
### Cronograma Gantt
![image](https://github.com/dfcantors/Proyecto_APM/assets/83465309/a46352c6-846e-4887-8761-d30230babd30)

## 1.4 Evaluación económica del proyecto

## Business Model Canvas

Inicialmente se propone el siguiene Business Model Canvas para la empresa que constituimos para el proyecto:
![Business Model Canvas drawio](https://github.com/dfcantors/Proyecto_APM/assets/51063831/4c971e23-9043-4a2b-880d-9d04d4d4dff8)

### 1.4.1.	Excel con indicadores financieros completado.
![image](https://github.com/dfcantors/Proyecto_APM/blob/main/1.%20Seccion%20de%20Producto/1.4.%20Evaluacion%20Economica/1.4.1%20Excel.png)

### 1.4.1.1.	 VPN calculado.
![image](https://github.com/dfcantors/Proyecto_APM/blob/main/1.%20Seccion%20de%20Producto/1.4.%20Evaluacion%20Economica/1.4.1.1%20VPN.png)

### 1.4.1.2.	 TIR calculada.
![image](https://github.com/dfcantors/Proyecto_APM/blob/main/1.%20Seccion%20de%20Producto/1.4.%20Evaluacion%20Economica/1.4.1.2%20TIR.png)

### 1.4.1.3.	 Payback calculado.
![image](https://github.com/dfcantors/Proyecto_APM/blob/main/1.%20Seccion%20de%20Producto/1.4.%20Evaluacion%20Economica/1.4.1.3%20Payback.png)

### 1.4.2.	Oferta comercial escrita.

El proyecto no generará ganancias durante los primeros cuatro meses de operación. Durante este tiempo se llevarán a cabo modificaciones, se contratarán y pagarán los salarios de los ingenieros encargados y se iniciará la infraestructura requerida. Se espera que la planta esté paralizada durante los meses 3 y 4, lo que aumentará las pérdidas de producción.

El proyecto tiene un costo de inversión estimado de $1.137.039.852 COP, que incluye gastos de interrupción de producción, maquinaria, robots, servicios y software, entre otros.

Sin embargo, los indicadores financieros indican que el proyecto es viable a pesar de estos obstáculos iniciales, con un Valor Actual Neto (VAN) de $390.077.121 respecto a la inversión total y una Tasa Interna de Retorno (TIR) del 11%. Además, se estima que el período de recuperación de la inversión (payback) durará 19 meses, generando más de $1.160.000.000 en ingresos.

## Primera propuesta en NX con Layout provisional
Inicialmente se tiene un layout funcional en simulación con el fin de probar cada parte del plan de automatización desarrollado en cada máquina, es por esta razón que se tiene un ejemplar de cada sistema, una vez definida la producción individual por máquina se hará el ajuste numérico.
La planta cuenta con las siguientes máquinas:
-Silo con la mezcla ya preparada
-Prensa
-Secadora
-Horno
-Qualitron
-Apiladora de baldosas / empaquetadora

Siendo estos los sistemas en los cuales está más enfocada la propuesta de automatización.
Paulatinamente se agregarán los sistemas restantes como el barnizado y el embalaje final para envío, así como la conexión con el PLC y su control.

![Primera version planta](https://github.com/dfcantors/Proyecto_APM/assets/51063831/801da997-c34b-4679-9dc3-79cd4f020379)



## Partes del proceso que serán automatizadas

## Propuesta inicial de automatización
Se seleccionaron la impresion de patrones, el proceso de calidad del producto y el embalaje como los procesos a automatizar. Luego de investigar respecto a soluciones similares en la industria, se llegaorn a las siguientes conclusiones:
#### Impresion de patrones
 Implentacion de máquina impresora de patrones, se pidió cotización pero aun se espera respuesta, por lo que las maquinas entre las opciones a elegir son:
 - https://www.systemceramics.com/es/maquinas-para-ceramica/control-de-calidad/qualitron
 - https://sacmi.com/en-us/ceramics/Tiles/Sorting,-packing-and-pallettizing
 - https://www.iris-im.com/complete-inspection-line/

#### Calidad del producto
Para la etapa de calidad se busca implementar en la linea de producción un Qualitron. Nuevamente debido a que no han llegado las cotizaciones y no todas las caracteristicas de las máquinas pueden hallarse, entre las posibles opciones se tienen:
 - https://www.efi.com/products/industrial-printing/ceramics/efi-cretaprint-printers/
 - https://kerajet.com/es/soluciones-para-ceramica/
 - https://www.systemceramics.com/es/maquinas-para-ceramica/decoracion/creadigit 
#### Embalaje de cajas

El proceso de embalaje de cajas se dividirá en 3 fases distintas. Esto contemplara el proceso desde el armado de la caja y su la disposición de las baldosas hasta su cobertura de vinipel:

-Doblado y posicionamiento de las baldosas: Las baldosas serán posicionadas previamente en grupos de a 5 las cuales entrarán a una empaquetadora que cumple la doble tarea de plegar la caja a la vez que las baldosas quedan correctamente colocadas en su interior.
- Posicionamiento de las cajas: Las cajas se ubican de acuerdo con la distribución definida para el transporte de las baldosas esta tarea será realizada por un sistema robotizado para reducir tiempos. 
- Embalaje del conjunto de cajas: Una máquina pondrá finalmente el vinipel para mantener fijas las cajas y protegerlas para el transporte.
 

### Robots propuestos para cada parte del proceso

## 1.5.4 Análisis de riesgo y peligros
La información correspondiente se encuentra dentro de la carpeta:
<br>
        1.5 [Contenido de módulo de celda de manufactura robotizada completado](https://github.com/dfcantors/Proyecto_APM/tree/main/1.%20Seccion%20de%20Producto/1.5.%20Celda%20Robotizada)
        
## 1.7 Contenido de módulo de controladores industriales completado.
[Sensores y Equipos de Seguridad](https://github.com/dfcantors/Proyecto_APM/blob/main/1.%20Seccion%20de%20Producto/1.7.%20Controladores%20Industriales/Sensores%20%20Industriales%20y%20Elementos%20de%20Seguridad.md)\
[GRAFCET](https://github.com/dfcantors/Proyecto_APM/blob/main/1.%20Seccion%20de%20Producto/1.7.%20Controladores%20Industriales/GRAFCET.pdf)

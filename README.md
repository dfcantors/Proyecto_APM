# Propuesta de automatización para la industria cerámica - Chía Dynamics :factory:
![Chia Dynamics (3)](https://github.com/dfcantors/Proyecto_APM/assets/82415576/4d8c8762-f4c8-48ab-99b0-9d2236f686b9)

## Objetivos

## Contextualización del proyecto

## 1.1.2.1.3 KPI's Planteados
La información correspondiente se encuentra dentro de la carpeta:
<br>
        1.1 [Gestión de Producción](https://github.com/dfcantors/Proyecto_APM/tree/main/1.%20Seccion%20de%20Producto/1.1.%20Gestion%20de%20Produccion)

## 1.1.2.1 VSM pre automatizado
  Se realizaron  2 VSM para el proceso pre automatización y automatizado, como se ven en las siguientes figuras:
  ![image](https://github.com/dfcantors/Proyecto_APM/blob/main/1.%20Seccion%20de%20Producto/1.1.%20Gestion%20de%20Produccion/1.1.2.2.1.%20VSM%20pre-automatización.png)

## 1.1.2.2 VSM pre automatizado
  ![image](https://github.com/dfcantors/Proyecto_APM/blob/main/1.%20Seccion%20de%20Producto/1.1.%20Gestion%20de%20Produccion/1.1.2.2.2.%20VSM%20pos-automatización.png)

  Las etapas a automatizar se asumieron que se realizan por personal



## 1.2 Módulo de industria 4.0

## 1.2.1 Propuesta de Arquitectura de Red

Como propuesta de arquitectura de red se pretende hacer una integración con las herramientas vistas en clase, para la celda robotizada se tiene una propuesta que conecta toda la suite de ABB para el control del robot así como la conexión a NX para los demás sensores y actuadoes.

Las líneas rojas representan los protocolos de comunicación estándar, tales como análogo por corriente o voltaje, RS232 y MODBUS. Que suelen ser los protocolos utilizados por los sensores comunmente.

En la etapa superior se propone un protocolo de comunicación TCP/IP, protocolo que puede implementarse para conectar sistemas de alto nivel a la nube y demás interfaces en tiempo real.

![Diagrama de red-Página-1](https://github.com/dfcantors/Proyecto_APM/assets/51063831/fa50e89b-f4bf-45d0-9401-13e3ba98b44f)

Para los demás sistemas en los que no se implementarán celdas robotizadas el cambio radica en la ausencia del controlador robótico, la integración será similar y la agrupación de PLC's se dividirá de la siguiente manera:

![Diagrama de red-Página-3](https://github.com/dfcantors/Proyecto_APM/assets/51063831/6665e4f5-1fd4-45d6-9d08-94c6b3611c3d)

## 1.2.2 Implementación de IoT

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

## Primera propuesta de layout

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

El proceso de embalaje de cajas se dividirá en 5 fases distintas. Esto contemplara el proceso desde el armado de la caja y la deposición de las baldosas en su imterior hasta el posicionamiento de las cajas y su cobertura de vinipel:

- Doblado inicial de la caja: En esta etapa partimos de la caja desarmada completamente y a través de una máquina le daremos el formado respectivo para poner posteriormente las lozas.
- Posicionamiento de las cerámicas dentro de la caja: Una vez armada la caja se dispondrá de un brazo que posicionará doce baldosas en cada caja mientras se mueven por una línea transportadora.

![WhatsApp Image 2024-04-23 at 3 08 32 PM](https://github.com/dfcantors/Proyecto_APM/assets/51063831/40bb5654-509c-41a8-a91d-ee6f792a28dc)

En este momento se están esperando las cotizaciones por parte de los proveedores, inicialmente se tienen las siguientes propuestas de robot que podrían cumplir con la tarea especificada:

![Captura de pantalla 2024-04-23 210805](https://github.com/dfcantors/Proyecto_APM/assets/51063831/a8f6d38b-f9e5-4dd8-8582-abe6ce4febed)


- Cierre de la caja: En esta etapa se dispondrá de una máquina que pondrá pegamento doblará los bordes restantes para el sellado de la caja con el fin de terminar el producto que se enviará.
- Posicionamiento de las cajas: Las cajas se ubican de acuerdo con la distribución definida para el transporte de las baldosas.
- Embalaje del conjunto de cajas: Una máquina pondrá finalmente el vinipel para mantener fijas las cajas y protegerlas para el transporte.
 

### Robots propuestos para cada parte del proceso

## 1.5.4 Análisis de riesgo y peligros
La información correspondiente se encuentra dentro de la carpeta:
<br>
        1.5 [Contenido de módulo de celda de manufactura robotizada completado](https://github.com/dfcantors/Proyecto_APM/tree/main/1.%20Seccion%20de%20Producto/1.5.%20Celda%20Robotizada)
        
        

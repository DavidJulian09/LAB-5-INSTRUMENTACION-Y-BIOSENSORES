# LAB 5: RECONOCIMIENTO DE PARTES Y FUNCIONAMIENTO DE UNA MÁQUINA DE ANESTESIA

## I. INTRODUCCIÓN

En el presente documento, se hablará sobre las máquinas de anestesia, las cuales su función principal es mantener las funciones vitales del paciente en un estado equilibrado y estable de inconsciencia controlada, cumpiendo las labores de proporcionar oxígeno y ventilación alpaciente, además de mezclar diferentes gases anestésicos en las dosis adecuadas. A pesar de lo fundamental de sus funciones, y de los posibles riesgos que puede simbolizar al paciente un error en la máquina y del operador, no se trata de un dispositivo complejo u hostil, sino se trata de un conjunto de tuberías y sistemas de bombeo quesuministran una mezcla de gases de forma cuidadosamente controlada y de fácil uso y mantenimiento bajo la capacitación adecuada. [1]

Con esta práctica, nosotros como ingenieros biomédicos, podremos familiarizarnos con uno de los equipos de mayor aplicación en entornos quirúrgicos, desmitificando su aparente complejidad y reconociendo la importancia de cada uno de sus subsistemas. Todo lo anterior mediante el desarrollo de los siguientes objetivos:

### Objetivo general:

Familiarizarnos con los componentes, funcionamiento y labores de mantenimiento de una máquina de anestesia.

### Objetivos específicos:

• Identificar las partes principales de una máquina de anestesia WATO EX20.

• Comprender el funcionamiento y modos de operación de una máquina de anestesia.

• Reconocer la relevancia de las labores de mantenimiento aplicadas a una máquina de anestesia.

## II. ASPECTOS FUNDAMENTALES MÁQUINA DE ANESTESIA (PARTE A)

### a) Tipos de anestesia aplicados durante una cirugía

Los tipos de antesia se clasifican en tres categorías, según que tantto se desea afectar al sistema nervioso central y la zona del organismo afectada, los cuales son:

#### 1. Anestesia general:

Este tipo de anaestesia provoca un estado de inconsciencia controlada, amnesia, analgesia y relajación muscular; se administra por vía intravenosa  o por inhalación (agentes volátiles mezclados con O₂, N₂O o aire). En el modelo de WATO EX-20, está diseñada específicamente para administrar anestesia general inhalatoria, mezclando los gases medicinales (O₂, N₂O, aire) y agentes anestésicos volátiles a través del vaporizador y suministra la mezcla al paciente mediante un sistema de respiración.

#### 2. Anestesia regional: 

Para ese segundo tipo, se realiza un bloqueo reversible de la conducción nerviosa en una región específica del cuerpo, como en la zona espinal o epidural por ejemplo; adicionalmete el paciente permanece puede permanecer consciente o sedado. Respecto a la aplicación en el modelo WATO EX-20, no se utiliza directamente para administrar anestesia regional, pero puede emplearse para proporcionar sedación complementaria con O₂ o agentes volátiles a bajas concentraciones durante el procedimiento, así como para monitorizar la ventilación si la sedación es profunda.

#### 3. Anestesia local:

Esta anestesia es la eliminación temporal de la sensibilidad en una pequeña zona mediante infiltración de anestésico local, este tipo de anestesia no se puede controlar con el modelo que poseemos, aunque puede llegar a suministrar O₂ suplementario de ser requerido.

### b) Gases trabajados por la máquina de anestesia

Los gases medicinales con los que se trabaja, y que además se incorporan mediante un sistema de alta presión, son descritos en el manual de servivicio, y son especificados en las secciones 2.1.6.1 "Gas Supplies" y 2.1.6.2 "Anesthetic Gas Delivery System", los cuales son:

#### 1. Oxígeno (O₂):

Su función principal es de sevir como gas de trabajo, garantizando la oxigenación del paciente durante el proceso de anestesia; a su vez, actúa como gas impulsor (drive gas) en el ventilador neumático permitiendo su movimiento.

#### 2. Óxido nitroso (N₂O):

Este gas es el encargado de realizar el proceso de anestesia y coadyuvante anestésico, pues reduce la concentración de anestésico volátil necesario. Suele ser usado en conjunto con el O₂, y su suministro se corta automáticamente si la presión de O₂ desciende por debajo de 0.1 MPa (válvula de corte O₂‑N₂O)

#### 3. Aire medicinal (Air):

Funciona como diluyente de gases para disminuir o aumentar la consentración de agente analgésico según se requiera; al igual que el O₂ también actúa como gas impulsor (drive gas). Este gas es especialmente útil cuando el suministroo de O₂ es limitado o cuando no hay tolerancia por parte del paciente al O₂.

<img width="1204" height="1600" alt="image" src="https://github.com/user-attachments/assets/d9c4ba7d-a281-4327-8b39-056912897979" />

_(Fig 1. Suministro de gases médicos WATO EX-20.)_

Cabe mencionar que los gases anteriores necesitan de un sistema de alta presión pues ingresan a la máquina por medio de cilindros, estos cilindros se conectan a través de uniones de horquilla (yoke) con válvulas antirretorno y filtros, luego los gases pasan por un regulador que reduce la presión a aproximadamente a 400kPa y posteriormente a 200kPa. La presión que pueden poseer estos gases antes de pasar por el regulador varian, por ejemplo el O₂ y el aire pueden poseer una presión de entre 6.9 – 15MPa, en cambio el N₂O es significativamente menor con valores de 4.2 – 6MPa.

Además de los gases ya mencionados, la máquina incorpora agentes anestésicos volátiles (sevoflurano, isoflurano, desflurano...) que se evaporan en el vaporizador, estos que se evaporan en el vaporizador.

### c) Sistema de respiración y su función

El sistema de respiración se describe en la sección 2.1.6.4 del manual de servivicio, indicando: "El sistema respiratorio proporciona un circuito cerrado para el gas anestésico. El CO₂ presente en el aire espirado del paciente puede ser inhalado durante la fase de inspiración para mantener la temperatura y la humedad del aire espirado".

<img width="600" height="461" alt="image" src="https://github.com/user-attachments/assets/8f8ce41b-2114-4ceb-9dc9-19ce37ab1371" />

_(Fig 2. Diagrama sistema de respiración.) [Manual Service]_

Es decir, conduce los gases anestésicos desde la máquina de anestesia hasta el paciente y viceversa; elimina el dióxido de carbono (CO₂) exhalado mediante un absorbente de CO₂ (cal sodada – CO₂ absorbent canister); también permite la re‑inhalación de gases (con CO₂ eliminado) para conservar calor y humedad, reduciendo la pérdida de agua insensible y el consumo de agentes anestésicos. Por último, cabe resaltar que dispone de dos modos de ventilación: manual (con bolsa reservorio y válvula APL) y mecánica (con fuelle y ventilador neumático).


<img width="261" height="240" alt="image" src="https://github.com/user-attachments/assets/c03ddca7-c0ba-4917-835c-6f9384ee60e1" />

_(Fig 3. cal sodada – CO₂ absorbent canister.) [Manual Service]_

<img width="1204" height="1600" alt="image" src="https://github.com/user-attachments/assets/64f283c7-602a-47a2-814f-8de8590aa966" />

_(Fig 4. Válvula APL y fuelle sistema de respiración.)_

#### Partes esterilizables en autoclave:

La esterilización por autoclave es un método que utiliza vapor de agua saturado a alta presión, con el fin de eliminar microorganizmosy esporas en la instrumentación; el propio manual indica que todo el sistema de respiración puede ser desmontado y esterilizado en autoclave a 134 °C, por tanto se incluye:

• Canister de CO₂ (absorbente y su recipiente)

• Válvulas inspiratoria y espiratoria (check valves)

• Fuelle (bellows) – ver página 6‑42 (desmontaje)

• Bolsa manual (manual bag)

• Tubuladuras del paciente (breathing tubes) y pieza en Y

• Válvula APL (desmontable, página 6‑56)

• Cuerpo del circuito adaptador (circuit adapter), excepto componentes eléctricos

### d) Submenús del ventilador

El ventilador neumático del WATO EX-20 es un componente controlado por microprocesador que ofrece múltiples modos y parámetros ajustables, estos se controlan desde la interfaz de usuario donde se se puede acceder a cada uno de ellos, y que se describen a continuación:

#### 1. Modos de ventilación:

La ventilación  neumática es un aspecto fundamental en las máquinas de anestesia, pues es la encargada de garantizar las respiraciones de los pacientes cuando se encuentran en un determinado nivel de sedación, sus patologías pulmonares y esfuerzo respiratorio; dependiendo de la profundidad de dichos estados se requieren multitud de modos que se presentan a continuación:

• VCV (Volume Control Ventilation): se entrega un volumen tidal preestablecido independiente de la presión, en donde se debe realizar un monitoreo constante de este último. En este modo puede llevarse a cabo asincronías entre el paciente y el ventilador e inclusive, se dificuta el intercambio gaseoso.

<img width="361" height="243" alt="image" src="https://github.com/user-attachments/assets/b99dfd1e-06e0-44a5-b4bc-cd981df76af4" />

_(Fig 5. Ventilación VCV.)_

• PCV (Pressure Control Ventilation): se limita (controla) la presión inspiratoria, y el volumen resultante es dependiente de la presión y la complianza (capacidad de expansión) del paciente. En este modo hay un mejor intercambio gaseoso pero hay un alto riesgo de volutrauma si la distensibilidad mejora repentinamente.

<img width="298" height="257" alt="image" src="https://github.com/user-attachments/assets/66e24c8a-1037-454f-8930-ef24f6a79a34" />

_(Fig 6. Ventilación PCV.)_

• PSV (Pressure Support Ventilation): en este modo, es el paciente quien dispara la inspiración, y el ventilador únicamente mantiene una presión de soporte para facilitar dichs inspiraciones.

• SIMV (Synchronized Intermittent Mandatory Ventilation): este modo permite incluir los dos modos de ventilación, mandatorias con esontáneas, es decir, cumple el rol de establecer el patrón respiratorio pero con la capacidad de permitir al paciente de realizar respiraciones espontáneas.

<img width="250" height="182" alt="image" src="https://github.com/user-attachments/assets/1bb71b56-2ead-4217-b655-9f57d579ecd3" />

_(Fig 7. Ventilación SIMV.)_

#### 2. Volumen corriente (TV) y presión límite (Plimit)

Estos modos del ventilador permiten ajustar los parámetros con los que se trabajará en los modos de ventilación. 






























# LAB 5: RECONOCIMIENTO DE PARTES Y FUNCIONAMIENTO DE UNA MÁQUINA DE ANESTESIA

## I. INTRODUCCIÓN

En el presente documento, se hablará sobre las máquinas de anestesia, las cuales su función principal es mantener las funciones vitales del paciente en un estado equilibrado y estable de inconsciencia controlada, cumpiendo las labores de proporcionar oxígeno y ventilación alpaciente, además de mezclar diferentes gases anestésicos en las dosis adecuadas. A pesar de lo fundamental de sus funciones, y de los posibles riesgos que puede simbolizar al paciente un error en la máquina y del operador, no se trata de un dispositivo complejo u hostil, sino se trata de un conjunto de tuberías y sistemas de bombeo quesuministran una mezcla de gases de forma cuidadosamente controlada y de fácil uso y mantenimiento bajo la capacitación adecuada. [1]

Con esta práctica, nosotros como ingenieros biomédicos, podremos familiarizarnos con uno de los equipos de mayor aplicación en entornos quirúrgicos, desmitificando su aparente complejidad y reconociendo la importancia de cada uno de sus subsistemas. Todo lo anterior mediante el desarrollo de los siguientes objetivos [1]:

### Objetivo general:

Familiarizarnos con los componentes, funcionamiento y labores de mantenimiento de una máquina de anestesia.

### Objetivos específicos:

• Identificar las partes principales de una máquina de anestesia WATO EX20.

• Comprender el funcionamiento y modos de operación de una máquina de anestesia.

• Reconocer la relevancia de las labores de mantenimiento aplicadas a una máquina de anestesia.

## II. ASPECTOS FUNDAMENTALES WATO EX-20 (PARTE A)

### A) Tipos de anestesia aplicados durante una cirugía

Los tipos de antesia se clasifican en tres categorías, según que tantto se desea afectar al sistema nervioso central y la zona del organismo afectada, los cuales son [2]:

#### 1. Anestesia general:

Este tipo de anaestesia provoca un estado de inconsciencia controlada, amnesia, analgesia y relajación muscular; se administra por vía intravenosa  o por inhalación (agentes volátiles mezclados con O₂, N₂O o aire). En el modelo de WATO EX-20, está diseñada específicamente para administrar anestesia general inhalatoria, mezclando los gases medicinales (O₂, N₂O, aire) y agentes anestésicos volátiles a través del vaporizador y suministra la mezcla al paciente mediante un sistema de respiración.

#### 2. Anestesia regional: 

Para ese segundo tipo, se realiza un bloqueo reversible de la conducción nerviosa en una región específica del cuerpo, como en la zona espinal o epidural por ejemplo; adicionalmete el paciente permanece puede permanecer consciente o sedado. Respecto a la aplicación en el modelo WATO EX-20, no se utiliza directamente para administrar anestesia regional, pero puede emplearse para proporcionar sedación complementaria con O₂ o agentes volátiles a bajas concentraciones durante el procedimiento, así como para monitorizar la ventilación si la sedación es profunda.

#### 3. Anestesia local:

Esta anestesia es la eliminación temporal de la sensibilidad en una pequeña zona mediante infiltración de anestésico local, este tipo de anestesia no se puede controlar con el modelo que poseemos, aunque puede llegar a suministrar O₂ suplementario de ser requerido.

### B) Gases trabajados por la máquina de anestesia

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

### C) Sistema de respiración y su función

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

### D) Submenús del ventilador

El ventilador neumático del WATO EX-20 es un componente controlado por microprocesador que ofrece múltiples modos y parámetros ajustables, estos se controlan desde la interfaz de usuario donde se se puede acceder a cada uno de ellos, y que se describen a continuación:

#### 1. Menú de ventilación:

La ventilación  neumática es un aspecto fundamental en las máquinas de anestesia, pues es la encargada de garantizar las respiraciones de los pacientes cuando se encuentran en un determinado nivel de sedación, sus patologías pulmonares y esfuerzo respiratorio; dependiendo de la profundidad de dichos estados se requieren multitud de modos que se presentan a continuación [3]:

• VCV (Volume Control Ventilation): se entrega un volumen tidal preestablecido independiente de la presión, en donde se debe realizar un monitoreo constante de este último. En este modo puede llevarse a cabo asincronías entre el paciente y el ventilador e inclusive, se dificuta el intercambio gaseoso.

<img width="361" height="243" alt="image" src="https://github.com/user-attachments/assets/b99dfd1e-06e0-44a5-b4bc-cd981df76af4" />

_(Fig 5. Ventilación VCV.) [3]_

• PCV (Pressure Control Ventilation): se limita (controla) la presión inspiratoria, y el volumen resultante es dependiente de la presión y la complianza (capacidad de expansión) del paciente. En este modo hay un mejor intercambio gaseoso pero hay un alto riesgo de volutrauma si la distensibilidad mejora repentinamente.

<img width="298" height="257" alt="image" src="https://github.com/user-attachments/assets/66e24c8a-1037-454f-8930-ef24f6a79a34" />

_(Fig 6. Ventilación PCV.) [3]_

• PSV (Pressure Support Ventilation): en este modo, es el paciente quien dispara la inspiración, y el ventilador únicamente mantiene una presión de soporte para facilitar dichs inspiraciones.

• SIMV (Synchronized Intermittent Mandatory Ventilation): este modo permite incluir los dos modos de ventilación, mandatorias con esontáneas, es decir, cumple el rol de establecer el patrón respiratorio pero con la capacidad de permitir al paciente de realizar respiraciones espontáneas.

<img width="250" height="182" alt="image" src="https://github.com/user-attachments/assets/1bb71b56-2ead-4217-b655-9f57d579ecd3" />

_(Fig 7. Ventilación SIMV.) [3]_

#### 2. Menús control volumen corriente (TV) y presión límite (Plimit):

Estos submenus del ventilador permiten ajustar los parámetros con los que se trabajará en los modos de ventilación. El modo de volumen corriente o tidal volume (TV), corresponde al volumen de gas que se introduce en los pulmones del paciente en cada respiración (en modo VCV o PCV), este parámetro permite tener un rango ajustable de entre 20 - 1500ml; en este ajuste se garantiza una ventilación alveolar adecuada, un volumen demasiado bajo produce hipoventilación y atelectasias; uno demasiado alto puede causar barotrauma o volutrauma.

Respecto al control de la presión límite, corresponde al control de la presión máxima de la vía aérea (Paw) que el ventilador permite durante la inspiración. Si la presión supera este valor, se activa una alarma y se abre una válvula de seguridad para liberar presión; el equipo permite el ajuste de valores entre 10 – 80 cmH₂O, con el fin de proteger los pulmones del paciente de presiones dañinas (barotrauma)

#### 3. Menús control frecuencia respiratoria, relación inspiración:espiración y pausa inspiratoria:

• Frecuencia respiratoria: el equipo a su vez posee un menú para el ajuste del proceso respiratorio del paciente, el cual permite establecer el número de ciclo respiratorios por minuto (BPM), el cual permite establecer un rango entre 4-60BPM (en adultos) y hasta 100 BPM en neonatos. Este control a su vez nos permite determinar el volumen tidal, y define la ventilación minuto.

• Relación inspiración:espiración: corresponde a la proporción entre la duración de la fase inspiratoria y la duración de la fase espiratoria, este valor se muestra como un cociente, ejemplo, 1:2 significa que la espiración dura el doble que la inspiración. La función de este menú es optimizar el intercambio gaseoso y evitar la retención de CO₂, Una relación I:E muy alta (inspiración larga) puede causar auto‑PEEP; muy baja (espiración muy larga) puede reducir la ventilación minuto. El rango de control es desde 1:4 (espiración muy larga) hasta 2:1 (inspiración invertida).

• Pausa inspiratoria (TIP:TI): este como tal es un submenú dentro del menú del control del ventilación, más en específico de los modos PCV, PSV y SIMV; se encarga de dar un tiempo adicional sin flujo de gas al final de la inspiración, durante el cual la vía aérea permanece cerrada, este parámetro define la relación entre el tiempo de pausa y el tiempo inspiratorio total. Lo anterior permite facilitar la medición de la compliance estática y la eficacia del intercambio gaseoso en algunas patologías. Para su ajuste se entra al submenú TIP:TI y se cambia el valor de “OFF” a un porcentaje deseado (10% , 20% del tiempo inspiratorio).


## III. IDENTIFICACIÓN DE COMPONENTES, PROCEDIMIENTOS Y MANTENIMIENTO WATO EX-20

### A) Identificación y función de partes

#### 1. Vaporizador: 

Este elemento se monta sobre el múltiple del vaporizador situado en la parte superior frontal de la máquina, debajo de la cubierta; su función es la de convertir el agente anestésico líquido en vapor que se mezcla con el flujo de gases frescos (O₂, N₂O, aire) que proviene del sistema de suministro de forma precisa y controlada. Según el manual (página 2‑31), se indica que el colector de vaporizador integra una válvula antirretorno para evitar que el O₂ o los gases retornen al vaporizador, alterando la concentración suministrada.

<img width="1204" height="1600" alt="image" src="https://github.com/user-attachments/assets/711e85a6-fd87-4203-9824-d3586835e900" />

_(Fig 8. Ubicación vaporizador.)_

<img width="217" height="131" alt="image" src="https://github.com/user-attachments/assets/72a4d887-6bf4-4d4a-b62e-0bc64fad6c1f" />

_(Fig 9. Vaporizador conectado.) [Manual service]_

#### 2. Válvula APL (Adjustable Pressure Limiting valve):

La válvula APL se localiza en el sistema de respiración, específicamente en el circuito manual. Se puede identificar como un mando giratorio con una escala de presión (en cmH₂O) situado en la parte frontal del sistema de respiración, tal como se observa en la figura 10. La función de esta válvula es durante la ventilación manual, la válvula APL limita la presión máxima que alcanza el circuito cuando se aprieta la bolsa manual; permite ajustar un umbral de presión, por ejemplo de 0 a 75 cmH₂O, si la presión supera el valor fijado la válvula se abre liberando el exceso de gas al exterior o al sistema de evacuación de gases anestésicos. Gracias a lo anterior se protege los pulmones del paciente de presiones excesivas durante la ventilación manual.

<img width="1204" height="1600" alt="image" src="https://github.com/user-attachments/assets/6325c000-4283-4967-9cfe-5f0d45398431" />

_(Fig 10. Ubicación valvula APL.)_


#### 3. Recipiente absorbente de CO₂ (CO₂ absorbent canister)

El recipiente absorbente de CO₂ se encuentra dentro del sistema de respiración, en la parte inferior del circuito debajo del fuelle como se muestra en la figura 11; se accede a el girándolo. La función de este recipiente es contener la cal-sodada, la cual absorbe el dióxido de carbono (CO₂) del gas exhalado por el paciente; de esta forma, el gas puede ser reinhalado sin peligroso y a su vez conservando calor y hummedad, esta cal sodada se puede observar en la figura 3 de la sección II.c.

<img width="1204" height="1600" alt="image" src="https://github.com/user-attachments/assets/4beca655-b90f-491c-a21e-2fe280562ad1" />

_(Fig 11. Ubicación Recipiente absorbente de CO₂.)_

#### 4. Fuelle:

El fuelle forma parte del sistema de respiración y se aloja dentro de una carcasa transparente situada en la parte frontal del circuito (se puede observar en la figura 10), la cual se puede desmontar girando en sentido antihorario. este es el elemento que separa el gas impulsor del gas que respira el paciente, cuando  el ventilador envía gas impulsor hacia la carcasa del fuelle, este se comprime y empuja el gas anestésico contenido en su interior hacia el paciente (inspiración); durante la espiración, el fuelle se reexpande al permitir la salida del gas exhalado. Finalmente, cabe resaltar que el fuelle es de un material libre de latex y no alergénico, que puede manejar un volumen de 1500ml para el control adecuado de ventilación. 

<img width="1204" height="1600" alt="image" src="https://github.com/user-attachments/assets/5ccff00f-cdf5-47e5-8be2-fb3a21bd9d57" />

_(Fig 12. Ubicación fuelle.)_


### B) Acción ante el mensaje “batería en uso”

En el manual de servicio se describe que hacer en este caso en la sección 3.12 Power Failure Test; cuando la máquina está funcionando con alimentación de red (AC) y de repente se desconecta el cable de alimentación, la pantalla muestra el mensaje “Battery in Use” y el LED de AC se apaga, mientras que la máquina continúa funcionando con la batería interna, conforme a lo anterior el procedimiento de acción es:

1. Verificar de inmediato la conexión del cable de alimentación a la red eléctrica y conectarlo nuevamente si se ha soltado.

2. Tras reconectar la alimentación AC, el mensaje debe desaparecer y el LED de AC debe encenderse. Si la batería está descargada, la máquina podría apagarse si no se restablece la AC a tiempo.

3. En caso de que la batería esté descargada y el paciente está conectado, se debe priorizar la seguridad del paciente, por tanto hay que asegurar una ventilación adecuada (manual o mecánica) mientras se restablece la alimentación principal.

4. Una vez finalizada la cirugía o el uso, realizar una prueba de autonomía de la batería y, si es necesario, reemplazar la batería de litio (la lista de piezas reemplazables cada 3 años incluye la batería)

### C) Frecuencia de reemplazo del recipiente absorbente de CO₂

La vida util de este recipinete depende del flujo de gas, el número de pacientes y la concentración de CO₂ exhalado, sin embargo en la sección 4.1.1 del manual de servicio se proporciona indicaciones prácticas:

• En la sección mencionada se listan los sellos del recipiente absorbente como el canister absorvente, que deben reemplazarse cada año para evitar posibles fugas. La cal sodada no se específica porque es un consumible de corta duración.

• En las pruebas de fugas del sistema de respiración (secciones 3.7.2 y 3.7.3), se comprueba que el canister no tenga fugas. La vida útil del absorbente se determina por el cambio de color (indicador químico) que muestran muchas marcas comerciales: cuando el color cambia, por ejemplo de blanco a violeta, el absorbente está agotado.

Ahora bien conforme a lo investigado en la práctica clínica, el absorvente de CO₂ se debe cambiar cada 8-12 horas de uso continuoo cuando el indicador de color muestre agotamiento. En entornos de baja frecuencia como quirófanos con pocas cirugías, se recomienda cambiarlo al menos cada 1‑2 semanas o antes si ha estado expuesto a la humedad.


### D) Verificación fuga en el cilindro de alta presión

Acorde a la sección 3.3.2 Cylinder High Pressure Leak Test, se deben tener ciertas precauciones previas: para el N₂O, después de la prueba se debe abrir el suministro de O₂, después se debe cerrar el interruptor principal de N₂O y abrir el flujómetro de N₂O para liberar el gas residual, finalmente esperar a que el manómetro de N₂O indique cero. Teniendo la precación explicada se debe seguir el siguiente procedimiento paso a paso:

1. Asegurar que el interruptor general (system switch) esté en la posición ⭘ (apagado).

2. Cerrar todas las válvulas de los cilindros, excepto la del cilindro que se va a probar.

3. Abrir la válvula del cilindro que se está comprobando.

4. Registrar la presión actual del cilindro (leer el manómetro de alta presión correspondiente).

5. Cerrar la válvula del cilindro.

6. Esperar un (1) minuto exacto.

7. Registrar nuevamente la presión del cilindro tras ese minuto.

Ahora bien el criterio para determinar una fuga, depende de la presión del gas impulsor, si este valor disminuye más de 5000 kPa (725 psi), hay fuga; de mismo modo, si la presión del gas no impulsor es menor de 690 kPa (100 psi) también significa fuga. Llegados a dichos casos se debe instalar una nueva junta del cilindro, de cambiarse y aún presentar la fuga se debe de revisar el circuito de alta presión.

### E) Influencia del sensor de O₂ en la prueba del sistema de control de flujo

El sensor de O₂ influye notablemente, pues permite realizar una comprobación de la concentración real de oxígeno (FiO₂) y requiere que el sensor esté previamente calibrado. Para demostrar la impor tancia del mismo en el manual de servicio en la sección 3.4.1 y 3.4.2 se muestra una comparación cuando se uso, o no, el sensor.

#### 1. Prueba sin sensor de O₂:

Para esta modalidad se debe verificar el funcionamiento mecánico que impide que el flujo de O₂ sea peligrosamente bajo cuando aumenta el flujo de N₂O. Para ello se conecta el suministro de gases y se abren sus válvulas por completo, posteriormente se deben llevar los flujos a mitad de escala y comprobar que los flotadores de los tubos de flujo se mueven suavemente, estos porcesos se deben verificar para la medición del flujo de O₂ y N₂O; finalmente se debe probar que si se disminuye el el flujo de O₂, el flujo de N₂O debe disminuir proporcionalmente. Aunque se puede medir y controlar el flujo de e O₂, no se sabe realmente la concentración real del mismo, olo se comprueba que los flujos mecánicos mantengan una relación mínima.

#### 2. Prueba con sensor de O₂:

Para este método se conserva el objetivo anterior, pero adicionando la verificación que la concentración de oxígeno medida nunca sea inferior al 25% durante toda la prueba, es decir, se debe llevar a cabo el mismo procedimiento descrito con anterioridad, pero manteniendo un control estricto de de la concentración de O₂. En llegado caso de que la concentración baje del 25%, la prueba falla y se debe revisar el sistema de enlace o el sensor. La principal ventaja de esta prueba radica en que con sensor de O₂ se detecta fallos en la mezcla real de gases que no serían detectados solo con los flujos.


### F) Importancia  del sistema de presión negativa

El sistema de presión negativa (succión) tiene como propósito aspirar fluidos corporales, como las secreciones, sangre, vómito, y otros de la viía aérea del paciente (generalmente de la faringe o tráquea) durante la cirugía, para prevenir la obstrucción, la broncoaspiración y la neumonía durante los procedimientos; este sistema está integrado directamente en la máquina de anestesia. Este elemento es fundamental cuando se entiende que durante a anestesia, el paciente no puede toser ni expulsar secreciones voluntariamente, lo que aumenta el riesgo de la obstrucción de la vía aérea, por tanto no es un elemento opcional, sino que es un requisito de seguridad obligatorio

Este elemennto está compuesto principalmente por un generador de vacio, por medio del flujo de gases impulsores; un reguldor de presión negativa, que permite controlar el nivel de vacio requerido; y finalmente un frasco colector para fluidos aspirados y un filtro.


## IV. ANÁLISIS DE FALLAS Y PREGUNTAS DE DISCUSIÓN WATO EX-20

### A) Fallas que pueden presentarse en el funcionamiento de los subsistemas y sus causas

#### 1. Fallas subsistema de suministro de gases

• Fugas en las conexiones de suministro pueden ocurrir a partir de un tubo de suministro dañado o sello en la conexión deteriorado, también a partir de la propia entrada del suministro.

• El manómetro de presión de red puede muestrar lecturas inexactas o no muestra nada a causa del mal estado del mismo, o una obstrucción en la entrada del suministro.

• No ocurre la alarma “O₂ Supply Failure” cuando la presión de O₂ es baja, o ocurre cuando la presión es normal, se debe a que el interruptor de presión  de la entrada de O₂ está mal ajustado.

#### 2. Fallas subsistema de administración de gases anestésicos

• Fuga en el conjunto del pulsador de O₂ u de otros gases puede deberse a un error en el sellado o po el vaporizador sin ajustar correctamente.

• El flotador del flujómetro indica valores incorrectos o no se mueve puede deberse a un flujómetro dañado.

• El sistema de corte O₂‑N₂O no funciona si las válvulas de dichos gases se encuentran en mal estado o directamente dañadas.

#### 3. Fallas subsistema del circuito del paciente

• La fugas en el circuito del paciente son las que más sujetos a fallas están pues depende de si el canoster se encuentra en buen estado o bien instalado, del estado del sello del brazo de la bolsa manual, del frasco colector de agua, de la carcasa y sellos del fuelle, de las válvulas de respiración, de los sensores de O₂ o inclusive por los propios tubos de respiración.

• Errores en las mediciones de concentración de oxígeno se pueden deber a agua acumulada en los sensores, un error en la calibración o en el estado de los mismos.

• La onda de flujo se muestra anormal, a causa de errores en los sensores y controladores de flujo, como una fuga en la línea de muestreo de presión del sensor de flujo.

#### 4. Fallas subsistema neumático del ventilador

• La falla más común es un volumen tidal inexacto, que puede deberse a errores en el sensor de flujo, fugas en el sistema de respiración o en la línea de muestreo de presión del sensor de flujo, en los sensores de presión en la placa monitora defectuoso, un límite de presión demasiado bajo, provocando espiración anticipada, entre otros.

• El ventilador puede no funcionar correctamente después de una prueba de fugas, ya que la La válvula de seguridad no es controlable por la placa auxiliar.

#### 5. Fallas subsistema eléctrico y de alimentación

• Durante la operación, la pantalla y el LED de CA se apagan repentinamente y el ventilador no arranca, lo anterior puede deberse a que la alimentación de CA no está conectada correctamente y la batería interna es insuficiente.

• Al encender, la pantalla se ilumina momentáneamente con destello y luego se normaliza, y se produce una alarma de fallo de comunicación con la placa de potencia; se debe a que el Software de la placa de potencia dañado y se debe reiniciar.

• Si la máquina no arranca puede deberse a un cable del interruptor general suelto, un fusible fundido, el Software de placa de potencia está dañado, el Hardware de la placa de potencia es defectuoso o el interruptor general  se encuentra en mal estado.

• No sale gas por la válvula en modo ventilación mecánica, se debe a un interruptor Bag/vent defectuoso o ACGO activado, también por una válvula que no puede abrirse.


### B) Orden de los subsistemas en función del número de fallas asociadas 

1. Sistema de respiración: con más de 20 causas de fuga más fallas de sensores (flujo, O₂, presión) es el subsistema con mayor número de entradas en la tabla y en las pruebas de fugas según el capítulo 5 del manual de servicio.

2. Subsistema eléctrico y de potencia:  con 12 fallas que pueden deberse a problemas de alimentación, pantalla, botones, ventilador y conexiones de red.

3. Suministro de gases y gas impulsor: aproximadamente 10 fallas, donde se incluyen problemas con manómetros, interruptores de presión, fugas en conexiones y reguladores.

4. Sistema de administración de gases anestésicos: tiene igual número de fallas que el sistema anterior, por fugas de en pulsador O₂ flush, interruptor general, rotámetros y válvula de corte O₂‑N₂O.

5. Sistema de ventilación: con 8 fallas que principalmente son e volumen tidal inexacto y apertura de válvulas.

6. Sensor de O₂ y calibración: específicamente con 5 fallas, que incluyen errores de calibración, conexión y desviaciones.


### C) ¿Qué tipos de anestésicos son los más usados en cirugía?

la anestesia se utiliza depediendo de su uso, y este uso depende de dos categorías, anestésicos intravenosos e inhalatorios, su selección depende del tipo de cirugía, la duración, el estado del paciente y la necesidad de relajación muscular o analgesia adicional; a partir de lo annterior se describen los anestésicos más usados de cada categoría [4]:

#### 1. Anestésicos intravenosos

• Propofol: es sin duda alguna el más usado en la actualidad para inducción y para sedación en procedimientos ambulatorios, ya que permite una recuperación rápida y suave con efecto antiemético, es decir, de aliviar las nauceas.

• Etomidato: se usa en pacientes con inestabilidad hemodinámica o shock, se caracteriza por tener una mínima depresión cardiovascular.

• Ketamina: se usa en procedimientos dolorosos, asmáticos, o en entornos con recursos limitados; pues posee una analgesia potente, manteniendo reflejos protectores y frecuencia cardíaca.

• Tiopental: anteriormente era el más usado, pero fue reemplazado por el propofol, aunque aún se usa en ciertos procedimientos de neurocirugía por sus características barbitúricas, es decir, que es depresor del sistema nervioso central.

#### 2. Anestésicos inhalatrios

• Sevoflurano: de la categoría de las anestesias inhalatorias es el más usado debido a su baja solubilidad sanguínea, no es irritante en vías respiratorias, y posee inducción y recuperación rápidas; es ideal para pacientes de todas las edades por las carecterísticas anteriores, sin embargo, puede generar compuestos nefrotóxicos al reaccionar con el absorbente de CO₂ seco.

• Isoflurano: es menos soluble que el sevoflurano y puede provocar cierto grado de depresión miocárdica, sin embargo es muy estable, de bajo costo y usado en cirugías largas; a pesar de ello posee una recuperación más enta que sevoflurano, adicionalmente puede causar taquicardia.

• Desflurano: de todos es el que menos solubilidad tiene, y con una recuperación extremadamente rápida, destaca en tener un excelente control de la profundidad anestésica aunque requiere de un vaporizador calentado especial y es irritante para las vias inhalatorias.


### D) ¿Qué diferencias plantea el modelo EX‑35 con respecto al EX‑20?

El Mindray WATO EX‑35 es una evolución del WATO EX‑20, con mejoras en capacidades de ventilación, monitorización, tamaño de pantalla y flexibilidad del sistema de respiración. Aunque el manual de servicio comparte muchos componentes, las principales diferencias son [5]:

• Pantalla más grande y curvas: el EX‑35 permite visualizar simultáneamente dos curvas (presión, flujo, volumen) y un bucle, lo que facilita la detección de asincronías y cambios en la mecánica pulmonar.

• Modos de ventilación avanzados: el EX‑35 incluye PCV‑VG (Pressure Control – Volume Guaranteed), que combina las ventajas del control por presión con la garantía de un volumen tidal mínimo, muy útil en pacientes con compliance variable. También incorpora SIMV‑PRVC, que regula la presión para mantener el volumen tidal en los ciclos mandatorios.

• Mayor capacidad de cilindros: el EX‑35 cuenta con cuatro horquillas que permite usar dos botellas de O₂ alternas, evitando cambios urgentes durante la cirugía, en cambio el EX-20 únicamente cuenta con 2 horquillas para cilindros (O₂ y N₂O o Aire).

• Sistema de respiración mejorado: el EX‑35 tiene un canister de CO₂ de mayor tamaño, de hasta 2L en comparación al de 1,5L del EX‑20, lo que prolonga la duración del absorbente; además, los sensores de flujo son de tipo de hilo caliente, más precisos y con menor caída de presión.

• Batería interna: el EX-20 posee una utonomiía de entre 30 a 40 minutos, en comparación del EX-35 que posee una capacidad para desenvolverse durante 90 minutos, sin contar que posee una opción de segunda batería.


## V. CONCLUSIONES

Finalizando este laboratorio, se ocalizaron y describieron componentes como el vaporizador, la válvula APL, el recipiente absorbente de CO₂, el fuelle, el sistema de respiración y el ventilador, con base en el manual de servicio y la observación directa; además se nalizaron los submenús del ventilador (VCV, PCV, PSV, SIMV, etc.), las funciones de la válvula APL, el sistema de enlace O₂‑N₂O y el sistema de presión negativa, comprendiendo su integración neumática y electrónica.

El estudio de la máquina de anestesia WATO EX‑20 ha proporcionado una visión de sus subsistemas, modos de operación, fallas frecuentes y procedimientos de verificación. Finalmente, se ha comprendido la importancia crítica del mantenimiento preventivo y de las pruebas de seguridad, especialmente las relacionadas con fugas y concentración de O₂, para prevenir eventos adversos; este conocimiento constituye una base sólida para futuras actividades de servicio técnico, gestión de equipos biomédicos y diseño de sistemas de anestesia seguros.


## VI. REFERENCIAS

[1] Alejandra Cárdenas, “Reconocimiento de partes y funcionamiento de una máquina de anestesia,” Laboratorio de Instrumentación Biomédica y Biosensores, UMNG, 2025.

[2] Shenzhen Mindray Bio-Medical Electronics Co., Ltd., "WATO EX-20/30/35 Anesthesia Machine Service Manual", Rev. 6.0, Shenzhen, China, Nov. 2012.

[3] Erick Arguello, "Instrumentación Biomédica y Biosensores, Clase 10", UMNG, 2026.

[4] R. D. Miller, L. I. Eriksson, L. A. Fleisher, J. P. Wiener-Kronish, y W. L. Young, Eds., Miller's Anesthesia, 8th ed. Philadelphia, PA, USA: Elsevier Saunders, 2015.

[5] Mindray Medical International Limited, WATO EX‑35 Anesthesia System – Product Brochure. Shenzhen, China: Mindray, 2019.



















% Clase Nº 8: Lavarropas. Relay. Triac. Presostato. Solenoide. Jaula ardilla. Motores universales. Hay que saber preguntar al cliente. 01:55:00 (no calienta la plancha XD, que pavote quiere probar con ella). Orrin. Entra agua bomba de agua. Cuando se usa RELAY y cuando TRIAC. Mosfet. En el final hay una complicada explicación. TRIAC cumple la misma función que un RELAY.
% Andrés Imlauer
% 16 Julio 2024
   
### 🔹 Motores y electrobombas

* Todos los motores tienen **bobinado** igual. ⚡
* Para probar una **electrobomba**, se conecta a **220V**. 💧
* Puede que la bomba funcione pero **no tire agua** si el eje está cortado. 🔧
* **Motores universales**: funcionan en corriente **continua y alterna**. 🔄

---

### 🔹 Solenoides y relays

* **Solenoide de carga** = **relay**. 🟢
* Se usan relays cuando la **potencia es alta**, para motores de lavado, centrifugado y resistencias. 💪
* Otros dispositivos de control pueden usar **triac**, a veces disparado por **diac** o rectificadores de silicio. ⚡

---

### 🔹 Presostato y electrovalvula

* **Presostato** = solo un **switch de contacto**, no tiene campo magnético. 🛑
* Posibles fallas en carga de agua:

  1. Deficiencia del **presostato** 💧
  2. Deficiencia de la **electrovalvula** 🚰
* Siempre revisar la **manguera** y la presión dentro de ella. 🔍
* Filtro de agua en la parte de atrás de la lavadora: sacar con **pinza**. 🛠️

---

### 🔹 Componentes del motor

* **Jaula de ardilla**: bobinas en diagonales. 🏐
* **Trazo grueso**: hierro al silicio. 🟫
* **Trazo fino**: aluminio, que **no se magnetiza**. ⚪
* Para medir:

  * Corriente alterna → resistencia ⚡
  * Corriente continua → impedancia (resistiva, capacitiva, inductiva) 🧲

---

### 🔹 Carbones y mantenimiento

* Si no hay carbón del tamaño exacto, comprar el **más grande** y ajustar con lija. 🪵
* Tener siempre **carbones de repuesto**: medidas 12,5mm y 13,5mm. 📏
* Si el carbón es más chico en un motor grande, **chispea mucho** ⚡🔥

---

### 🔹 Reparaciones y herramientas

* **Plancha**: limpiar platino con **lija**. ✨
* **Soldador**: 60W mejor, pero 30W recomendado para pistas delicadas 🔩.
* Uso de **mallita** para desoldar más que chupador. 🧰

---

### 🔹 Diagnósticos finales

* Revisar **carbón** y bobina con **tester** antes de armar motor. ✅
* Blocapuertas defectuoso → puede ser **triac**. 🚪
* Electrovalvula y bomba → **2 triacs cada uno** ⚡

---

Si querés, puedo hacer una **versión tipo “chuleta” visual**, con emojis y colores para cada componente/fallo, lista para estudiar rápido antes de un práctico. Esto lo hace mucho más fácil de memorizar.

¿Querés que haga esa versión?
¡Perfecto! Te hago un resumen con los puntos más importantes de tu transcripción y agrego emojis para que quede más visual y fácil de estudiar:

---

### 🔹 Interpretación y actitud ante la electricidad

* Los hornos y otros equipos permiten modificaciones, pero **hay que saber interpretar lo que está hecho** 🔧.
* La **cantidad de cables da susto**, pero no hay que temer, sino tener **respeto** ⚡.
* La seguridad depende más del **conocimiento** que de la práctica mecánica. 👷‍♂️

---

### 🔹 Tipos de motores y componentes

* Tipos fundamentales de motores: **universales** y **timer mecánico** ⏱️.
* Todos los motores funcionan con **campo magnético**:

  * **Jaula de ardilla**: chapas diagonales, aluminio + hierro al silicio 🏐
  * **Aluminio** → conduce electricidad, **no se magnetiza** ⚪
  * **Hierro al silicio** → se magnetiza ✅
* **Aluminio y hierro al silicio conforman la jaula de ardilla**.

---

### 🔹 Electrónica de lavadoras

* **Procesador**: recibe órdenes y controla la lavadora 🖥️.

  * Trabaja con **5V**, necesita **TRIAC** para disparar los 220V ⚡.
* **Relays** = solenoides que manejan componentes de alta potencia 🟢.
* **Electrobomba**: expulsa el agua 💧.
* **Presostato**: solo un **switch por presión**; informa al procesador mediante **pulso o PTC** 🛑.
* **Blocapuertas**: el chip no hace nada si la puerta no cierra 🚪.

---

### 🔹 Secuencia de chequeo del chip

1. Testea si **puede cargar agua** 💧.
2. Verifica que la **puerta esté bloqueada** 🔒.
3. Chequea otros **componentes antes de iniciar** 🛠️.
4. La **bomba puede funcionar antes de cargar agua**, para garantizar drenaje inicial. 💦

---

### 🔹 Electricidad y conexiones

* Para motores y bobinas: se necesita **fase y neutro** correctamente ⚡.
* Cada motor tiene aislantes **anti magnéticos pero conductores eléctricos**.
* El trazo grueso = hierro al silicio, el trazo fino = aluminio (en diagonal) 🏗️.

---

Si querés, puedo hacer otra versión **tipo “mapa visual con emojis y colores”** donde se vea claramente la **jaula de ardilla, procesador, relays, bomba y presostato**, lista para estudiar en 1 minuto. Esto ayuda mucho para memorizar rápido.

¿Querés que haga esa versión?

¡Perfecto! Te hago un resumen con los puntos más importantes de tu transcripción y agrego emojis para que sea más visual y fácil de estudiar:

---

### 🔹 Condiciones del trabajo eléctrico

* Para que haya **trabajo eléctrico**, debe existir **resistencia** ⚡.
* Si no hay resistencia → **cortocircuito** ❌.
* La **resistencia** en un motor determina el **consumo de amperaje** y, multiplicado por el voltaje, nos da la **potencia consumida** 🔋.

---

### 🔹 Resistencia vs Impedancia

* **Resistencia (R)** → corriente continua (DC) ⚡
* **Impedancia (Z)** → corriente alterna (AC) 🔄
* La impedancia puede ser:

  * **Resistiva** 🟫
  * **Capacitiva** 🟦
  * **Inductiva** 🟪
* Para generar trabajo eléctrico debe haber **caída de tensión** ⬇️.

---

### 🔹 Probar una electrobomba

* Conectar a **220V** ⚡💧
* Para electrobombas de **12V AC**, usar un **transformador**:

  * Primario → 220V
  * Secundario → 12V AC 🔄
* **Nunca hay transformador para DC pura**, necesita **variación de voltaje** (AC).

---

### 🔹 Corriente alterna vs continua punzante

* **Corriente alterna**: pasa de 0 → máximo → 0 → negativo → 0… infinitamente 🔄
* **Corriente continua punzante**: siempre positivo y negativo, no varía ⚡
* **Fuente conmutada / switching**: convierte DC punzante para usar en transformadores 🔧
* **Fuente lineal**: misma frecuencia que la “línea” de la casa, 50 Hz, se puede conectar a cualquier enchufe 🏠

---

Si querés, puedo hacer una **versión tipo esquema visual**, mostrando **resistencia, impedancia, transformador AC/DC, y tipos de fuentes**, lista para estudiar en un vistazo. Esto ayuda a entender la diferencia entre AC, DC, lineal y switching.

¿Querés que haga ese esquema visual?

¡Listo! Te hago un **resumen con los puntos más importantes** de tu transcripción, con emojis para que sea más visual y fácil de estudiar:

---

### 🔹 Motocompresor y parámetros eléctricos

* **PH = 1 fase → monofásico** ⚡
* Frecuencia: **50 Hz** (si fuera 60 Hz, calienta más) 🔥
* Voltaje nominal: **220–240 V** ⚡
* **LRA (Locked Rotor Amper)**: corriente inicial para romper la inercia → 24 A 🔧
* **Consumo normal**: 7 A ⚡
* La corriente y el voltaje determinan la **potencia**:

  * P = V × I 🔋
  * Voltaje alto → menos amper para misma potencia 💡
  * Voltaje bajo → más amper para misma potencia ⚡

---

### 🔹 Carga de baterías y amperaje

* 1 A por hora → carga lenta de batería ⏳
* Mejor usar cargadores de 15–20 A/h ⚡
* **Importante**: no confundir **tensión (V)** con **intensidad (A)** ⚡💡

---

### 🔹 Electrobomba y lavadora

* Electrobomba diseñada para **220 V AC** 💧
* El **chip** controla:

  1. **Blocapuertas** 🚪
  2. **Electrobomba** 💧
  3. **Electroválvula** 🚰
* Lavadoras modernas: verifican **carga de agua** antes de activar bomba 💦
* Dispensers:

  * 1 → jabón líquido 🧴
  * 2 → jabón en polvo 🧼
  * 3 → lavandina 🧴

---

### 🔹 Conexiones eléctricas

* Electroválvula: **3 cables** → 1 común + 2 colores 🌈
* **Tierra**:

  * Diferente en chip y placa ⚡
  * No unir distintas tierras si no corresponden 🔌
* Neutro → común con tierra donde corresponda 🟢
* Presostato: **solo switch**, informa al chip apertura/cierre 💧

  * No tiene fase ni neutro ⚡
  * Funciona como termostato de agua o aire 🔄

---

### 🔹 Conceptos de voltaje y potencia

* 220 V → menos amper para misma potencia que 110 V 🔌
* Una lámpara de 12 V no se puede enchufar a 220 V ⚠️
* La potencia se mantiene → P = V × I, el voltaje no cambia la energía consumida por sí solo 💡

---

Si querés, puedo hacer una **versión visual tipo “diagrama de lavadora”** con el chip, blocapuertas, electrobomba, electroválvulas, dispensers, presostato y tierra/neutro, todo en un solo esquema con colores y emojis. Esto ayuda muchísimo a memorizar cómo funciona.

¿Querés que haga ese esquema?

¡Perfecto! Te hago un **resumen con los puntos más importantes** de tu explicación sobre cómo funciona el presostato en la lavadora, con emojis para que sea más visual y fácil de estudiar:

---

### 🔹 Funcionamiento del presostato

* El **presostato** controla la cantidad de agua en la tina/tacho 💧
* Funciona como un **switch**, abre o cierra según la presión en la manguera. ⚡
* La manguera conectada entre **tacho y presostato** debe estar **sin fugas de aire** 🟢
* Cuando el agua sube, ejerce presión → **el diafragma abre o cierra el switch** 🔄
* Problemas comunes:

  * Manguera mordida por rata 🐀
  * Manguera reseca o floja 💨
  * Cortar la manguera cambia la presión → la lavadora **cargará menos agua** ⚠️

---

### 🔹 Medición y diagnóstico

* **No se puede “medir” el presostato** como tal, solo funciona o no funciona. ✅❌
* Se mide **continuidad** con tester:

  * Normalmente cerrado → deja pasar corriente mientras la tina se llena 🔔
  * Abierto → indica que la tina está llena 🚱
* **Presostato vs termostato**:

  * Presostato → cambia con **presión** 💧
  * Termostato → cambia con **temperatura** 🌡️

---

### 🔹 Señales digitales e inversores

* Algunas señales son **inversoras** 🔁:

  * 0 → da 1
  * 1 → da 0
* Al medir con tester:

  * Señal normal → continuidad suena cuando debe cerrar 🔔
  * Señal inversa → continuidad se interpreta al revés ⚡
* El chip **necesita información del presostato** para saber si puede cargar agua o no 🖥️

---

### 🔹 Conceptos clave

* Nunca cortar la manguera ⚠️
* La presión depende del **largo de la manguera** → determina cuánta agua carga 🏗️
* El chip **no activa la bomba ni carga agua** hasta recibir señal correcta del presostato 💧🖥️

---

Si querés, puedo hacer un **diagrama visual del presostato y la manguera**, mostrando cómo la presión de agua abre el switch, cómo el chip recibe la señal y cómo se interpreta la señal inversa. Esto ayuda muchísimo a entenderlo en 1 vistazo.

¿Querés que haga ese diagrama?

¡Perfecto! Te hago un **resumen con los puntos más importantes** de esta explicación sobre el presostato, el chip y las electroválvulas en la lavadora, con emojis para hacerlo más visual:

---

### 🔹 Flujo de señales entre chip y presostato

* La **placa/chip** envía señal al presostato para cargar agua 💧
* El presostato puede ser **normalmente abierto (NO)** o **normalmente cerrado (NC)** 🔄

  * NC → corriente pasa mientras se llena el agua
  * NO → corriente pasa cuando está vacío ⚡
* Voltaje de señal: **0.75–1.5 V** ⚡
* El chip **lee la señal** del presostato:

  * Si recibe información → 1
  * Si no recibe → 0
* Señales inversoras: a veces un 0 → indica 1 para el chip 🔁

---

### 🔹 Qué ocurre cuando hay fallo

* Si a los **8 minutos** el chip no recibe señal de carga completa, **marca error** ⏱️❌
* La señora puede notar que **carga el agua, pero no lava** 🧴
* Responsable del corte por tiempo → **presostato** ⚠️
* El chip **ordena cortar agua**, pero si el presostato no responde → sigue llenando → error marcado ❌💧

---

### 🔹 Electrovalvulas

* Funcionan con **campo magnético (solenoide)** ⚡🧲
* Al quitar electricidad → resorte cierra el paso del agua ⬇️
* Problema típico: si la válvula actúa sin electricidad → indica fallo de control eléctrico o mecánico 🔧

---

### 🔹 Diagnóstico práctico

* Revisar si el tacho giró 🏺
* Revisar nivel de agua 💧
* Comparar con señales del chip y presostato 🖥️
* Si se corta por tiempo → presostato es el responsable ⚠️
* Si el chip no recibe señal de corte → marca error ❌

---

### 🔹 Tip adicional: reparación de planchas

* Para limpiar platinos: usar **tira fina de lija** y cerrar ambos platinos juntos ✨
* Doblar suavemente para que haga contacto sin romperlo 🛠️

---

Si querés, puedo hacer un **diagrama visual completo** del **flujo de señales chip → presostato → electroválvula → motor**, mostrando qué ocurre cuando hay error de carga o de corte. Esto deja todo mucho más claro y fácil de estudiar en 1 vistazo.

¿Querés que haga ese diagrama?

¡Perfecto! Te hago un **resumen estructurado y visual** con los puntos más importantes de tu explicación sobre errores en la carga de agua y el funcionamiento del motor en la lavadora:

---

### 🔹 Posibles errores en la carga de agua

1. **Deficiencia del presostato** 💧

   * No corta al llegar al nivel correcto → no reboza
   * Puede incluir problemas en la **manguera** si está floja, reseca o perforada
   * Resultado: carga normal o algo menor, pero **el motor no funciona correctamente** ⚠️

2. **Deficiencia de la electroválvula** 🚰

   * Reboza → agua en exceso
   * Si la válvula no corta bien, aunque el chip ordene cortar, sigue entrando agua
   * Puede generar ropa mojada tras centrifugado o exceso de agua

3. **Presión del agua insuficiente o lenta** ⏳

   * El presostato no recibe señal a tiempo → **corte por tiempo**
   * Resultado: lavadora corta antes de llenar suficiente agua → **lavado incompleto**

4. **Suciedad en filtro de entrada** 🧹

   * Reduce velocidad de entrada de agua
   * Si el émbolo del filtro no baja correctamente → sigue cargando agua
   * Consecuencia: exceso de agua, ropa mojada o centrifugado ineficiente

---

### 🔹 Secuencia de funcionamiento normal

1. Entrada de agua a través de manguera y **electroválvula** 💧
2. **Presostato** mide presión y envía señal al chip 📡
3. Chip ordena cortar ingreso de agua cuando está llena ✅
4. Motor comienza el **proceso de lavado** 🔄

   * Motor necesita **fase y neutro** ⚡
5. Electrovalvula y bomba dejan de funcionar para permitir lavado ⚠️

---

### 🔹 Diagnóstico práctico

* Si cliente dice: “Cargó agua pero no lavó”

  * Revisar **motor**: es la causa si no se mueve ⚠️
  * Revisar **electroválvula** y **presostato** para descartar errores de agua 💧
* La información del presostato es crítica para que el chip autorice el lavado 🖥️

---

Si querés, puedo hacer un **diagrama visual de flujo de lavado**, mostrando:
**entrada de agua → filtro → presostato → chip → electrovalvula → motor**, con errores y consecuencias indicadas. Esto hace que sea **mucho más fácil de memorizar y diagnosticar**.

¿Querés que haga ese diagrama?

¡Genial! Te hago un **resumen completo y visual** de esta clase sobre **motores de lavadora y sus diferencias** con énfasis en los errores de funcionamiento:

---

### 🔹 Electroválvulas y entrada de agua 🚰

* **1 ingreso de agua, 2 electroválvulas**

  * El chip decide cuál válvula abrir según el ciclo de lavado
* Si el motor **no lava**, el problema no es del agua, **viene del motor** ⚡

---

### 🔹 Tipos de motores en lavadoras

1. **Motor universal (con placa electrónica) 🔌**

   * Un **solo bobinado** en el estator y otro en el rotor
   * Recibe **pulsos del chip** para controlar giro y sentido
   * Puede girar en **cualquier dirección** (horario/antihorario)
   * No tiene **capacitor**, porque no hay bobinas en paralelo

2. **Motor mecánico (sin chip) ⚙️**

   * Dos bobinas:

     * **Trabajo (lavado)**
     * **Arranque (centrifugado)**
   * Necesita **capacitor** (14–16 µF) para regular desfasaje y mejorar factor de potencia
   * Solo puede girar en sentido definido por el sistema mecánico

---

### 🔹 Componentes del motor universal

* **Estator:** bobina fija
* **Rotor:** bobinado móvil conectado a **carbones**
* **Carbones:** transfieren corriente al rotor, creando el **campo magnético**
* Problema común: **desgaste de carbones** → motor no recibe corriente → no funciona ⚠️

  * Cliente ve: “cargó agua pero no lava”
* Solución: revisar carbones, bobina y conexiones antes de armar de nuevo

---

### 🔹 Diagnóstico práctico

* Sacar **motor y probarlo en la mesa** ⚡

  * Arranca a máxima velocidad (14–15 mil rpm)
  * Comprobar conexión de **fase y neutro**
* Medir bobina y verificar estado de carbones
* Revisar conexiones antes de instalar en la lavadora

---

### 🔹 Notas adicionales

* Motor universal no requiere capacitor
* Motor mecánico sí requiere capacitor → mejora arranque y factor de potencia
* El primer arranque del motor es crítico para acoplarse a la cuba de lavado 🏺

---

Si querés, puedo hacer un **diagrama visual comparativo** entre **motor universal y motor mecánico**, mostrando bobinas, carbones, capacitor, conexión con el chip y flujo de corriente. Esto deja **clarísimo dónde fallan y cómo se diagnostican**.

¿Querés que haga ese diagrama?

¡Perfecto! Te hago un **resumen completo y visual** de todo lo que acabás de transcribir sobre **pruebas de motor y bomba de agua en lavadoras**:

---

### 🔹 Prueba de motor universal ⚡

1. **Precaución al conectar**

   * Agarrar el **chicote del cable**, nunca adelante → evita saltos peligrosos ⚠️
   * Colocar en recipiente con agua dulce (ofrece resistencia al paso de corriente) 💧

2. **Formas de prueba**

   * Agua en recipiente pequeño → motor puede moverse sin saltar
   * Fuente de 12V, transformador, o batería de auto → velocidad más baja pero suficiente para comprobar funcionamiento

3. **Diagnóstico de carbones** 🪛

   * Problema común: **desgaste de carbones** → rotor no se electrifica → motor no gira
   * Diferencia de tamaño:

     * Si carbón de 12 en motor de 13 → chispeo, comportamiento incorrecto ⚡
     * Mejor comprar más grande y lijar hasta ajustar suavemente
   * La **cola de ratón**: tira de cobre que conecta el carbón al rotor
   * Resorte interno debe permitir deslizamiento → si está rígido → falla

---

### 🔹 Proceso después del lavado 🌀

1. **Desagote y centrifugado**

   * No puede centrifugar con agua → presostato informa 1 a la placa
   * La placa recibe 0 → autoriza motor para centrifugar
   * **Auto-balance:** motor gira lentamente a ambos lados antes de acelerar

2. **Funcionamiento de la bomba de agua** 🚰

   * Bombea durante lavado y centrifugado hasta cortar completamente
   * Puede fallar durante 2do enjuague → cambiar bomba si no desagua bien
   * Problemas comunes: desgaste de **eje** o falta de **orings** en rotor → agua pasa donde no debe

3. **Estructura de la bomba**

   * Rotor con imán y paletas
   * Oring evita que el agua entre al circuito del motor
   * Eje de acero → se desgasta con el tiempo, no la goma

---

### 🔹 Consejos prácticos 🛠️

* Tener **bomba de repuesto** en el taller
* Revisar **carbones y bobinado** antes de asumir falla de placa
* Cada prueba debe ser progresiva: verificar motor → carbones → conexión → bomba

---

Si querés, puedo hacer un **diagrama visual del motor + rotor + carbones + bomba**, mostrando **flujo de corriente, señales de presostato y chip**, para que se vea **todo el proceso de lavado, desagote y centrifugado** de manera clara y rápida de entender.

¿Querés que haga ese diagrama?

¡Excelente! Acá podemos resumir y ordenar toda la explicación sobre **TRIACs, relays y control de carga de motores en lavadoras y equipos electrónicos**:

---

### 🔹 Problema inicial

* Si al sacudir la lavadora empieza a caer agua → **bomba dañada** → cambiar bomba.
* Si la bomba falla, puede **dañar la placa** → los elementos más afectados: **TRIACs**.

---

### 🔹 TRIAC vs Relay ⚡

| Característica | Relay                                       | TRIAC                                     |
| -------------- | ------------------------------------------- | ----------------------------------------- |
| Función        | Interruptor electromecánico                 | Interruptor electrónico de AC             |
| Potencia       | Muy alta                                    | Alta, menor costo que relay               |
| Disparo        | 12V+                                        | 0.x V (muy bajo voltaje)                  |
| Vida útil      | Mecánica → desgaste                         | Electrónica → sin desgaste mecánico       |
| Usos           | Motor de lavado, centrifugado, resistencias | Motores pequeños, bombas, cargas medianas |

* Relays grandes → se usan en **motores de split**, compresores, resistencias de alta potencia.
* TRIACs → se usan en **lavadoras, bombas y motores AC**, pueden reemplazar relays en muchos casos.

---

### 🔹 Funcionamiento de un TRIAC

* Tiene **3 pines**: MT1, MT2 y Gate (compuerta).
* La corriente alterna **pasa entre MT1 y MT2** si se aplica señal de disparo a la Gate.
* Puede controlar **220V AC** sin que el procesador lo maneje directamente.

**Notas importantes:**

* Algunos TRIACs se disparan con **DIAC**, otros con **rectificadores o resistencias**.
* La señal de la placa → disparo del TRIAC → permite que la corriente AC llegue a la carga (motor/bomba).

---

### 🔹 Medición de un TRIAC

1. Poner tester en **continuidad**:

   * Punta 1 → MT1
   * Punta 2 → Gate
   * Debe dar un valor en ohmios.
2. Invertir punta → mismo valor esperado.
3. MT2 siempre aislado, si da continuidad → TRIAC dañado.

---

### 🔹 Control de motor con TRIAC

1. Motor de 220V AC → 2 cables: fase y neutro.
2. Placa electrónica **no maneja directamente 220V**, solo dispara TRIAC.
3. TRIAC deja pasar corriente hacia el motor → motor funciona.
4. Se puede usar un pulsador o la señal de la placa para controlar el motor sin riesgo de sobrecarga de la placa.

---

Si querés, puedo hacer un **diagrama visual mostrando la placa, TRIAC, presostato, electrobomba y motor**, para que veas **cómo fluye la señal desde el chip hasta el motor/bomba** y dónde actúan TRIAC y relays. Esto deja clarísimo todo el control de carga y lavado.

¿Querés que haga ese diagrama?

Perfecto, vamos a organizar todo lo que estás describiendo para que quede **claro el rol de los TRIACs y resistencias en la placa de una lavadora** y cómo se hace funcionar la bomba, electroválvula y blocapuertas:

---

### 🔹 Principio de funcionamiento

1. **Placa electrónica (chip)** → solo maneja **señales de bajo voltaje**.
2. **Elementos que requieren 220V AC** (bomba, electroválvula, blocapuertas, motor) → **no los puede manejar directamente el chip**.
3. Para esto se usan **TRIACs o relays**:

   * Cada carga tiene su TRIAC o relay dedicado.
   * TRIAC → permite pasar 220V AC a la carga cuando recibe señal de la placa.

---

### 🔹 TRIAC y resistencias

* Cada TRIAC suele estar **acompañado de 2 resistencias muy cercanas**.
* Estas resistencias cumplen funciones de:

  * **Despolarización** → permiten que el TRIAC se apague correctamente.
  * Ajuste de disparo → evitan que el TRIAC se active con señales incorrectas.
* Siempre que se reemplaza un TRIAC, **es recomendable cambiar las dos resistencias asociadas**.

---

### 🔹 Control de cargas

| Carga          | Tipo de TRIAC/Relay  | Observaciones                                                      |
| -------------- | -------------------- | ------------------------------------------------------------------ |
| Blocapuertas   | TRIAC                | Trabaja 220V, disparado por chip                                   |
| Electroválvula | 2 TRIACs             | Cada válvula tiene su TRIAC                                        |
| Electrobomba   | 1 TRIAC              | Control total por TRIAC, funciona a 220V                           |
| Motor          | Dependiendo del tipo | Motor universal puede controlarse con TRIAC o relay según la placa |

* Todo lo que el **microcontrolador necesita manejar a 220V** → requiere **su propio TRIAC o relay**.
* La fuente, información y potencia están separadas:

  1. **Fuente** → da alimentación a chip y componentes de baja tensión.
  2. **Información** → señales del presostato, botones, sensores.
  3. **Potencia** → TRIACs y relays para cargas de 220V AC.

---

### 🔹 Cómo probar TRIACs y funcionamiento

* No se puede disparar TRIAC directamente con 220V sin riesgo.
* Para probar: usar **fuente de bajo voltaje** o colocar carga controlada.
* TRIAC recibe señal de la placa → permite paso de 220V a carga.
* TRIAC defectuoso → carga no funciona → revisar TRIAC + resistencias cercanas.
* En bloque de potencia, hay que identificar si es TRIAC, transistor de juntura, MOSFET o regulador según datasheet.

---

### 🔹 Conclusión práctica

* Cada carga a 220V necesita **su TRIAC o relay dedicado**.
* TRIAC = permite control de potencia con señales bajas del chip.
* Siempre revisar **TRIAC + resistencias asociadas** si falla la carga.
* Separación de fuentes: **chip de control** vs **cargas de potencia**.

---

Si querés, puedo hacer un **diagrama completo de la placa de lavadora** mostrando: **chip → TRIAC → bomba → electroválvula → blocapuertas**, con las resistencias de disparo, para que visualices **cómo fluye la señal y la potencia**. Esto resume toda la clase de manera gráfica.

¿Querés que haga ese diagrama?



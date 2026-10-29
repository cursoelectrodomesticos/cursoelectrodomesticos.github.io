% Clase Nº 9: Medición de fuentes, relays y bobinados de ventilador
% Andrés Imlauer
% 16 Julio 2024

### Audio de la clase:

[https://youtu.be/xniJUxh04qI](https://youtu.be/xniJUxh04qI)

### O mirala en invidious

[https://redirect.invidious.io/watch?v=xniJUxh04qI](https://redirect.invidious.io/watch?v=xniJUxh04qI)

### Audio en Vocaroo:

[https://voca.ro/14o6t9RexjMx](https://voca.ro/14o6t9RexjMx)

#### Temas tocados en esta clase:
Tipos de fuentes, transformadores, procesadores, fuente standby en aires acondicionados, placas con más de 1 fuente.

Transformadores función: bajar la tensión.

En el transformador del microondas el bobinado tiene más vueltas en la segunda bobina.
Todo conductor tiene impedancia.

Cable más largo: mayor impedancia.



Aquí tienes un resumen de los puntos más importantes de la clase, con emojis incluidos:

* 🔌 **Tipos de fuentes**: Conocer las distintas fuentes de alimentación y sus aplicaciones.
* 🔄 **Transformadores**: Su función principal es **bajar la tensión**.
* ⚡ **Procesadores**: Se mencionaron como parte de la electrónica de control.
* ❄️ **Fuente standby en aires acondicionados**: Permite mantener funciones mínimas sin activar toda la unidad.
* 🖥️ **Placas con más de 1 fuente**: Placas que requieren varias fuentes para diferentes circuitos.
* 🔧 **Transformador de microondas**: El bobinado secundario tiene **más vueltas** que el primario.
* 🛠️ **Impedancia de conductores**: Todo conductor tiene **impedancia**, que aumenta con la longitud.
* 📏 **Cable más largo**: Mayor impedancia → puede afectar el rendimiento del circuito.

Si quieres, puedo hacer una **versión aún más resumida tipo “chuleta rápida”** con emojis y palabras clave para estudiar. ¿Quieres que lo haga?
Aquí tienes un **resumen destacado y con emojis** de los puntos clave de tu transcripción, organizado para estudio:

---

### 🔹 Identificación y medición

* 🔍 **Primario vs secundario de transformador**: El **primario tiene menos resistencia**.
* 🔋 **Capacitores**:

  * Polarizado → para **corriente continua**.
  * No polarizado → puede usarse en corriente continua y alterna.
* 🧪 **Capacitor en paralelo**: sirve para **prueba rápida**; se puede medir **sin sacar**.
* 🌡️ Medir **en frío o caliente** puede dar resultados diferentes.
* ⚙️ **Relay**: medir pines 2 y 3 de los 3 pines superiores.
* ⚡ **Tipos de relay**: amperimétrico y voltáico.

---

### 🔹 Corriente y fuentes

* 🔄 **Corriente en placas**: alterna y continua.
* 🔌 **Fuentes**: lineal, switching/conmutada, resistiva/capacitativa.
* 🔧 Hasta antes del rectificador → corriente alterna.
* 🔋 Capacitor → transforma corriente **pulsante** en corriente **continua pura**.
* 🔄 Rectificador de onda completa → importante **hacer pares de salida**, no solo el símbolo en el circuito.

---

### 🔹 Transformadores y microprocesadores

* 🔧 Transformador → **reduce el voltaje** para trabajar con el microprocesador.
* 💻 Microprocesador → recibe órdenes y controla los tiempos de operación.
* ⚡ Ejemplo split: toma temperatura y enciende según la orden del usuario.

---

### 🔹 Reparación y práctica

* 🛠️ **Placas electrónicas** → mismos componentes: resistencias, capacitores, bobinas, mosfets, triacs, relays.
* ⚠️ **Precaución**: alto voltaje vs bajo voltaje; cuidado con el espacio reducido entre secciones.
* 🧩 **Desarmado de equipos** (split, tostadora, plancha):

  * Tornillos separados por tipo (philips, torx).
  * Orden de desarmado puede variar (adelante-atrás o atrás-adelante).
  * Evitar forzar plásticos o piezas.
* 🔌 Se puede crear un **cargador de celular con fuente lineal**.

---

Si quieres, puedo hacer una **versión ultra resumida tipo “chuleta visual”** con solo palabras clave + emojis para estudiar rápido antes del examen. Esto queda muy práctico para repasar placas y transformadores.

¿Querés que haga esa versión?
Aquí tienes un **resumen organizado y con emojis** de los puntos más importantes de tu última transcripción:

---

### 🔹 Fuente y microprocesador

* 🟢 **Recepción de la orden**: el microprocesador recibe la orden del control porque la **fuente standby** siempre está encendida.
* 🔋 **Fuente standby**: mantiene activo solo el microprocesador; forma parte de la fuente principal.
* 🖥️ **Placas**: algunas tienen 2 fuentes, otras 3, pero el funcionamiento es similar.

---

### 🔹 Tipos de fuentes

* ⚡ **Lineal**: se alimenta de la misma frecuencia que la tensión (220 V x 50 Hz).
* 🟡 **Resistiva/capacitativa**: no usan transformador; usan **resistencia y/o capacitor en serie** para reducir tensión.
* 🔄 **Switching/conmutada**: no se detalla, pero es otra de las tres principales.

---

### 🔹 Transformadores

* 🔧 Función: **bajar la tensión**.
* 🔁 Estructura: espira primaria → núcleo de hierro → espira secundaria.
* 🔹 Primario vs secundario:

  * Primario → más vueltas → mayor impedancia.
  * Secundario → menos vueltas → menor voltaje de salida.
* 📏 **Impedancia**: todo conductor tiene impedancia; mayor longitud → mayor caída de tensión.
* ⚡ Identificación: el **primario tiene mayor impedancia**.

---

### 🔹 Capacitores

* 🔵 **Polarizado**: para corriente continua (positivo y negativo).
* ⚪ **No polarizado**: para corriente alterna; puede usarse en continua.
* 🔧 Función: **reducir tensión** y **causar impedancia** al circuito.
* ❌ Conectarlo al revés en CC → puede explotar.
* 🌀 En AC → capacitor cambia de polaridad constantemente; no necesita polaridad marcada.

---

### 🔹 Placas electrónicas

* 🔌 Entrada de **220 V** y salida de **12 V**, dependiendo de la placa.
* 🖥️ Microprocesador → alimentado con 3-5 V.
* ⚙️ Uso de **relevadores/relays** requiere un voltaje mayor que el necesario para el chip.
* 🔧 Reguladores de voltaje: algunos componentes de 3 patas son reguladores, no transistores.
* 🟡 Capacitiva/resistiva → reemplaza transformador en algunas placas (como lavadoras).

---

Si querés, puedo hacer un **resumen completo de todas tus clases de fuentes, transformadores y placas electrónicas** en **una sola “chuleta visual” con emojis**, lista para estudiar rápido. Esto incluiría standby, tipos de fuentes, transformadores, capacitores y microprocesadores.

¿Querés que haga eso?
Aquí tienes un **resumen con emojis** de los puntos clave sobre fuentes y rectificación de tu clase:

---

### 🔹 Detección de falla

* ⚠️ **No enciende nada** → revisar **fuente** o **chicote de power**.
* 🔌 Placas de aire acondicionado siempre necesitan **corriente continua de bajo voltaje** (30, 12, 9 V según placa).

---

### 🔹 Tipos de fuentes

* 🔹 **Lineal**: usa transformador lineal, trabaja a **50 Hz**, salida 12 V, fácil reemplazo si amperaje es mayor o igual.
* ⚡ **Switching/conmutada**: transformador pequeño, trabaja de **10.000 a 100.000 Hz**, requiere filtrado para el microprocesador.
* 🟡 **Capacitiva/resistiva**: sin transformador, capacitor en serie con entrada de 220 V, cae la tensión.
* 🛠️ Calidad: **switching > capacitativa/resistiva** (menos fallas).

---

### 🔹 Transformador y reducción de tensión

* 🔧 Función: **bajar tensión** de 220 V a valores bajos para el chip o relays.
* ⚡ Diferencia con capacitor en serie: el transformador trabaja con **frecuencia de línea**, el capacitor con **impedancia**.

---

### 🔹 Rectificación

* 🔄 Rectificador → convierte **corriente alterna pulsante** en **corriente continua**.
* 🟢 **Puente de diodos (ciclo completo)**:

  * Entrada: fase y neutro.
  * Salida: positiva y negativa.
  * Importante: **armar pares de diodos correctamente**; ubicación física no importa.
* ⚡ Antes del rectificador → AC, después → CC punzante.

---

### 🔹 Filtrado con capacitor

* 🔵 Después del rectificador → capacitor **filtra la corriente**, pasando de **CC punzante** a **CC pura**.
* ❌ Si la fuente falla → capacitor defectuoso es la causa más común.
* 🔧 Práctica del profesor: **medir primero**, cambiar si no filtra bien; evita conectar polarizado al revés.

---

### 🔹 Consideraciones prácticas

* 🧰 **Transformadores lineales**: el amperaje debe ser **igual o superior** al requerido por la placa.
* 💰 Fabricante usa amperaje mínimo para **reducir costos**.
* 🔌 Capacitiva/resistiva → carece de transformador, más económica, pero falla más.
* 🟢 Switching → requiere filtrado y rectificación antes de alimentar microprocesador.

---

Si querés, puedo hacer un **resumen completo de todas tus clases de fuentes, transformadores, rectificación y capacitores** en **una sola “chuleta visual con emojis”** lista para repasar todo de golpe. Esto quedaría muy práctico para estudiar antes de un examen.

¿Querés que haga eso?
Aquí tienes un **resumen destacado con emojis** de los puntos clave sobre medición y regulación de voltaje en placas electrónicas:

---

### 🔹 Medición de componentes en la placa

* 🟢 **En serie**: componentes se pueden medir directamente en la placa.
* ⚠️ **En paralelo**: pueden dar valores engañosos → es mejor **sacar uno de los pines o el componente completo**.
* 🌡️ **Medición en frío vs en funcionamiento**: en frío puede dar **bien**, pero al trabajar el componente falla.
* 🔧 Ejemplo: **capacitor en corto sobre un TRIAC** → hacía que TRIAC pareciera recibir señal, pero en realidad el capacitor era el problema.

---

### 🔹 Regulación de voltaje

* 🔌 Transformador → puede dar **30 V AC**, pero la placa necesita **12 V DC**.
* 🛠️ Solución: usar un **regulador de voltaje de 12 V** (componentes de 3 patas: entrada, tierra, salida).
* ⚡ Funcionamiento:

  * Entrada → 30 V AC filtrada
  * Salida → 12 V DC hacia la placa
* 🔵 Donde conectar: **después del capacitor que filtra la salida del transformador**.

---

### 🔹 Componentes lógicos y reguladores

* 78xx → reguladores de voltaje estándar.
* Circuitos lógicos → XOR, AND; requieren combinaciones de 0 y 1 para funcionar.
* 🔧 Aplicación práctica: siempre verificar **entrada, tierra y salida** antes de soldar en la placa.

---

Si querés, puedo armar **una guía completa tipo “chuleta de laboratorio”** que incluya:

* Identificación de fuentes y transformadores
* Rectificación y filtrado con capacitores
* Reguladores de voltaje
* Medición de componentes en serie/paralelo

Esto quedaría listo para usar en tus prácticas de laboratorio o reparaciones de placas.

¿Querés que haga esa guía completa?
Aquí tienes un **resumen con emojis** de los puntos clave de esta clase sobre transformadores, filtrado, tierra y relays:

---

### 🔹 Adaptación de transformadores y filtrado

* 🔧 Transformador de **15 V para usar en 12 V**:

  * Rectificamos → pusimos **filtro (capacitor)**.
  * Cortamos la pista del transformador original para **reemplazarlo** sin dañar otros sectores.
* ⚠️ No se puede bajar tensión de AC directamente (como de 30 V a 15 V) salvo con **capacitiva resistiva**, pero es insegura.
* 🟢 Punto clave: **llegar al primer filtro después del puente rectificador** para alimentar reguladores de 9 V, 5 V, 3 V.

---

### 🔹 Cargador de celular ejemplo

* 🔌 Se puede usar un **transformador lineal** y un cable del celular.
* Requiere **5 V DC** para cargar.
* Batería solo sirve para alimentar → no se “carga” directamente en la placa.

---

### 🔹 Corriente continua y tierra

* 🟡 Corriente continua punzante → **negativo siempre a tierra (chasis)**.
* Todos los **capacitores polarizados** conectan su negativo al chasis → punto común de la placa.
* ✅ No hay múltiples negativos en un sector.

---

### 🔹 Relays y conexiones

* 🔗 Relay de 5 pines:

  * Entrada/salida de 220 V puede variar → importante **observar la función real en la placa**.
  * La bobina genera **campo magnético**, que mueve el émbolo.
* ⚡ Fase y neutro: siempre verificar por dónde entra la fase para alimentar correctamente.
* 🔄 Teoría vs práctica: la entrada puede estar en un lado o en otro según la placa, pero la función siempre es la misma.

---

### 🔹 Conceptos finales

* 🔋 Campo magnético en relays → movimiento mecánico (énfasis en **electromagnetismo aplicado**).
* 🧩 Adaptación de fuentes y transformadores → clave para alimentar correctamente microprocesadores y otros circuitos.

---

Si querés, puedo hacer un **resumen unificado de todas tus clases de fuentes, transformadores, capacitores, rectificación y relays** en **una sola “chuleta visual con emojis” lista para estudiar rápido**. Esto incluiría todo: standby, lineal, switching, resistiva/capacitiva, filtrado, tierra y reguladores.

¿Querés que haga esa guía final?
Aquí tienes un **resumen con emojis** de los conceptos sobre **relays y control de electrobombas**:

---

### 🔹 Principio de funcionamiento del relay

* 🧲 **Bobina**: crea un **campo magnético** que mueve un émbolo.
* ⚡ **Corriente aplicada**:

  * Estado de reposo → normalmente abierto (NO) y normalmente cerrado (NC).
  * Al excitar la bobina → NO se cierra, NC se abre.
* 🔄 **Inversión**: de ahí el nombre “inversora” → invierte el estado de los contactos.

---

### 🔹 Tipos de relays

* 5 pines → bobina + NO + NC.
* 4 pines → normalmente cerrado cortado, solo NO.
* 8 pines → doble inversora (2 NO + 2 NC + 2 bobina).
* ⚙️ Incluso hay **triple inversora** en aplicaciones más complejas.

---

### 🔹 Aplicación práctica

* 🔌 **Electrobomba**:

  * Señal de control → 12 V DC desde el procesador.
  * Relay → conecta la electrobomba a **220 V AC**.
* 🟢 Tensión de bobina → 12 V DC
* ⚡ Tensión de carga → 220 V AC
* 🌐 Tierra: hay **CC y AC** en la misma placa; símbolos gráficos son solo referenciales.

---

### 🔹 Configuraciones especiales

* 🔄 Combinación de relays → permite cambiar dirección de motor o controlar distintos circuitos.
* 💡 Entrada y salida → pueden intercambiarse según diseño; lo importante es **la función de apertura/cierre**.

---

Si querés, puedo hacer un **resumen final unificado de todas tus clases sobre placas, fuentes, transformadores, capacitores, reguladores y relays** en **una sola “chuleta visual con emojis” lista para repasar todo de golpe**. Esto quedaría perfecto para estudiar antes de laboratorio o examen.

¿Querés que haga esa guía final?
Aquí tienes un **resumen con emojis y los puntos clave** sobre **medición de relays, reguladores, y motores** según tu clase:

---

### 🔹 Medición de relays y bobinas

* 🔎 **Medición de bobina**: entre pines 2 y 3 → debe dar resistencia (ej. 15–16 Ω).
* ⚠️ Componentes similares pueden engañar → siempre verificar a simple vista y medir con cuidado.
* 🔋 Capacitores que trabajan a **311 V** → **descargar antes de medir**.
* 🔌 Relay de potencia → común en 220 V AC, bobina excitada con 12 V DC.
* 🔄 Entrada/salida de relay: fase y neutro pueden variar según diseño, la función es **conmutar corriente**.

---

### 🔹 Reguladores de voltaje

* 🔧 Reguladores 78xx → reducen tensión:

  * 7812 → 12 V DC
  * 7805 → 5 V DC (ej. para cargar celular)
* ⚡ Entrada siempre > salida, sobrante → disipado a tierra.
* 📱 Cargador de celular: requiere **5 V DC**, el chip interno regula corriente según carga.

---

### 🔹 Relays en sistemas de alarmas

* 🌐 Señales de falla → tierra activa el relay → manda información a equipo central (ej. Buenos Aires).
* 🔋 Bobina sensible → maneja poca corriente.
* ⚡ Diferentes relays → manejan distintas tensiones (220 V AC, 48 V DC).
* 🔄 Relays con varios inversores → para controlar múltiples acciones independientes (lámparas, alarmas, señales).

---

### 🔹 Principio de motores

* 🧲 **Campo magnético** generado por bobina → interactúa con **núcleo magnetizado (estator)** → mueve rotor.
* 🔄 Corriente alterna → cambia polaridad 50 veces por segundo → crea polos norte/sur variables.
* 🏗️ Motores tipo **jaula de ardilla**: chapas de acero + aluminio → polos se atraen y repelen → rotación continua.
* ⚡ Motores ventiladores CC → imán permanente + bobina → bobina varía el campo magnético, imán permanece constante.

---

### 🔹 Bobinas de trabajo y arranque

* 🔵 Motor necesita:

  * Bobina de **arranque**
  * Bobina de **trabajo**
* 🔧 Componente de corte (relay o capacitor) → desconecta bobina de arranque al arrancar el motor.
* ⚡ Diferentes velocidades → por eso se separan arranque y trabajo.

---

Si querés, puedo hacer un **resumen final completo de todas tus clases de placas, fuentes, relays, motores y reguladores** en **una guía visual con emojis** lista para repasar todo de golpe antes de laboratorio o examen. Esto uniría todos los conceptos que vimos hasta ahora en un solo documento muy práctico.

¿Querés que haga esa guía final?
Perfecto, vamos a resumir todo lo que explicaste sobre **tipos de relays, motores y corrección de factor de potencia** en puntos claros con ejemplos y emojis para que quede fácil de estudiar:

---

### 🔹 Tipos de relays

1. **Amperométricos** ⚡

   * Se activan según **consumo de corriente**.
   * Ej.: Relay que deja pasar electricidad al arranque y se desconecta al caer el consumo.

2. **Volumétricos** 💨

   * Trabajan según **flujo de aire o líquido** (similar a amperométricos pero basado en otro principio).

3. **Por fuerza centrífuga** 🌀

   * Mecanismo mecánico → placas y resortes.
   * Estado quieto → cierra; al girar muy rápido → abre.
   * Ej.: Cortadoras de césped.

---

### 🔹 Motores con bobinas

* **Motor de heladera/freezer:** bobina de arranque + bobina de trabajo.
* **Motor de ventilador/split:** no tiene bobina de arranque → ambas bobinas trabajan **en paralelo**.
* Punto común → si pongo fase o neutro, llega a ambas bobinas.

---

### 🔹 Problemas si conectamos mal las bobinas

* Dos bobinas en paralelo sin corrección → **desfase**.
* Consecuencias:

  * 🔥 Exceso de consumo
  * 🌀 Sobrecalentamiento
  * 💥 Desprendimiento del esmalte → cortocircuito
* Solución: **corrección del factor de potencia** con un capacitor.

---

### 🔹 Corrección de factor de potencia ⚙️

* Corrige desfasajes entre **inductancia** y **capacitancia**:

  * Error de inductancia → se corrige con capacitancia
  * Error de capacitancia → se corrige con inductancia
* Objetivo → consumo más cercano al real.
* Precaución: no modificar microfaradios sin medir → riesgo de sobrecarga.

---

### 🔹 Medición y prueba de motor

* Medir amperaje → con **pinza amperométrica**.
* Probar bobina con **foco en serie**.
* Ajustar **capacitor** → menor consumo posible sin exceder amperaje nominal.

---

### 🔹 Conexión del capacitor en motor de ventilador

1. Bobina de trabajo → fase directa
2. Bobina de arranque → alimentada a través de capacitor
3. Neutro:

   * Trabajo → directo
   * Arranque → mismo polaridad que trabajo
4. Resultado: las bobinas trabajan en paralelo **corrigiendo factor de potencia** y evitando sobreconsumo.

---

Si querés, puedo hacer un **diagrama visual de motor de ventilador con capacitor y bobinas** mostrando cómo se conectan fase, neutro y punto común para que se vea clarísimo.

¿Querés que haga ese diagrama?
Perfecto, todo lo que contaste es clave para **probar y conectar ventiladores de CA con selector de velocidad**. Te hago un resumen organizado y claro con puntos clave:

---

### 🔹 Fase y neutro

* Siempre es preferible **cortar la fase**, no el neutro.
* Problemas comunes si se invierte: chasis puede quedar vivo → ciclos de magnetismo y riesgos eléctricos.
* Neutro nunca va a tierra; fase sí pasa por switch o relay.

---

### 🔹 Cambio de velocidad en ventiladores

* Se hace **eléctricamente mediante bobinados y capacitores**.
* Ventiladores de pie: tienen bobinas para inducción/impedancia.
* Ventiladores de techo: la bobina no tiene impedancia, usan selector externo.

---

### 🔹 Identificación de cables y bobinas

1. Quitar tapas y exponer los cables.
2. Colores no confiables → medir **impedancia entre pares**.
3. Medición:

   * Todos los pares posibles → se repiten valores similares.
   * Valor más alto → bobina de arranque.
   * Valor siguiente → bobina de trabajo.
   * Valores intermedios → bobinas de impedancia.

---

### 🔹 Conexión de capacitor

* Los capacitores **para ventiladores de CA no son polarizados**.
* Se conecta:

  * Neutro → bobina de arranque **a través del capacitor**
  * Fase → bobina de trabajo directa
* Resultado: ambas bobinas trabajan en paralelo **corrigiendo el factor de potencia**.

---

### 🔹 Fusible interno

* Protege por **cortocircuito o temperatura**.
* Puede estar dentro del bobinado o en serie con el capacitor.
* Si se reemplaza o puentea, tener cuidado → cables finos y delicados.

---

### 🔹 Identificación y etiquetado

* Usar **cinta de papel o enmascarar** para marcar cada cable.
* Mantener la correspondencia entre entradas y salidas → A con A, B con B, etc.
* Esto evita confusión al desarmar/rearmar ventiladores.

---

### 🔹 Velocidades del selector

* Selector tipo **impedancia**:

  * Velocidad 1 → más baja (mayor impedancia)
  * Velocidad 2 → intermedia
  * Velocidad 3 → más alta (mínima impedancia, casi directo)
* No conectar en medio de bobinado → puede dañarlo.

---

Si querés, puedo hacer un **diagrama completo de ventilador con bobina de arranque, bobina de trabajo, capacitor y fusible**, mostrando cómo medir e identificar cada cable para diferentes velocidades. Esto hace que sea mucho más fácil de entender visualmente.

¿Querés que haga ese diagrama?
Perfecto, todo lo que contaste corresponde a **diagnóstico de un ventilador con bobinas y fusible interno**. Te hago un resumen organizado y práctico con los puntos clave:

---

### 🔹 Fusibles internos

* **Aluminio:** no tocar, irreparable.
* **Térmico:** protege por sobretemperatura → ubicado dentro del bobinado, no al lado.
* Puede haber fusibles “destornillables” en otros equipos, pero aquí es térmico.
* Si se rompe, hay que localizar ambos extremos dentro del bobinado y reconectarlos con cuidado.

---

### 🔹 Comprobación de fase y neutro

* Fase → preferentemente lado derecho del enchufe.
* Neutro → lado izquierdo.
* Algunos ventiladores nuevos pueden venir invertidos → hay que corregir.
* Continuidad: medir neutro con selector de velocidad para asegurarse que no hay cortes.

---

### 🔹 Medición de la bobina y circuito

* Usar **pinza amperométrica** en el neutro (fase muy corta no sirve).
* Si el multímetro da menos voltaje de 220V: caída de tensión por **impedancia de la bobina** → normal si está funcionando.
* Si no hay corriente: posible fusible abierto o cable cortado.

---

### 🔹 Detectar bobina cortada

* Si el fusible está bien pero hay un **cable suelto dentro del bobinado**, la bobina parece cortada.
* No necesariamente está quemada, pero el flujo de corriente se interrumpe.
* Para medir continuidad en serie con foco → seguro: si hay corto, la lámpara se enciende pero no vuela la instalación.

---

### 🔹 Procedimiento para localizar fusible o cable suelto

1. Romper precinto o barniz con paciencia.
2. Localizar ambas patitas del fusible dentro del bobinado.
3. Reconectar con soldadura o puente si es posible.
4. Verificar continuidad antes de energizar.

---

Si querés, puedo hacer un **diagrama paso a paso de cómo medir la continuidad de cada bobina, ubicar el fusible y verificar la fase/neutro** para un ventilador con bobina de arranque y trabajo, incluyendo la posición correcta del capacitor. Esto hace mucho más fácil seguirlo visualmente.

¿Querés que haga ese diagrama?

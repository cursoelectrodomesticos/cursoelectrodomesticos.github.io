% Clase Nº 4: Capacitores, Transformadores - Fuente lineal, switching o conmutada, y capacitiva. Rectificador onda completa. Núcleo ferrita, núcleo hierro.
% Andrés Imlauer
% 16 Julio 2024
   
## Audio de la clase:

[https://youtu.be/OSlqnhmQsMQ](https://youtu.be/OSlqnhmQsMQ)

[https://vocaroo.com/1dD9MmKu95UO](https://vocaroo.com/1dD9MmKu95UO)

### O miralo desde una instancia de invidious

[https://redirect.invidious.io/watch?v=OSlqnhmQsMQ](https://redirect.invidious.io/watch?v=OSlqnhmQsMQ)


### **Medición y prueba de fuentes switching**

* Sin osciloscopio, medir los pulsos de una fuente switching es difícil por la **alta frecuencia**.
* El tester convencional se puede **quemar**, no sirve para alta frecuencia.
* Uso de un **foco de neón** como indicador: titila si la fuente funciona hasta antes del transformador.
* Si el foco titila, se puede deducir que el problema está en el **transformador**, no en la fuente.
* **Buscapolo digital** recomendado: distingue **descarga directa** de **corriente de inducción**.
* Los buscapolos analógicos pueden no verse bajo luz solar intensa.

---

### **Capacitores**

* Existen **capacitores simples y dobles**; todos son genéricos salvo uno distinto.
* Se usan en las **bobinas de trabajo de aires acondicionados** (ej.: 35 μF, 45 μF, 50 μF).
* **No confiarse del tamaño**: el valor real puede diferir del aparente.
* Medir un capacitor no garantiza que funcione correctamente; ejemplo: medir 65 μF en uno de 90 μF es **incorrecto**.
* Tipos: **polarizados** y **no polarizados**.

  * Polarizados: cuidado con la **polaridad**, invertir puede causar **explosión**.
  * No polarizados: para corriente alterna (AC).
* Capacitores tienen dos medidas: **microfaradios (μF)** y **voltaje (V)**.
* Se cargan al **valor pico** de la corriente.

---

### **Electricidad y transformadores**

* Con **corriente continua (CC)** no funciona un transformador; requiere **variación de campo magnético** (corriente alterna).
* Cada ciclo de corriente alterna genera **cambio de polos magnéticos**: norte ↔ sur constantemente.
* Corriente directa crea solo un **electroimán**, no induce voltaje en el secundario.
* Para aumentar voltaje de CC directamente (ej. de 9 V a 12 V) **no se puede** sin un método especial (inversor o convertidor).

---

### **Otros consejos y buenas prácticas**

* Ahora **no se puede falsificar el consumo eléctrico** debido a medidores digitales.
* Antiguamente se falsificaba desconectando un puente, pero se detectaba fácilmente.
* **Respeto al cliente** y cuidado de la **imagen profesional** son fundamentales.
* Lo más difícil en electricidad es **manejar electromagnetismo** (transformadores, bobinas, núcleos de hierro).

---

Si quieres, puedo hacer **un diagrama visual resumido** que conecte **fuente switching → transformador → capacitores → mediciones**, para que se entienda más rápido cómo todo se relaciona. Esto te sirve mucho para estudio práctico.

¿Quieres que haga ese diagrama?

Aquí tienes un resumen con los **puntos más importantes** usando **emojis** para destacar conceptos clave:

---

### **Magnetismo y transformadores** 🧲⚡

* Un **imán roto** no se puede unir para generar un campo magnético 🔧❌.
* La corriente que inicia de 0 crea un **campo magnético en el hierro** 🔄.
* El **campo magnético** se propaga en todas direcciones, pero se orienta según el estudio 📐.
* Cada **medio ciclo** genera un campo magnético; el hierro puede quedar imantado 🌀.
* En **corriente alterna**, el secundario también tendrá AC; la diferencia es el voltaje ⚡↔⚡.
* **Neutro AC = tierra**, mientras que en CC el negativo ≠ tierra 🔋❌🌍.

---

### **Uso seguro de tierra** 🌍⚠️

* Si conectamos la tierra mal (ej.: como neutro), la **tensión baja** y los motores “pistonean” 🏎️💥.
* La electricidad **siempre sigue el camino de menor resistencia** ⚡↘️.
* Instalación de jabalina a tierra: protege al usuario y dirige la corriente correctamente 🪛✅.
* No usar la tierra como neutro para **reducir consumo eléctrico** ❌💡.
* Concepto de **aislación galvánica**: primaria y secundaria de un transformador están aisladas 🔌🛡️.

---

### **Potencia y capacitores** ⚡🔋

* **Potencia = tensión × intensidad** ⚡✖️🔋.
* Capacitores negros: usados para **arranque de motores** ⚫🔄.
* Relé elimina la bobina de arranque 🔧.
* Valor de 220 V = valor eficaz, mientras que el **pico real** en capacitor es 320 V 🔺⚡.

---

### **Baterías y carga** 🔋💡

* Incorrecto decir “cargar la batería”; se **equilibran potenciales** ⚖️.
* Los electrones van de la **placa positiva a la negativa**, restableciendo la diferencia de potencial 🔁.
* La batería pierde voltaje cuando **placas positivas y negativas se igualan** 0️⃣.
* Al “cargar”, movemos electrones a la placa negativa y liberamos agujeros en la positiva 🔄⚡.

---

### **Electrónica y chips** 💻🔋

* Debemos **procesar la electricidad** para que al chip le lleguen 3 V, aunque pueda recibir hasta 9 V ⚡➡️💻.

---

Si querés, puedo hacer **una versión más visual** usando **dibujos de imanes, transformadores y flujo de corriente** para que se entienda todo de un vistazo.

¿Querés que haga eso?

Aquí tienes un resumen con los **puntos más importantes** de tu texto, usando emojis para mayor claridad:

---

### **Por qué el chip necesita 3 V** 💻⚡

* Los chips necesitan **activación de energía** para funcionar 🔋.
* También se llaman **procesador o junta**; su función es **recibir órdenes** 🧠📡.
* Para funcionar, **requiere diferencia de potencial**: positivo y tierra/negativo ⚡↔🌍.
* Si no llega el voltaje correcto, puede haber fallas por:

  * Bobina quemada 🔥
  * Transistor dañado ⚡❌
  * Resistencias o diodos quemados ♻️🔥
  * Pista rota en la placa 🛠️ (se usa microescopio para inspección 🔬)

---

### **Lavadoras y selectores** 🧺⚙️

* Selectores antiguos: **mecánico-voltaico**, regresan al estado inicial 🔄.
* Lavadoras modernas: **electrónicas**, no vuelven automáticamente; usan **placa con memoria y programador** 💾.
* La placa **lee la acción** solo cuando se activa el programa 📝.

---

### **Corriente para chips** ⚡💻

* Necesita **3 V de corriente directa (DC)** para funcionar 🟢.
* Chips sensibles: incluso **frecuencias parásitas en el aire** pueden afectar su funcionamiento 🌫️⚠️.
* Para medir capacitores: deben estar **totalmente descargados** primero 🟢⚡.

---

### **Conversión de corriente** 🔄⚡

* La corriente alterna (AC) de 220 V **no sirve directamente para chips** ❌⚡.
* Se debe convertir AC a **corriente continua lineal (DC)** 🔌➡️💻.

---

### **Componentes electrónicos básicos** 🛠️

1. **Resistencias** 🔹

   * Símbolo Ω
   * Ej: 2k = 2000 Ω
2. **Capacitores** ⚫

   * Polarizados → CC, cuidado con invertirlos ❌🔋
   * No polarizados → AC
3. **Bobinas / Inductores** 🌀

   * Símbolo: L
   * Pueden parecer resistencias, se distingue por el símbolo de faradios (F) o inductancia (L)
4. **Diodos** ➡️

   * Permiten paso de corriente en un solo sentido
   * Terminales: **ánodo (+)** y **cátodo (-)**
   * Usos: rectificar AC a DC 🔄➡️💡

---

Si querés, puedo hacer una **versión súper resumida y visual con emojis + flechas**, para que tengas todo el flujo de energía en chips y placas de manera rápida y fácil de estudiar.

¿Querés que haga eso?

Aquí tienes un **resumen con los puntos más importantes** de tu texto, usando **emojis y flechas** para mayor claridad:

---

### **Diodos y rectificación** ➡️🔋

* La **corriente pasa según la orientación del diodo**:

  * Ciclo positivo → pasa ✅
  * Ciclo negativo → bloquea ❌
* Corriente desde **ánodo → cátodo** pasa; inversa también puede pasar según polaridad de CC ⚡.
* Usamos diodos para **convertir AC en DC** (rectificación) 🔄➡️💡.
* El diodo debe estar **en serie con la corriente** que ingresa 🔗.

---

### **Transformadores lineales vs switching** 🌀⚡

* **Transformador lineal**: núcleo de hierro, trabaja a **50/60 Hz**, se magnetiza y desmagnetiza cada ciclo 🔄🧲.
* **Transformador con núcleo de ferrita**: alta frecuencia (10.000 – 100.000 Hz), se mantiene magnetizado constantemente ⚡🧲.
* El **primario y secundario** se conectan al bobinado, con placas en forma de “E” + recta.
* Línea: lineal = ciclo de la red ⚡; switching = ciclo altísimo ⏱️.
* **No se puede reemplazar un transformador switching con otro que no tenga la misma frecuencia** ❌⚠️.
* Materiales:

  * Lineal → hierro + silicio o cromo 🧲
  * Switching → ferrita 🟣

---

### **Rectificación y regulación de voltaje** 🔧

* Para rectificar se usa un **puente rectificador de onda completa** (4 diodos) 🔲.
* En placas, los diodos no se ven en rombo por espacio; se conectan **opuestos en la pista** 🔀.
* Después de rectificar, un capacitor almacena y suaviza la DC ⚡🟢.
* Para obtener voltajes distintos (12 V → 9 V o 5 V) se usa un **regulador de voltaje** 🔧💡.
* Antes de rectificar, siempre definir si es **fuente lineal o switching** 📝.

---

### **Proceso de generación de corriente en transformadores** ⚡🧲

* La corriente alterna genera **variación de campo magnético** → induce electricidad en el secundario 🔄.
* Si el transformador no pierde magnetización rápido (alta frecuencia) → no funciona como lineal ❌.
* Ejemplo cotidiano: **destornilladores magnetizados** muestran cómo se mantiene el campo 🛠️🧲.

---

Si querés, puedo hacer un **diagrama visual paso a paso de la rectificación AC → DC** mostrando **diodos, capacitor, regulador** y diferencias entre **lineal vs switching**, para que quede súper claro.

¿Querés que haga eso?

Aquí tienes un **resumen con los puntos más importantes** usando emojis y estructura clara:

---

### **Tipo de corriente en tu circuito** ⚡

* Entrada: **corriente alterna (AC)** de fase y neutro 🔄.
* Salida: **corriente continua punzante (DC pulsante)** tras rectificación ⚡➡️🟢.

---

### **Proceso de rectificación con diodos** ➡️🔧

* **Corriente positiva**: entra por **ánodo**, sale por **cátodo** 🔹.
* **Corriente negativa**: entra por **cátodo**, sale por **ánodo** 🔹.
* Se usa un **puente rectificador de onda completa** para obtener DC en ambos ciclos 🔲.
* Existen rectificadores de **medio ciclo** y de **onda completa con punto intermedio**.

---

### **Medición de voltaje** 🧰

* Con **tester**: medir **voltaje de corriente continua (DC)** en la escala correcta.
* La DC obtenida es **punzante**, no completamente suave sin filtro ⚡.

---

### **Protecciones y filtros** 🛡️

* Filtros tipo **uber**: combinan **diodo + resistencia + capacitor** para absorber energía residual 🔄⚡🟢.
* Evitan que subidas de tensión dañen fotocélulas o elementos sensibles 💡🔥.

---

### **Transformador reductor** 🔻

* Reduce de **220 V AC → 12 V AC** ⚡🔄.
* Siempre trabaja con **corriente alterna** antes de rectificación.

---

### **Seguridad eléctrica** ⚠️

* Sentir **cosquilleo** = circuito no aislado; **aislarse** evita peligro ⚡🖐️.
* CC muy alta → te **quema**; AC → te **sacude** por los ciclos 🔥⚡.
* Fuentes **switching** → no hay AC directa, pero generan **altísimo voltaje** ⚡💥.

---

Si querés, puedo hacer un **diagrama visual de un puente rectificador** mostrando **entrada AC → diodos → salida DC punzante → filtro capacitor**, para que quede clarísimo cómo fluye la corriente.

¿Querés que haga ese diagrama?

Aquí tienes un **resumen con los puntos más importantes** usando emojis para que quede claro y resumido:

---

### **Flujo de corriente en fuentes** ⚡🔄

* **AC → rectificación → filtrado → DC pura** 💡🟢
* **Capacitor**: se coloca en **paralelo** para cargar ambas placas (positiva y negativa) 🔋↔🔋
* **Rizado**: pequeña variación residual en DC; depende del capacitor y su cálculo ⚖️

---

### **Fuentes lineales vs switching** 🔧

**Fuentes lineales:**

* Entrada → **transformador** → rectificación → salida DC 💡
* Primero **bajar el voltaje** con el transformador, luego rectificar 🔻➡️🔋

**Fuentes switching (conmutadas):**

* La AC de 50 Hz **no sirve**; se rectifica inmediatamente ⚡❌
* Puede haber **múltiples salidas**:

  * Una para **circuito integrado / chip** 💻
  * Otra para **relays** (12, 24 o 30 V según fabricante) 🔄

---

### **Relays y control** ⚙️

* El **chip dispara el relay** 🧠➡️🔘
* Componentes como **transistores o triac** permiten usar **voltajes altos** (30 V) con señales bajas (1 V) ⚡➡️💥

---

### **Transformadores especiales** 🧲

* Transformador con **ferrita** = **chopper** 🔹
* Tras rectificación → **no hay frecuencia** ⏱️❌
* Los transformadores requieren **frecuencia para funcionar** 🌀⚡
* DC (como en pilas) **no tiene frecuencia** 🔋

---

### **Resumen técnico práctico** 📝

* Fuente lineal: baja el voltaje primero, luego rectifica.
* Fuente switching: rectifica primero y luego ajusta frecuencia y voltaje.
* Capacitores y filtros ajustan la **suavidad de la DC** y alimentan correctamente chips y relays.
* Para manipular relays y circuitos integrados se usan transistores o triac según voltajes requeridos.

---

Si querés, puedo hacer un **diagrama comparativo visual de fuente lineal vs fuente switching**, mostrando **AC → transformador → rectificación → DC → relays/chip**, para que se vea todo el flujo de manera intuitiva.

¿Querés que haga eso?

Aquí tienes un **resumen con los puntos más importantes** usando emojis y claridad técnica:

---

### **Generar frecuencia en corriente continua (DC)** ⚡🔄

* Para generar frecuencia en DC, se necesita un **generador de pulsos** 🟢⚡.
* Conectar la batería produce un **pulso inicial (chispa)** que genera un campo magnético momentáneo 💥🧲.
* Algunos generadores de pulsos alcanzan **10.000 – 12.000 pulsos por segundo** ⏱️.

---

### **Circuitos integrados y pines** 🧠📌

* Integrados generadores de pulsos usualmente tienen **8 pines** (se cuentan desde la marca izquierda, siguiendo sentido antihorario) 🔢.
* Algunos ICs generan pulsos, otros generan pulsos y **controlan** el circuito.
* **Alimentación**: típicamente **3–5 V**, positivo en un pin y negativo en otro ⚡🟢.

---

### **Corriente y voltajes en bobinado** ⚡🌀

* La corriente DC irá al **bobinado**; el **voltaje pico** de capacitor = **311 V** (equivalente a 220 V AC) ⚡📏.
* No se puede aplicar directamente al circuito; se usa un **transistor MOSFET** para manejar la oscilación ⚡🔧.

---

### **Oscilaciones y conmutación** 🔄

* El MOSFET hace que la **DC oscile** → simula corriente alterna ⚡🔄.
* Con un **núcleo de hierro**, no se puede oscilar; por eso se usan **transistores de ferrita** 🟣.
* En circuitos modernos, los MOSFET pueden estar **integrados dentro del chip**, cambiando la entrada a una pata específica del IC (ej.: pata 6) 🔌.
* Algunos IC ya no usan **8 patas completas**, ahora funcionan con 7 🧩.

---

### **Concepto clave** 📝

* Oscilar/conmutar DC permite que **una corriente continua funcione como AC** para alimentar transformadores y circuitos de fuentes switching ⚡🟢➡️🌀.

---

Si querés, puedo hacer un **diagrama visual de cómo la DC se convierte en pulsos con MOSFET y luego alimenta un transformador de ferrita**, mostrando **entrada DC → generador de pulsos → MOSFET → transformador → IC**. Esto hace que se vea todo el flujo de forma clara.

¿Querés que haga ese diagrama?


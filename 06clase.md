% Clase Nº 6: Relay. Triac: corriente alterna. Mosfet: continua y alterna?. Contactora. Varistor. Termistor. Fuentes. Puente Rectificador. Mosfet. Soldador no funcionó.
% Andrés Imlauer
% 16 Julio 2024
   
### **Problemas comunes en placas electrónicas y fuentes**

* En televisores, ciertos **circuitos integrados fallan por temperatura**, generando problemas recurrentes.
* **Consumo eléctrico = potencia**; siempre hay que tenerlo en cuenta al medir o dimensionar.
* La **fuente siempre necesita dos conductores**: fase y neutro.

---

### **Diagnóstico inicial**

* Lo primero que hay que medir es **continuidad**.
* Los elementos en **paralelo** (switch, pulsador) no cortan la continuidad a menos que haya un corto.
* La **continuidad se rompe en serie**: si un componente falla, todo el circuito se interrumpe.
* Todas las partes que controlan el trabajo suelen estar en **serie**, por eso la continuidad es clave.
* **Conexión directa**: si algo funciona conectado directo, el problema está en la placa o control.

---

### **Componentes y su función**

* **Resistencia → carga**
* **Capacitores → potencia**
* Muchos problemas en **plancha, microondas, secador, licuadora** están en la **fuente o la parte de potencia**.

---

### **Partes de la placa y alimentación**

* La placa tiene dos secciones:

  1. **Control**: trabaja con bajos voltajes (\~3-9 V).
  2. **Potencia**: trabaja con 220 V para alimentar la carga.
* El paso de los **220 V a la carga** puede ser mediante:

  * **Relé / relevadores**
  * **Triac** si no hay relé

---

### **Relés y Triacs**

* **Relé:** funciona por **magnetismo**, activado por bajo voltaje de la placa.
* **Triac:** transistor para corriente alterna.
* **Diac:** rectificador controlado, usado antes para corriente continua.
* Nota: Si la placa da 9 V y el relé es de 30 V, no se dispara.
* En potencia se encuentra principalmente **relé y triac**.

---

### **Notas de placas switching**

* Placas **switching** no manejan voltaje alto; trabajan con **corriente continua hasta 30 V** (como placas de PC).
* La diferencia entre placas **lineales y switching** afecta cómo se entrega la potencia y el control.

---

Si querés, puedo hacer un **diagrama visual simple** que conecte **control → relé/triac → potencia → carga**, para que quede todo clarísimo de un vistazo. Esto suele ayudar mucho para memorizar diagnóstico y fallas. ¿Querés que lo haga?

Aquí tienes un **resumen organizado y destacado** de los puntos más importantes de tu texto:

---

### **1. Relés y contactoras**

* **Relay:** elemento de control en la parte de potencia.

  * Se chequea midiendo la **continuidad de la bobina**.
  * Tiene pines **normalmente abierto (NA)** y **normalmente cerrado (NC)**.
  * Funciona por **magnetismo**.
  * Ejemplo de conexión: 220 V entre pines 1, 4 y 5.
* **Contactora:** relay para **múltiples funciones**, usada especialmente en **trabajos trifásicos** para proteger motores y evitar zumbidos o sobrecargas.
* **Triac:** transistor para **corriente alterna**, sin magnetismo.

---

### **Protecciones y varistores**

* **Varistor:** protege de **sobretensiones**.

  * Colocado en **paralelo** al circuito.
  * Funciona como **PTC o NTC** según coeficiente térmico:

    * PTC: si sube tensión → aumenta la resistencia.
    * NTC: si sube tensión → disminuye la resistencia.
  * Su resistencia es muy alta normalmente (\~1.180.000 Ω), por lo que **la electricidad “no lo siente” hasta una sobretensión**.

---

### **Osciladores y fuentes con MOSFET**

* En fuentes de computadora:

  * La **CC de 311 V** del capacitor va a la bobina del primario.
  * Para proteger la placa, pasa por un **MOSFET** que controla la entrada al oscilador.
  * Componentes clave en la fuente: **puente rectificador, capacitor, chopper, oscilador, MOSFET**.
  * Si el MOSFET está dentro del chip integrado, **hay que cambiar todo el integrado**; si está afuera, solo se cambia el MOSFET.
* Nota: un **capacitor en corriente continua no puede trabajar en serie**, equivaldría a un circuito abierto.

---

### **Diagnóstico de aparatos eléctricos**

* **Problemas comunes dependen de la marca** y condiciones ambientales.

  * Ej.: ciertos televisores o lavarropas tienen fallas repetitivas conocidas.
* Para motores y aparatos con partes mecánicas:

  * Revisar **rulemanes, bujes, ejes** según el ruido o fallo.
  * Ej.: lavarropas de carga superior que hace ruido → desarmar transmisión, aflojar tornillo, revisar.
* Siempre medir **consumo (potencia)** antes de cualquier diagnóstico.

---

### **Principios eléctricos básicos**

* Una **carga necesita fase y neutro** para funcionar con corriente alterna.
* **Continuidad:**

  * Se verifica primero para detectar fallas.
  * Se rompe en **serie** si un componente falla.
  * No se afecta por elementos en **paralelo**, salvo que haya corto.
* **Elementos en serie:** si uno falla, todo deja de funcionar.
* **Elementos en paralelo:** fallos individuales no afectan al resto, excepto cortocircuitos.

---

Si querés, puedo hacer un **diagrama tipo “mapa de control y potencia”** que conecte: **placa → relay/triac → motor/carga → protecciones → continuidad**, para que se vea todo de un vistazo y ayude a memorizar cómo diagnosticar problemas en aparatos eléctricos.

¿Querés que lo haga?


Aquí tienes un **resumen de examen** con los puntos clave de tu texto, organizado de forma clara y directa:

---

### **1. Comprobación de continuidad**

* Primero verificar: **switch, pulsador, térmico, fusible**.
* Herramienta: **tester en escala de continuidad**.
* Procedimiento:

  1. Cerrar la llave del switch, dejar pulsador conectado.
  2. Desenchufar y hacer puente si es necesario (ej.: termostato).
  3. Colocar tester en ambas puntas para medir continuidad.

---

### **2. Diagnóstico de resistencias y bobinas**

* **Resistencias de elementos de trabajo** (plancha, jarra eléctrica):

  * No pueden quedar en corto.
  * Impedancia nueva y usada debe ser casi igual.
  * Valores muy bajos pueden indicar fallo de tester.
* **Bobinas de motores o ventiladores:**

  * Cada bobina es **individual** gracias al esmalte del alambre.
  * Si el esmalte se quema, bobinas se unen → **resistencia baja**, cortocircuito interno.
  * Ej.: ventilador nuevo 18 Ω, quemado 3-5 Ω.
  * Nunca usar cable demasiado grueso que reduzca vueltas disponibles.

---

### **3. Medición directa**

* Si resistencia funciona, se puede **conectar carga en directo**, control manual:

  * Funciona pero **sin control** (ventilador, compresor).
  * No aplicar directo a componentes electrónicos que trabajan a menor tensión que 220 V → explota.

---

### **4. Fallas en fuentes de equipos electrónicos**

* **70% de los problemas** provienen de la **fuente**, porque soporta toda la carga del circuito.
* Transformadores:

  * Se quema casi siempre el **bobinado primario**, nunca el secundario (salvo humedad, cortocircuito o golpes).
* Función de la fuente: **adaptar la fuente a la carga**.

---

### **5. Fusibles**

* Siempre se colocan siguiendo la **capacidad del conductor**, no solo la carga:

  * Ej.: circuito consume 5 A, conductor soporta 2 A → fusible debe ser 2 A, no 5 A.
  * Si el fusible es mayor que el conductor → conductor se quema antes que el fusible.
  * Si fusible es adecuado → protege conductor y evita incendio.

---

### **6. Principios eléctricos básicos**

* Medición de **continuidad** primero para diagnosticar.
* **Conectar directamente** solo si se sabe que la carga soporta 220 V y no hay control electrónico de tensión.
* **Cargas en serie**: falla de un componente → circuito interrumpido.
* **Cargas en paralelo**: falla de un componente → circuito sigue funcionando, salvo cortocircuitos.

---

Si querés, puedo hacer un **esquema paso a paso de diagnóstico de continuidad y pruebas directas** que sirva para **examen práctico**, donde quede claro qué medir primero, cómo medir y cuándo poner directo. Esto suele ayudar mucho para memorizar.

¿Querés que haga ese esquema?

Aquí tienes un **resumen organizado de los puntos clave sobre fuentes, relés, TRIAC y bobinas** que mencionaste:

---

### **1. Fuentes de alimentación**

* **Fuente lineal:**

  * Trabaja con la **frecuencia de la línea** (50 Hz).
  * Utiliza **transformador de hierro al silicio**, que se **magnetiza y desmagnetiza rápido** según los ciclos de la red.
  * Adaptación: convierte 220 V AC a voltajes bajos (ej.: 3 V DC para chips).
  * Problemas comunes: casi siempre están en la **fuente** o en la **parte de potencia**.
* **Fuente switching (conmutativa):**

  * Trabaja a **frecuencias muy altas** (10.000–100.000 Hz).
  * No se puede usar hierro al silicio, se usan **núcleos de ferrita**.
  * Permite reducción de tamaño y potencia más alta que lineal para voltajes >90 V.
* Otros tipos: **capacitiva, resistiva**.

---

### **2. Relés y TRIAC**

* **Relay:**

  * Dispara carga mediante bajo voltaje de control (ej.: 9 V).
  * Peligro: si se usa un relay de 30 V con control de 9 V → no funciona; si es de trabajo continuo, **se quema la bobina**.
  * Tiene 5 pines (entrada de energía, control y salida de carga).
  * Genera un **campo magnético** al energizar la bobina, moviendo el émbolo hacia arriba o abajo.
* **TRIAC:** transistor para **corriente alterna**, reemplaza al relay donde no hay relevadores.
* **DIAC:** rectificador controlado de silicio, usado inicialmente para corriente continua, funciona como conmutador.

---

### **3. Bobinas y funcionamiento magnético**

* **Función de la bobina:** generar **campo magnético**.
* Con émbolo ferroso dentro del campo:

  * El émbolo se mueve según la **polaridad y orientación del bobinado**.
  * Invertir polaridad → el émbolo se mueve en dirección contraria.
* Aplicación:

  * Relés, motores, solenoides.
  * Fuerza generada depende de número de vueltas del alambre y del material del núcleo.

---

### **4. Adaptación de voltajes**

* La **fuente lineal** adapta la tensión de línea (220 V AC) a la requerida por la **placa o chip**.
* Debe respetarse el voltaje nominal de relés y cargas:

  * Ej.: relay de 9 V no puede recibir 30 V de placa switching.
* La parte de potencia siempre se encuentra **desacoplada de la parte de control**.

---

Si querés, puedo hacer un **diagrama visual tipo “fuente → relé/TRIAC → carga”**, mostrando cómo actúa la bobina y el campo magnético, para entender mejor los relés y motores. Esto suele ayudar mucho para examen.

¿Querés que haga ese diagrama?


Aquí tienes un **resumen organizado y destacado** de los puntos clave sobre motores universales, relés, triac y bobinas que mencionaste:

---

### **1. Motores universales en lavadoras**

* Los motores de lavadoras son **universales**, funcionan tanto con **corriente continua como alterna**.
* La **rotación se cambia invirtiendo la polaridad** de la corriente que llega al motor.
* En lavadoras antiguas no se podía invertir la rotación porque no tenían **placa electrónica** que controle la polaridad.
* La placa genera **pulsos con dirección**, controlando la rotación del motor.

---

### **2. Relés y bobinas**

* La **bobina del relay** contiene un **émbolo ferroso** que se magnetiza al recibir corriente.
* Materiales ferrosos (hierro, acero) generan el campo magnético; cobre o bronce no.
* El **campo magnético mueve el émbolo**, venciendo la fuerza de un resorte que mantiene los platinos abiertos.
* **Platinos:** contacto que cierra y abre el circuito cuando se magnetiza el émbolo.
* Aplicaciones: motor reversible, solenoides, bombas.
* **Protección del triac:**

  * Un relay soporta alto voltaje y protege el triac.
  * Un fusible no protege eficazmente un semiconductor porque es demasiado lento.

---

### **3. TRIAC**

* Semiconductor de **corriente alterna**, usado en lugar de relé donde no se requiere fuerza mecánica.
* No puede ser protegido eficientemente con fusible; mejor usar **relay como protección adicional**.

---

### **4. Contactores**

* Similar al relay, pero **para múltiples aperturas y cierres**, usado especialmente en **trabajo trifásico**.
* También se puede usar en monofásica para controlar varias cargas simultáneamente.
* Funciona con **bobina y fuerza magnética**, cerrando y abriendo las cuchillas de contacto.

---

### **5. Funcionamiento eléctrico**

* Para que un relay cierre correctamente:

  * La **bobina debe recibir el voltaje nominal** (ej.: 12 V DC).
  * **Corriente continua**, no alterna.
  * Al quitar alimentación, el resorte abre los platinos.
* Los **extremos de la bobina** se etiquetan A y B.

---

### **6. Calidad de motores y ventiladores**

* La velocidad depende de la **cantidad de polos y espiras de la bobina**.
* Más bobinas, menos espiras → **motor de mala calidad**.
* Menos bobinas, más espiras → **motor de mejor calidad**.
* Ventiladores de techo tienen **reactor con bobina**, ventiladores de piso no.
* Bajando la velocidad de un ventilador, el motor calienta el plástico; térmico abre al calentarse.

---

Si querés, puedo hacer un **diagrama que conecte la placa, relay, triac y motor universal**, mostrando **cómo cambia la rotación del motor** y cómo actúan los platinos y bobina. Esto sirve mucho para memorizar para examen práctico.

¿Querés que lo haga?


Aquí tienes un **resumen organizado y paso a paso** de cómo probar un **relay de 12 V DC** según tu texto:

---

### **1. Condiciones para el relay**

* La **bobina del relay** necesita **12 V de corriente continua** para cerrar.
* Cuando se quita alimentación, el **resorte abre los platinos**.
* Al aplicar los 12 V DC, el **campo magnético vence la fuerza del resorte** y los platinos se cierran.

---

### **2. Medición inicial**

* Primero se mide **continuidad** con tester para verificar que la bobina no esté abierta o en corto.
* Se escucha el típico **“clic”** al energizar la bobina.

---

### **3. Fuente de prueba**

* Para probar el relay se puede usar:

  * **Transformador de 220 V → 12 V AC**, luego un **puente rectificador de 4 diodos** → capacitor para suavizar tensión → DC estable.
  * **Cargadores de herramientas eléctricas** (12 V, 19 V, 5 V, 9 V) porque el relay **consume muy poco**.
  * Una **fuente casera de 12 V DC**.

---

### **4. Procedimiento de prueba**

1. Conectar la bobina a la fuente de 12 V DC.
2. Observar que **el platino normalmente abierto (NA) se cierre** y el **normalmente cerrado (NC) se abra**.
3. Comprobar que el **campo magnético vence la fuerza del resorte**.
4. Verificar la salida:

   * Si se aplican 220 V a la entrada de fase → debe **pasar la corriente a la salida** cuando el relay está cerrado.

---

### **5. Notas importantes**

* Guardar **cargadores fundidos**: sirven como fuentes de bajo consumo para probar relays.
* Los relays no consumen prácticamente corriente, por lo que cualquier cargador con voltaje adecuado funciona.
* La prueba completa consiste en: **alimentar la bobina, observar cierre de platinos y confirmar paso de corriente de entrada a salida**.

---

Si querés, puedo hacer un **esquema visual del circuito de prueba de un relay de 12 V**, mostrando **transformador → puente rectificador → capacitor → bobina del relay → platinos NA/NC → carga**, para que quede todo clarísimo para examen.

¿Querés que haga ese esquema?


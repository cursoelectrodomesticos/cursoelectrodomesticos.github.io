% Clase Nº 7: Diagrama horno eléctrico. Termostato. Selector de velas. Bobinas: arranque y trabajo.
% Andrés Imlauer
% 16 Julio 2024
   
### 1. **Funcionamiento de un aire acondicionado y heladeras**

* Los caños de los evaporadores suelen ser de **aluminio**, lo que los hace sensibles a la humedad.
* Arreglar caños de aluminio con poliuretano es **poco recomendable**, porque se deterioran rápido y deja la impresión de mal trabajo.
* Lo recomendable es **tomar las medidas del evaporador** y comprar uno nuevo (tipo freezer) en casas de repuestos especializadas.

---

### 2. **Seguridad en mediciones eléctricas**

* Tener **mucho cuidado al medir 220 V** con tester.
* No usar la función de continuidad para medir 220 V, porque **se puede dañar el tester**.

---

### 3. **Reparación de hornos eléctricos**

* Lo ideal es **cambiar las dos velas resistivas** al mismo tiempo:

  * Evita que el cliente se queje si la otra se quema.
  * Cubre al técnico en caso de fallas posteriores.
  * Las velas viejas se pueden guardar como repuesto temporal.
* Las resistencias son **dos cuerpos unidos** mediante un conductor de fibra de vidrio para soportar temperatura.
* Si no se pueden comprar por separado, hay que comprar **la vela completa y unirlas con una chapita**.

---

### 4. **Gestión de repuestos**

* Siempre llevar **la mejor pieza** para pedir repuesto y asegurarse de que tenga la misma medida.
* Al pasar presupuestos, incluir **ambas velas** para minimizar problemas futuros.
* Informar al cliente sobre la **posibilidad de que la otra vela se queme** si decide no cambiarla.

---

Si querés, puedo hacer un **resumen todavía más compacto en “tips prácticos”**, para que te quede listo para estudiar rápido o llevar al taller. ¿Querés que haga eso?

Acá te hago un **resumen de los puntos más importantes** del nuevo bloque de texto:

---

### 1. **Velas de horno**

* **No se pueden usar solas**: se necesitan ambas velas juntas para soportar 220 V.
* Si una vela vieja no calienta y las dos nuevas sí, el problema está en el **selector de velas**.
* Para reemplazo de evaporadores o resistencias, **tomar la medida exacta** y comprar el repuesto adecuado (nadie hace la serpentina nueva como se hace en teoría).

---

### 2. **Motores y funcionamiento**

* El **temporizador controla al termostato**.
* En motores, a veces **el rulemán está bien pero la estrella está rota**.
* **Motores universales**: se pueden probar con 12 V, tienen delgas y necesitan carbones.
* Motores controlados por pulsos **no necesitan capacitor** si tienen una sola bobina.
* La bobina de arranque es la que **tiene mayor resistencia (ohm)**.
* Si un motor necesita ayuda para arrancar, **se puede usar un capacitor de arranque**, incluso si originalmente no lo tiene (como en heladeras o splits).
* El capacitor puede conectarse **antes o después del relay**, sin que afecte el funcionamiento.

---

### 3. **Recomendaciones prácticas**

* Comercialmente no conviene “forzar” motores con capacitores, porque puede acortar la vida útil del motor.
* Para uso propio o casos especiales (como una heladera sobrecargada), **sí se puede colocar un capacitor de arranque temporal**.

---

Si querés, puedo combinar **estos dos bloques que me mandaste** y hacer un **resumen final ultra conciso**, con todo lo importante sobre velas, evaporadores, motores y seguridad eléctrica, para tenerlo listo como guía de taller. ¿Querés que haga eso?

Acá te hago un **resumen organizado y destacado** de este último bloque sobre bobinas, capacitores y motores:

---

### 1. **Capacitores en motores**

* Los **capacitores de arranque** se usan para corregir el **desfase** entre corriente y voltaje en motores con bobina de arranque.
* Los **capacitores de trabajo** mantienen el motor en fase durante operación normal.
* Diferencias visuales:

  * Arranque: negro o azul, generalmente dice “capacitor de arranque”.
  * Trabajo: blanco o metálico, no siempre indica su función.
* **Capacitor = condensador**, son lo mismo.
* La **bobina de arranque** casi siempre está por fuera; la de trabajo, por dentro.
* La bobina de arranque **requiere un relay**; la de trabajo, no necesariamente.

---

### 2. **Determinación de bobinas**

* Cada bobina tiene **un principio y un final**.
* Para identificar arranque y trabajo:

  * Medir resistencia de las bobinas.
  * La bobina con **mayor resistencia** es la de arranque.
  * Se identifican colores de cables y se combinan: por ejemplo rojo-azul, azul-marrón, rojo-marrón.
* En motores universales: se pueden probar con 12 V.

---

### 3. **Cálculo y función del capacitor**

* El **valor del capacitor** depende de la **impedancia inductiva de la bobina** y el desfase que se quiere corregir.
* No se puede poner un valor “cualquiera”: tiene que **corregir la fase sin sobrecargar el motor**.
* El capacitor adelanta o retrasa la corriente para **mantener voltaje y corriente en fase**, evitando pérdida de potencia y recalentamiento.
* En motores con dos bobinas en paralelo: se produce **fuera de fase**, que aumenta consumo y reduce potencia; se corrige con un capacitor.

---

### 4. **Relay y amperaje**

* El **relay debe coincidir con el amperaje del motor**:

  * Si es mayor, tarda en accionar.
  * Si es menor, corta rápido.
* En heladeras normalmente hay relay y no capacitor. Capacitores más grandes (1/4 HP en adelante) están llegando al mercado.

---

### 5. **Prácticas y precauciones**

* Antes de reemplazar o probar: medir correctamente resistencia y asegurarse de **tomar punto común y fase correctamente**.
* La experiencia es clave para determinar **cuándo usar capacitor y qué valor exacto**.
* La teoría explica que la impedancia capacitiva corrige la inductiva; esto **no se improvisa**, se calcula según el motor.

---

Si querés, puedo armarte un **resumen único de todos los bloques que me mandaste**, en formato **“guía de taller: velas, evaporadores, motores y capacitores”**, todo listo para repasar rápido. Esto dejaría todo en un solo documento práctico.

¿Querés que haga eso?

Acá te hago un **resumen organizado y destacado** del último bloque sobre motores, capacitores y factor de potencia:

---

### 1. **Bobinas en paralelo y potencia**

* Cuando un motor tiene **dos bobinas en paralelo**, las inductancias se afectan entre sí y se pierde potencia.
* Esto provoca **mayor consumo y recalentamiento** si no se corrige la fase.
* La corrección se hace con **capacitores de arranque o de trabajo**, según corresponda.

---

### 2. **Capacitor y factor de potencia**

* El capacitor **corrige el factor de potencia** adelantando o retrasando la corriente para que coincida mejor con el voltaje.
* Nunca corrige al 100%; siempre hay **pérdidas y ruido**, pero mejora eficiencia.
* Un capacitor demasiado grande puede **quemarse** porque soporta más carga de la que debería.
* El **capacitor ideal** es el que genera **el menor amperaje** en el motor.
* Medir el amperaje es la forma práctica de comprobar si el capacitor es correcto.

---

### 3. **Tipos de motores**

* Motores con **bobina de arranque**: requieren relay.
* Motores sin bobina de arranque (por ejemplo, aire acondicionado split): **no requieren relay**, pero sí pueden tener capacitor de trabajo.
* En todos los motores: la experiencia y medición correcta son clave para determinar si se necesita capacitor y cuál es su valor.

---

### 4. **Prácticas y seguridad**

* Medir con **pinza amperométrica** para confirmar consumo.
* Lo ideal es que el motor consuma exactamente lo que corresponde a su potencia nominal (1000 W → 1000 W de consumo).
* No improvisar con capacitores más grandes: puede **disparar y quemar el motor**.

---

Si querés, puedo hacer un **resumen final de todo lo que me mandaste hasta ahora**, combinando **velas, evaporadores, bobinas, motores y capacitores**, en un **guía práctica de taller**, para tenerlo todo en un solo documento listo para estudio o uso en reparaciones.

¿Querés que haga eso?

Acá te hago un **resumen organizado y destacado** del último bloque que enviaste:

---

### 1. **Relay y motor**

* Se puede poner un **relay multimétrico** a un motor que tenga problemas de arranque.
* El relay permite que el **capacitor de arranque** funcione solo durante el arranque y luego se desconecte.
* Ejemplo práctico: un aire acondicionado que no arranca puede funcionar agregando capacitor y relay, aunque **es costoso**.

---

### 2. **Capacitores según tipo de motor**

* **Capacitor de trabajo:**

  * Lavarropas: \~16 µF
  * Motores grandes: hasta 80 µF
  * Heladera: 5–8 µF
* **Capacitor de arranque:**

  * Generalmente >70 µF
* **Voltaje de capacitores:** indica **el límite que soporta el aislante**.

---

### 3. **Motores inverter**

* La corriente inverter transforma **monofásica a trifásica** mediante un circuito integrado + potenciador.
* Motor trifásico “común” adaptado con capacitor **funciona, pero el bobinado no durará**.
* Los motores para inverter están diseñados específicamente para la **amplitud y desfase de esa corriente**.

---

### 4. **Jarra eléctrica**

* Termostato de arriba: **corte principal**, si falla corta para siempre.
* Termostato de abajo: **seguridad**, si falla se puede puentear temporalmente.
* No hay chips que trabajen directamente a 220 V.

---

### 5. **Hornos eléctricos**

* Las velas de arriba son más importantes; recomendable **quedarse con las velas originales** como repuesto.
* El **termóstato** controla la temperatura y las velas, mientras que el **temporizador** controla el encendido del horno.

---

Si querés, puedo armar un **resumen definitivo de todo lo que me mandaste hasta ahora**, combinando:

* Velas y hornos
* Evaporadores y heladeras
* Motores (bobinas, arranque, trabajo)
* Capacitores (arranque, trabajo, valores, relays)
* Seguridad y prácticas de taller

De manera que quede **una guía práctica completa** lista para estudio o uso en reparaciones.

¿Querés que haga eso?



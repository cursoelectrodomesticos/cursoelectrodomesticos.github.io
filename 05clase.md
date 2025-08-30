% Clase Nº 5: Lavarropas y Termotanque. Triac. Mosfet. Osciladores. Fabricar plástico para nivel el succionador (fallo común).
% Andrés Imlauer
% 16 Julio 2024
   
### 🧺 Lavarropas

* ⚖️ Auto-balance: por eso **no conviene lavar zapatillas** en la lavadora.
* 🔧 Se hizo cambio de **amortiguadores**.
* 🖥️ Placa vs periféricos: los periféricos son todos los otros componentes.
* ⚡ Componentes en la placa (menos sensores) trabajan con **220V**.
* 🔒 Blocapuertas: comunica a la placa que está bloqueada → permite **cargar agua**.
* 💧 Electroválvula / solenoide de carga: controla entrada de agua.
* 🧪 Presostato: importante para control de nivel de agua.
* ⚠️ Revisar: solenoide, bomba de agua, presostato, porque **pueden quemar la placa**.
* 🔀 Triac = transistor de **corriente alterna**, reemplaza al diac.
* 🔋 Mosfet: semiconductor de óxido metálico, usado en **fuentes switching**.
* 🌀 Fuente switching: tiene **oscilador + mosfet**, rectifica y nivela ondas con capacitor.
* 🌐 Aislación galvánica: tierra del primario ≠ tierra del secundario.

---

### ⚡ TRIAC

* 🔌 Interruptor electrónico para **corriente alterna**.
* 📛 TRIAC = TRIode for Alternating Current.
* 🔄 Funciona como un transistor en CC pero para **CA**.
* 🤏 Corriente de activación se aplica en la **puerta (Gate)**.
* ⏹ Corriente fluye hasta que caiga por debajo de un **umbral**.
* 🔁 Se usa como **alternativa a relé**.

---

Si querés, puedo hacer **un diagrama visual con emojis** que conecte lavarropas, bloque puertas, electroválvula, presostato y triac para que se entienda el flujo de señal y corriente. Esto ayuda mucho para estudiar.

¿Querés que haga eso?

Aquí va un resumen visual y con emojis de los puntos más importantes que mencionaste, incluyendo el MOSFET y el procedimiento de reparación de lavarropas:

---

### 🔹 MOSFET

* 🧪 **Transistor de efecto de campo metal-óxido-semiconductor**.
* ⚡ Se usa para **amplificar o conmutar señales**.
* 🏭 Muy utilizado en **circuitos analógicos y digitales**.
* ⚡🔄 Ventajas: **conmutación rápida, baja resistencia, bajo costo, alta durabilidad térmica**.

---

### 🧺 Lavarropas – Procedimiento de inspección y desarme

* 👀 **Primero**: inspección visual para detectar algo suelto o roto antes de conectar.
* ⚠️ **No testear con tester al azar**, puede empeorar el problema.
* 🔧 Problemas frecuentes: **amortiguadores** si se sacude mucho.
* 🚪 La **puerta** conviene mantener cerrada para no romperla.
* 🏗️ **Desarme**: sacar la **mesa de arriba y tapa trasera** con cuidado.
* 🛠️ Tornillería: generalmente **tuercas 1/4" (6.5 mm) hexagonal**, cómoda de manipular.
* ⚠️ Partes delicadas: algunas tapas o piezas cristalizadas se rompen con calor/frío.
* 🔄 Sistemas de enganche: algunas tapas se corren hacia adelante, otras hacia atrás, hay que hacer movimientos suaves para no romper.
* 🔌 **Periféricos**: todos los componentes aparte de la placa principal, **son los que se reparan**.
* ⚡ La mayoría trabajan con **220V**, excepto sensores.
* 🔧 Prueba de componentes: **desenganchar y probar con pinzas de 220V** si se sabe qué hacer.

---

### 🔒 Blocapuertas

* 🚪 Función principal: **controlar la puerta**.
* 🔄 No tiene otra función eléctrica.
* 🔧 Se puede **puentear para engañar a la placa** y probar funcionamiento del lavarropas.

---

Si querés, puedo hacer un **diagrama de flujo del lavarropas con blocapuertas, MOSFET y periféricos**, mostrando cómo fluye la señal y la corriente. Esto hace que todo quede clarísimo para estudiar.

¿Querés que haga ese diagrama?

Perfecto, vamos a resumir todo esto en los **puntos más importantes con emojis** para que quede claro y fácil de estudiar:

---

### 🔥 Termostato y Blocapuertas

* 🌡️ **Termostato**:

  * Común (1) → entrada de fase (220V).
  * Contiene un **PTC** que al calentar bloquea el switch.
  * Una vez que se bloquea, cierra el **switch** y el circuito queda en serie.
* ⚠️ **Precaución**: al puentear, respetar **fase y neutro**, sino puede haber explosión.
* 🔒 **Blocapuertas**: comunica a la placa que la puerta está cerrada y activa:

  * **Presostato**
  * **Solenoide de carga**

---

### 💧 Solenoide de carga / Electroválvula

* 1 solenoide por lo general.
* Función: **recibir señal de la placa y permitir ingreso de agua**.
* Orden de carga: se activa primero la **válvula azul**, luego el resto en diagonal.

---

### 🧴 Dispenser – Jabón y suavizante

* 💧 Bandejita ajustable: para **jabón líquido o en polvo**.
* 🔧 Trabita de plástico: controla **caída por gravedad** para que el agua mezcle correctamente el detergente.
* ⚖️ Dosificación:

  * Jabón líquido → máximo hasta la bandeja indicada, no sobrecargar.
  * Agua y detergente → mezcla más soluble y homogénea.

---

### 🔄 Flujo resumido

1. 🚪 Puerta cerrada → blocapuertas activa switch térmico.
2. ⚡ Se confirma circuito → placa permite carga de agua.
3. 💧 Solenoide de carga abre → agua ingresa al dispenser.
4. 🧴 Dispenser distribuye jabón líquido o en polvo según bandejita.
5. 🔄 Agua mezcla detergente correctamente para iniciar lavado.

---

Si querés, puedo hacer un **diagrama visual tipo flujo de agua y señales eléctricas con emojis**, mostrando **puerta → blocapuertas → presostato → solenoide → dispenser**, que queda clarísimo para estudiar.

¿Querés que haga ese diagrama?


Perfecto, vamos a resumir toda esta explicación del **funcionamiento del lavado y del dispensador** con emojis para que quede muy claro:

---

### 💧 Funcionamiento del jabón y agua

* ↔️ **Carga cruzada**: el agua entra de forma diagonal para mezclar correctamente con detergente.
* ⏸️ **Pausa y recarga**: si la ropa necesita más jabón líquido, poner pausa y recargar **máximo 2 veces**.
* ⚠️ No sobrecargar: exceso de jabón líquido **decanta mal** y dificulta la succión.
* 🌬️ Aire y decantación: el agua necesita **filtración de aire** para caer correctamente, como un valde que chupa aire al vaciarse.

---

### 🌊 Ciclo de entrada de agua

* 1️⃣ Primera manguera → carga inicial de agua y detergente.
* 2️⃣ Segunda manguera → carga final, hasta que el **presostato indique nivel correcto**.
* ⏱️ Agua cae un minuto aproximadamente al inicio para **alivianar el líquido** antes de lavar.

---

### 🧼 Tipos de limpieza

* 🍋 **Vinagre blanco** → limpia y deja aroma especial.
* 🧴 **Jabón líquido** → más rápido, pero **destruye la estrella del agitador**.
* 🧹 **Jabón en polvo** → más lento, también desgasta la estrella con el tiempo.
* ⭐ **Estrella** = sistema dentro de la tina que hace girar la ropa.

---

### ⚙️ Dispensador y electroválvulas

* 3 compartimientos, pero **solo 2 electroválvulas**.
* 💻 Sistemas electrónicos fijan la secuencia según el **programa de la placa**.
* 🔀 Lavadoras mecánicas antiguas tenían 1 válvula y un sistema de redirección manual.
* ⚡ Problema frecuente: lavarropas funciona bien, pero **no dispensa suavizante**.

---

Si querés, puedo hacer un **diagrama visual tipo flujo con emojis** mostrando **agua → mangueras → presostato → dispensador → estrella → ropa**, con el jabón líquido/polvo y el suavizante incluido. Esto ayuda muchísimo para memorizar cómo funciona todo el sistema.

¿Querés que haga ese diagrama?

Perfecto, aquí va un **resumen con emojis** de todo lo que mencionaste sobre **electroválvulas, presostato, bomba y amortiguadores**, para que quede claro y fácil de estudiar:

---

### 💧 Electroválvulas y flujo de agua

* ⚠️ Problema frecuente: una electroválvula no funciona → agua va solo a un lado.
* 🔌 Verificación: medir con **220V** usando **chicote de prueba** (interruptor y pinzas).
* 🧲 Solenoide: trabaja por **campo magnético** → émbolo abre/cierra paso del agua.
* ⏹ La placa corta corriente cuando el **presostato indica nivel correcto**.
* 💡 Tip extra: bajo consumo → se puede probar con timer para riego de jardín.
* 💦 Prueba práctica: manguera abierta → activar 220V → agua sale si funciona.

---

### ⚙️ Presostato

* 🌊 Controla **nivel de agua**: detecta cuando falta o sobra.
* 🔁 Hay muchos tipos, pero todos funcionan similar.
* 🔄 Compatible con varias electroválvulas, aunque algunas sean distintas para compra.

---

### 🛠️ Instalación y medición

* 🔧 Primer enganche: **aletas y pines afuera**, luego girar para fijar.
* ⚠️ Verificar que no esté incómodo o forzado, ajustar antes de medir o colocar.

---

### 🚿 Ciclo de lavado

1. 💧 Carga de agua con jabón (primer y segundo ciclo).
2. 🌀 Lavado normal.
3. ⏹ Pre-centrifugado para descartar agua con jabón y suciedad.
4. 💦 Enjuague 1 y 2.
5. 🧴 Suavizante → final de ciclo.

* ⚠️ Peligro: lavarropas puede **deslizarse**, usar **cajón de apoyo** para seguridad.

---

### 🏗️ Bomba de agua

* ⬇️ Ubicada en la parte inferior → saca el agua.
* 🛠️ Eje de acero inoxidable soldado al imán → difícil de reparar sin romper.
* 💡 Experimentos frecuentes de reparación: eje desgastado, rotor dañado.

---

### ⚙️ Amortiguadores

* ⚙️ No tienen resorte ni líquido → solo cilindro que debe estar duro.
* 🔧 Se puede “engrasar” ligeramente, pero no demasiado.
* ⚠️ Problema frecuente: sacudida de lavarropas → generalmente **amortiguadores**.
* 🔄 Compatibles entre la mayoría de los modelos, tienen **pequeño freno interno**.

---

Si querés, puedo hacer un **diagrama visual completo del flujo de agua y ciclo del lavado**, integrando:
**electroválvulas → presostato → dispensador → bomba → centrifugado → suavizante → amortiguadores**, con emojis para que se vea todo el proceso de forma didáctica.

¿Querés que haga ese diagrama?


Perfecto, Magomed. Vamos a resumir **todo este bloque** en los puntos clave con emojis y resaltar la relación entre **lavarropas, electrónica y fuente switching**, porque es mucha información técnica:

---

### 🛠️ Amortiguadores y rulemanes

* 🔧 Amortiguadores: solo un **cilindro con retén de silicona**, sin tecnología, sirven para **controlar sacudidas**.
* 🪛 Resortes de arriba: se cambian solo si están rotos; medidas casi siempre estándar.
* ⚙️ Rulemanes:

  * Lado interno → retén.
  * Se cambian cuando el **retén pierde precisión y filtra agua**, daña el rulemán.
  * Se accede quitando el **puente** y resorte del tambor.

---

### 🔩 Tornillería y dispenser

* Tornillos especiales: cubrir con **trapito** para que no caigan dentro de la caja.
* ⚠️ No reemplazar con tornillos más grandes → puede romper el plástico.
* Guardar tornillos pequeños en **cajita tipo Tiktak**.

---

### 🔒 Blocapuertas, solenoide y bomba

* 🔌 Estos tres son críticos → **pueden quemar placa**.
* Verificar antes de cambiar la placa:

  * Blocapuertas
  * Solenoide
  * Bomba de agua
  * Presostato
* Blocapuertas funciona con 220V → necesita TRIAC para ser activado por la placa.

---

### ⚡ TRIAC y DIAC

* TRIAC = **transistor para corriente alterna** → controla 220V de carga.
* DIAC → solo para corriente continua, reemplazado por TRIAC.
* Dos diodos opuestos permiten pasar ambos ciclos de corriente alterna.
* ⚠️ Importante: el chip debe entregar suficiente voltaje para disparar el TRIAC.

---

### 🧪 MOSFET y fuentes

* MOSFET = transistor de óxido metálico → trabaja **en fuentes switching**.
* Fuente lineal → rectifica y luego transforma voltaje.
* Fuente switching → rectifica y luego oscila de **10.000 a 100.000 Hz**.
* Oscilador de 8 patitas + MOSFET → controla voltaje bajo y alta frecuencia.
* ⚠️ Diferencias de tierra: **aislación galvánica** entre primario y secundario.
* Salida de transformador → positivo al devanado y negativo al chasis para oscilar correctamente.

---

### 🌐 Flujo resumido en la fuente switching

1. ⚡ Rectificación → corriente continua.
2. 🌀 Oscilador + MOSFET → alta frecuencia.
3. 🔋 Capacitor → nivela ondas.
4. 🔄 Transformador → lleva corriente a secundario manteniendo aislación galvánica.
5. 📡 Conexión al integrado que oscila → alimenta secundario correctamente.

---

Si querés, puedo armar **un diagrama completo con emojis** que combine:
**lavarropas → blocapuertas/solenoide/bomba → TRIAC → MOSFET → fuente switching → transformador → circuito de alta frecuencia**, para que se vea **el flujo eléctrico y mecánico** de principio a fin.

¿Querés que haga ese diagrama?





Perfecto, Magomed. Vamos a resumir este bloque con **puntos clave y emojis**, destacando **oscilador, MOSFET, blocapuertas y amortiguadores**, y la relación mecánico-eléctrica:

---

### 🌀 Oscilador y MOSFET

* 🎛️ Oscilador integrado de 8 patitas → genera frecuencia de trabajo (\~15.000 Hz).
* 🔋 Componentes alrededor (resistencias y capacitores) → determinan frecuencia final.
* ⚡ MOSFET → actúa de **intermediario** porque el chip no soporta 311V.

  * Puerta del MOSFET recibe señal del oscilador.
  * Conecta una pata a tierra y la otra al transformador.
* 🔍 Dentro de fuentes switching modernas → MOSFET puede estar **dentro del integrado**.

---

### 🔒 Blocapuertas

* ✅ Función: asegurar la puerta, prevenir accidentes (niños), aunque casi imposible que entre alguien.
* ⚠️ Problema: quema placa si falla.
* 🔧 Solución temporal (puentear): unir los dos cables marrones → el lavarropas “cree” que la puerta está cerrada.
* 🔌 No se puede hacer lo mismo con **bomba o solenoide** → necesitan corriente real para funcionar.
* 🔄 Blocapuertas nuevo → viene **sin cable**, hay que conectar correctamente.
* 🔢 Correcta conexión: números 1, 2, 3 → 1 es común, 2 calienta pastilla, 3 va a la placa.

---

### 🛠️ Amortiguadores

* 📍 Ubicar agujerito → contar orificios para compatibilidad (3 orificios recomendados).
* 🔩 Colocar perno + tuerca + arandela → apriete normal, sin fuerza excesiva.
* 👌 Lengueta → empujar con cuidado para que el amortiguador quede firme.
* 🛒 Dónde comprar: varias tiendas en Uruguay, San Lorenzo, Santa Fe, San Martín, etc.

---

### 🧴 Lavado y controles

* ⏱️ Programas → elegir tiempo y tipo de ropa.
* 👖 Delicados (ropa fina) → usar opción “lavado a mano”.
* 🔄 Lavado con ropa mezclada (jean + delicada) → no recomendado.
* ⚙️ Control de centrifugado y temperatura ajustable → depende del programa elegido.

---

### 🔧 Tips prácticos

* 🚫 No sacar tapa mientras está en funcionamiento → peligro.
* ⚠️ Revisar conexiones x1, x2, … x10 antes de desmontar o puentear.
* 🟢 Primero verificar mecánica y amperajes antes de enchufar para no dañar placa o componentes.

---

Si querés, puedo armar **un mega-diagrama resumido con emojis** de todo el ciclo del **lavarropas desde la puerta, agua, solenoide, bomba, TRIAC, MOSFET y fuente switching**, combinando la parte mecánica y eléctrica de todo lo que me enviaste hasta ahora. Esto te serviría como guía visual completa.

¿Querés que haga ese diagrama?

Perfecto, Magomed. Vamos a organizar todo este bloque en **resumen técnico y puntos clave** para que quede más claro, integrando la parte mecánica, eléctrica y de diagnóstico de lavarropas:

---

### 🔹 Orden de operación inicial

1. **Blocapuertas** se bloquea primero ✅ → asegura que la puerta esté cerrada.
2. **Carga de agua** mediante los dos solenoides de carga 💧.

   * Se prueba cada solenoide y la bomba antes de continuar.
   * Agua de los solenoides choca en el centro → correcta distribución.
3. **Testeo de bomba y solenoides**: si falla, se marca error.
4. Dependiendo de la ubicación de tornillos, se **saca el tambor por arriba o por abajo**.

---

### 🔹 Medición eléctrica

* Tester común vs tester avanzado ⚡:

  * Tester avanzado detecta **campo magnético en corriente alterna**.
  * Corriente continua → tester común no tiene problema.
* Fuente resistiva: tiene **resistencia + capacitor** → sirve para bajar de 220V al voltaje del chip.

---

### 🔹 Componentes mecánicos

* **Estrella del tambor**: puede romperse con jabón líquido.
* **Rulemanes**:

  * Ruido fuerte → rulemán roto.
  * Sin ruido → posible estrella rota.
  * Comprobación: mover el tambor o la tina para detectar el origen del ruido.
* **Chasis y chapa**: si se rompe, reparar con remaches, no soldadura.

---

### 🔹 Ciclo de lavado

1. Lavar → carga de agua y detergente.
2. Centrifugado previo → balance automático (AB) para evitar sacudones.
3. Enjuague y suavizante → se activa según la placa y electroválvulas.
4. Centrifugado final → cuidado con zapatillas y ropa delicada para evitar desbalance.

---

### 🔹 Notas de diagnóstico

* Blocapuertas quemado → se puede puentear temporalmente (marrones unidos).
* Bomba o solenoide defectuoso → **no se pueden puentear**; necesitan corriente real.
* Revisión antes de enchufar → evita quemar placa.
* Si falla la estrella o los rulemanes → revisar visualmente y manualmente.

---

### 🔹 Experiencia del profesor

* Aprender cable por cable y entender la función de cada componente.
* Los manuales no enseñan la experiencia real de reparación.
* Decisión de precios según dificultad o cliente “complicado”.
* Método práctico: prueba, observación y medición antes de reemplazo.

---

Si querés, puedo hacer ahora un **diagrama paso a paso del ciclo del lavarropas**, desde **blocapuertas → solenoides → bomba → centrifugado**, incluyendo **cómo interactúan TRIAC y MOSFET en la placa**. Esto te daría una visión **global mecánico-eléctrica** del equipo.

¿Querés que haga ese diagrama?



Perfecto, Magomed. Vamos a organizar este bloque sobre **termotanques y lavadoras semiautomáticas** de forma técnica y clara:

---

### 🔹 Protección y mantenimiento del termotanque

* Se puede aplicar **brea** en el interior del tanque:

  * Objetivo: que las sales y minerales del agua se adhieran a la brea en vez de corroer el tanque.
  * Actúa como una **protección contra la oxidación**.

---

### 🔹 Termostato

* Funciona como un **switch térmico**:

  * **Normalmente cerrado (NC)** → deja pasar corriente mientras no alcanza la temperatura deseada.
  * Se abre cuando se alcanza la temperatura → corta el paso de corriente.
* Se debe medir con **tester** o continuidad:

  * Si está pegado y no corta → el agua puede hervir → **hay que cambiarlo**.
* Se controla con **pinza amperométrica**:

  * Corriente típica: 9–10 A.
  * Debe caer a 0 A cuando el termostato abre.
* No hay **campo magnético**, funciona solo por temperatura.

---

### 🔹 Medición y diagnóstico

* Medir resistencia de la **resistencia calefactora**: verificar continuidad.
* Medir termostato: continuidad en frío, apertura al alcanzar temperatura.
* Si falla el termostato → riesgo de sobrecalentamiento o hervido del agua.

---

### 🔹 Semiautomático

* Función: **enguaja y desagota**, no centrifuga.
* Resultado: ropa húmeda → normal en este tipo de lavarropas.
* Centrifugado más rápido → ropa más seca pero más arrugada.

---

### 🔹 Trifásico (aplicable a lavadoras industriales o cámaras frigoríficas)

* Fases: R, S, T (o U, V, W).
* Problema: si el motor gira en dirección incorrecta → cambiar dos fases.
* Si no se tiene detector de fase → probar intercambio de polos.

---

Si querés, puedo hacer un **diagrama comparativo entre termotanque, semiautomático y trifásico**, mostrando **circuito de corriente, termostato y resistencia**, para que quede todo visual y fácil de recordar. Esto integraría la parte eléctrica con la mecánica y el mantenimiento.

¿Querés que haga ese diagrama?



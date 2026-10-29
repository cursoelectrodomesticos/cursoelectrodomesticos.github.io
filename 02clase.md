% Clase Nº 2: Ventiladores, armado de lámpara serie y jarra eléctrica
% Andrés Imlauer
% 16 Julio 2024

## Audio de la clase:

[https://www.youtube.com/watch?v=3nJnAqAZQpY](https://www.youtube.com/watch?v=3nJnAqAZQpY)

[https://vocaroo.com/1jjk6YDCw6js](https://vocaroo.com/1jjk6YDCw6js)

### O miralo desde una instancia de invidious

[https://redirect.invidious.io/watch?v=3nJnAqAZQpY](https://redirect.invidious.io/watch?v=3nJnAqAZQpY)



Aquí te destaco los puntos más importantes de todo lo que compartiste, en forma clara y resumida:

---

### 🔧 Motor y ventilador

* El **ventilador se calienta** porque el motor está frenado y trabaja exigido → mayor consumo de potencia → aumenta el amperaje.
* Puede deberse a que el **rotor no está centrado en el estator**, lo que genera rozamiento y mal funcionamiento.
* El **estator debe tener una película de luz** (pequeño espacio de aire) para que el campo magnético actúe correctamente.
* Revisar que los **esparragos (tornillos de fijación)** estén bien ajustados; algunos motores permiten centrar el rotor con sondas.
* **Regla general:** no poner en marcha nada hasta controlar el centrado del sistema.

---

### ⚡ Monofásico y trifásico

* En **viviendas → monofásico** (1 fase + neutro).
* En **locales e industrias → trifásico** (3 fases + neutro).
* En instalaciones trifásicas hay que **medir cada fase** y equilibrar cargas.
* El **neutro es indispensable** para cerrar el ciclo de trabajo; sin él los electrones no completan el circuito.

---

### 🔌 Identificación de conductores

* En **corriente alterna** los cables se identifican como **fase y neutro**, no positivo y negativo.
* La fase alterna entre positivo y negativo en cada ciclo (50 Hz).
* Con un **buscapolo**: si enciende → es la fase; si no enciende → neutro.

---

### 🔋 Cargas eléctricas

* Una **carga resistiva** puede ser: bobina de motor, estufa, ducha, ventilador, etc.
* Diferencia:

  * Estufa → carga resistiva pura.
  * Ventilador → motor (comportamiento distinto, no es lineal).
* La corriente entra por la fase y retorna por el neutro, pero el ciclo que regresa está invertido.

---

### 📏 Medición de consumo (Pinza amperométrica)

* Instrumento clave para verificar el **consumo real de amperaje** de una carga.
* Ejemplo: si un motor debe consumir **5 A**, pero mide **7 A → está mal** (exceso de consumo).
* Valores cercanos (ej. 5,2 A) son aceptables.
* Considerar el **régimen de trabajo**:

  * Motor en vacío consumirá menos.
  * Una heladera antes de cargar gas puede medir 4,2 A; al trabajar con gas subirá a 5 A.
* Cada aparato tiene su consumo esperado: **un ventilador no consume 5 A**, su consumo es menor.

---

¿Querés que te lo arme en **formato de apuntes esquemáticos tipo examen** (con viñetas más cortas y conceptos clave) para que lo uses como repaso rápido?

Perfecto 👌 Te hago un **resumen con los puntos más importantes y claros**, así lo podés usar como guía de repaso:

---

### ⚡ Relación Tensión – Corriente – Potencia

* La **tensión siempre es 220 V** (en instalaciones domiciliarias).
* Lo que varía es el **amperaje** según la carga.
* La **potencia (W)** depende de la tensión × corriente:

  * Ejemplo: **1 A ≈ 220 W**.

---

### 🔧 Motores y ventiladores

* El motor del ventilador se calienta si:

  * Está **exigido** (ej: bujes gastados).
  * El **rotor no está bien centrado en el estator** (debe existir una “película de luz” para que el campo magnético actúe bien).
* Si consume **más amper de lo normal** (ej: 6 A en lugar de 4 A) → está forzado.
* Si consume **menos amper de lo esperado** → puede que el motor no esté trabajando como debe.
* Lubricante recomendado: **líquido hidráulico de freno** (mejor resultado que otros aceites).

---

### ❄️ Caso heladera (motor de compresor)

* Si al cargar gas sigue consumiendo **4 A en lugar de 5 A** → está mal porque el motor no está comprimiendo.
* Causas posibles:

  1. **Pistón con fuga** dentro del cilindro (no llega a presión).
  2. **Flapper de alta con hollín/aceite** → no cierra bien y hay pérdida de presión.

---

### 🧲 Corriente y campo magnético

* **Corriente alterna (CA):** genera campo magnético constante (50 Hz).
* **Corriente continua (CC):** no genera campo magnético estable; solo un “mini campo” al conectar/desconectar.
* La electricidad en generadores se produce por **campos magnéticos**.
* La batería produce electricidad por **reacción química** (acumulador ≠ generador).
* Los electrodomésticos funcionan gracias al **campo magnético generado por la corriente alterna en bobinas**.

---

### 🔍 Conceptos clave

* **Buscapolo**: debería llamarse *busca fase*, porque detecta fase, no polo.
* **Amperímetro**: para medir corriente directa se coloca **en serie** con la carga.
* **Cortocircuito**: ocurre cuando no hay resistencia → el voltaje no cae → salta fusible o disyuntor.
* **Trabajo eléctrico**: existe cuando la corriente pasa por una carga resistiva (ej: estufa, motor, lámpara).
* **Diferencia**:

  * Circuito normal → hay resistencia → hay trabajo.
  * Cortocircuito → no hay resistencia → protección actúa.

---

👉 Si en un tester medís **continuidad en la bobina** → significa que la bobina no está cortada y puede repararse.

---

¿Querés que te arme un **esquema tipo mapa conceptual** (con flechas y relaciones entre tensión, corriente, potencia, campo magnético, cargas, etc.) para que lo tengas más gráfico?

Excelente material 👌 Te lo resumo en **puntos clave bien organizados** para que tengas un apunte claro sobre **bobinados, alambre esmaltado y funcionamiento del motor**:

---

## 🧲 Bobina y campo magnético

* La **bobina** se hace con **alambre esmaltado (alambre magneto)**.
* El esmalte sirve como **aislante térmico y eléctrico**, evitando que los hilos hagan masa entre sí.
* La función de la bobina:

  * **Generar campo magnético** en el estator.
  * Este campo induce otro en el rotor → ambos se repelen (como imanes) y producen el giro.
* Sin bobina no hay fuerza → no se mueve nada.

---

## 🔌 Conductores y alambres

* Los **primeros conductores eran monofilamento** (un solo hilo).
* Hoy se usan **multifilamento** (más maniobrables y flexibles).
* El alambre para bobinar: **finito, esmaltado, resistente al calor**.
* No se puede usar un cable común porque:

  * Es muy grueso y no entran las vueltas necesarias en la ranura (≈ 10 mm).
  * No soporta las temperaturas del bobinado.

---

## 🔥 Fallas y sobrecalentamiento

* Cuando se recalienta el bobinado:

  * El **esmalte se quema** → los hilos se unen → baja la resistencia → aumenta la corriente → efecto de cortocircuito parcial.
* Resultado: más consumo de amperes, pérdida de campo magnético y finalmente motor quemado.

---

## 🔧 Rebobinado de motores

* Pasos:

  1. **Cortar el bobinado viejo**.
  2. **Contar las puntas** que se cortan.
  3. **Anotar cantidad de vueltas**.
  4. **Medir el calibre del alambre** (con micrómetro).
  5. **Pesar una muestra** (ej: 100 g) y comprar más (ej: 120 g).
  6. Bobinar con la **misma cantidad de vueltas** y **mismo calibre**.

---

## ⚖️ Calibre del alambre

* **No debe cambiarse nunca**.
* Si se usa **más grueso**:

  * Menor resistencia → más velocidad → pero calienta más → riesgo de quemarse.
* Si se usa **más fino**:

  * Mayor resistencia → menor voltaje efectivo → menos velocidad.
  * Se calienta menos, pero el motor pierde rendimiento.
* El **núcleo del motor determina la potencia** y, a partir de ahí, el calibre adecuado del alambre.

---

## ⚡ Conceptos adicionales

* **Serie**: cuando la corriente pasa por un componente y después por otro en una misma línea (ej: lámpara en serie).
* **Buscapolo**: permite identificar la **fase (vivo)** porque enciende; en el neutro no.
* Ejemplo: para identificar en una zapatilla hay que abrirla y seguir la conexión en serie.

---

👉 En resumen: **el corazón del motor es el bobinado y el núcleo**. El esmalte del alambre mantiene aisladas las espiras; si se quema, se pierde resistencia, sube la corriente y se destruye el motor.

---

¿Querés que te lo arme en un **diagrama tipo mapa mental** (con ramas: bobina → campo magnético → núcleo → calibre → fallas) para visualizarlo mejor?

Perfecto 👍 Te armo un **resumen claro y directo** de los puntos que mencionaste, con foco en resistencias, diodos y transformadores:

---

## 🔥 Resistencias en electrodomésticos

* En **plancha o jarra eléctrica**, si no funciona la resistencia → **no conviene repararla**.
* Cuando dicen *“no calienta nada”*, lo primero a revisar es la **resistencia**.
* En una jarra, la **resistencia obedece al termostato** (pasa corriente cuando el termostato cierra).
* En la **base de la jarra eléctrica** hay dos **láminas de bronce** que hacen contacto para alimentar la resistencia.

---

## 💡 Focos

* Los focos antiguos eran de **filamento incandescente** (ya casi no existen).

---

## 🔌 Transformador

* Su función es **transformar el voltaje** (elevar o reducir tensión según sea necesario).

---

## ⚡ Diodo y rectificación

* El **diodo** convierte **corriente alterna (CA)** en **corriente continua pulsante (CC)** → proceso de **rectificación**.
* La CC pulsante se **suaviza con un capacitor** (filtrado).
* Para probar diodos se usa el tester en **escala de diodos**, no solo continuidad.

---

👉 En resumen:

* **Resistencias** = parte clave en electrodomésticos de calor.
* **Transformador** = cambia voltaje.
* **Diodo + capacitor** = rectificación (CA → CC más estable).
* **Focos de filamento** = reemplazados por tecnologías modernas (LED, bajo consumo).

---

¿Querés que te prepare una **tabla comparativa** (Resistencia – Transformador – Diodo – Capacitor) con **función, prueba y falla típica** para tenerlo como apunte rápido?


NotebookLM

Aquí tiene un resumen extenso del documento proporcionado, centrado en los principios de reparación y funcionamiento de motores eléctricos y electrodomésticos:

El documento aborda diversos aspectos del funcionamiento, diagnóstico y reparación de motores eléctricos y otros electrodomésticos, destacando la importancia de la precisión y el conocimiento en el trabajo eléctrico.

**1. Funcionamiento y Problemas Comunes en Motores Eléctricos:**

*   **Calentamiento del motor:** Un motor puede calentarse si está "frenado" o trabajando exigido, lo que requiere más potencia y, consecuentemente, un mayor amperaje. Una causa común de esto es que **el rotor no esté perfectamente centrado en el estator**. Debe existir una "película de luz" entre el rotor y el estator para que el campo magnético de la bobina influya adecuadamente en el hierro del rotor, permitiendo un giro conveniente. Si los espárragos (tornillos) que sujetan el motor se aflojan o no calzan bien, el centrado se ve comprometido. Algunos motores permiten un centrado preciso del rotor en el estator mediante sondas antes de apretar los espárragos. En ventiladores, el centrado puede ser más difícil debido a la falta de espacio, aunque suelen venir con una "cuna" que ayuda a que las tapas asienten bien.
*   **Sistema de Centrado:** Es crucial controlar el sistema de centrado y, por regla general, no poner en marcha ningún aparato sin antes verificarlo.
*   **Tipos de Corriente y Cargas:**
    *   La corriente puede ser continua (pura o pulsante, con positivo y negativo) o alterna. En corriente alterna, los cables se identifican como **fase y neutro**. La fase es donde se encuentra la alternancia de energía y es el cable que enciende un buscapolo, mientras que el neutro no.
    *   Una carga resistiva (como la bobina de un motor, una ducha, estufa o ventilador) permite el paso de electrones desde la fase a través de la carga y hacia el neutro, con un movimiento inverso.
    *   La tensión suele ser de 220 voltios, mientras que el amperaje es lo que varía, y los vatios dependen del amperaje.
*   **Problemas específicos de electrodomésticos:**
    *   **Heladeras (refrigeradores):** Si el motor de una heladera consume 4 amperios en lugar de 5 después de cargar el gas refrigerante, indica un problema de compresión. Esto puede deberse a que el pistón ya no comprime (fuga interna) o a que el "flapper de alta" se calienta y se ensucia con hollín de aceite de mala calidad, impidiendo un cierre adecuado y causando fuga de presión. Un motor que no comprime trabaja "liviano".
    *   **Ventiladores:** Un ventilador que consume 4 amperios en lugar de 5 es visto como algo positivo, ya que solo necesita girar para generar viento. Si un ventilador marca 6 amperios después de un cambio de bujes, está mal, ya que indica una mayor fuerza (y consumo) del motor. El líquido hidráulico es considerado el mejor lubricante para ventiladores.

**2. Conceptos Eléctricos Fundamentales:**

*   **Campo Magnético:** Es generado por una bobina. La electricidad nace gracias al campo magnético de la bobina. La corriente alterna tiene un campo magnético de 50 ciclos (norte y sur), mientras que la corriente continua solo crea un "minicampo magnético" al encender o apagar. Un campo magnético genera electricidad, y la corriente alterna genera el campo magnético que se utiliza en los electrodomésticos.
*   **Polaridad:** La presencia de un campo magnético implica polaridad. El "buscapolo" debería llamarse "buscafase" porque busca electricidad, y la brújula debería llamarse "buscapolo".
*   **Neutro:** Es esencial para crear un ciclo de trabajo en un circuito eléctrico. Sin el neutro, los electrones llegarían a un punto y se detendrían. El neutro lleva el mismo ciclo de 50 Hz que la fase, pero invertido.
*   **Cortocircuito vs. Trabajo Eléctrico:** La diferencia principal es la presencia de "trabajo". Hay trabajo cuando existe una carga con resistencia que hace caer el voltaje. En un cortocircuito, no hay resistencia significativa, el voltaje no cae, y esto provoca que salte el fusible o el disyuntor.

**3. Componentes y Reparación de Bobinados:**

*   **La Bobina:**
    *   Las bobinas se crean para generar fuerza magnética. Captan y "duplican" la fuerza magnética.
    *   El campo magnético generado en el estator induce un campo magnético similar en el rotor, lo que causa repulsión y hace girar el rotor.
    *   El **núcleo** de la bobina es crucial, ya que determina la potencia del motor, y a partir de él se saca la medida del calibre del alambre.
*   **Alambre de Bobinado:**
    *   El alambre de bobinado es un conductor aislado con un esmalte especial. Los cables actuales son multifilamento, lo que los hace más maniobrables.
    *   No se utilizan cables pre-aislados comunes para bobinas porque son demasiado gruesos, ocupan mucho espacio en las ranuras y no soportarían las altas temperaturas.
    *   El alambre utilizado, llamado "alambre magneto", está diseñado para soportar temperaturas específicas.
    *   **Quema del Bobinado:** Se produce cuando el bobinado se recalienta excesivamente, quemando el esmalte aislante del alambre. Esto provoca la pérdida del campo magnético, un aumento del consumo de corriente (para compensar la falta de campo) y, finalmente, un cortocircuito debido a la reducción de la resistencia.
*   **Variación del Calibre del Alambre y Cantidad de Vueltas:**
    *   **Nunca se debe cambiar el calibre del alambre original**.
    *   Si se usa un alambre más grueso, la resistencia disminuye, lo que aumenta la velocidad (menos caída de tensión) y la cantidad de electrones, pero causa **mayor calentamiento**.
    *   Si se usa un alambre más fino, la resistencia aumenta, lo que reduce la velocidad (mayor caída de tensión) y **calienta mucho menos (no se quema)**.
    *   Aumentar la cantidad de vueltas del conductor aumenta la resistencia y disminuye el voltaje. Reducir las vueltas disminuye la resistencia, aumenta el voltaje y la velocidad, pero el alambre podría no soportar ese voltaje.
*   **Proceso de Rebovinado:** Para reparar un bobinado quemado, hay que cortar el bobinado, contar las puntas, anotar, medir el calibre del alambre, pesar la cantidad de alambre necesaria y comprar un poco más (ej. 100g -> comprar 120g). Se debe mantener la misma cantidad de vueltas y el mismo calibre de alambre.

**4. Herramientas y Mediciones:**

*   **Pinza Amperométrica:** Un instrumento esencial que mide directamente el amperaje que está consumiendo una carga eléctrica en funcionamiento. Permite verificar si el consumo es el adecuado para el aparato. Es importante considerar el régimen de trabajo de la carga (ej. motor con gas vs. en vacío en una heladera).
*   **Tester (Multímetro):** Se usa para medir continuidad de la bobina y la resistencia. También se usa para medir diodos en su escala específica.
*   **Buscapolo (Test Light):** Permite identificar la fase ("vivo") que enciende el buscapolo, y el neutro que no.
*   **Micrómetro:** Una herramienta para medir el calibre del alambre.
*   **Serie Eléctrica:** Se puede armar una serie para pruebas, usando una lámpara o un reflector con ampolla.

**5. Otros Componentes y Consejos de Reparación:**

*   **Resistencia:** Cuando un aparato no calienta, lo primero que se debe revisar es la resistencia. Si la resistencia de una plancha o jarra eléctrica no funciona, generalmente no conviene arreglarlo.
*   **Transformador:** Transforma el voltaje.
*   **Diodos:** Rectifican la corriente alterna, convirtiéndola en corriente continua pulsante.
*   **Capacitor (Condensador):** Se usa después de los diodos para hacer la corriente continua menos "tildante" o más suave.
*   **Recomendación General:** No es conveniente poner en marcha un electrodoméstico tal como llega, ya que algún componente podría haberse soltado o cambiado de lugar durante el movimiento. Es fundamental obtener la máxima cantidad de información posible antes de proceder con el diagnóstico o la reparación.

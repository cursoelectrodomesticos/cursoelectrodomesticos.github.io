% Clase Nº 11: Microondas: transformador de alta, diodos y magnetrón
% Andrés Imlauer
% 16 Julio 2024

### Audio en YouTube

[https://www.youtube.com/watch?v=VBKQeiF5XVM](https://www.youtube.com/watch?v=VBKQeiF5XVM)

### Audio en Invidious

[https://redirect.invidious.io/watch?v=VBKQeiF5XVM](https://redirect.invidious.io/watch?v=VBKQeiF5XVM)

### Audio en Vocaroo

[https://vocaroo.com/187G3giPOmoV](https://vocaroo.com/187G3giPOmoV)


⚡ **Funcionamiento del microondas**

* Cocina gracias a ondas que excitan moléculas de agua.
* Tiene un **transformador lineal** con dos secundarios: baja tensión (\~3V) y alta (\~2000V).
* Usa **duplicador de voltaje** (diodo + capacitor) → \~4000V para alimentar el magnetrón.

🔧 **Magnetrón**

* Tiene **filamento muy delicado**.
* Para probarlo: medir continuidad del filamento y comprobar que el colector no esté a tierra.
* Si los imanes están rotos o golpeados, no sirve más.
* No usar el microondas sin ventilador → el magnetrón se quema.

📐 **Mediciones**

* **Transformador:** se puede medir de forma indirecta con un trafo auxiliar (ejemplo: 5V en secundario → 50V en salida alta).
* **Diodo de microondas:** siempre debe rectificar con caída de tensión (\~4V).

  * En directa: deja pasar con caída.
  * En inversa: abierto.
  * Si está en corto: siempre marca voltaje de la fuente.
* **Capacitor de alta:** nunca tocarlo (puede retener hasta 4000V).

  * Debe llegar a valores altos (ej. 1000 µF).
  * Si mide menos (ej. 1 µF), está dañado.
* **Regla general:** al medir con tester, esperar descarga, no es como medir resistencia.

⚠️ **Seguridad**

* Nunca tocar el capacitor de microondas.
* Siempre separar y ordenar tornillos al desarmar.
* No colocar objetos metálicos dentro del microondas.
* El chasis no debería tener continuidad con la bobina de baja → si hay, está en falla.

🧰 **Conceptos eléctricos clave**

* Electricidad → energía electromagnética.
* Campo magnético se usa en relés y transformadores.
* En corriente continua no se puede transformar → se necesita fuente oscilante (switching).
* Diferencia entre transformadores:

  * **Lineal (hierro-silicio)** → 50/60 Hz.
  * **Ferrita (switching)** → alta frecuencia, no intercambiables aunque tengan mismo voltaje.
* Potencia = tensión × intensidad.

🔥 **Fallas comunes**

* Causas de quema de placas: blocapuertas, termoactuador, refrigerante 410.
* Capacitores y diodos defectuosos → no generan la duplicación de voltaje.

---

¿Querés que te lo organice en un **esquema visual tipo mapa conceptual** (con bloques: *Magnetrón, Transformador, Diodo, Capacitor, Seguridad, Fallas*) para que quede más claro para repaso rápido?

Perfecto 👌 te resumo y destaco lo **más importante de tu apunte extendido sobre el microondas (Clase 11):**

---

### ⚡ Transformadores

* **Microondas:** usa transformador **lineal** de hierro-silicio → trabaja en **50/60 Hz** (baja frecuencia).
* **Ferrita (switching):** trabajan en frecuencias muy altas (10.000 – 100.000 Hz).
* No se puede usar hierro-silicio en esas frecuencias → se satura.
* **Precaución:** no poner un transformador de menor potencia en una fuente que exige más (ejemplo: no poner uno de 2A en una fuente de 3A).

---

### 🔌 Sistema de alta tensión del microondas

* El transformador tiene dos secundarios:

  * **Baja tensión (\~3V):** filamento del magnetrón.
  * **Alta tensión (\~2000V):** luego duplicado con **capacitor + diodo → \~4000V**.
* El **magnetrón** necesita esos **3V en filamento** para generar la nube de electrones que, acelerados por los 4000V, producen las microondas.

---

### 🔧 Mediciones

* **Diodo de microondas:**

  * No se mide con tester/buscapolo → se usa batería.
  * Ejemplo: batería de 9V → el diodo debe dejar pasar con caída de tensión (≈ 5V medidos).
  * Si da 9V → está en corto.
  * Umbral: \~3,7V.
* **Regla:** en directa → conduce con caída; en inversa → no deja pasar.
* **Transformador:** se puede probar con método indirecto (trafo auxiliar).
* **Magnetrón:** comprobar continuidad del filamento y que no esté derivado a tierra.
* **Capacitor:** nunca tocarlo, puede tener **4000V almacenados**.

---

### 🔥 Cómo cocina el microondas

* No genera calor por resistencia o llama.
* Funciona por **vibración de moléculas de agua** a **2.500 MHz** → fricción interna → cocción **desde adentro hacia afuera**.
* En un horno común el calor llega por radiación/convección y quema primero la superficie; en el microondas se excita el agua dentro del alimento.
* Ejemplo: hueso seco no calienta, pero si tiene humedad sí.

---

### ⚠️ Seguridad

* **Nunca** usar microondas con el ventilador dañado (se quema el magnetrón).
* **Nunca** abrir la puerta mientras funciona → radiación puede dañar internamente (cocción de tejidos).
* El microondas es uno de los **electrodomésticos más peligrosos**: tensiones muy altas y radiación.
* El capacitor se descarga lentamente → esperar siempre antes de medir.

---

### 🛠️ Fallas típicas

* Fusible dañado.
* Capacitor en mal estado.
* Diodo en corto o sin caída de tensión.
* Blocapuertas o ventilador fallando.

---

👉 En resumen:

* **Transformador lineal** (50/60 Hz, hierro-silicio) + **duplicador (diodo+capacitor)** → alimentan magnetrón (3V filamento + 4000V).
* **Cocción interna** por vibración de moléculas de agua a 2.500 MHz.
* **Mediciones seguras:** usar batería para diodo, tester para filamento, nunca tocar capacitor.
* **Riesgos mayores:** alta tensión y radiación.

---

¿Querés que te lo arme en un **esquema paso a paso tipo “circuito del microondas”** (entrada 220V → trafo → duplicador → magnetrón → cavidad) para repasar fácil?

Muy buen apunte 👌. Te destaco lo **más importante y claro de todo este bloque sobre el funcionamiento, seguridad y usos del microondas (Clase 11):**

---

## ⚡ Funcionamiento del microondas

* Cocina por **movimiento de moléculas de agua** a **2.450–2.500 MHz** → fricción interna → cocción **de adentro hacia afuera**.
* No genera calor por resistencia, llama o gabinete caliente.
* Ejemplo: hueso seco no calienta; carne con agua y sal sí.

---

## 🔌 Circuito de potencia

* **Transformador lineal (50/60 Hz)** hierro-silicio.
* Dos secundarios:

  * **3V** → filamento del magnetrón (nube de electrones).
  * **2000V** → duplicador (diodo + capacitor) ≈ **4000V**.
* Magnetrón convierte alta tensión en microondas.

---

## 🔧 Mediciones

* **Diodo:** no sirve con tester/buscapolo. Usar batería de 9V:

  * Directa → caída de tensión (\~3,7–4V).
  * Inversa → no conduce.
  * Si marca 9V → está en corto.
* **Capacitor:** nunca tocarlo, puede quedar cargado a 4000V.
* **Magnetrón:** continuidad en filamento y sin derivación a tierra.

---

## 🔥 Cocción y diferencias con horno tradicional

* Horno convencional → calor por resistencia/llama, cocina **desde afuera hacia adentro** y puede dorar.
* Microondas → energía electromagnética, cocina **todo el volumen del alimento a la vez**, pero no dora.
* Por eso se recomienda dejar la puerta abierta un rato después → disipar vapor acumulado.

---

## 🍽️ Recipientes

* Aptos: vidrio, plástico, cerámica, porcelana lustrosa.
* No aptos: metales, cerámica rústica que se calienta sola.
* Diferencia con horno convencional:

  * En horno, el plástico se derrite porque el calor viene del gabinete.
  * En microondas, el plástico soporta porque no tiene agua → lo que calienta es solo el alimento.

---

## ⚠️ Seguridad

* Microondas solo funciona con puerta cerrada (blocapuertas).
* No mirar dentro mientras funciona → radiación dañina.
* Nunca usar sin ventilador → se quema el magnetrón.
* No usar componentes metálicos dentro (se electrifican por el campo electromagnético).
* El microondas es uno de los **electrodomésticos más peligrosos**:

  * Alta tensión (2000–4000V).
  * Radiación de microondas.

---

## 🛠️ Fallas comunes

* Fusible abierto.
* Capacitor dañado.
* Diodo en corto o sin caída de tensión.
* Blocapuertas defectuoso.
* Termoactuador.
* Problemas con nuevos gases refrigerantes (R410).

---

👉 En resumen:
El microondas **no genera calor directo** sino que excita las moléculas de agua.
El **transformador lineal** + duplicador de voltaje alimenta el magnetrón.
El alimento se cocina desde adentro, con riesgos altos de **alta tensión y radiación**.
Recipientes adecuados son clave y nunca deben usarse metales.

---

¿Querés que te lo arme en un **cuadro comparativo Microondas vs Horno tradicional** (fuente de calor, forma de cocción, recipientes aptos, ventajas, limitaciones)?

Te hago un resumen bien ordenado de lo que explicó el profesor sobre **el microondas**, para que tengas clara la lógica de análisis y reparación 🔧⚡:

---

## 🍽️ Uso de recipientes

* **Plástico**: no va en microondas porque se quema.
* **Metal**: va en horno eléctrico, pero **prohibido en microondas** (chispazos).
* **Vidrio templado**: se usa en ambos, pero tiene que estar diseñado para resistir el calor del microondas.

---

## 🔧 Partes del microondas

El microondas se divide en **2 etapas** para poder analizarlo:

### 1️⃣ Etapa de Control

* Timer / electrónica de mando
* Termostatos / sensores
* Placa de control
  👉 Si falla acá, no se debe revisar la etapa de potencia.

### 2️⃣ Etapa de Potencia

Es la que **genera los microondas**. Incluye:

* **Transformador** (eleva de 220V a \~2000-4000V).
* **Capacitor** (almacena y descarga para excitar el magnetrón).
* **Diodo** (rectificación de alta tensión).
* **Magnetrón** (genera la radiación de 2450 MHz).
* **Ventilador/forzador** (enfría magnetrón y circuito).
* **Fusible** (protección).

👉 El **magnetrón** necesita unos **4000 voltios** para funcionar.
👉 Los **2450 MHz** no vienen del transformador ni del capacitor, sino que **los genera el magnetrón mismo** en su disparo de electrones.

---

## 📖 Comparaciones con otros aparatos

* **Horno eléctrico**:

  * Potencia → resistencia
  * Control → termostato
  * Se puede usar directo, pero sin control es inseguro.
* **Plancha**: igual lógica, primero resistencia, luego se sumó el termostato.
* **Pava eléctrica**: a veces se anula el termostato para que funcione siempre la resistencia → ejemplo de “sacar la etapa de control”.

---

## ⚡ Claves del magnetrón

* Trabaja a **2450 MHz** (frecuencia fija internacional).
* Requiere **alta tensión (4000V aprox.)** que viene del transformador y capacitor.
* El transformador NO cambia la frecuencia (eso fue una confusión común, incluso en técnicos de radio).

---

✅ Conclusión:
El **análisis de fallas** siempre conviene empezarlo por la **etapa de potencia** (transformador, capacitor, diodo, magnetrón, fusible, ventilador).
La **etapa de control** puede estar rota y el horno igual se puede hacer funcionar “en directo” (aunque sin seguridad ni comodidad).

---

¿Querés que te arme un **esquema tipo mapa** 🗺️ con las dos etapas (control y potencia) y sus componentes para que te quede bien visual?

Perfecto 👌, esta parte que anotaste es CLAVE porque el profe está diferenciando conceptos que suelen confundirse, sobre todo entre **fuente switching** y **fuente lineal** en los microondas. Te lo reordeno como una **nota técnica clara** (podés usarla como machete):

---

## 🔌 Tipos de transformadores

### 1. **Transformador de hierro-silicio (lineal)**

* Trabaja con la frecuencia de red: **50/60 Hz**.
* Ejemplo: transformador de microondas, transformadores de línea clásicos.
* Ventaja: robusto, no depende de frecuencias especiales.
* Si un transformador es de **12V / 3A**, se puede reemplazar por otro de 12V con más amperaje (no pasa nada).
* ⚠️ Lo único que NO se puede es poner uno de menor corriente (ej: 2A en lugar de 3A).

### 2. **Transformador de ferrita (switching)**

* Trabaja a **altas frecuencias**: entre **50 kHz y 100 kHz**.
* Mucho más chico y liviano porque a mayor frecuencia, menos hierro se necesita.
* PERO: cada transformador está diseñado para UNA frecuencia de trabajo.
* ⚠️ No se pueden intercambiar libremente aunque entreguen el mismo voltaje (ej: 12V).

👉 Conclusión:

* En **microondas hogareños comunes** → se usa **transformador lineal de 50 Hz**.
* El **magnetrón** es el que genera los **2450 MHz**, NO el transformador.

---

## ⚡ Transformador de microondas

El trafo de microondas es especial porque entrega **dos tensiones distintas**:

1. **Baja tensión (\~3V AC, cables gruesos)** → sirve para calentar el **filamento del magnetrón** (como una lámpara incandescente).
2. **Alta tensión (\~2000V AC, cable fino y aislado)** → servirá, con el **diodo + capacitor**, para obtener los **4000V DC** que necesita el magnetrón para disparar electrones.

### Particularidades

* El secundario de alta tensión **tiene un extremo conectado al chasis (tierra)**.
* Por eso muchas veces vemos un solo cable de alta: el otro “cable” es la carcasa metálica del trafo.
* Gracias a eso se puede cerrar el circuito con el capacitor/diodo y con el propio magnetrón.

---

## 🔬 Funcionamiento del magnetrón

* Tiene un **filamento** → se enciende con **3V**.
* En vacío (sin gas, vacío casi perfecto) emite electrones cuando el filamento se pone incandescente.
* Esos electrones se aceleran con los **4000V**.
* El campo magnético interno los hace girar y concentrarse en un **haz único**, que se dispara por la antena → salen los microondas a **2450 MHz**.
* Comparación: como un láser, pero en vez de fotones, es un haz de electrones.

---

## 🔋 Cómo se obtienen los 4000V

* El trafo solo da \~2000V.
* Se usa un **doblador de voltaje** (diodo + capacitor).
* Así se llega a los \~4000V DC necesarios para que el magnetrón funcione.
* En esta etapa, lo que importa es el **voltaje**, no la intensidad (corriente muy baja).

---

## ⚠️ Seguridad y Tierra

* El trafo de microondas tiene parte de la alta tensión conectada a chasis/tierra.
* Eso evita tener cables sueltos con 2000V.
* Si la instalación de la casa **no tiene buena puesta a tierra**, puede ser peligroso → pero en Argentina ya sabés cómo se “resuelve” (👀 cortar la tierra para que no salte el disyuntor en duchas eléctricas y aires viejos).
* El profe dice: como técnico no lo recomiendes, pero en la práctica mucha gente lo hace.

---

📌 Nota personal tuya (resumida):

> El colega experto en transformadores se confundió porque pensó que el microondas usaba una **fuente switching** (50-100 kHz) y que de ahí salía la frecuencia de microondas. Pero en realidad:
>
> * El trafo del microondas es **lineal de 50 Hz**.
> * La frecuencia de **2450 MHz la genera el magnetrón**, NO el transformador.

---

¿Querés que te arme un **esquema visual del transformador de microondas** con:

* primario,
* bobina de filamento (3V),
* bobina de alta (2000V a tierra),
* capacitor + diodo → 4000V al magnetrón?

Te quedaría como un diagrama de referencia rápida para diagnóstico y reparación.

Perfecto 👍
Esto que compartís corresponde a la **etapa de potencia de un microondas**, y la explicación que dio el profesor fue para entender cómo funcionan el **transformador de alta tensión, el capacitor, el diodo y el magnetrón**. Te lo resumo con los puntos clave para que te quede más claro (y sin tanto enredo entre alumno/profe):

---

### 🔌 Transformador del microondas

* **Primario** → se conecta a 220 V (50 Hz).
* **Secundarios**:

  * **Alta tensión (≈2000 V AC)** → va al **magnetrón** (para acelerar electrones).
  * **Baja tensión (≈3 V AC, muy alta corriente)** → alimenta el **filamento del magnetrón** (genera la nube de electrones).

---

### ⚡ Etapa de alta tensión

* El **diodo de alto voltaje** y el **capacitor (0,9–1,1 µF, aislación 4000 V, no polarizado)** trabajan en conjunto para formar un **doblador de tensión**.
* Con eso, los ≈2000 V del trafo se convierten en **≈4000 V DC**, que son los que necesita el magnetrón para emitir microondas.

---

### 🔥 Magnetrón

* Funciona parecido a un tubo de vacío.
* **Filamento (3 V)** → calienta y libera electrones.
* **Ánodo (≈4000 V DC, conectado al chasis)** → atrae los electrones.
* El campo magnético los hace girar y eso genera la radiación de microondas.
* El filamento **no explota aunque conviva con 2000–3000 V**, porque:

  * Está **aislado galvánicamente** respecto a la alta tensión.
  * Es como tocar solo fase sin neutro/tierra: tenés tensión, pero sin circuito cerrado no circula corriente peligrosa para el filamento.

---

### 🔍 Diagnóstico en taller

* Si **no calienta** pero **el transformador zumba** → revisar **diodo, capacitor, magnetrón** (etapa de potencia).
* Si **no zumba** → falla en **etapa de control** (placa, fusibles, relés, interruptores de puerta).
* Siempre separar:

  * **Etapa de control** (placa, relés, fusibles comunes).
  * **Etapa de potencia** (trafo, capacitor, diodo, magnetrón).

---

📌 **Dato de seguridad**: Estas tensiones (2000–4000 V) son letales ⚠️. Siempre descargar capacitor antes de manipular.

---

¿Querés que te haga un **esquema gráfico simplificado** con el transformador, el capacitor, el diodo y el magnetrón, para que veas el recorrido de la tensión?

Exacto 👍, lo que estás reconstruyendo es **el proceso de diagnóstico paso a paso que suele hacerse en un microondas** cuando no calienta, y hasta ahora lo resumiste bien.

La secuencia que siguieron (y que es la correcta en laboratorio/taller con seguridad extrema) es:

1. **Aislar el primario** del transformador (desconectar faston macho/hembra).

   * Así se puede comprobar si la **etapa de control** realmente está habilitando el trafo cuando se da la orden de marcha.
   * Para esto se usa una **lámpara incandescente de 220 V en serie** o el tester → si enciende, la parte de control funciona.

2. **Comprobar el magnetrón**:

   * Continuidad en los pines → debe marcar como filamento (unos pocos ohmios).
   * No debe dar fuga a masa (chasis).
   * Imanes enteros → si están rajados pierde campo magnético y no sirve.

3. **Capacitor de alta tensión** (1 µF, 2100 VAC aprox):

   * Debe descargarse siempre antes de manipular (destornilladores aislados en cruz).
   * Si no mide capacidad (queda muy bajo, no sube a µF en tester), está malo.
   * Además debe soportar unos 4000 V de aislación.

4. **Diodo de alta tensión**:

   * No se mide bien con tester común en escala de diodos porque su umbral es de 3–5 V.
   * Se prueba con batería externa (9 V o más) en serie con el tester → debe mostrar caída de 3–5 V en directa, y bloqueo total en inversa.
   * Si marca 0 V en ambas direcciones = corto, si marca siempre abierto = abierto.

5. **Fusible de alta tensión**:

   * Va en serie con el capacitor.
   * Si está abierto, no va a cargar el capacitor y no se eleva la tensión para alimentar el magnetrón.

6. **Transformador**:

   * Lo último que se mide, porque es lo más peligroso.
   * Se puede comprobar continuidad en primario, secundario de filamento (\~3 V) y secundario de alta (\~2000 V).
   * Para ensayos bajo tensión hay que hacerlo con muchísima precaución, preferiblemente con carga y siempre aislando.

👉 Resultado de tu práctica según lo que contaste:

* **Magnetrón: bueno.**
* **Diodo: bueno.**
* **Capacitor: malo.**
* **Fusible: malo.**
* **Transformador: pendiente de prueba.**

---

📌 **Conclusión hasta acá**:
El problema estaba en la **etapa de alta tensión** → específicamente el **capacitor** y el **fusible**, que son bastante comunes de fallar.

---

¿Querés que te arme un **esquema simplificado del circuito de potencia del microondas** (transformador, diodo, capacitor y magnetrón) para que te quede claro cómo circulan los 2000–4000 V?

Perfecto 👌, lo que escribiste es justamente el razonamiento que se hace cuando se revisa un **transformador de microondas** y se quiere probarlo sin tener que trabajar con los **2000 V** reales, que son extremadamente peligrosos ⚡.

Te resumo los puntos más importantes de lo que anotaste y los aclaro un poco:

---

### 🔹 Principio de la prueba con otro trafo

* Si al trafo del microondas (primario 220 V → secundario 2000 V) le das en lugar de 220 V, una tensión mucho más baja (ej. 17 V), entonces la salida también baja en la misma proporción.
* Como la relación de transformación es aprox. **1:10**, si alimentás con 17 V → obtenés unos **170 V** en el secundario de alta.
* Esto ya es un voltaje que permite comprobar funcionamiento sin llegar a los 2000 V reales, y además no se sobrecalienta el trafo.

---

### 🔹 Bobinados del transformador de microondas

* **Primario (220 V):** está en los faston grandes.
* **Secundario de alta (\~2000 V):** es el bobinado grueso con salida aislada, normalmente trae el fusible de alta en serie.
* **Secundario de filamento (\~3 V):** alambre grueso, baja tensión, alimenta el filamento del magnetrón.

---

### 🔹 Mediciones con tester (ohmímetro)

1. **Primario:** debe dar unos pocos ohmios (1–3 Ω aprox).
2. **Secundario de alta:** suele marcar entre 100 y 200 Ω.
3. **Secundario de filamento:** muy baja resistencia (0,1–1 Ω).
4. **A masa:** ninguno de los bobinados debe dar continuidad con el chasis → si da, está en corto.

---

### 🔹 Fusible y capacitor

* Si el **capacitor falla**, el circuito de doblador de tensión no funciona y no se genera la tensión para el magnetrón.
* El **fusible de alta** protege al trafo → si el capacitor se cortocircuita, se abre el fusible antes de que el trafo explote.
* En tu caso, efectivamente se quemó el fusible porque el capacitor quedó en mal estado.

---

### 🔹 Aire como dieléctrico

Muy bien observado:

* El **magnetrón oscila a 2,45 GHz** (frecuencia de microondas).
* A esa frecuencia, el aire entre la antena del magnetrón y el chasis se comporta como un capacitor → baja impedancia.
* Es decir, a **50 Hz el aire es aislante**, pero a **2,45 GHz deja pasar la señal** (por eso puede cerrarse el circuito de RF).

---

✅ **Conclusión de tu práctica:**

* El **transformador está bien** (primario sano, bobinados sin cortos a masa).
* Los **dañados fueron el capacitor y el fusible de alta**.
* El magnetrón y el diodo dieron OK.
* La falla principal fue en la **etapa de alta tensión** → se soluciona reemplazando esos dos componentes.

---

¿Querés que te haga un **dibujo esquemático simplificado** del circuito de potencia (220 V → trafo → doblador → magnetrón) para que te quede bien claro dónde están el fusible, capacitor y diodo?

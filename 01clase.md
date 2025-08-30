% Clase Nº 1: Potencia. Voltios. Amper. Fuente. Corriente alterna (VAC) vs continua (VDC). Transformador. Amper. Fuera de ciclo. 
% Andrés Imlauer
% 16 Julio 2024
   
Aquí te destaco los **puntos más importantes** de la clase del Profesor Marcelo Barrios, organizados y claros:

---

⚡ **Conceptos básicos**

* **Potencia (Watt o vatio) = Voltios × Amperios.**
* **Voltios = Tensión (energía).**
* **Amper = Intensidad de corriente (flujo de electrones).**
* **Fuente → Carga** (principio básico de un circuito).

🔌 **Corriente alterna (VAC) vs continua (VDC)**

* **VDC:** tiene polaridad fija (+ y -).
* **VAC:** no hay positivo ni negativo; cambia de polaridad en cada ciclo (medio ciclo positivo y otro negativo).
* En VAC **no se puede hablar de positivo y negativo**.
* **Fase = línea o vivo**, el **neutro no da descarga**, la fase sí.

🔋 **Transformador**

* Se representa con **placas en forma de E e I**, con una bobina en medio.

🌌 **Concepto físico**

* Amper: partículas (electrones).
* Voltaje: campo de energía.
* Mejor conductor = más electrones libres en sus átomos.

📈 **Valores de la tensión alterna**

* **Valor pico/cresta ≈ 311 V** para una red de 220 V.
* **Los cálculos se hacen con valor eficaz (RMS = 220 V), no con el pico.**
* **Los capacitores se cargan al valor pico.**
* Cuando sentimos una descarga, es porque nos afecta el valor de pico (\~300 V).

⚙️ **Relación tensión–corriente–potencia**

* La **tensión y la intensidad deben estar en fase** para que haya potencia real.
* Mientras no haya trabajo, **no circula intensidad**.
* El amperaje es resultado de la potencia y el voltaje: I = W/V. Ejemplo: I = 2500/220 = 11,36 A
* El voltaje es constante, el amper depende de la potencia.

---

⚡ **Fuera de ciclo (desfasaje)**

* Estar *fuera de ciclo* = que la corriente y la tensión no están en fase (onda seno desfasada).
* Ocurre principalmente en **motores eléctricos** (bobinas de arranque y trabajo).
* Ejemplo: aire acondicionado → usa bobinas en paralelo → provoca desfasaje.
* El **factor de potencia (cos φ)** mide ese desfasaje:

  * 1 =1 (sin desfasaje, potencia activa = potencia consumida).
  * 1=0,65 (desfasaje, menor eficiencia).
* **El desfasaje se corrige con capacitores.**

🔋 **Baterías y pilas**

* Una batería de auto tiene **6 vasos** → cada uno genera su voltaje.
* **Bornes** = polos (positivo y negativo).
* **Serie:** se suman los voltajes (ej. 3 pilas de 1,5 V = 4,5 V).
* **Paralelo:** se mantiene el voltaje, pero aumenta la capacidad de corriente.
* Al conectar/desconectar baterías, siempre primero el negativo (seguridad).
* Motores de corriente continua → al invertir polaridad, cambia el sentido de giro.

💡 **Circuito eléctrico básico**

* Voltaje = campo de fuerza que impulsa electrones.
* Intensidad = flujo de electrones (partículas).
* Circuito abierto → no hay corriente.
* Circuito cerrado → circula corriente, se produce **trabajo eléctrico**.

📏 **Medición con tester**

* Se selecciona la escala adecuada (ej: 20 V CC).
* Negro en común, rojo en voltaje/resistencia.
* Si se invierte polaridad, solo aparece el voltaje en negativo (ej: -12 V).

🔢 **Amperaje y electrones**

* 1 A = paso de **aprox. 4,73 × 10¹⁸ electrones por segundo**.
* Cables deben dimensionarse según amperaje → si circula más corriente de la soportada, se calientan por fricción de electrones.
* **Ejemplo práctico:**

  * Zapatilla → soporta 10 A por toma.
  * Cable muy fino → mayor calentamiento.
  * Cables gruesos → menor resistencia, menos calor.

💡 **Aplicaciones prácticas**

* Una lámpara de 45 W 220 V no funciona en un auto (12 V).
* Una lámpara de bajo voltaje conectada a 220 V **explota**.
* Voltaje “empuja” a los electrones → cuanto mayor el voltaje, mayor velocidad de movimiento.

---

📌 **Resumen clave en una frase:**
La eficiencia eléctrica depende de mantener tensión e intensidad en fase, usar capacitores para corregir desfasajes, dimensionar bien cables según amperaje, y entender la diferencia entre conexiones en serie/paralelo en baterías y cargas.

---

¿Querés que te arme esto en un **esquema visual tipo mapa conceptual** para que te sea más fácil repasarlo antes del examen?

Buenísimo, te armo un **resumen con los puntos más importantes de la clase sobre cómo se carga la batería de un auto**:

---

⚡ **Carga de la batería del auto**

* Se carga a través de un **alternador (generador de corriente alterna)**.
* En algunas motos todavía se usa **dínamo**.
* La **batería es corriente continua (CC)**, por eso:

  * La corriente alterna debe convertirse a continua mediante **rectificación** (diodos).

🔄 **Transformador y rectificación**

* **Transformador**: cambia el **voltaje** (220 V → 16 V, etc.) pero siempre dentro de corriente alterna.
* No funciona con corriente continua.
* Está compuesto por:

  * **Bobinado primario y secundario** (relación de vueltas define el voltaje).
  * **Núcleo (hierro al silicio, no cromo)** → se magnetiza y desmagnetiza en cada ciclo (50 Hz).
* **Rectificador**: convierte la alterna en continua, mediante diodos + filtros + controladores.

🧲 **Magnetismo en el transformador**

* La energía eléctrica aplicada genera un **campo magnético** en el núcleo.
* Ese campo varía con los ciclos de la CA (medio ciclo positivo, medio negativo).
* El secundario recibe el campo magnético y lo convierte de nuevo en electricidad.
* **Más vueltas → más voltaje**; **menos vueltas → menos voltaje**.

🔌 **Ejemplo de carga**

* Alternador entrega **CA** → transformador baja voltaje → rectificador convierte en **CC** → batería se carga.

📐 **Medición y herramientas**

* **Multímetro (tester)** debe medir:

  * Voltaje (CA y CC).
  * Amperaje.
  * Resistencia (Ω).
  * Capacitancia (µF).
* Escoger escala adecuada (ej: 20 V CC).
* Negro en común, rojo en voltaje/resistencia.
* Si se invierte polaridad → solo muestra voltaje en negativo (ej: -12 V).
* **Pinza amperométrica** mide corriente a través del campo magnético.

⚙️ **Aplicaciones y precauciones**

* Chips y controladores de electrodomésticos (ej: aire acondicionado, lavarropas) usan **transformador + diodos + capacitores** para obtener CC.
* Motores pueden trabajar con pulsos de CA y CC.
* Uso de **serie con lámparas** para proteger al probar placas:

  * Si hay corto, la lámpara prende fuerte.
  * Si no hay corto, prende débil.
* Herramientas básicas: tester, pinzas, soldador de estaño, cinta aislante, termocontraíble.

💡 **Ejemplos prácticos**

* Una lámpara de **220 V / 45 W no funciona en 12 V** (auto).
* Una lámpara de **12 V conectada a 220 V explota**.
* Alternador trabaja a **50 Hz**.

---

📌 **Idea clave:**
La batería del auto (corriente continua) se carga con energía del alternador (corriente alterna) que pasa por un transformador y un rectificador para convertirse en corriente continua regulada.

---

¿Querés que te lo pase en un **esquema tipo diagrama de flujo** (Alternador → Transformador → Rectificador → Batería) para visualizarlo rápido?


Aquí tienes un resumen extenso y detallado de los puntos más importantes de los materiales proporcionados:

***

### Resumen Extenso de Fundamentos de Electricidad y Circuitos

Este material aborda conceptos fundamentales de la electricidad, tipos de corriente, componentes clave, funcionamiento de circuitos, y prácticas de seguridad y medición, destacando la interacción entre la teoría y la aplicación práctica.

#### 1. Conceptos Fundamentales de Electricidad

*   **Potencia (Watts)**: Se define como "Watts" o "vatio" y representa la potencia eléctrica. La potencia se relaciona con la intensidad (amperaje) y la tensión (voltaje); de hecho, la electricidad es la **tensión por intensidad**.
*   **Tensión o Voltaje (Voltios)**: Se refiere a la "energía" y al "campo de energía". Es una **fuerza** que mueve los electrones. Los voltios se consideran una constante en ciertos cálculos. Cuando nos "patea", lo hace con **300 Voltios en el valor cresta**, aunque los cálculos se realizan con el **valor eficaz**, no el valor pico. Sin embargo, los capacitores se cargan al valor pico. El valor pico también se menciona como 311 voltios.
*   **Intensidad o Amperaje (Amper)**: Se refiere a la "intensidad" y son **partículas: electrones**. La intensidad es un resultado de la potencia. Para que se forme 1 amper, se necesitan electrones. **Un amper equivale a 4.73 trillones de electrones en 1 segundo**.
*   **Ecuaciones Fundamentales**: Se presenta el triángulo W (Potencia), E (Tensión), I (Intensidad). La fórmula derivada es **I = W/V** (Intensidad = Potencia / Voltaje). Por ejemplo, para 2500 Watts y 220 Voltios, la intensidad es 11.36 amperes.
*   **Naturaleza de la Electricidad**: Toda la materia tiene átomos; cuantos más electrones libres, mejor conductor. El voltaje se describe como un **campo de fuerza** con expansión. La intensidad son partículas de electrones.

#### 2. Corriente Alterna (CA) y Corriente Continua (CC)

*   **Corriente Alterna (VAC)**:
    *   Está constantemente en **alternancia**.
    *   **No hay un positivo fijo**; en un medio ciclo es positivo y en otro negativo.
    *   Tiene **ciclos**, por ejemplo, 50 ciclos por segundo, donde un medio ciclo positivo y uno negativo forman un ciclo.
    *   No se puede saber el positivo y el negativo en VAC.
    *   La **fase** (también conocida como línea o "vivo") es la que "patea", mientras que el **neutro no patea**. Se aclara que "el vivo" no tiene nada que ver con la fase, lo cual puede ser confuso.
    *   La corriente eficaz es de 220 voltios.
*   **Corriente Continua (VDC)**:
    *   Tiene un polo positivo (+) y un polo negativo (-) definidos.
    *   Los motores de corriente continua pueden girar en el sentido contrario si se invierten sus conexiones.
    *   Las baterías operan con corriente directa.
    *   Los chips de las placas electrónicas suelen trabajar con energía continua.
*   **Valor Pico y Valor Eficaz**:
    *   El **valor pico** o **valor cresta** es la tensión máxima que alcanza la corriente alterna en un ciclo. Se menciona un valor de 300V o 311V para el pico.
    *   Todos los cálculos eléctricos se realizan con el **valor eficaz**, no el valor pico. Los capacitores, sin embargo, se cargan al valor pico.
*   **Fase y Desfasaje**:
    *   La **tensión y la intensidad deben trabajar "en fase"**. Esto significa que no deben "salir de fase" o que la onda del seno esté mal.
    *   El único componente que puede generar un **desfasaje** son los **motores**, especialmente aquellos con bobinas trabajando en paralelo (como los aires acondicionados).
    *   Un desfasaje implica que la potencia nominal no es igual a la potencia consumida (ejemplo: 1=0.65).
    *   Los **capacitores pueden mejorar el desfasaje** (factor de potencia).
    *   Las cargas resistivas y "disruptivas" (posiblemente capacitivas o inductivas) pueden tener un factor de potencia 1=1 si tienen bobina para corregirlo.
*   **Seguridad con CA**: Cerrar un circuito con un conductor, como conectar un cable en un enchufe, provoca un **cortocircuito**. La fase "patea".

#### 3. Circuitos y Conexiones

*   **Flujo de Corriente y Trabajo Eléctrico**:
    *   La fuerza (voltaje) sale del **polo positivo al negativo**, describiendo un ciclo. Esta es la **fuerza voltaica**.
    *   Los **electrones, en cambio, salen del polo negativo** y viajan hasta dentro de la batería, moviéndose por segundo para formar el amper.
    *   Cuando se cierra un circuito (por ejemplo, encendiendo una llave o switch), se produce un **trabajo eléctrico**. Si el circuito está abierto, no hay trabajo.
    *   Mientras no haya trabajo (una carga consumiendo), no habrá intensidad (amperaje).
*   **Conexiones en Serie**:
    *   Una conexión en serie se produce al "hacer un puente".
    *   Cuando se conectan pilas o baterías en serie, **se suma el voltaje**, pero **no sube el amperaje**.
    *   Conectar algo en "serie en paralelo" (una combinación o malentendido de conexión) podría causar una explosión.
*   **Conexiones en Paralelo**:
    *   Es posible conectar dos baterías en paralelo.
    *   Los motores de aire acondicionado trabajan con bobinas en paralelo.

#### 4. Componentes Eléctricos Clave

*   **Transformadores**:
    *   Son aparatos que **transforman el voltaje**.
    *   Se componen de placas con forma de "E" y una recta, con una **bobina** entre ellas.
    *   Tienen un **bobinado primario y uno secundario**. La **cantidad de vueltas del bobinado** determina la relación de voltaje. Más espiras resultan en más voltaje.
    *   Requieren un **núcleo** (tradicionalmente de hierro al silicio, no cromo) para generar y disipar campos magnéticos en cada ciclo de la corriente alterna.
    *   La finalidad de la energía en un transformador es generar un **campo magnético** que magnetiza el núcleo.
    *   **No pueden trabajar con corriente continua**.
    *   Ofrecen **aislación galvánica** entre el primario y el secundario. Si se pone resistencia, no hay aislación galvánica.
*   **Capacitores**: Se usan para **mejorar el factor de potencia** y corregir el desfasaje en motores. Se cargan a valor pico.
*   **Baterías**:
    *   Un conjunto de pilas se denomina batería.
    *   Las baterías de coche suelen tener 6 "vasos" independientes, cada uno generando su propio voltaje.
    *   Los bornes son los extremos de la batería donde se conecta.
    *   Se cargan a través de un **alternador** o un **dinamo**.
*   **Alternadores y Dínamo**: Son **generadores** que cargan las baterías de vehículos. Las motos pueden tener ambos. Los reguladores de voltaje varían entre ellos.
*   **Rectificación**: Es el proceso para **convertir la corriente alterna a corriente continua**. Sin rectificación, la CA y CC "explotan" al conectarse.
*   **Componentes Electrónicos (Chips, Transistores, Relays, Triac)**:
    *   Las placas de aire acondicionado, por ejemplo, contienen un "chip madre jungla" que, junto con transformadores, diodos, filtros y controladores de voltaje, forma una fuente de alimentación continua.
    *   El chip da órdenes, como encender un motor, cargar agua en un lavarropas, o controlar el giro del motor.
    *   Estos sistemas requieren de otros componentes como transistores, triac (trey) y relays.
    *   Los motores modernos trabajan por pulso y necesitan tanto corriente continua como alterna.

#### 5. Fenómenos Eléctricos

*   **Fricción de Electrones y Temperatura**:
    *   El movimiento y el roce de los electrones generan **fricción y temperatura**.
    *   Un consumo elevado de amperaje en un conductor inadecuado (de menor amperaje) causa un aumento de temperatura significativo.
    *   En un conductor adecuado, la fricción es mínima.
    *   El **amperaje puede derretir los cables** si excede su capacidad.
    *   La fricción de los electrones es lo que hace que una lámpara encienda.
*   **Campo Magnético**:
    *   Se genera cuando se aplica energía eléctrica a un transformador.
    *   Tiene polos norte y sur.
    *   La variación del semiciclo de la CA genera una variación de polos magnéticos.
    *   Las leyes del magnetismo indican que **polos iguales se rechazan** y **polos distintos se atraen** (aunque el texto menciona "se rechazan" para ambos en una parte, lo cual es una aparente contradicción, se entiende el principio general).
    *   La pinza amperimétrica detecta el campo magnético para medir el amperaje.
*   **Aislación Galvánica**: Es una separación eléctrica, como la que existe en el medio de los bobinados de un transformador. Si se coloca una resistencia, esta aislación no existe.

#### 6. Herramientas y Prácticas de Taller

*   **Multímetro/Tester**:
    *   Se utiliza para medir voltaje (CC y CA), resistencia (óhmios), amperaje (CC y CA) y capacitancia (faradios). Algunos modelos miden también frecuencia y temperatura.
    *   Al medir voltaje, se debe elegir la escala superior más cercana al valor esperado para evitar dañar el tester.
    *   Las puntas de prueba se conectan: la negra en "común" y la roja para voltios y resistencia. Invertir las puntas solo mostrará un voltaje negativo (-12V).
    *   Es importante que tenga un rango para medir capacitores, al menos hasta 200 microfaradios (µF).
*   **Pinza Amperimétrica**: Permite medir el amperaje detectando el campo magnético alrededor del cable.
*   **Otras Herramientas Esenciales**: Destornillador Philips, pinzas (de fuerza, de punta), lápiz soldador (de 30-40 watts), estaño, cinta aislante, buscapolo y termocontraíble.
*   **Reglas de Taller**: **Nunca dejar herramientas en el piso** y **no prestarlas**.
*   **Circuito en Serie para Pruebas (Limitador de Amperaje)**:
    *   Se construye con un enchufe, dos portalámparas de 10W conectados en serie, y tomas.
    *   Su propósito es **limitar el amperaje** en caso de cortocircuito al reparar placas o motores.
    *   Si la carga tiene un cortocircuito, la lámpara se encenderá con fuerza; si no, encenderá levemente.

#### 7. Consideraciones de Diseño y Compatibilidad

*   **Selección de Cables**: Es crucial elegir el cable adecuado para la carga debido a la **bajada de tensión** y para evitar el sobrecalentamiento por el amperaje (ej., para una ducha, un cable inadecuado está "mal"). La zapatilla soporta 10 amper, pero se debe verificar la capacidad del cable.
*   **Compatibilidad de Voltaje**:
    *   Una lámpara de 45W a 220V no funcionará en un auto (12V).
    *   Conectar una lámpara de voltaje incorrecto a 220V puede hacer que **explote**.
    *   La conexión directa de corriente alterna con continua puede ser peligrosa y causar explosiones.

Este compendio subraya la importancia de comprender la interacción entre los diferentes fenómenos eléctricos para un manejo seguro y eficiente de la electricidad y los circuitos.

% Clase Nº 1: Introducción a corriente alterna y continua, fuentes y transformadores
% Andrés Imlauer
% 16 Julio 2024

Aquí te destaco los **puntos más importantes** de la clase del Profesor Marcelo Barrios, organizados y claros:

***

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

***

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

***

📌 **Resumen clave en una frase:**
La eficiencia eléctrica depende de mantener tensión e intensidad en fase, usar capacitores para corregir desfasajes, dimensionar bien cables según amperaje, y entender la diferencia entre conexiones en serie/paralelo en baterías y cargas.

***

¿Querés que te arme esto en un **esquema visual tipo mapa conceptual** para que te sea más fácil repasarlo antes del examen?

Buenísimo, te armo un **resumen con los puntos más importantes de la clase sobre cómo se carga la batería de un auto**:

***

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

***

📌 **Idea clave:**
La batería del auto (corriente continua) se carga con energía del alternador (corriente alterna) que pasa por un transformador y un rectificador para convertirse en corriente continua regulada.

***

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

***

## Publicación original de Andrés Imlauer

**Título original:** [APUNTE] Taller reparacion electrodomesticos (Clase 1) - Introducción corriente alterna, continua, bobinas: fuera de ciclo, batería auto, núcleos.

**Publicado:** 8 de julio de 2024

<!-- Publicación original importada desde el tag electrodomesticos -->

Profesor: Marcelo Barrios


Watts=Potencia
Potencia = vatio
Voltios=Energía
Tension = voltaje
Amper=Intensidad
Tensión en amperage

Fuente--Carga

Las placas de un transformador son un montón de letras E y una recta: E I 3 entre las dos "E" va una bobina.

El amper son partículas: eléctrones
Voltaje es campo de energía


Toda la materia tiene átomo: Más electrones libres mejor conductor  
**Vac** - Fase neutro  
**Vdc** - + y -  


En corriente alterna no hay positivo: en un medio ciclo positivo en otro negativo:

Y eso estén en la fase: a la fase se lo conoce como línea
Y al otro se lo llama el vivo

El neutro no nos patea, la fase es el vivo patea.

No tiene nada que ver el vivo con la fase. La corriente alterna tiene ciclos.

En **VAC** no se puede saber el positivo y el negativo
Si cierro una con un conductor es corto, por ejemplo si en un enchufe conecto un cable.

Valor pico o valor cresta

Cuando nos patea lo hace con 300 Voltios (en el valor cresta)

Todos los cálculos se hacen a valor eficaz no valor pico. Los capacitores se cargan a valor pico.

La tensión y la intensidad deben trabajar en fase. Mientras no haya trabajo no hay intensidad. 
Si pongo un amperímetro no me marcada nada porque lo que consume es la potencia. 311 voltios es el pico.

##### Triángulo:
```
W
E|I
I=w/v I=2500/220 = 11,36 amperes
```

Si coloco una pinza me tiene que dar 3,333 watts. Los voltios son una constante. El amper es un resultado de la potencia.  No puede estar fuera del ciclo.
#### ¿Que significa que esté fuera de ciclo?
Significa salir de face cuando son distintos de la fase. Esta mal la onda del seno.
Hay casos especiales para que el ciclo esté fuera de fase: Lo único que nos puede saber de fase es un motor. Sólo los motores en donde las bobinas trabajen en paralelo.

Bobinas de arranque, bobinas de trabajo.
Si se usa una bobina para que arranque y cuando arranque no se la usa más ahí no puede hacer un desfasage.

Aire acondicionado trabajan con bobina en paralelo  .
Entonces eso me obliga a buscar favor de potencia  .
1=1 la potencia nominal es igual a la potencia que consumo  .
Si yo tengo un motor que me produce un desfasar 1=0.65.

Se puede mejorar el desface con un capacitor.

En qué caso yo tengo 1=1 (dos bobinas) en las cargas descripción y en las cargas disruptivas. Cuando las placas tienen bobina corrigen un factor de potencia.

La corriente alterna este constantemente en alternancia.

Es una batería cuando tengo un conjunto de pilas. La batería de auto contienen 6 vasos. Y son independientes. Cada una genera su propio voltaje. Borner se llama. Cuando hace un puente se llama serie.  Cuando llegó al final el borner será negativo.  Voy aumentando (inaudible)?.

Si uno dos batería me suma el voltaje. Cuando pongo pilas en serie suma el voltaje: 3 pilas 3,5 voltios.

La lamparita no debe ser más de 5 voltios. En serie no sube el amperage.

Si algo está conectado en serie en paralelo explota. Conectamos dos baterías en paralelo. Sacar borner al conectar batería. Tomás mi borner negativo y positivo y conecto al motor.  Motores de corriente continua puedo conectar al reves para que gire al otro lado.

Se dice campo porque tiene una expansión el voltaje es un campo de fuerza.  La intensidad son partículas de electrones.  Cuando yo conecto algo la fuerza sale desde el polo positivo al negativo.  Es un ciclo.


Colocamos una lamparita en la batería para que exista un trabajo eléctrico. La fuerza del voltios la energía pasara por cuando ciero el circuito produjo un trabajo eléctrico.
Si yo agarro un multímetro en la escala de corriente continua mido haga 20 voltios.

Elijo el superior más cercano. Si mido en la escala menor puedo destruir el tester. El negro va en común el rojo mide voltios resistencia.  Uno es negativo el otro positivo. Si invierto no pasara nada, solo que me macará el voltaje al reves por ejemplo: -12v.  A los extremos de la batería le podemos decir borner.

Se dice que el voltaje de la coffiege de la energía eléctrica va desde el borner positivo al negativo. Cuando agregamos una llave o switch. Puedo elegir si quiero que este abierto o cerrado.

Si está abierto no hay circuito esta apagado. Si cierro la llave pasa la electricidad. Cuando se cierra hay un trabajo eléctrico.
El voltaje se mueve desde el polo positivo al negativo.

Cuando cerramos la llave se genera una fuerza voltaica. Cuando uno cierra el circuito eléctrico se logra mover los electrones. La teoría dice que cuando yo genero la fuerza voltaica los electrones se mueven.  La fuerza voltaica que vienen desde el polo positivo al negativo desde el polo negativo salen los electrones.  Viajan hasta dentro de la bateria.  El movimiento de los electrones esta dado por segundo. Cuantos electrones pasan por segundo firman el amper. 1 amper: 4.73 trillones de electrones en 1 segundo.

Para que se forme 1 amper necesito electrones. El trabajo del amper esta dado por hora. Cuando ocuopo un conductor de menor amperaje. Cable 15 amper por hors.
A lo largo del tiempo si pide mucho amper consumirá más temperatura. Corriente eficaz es 220 voltios. Si consumo mas amperaje se calentara más por la fricción de los electrones las partículas.

En un conductor adecuado la fricción de los electrones es mínima. Los electrones son unos loquitos. Tienen muchos movimiento. Esos electrones generan movimiento. Ese roce genera temperatura.
Si el cable es grueso va a calentar sólo las patas del enchufe.

El amperaje hace que se derrita el cable. La zapatilla cada uno soporta 10 amper pero hay que saber cuánto aguanta el cable.

Lo que cambia es el amper. La resistencia del secador mide más amper. El motor tiene menos amper. La electricidad es la tensión por intensidad. Voltaje mueve electrones. Voltaje es una fuerza. La fricción de los electrones hace que la lámpara encienda. Cuando sea más fuerte el voltaje mueve más los electrones. Si agaero una lamparita de 45 wats el de 220 pongo en el auto y no prende.

Pongo una lamparita de otro voltaje a 220 y explota. Cuando hablamos de cargador.

#### Como se carga la batería de un auto
se carga a través del alternado un generador.
Puede haber un sistema de generador como un dinamo.
Hay motos que tienen alternadores.
Y hay otros que tienen dinamo.
Los reguladores de voltaje son diferentes.
La batería tiene corriente directa.
##### Si mi moto tiene un alternador que pasa.
La corriente alterna con la continua explota.
Hay forma de que la corriente alterna pase a continua.
Se llama **rectificación** ese proceso.
El transformador transforma el voltaje.
El rectificar modifica la corriente alterna a la continua.
El transformador tiene 4 puntas de cable y 2 bobinas.
Quiere decir que ese transformado en dos puntas va a tener dos bobinados: Principio y final.
Bobinado primario y secundario.

Tiene que ver la cantidad de vueltas del bobinado.
El núcleo es lo que me falta.
Lo voy a recuperar a través del núcleo.
**Mi núcleo es hiero al silisio.**
No puede ser hierro al cromo.
La corriente alterna tiene ciclos.
50 ciclos por segundo.
Un medio ciclo positivo y un medio ciclo negativo hacen 1 ciclo.
Los primeros transformadores tenían el núcleo de hierro a siliciio.
Tengo que generar el campo magnético y al siguiente ciclo tiene que desaparecer.
Tienen que imantarse y desaparecer.
El campo magnético se abre para todos lados.
El campo magnético aparece en un monto del ciclo positivo y ahi se imanta.
Hay un campo magnético creado y uno que se están creando.
El campo magnético se crea desde 0 hasta la crezca maxima de voltaje.
Pero en el momento que desaparecer la energía el otro campo magnético empieza a crecer y comienza a imantar la bobina.
Y ahí recién empiezo a a tenrer voltaje.
La primer fuerza voltaica sale del norte.
Dentro de la fase está el positivo y negativo porque tengo los ciclos.
Para pasarlo a corriente continua tengo que retificar.
El campo magnético tienen polo norte y polo sur.
La brújula es una aguja imantada.
Una de las leyes del magnetismo polos iguales se rechazan polos distintisbse rechazan.
El polo de la aguja es un acomodamento visual.
Nunca la aguja de la brújula me dicen que es norte añ.
Para que sea norte tiene que ser sur.
Los amplificadores marcan la raíz media cuadratica.
La electricidad tiene polos positivo y negstivo.
Y el magnetismo tiene polo sur y polo nortr.
La variación del semiciclo me genera una variación de polos.
No tengo electricidad tengo campo magnéticos.
La finalidad de la energía eléctrica que le pongo a un transformador es generar un campo magnético.
Tengo que magnetizar el núcleo.
Cuando mi gneerador llega a 0 ahí recién sale.
Lo que ocurre en el primero no tiene nada que ver con el bobinado secundario.
En el secundario es un campo magnético.
Es la cantidad de espiras.
Si pongo 100 de un lado y 100 del otro de un lado tendria 120 voltios y el otro también.
Lo que esta en el medio se llama aislaión garbánica.
**Si pongo resistencia no hay aislacion galbanica.**
Los rulos que tengo en el bobinado se va combinando con la energía eléctrica que pasa.
De un lado del conductor tengo energía eléctrica.

La pinza amperímetrica me dicen que campo magnético hay. Y a través de circuitos electrónicos me dice el amperaje. 
De un lado del bobinado tengo 220 con 100 vueltas bobina y del otro lado 22V.
De los dos lados voy a tener corriente alterna.
Si conecto transformador a la pared en el bobinado primario entra 220 y sale 16 voltios en el bobinado secundario.
Cuánto más número de espinas más voltaje.
A medida que le voy sacando rulos le voy sacando voltaje.
No se puede hacer trabajar ningún transformador con corriente continua.

Placa de aire acondicionado chip madre jungla.
Para que funcione se necesita una fuente se forma con transformador diodos filtros, controladores de volrakev. Para que sea continuo el voltaje.

El chip opera para que se encienda el motor.
Arranca con 30 amper y 220 voltios.
Necesita de otros componentes transistores trey y relay.
El chip ordena en un lavaderrapas que se cargue el aggua.
Tienen que dar ordenes que cargue el agua.
Se encarga de qienel motor gire para un y.el otro lado.
Los nuevs motores trabajan por pulso.
Se necesitan las dos.
Corriente continua y alteena.
Sibes continua pura oñ.
O puntante.

Núcleo de ferrita.
N.
S.
N.


Boca puertas.
Vamos a ver los filtros componentes delnresgusrdo.
Relays.
Sugerencia: traer cosas de la clase pasada.
Conseguir cosas para arreglar.
Pinza tester destornillador pinzs.
Fijarse en el selector de fusiones.
Que debe tener un selector de fusiones:.
Hay uno chiquito que no tiene para.medir capacitores.
Muchas de las cosas que fallan es por capacitoe.
Que debe tener nuestro selector para medir omnios.
Que es para medir resistenxiac.
Resistenxiac.
Debe tener para medir voltaje directo o pulsante.
Debe tener para medir voktskense corriente alterna.
Debe tener para.medie amper.
De continua alterna.
Y para.medir faradiis.
Faradios.
Hay uno que traen para medir frecuencia temperatura.
No importa.
Hay de diferentes escalas para medir capacitores por lo menos 200 microfaradiis.
UF.
Pinza amperímetrica.
Lápiz soldadores.
Para soldar estaño.
Hay de 3040 wats.
Nunca en el piso herramienta.
La herramienta no se presta.
Hay que hacer una serie.
Un enchufe como si fuera dos cables.
Fase y neutro.
Vamos a tener un porta lámparas de 10.
Y en el centro otro portalámparas de 10.
Tiene dos tomas.
Los dos estén en serie.
Porque sino corta luz escuela.
En la plaxita venden portalámparas.
Con enchufe.
Y tiene una llave cita del encendido y apagado.
Hay unos triples que.
Puedo comprar 5 porque de acuerdo a la potencia.
Si tengo un motor de 100 wats.
Siempre queda en serie.
El triple va en el medio.
Con 1 triple llegó a 300 wats no me da para el motor.
Puedo colocar 5 de focos.
Se usa para arreglar placas.
Con la serie si hay queda en corto me prende la lampara.
Es un imitador de amperake.
Si la carga tienen un corto prende el foco.
Sino el foco prende un poco.
Un enchufe dos tomas.
Un tipo llevo ventiladores.
La punta de prueba llevar.
Philips pinza de fuerza chica.
Pinza de punta.
Pinza amperímetrica soldador.
El otro que no es busca polo.
Cita aislante busca polo.
Termocontraible para cable de dos milimrtros.
1 metro yn1 netro.
Metro.
Punta de precisión.
si pones un cable en el enchufe XD.
cargas resistivas.
Hay que saber que cable usar por la bajada de tension.
para conectar una ducha.
ta mal.
una lamparita de 45 wats de 220 voltios no prende en el auto.
mal 12 voltios conecto a 220 voltios y explota.
el alternador es un generado.
50 hertz.
en el nucleo.
el chip que trabaja en energia continua.
### Fin clase 1

Fotocelda mecánica es mejor que fotocelda electrónica

https://redirect.invidious.io/playlist?list=PLuzS0jdNRVvoyXZYCFMJuHj7OhStWKeK1

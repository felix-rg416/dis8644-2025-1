# Proyecto 01

## Grupo 6

Antonia Fuentealba

Sofía Pérez

Félix Rodríguez

Izhak Villegas

## PREMISA/PLANTEAMIENTO

¿Cómo podríamos modificar un APC para que sea lo más parecido posible a un instrumento musical tradicional?

En este proyecto nos planteamos la idea y la duda de cómo las frecuencias de las notas musicales podrían ser replicadas, a través de un circuito electrónico a partir de un _Atari Punk Console_.

¿Cómo se genera una nota musical?

Una nota musical es una vibración del aire a una cierta frecuencia (medida en Hertz). Por ejemplo, la nota La (A4) vibra a 440 Hz.

La APC genera ondas cuadradas con frecuencias variables. Esas ondas sonoras entran en un altavoz, el cual vibra a esa frecuencia, y nuestro oído lo percibe como una nota.

Es por esto que nuestra decisión fue modificar el APC  para generar notas musicales a través de cables que conectan ondas eléctricas de distintos objetos, ya sean orgánicos o metálicos, simulando de esta forma una especie de teclado, que gracias a la suma de resistencias genera una frecuencia más grave o más aguda dependiendo del objeto que transmite la onda. Esto a través de un circuito que sería astable, debido a sus estados de on/off, al momento de presionar botones y accionar los clables en contacto con objetos. Además es un circuito robusto, que no es frágil en su fisicalidad, ya que cuenta con una carcasa exterior impresa ne 3d que protege el circuito solsdado en la pcb.

“Cada nota musical tiene una frecuencia principal, que indica cuántas veces por segundo vibra el elemento que la produce. La frecuencia producida por un temporizador 555 en modo astable depende de los valores del condensador (C) y dos resistencias (R A  y R B )”
Instructables. (2024, 6 marzo).
Simple Electronic piano. Instructables. <https://www.instructables.com/Simple-Electronic-Piano/>

Esta relación es:

![formula frecuencia](./archivos/formula.jpeg)

### ANATOMÍA FÍSICA, DIAGRAMAS, ILUSTRACIONES, TEXTO

### CAJA NEGRA (ANATOMÍA FÍSICA)

## Teclado musical APC

Cuenta con una carcasa, con 5 orificios (sin contar el parlante ni el conector a la batería), por donde salen cables que se conectan a caimanes y a su vez, a objetos metálicos y orgánicos, también un botón, cables y un potenciómetro que, al accionar cada uno de estos, genera una frecuencia distinta, la cuales son capaces de oírse a través de una bocina o parlante.
La carcasa contiene el circuito soldado a la placa perfboard con todos los componentes utilizados (BOM)

[Imágenes del teclado musical y sus partes]

![objeto_impreso](./archivos/pcb-cajita/objeto_impreso.jpeg)

![objeto_impreso(2)](./archivos/pcb-cajita/cajita.01.jpg)

![objeto_interior](./archivos/pcb-cajita/objeto_interior.jpeg)

### DIAGRAMA

A continuación se presenta el esquemático realizado para la construción del circuito e ilustraciones del planteamiento de cómo sería esta esquematización.

![proceso esquematico](./archivos/bitácoras/esquematico.jpeg)

![proceso esquemático 2](./archivos/bitácoras/esquematico01.jpeg)

![esquema PCB v01](./archivos/pcb-cajita/esquema.PCB.v01.jpg)

![atariPunk_tinkercad](./archivos/tinkecad.png)

## BITÁCORAS

### Bitácora Anto

![ilustraciones+pauta](https://github.com/user-attachments/assets/d9cf7cdb-72ed-40ac-83de-da013afd2faf)

![experimentaciones](./archivos/bitácoras/anto.feuntealba/bitacora.anto.03.jpeg)

![esquemático+resistencias](./archivos/bitácoras/anto.feuntealba/bitacora.anto.04.jpeg)

![diagrama_de_flujo](./archivos/bitácoras/anto.feuntealba/bitacora.anto.06.jpeg)

### Bitácora Sofía

![bitácora( 1)](./archivos/bitácoras/sofía/bitácora.sofía.01.jpeg)

![bitácora (2)](./archivos/bitácoras/sofía/bitácora.sofía.03.jpeg)

![bitácora (3)](./archivos/bitácoras/sofía/bitácora.sofía.04.jpeg)

![bitácora (4)](./archivos/bitácoras/sofía/bitácora.sofía.02.jpeg)

### Bitácora Izhak

![bitacoraa(1)](./archivos/bitácoras/izhak.villegas/bitacora.izhak.01.jpeg)

![bitacoraa(2)](./archivos/bitácoras/izhak.villegas/bitacora.izhak.02.jpeg)

![bitacoraa(3)](./archivos/bitácoras/izhak.villegas/bitacora.izhak.03.jpeg)

![bitacoraa(4)](./archivos/bitácoras/izhak.villegas/bitacora.izhak.04.jpeg)

![bitacoraa(5)](./archivos/bitácoras/izhak.villegas/bitacora.izhak.05.jpeg)

![bitacoraa(6)](./archivos/bitácoras/izhak.villegas/bitacora.izhak.06.jpeg)

![bitacoraa(7)](./archivos/bitácoras/izhak.villegas/bitacora.izhak.07.jpeg)

![bitacoraa(8)](./archivos/bitácoras/izhak.villegas/bitacora.izhak.08.jpeg)

### Bitácora y proceso Félix

![pcb-b 01](./archivos/pcb-cajita/pcb-b.01.jpg)

![pcb-b 02](./archivos/pcb-cajita/pcb-b.02.jpg)

![pcb-b 03](./archivos/pcb-cajita/pcb-b.03.jpg)

![pcb-b 04](./archivos/pcb-cajita/pcb-b.04.jpg)

![pcb-f 01](./archivos/pcb-cajita/pcb-f.01.jpg)

![pcb-f 03](./archivos/pcb-cajita/pcb-f.03.jpg)

![pcb-f 04](./archivos/pcb-cajita/pcb-f.04.jpg)

## PROCESOS

![collage](./archivos/pcb-cajita/collage.png)

[Videos de muestra del proceso en _Proto_]

<https://github.com/user-attachments/assets/790efdef-d78c-4d19-b25d-af472468af7d>

<https://github.com/user-attachments/assets/fc261a51-aa6d-4029-83d4-fa57e76a6de4>

## ESQUEMÁTICO ELÉCTRICO, BILL OF MATERIALS, CITAS Y REFERENCIAS

![esquemático final](./archivos/esquematico.jpeg)

## BILL OF MATERIALS (B.O.M)

| Tipo                  | Cantidad | Nombre                  | Valor      |
|-----------------------|----------|-------------------------|------------|
| Perforated board      | 1        | PB                      |            |
| Batería               | 1        | BAT.                    | 9 V        |
| Resistencias          | 8        | R1, R2, R3, R5, R6, R7, R8 | 1k      |
| Resistencias          |          | R4                      | 10k        |
| Condensador cerámico  | 3        | C1, C2, C4              | 100nF      |
| Condensador electrolítico   | 1  | C5                      | 100uF      |
| Condensador           | 1        | C3                      | 470nF (474)|
| Jumpers               | 12-17    |                         |            |
| Bocina                | 1        | Speaker                 | 0.5W/8Ω    |
| Caimanes              | 5        |                         |            |
| Circuito integrado    | 2        | Chip 1, Chip 2          | 555        |

Para nuestro proceso nos referenciamos en el piano electrónico creado por Joshua Brooks.

"La electrónica puede producir sonidos muy fácilmente con solo unas pocas piezas".

<https://www.instructables.com/Simple-Electronic-Piano/>

## CONCLUSIÓN

Finalmente a la hora de probar por primera vez nuestro circuito nos dimos cuenta que no funciona
¿qué errores hay?, ¿son solucionables?, ¿se puede llegar al resultado deseado?
Pedir retroalimentación.
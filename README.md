                                                         PROYECTO-PARCIAL-1
 
 INTEGRANTES:
 
 Danny Guallpa
 
 Joshua Rivera 
 
 Juan Salazar 


1. OBJETIVOS 

- Generales: 

 - Simular y poner a prueba los distintos casos que se pueden dar con el fin de encender una led.
 
 - Aplicar conceptos previos a la realización del proyecto, con el uso de definiciones ya conocidas.
 
 - Aprender sobre los componentes electronicos que estamos manupulando.

- Especificos: 

- Aplicar los conceptos aprendidos como circuitos en serie y paralelo.

- Analizar el volatje junto al potenciometro en funcion al efecto que tiene en los leds.

- Localizar fallas en circuitos.

- Aplicar lo aprendido en los laboratorios y el cimulador.

MARCO TEORICO:

Detector de luz transistorizado

Este circuito detector de luz transistorizado permite activar un dispositivo de iluminación u otro, por medio de un relé cuando la intensidad de la luz del día ya no es suficiente.

Funcionamiento del detector de Luz transistorizado

El elemento sensor de la intensidad de luz es un LDR (fotorresistencia) cuya resistencia depende de la intensidad de luz que lo incide. A mayor cantidad de luz, menor resistencia en el LDR y viceversa. Para ajustar el nivel de luz, con el cual el relé se debe activar para conectar la iluminación artificial, se utiliza el potenciómetro P.

![image](https://user-images.githubusercontent.com/117873786/205939051-ccd3bb44-cfd2-4908-9113-df6b78a76016.png)

Cómo Construir

Primero, conecte el terminal de contacto del potenciómetro de 10 KΩ al terminal inversor del amplificador operacional. Luego, cree una unión de conexión entre el LDR y la resistencia de 10 KΩ. Como resultado, creará un divisor potencial que alimenta la salida al amplificador operacional.

Además, cree una conexión entre el LED blanco y la resistencia de 220 Ω. Luego, conecta tu fuente de alimentación de 9v al circuito y prueba para ver si funciona.

Cuando iluminas un poco el LDR, debería disminuir su resistencia. Y el voltaje inversor será más alto que el voltaje no inversor, lo que mantiene el LED apagado.

Si no hay luz incidente en el LDR, tendría una mayor resistencia. Como resultado, el voltaje inversor será más bajo que el voltaje no inversor. Por lo tanto, la salida del OP-Amp aumentará y encenderá el LED.

PROCEDIMIETO:


1. Materiales: 

• Protoboard

• Resistencia de 220 Ω

• Resistencia de 10k Ω

• Leds

• Fotorresistencia o fotocelda

• Cable para conexiones

• Fuente de voltaje de 9v

• Potenciómetro de 100k

• Transistor Bipolar NPN 2N3904

2. Proceso:

- Conectamos el transistor y lo polarizamos a negativo en su pin emisor.

- Conectamos dos diodos en serie al emisor del transistor.

- Conectamos una fotocelda a la base del transistor y a negativo.

- Conectamos la resistencia y el potenciómetro en serie.

- Hacemos una conexión desde el pin medio del potenciómetro hasta la base del transistor.

- Finalmente conectamos la fuente de alimentación para que nuestro circuito empiece a funcionar.

- Notamos que al obstruir la fotocelda los leds se encenderán, mientras tanto permanecerán apagados.


Simulacion de circuito:

![204463465-89f5d8c1-7327-430b-9727-07e01b25084f](https://user-images.githubusercontent.com/117873786/204558903-9acde561-577c-4ed4-8fa7-d672b4410a32.png)


Armado del circuto:

![d62c1eae-7cab-4026-87b1-33a1e4b733a0](https://user-images.githubusercontent.com/117873786/205934623-31607c1c-10e7-4c31-87fe-cb869393f868.jpg)

![d8100874-d296-4060-ad6e-5ea72d4ea186](https://user-images.githubusercontent.com/117873786/205934697-d95ff903-8385-4854-9c44-cc0f5e63c3ec.jpg)

![d49585ec-6809-4c22-8a6c-f8567ad7126f](https://user-images.githubusercontent.com/117873786/205934721-9e9b9e46-0fa3-4aba-8db0-ca948310b3cc.jpg)




4. VIDEO


https://uespe-my.sharepoint.com/:v:/g/personal/dxguallpa_espe_edu_ec/EQQUU0D492JOnEp9sk6PUj4Bk5j2lgCy5aXQR8LhtV2LqQ?e=PR712o

5. CONCLUSIONES


• En un circuito se pueden encontrar que muchos componentes estan en en serie y en paralelo, junto a lo aprendido amteriormente ya sabemos como pasamos de una simulacion a un circuito real.

• Los componentes de dicho circuitos como el trancistor y el fotoresistor dan una nocion de ideas que podemos aplicar en diversos aspectos.

• Hay muchas formas de armar el circuito, no especificamente como en el video, entonces buscamos una forma de que funcione pues hubo dificultades.


6. BIBLIOGRAFÍA


Circuitos de detección de luz:una manera fácil de detectar la luz. (n.d.). Mfgrobots.com. Retrieved December 6, 2022, from http://es.mfgrobots.com/mfg/it/1003029802.html

Detector de luz transistorizado - Electrónica Unicrom. (2018, March 28). Electrónica Unicrom. https://unicrom.com/detector-de-luz-transistorizado/





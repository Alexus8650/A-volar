# A-volar
## DESCRIPCIÓN DEL PROYECTO
En este proyecto el objetivo clave es dar la vuelta en forma de infinito a dos columnas con un dron que hay afuera de la clase de robótica. Somos 14 en clase, y hemos hecho 4 grupos, asique 2 de 3 y 2 de 4. En cada grupo tenemos que hacer el infinito de una manera distinta, y cada participante de cada grupo debe empezar y acabar el infinito con una orientación diferente. Este es el recorrido de mi grupo y mi orientación de inicio y final:
![](https://github.com/Alexus8650/A-volar/blob/b41d666dd22c47ef444ec1ade85a98302b956dcc/gta.PNG)

La flecha negra es el recorrido, la flecha roja es mi orientación, el circulo cian es el punto de salida y final y los cuadrados verdes son las columnas.

## DESCRIPCIÓN DEL DRON
La definición de dron en la RAE es: Aeronave no tripulada. Al fin y al cabo es un robot que vuela no tripulado (no transporta a personas con él) que se controla o remotamente o con un programa pre-instalado en él, este al ser un robot tiene sensores y actuadores para relacionarse con el medio y todo lo de más que pueda tener un robot normal lo puede tener un dron.
El dron que vamos a usar es el Tello, es un cuadricóptero (tiene 4 hélices), con un motor y un protector de hélice en cada una (4 en total), tiene una cámara y al lado de ella un Led RGB el cual indica el estado del dron según el color emitido, 2 antenas para la comunicación, un sistema de posicionamiento visual (es un sensor de ultrasonidos para detectar la distancia del suelo a la que está posicionada la aeronave), batería para la fuente de energía, un puerto micro USB y no menos importante el botón de encendido y apagado del dron justo en la parte opuesta de este. Aquí tenemos varias imágenes de un dron que usaremos y otra a modo de explicacíon de lo anterior:
![](https://github.com/Alexus8650/A-volar/blob/a547b898540c254bb7a70a508de72580c4808184/gta1.PNG)
![](https://github.com/Alexus8650/A-volar/blob/910c1b0cdebedd6b1b032551df74790c62e24870/IMG_20260306_094312.jpg)

![](https://github.com/Alexus8650/A-volar/blob/6788fe7db5c8ad39f7ac2a6620a5813550d31635/IMG_20260306_094347.jpg)

## NORMATIVA EUROPEA DE VUELO
La normativa europea de vuelo de drones clasifica los drones en 7 clases, cuanto más grande sea el número de la clase, más grande, y por lo tanto, más peligroso será el dron. La normativa obliga a todos los drones poner una pegatina en la que se indique la clase en la que está y la matrícula del dron. El Tello está en la clase 0, esta clase se caracteriza por tener un peso de menos de 250g y una velocidad máxima de 19 m/s.

## ¿CÓMO TE DEBES CONECTAR AL DRON PARA PODER CONTROLARLO?
El Tello usa vía Wifi para la conexión con el maestro que lo controle, ya sea el teléfono para controlarlo como si fuese un mando o un programa para que haga los movimientos que queramos. Te tienes que conectar a la Wifi del Tello, saldrá como "TELLO-XXXXXX", en las "X" saldrá la matrícula del dron, para diferenciarlos de otros. Nosotros usaremos la programación, lo programaremos con DroneBlocks.
![](https://github.com/Alexus8650/A-volar/blob/89f7c2e2f9008c0997d33a663d7223cb326388d5/DB.PNG)

## PROGRAMACIÓN CON DRONEBLOCKS
DroneBlocks es la plataforma con la que vamos a programar el dron. Es una programación muy sencilla de bloques en la cual nos encontramos con 8 apartados a la izquierda, cuando sean pulsados se abrirá una interfaz de los bloques correspondientes a la categoria seleccionada.
1. Take off: Tenemos el bloque de "Take off" que es el bloque de inicio que tiene que tener todo programa, que hace que se inicie el dron.
2. Navigation: Tenemos todo lo que es el movimiento del dron, arriba, abajo, derecha izquierda, delante y atrás, junto a las curvas.
3. Flip: Aquí tenemos lo que son los "Flips", dar una vuelta completa de campana, o como se podría llamar tambien, un backflip, frontflip o lateralflip.
4. Loops: Los bucles se estacionan aquí, simplemente repite lo que le pongas las veces que le digas, una parte esencial para la programación.
5. Logic: Lógica, los "if" y los "when" se localizan aquí.
6. Math: Aquí tenemos las sumas, rectas, multiplicaciones y divisiones para el programa, normalmente usadas con los "if" y "when".
7. Variables: Las variables, la creación y asignacion de números a variables están aquí.
8. Land: Tenemos el último bloque de todo programa, aterrizar.

Una vez elegida la categoria se selenciona el bloque preferido y se arrastra a la zona de programación.
Aquí tenemos una imagen de la interfaz que tiene un programa hecho con Take off, varias curvas con Navigation y Land:
![](https://github.com/Alexus8650/A-volar/blob/06196b8a79ed01029124f3401d608ea057f7cbfa/DBI.PNG)

## APLICACIONES DE LA DRÓNICA
Este proyecto es solo una minuscula demostración de lo que se puede hacer con los drones, son robots, entonces sirven para ayudar a la humanidad. Voy a decir 3 maneras de usar este aparato volador:
· Polinización Artificial:

# Laboratorio-5
- INTEGRANTES : Boza Paul

- NRC:10069

- FECHA: 10 de Enero de 2023
 
- Objetivo General.-

Analizar y desarrollar ejercicios de circuitos aplicados al teorema de Thevenin, descomponiendo sus propiedades, que permitan calcular mejor y de forma más sencilla variables desconocidas utilizando información teórica.

- Objetivo Especifico.-

Usando la información teórica provista en el sitio web y los tutoriales en video, describa y descubra las características correspondientes del teorema de Thevenin. Utilice el teorema de Thevenin aprendido en el aula para analizar y calcular diferentes ejemplos de circuitos y realizar ejercicios experimentales a través de simuladores virtuales.

- Marco Teorico.-

Utilizando la teoría de circuitos, se pueden adquirir nociones para entender, diseñar y modificar circuitos eléctricos. Este se encuentra definido como la interconexión de distintos componentes, formando caminos a través de los cuales la corriente eléctrica realiza un recorrido. Para que se logre que estos funcionen correctamente, es necesaria la aplicación de leyes y teoremas que permiten su construcción, obteniendo los resultados adecuados. El teorema de Thevenin es uno de los enunciados básicos de la teoría de circuitos. A través de este, es posible calcular y simplificar un sistema eléctrico.

Aplicando este teorema, se puede convertir un circuito complejo, el cual cuenta con dos terminal, a uno simple, compuesto por una sola fuente de voltaje en serie con una resistencia.

![image](https://user-images.githubusercontent.com/116833964/211582690-679aef20-db8d-45c7-a201-326b0850114a.png)

¿Qué es el teorema de Thevenin?

A través de la aplicación del teorema de Thevenin, se logra que un circuito complejo se convierta en uno más simple. De esta manera, se expresa que al estar existir dos terminales A y B dentro de la estructura de un circuito eléctrico lineal, es posible convertirlo a un circuito equivalente más simple. La teoría expresa que a través de la resistencia del circuito transformado la corriente seguirá circulando.

Calcular la resistencia de Thevenin

Para obtener el valor de la resistencia de Thevenin (RTH), es necesario realizar reemplazar cada una de las fuentes de tensión que integran el circuito original a través de un cortocircuito, mientras que en el caso de las fuentes de corriente pasarán a ser circuito abierto. A partir de aquí se procede a calcular la resistencia total del circuito.

En el momento en que se vaya a realizar el cálculo de la resistencia de Thevenin, se pueden usar diversos métodos. El más común es agrupando las resistencias en paralelo, transformándolas en una sola. De esta manera, el circuito equivalente solo deberá contener resistencias en serie. Estas deberán ser sumadas, lo que nos dará como resultado la resistencia de Thevenin. Si estamos ante un circuito de corriente alterna, entonces será necesario realizar el cálculo de la impedancia equivalente.

Calcular la tensión de Thevenin

En el circuito original se calcula la tensión existente entre los puntos A y B. La mejor manera es realizando la suma y resta de los valores de las fuentes de tensión. Lo mismo será con las caídas de tensión en las resistencias, pero aplicando en este caso las leyes de Kirchhoff, la ley de ohm u otro método válido para el procedimiento.

![image](https://user-images.githubusercontent.com/116833964/211583512-8723c724-7793-4dee-91cb-7a4d026ae97e.png)

Pasos para aplicar el teorema de Thevenin

Cuando se construye un circuito equivalente de Thevenin, es posible realizar cálculos más sencillos y en menos tiempo que al trabajar con el circuito completo original. Para lograr aplicar el teorema correctamente, se deben realizar estos pasos:

1.Al eliminar las fuentes de alimentación del circuito original, será posible encontrar la resistencia de Thevenin. 

2.Luego se deberá calcular el valor de la resistencia total que existe entre los punto A y B donde se encuentre conectada la resistencia de carga.

3.Para el caso de hallar la tensión de Thevenin, se elimina la resistencia de carga, y se calcula el voltaje de los puntos de conexión abiertos donde esta se encontraba.

4.Construye el circuito equivalente utilizando la tensión de Thevenin y la resistencia de Thevenin en serie. Conecta la resistencia de carga entre los puntos de conexión abiertos de este circuito.

5.Utilizando las reglas de circuitos en serie, se analiza la tensión y corriente de la resistencia de carga.

- Procedimiento.-

![image](https://user-images.githubusercontent.com/116833964/211584016-7afca536-f671-4dd5-a69f-6839fa4ed408.png)

_ Simulacion en Tinkercad

![image](https://user-images.githubusercontent.com/116833964/211587851-c490320d-2390-46c6-bb0c-3ad9ec49d1e8.png)

5.5.2. Mida el voltaje y la corriente en el resistor R5, anote los resultados en la tabla 5.2.

Voltaje:

![image](https://user-images.githubusercontent.com/116833964/211588826-e516c0bd-360a-4f90-a372-f4a26a0666eb.png)

Corriente:

![image](https://user-images.githubusercontent.com/116833964/211589433-8a7eff24-486c-4b76-825a-5f30e95d2732.png)
![image](https://user-images.githubusercontent.com/116833964/211617740-91a8d0d9-d087-4340-a6ac-46248f3016f1.png)

5.5.3. Desconecte el resistor R5 y mida el voltaje en el circuito abierto. Anote el valor
medido en la tabla 5.1.

![image](https://user-images.githubusercontent.com/116833964/211591623-2cd5c16f-52cc-4726-9f28-25485dfe8ac7.png)
![image](https://user-images.githubusercontent.com/116833964/211619610-9b987680-e585-4b3c-b65a-d5d5c5a088d5.png)


5.5.4. Anule el efecto de las fuentes de alimentación. Desconecte R5 y desde el circuito
abierto resultante mida la resistencia equivalente. Anote el valor medido en la tabla 5.1.

![image](https://user-images.githubusercontent.com/116833964/211592068-bfe16c55-88a3-4769-b0d9-11913ea4bcf2.png)
![Resolución por mallas_2](https://user-images.githubusercontent.com/116833964/211640514-94381ce6-750c-4227-8b1a-56303850615c.jpg)

5.5.5. Implemente el circuito equivalente de Thévenin, agregue el resistor R5 y mida la
corriente y el voltaje en el mismo, anote los resultados en la tabla 5.2.

Voltaje:

![image](https://user-images.githubusercontent.com/116833964/211594073-b299760d-4ea8-4ee6-8adc-6f0188594dc7.png)

Corriente:

![image](https://user-images.githubusercontent.com/116833964/211594395-44ba2430-d1ca-4b1f-acbd-ba2e9c321f77.png)

![image](https://user-images.githubusercontent.com/116833964/211640226-100675b0-ddcd-4e2b-a408-4db99493add6.png)

![image](https://user-images.githubusercontent.com/116833964/211640130-712067de-d76a-4190-83d0-fbfd5baeda7e.png)

- Conclusion.-

En clonclusion usando la información teórica provista en el sitio web y los tutoriales en video, describa y descubra las características correspondientes del teorema de Thevenin.

Utilice el teorema de Thevenin aprendido en el aula para analizar y calcular diferentes ejemplos de circuitos y realizar ejercicios experimentales a través de simuladores virtuales.

- Bibliografia.-
- 
Floyd, T. L. (2007). Principios de Circuitos Electronicos. Mexico: Pearson educación.

Xnomind (2020) Teorema de Thevenin explicado para que lo entiendas, Teorema. Available at: https://www.teorema.top/teorema-de-thevenin/ (Accessed: January 10, 2023). 

# Semana 1
### Lenika Elizabeth Montoya Valencia

Inteligencia Artificial es el desarrollo de agentes racionales que interactuan con un entorno.

[Imagen agente-entorno]

#### Agente de entorno:
* **Medida de desempeño/Utilidad (performance)** se tiene que dejar en claro lo que se va a hacer y la manera correcta de medirlo
* **Características del entorno** acciones posibles y acciones legales
* **Actuadores**
* **Sensores**

#### Características del entorno
* **Discreto:** Ejemplo de la aspiradora que tiene que limpiar los cuartos A y B en la menor cantidad de 
movimientos y con la menor cantidad de energía. 
  * Sus acciones: {L , -> , <- , no}  
  * Percepción *pt* =(localización, situación en loc)
  * Espacio estado: cuarto A {L,S}, cuarto B {L,S}, Y {A,B}
  * *X*= A x B x Y donde los posibles estados son x = (L,S,A), (L,L,B), (S,L,A), (S,S,B),etc

* **Continuo**: La Ubicación de un dron, es necesario saber las coordenadas en (X, Y , θ) y la altura (h) en la que se encuentra, al igual que
  (X', Y', θ') y (h') donde X'(t)= f(x(t), a(t)) y p(t)= g(x(t)). Es continuo por que hay una infinita cantidad de posibles posiciones.
* **Estático**: Permanece constante durante el periodo de tiempo en el que el agente esta tomando una desición. Ej. contenido de un libro, entornos digitales estáticos, etc. *X*t= f(at)
* **Dinámico**: Cambia con el paso del tiempo
* **Observable**: Es donde el agente tiene acceso a un estado completo y preciso del entorno en cada momento. Ej. Un juego de ajedrez. Pt=Xt
* **Parcialmente observable**: Es donde el agente solo tiene acceso a una parte de la información del entorno.
* **Determinista**: Si el siguiente estado esta determinado por el estado actual y la acción realizada por el agente.
* **Estocástico**: Si el siguiente estado se determina parcialmente por el estado actual, la acción del agente y un elemento aleatorio.
* **Conocido**: El agente tiene un modelo preciso del entorno, sus reglas, dinamicas, posibles acciones.
* **Desconocido**: El agente no tiene un modelo completo del entorno y debe aprender sobre él mientras va interactuando con él.
* **Un agente**: Un solo agente interactua con el entorno.
* **Multiagente**: Multiples agentes interactuan con el entorno.
* **Episódico**: Las acciones del agente son independientes
* **Seciuencial**: Las acciones del agente tienen consecuencias a largo plazo.

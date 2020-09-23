# Cigarrillos y fumadores

Un cigarrillo necesita de papel, tabaco y fósforos para ser preparado y fumado. Hay tres fumadores, y cada uno tiene un único ingrediente al que puede acceder todo el tiempo: papel, tabaco o fósforos. Un agente coloca sobre la mesa al azar dos ingredientes, y el correspondientes fumador debe darse cuenta, tomarlos, armar el cigarrillo y fumarlos. Luego el agente vuelve a colocar al azar sobre la mesa dos ingredientes, y así se sigue.

1. Usar `fumadores.py` como base para sincronizar el agente y los fumadores.
1. ¿Hay alguna sección crítica?
1. En vez de con flags que den cuenta si hay o no tal cosa en la mesa, realice una versión con listas. Por ejemplo `listaPapel` si no está vacía es porque hay papel (la puede llenar con cualquier cosa, con 1s por ejemplo).

## Bonus: variantes 

* Que haya tres agentes, y no una solo, uno por cada par de ingredientes. Compiten entre sí para entrar a la mesa y poner sus dos respectivos ingredientes.
* Que la cantidad de veces que el agente pone ingredientes en la mesa sea acotada.
* Que puedan haber en la mesa hasta un máximo de dos por cada ingrediente.
* Que puedan haber en la mesa hasta un máximo de dos por cada ingrediente, salvo para fósforos que sea un máximo de uno.
* Que los tres fumadores solamente ahora sean armadores de cigarillos, y que haya un único fumador. Como fumar es más lento que armar (poner los `sleep` para que se simule esto), entonces que haya una cantidad acotada de cigarrillos armados sin fumar.
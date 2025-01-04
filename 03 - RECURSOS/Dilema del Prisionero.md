# Historia
1950, Corporación RAND, Merrill Flood y MElvin Dreshar.

# Problema
Un cofre de dinero y dos jugadores
Tienen dos opciones, cooperar o no cooperar.
Situaciones:
1. Los dos cooperan --> 3 monedas para cada uno.
2. Uno coopera y el otro no --> El primero se lleva 1 y el otro 5 monedas.
3. Ninguno coopera --> Los dos reciben 1 moneda.

# Inicio
1. Primero el otro coopera, :) y yo no coopero --> Yo gano 5. Siempre conviene
2. Primero el otro coopera, :), y yo coopero --> Ganamos 1 cada 1
- Mismo resultado si empiezo yo --> el otro nunca coopera, el resultado es poco óptimo cuando ambos podrían haber recibido 5.
> Los Impalas se quitan las garrapatas entre sí. Acicalar a otro supone esfuerzo, tiempo, saliva, etc. pero uno mismo no llega, lo necesita.
> Si solo se da una vez, beneficia no cooperar, pero generalmente no es así.
> Al pasar muchas veces, si uno sabe que no vas a cooperar, el otro puede usar eso en el futuro.
> ¿Cuál es la mejor estrategia entonces?

# Torneo
Robert Axelrod. 1980. Competición de programadores de software para competir en el juego.
Cada estrategia se enfrentarán a todos los demás y a una copia de sí misma y cada duelo tendría 200 jugadas.
El torneo se repitió 5 veces.
Ejemplo. Empieza cooperando y no coopera solo cuando el otro no coopere dos veces seguidas:

| S   | S   | S   | S   | N   |
| --- | --- | --- | --- | --- |
| N   | S   | N   | N   | S   |

Se recibieron 14 estrategias mas 1 al azar. 
Estrategias:
1. Friedman: Empieza S, pero si el otro N, ya no coopera nunca mas.
2. Josh: Empieza S y hace copia de lo que hace el otro, pero una de cada 10 veces no coopera.
3. Graaskomp: Es como Josh, pero a la jugada 50 no coopera.
4. Tit for Tat: Empieza cooperando y luego copia lo que hace el otro, pero si el otro N solo hace N una vez. Esta estrategia ganó.


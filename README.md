Dune

El planeta de Arrakis es un gran desierto, por lo que el agua es un recurso escaso y codiciado. Irónicamente, el recurso más codiciado del universo por sus propiedades como combustible, 
la Especia, es tremendamente abundante. 

En Arrakis habitan los Fremen, 
una tribu que venera al agua y a la Especia de forma religiosa. 

Ellos viven con la esperanza de encontrar un elegido que libere al planeta de la explotación de la Especia por parte del Imperio. 


Los Fremen 

La tribu está compuesta por varios Fremen. Cada Fremen tiene un nombre, un nivel de tolerancia a la Especia, una serie de títulos y una cantidad de reconocimientos.  

Ejemplo:
Stilgar tiene un nivel de tolerancia a la Especia de 150 y el título de "Guía". Fue reconocido 3 veces. 

Se pide:
Averiguar cómo queda un Fremen al recibir un nuevo reconocimiento.

Saber si hay algún candidato a ser el elegido. Son candidatos quienes tengan el título de "Domador" y una tolerancia a la especia de más de 100.

Hallar al Elegido: Es el Fremen de la tribu que más reconocimientos tenga entre los candidatos a serlo. 

Gusanos de arena

Se conoce su longitud, su nivel de hidratación y una descripción. 

Los gusanos se reproducen. Dados dos gusanos, la cría nace de la siguiente manera:
Su longitud es el 10% de la máxima longitud de sus dos progenitores
Su nivel de hidratación es 0
La descripción es la concatenación de ambas descripciones de sus progenitores. 

Ejemplo:
Un gusano de longitud 10, hidratacion 5 y descripción “rojo con lunares”

Otro gusano de longitud 8, hidratación 1 y descripción “dientes puntiagudos”

La cría entre estos dos gusanos debería tener de longitud 1, hidratación 0 y descripción “rojo con lunares - dientes puntiagudos”
Se pide:
Obtener la lista de crías que surge de aparear dos listas de gusanos, uno a uno. En caso que un gusano no tenga con qué otro gusano aparearse, obviamente no hay cría. Por ejemplo, el primero de la primera lista con el primero de la segunda lista, los segundos entre sí y así sucesivamente.
Importante: No vale usar zipWith


Misiones

Los Fremen realizan misiones para sobrevivir en el desierto donde proliferan los gusanos. Las misiones son:

Domar gusano de arena: Un Fremen puede domar a un gusano de arena si su nivel de tolerancia a la Especia es al menos la mitad de la longitud del gusano. Al hacerlo, obtiene el título de "Domador" y su tolerancia a la especia aumenta en 100 unidades. Si no lo puede hacer su tolerancia a la Especia baja un 10%. 

Destruir gusano de arena: Un Fremen puede destruir a un gusano de arena si tiene el título de "Domador" y si su nivel de tolerancia a la Especia es menor que la mitad de la longitud del gusano. Al hacerlo, recibe un reconocimiento y su tolerancia a la especia aumenta en 100 unidades. Si no lo logra, su especia baja un 20%. 

Inventada: Inventar otra misión que un Fremen pueda hacer con un gusano, que también se pueda realizar dependiendo de cómo sea el gusano en relación al Fremen y que provoque consecuencias diferentes sobre el Fremen si lo logra o no.

Se pide:
Simular la realización colectiva de una misión: Dada una tribu, una misión cualquiera y un gusano de arena, hacer que cada uno de los Fremen de la tribu intenten llevar a cabo la misión con dicho gusano, obteniendo cómo queda la tribu en consecuencia.

Averiguar, para una tribu, una misión y un gusano, si el hecho de realizarla colectivamente haría que el elegido de la tribu fuera un Fremen diferente al que hubieran elegido previamente.

Al infinito 

Qué pasaría con una tribu de infinitos Fremen?
Al entrenarlos
Al querer saber si hay algún candidato a ser elegido
Al encontrar al elegido

Justificar conceptualmente
Mostrar un ejemplo de consulta y su resultado.

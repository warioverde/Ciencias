# avanze 2
- M -> prototipos con M siendo un natural.

- N -> capas de cada prototipo con N sinedo un natural.

- V_i ->valores de cada capa , tambien natural.

- Las  capas del prototipo seran los vertices de nuestro arbol binario (solo puede tener 2 hijos) , siendo v_0 la raiz del arbol.

- Si v_o > v_i => el vertice se posicionara a la izquierda de v_0. Sino , a la derecha

- A medida que se van agregando vertices , se debe repetir la regla primero con v_n y luego con V_{n+1}

- Por cada prototipo (M) habra un arbol , entonces tendremos M arboles 
# aplicando teoria de grafos

# tenemos M arboles , ahora habra que diferenciar c/u de ellos.

- en ciertos casos , el nivel puede variar , la altura del arbol y el grado de este.

- sin embargo , utilizando recorrido de arboles y comparandolos se podria obtener cuantas cantidades de formas distintas hay

# implementacion 

- armar un arbol 
- cambiar el contenido de los nodos por letras , siendo a la raiz , b el segundo hijo de la izquierda , c el de la derecha y asi..
- hacer un recorrido de estos arboles y comparar cuantas configuraciones distintas de letras hay.


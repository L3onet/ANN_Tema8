# Aspecto 1

Considera los siguientes 3 ejemplos. Construye un perceptrón multicapa con una unidad en la capa oculta. Realiza una sólo iteración para todos los patrones, suponiendo un valor umbral de 4, unos pesos iniciales wij=1 y un factor de aprendizaje = 0.6. Utiliza también una función de activación sigmoide y la regla delta generalizada como regla de aprendizaje. ¿Cuáles son los pesos finales?

| ** x1  ** | ** x2 ** | ** x3 ** | ** x3 ** | ** Clase ** |
|-----------|----------|----------|----------|-------------|
| 1 | 1 | 0 | 1 | + |
| 0 | 1 | 1 | 0 | - |
| 0 | 0 | 1 | 1 | - |
| 0 | 0 | 0 | 1 | + |

# Aspecto 2

Se cree que los niños aprenden mediante un proceso llamado razonamiento por analogías, en el que intentan asociar objetos parecidos a otros que ya conocen, y los intentan agrupar por categorías. Supón que un niño ha visto alguna vez un león en el zoo y que sabe que es peligroso, y lo ha representado internamente por el patrón (1 1 0 1 0) Un día va por la calle y se encuentra a un gato, que representaremos por el patrón (1 1 1 0 1) ¿Debe salir corriendo el niño porque crea al verlo que se parece demasiado a un león? Modela ésta situación (el aprendizaje del león y después del gato) mediante un perceptrón multicapa y mediante un algoritmo de aprendizaje no supervisado.
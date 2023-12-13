# Chess_DS_Model_Creator

Programa de python simple que toma informacion de un CSV con dos columnas, el FEN del tablero y su evaluacion, y convierte el tablero en un tensor 14x8x8, y los guarda en un fichero .npz para su uso.

El fichero Model_Creator crea una Red neuronal siguiendo el modelo de AlphaZero, sin el output de probabilidades, que devuelve un valor estimado de la posicion.

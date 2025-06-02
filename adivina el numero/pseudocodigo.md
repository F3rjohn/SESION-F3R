Main

int intento //guardar los intentos del usuario
bool adivinado = TRUE  //saber si ya adivino el numero
bool adivinado = FALSE //saber si aun no adivino el numero
int numeroSecreto //aqui almacena el numero secreto
int intentoJugador //aqui guardo el numero dado por el jugador

escribnir en consola "adivina un numero"
leer intentoJugador
numeroSecreto = Random(0,101)

while (intentos > 0 && !adivinado)
      leer intentoJugador
      if (intentoJugador > numeroSecreto && intentoJugador =/ numeroSecreto)
          imprimir "Demasiado alto"
          --intentos
finif
      if (intentoJugador < numeroSecreto && intentoJugador =/ numeroSecreto)
          impprimir "Numero bajo"
          --intentos
finif
      if (intentoJugador = numeroSecreto)
          imprimir "Felicidades, lo lograste"
          adivinado = TRUE
finif
fin while

FinMain


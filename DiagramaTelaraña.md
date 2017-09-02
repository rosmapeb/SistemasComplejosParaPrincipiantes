
# Diagrama Fase o Telaraña #

Es la forma en como se ve el atractor.
Es una gráfica cartesiana en donde se contraponen el valor inicial (Xn~) y el valor calculado (Xn+1~) [^1].

Un componente importante para evaluar el diagrama es la recta a 45° donde Xn+1~ = Xn~. Es importante por que si existe o no intersección con la recta de la función analizada habrá un punto fijo además de cero

En el caso de esta función, la gráfica representativa será una parábola invertida donde **a** determina que tan achatada esté la parábola

En este caso **a** debe acotarse a valores de 0 a 4 porque al estar acotado el plano de 0 a 1 los valores saldrían del plano

En el diagrama puede verse si es un punto fijo:

* Atractor
* Repulsor
* Neutral
* Caótico

Esto se realiza con el trazado de la trayectoria que se hace a partir de cualquier punto del eje X (Xn) en angulo de 90° con respecto a él, hacia la recta de la funcion que se analliza. Una vez hecho esto se desplaza en angulo de 90° con respecto al eje Y (X n+1), hacia la recta de 45°. Este paso se repite una y otra vez hasta saber el compoetamiento de este desplazamiento con respecto al punto fijo. Si el trazado va hacia el es un punto fijo **atractor**, si se aleja, será un punto fijo **repulsor**, y si cambia continuamente de comportamiento y nunca llega o se aleja será uno **caótico**.

El coportamiento caótico en el diagrama formar´un fractal, ya que aunque parezca lleno el espacio fase, siempre habrá huecos

## Diagrama de Telaraña en NetLogo #*





[^1]: Partiendo del modelo logistico de Malthus donde X~~n+1~~ = aX~~n~~ (1-X~~n~~).

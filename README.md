# pasapalabras

<h3>Principales funciones utilizadas</h3>

<ul>
<li>
largarTiempo: Inicia el cronómetro y actualiza el tiempo restante cada segundo. Detiene el cronómetro cuando el tiempo llega a cero.

mostrarPantallaFinal: Muestra la pantalla final del juego, actualizando los elementos HTML con la cantidad de preguntas acertadas y el puntaje.

cargarPregunta: Carga la siguiente pregunta en el juego, actualizando el contenido de la interfaz con la pregunta actual.

controlarRespuesta: Comprueba si la respuesta proporcionada por el usuario es correcta. Actualiza el estado de la pregunta y aplica estilos a los círculos correspondientes en la interfaz.
</li>

<li>
Event Listeners:

Para el botón "Comenzar": Muestra la pantalla de juego y comienza el tiempo.
Para el input de respuesta: Detecta la tecla Enter para procesar la respuesta.
Para el botón "Pasar": Permite pasar a la siguiente pregunta sin responder.
</li>

<li>
Botones de Recomenzar:

Incluye un botón para reiniciar el juego, restableciendo el estado del juego y reiniciando el cronómetro.
</li>

<li>
Creación de Elementos Circulares:

Utiliza un bucle para crear círculos representando cada pregunta del juego en la interfaz.
</li>

<li>
Inicialización:

Inicializa variables como TOTAL_PREGUNTAS, TIEMPO_DEL_JUEGO, y la estructura de preguntas bd_juego.
Configura eventos de clic para el botón de comenzar y el botón de recomenzar.
</li>

</ul>
  
</ul>


Puedes usar los bloques `preguntar`{:class="block3sensing"} y `respuesta`{:class="block3sensing"} del menú de bloques `Sensores`{:class="block3sensing"} para tener una conversación.

![Diálogo del bloque preguntar con un sí como entrada](images/ask-answer.png)

Agrega bloques a un script en el objeto que va a `preguntar`{:class="block3sensing"} algo:

```blocks3
ask [¿Encontraste todo lo que querías comprar hoy?] and wait
if <(answer) = [sí]> then
say [¡Fantástico!] for [2] seconds
else
say [Quizás debería agregar más artículos a mi tienda] for [2] seconds
end
```

**Depurar:** Comprueba que has escrito las opciones correctamente en tu código y en tu respuesta. Está bien si usas letras mayúsculas, por lo que "Sí" y "SI" coincidirán con "sí".

Agrega varias preguntas para crear un chatbot o un personaje no jugador con el que puedas hablar.

**Sugerencia:** Si usas `esconder`{:class="hide"} en el objeto que hace una pregunta, la pregunta aparecerá dentro del cuadro de entrada en lugar de como un burbuja de diálogo.

![Diálogo del bloque preguntar con una pregunta dentro](images/ask-hidden-sprite.png)


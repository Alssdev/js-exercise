# 🎮 Adivina el Número

En este ejercicio, los estudiantes deben crear un juego en el que el usuario tiene que adivinar un número aleatorio entre 1 y 100.

## 🎯 Objetivos

Los estudiantes deben:

1. Generar un número aleatorio entre 1 y 100.
2. Capturar el número ingresado por el usuario.
3. Comparar el número ingresado con el número aleatorio.
4. Mostrar un mensaje indicando si el número es demasiado **alto**, demasiado **bajo** o **correcto**.
5. Permitir que el usuario siga adivinando hasta que el número sea adivinado correctamente.

## 🛠️ Instrucciones

1. Abre el archivo `index.html` en tu navegador.
2. Edita la sección `<script>` en el archivo HTML.
3. Implementa la lógica para generar el número aleatorio y manejar las comparaciones con el número ingresado.
4. Haz pruebas para verificar que el juego funcione correctamente y que el número generado sea aleatorio.

## 💡 Pistas

- Usa `Math.random()` para generar un número aleatorio entre 1 y 100.
- Puedes usar `addEventListener()` para capturar el clic en el botón y la entrada del usuario.
- Asegúrate de proporcionar retroalimentación al usuario sobre si el número es demasiado alto o bajo.
- Utiliza `alert()` o el div `#resultado` para mostrar los mensajes.

## 📁 Estructura

> **Tu número es demasiado bajo.**  
> **Tu número es demasiado alto.**  
> **¡Felicidades! Has adivinado el número correctamente.**
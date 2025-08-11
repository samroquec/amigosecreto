# amigosecreto
Este es un proyecto simple en **HTML**, **CSS** y **JavaScript** que permite a un usuario ingresar los nombres de sus amigos y sortear aleatoriamente quién será el "amigo secreto".

##  Funcionalidades

1. **Agregar amigos a una lista**
   - El usuario escribe el nombre de un amigo y presiona el botón **Añadir**.
   - El nombre se agrega a una lista visible en pantalla.
   - No se permite agregar campos vacíos. Si el campo está vacío, aparece un **alert** con el mensaje:  
     > "Por favor ingrese un nombre válido"

2. **Visualización de la lista**
   - Cada nombre ingresado se muestra en una lista debajo del campo de texto.
   - Los nombres se almacenan en un arreglo interno en JavaScript.

3. **Sorteo aleatorio**
   - Al presionar **Sortear amigo**, el sistema elige un nombre aleatorio de la lista.
   - Muestra en pantalla el mensaje:  
     > "El amigo secreto es: `<nombre>`"
   - Si la lista está vacía, muestra un **alert** indicando que se debe agregar al menos un amigo.

##  Tecnologías utilizadas

- **HTML5** para la estructura de la aplicación.
- **CSS3** para el estilo (archivo `style.css`).
- **JavaScript (ES6)** para la lógica de la aplicación (`app.js`).

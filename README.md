# Formulario de Registro 📝

Este proyecto es un formulario de registro sencillo, creado con **HTML** y **CSS**. El objetivo principal fue construir un formulario funcional y bien estructurado, aplicando diferentes tipos de campos de entrada y utilizando CSS para darle un diseño limpio y atractivo.

---

### Enlace en vivo !

Puedes visitar la pagina en el siguiente enlace: https://magicdev-rc.github.io/formulario-registro/

---

### Elementos HTML y Propiedades CSS Utilizados 🛠️

El proyecto está organizado en dos archivos principales: `index.html` y `formularioStyle.css`, que trabajan en conjunto para crear la página.

#### Archivos HTML (`index.html`)

* **`<form>`**: El contenedor principal del formulario. Se utilizan los atributos `action` y `method` para especificar cómo se envían los datos.
* **`<fieldset>` y `<legend>`**: Se usan para agrupar campos relacionados, como la información personal o el tipo de cuenta, lo que mejora la organización del formulario.
* **`<label>`**: Vinculado a cada `<input>` con los atributos `for` e `id`, lo que mejora la accesibilidad.
* **`<input>`**: Se utilizaron varios tipos, como `text`, `email`, `password`, `radio`, `file`, `number` y `submit`.
    * **Atributos de validación**: `required`, `minlength`, `max` y `pattern` se emplearon para asegurar que la información ingresada cumpla con los requisitos.
* **`<textarea>`**: Para permitir que el usuario escriba un texto más largo en su biografía.
* **`<select>` y `<option>`**: Para crear un menú desplegable con opciones predefinidas.
* **`<a>`**: Se utilizó para crear un enlace a los términos y condiciones.

#### Archivos CSS (`formularioStyle.css`)

Se usaron las siguientes propiedades para dar estilo a los elementos del formulario:
* **Diseño y Posicionamiento**:
    * `width`, `max-width`, `min-width`: Para controlar el ancho de los elementos y hacer que el formulario sea **responsivo**.
    * `display: block` e `inline`: Para cambiar el comportamiento de los elementos y lograr el diseño deseado.
    * `margin` y `padding`: Para crear espacio entre los elementos y centrar el formulario.
    * `border` y `border-radius`: Para dar estilo a los bordes de los contenedores y los campos de entrada.
* **Colores y Tipografía**:
    * `background-color`: Para definir el color de fondo de la página y los elementos.
    * `color`: Para el color de la fuente.
    * `font-family` y `font-size`: Para seleccionar la tipografía y el tamaño del texto.
* **Selectores Especiales**:
    * `fieldset:last-of-type`: Un pseudo-selector que permite aplicar estilos específicos al último `fieldset`.
    * Selectores de atributo (`input[type="submit"]`): Para aplicar estilos solo a elementos con atributos específicos, como los botones de envío.

---

### Cómo Visualizar el Proyecto

Para ver la página web, solo necesitas abrir el archivo `index.html` en tu navegador web. El proyecto es completamente estático y no requiere de un servidor local.

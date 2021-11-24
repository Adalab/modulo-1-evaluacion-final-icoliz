# Evaluación final Ico

Partiendo del enunciado dado en clase para la evaluación de los conocimientos adquiridos en el primer módulo (Maquetación Web) he utilizado Adalab Web Starter Kit para facilitar la automatización de tareas de cara al desarrollo del ejercicio.

## HTML

División utilizando etiquetas semánticas:

- **Header.** Consistente en el icono con fondo azul que lleva al menú (en este caso a la página de Adalab) hero (fotografía de fondo), subtítulo y flecha (scroll hasta la sección de "3 reasons")
- **Main.** Divisón en dos secciones: blanca y azul, maquetadas en flexbox y Grid respectivamente). Uso de motor de plantillas en la sección blanca para personalizar el texto en caso de ser necesario.
- **Footer.** Pie de página con un `nav` con una lista de enlaces (en este caso todos dirigen a la página de Adalab) y el copyright.

Uso de selectores de ID para enlazar con otras secciones dentro de la misma página así como enlaces a webs externas.

## CSS / SASS

- Maquetación con flexbox o Grid, según procediera. Incorporación de un elemento fijo en la página.
- Creación y aplicación de estilos a través de selectores de clase.
- Uso de las posibilidades de anidación proporcionadas por SCSS.
- Uso de **mediaqueries** para crear un diseño responsive que se adaptase a tres tamaños diferentes de pantalla.
- Uso de transiciones en los dos botones del body.
- Pequeña animación en el botón del footer.

### Adalab Web Starter Kit

- Uso de partials (en HTML y CSS) y motor de plantillas a través de `includes`.
- Uso de variables.
- Uso de una hoja de reset personalizada.
- Uso de `npm`y `gulp`.

### Otras tecnologías / metodologías implementadas

- Uso de **BEM** en la medida de lo posible.
- Uso de `mixins` para incluir los breakpoints más fácilmente.
- Inclusión de fuentes (tipografías) externas.
- Creación de ramas de `git`para trabajar en las distintas partes del documento: `mainsection` y `responsive`.

### Dificultades técnicas encontradas (solucionadas gracias al soporte de profes)

- `Header` adaptado a altura de pantallas pequeñas.
- Incorporación de `mixins` en SASS.
- Dudas sobre semántica y buenas prácticas en general.

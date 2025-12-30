# Dientolin - Consultorio Dental

Esta página web es informativa, en ella se puede observar el objetivo, sobre ellos y servicios que branda el consultorio, así mismo, evidenciando a la Doctora con el objetivo de expresar confianza, también el usuario que este interesado, podrá agendar cita para consulta, dando así, un poco de dinamismo a la página web.

## Caracteristicas:

- Página web informativa

## Instalación y Configuración:

Para esta pagina se utilizo la Motodología BEM. Es una metodología funciona para nombrar clases CSS y archivos de forma organizada y clara.

Los 3 componentes son:

### 1. **Block (Bloque)**

- Es el componente principal
- Ejemplo: `header`, `menu`, `card`

### 2. **Element (Elemento)**

- Parte del bloque que no puede existir sola
- Se escribe: `bloque__elemento`
- Ejemplo: `header__logo`, `menu__item`

### 3. **Modifier (Modificador)**

- Variación del bloque o elemento
- Se escribe: `bloque--modificador` o `bloque__elemento--modificador`
- Ejemplo: `button--red`, `menu__item--active`

Una vez hayas decidido cómo estructurar tu página web, puedes crear un archivo para cada bloque dentro de la carpeta **blocks**. Cada uno de estos archivos actuará como un fragmento independiente de CSS para un solo bloque y todos sus elementos que puedes reutilizar en páginas y proyectos.

Ahora que tenemos un archivo para cada bloque BEM, los importaremos todos en nuestro archivo** index.css**, que se conectará a **index.html** con una etiqueta` <link>`.

Ejemplo:
`@import url("../blocks/header.css");`
`@import url("../blocks/logo.css");`
`@import url("../blocks/footer.css");`
`/* ...etc... */`

Los **_archivos se organizaron_** de la siguiente manera:

- El bloque.
- Todos los modificadores de bloque.
- Cada elemento.
- Después de cada elemento, todos sus modificadores (antes del próximo elemento).

### Método responsivo:

- Flexbox
- Grid

## Tecnologías:

- HTML5
- CSS3
- GIT y GitHub

## Mejora del proyecto:

Se concidera realizar un formulario en el que pueda tener acceso el usuario para agedar las citas con el Consultorio Dental.

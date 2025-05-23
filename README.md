# HTML- 2
## HTML Styles
### HTML Text Formatting
 <b> - Bold text
 <strong>  - Important text
 <i> - Italic text
 <em> - Emphasized text
 <small> - Smaller text
 <del> - Deleted text
 <ins> - Inserted text
 <sub> - Subscript text
 <sup> - Superscript text

 ### Quotation and citation examples
 <blockquote>,<q>, <abbr title="HyperText Markup Language">, <address>, <cite> and <bdo>

 Este código HTML representa una página web llamada "Pasión Futbolera", y está escrita en español. A continuación se explica cada una de sus partes:

Encabezado del documento (<head>):

Se declara el tipo de documento como HTML5 con <!DOCTYPE html>.

Se especifica que el idioma es español mediante <html lang="es">.

Dentro del <head>, se incluye <meta charset="UTF-8" /> para permitir caracteres especiales (como tildes o eñes).

La etiqueta <meta name="viewport" content="width=device-width, initial-scale=1.0"/> asegura que el diseño se adapte correctamente a pantallas pequeñas como las de los móviles.

Se incluye un título de pestaña: <title>Pasion Futbolera</title>.

Se importa la biblioteca de íconos Font Awesome para poder usar íconos como correo, teléfono, etc.

Se enlaza un archivo CSS externo ubicado en css/style.css para aplicar estilos visuales a la página.

Encabezado visual del sitio (<header>):

Contiene una barra de navegación (<nav>), en la cual hay una lista (<ul>) de enlaces a diferentes secciones del sitio como Inicio, Servicios, Nosotros, Blog y Contacto.

También incluye una imagen del logo (<img src="img/logo.png">) que representa la marca o nombre del sitio web.

Cuerpo principal del contenido (<main>):

Dentro de <main> hay una sección con el ID "bienvenida" que contiene un título de bienvenida en negrita (<strong><b>¡Bienvenido a Pasión Futbolera!</b></strong>).

Luego hay un párrafo que utiliza muchas etiquetas semánticas:

<br> crea un salto de línea.

<i> pone en cursiva la frase “En este espacio”.

<blockquote> resalta la frase “verdaderos amantes del fútbol” como una cita destacada.

<q> agrega una cita corta: “que sientas la emoción”.

<abbr title="HyperText Markup Language"> muestra un texto abreviado y, al pasar el mouse, se ve el significado completo (muy útil para siglas).

<sup> se usa para mostrar una idea secundaria como si estuviera en superíndice, aunque en este caso es más decorativo.

<address> se usa de manera creativa para destacar una frase, aunque técnicamente se recomienda para direcciones o contactos.

<cite> se usa para mencionar una fuente, aunque en este caso se adapta para indicar las “últimas noticias”.

<bdo dir="rtl"> invierte visualmente el orden del texto (de derecha a izquierda).

Después de ese texto se incluye una imagen decorativa de bienvenida con <img src="img/bien.png">.

Pie de página (<footer>):

Contiene una sección con íconos sociales:

Ícono de correo con un enlace para enviar un email: <a href="mailto:..."><i class="fas fa-envelope"></i></a>.

Ícono de teléfono: <a href="tel:..."><i class="fas fa-phone"></i></a>.

Ícono de WhatsApp: <a href="https://wa.me/..."><i class="fab fa-whatsapp"></i></a>.

Ícono de Instagram: <a href="https://www.instagram.com/..."><i class="fab fa-instagram"></i></a>.

Finalmente, una línea de texto con derechos de autor usando &copy; 2025 pasion futbolera
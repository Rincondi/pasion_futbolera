Proyecto Web de Fútbol

Este repositorio contiene una página web sencilla dedicada al fútbol, con secciones de navegación, estilos, y contenido básico para las páginas: Servicios, Nosotros, Blog, Contacto y una sección de bienvenida.

---

# Estructura de Archivos y Carpetas

mi-pagina-web/
├── index.html
├── servicios.html
├── nosotros.html
├── blog.html
├── contacto.html
├── styles/
│ └── style.css
└── README.md


---

## Código HTML para las páginas

### Servicios (`servicios.html`)

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Servicios</title>
  <link rel="stylesheet" href="styles/style.css" />
</head>
<body>
  <header>
    <nav>
      <ul class="nav-links">
        <li><a href="index.html">Inicio</a></li>
        <li><a href="servicios.html">Servicios</a></li>
        <li><a href="nosotros.html">Nosotros</a></li>
        <li><a href="blog.html">Blog</a></li>
        <li><a href="contacto.html">Contacto</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <h1>Servicios</h1>
      <p>Ofrecemos una amplia gama de servicios diseñados para satisfacer las necesidades de los verdaderos amantes del fútbol. Desde cobertura profesional de eventos deportivos hasta asesorías personalizadas para jugadores y entrenadores.</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Pasión Futbolera</p>
  </footer>
</body>
</html>

###Sección de bienvenida (ejemplo para index.html)
<section id="bienvenida">
  <h1>¡Bienvenido a Pasión Futbolera!</h1>
  <p>En este espacio creado para verdaderos amantes del fútbol, queremos que sientas la emoción del deporte más apasionante del planeta. Desde los goles que hacen historia hasta las jugadas que nos dejan sin aliento, aquí celebramos cada pase, cada táctica y cada victoria como si estuviéramos en la cancha.</p>
  <p>Nuestro objetivo es acercarte al corazón del juego: te traemos las últimas noticias, análisis profundos de los partidos, perfiles de jugadores legendarios y emergentes, así como historias inspiradoras del fútbol en todo el mundo.</p>
  <p>Ya seas fanático de tu equipo local, seguidor fiel de las grandes ligas internacionales o simplemente alguien que disfruta del sonido del balón rodando, este es tu lugar. Bienvenido a la comunidad donde el fútbol nunca duerme y la pasión se vive a cada minuto.</p>
</section>

#### transform: translate(x, y)=
Cómo mover elementos en CSS (ejes X e Y)

###Usando position + top y left
css
Copiar
Editar
.mi-elemento {
  position: relative;
  top: 20px;  /* mueve hacia abajo */
  left: 50px; /* mueve hacia la derecha */
}
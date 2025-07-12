<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Portafolio</title>
</head>
<body>
  <h1>Portafolio</h1>

  <nav>
    <a href="#about">About Me</a>
    <a href="#projects">Projects</a>
    <a href="#blog">Blog</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2>About Me</h2>
    <p>Soy un programador/artista en proceso.</p>
    <p>Manejando el conocimiento poco a poco, sin afán.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <select>
      <option value="all">All Projects</option>
      <option value="Web">Web Development</option>
    </select>
    <div>
      <img src="https://preview.redd.it/whats-your-opinion-on-the-nerd-emoji-meme-v0-8n14e28ef25c1.png?width=640&crop=smart&auto=webp&s=00ec94716e0562c27eb13fcadeb50cabcd81ce74" alt="E-commerce Platform">
      <h3>E-Commerce Platform</h3>
      <p>Tienda Online</p>
      <a href="#">Ver Proyecto</a>
    </div>
  </section>

  <section id="blog">
    <h2>Blog</h2>
    <button>New Post</button>
    <div>
      <!-- Aquí van las entradas del blog -->
    </div>
  </section>

  <section id="testimonials">
    <h2>Testimonials</h2>
    <div>
      <img src="https://i.pinimg.com/1200x/cb/3e/01/cb3e014d6122af3b43933bb571859ae7.jpg" alt="">
      <p>Gran desarrollador, cumple con sus tareas a tiempo</p>
      <p>Iván Duque</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <label for="nombre">Nombre</label>
      <input type="text" id="nombre" placeholder="Tu nombre">

      <label for="email">Correo</label>
      <input type="email" id="email" placeholder="Tu correo">

      <label for="message">Mensaje</label>
      <textarea name="message"placeholder id="Tu mensaje"></textarea>

      <button type="submit">Enviar</button>
    </form>
  </section>

</body>
</html>

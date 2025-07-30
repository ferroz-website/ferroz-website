<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ferroz</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>

<body class="bg-white text-blue-900 font-sans">
  <nav class="bg-blue-900 text-white p-4 shadow-md">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-xl font-bold">Ferroz</h1>
      <ul class="flex space-x-4">
        <li><a href="#inicio" class="hover:underline">Inicio</a></li>
        <li><a href="#nosotros" class="hover:underline">Quiénes Somos</a></li>
        <li><a href="#productos" class="hover:underline">Productos</a></li>
        <li><a href="#galeria" class="hover:underline">Galería</a></li>
        <li><a href="#blog" class="hover:underline">Blog</a></li>
        <li><a href="#contacto" class="hover:underline">Contacto</a></li>
        <li><a href="#tienda" class="hover:underline">Tienda</a></li>
      </ul>
    </div>
  </nav>

  <section id="inicio" class="h-screen bg-gradient-to-r from-white to-blue-50 flex items-center justify-center">
    <div class="text-center px-4">
      <h2 class="text-4xl font-bold mb-4">Soluciones Inteligentes para tu Negocio</h2>
      <p class="text-lg">Somos Ferroz: innovación, distribución y futuro</p>
    </div>
  </section>

  <section id="nosotros" class="py-16 px-8 bg-blue-50">
    <div class="max-w-4xl mx-auto">
      <h3 class="text-3xl font-bold mb-4 text-center">Quiénes Somos</h3>
      <p class="text-lg text-center">En Ferroz combinamos experiencia y pasión por brindar soluciones en empaque, belleza, marina, agrícola y más. Nuestro compromiso es con el crecimiento de nuestros clientes.</p>
    </div>
  </section>

  <section id="productos" class="py-16 px-8">
    <div class="max-w-6xl mx-auto">
      <h3 class="text-3xl font-bold mb-8 text-center">Nuestros Productos</h3>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="border p-4 shadow hover:shadow-lg">
          <h4 class="font-semibold text-xl mb-2">Foam EVA Antiestático</h4>
          <p>Protección especializada para electrónica y embalaje.</p>
        </div>
        <div class="border p-4 shadow hover:shadow-lg">
          <h4 class="font-semibold text-xl mb-2">Tanques de Agua</h4>
          <p>Distribuidores Durman: calidad y resistencia certificada.</p>
        </div>
        <div class="border p-4 shadow hover:shadow-lg">
          <h4 class="font-semibold text-xl mb-2">Aislante Marino y Agrícola</h4>
          <p>Soluciones para producción, transporte y exportación.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="galeria" class="py-16 px-8 bg-blue-50">
    <div class="max-w-6xl mx-auto text-center">
      <h3 class="text-3xl font-bold mb-8">Galería</h3>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
        <div class="bg-gray-200 h-40">Imagen 1</div>
        <div class="bg-gray-200 h-40">Imagen 2</div>
        <div class="bg-gray-200 h-40">Imagen 3</div>
        <div class="bg-gray-200 h-40">Imagen 4</div>
      </div>
    </div>
  </section>

  <section id="blog" class="py-16 px-8">
    <div class="max-w-4xl mx-auto">
      <h3 class="text-3xl font-bold mb-8 text-center">Noticias & Blog</h3>
      <div class="space-y-6">
        <div>
          <h4 class="font-semibold text-xl">Cómo elegir el mejor material para exportación agrícola</h4>
          <p class="text-sm text-gray-600">Publicado el 30 julio 2025</p>
        </div>
        <div>
          <h4 class="font-semibold text-xl">Foam EVA: el aislante estrella de la nueva era</h4>
          <p class="text-sm text-gray-600">Publicado el 25 julio 2025</p>
        </div>
      </div>
    </div>
  </section>

  <section id="contacto" class="py-16 px-8 bg-blue-50">
    <div class="max-w-xl mx-auto">
      <h3 class="text-3xl font-bold mb-6 text-center">Contacto</h3>
      <form class="space-y-4">
        <input class="w-full p-2 border border-gray-300" type="text" placeholder="Nombre" required>
        <input class="w-full p-2 border border-gray-300" type="email" placeholder="Correo electrónico" required>
        <textarea class="w-full p-2 border border-gray-300" rows="4" placeholder="Mensaje" required></textarea>
        <button type="submit" class="bg-blue-900 text-white px-6 py-2">Enviar</button>
      </form>
    </div>
  </section>

  <section id="tienda" class="py-16 px-8">
    <div class="max-w-6xl mx-auto text-center">
      <h3 class="text-3xl font-bold mb-6">Tienda en Línea</h3>
      <p class="mb-4">Muy pronto disponible. Estamos trabajando para que puedas comprar nuestros productos desde cualquier lugar.</p>
      <button class="bg-blue-900 text-white px-6 py-2">Notificarme</button>
    </div>
  </section>

  <footer class="bg-blue-900 text-white text-center p-4">
    <p>&copy; 2025 Ferroz. Todos los derechos reservados.</p>
  </footer>
</body>

</html>

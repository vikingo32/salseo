# salseo
Salseo es una red social centrada en recetas, creada para alejarse del scrolling infinito y las promociones de pago. Su código y desarrollo pueden consultarse en https://github.com/softfxc/salseo  Por ahora, el proyecto será portado aquí, donde continuará su evolución.
# Salseo v4.0

### «Tu nueva red social favorita al alcance de tu mano»

Salseo es una aplicación que nace con la idea de crear una red social diferente, alejada del **scrolling infinito** y de las **promociones previo pago**. Para ello, el proyecto combina el concepto de red social con una temática cotidiana y persistente: **las recetas de cocina**.

En lugar de recurrir a interminables libros de recetas o a búsquedas convencionales, Salseo recopila automáticamente información de diferentes páginas web mediante métodos internos de **scraping**, obteniendo los datos esenciales de cada receta, principalmente:

* Ingredientes.
* Preparación.

Las páginas que no ofrecen claramente ambos tipos de información son descartadas automáticamente. La lista de páginas web compatibles está integrada directamente en el código de Salseo y puede consultarse en los propios resultados de búsqueda.

## 🍅 El concepto de Salseo

El nombre **Salseo** surge de la combinación de:

* **Salsa**, por la temática gastronómica.
* **Movimiento social**, por su concepto de red social.

De ahí nace también su identidad visual, cuyo icono representa una **salsa de tomate**.

La **cuchara** presente en el diseño tiene un doble significado: representa la cocina y, al mismo tiempo, constituye una referencia artística al logotipo de **FitGirl-Repacks**.

## 🍳 Recetas mediante scraping

Una de las funciones principales de Salseo es la recopilación automática de recetas desde páginas web compatibles.

El sistema analiza las páginas y extrae la información relevante mediante métodos internos de scraping. Para mantener la calidad de los resultados, aquellas páginas que no presentan de forma clara tanto los **ingredientes** como la **preparación** son descartadas.

La lista de fuentes compatibles se encuentra integrada en el propio código de la aplicación y es visible dentro de los resultados de búsqueda.

En esta versión se han **añadido nuevas páginas web compatibles**, ampliando la cantidad de recetas disponibles. Entre las nuevas fuentes destaca **Thermomix**.

## 🎲 ¡Sorpréndeme!

Salseo incorpora el nuevo botón **«¡Sorpréndeme!»**, diseñado para descubrir recetas de forma aleatoria.

Al utilizarlo, la aplicación carga **recetas aleatorias**, ofreciendo una forma rápida de encontrar nuevos platos sin necesidad de realizar una búsqueda concreta.

## ▶️ Vídeos de YouTube

Además de las recetas, Salseo busca recopilar y mostrar vídeos relacionados mediante **YouTube**, utilizando **Piped** para su integración.

El objetivo es ofrecer la mayor cantidad y precisión posible de vídeos relacionados con las recetas encontradas.

En esta versión también se mejora la:

* Búsqueda de recetas con vídeos.
* Reproducción integrada de contenidos.
* Integración de vídeos mediante Piped.

## 👤 Búsqueda de usuarios

Salseo incorpora una función especial dentro del buscador para localizar usuarios mediante su nombre exacto.

Si se introduce un **`@`** delante del nombre de usuario, el sistema permite buscar directamente a dicho usuario, siempre que no sea una cuenta de tipo lector/invitado.

Por ejemplo:

* Buscar `Tortilla` → búsqueda general.
* Buscar `@teresa` → búsqueda específica del usuario cuyo nombre exacto es `teresa`.

## 🔔 Notificaciones

Una de las funciones más curiosas de esta versión es la posibilidad de consultar qué recetas han marcado los usuarios como **favoritas**.

Las notificaciones contemplan diferentes tipos de actividad:

* Mensajes.
* Seguidores.
* Publicaciones.
* Recetas favoritas.

## 💬 Chat y perfiles

El sistema social de Salseo incorpora funciones adicionales para facilitar la comunicación entre usuarios.

En esta versión, el **chat ha sido cambiado visualmente**, con una interfaz renovada y una presentación más cuidada de las conversaciones.

También se incluyen:

* Mensajes privados entre usuarios.
* Eliminación de mensajes enviados.
* Compartir perfiles mediante enlace.
* Apertura de perfiles desde la aplicación cerrada.
* Confirmación antes de dejar de seguir a un usuario.
* Nombres de usuario únicos.
* Visualización del número de seguidores y seguidos.
* Listado privado de seguidores y seguidos.

## 🔐 Firebase y plan Spark

Salseo utiliza **Google Firebase**, concretamente el **plan Spark**, aprovechando las posibilidades disponibles dentro de sus servicios gratuitos.

La elección de este plan responde al objetivo del proyecto: ofrecer el servicio a un grupo reducido de usuarios, como amistades, familiares y personas interesadas en el código abierto.

Debido a las limitaciones del plan Spark:

* No se utilizan imágenes almacenadas directamente en el servidor.
* En los chats, las fotografías se manejan mediante enlaces.
* No se utiliza verificación mediante SMS y número de teléfono.

Estas decisiones permiten mantener Salseo dentro de las posibilidades del plan gratuito.

## ✉️ Autenticación y correos

En esta versión también se trabaja en la mejora del sistema de autenticación:

* Mejora del inicio de sesión.
* Mejora de los correos de autenticación.
* Uso de correos `noreply` de Firebase.
* Mejora de la gestión de nombres de usuario únicos.

## 🎵 Integración con TikTok

Salseo mejora la reproducción integrada de contenido de TikTok, incluyendo su correspondiente **portada** para ofrecer una presentación más adecuada dentro de la aplicación.

## 🗑️ Eliminación de cuentas

La eliminación de cuentas forma parte de las mejoras importantes de Salseo.

La aplicación contempla la evolución del sistema de borrado hacia una **eliminación total de la cuenta y sus datos**, en lugar de mantener únicamente un borrado parcial.

## 🚀 Salseo v4.0 — Resumen de novedades

### Red social

* Mensajes privados entre usuarios.
* Eliminación de mensajes enviados.
* Notificaciones de mensajes.
* Notificaciones de seguidores.
* Notificaciones de publicaciones.
* Notificaciones de recetas favoritas.
* Compartir perfiles mediante enlace.
* Confirmación para dejar de seguir.
* Nombres de usuario únicos.
* Número de seguidores y seguidos.
* Listado privado de seguidores y seguidos.
* Búsqueda exacta de usuarios mediante `@`.
* **Chat renovado visualmente.**

### Recetas

* Scraping automático de recetas.
* Extracción de ingredientes y preparación.
* Descarte de páginas sin información suficiente.
* Lista de fuentes integrada en el código.
* Fuentes visibles en los resultados de búsqueda.
* Búsqueda de recetas con vídeos.
* **Botón «¡Sorpréndeme!» para cargar recetas aleatorias.**
* **Más páginas web compatibles.**
* **Añadida compatibilidad con Thermomix.**

### Vídeo

* Integración de vídeos de YouTube mediante Piped.
* Mayor cantidad y precisión de resultados.
* Reproducción integrada de TikTok con portada.

### Cuenta y autenticación

* Mejoras en el inicio de sesión.
* Mejora de los correos de autenticación.
* Correos `noreply` de Firebase.
* Nombres de usuario únicos.
* Mejora de los enlaces de perfil compartido.
* Apertura de perfiles desde la aplicación cerrada.

### Infraestructura

* Google Firebase como backend.
* Uso del plan Spark.
* Gestión de imágenes mediante enlaces en los chats.
* Sin verificación SMS debido a las limitaciones del plan utilizado.

---

**Salseo v4.0** representa una evolución del proyecto hacia una red social centrada en la cocina, con recetas recopiladas automáticamente, nuevas fuentes de contenido, descubrimiento aleatorio de recetas, contenido multimedia y funciones sociales, manteniendo el objetivo de ser un proyecto pequeño, abierto y sin depender de modelos basados en publicidad o promociones de pago.

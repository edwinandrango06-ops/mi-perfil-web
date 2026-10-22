# Mi Perfil Profesional - Sitio Web Personal

## 🎯 Objetivo del Proyecto
Desarrollar una página web estática de perfil profesional moderna y semántica, contenerizada mediante un servidor web Nginx y desplegada en Docker Hub.

---

## 🛠️ Tecnologías Utilizadas
* **HTML5 & CSS3:** Estructura semántica, diseño responsivo con CSS Grid y Flexbox.
* **Font Awesome:** Iconografía interactiva.
* **Nginx (Alpine):** Servidor web ultraligero para contenido estático.
* **Docker:** Contenerización de la aplicación.
* **GitHub & Docker Hub:** Control de versiones y distribución de imágenes.

---

## 🚀 Instrucciones para Ejecutar desde Docker Hub
Puedes descargar y probar la imagen directamente ejecutando en tu terminal:

```bash
docker pull edwinan21/mi-perfil-web
docker run -d -p 8080:80 edwinan21/mi-perfil-web
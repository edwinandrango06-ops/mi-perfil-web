
# Mi Perfil Profesional - Sitio Web Personal

## Objetivo del Proyecto
Desarrollar una página web estática de perfil profesional moderna y semántica, contenerizada mediante un servidor web Nginx y desplegada en Docker Hub.

---

## Tecnologías Utilizadas

* **HTML5 & CSS3:** Estructura semántica, diseño responsivo con CSS Grid y Flexbox.
* **Font Awesome:** Iconografía interactiva.
* **Nginx (Alpine):** Servidor web ultraligero para contenido estático.
* **Docker:** Contenerización de la aplicación.
* **GitHub & Docker Hub:** Control de versiones y distribución de imágenes.

---

## Estructura del proyecto

PerfilMokup/
├── Dockerfile      
├── Edwin.jpeg          
├── estilo.css       
├── index.html          
└── README.md       

### Descripción de componentes

- **index.html**: Es el archivo de entrada a la aplicación web. Contiene el marcado semántico en HTML5, en el cual se integran secciones como la presentación personal, la formación académica, las áreas de interés y enlaces relacionados.

- **estilo.css**: Archivo de estilos responsivo. Este define el diseño visual, paleta de colores, tipografía, efectos hover y ajuste ajuste adaptativo mediante flexbox.

- **Edwin.jpeg**: Recurso multimedia usado para la presentación del perfil profesional.

- **Dockerfile**: Script de automatización de Docker basado en la imagen ligera nginx:alpine. Copia la totalidad de archivos y expone el puerto estándar HTTP (80).

- **README.md**: Posee la documentación con la descripción de las tecnologías, requerimientos previos a la ejecución y comandos necesarios para probar la imagen desde Docker Hub.

---

## Instrucciones para Ejecutar desde Docker Hub
Puede descargar y probar la imagen directamente ejecutando en tu terminal:

```bash
docker pull edwinan21/mi-perfil-web
docker run -d -p 8080:80 edwinan21/mi-perfil-web
```
## Enlace a Docker Hub

https://hub.docker.com/r/edwinan21/mi-perfil-web

---   

# 🎬 **Starless – Backend CMS**

Backend de contenido construido con **Strapi v5** para un sitio web cultural que reúne secciones de **Cine**, **Música**, **Noticias**, **Home**, **Contacto** y **Navegación**.  
Este proyecto actúa como el **CMS oficial** que alimenta al frontend desarrollado en Astro.



## 📋 **Descripción General**

Este sistema administra todo el contenido dinámico de **Starless Magazine**.  
Desde aquí se controlan textos, imágenes, artículos y configuraciones del sitio web.

### **Apartados del CMS**

- 🎬 **Cine** – Artículos y reseñas cinematográficas.  
- 🎵 **Música** – Contenido editorial y reseñas musicales.  
- 📰 **Noticias** – Publicaciones, novedades y actualidad.  
- 🏠 **Home** – Slider principal, título y cita destacada.  
- 📧 **Contacto** – Textos del formulario y contenido informativo.  
- 🧭 **Navegación** – Items del menú principal de la web.  

---

# ⚙️ **Instalación**

### 1️⃣ Clonar el repositorio

bash
git clone <repository-url>
cd strapi-starless-main


### 2️⃣ Instalar dependencias

bash
npm install

### 3️⃣ Configurar variables de entorno

Copia el archivo de ejemplo:

bash
cp .env


Edita `.env` con tus valores (puerto, DB, URL pública, etc.).

### 4️⃣ Iniciar el servidor en desarrollo

bash
npm run develop

El panel de administración estará disponible en:
👉 **[http://localhost:1337/admin](http://localhost:1337/admin)**

---

# 📁 **Estructura del Proyecto**

strapi-starless-main/
├── config/           # Configuración de Strapi
├── database/         # Archivos de base de datos (dev)
├── public/           # Archivos públicos y uploads
├── src/
│   ├── admin/        # Personalización del panel de administración
│   ├── api/          # Definiciones de API (Cine, Música, etc.)
│   │   ├── cine/
│   │   ├── musica/
│   │   ├── noticia/
│   │   ├── home/
│   │   ├── contact/
│   │   └── navmenu/
│   └── extensions/   # Extensiones personalizadas
└── types/            # Tipos de TypeScript


# 🌐 **Rutas de API Disponibles**

| Sección    | Endpoint        |
| ---------- | --------------- |
| Cine       | `/api/cines`    |
| Música     | `/api/musicas`  |
| Noticias   | `/api/noticias` |
| Home       | `/api/home`     |
| Contacto   | `/api/contacts` |
| Navegación | `/api/navmenus` |

---

# 🛠️ **Tecnologías Utilizadas**

* **Strapi v5.31.2**
* **Node.js 20+**
* **TypeScript**
* **Database**

  * PostgreSQL (Producción – Render)
  * SQLite (Desarrollo local)
* **Render**

  * Build Command:

    bash
    npm install
    npm run build
    ```
  * Start Command:

    `bash
    npm run start
    

---

# 👥 **Créditos del Equipo**

### **Ruben Neguel** — Backend Lead & DevOps

Arquitectura del CMS, configuración de PostgreSQL, permisos API y despliegue en Render.

### **Cristofer Sánchez** — Content Manager

Diseño de colecciones, carga de contenido y validación editorial.

---

# 📚 **Recursos Útiles**

* **Documentación Strapi:** [https://docs.strapi.io](https://docs.strapi.io)
* **API REST Strapi:** [https://docs.strapi.io/dev-docs/api/rest](https://docs.strapi.io/dev-docs/api/rest)
* **Documentación PostgreSQL:** [https://www.postgresql.org/docs/](https://www.postgresql.org/docs/)



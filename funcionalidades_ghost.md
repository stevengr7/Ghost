# Listado de funcionalidades de GHOST (Semana 1)

**Autor:** Steven Garzón  
**Fecha:** 6 de octubre de 2025  
**Versión de Ghost:** 5.x (Docker local)

A continuación se listan las funcionalidades principales identificadas tras la exploración inicial de la aplicación **Ghost 5.x** desplegada localmente mediante Docker.

---

### 1. Autenticación de administrador
**Descripción:** Permite crear el usuario administrador inicial, iniciar sesión y cerrar sesión en el panel administrativo.  
**Pantallas involucradas:** `/ghost/#/signin`, `/ghost/#/setup`

---

### 2. Panel de análisis y métricas
**Descripción:** Presenta un resumen general del sitio, incluyendo número de publicaciones, miembros y rendimiento de newsletters.  
**Pantallas involucradas:** `/ghost/#/analytics`

---

### 3. Gestión de publicaciones
**Descripción:** Permite crear, editar, publicar, programar y eliminar posts del blog.  
**Pantallas involucradas:** `/ghost/#/posts`

---

### 4. Gestión de páginas estáticas
**Descripción:** Permite crear, modificar y eliminar páginas fijas (por ejemplo, “Acerca de” o “Contacto”).  
**Pantallas involucradas:** `/ghost/#/pages`

---

### 5. Administración de etiquetas
**Descripción:** Permite crear, editar o eliminar etiquetas, así como clasificarlas como públicas o internas.  
**Pantallas involucradas:** `/ghost/#/tags`

---

### 6. Gestión de miembros
**Descripción:** Muestra la lista de suscriptores del sitio y permite agregar, editar o eliminar miembros.  
**Pantallas involucradas:** `/ghost/#/members`

---

### 7. Personalización de diseño y temas
**Descripción:** Permite subir, activar o eliminar temas visuales, así como ajustar el diseño y los colores del sitio.  
**Pantallas involucradas:** `/ghost/#/settings/design`

---

### 8. Configuración de navegación
**Descripción:** Permite editar los menús principal y secundario, añadiendo o reordenando enlaces del sitio.  
**Pantallas involucradas:** `/ghost/#/settings/navigation`

---

### 9. Configuración general del sitio
**Descripción:** Permite modificar el título, descripción, idioma, zona horaria y favicon del sitio.  
**Pantallas involucradas:** `/ghost/#/settings/general`

---

### 10. Configuración de integraciones
**Descripción:** Permite registrar integraciones externas, generar API keys y definir webhooks personalizados.  
**Pantallas involucradas:** `/ghost/#/settings/integrations`

---

### 11. Gestión de laboratorios (Labs)
**Descripción:** Permite habilitar funciones experimentales o en prueba, como nuevos formatos o flujos beta.  
**Pantallas involucradas:** `/ghost/#/settings/labs`

---

### 12. Configuración de usuarios API
**Descripción:** Permite crear claves de acceso personalizadas para desarrolladores o servicios externos.  
**Pantallas involucradas:** `/ghost/#/settings/integrations/new`

---

### 13. Configuración del sitio (Site Settings)
**Descripción:** Muestra una vista general de la configuración del sitio, incluyendo el título, descripción, idioma, URL principal, zona horaria, logo y favicon. Desde aquí se accede también a los ajustes de diseño, navegación y membresías.  
**Pantallas involucradas:** `/ghost/#/site`

---

### 14. Gestión de etiquetas internas
**Descripción:** Permite crear, editar y eliminar etiquetas internas (prefijadas con `#`), las cuales se usan para categorizar contenido, filtrar publicaciones y automatizar boletines internos. Estas etiquetas no son visibles para los visitantes del sitio.  
**Pantallas involucradas:** `/ghost/#/tags` → pestaña “Internal tags”

---

### 15. Integración con ActivityPub
**Descripción:** Permite conectar el sitio de Ghost con el protocolo ActivityPub para compartir publicaciones en redes federadas como Mastodon. Desde esta pantalla se configuran los permisos y el nombre de usuario federado del sitio.  
**Pantallas involucradas:** `/ghost/#/activitypub/welcome/1`

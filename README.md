# 🌿 Plantilla Web: Lumina Health (Base Holística)

Esta es una plantilla HTML5 moderna diseñada para sitios web de salud, bienestar, medicina integrativa o clínicas.

**Características principales:**
* 🚀 **Sin Backend:** Funciona con HTML, CSS y JS puro.
* 📝 **Blog Dinámico:** Carga artículos automáticamente desde la carpeta `/blog` usando la API de GitHub (sin necesidad de WordPress).
* 📧 **Formulario Funcional:** Integrado con Formspree para recibir correos.
* ⚡ **Optimizado:** Listo para desplegar en Cloudflare Pages o GitHub Pages.

---

## 🛠 Cómo usar esta plantilla para un nuevo cliente

### 1. Generar el Repositorio
No clones este repo manualmente. En la página principal de este repositorio en GitHub:
1.  Haz clic en el botón verde **"Use this template"**.
2.  Selecciona **"Create a new repository"**.
3.  Asigna el nombre del nuevo proyecto (ej: `web-nutricionista-ana`).

### 2. Configuración Obligatoria (index.html)
Para que el blog y el formulario funcionen en la nueva web, debes editar el archivo `index.html`:

**A. Conectar el Blog (Líneas ~660):**
Busca la sección de configuración de JavaScript al final del archivo y actualiza los datos del nuevo repositorio:

```javascript
// --- CONFIGURACIÓN (¡CAMBIA ESTO!) ---
const GITHUB_USER = "TU_USUARIO_GITHUB";  // Tu usuario (ej: juanperez)
const GITHUB_REPO = "NOMBRE_NUEVO_REPO";  // El nombre que pusiste en el paso 1 (ej: web-nutricionista-ana)
const BLOG_FOLDER = "blog";


# Blog con Editor Avanzado en Django y QuillJS 🚀

Un sistema de gestión de contenido (CMS) moderno desarrollado en Django que permite crear, editar y publicar artículos con un editor de texto enriquecido potente y fácil de usar.

## ✨ Características Principales

- **Editor de Texto Avanzado**: Integración con QuillJS para formateo de texto enriquecido
- **Diseño Responsive**: Interfaz moderna y adaptable a cualquier dispositivo con Bootstrap 5
- **Base de Datos Robusta**: Almacenamiento seguro en MySQL
- **Panel de Administración**: Gestión completa de artículos y contenido
- **Fácil de Implementar**: Configuración sencilla y documentación clara

![image](https://raw.githubusercontent.com/urian121/imagenes-proyectos-github/refs/heads/master/editor-Quill-condjango-y-mysql.gif)

## ⚙️ Instalación de todas las dependencias del proyecto

```bash
pip install -r requirements.txt
```

## 🔧 Configuración

1. Crea la base de datos en MySQL:
```sql
CREATE DATABASE blog_db CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;
```

2. Ajusta `settings.py` con tus credenciales MySQL.

3. Ejecuta migraciones:
```bash
python manage.py migrate
```

4. Corre el servidor:
```bash
python manage.py runserver
```


## ✨ Funcionalidad
- Crear nuevos posts con editor QuillJS.
- Listar posts en tarjetas Bootstrap.
- Soporte para emojis y caracteres especiales (utf8mb4).

## 🖼 Captura rápida
- `/` → Lista todos los posts.
- `/new/` → Crear un nuevo post.

## 🙌 Cómo puedes apoyar 📢:

✨ **Comparte este proyecto** con otros desarrolladores para que puedan beneficiarse 📢.

☕ **Invítame un café o una cerveza 🍺**:
   - [Paypal](https://www.paypal.me/iamdeveloper86) (`iamdeveloper86@gmail.com`).

### ⚡ ¡No olvides SUSCRIBIRTE a la [Comunidad WebDeveloper](https://www.youtube.com/WebDeveloperUrianViera?sub_confirmation=1)!

#### ⭐ **Déjanos una estrella en GitHub**:
   - Dicen que trae buena suerte 🍀.
**Gracias por tu apoyo 🤓.**

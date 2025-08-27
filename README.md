
# QuillBlog 📝

Pequeño proyecto en **Django** que permite crear y listar posts usando:
- **MySQL** como base de datos.
- **QuillJS** como editor de texto enriquecido.
- **Bootstrap 5** para la interfaz.

## 🚀 Requisitos
- Python 3.10+
- MySQL 5.7+ o MariaDB
- pip y virtualenv

## ⚙️ Instalación

```bash
# Clona el repositorio (o copia los archivos)
git clone <tu-repo>

# Crea y activa entorno virtual
python3 -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate

# Instala dependencias
pip install django mysqlclient
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

## 📂 Estructura
```
blog_project/
 ├── blog_project/
 │    └── settings.py
 ├── posts/
 │    ├── models.py
 │    ├── views.py
 │    ├── urls.py
 │    └── templates/
 └── manage.py
```

## ✨ Funcionalidad
- Crear nuevos posts con editor QuillJS.
- Listar posts en tarjetas Bootstrap.
- Soporte para emojis y caracteres especiales (utf8mb4).

## 🖼 Captura rápida
- `/` → Lista todos los posts.
- `/new/` → Crear un nuevo post.

---
**Autor:** Urian  

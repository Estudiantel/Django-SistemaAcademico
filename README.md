# 🎓 Sistema de Gestión Académica - Django

Este es un sistema integral para la gestión de carreras, materias, alumnos y docentes, desarrollado con Python y Django.

### Integrantes:
- Gomez, Fabio
- Silvera, Joaquin

## 🔐 Usuarios y Roles
El sistema cuenta con 4 niveles de acceso:
- **Administrador:** Gestión total de Carreras, Materias, Alumnos y Docentes.
- **Docente:** Visualización de sus cátedras asignadas y listas de alumnos.
- **Alumno:** Consulta de oferta académica, inscripción a materias de su carrera y gestión de su estado académico.
- **Invitado:** Acceso público para consultar las carreras disponibles y sus planes de estudio sin necesidad de login.

## 📋 Requisitos Previos
- **Python 3.10 o superior** (Desarrollado en 3.13)
- **Git** para clonar el repositorio.
- **pip** (gestor de paquetes de Python).

## 🚀 Instalación Paso a Paso

### 1. Clonar el Repositorio
```bash
git clone https: https://github.com/Estudiantel/Django-SistemaAcademico#
cd DjangoSistemaAcademico
```

### 2. Crear y Activar un Entorno Virtual
```bash
# Crear el entorno
python -m venv env

### Activar en Windows
.\env\Scripts\activate
Una vez activado, verás el prefijo (env) en tu terminal.
```

### 3. Instalar Dependencias
```bash
pip install -r requirements.txt
```

### 4. Configurar la Base de Datos
```bash
python manage.py makemigrations
python manage.py migrate
```

### 5. Crear el Administrador
```bash
python manage.py createsuperuser
```

### 6. Ejecutar el Servidor

Inicia el servidor local de Django:

```bash
python manage.py runserver
```

Deberías ver un mensaje similar a:
```
Starting development server at http://127.0.0.1:8000/
Quit the server with CTRL-BREAK.
```

### 🔑 7. Acceder al Sistema

Abre tu navegador web y visita:

- **Página principal:** http://127.0.0.1:8000/
- **Panel de administración:** http://127.0.0.1:8000/admin/
- **Invitado (Post-login):** http://127.0.0.1:8000/carreras-disponibles/

Para acceder al panel de administración, usa las credenciales del superusuario que creaste en el paso 5.

Nota de seguridad: Al crear Alumnos o Docentes desde el panel de administración, la contraseña inicial por defecto será su número de DNI. El sistema obligará al usuario a cambiarla en su primer inicio de sesión.

**Extra**

Enlace de los [Diagramas](https://drive.google.com/drive/folders/1IplQj3dJZHUAnR9sSKFHR-t3fTqbQ2-M?usp=sharing)

Enlace del [Video](https://drive.google.com/file/d/1UjAXroOE8uQgn1xkEGrP8zT_dQy4Lg-q/view?usp=sharing)

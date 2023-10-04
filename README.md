# MyDailyDrive
Ejemplo de Blog automotor hecho con Django!

Este es un proyecto de ejemplo de un blog desarrollado utilizando el framework Django. El blog cuenta con funcionalidades como registro de usuarios, inicio de sesión, cierre de sesión, cambio de imagen de perfil, creación de publicaciones, edición de publicaciones, comentarios y eliminación de publicaciones.

# Instalación
Asegúrate de tener Python y Django instalados en tu sistema. Si no los tienes instalados, puedes seguir las instrucciones en la documentación oficial de Django para la instalación.
1. Clona el repositorio:

2. Navega al directorio del proyecto:

3. Instala las dependencias:

4. Aplica las migraciones de la base de datos:

5. Crea un superusuario para acceder al panel de administración:

6. Inicia el servidor de desarrollo:

La aplicación estará disponible en http://127.0.0.1:8000/

# Uso
-Regístrate como un nuevo usuario en la página de inicio, en el boton de arriba a la derecha "Register"
-Inicia sesión con tu nueva cuenta, en el boton de arriba a la derecha "Login"
-Cambia tu imagen de perfil desde la página de perfil de usuario.
-Crea nuevos posts desde la página de inicio, en el boton "New Post"
-Modifica tus publicaciones existentes desde la página de detalle de la publicación, entrando al post y tocando "update"
-Comenta en las publicaciones de otros usuarios desde la página de detalle de la publicación.
-Elimina tus propias publicaciones desde la página de detalle de la publicación o desde la página de inicio.
-Cierra sesión cuando hayas terminado.

usuario administrador
usuario: TomasMantegazza
contraseña: holacomova

# Estructura del Proyecto
El proyecto está organizado de la siguiente manera:

blog: Aplicación principal del blog.
user: Aplicación de usuarios y autenticación.
static: Carpeta que contiene archivos estáticos como CSS e imágenes.
templates: Carpeta que contiene las plantillas HTML de la aplicación.
media: Carpeta donde se almacenan los archivos multimedia como las imágenes de perfil de los usuarios.
manage.py: Script de gestión de Django para realizar tareas administrativas.

# Tecnologías Utilizadas
Python
Django
HTML/CSS
Bootstrap (opcional)





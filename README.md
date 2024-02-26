PlaygroundFinalProject-PerezSebastian
Alumno: Sebastian Carlos Perez

Proyecto final, curso Python CODERHOUSE Comisión 56060

Aplicacion tipo BLOG DE SELLO DISCOGRAFICO:

Este es un proyecto creado para crear posts, los usuarios que se registren pueden comentar publicaciones ,Buscar cada publicacion subida por el administrador, desde el panel de administrador podemos eliminar usuarios,tambien posts que no deseemos y grupos que creamos mediante el administrador.

Enlace youtube web funcionando
https://youtu.be/yZfiWuCVko8


Requisitos
Asegúrate de tener Python,pip y Django instalados en tu sistema. Puedes instalar Django utilizando el siguiente comando:
pip install Django

Verifica el comando Pip utilizando el siguiente comando:
pip --version

Configuración del Proyecto
Clona el repositorio:

git clone: https://github.com/bastiengroove/PlaygroundFinalProject-PerezSebastian.git



Navega al directorio del proyecto:

Crea un entorno virtual (opcional pero recomendado):

pip install --user pipenv

Activa el entorno virtual:

pipenv shell 

Instala las dependencias del proyecto:

pip install -r requirements.txt

Aplica las migraciones de la base de datos:

python manage.py makemigrations
python manage.py migrate

Ejecución del Proyecto
Ejecuta el servidor de desarrollo:

python manage.py runserver

Abre tu navegador y visita http://127.0.0.1:8000/

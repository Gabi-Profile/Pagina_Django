# Pagina_Django
Pagina web básica con Django

1. Instalar Django (Si no tienes Django instalado, debes instalarlo primero):

pip install django

2. Instalar dependencias desde requirements.txt:

pip install -r requirements.txt

3. Activar el entorno virtual:

source D:/ProyectoDjango/entorno/Scripts/activate

Si se activa correctamente, deberías ver algo como esto en la terminal:

(entorno) user@hostname MINGW64 /d/ProyectoDjango/PaginaPatitas

4. Ir al directorio del proyecto Django:

cd D:/ProyectoDjango/PaginaPatitas

5. Hacer las migraciones:

python manage.py makemigrations
python manage.py migrate

6. Iniciar el servidor de desarrollo (una vez las migraciones estén aplicadas):

python manage.py runserver

7. Acceder a la página de inicio:
   
Ahora, abre un navegador y accede a la URL de la página de inicio:

http://127.0.0.1:8000/paginainicio

Si todo se configura correctamente y no hay errores en los pasos previos, deberías poder ver la página de inicio sin problemas, recuerda poner 'paginainicio' como en el ejemplo de arriba.



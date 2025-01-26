[README.md](https://github.com/user-attachments/files/18548872/README.md)[Uploading README# Pagina_Django
Pagina web básica con Django

1. Instalar Django (Si no tienes Django instalado, debes instalarlo primero):

pip install django

2. Ir al directorio del proyecto Django:

cd D:/ProyectoDjango/PaginaPatitas

3. Instalar dependencias desde requirements.txt:

pip install -r requirements.txt
pip install pillow
pip install django-extensions

4. Regresar

cd..

5. Activar el entorno virtual:

source D:/ProyectoDjango/entorno/Scripts/activate

Si se activa correctamente, deberías ver algo como esto en la terminal:

(entorno) user@hostname MINGW64 /d/ProyectoDjango/PaginaPatitas

6. Ir al directorio del proyecto Django:

cd D:/ProyectoDjango/PaginaPatitas

7. Hacer las migraciones:

python manage.py makemigrations
python manage.py migrate

8. Iniciar el servidor de desarrollo (una vez las migraciones estén aplicadas):

python manage.py runserver

9. Acceder a la página de inicio:
   
Ahora, abre un navegador y accede a la URL de la página de inicio:

http://127.0.0.1:8000/paginainicio

Si todo se configura correctamente y no hay errores en los pasos previos, deberías poder ver la página de inicio sin problemas, recuerda poner 'paginainicio' como en el ejemplo de arriba.

---------------------
En caso de error con python volver a instalar el entorno:

a. Eliminar el entorno virtual
Borra la carpeta de tu entorno virtual. En tu caso, está en:

D:/ProyectoDjango/entorno

b. Usa el explorador de archivos o este comando:

rm -rf D:/ProyectoDjango/entorno

c. Crear un nuevo entorno virtual
Ve a la carpeta raíz de tu proyecto (D:/ProyectoDjango/) y crea un nuevo entorno virtual:

python -m venv entorno

d. Activar el entorno virtual recién creado:

source D:/ProyectoDjango/entorno/Scripts/activate

f. Instalar dependencias nuevamente Una vez activado el entorno virtual:

pip install django
pip install -r requirements.txt

g. Ejecutar el servidor Ahora puedes iniciar el servidor:

python manage.py runserver



.md…]()

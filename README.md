Para crear un entorno virtual con venv se require la siguiente linea en la terminal
todas las lineas se tiene que escribir en la terminal

python -m venv "nombre de tu entorno viertual"

Ejemplo:
python -m venv env en este caso el nombre de mi entorno virtual es env

Activar el entorno virtual
ya que creaste la carpeta de tu entorno virtual es necesario activarla para empezar a usarla:

.\env\Scripts\activate

o tambien:

env/Scripts/activate
esto activara el entorno virtual


Desactivar el entorno virtual
para poder salir del entorno virtual es necesario esta linea en la terminal:

deactivate


Archivo requirements.txt
para generar un archivo con que contenga todas las librerias de tu proyecto usa:

pip freeze > "el nombre de el archivo".txt

Ejemplo
pip freeze requirements.txt

Para poder instalar las librerias del archivo usa:
pip install -r "nombre del archivo".text

Ejemplo
pip install -r requirements.txt y se instalaran todas las librerias en tu proyecto

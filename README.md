crear entorno en django 

python -m venv env
 Instalar virtualenv usando pip:

bash
Copiar código
pip install virtualenv
Verifica si virtualenv se ha instalado correctamente:

bash
Copiar código
virtualenv --version

activar entorno virtual 
venv\Scripts\activate

cuando el entorno virtual este funcionandocinstalar dependencias 
 pip install django 
pip install djangorestframework 

crear backend del proyecto en django 
django-admin startproject backend 
crear una app dentro del proyecto 
python manage.py startapp productos

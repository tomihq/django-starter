# Instalar dependencias
pip install 

# Llenar las variables de entorno
Es estrictamente necesario definir la variable de SECRET_KEY. Esta debe utilizarse en un archivo .env.development u .env.production según desee utilizar la aplicación.

# Levantar el servidor con las variables de entorno de Desarrollo
python manage.py runserver --settings=config.settings.development

# Levantar el servidor con las variables de entorno de Producción
python manage.py runserver --settings=config.settings.production
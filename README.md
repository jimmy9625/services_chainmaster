# Proyecto de Servicios Web con Python y Flask

Este proyecto consiste en un conjunto de servicios web implementados en Python utilizando el framework Flask. Proporciona funcionalidades de autenticación, registro de usuarios y toma de registros.

## Configuración del Entorno

1. Asegúrate de tener Python instalado en tu sistema. Puedes descargarlo desde [python.org](https://www.python.org/).

2. Instala las dependencias del proyecto ejecutando el siguiente comando en tu terminal:

    pip install -r requirements.txt


3. Configura las variables de entorno necesarias, como la URI de la base de datos y las claves secretas, en un archivo `.env`. Puedes usar el archivo de ejemplo `.env.example` proporcionado como referencia.

## Ejecución del Proyecto

1. Ejecuta la aplicación Flask con el siguiente comando:


python app.py


2. La aplicación estará disponible en `http://localhost:5000`.

## Endpoints Disponibles

- `/register`: Permite a los usuarios registrarse en la plataforma.
- `/login`: Permite a los usuarios iniciar sesión en la plataforma.
- `/logout`: Permite a los usuarios cerrar sesión en la plataforma.
- `/dashboard`: Página de inicio para usuarios autenticados.
- `/records`: Permite la toma y visualización de registros.

## Estructura del Proyecto

El proyecto sigue la siguiente estructura de directorios:



## Tecnologías Utilizadas

- [Python](https://www.python.org/)
- [Flask](https://flask.palletsprojects.com/)
- [SQLAlchemy](https://www.sqlalchemy.org/) (para la interacción con la base de datos)
- [Bootstrap](https://getbootstrap.com/) (para la interfaz de usuario)

## Contribución

¡Siéntete libre de contribuir al proyecto enviando pull requests!

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

# face_recognition

Reconocimiento facial usando el modelo pre entrenado VGGFace2.



**Implementación del modelo de Reconocimiento facial.**

[Link del repositorio](https://github.com/royquillca/face_recognition)

1. **Librerías necesarias.**
2. Pytorch o Tensorflow. **Elegiremos Pytorch por la gran comunidad que tiene y porque por lo pronto queremos hacer el MVP y sea más rapido ya fácil de programadr.**
3. Plataformas para desplegar/deployment streamlit, dash. **Usaremos Streamlit porque permite tambien interactuar con el usuario a través de widgets, y para la parte de visualización podemos agregarle plotly además de seaborn y matplotlib.**
4. Tareas que podemos asignar a cada dev. Modelado de datos scripts, la implementación el modelo pre entrenado, MVP.
5. Cómo implementar el modelo  VGGFace2. **Aún no le he leido estaba probando streamlit.**
6. **Gestor de librerías y/o módulos.**


**Instaalación de Streamlit**

Primero creamos el ambiente virtual con nombre ``face-recognition-venv`` y le pasamor  ``--upgrade-deps`` para que descargue depenedencias actualizadas:

``python -m venv face-recognition-venv --upgrade-deps``

Accedemos al entorno virtual cada vez que queremos añadir código y acceder a nuestras dependencias con:

``source face-recognition-venv/Scripts/activate``

Una vez dentro del ambiente virtual desarrollamos nuestro código he aquí recien debemos instalar nuestras dependencias, librerías y/o módulos ya sean usando el gestor de paquetes ``pip``, por ejemplo:

``pip install streamlit``
``pip install torch``

En este caso para replicar se debe instalar las dependencias desde el ``requirements.txt`` usando el comando:

``pip install -r requirements.txt``

**Ojo: Aseguremonos siempre estar dentro del ambiente virtual que hemos creado.**

La carpeta o directorio ``pages/`` contendrá todas cada uno de los componentes de nuestra aplicacion web. Es importante mencionar que los nombres de los archivos dentro este directorio pasarán a ser los títulos omitiendo el ``_`` en caso hubiera. Por ejemplo; si nuestro archivo tiene de nombre ``01_About.py`` el título en el sidebar será ``01 About``.

Para ejecutar streamlit y ver el local los avances usaremos:
``streamlit run App.py``

Se abrirá automáticamente una pestaña del navegador para visualizar el ``Hola Mundo`` en streamlit.

``source face-recognition-venv/Scripts/activate``

Una vez dentro del ambiente virtual desarrollamos nuestro código he aquí recien debemos instalar nuestras dependencias, librerías y/o módulos ya sean usando el gestor de paquetes ``pip``, por ejemplo:

``pip install streamlit``
``pip install torch``

En este caso para replicar se debe instalar las dependencias desde el ``requirements.txt`` usando el comando:

``pip install -r requirements.txt``

**Ojo: Aseguremonos siempre estar dentro del ambiente virtual que hemos creado.**

La carpeta o directorio ``pages/`` contendrá todas cada uno de los componentes de nuestra aplicacion web. Es importante mencionar que los nombres de los archivos dentro este directorio pasarán a ser los títulos omitiendo el ``_`` en caso hubiera. Por ejemplo; si nuestro archivo tiene de nombre ``01_About.py`` el título en el sidebar será ``01 About``.

Para ejecutar streamlit y ver el local los avances usaremos:
``streamlit run App.py``

Se abrirá automáticamente una pestaña del navegador para visualizar el ``Hola Mundo`` en streamlit.
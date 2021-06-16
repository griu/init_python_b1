# Iniciación a Python Bloque 1

Dos opciones alternativas para realizar el curso, o bién, des de Colab, o bién, des de Jupyter Notebooks en local.

## Preparación entorno Colab

Visita la siguiente página en [Introducción Curso de Python](https://github.com/griu/init_python_b1/blob/master/modulo1_tema4_Py.ipynb) y accede al notebook des de Colab en el enlace que econtrarás dentro del documento abierto. No necesita ningún tipo de instalación, sólo un usuario de gmail.

## Preparación entorno Jupyter local

Alternativamente, puedes preparar tu entorno en un servidor de Jupyter o en tu PC con Anaconda.

### Descarga des de github el repositorio del curso.

```console
git clone https://github.com/griu/init_python_b1.git
cd init_python_b1
```

### Crea el environment con Anaconda.

```console
conda create -n initPython383 python=3.8.3
```

Una vez ha analizado las dependencias, aceptamos la creación del entorno.

Ahora activamos el entorno e instalamos resto de paquetes. 

```console
conda activate initPython383
python -m pip install -r requirements.txt

# publica el kernel de python
python -m ipykernel install --user --name initPython383 --display-name "initPython383"
```

Si necesitas iniciar sesión des de una máquina local (no un servidor).

```console
jupyter notebook
```

Puedes empezar el curso des del notebook llamado:  **"modulo1_tema4_Py.ipynb"**.

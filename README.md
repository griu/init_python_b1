# Iniciación a Python Bloque 1

Dos opciones alternativas para realizar el curo, o bién, des de Colab, o bién, des de Jupyter Notebooks en local.

## Preparación entorno Colab

Visita la siguiente página en [GitHub](https://github.com/griu/init_python_b1) y accede a cada uno de los notebooks del curso que podràs abrir directamente en Colab.

## Preparación entorno Jupyter local

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


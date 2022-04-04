# JupyterNotebooks_Anaconda

## Description

----

## Jupyter Notebooks - Anaconda 


   * [Introducción a las notebooks
](#introducción-a-las-notebooks)
      * [Lugares programar para ciencia de datos](#lugares-programar-para-ciencia-de-datos)
      * [Google Colab: primeros pasos](#google-colab-primeros-pasos)
      * [Google Colab: ciencia de datos](#google-colab-ciencia-de-datos)
      * [Utilizar Deepnote](#utilizar-deepnote)
      * [Introducción a las notebooks](#introducción-a-las-notebooks)
   * [Configuración de VSCode
](#configuración-de-vscode)
      * [Instalar VSCode](#instalar-vscode)
      * [Windows Subsystem for Linux](#windows-subsystem-for-linux)
      * [Agregar extensiones para VSCode](#agregar-extensiones-para-vscode)
      * [Uso de VSCode notebooks](#uso-de-vscode-notebooks)
   * [Entorno de desarrollo con Anaconda
](#entorno-de-desarrollo-con-anaconda)
      * [¿Qué son los ambientes virtuales?](#que-son-los-ambientes-virtuales)
      * [Instalar Conda a través de la terminal](#instalar-conda-a-través-de-la-terminal)
      * [Crear y actualizar ambientes](#crear-y-actualizar-ambientes-conda)
      * [Abrir VSCode Notebooks con tu ambiente creado Conda](#abrir-vscode-notebooks-con-tu-ambiente-creado-conda)
      * [Eliminar ambientes y librerías](#eliminar-ambientes-y-librerías-conda) 
      * [Comandos avanzados Conda](#comandos-avanzados-conda)  
      * [Acelerar la creación de ambientes virtuales con Mamba](#acelerar-la-creación-de-ambientes-virtuales-con-mamba)  
      * [Bonus: divide y vencerás](#Bonus:-divide-y-vencerás) 
      * [Entorno de desarrollo con Anaconda](#Entorno-de-desarrollo-con-Anaconda) 
   * [¿Qué sigue con estas herramientas?
](#¿Qué-sigue-con-estas-herramientas?)
      * [Cómo seguir tu camino en ciencia de datos](#Cómo-seguir-tu-camino-en-ciencia-dedatos) 


Introducción a las notebooks
============

Lugares programar para ciencia de datos
-----------

Existen muchas plataformas para trabajar en Data Science, se recomiendo usar algún Sistema Operativo basado en UNIX usando Linux, MacOS o WSL en Windows, en editores estan VSCode, PyCharm, Deepnote, Google Colab, y el que usaremos Jupyter, todo basado en Notebooks que te permiten ir ejecutando trozos de código, en el cual puedes escribir pocas lineas de código probarlas, asegurarse de que estén bien y seguir adelante con otro trozo, allí también se pueden añadir código, ecuaciones, gráficas, texto enriquecido, etc.

Notebooks Vs Scripts
Ambos son útiles, aunque los Scripts son mas directos, los Notebooks te permiten ver lo que haces, a medida de que lo haces, en estos puedes encargarte de experimentar y hacer el prototipado de tu script y finalmente pasarlo a un Script cuando ya este listo y estés seguro de que todo funciona como es esperado

Google Colab: primeros pasos
-----------

Es una herramienta basada en la nube que te permite trabajar en notebooks, y se guardan en tu cuenta de Google Drive 😃.

Nube vs local: Ambas son útiles, pero se diferencian en la configuración de entornos, ya que en la nube ya están precargadas, y de local tienes que configurarlo manualmente. También es diferente el tiempo de ejecución y la escalabilidad: la nube tiene más poder porque puedes rentarlo!. 💸

Google Colab: Servicio en la nube basado en Jupyter Notebooks, no requiere configuración y tiene un trabajo a nivel de archivo (el notebook es la base). Tiene uso de gratuito de GPUs y TPUs para correr modelos grandes. ☁️

Puedes acceder a Google Colab desde tu drive o desde el navegador.

Para aprender Markdown.

Markdown Guide

Las variables son persistentes (se conservan) entre celdas de código!. 🔥

Para llamar a la línea de comandos, debemos usar primero un signo de admiración ! y luego un comando válido, por ejemplo !pwd o !pip install session-info.


Google Colab: ciencia de datos
-----------

Puedes cargar archivos a tu notebook desde tu computadora, pero se borrarán una vez cierres tu notebook. También puedes vincular tu google drive para que tome los archivos desde ahí y de esta forma conservarlos.

Colab está enfocado a trabajar con Python (también puede usar otros lenguajes) y ya trae librerías de ciencia de datos precargadas como:

matplotlib: Generación de gráficos a partir de listas o arrays.

numpy: Cómputo científico para la manipulación de vectores.

pandas: Manipulación y análisis de datos de tablas y series temporales.

scipy: Herramientas y algoritmos matemáticos.

seaborn: Visualización de datos estadísticos.

Colab también tiene fragmentos de código (parecido a la herramienta para insertar funciones de Excel) que te facilita la programación.
Con ctrl + shift +p abres la paleta de comandos, si escribes shortcuts o atajos de teclado te mostrará una lista de todos los atajos que puedes ejecutar en Colab.

Utilizar Deepnote
-----------

* Deepnote es un servicio en la nube basado en Jupyter Notebooks. No requiere configuración y tiene un trabajo a nivel de proyecto. Tiene colaboración en tiempo real, integración con múltiples Apps y tiene acceso a una terminal o línea de comandos integrada 😎.
* Tiene también variables de entorno y permite publicar proyectos (para construir portafolio). 🎉
* Podemos correr y agregar lo mismo que en Colab, pero además podemos subir archivos que se quedan siempre en el proyecto.
Permite previsualizar los archivos CSV de manera muy bonita 😄.
* Parte de lo poderoso de Deepnote es que podemos integrar muchas cosas 🔥.
* No solo podemos agregar celdas de código y de texto, si no que en la opción de Bloque vienen muchos más tipos, como input, chart, dataframe sql, etc 🤯. Puede crear gráficas de manera automática sin código!
* Para acceder a los atajos de teclado usamos Ctrl + i.
* También es importante resaltar que tenemos una terminal integrada 🤖



Configuración de VSCode
============


Instalar VSCode
-----------

Editores de código: Enfocados a multiples lenguajes. Se pueden potencial con extensiones o plugins. Por lo general son gratuitos. Mejor este 😄. Tenemos Pycharm VSCode, Atom, etc.
IDE (entornos de desarrollo integrado): Enfocado a un solo lenguaje y seguimiento a un solo proyecto. Por lo general son de pago 💸

Windows Subsystem for Linux
-----------
Windows Subsystem for Linux es una capa de compatibilidad desarrollada por Microsoft para correr ejecutables de Linux nativamente en Windows 10 y Windows Server 2019. A partir de junio de 2019 está disponible WSL versión 2, el cual incorpora cambios importantes, como el uso de un núcleo Linux real.​

Agregar extensiones para VSCode
-----------

* Hay muchas extensiones para VSCode que hacen trabajar con datos más cómodo. ☁️
* Se pueden instalar todas las extensiones directamente desde VSCode 😄.
* Es recomendable activar la sincronización automática en la nube, para que siempre puedas tener tu entorno de trabajo en cualquier lugar. Lo puedes contectar con tu cuenta de GitHub 🤖
* Hay extension para Python que incluye muchas funcionalidades 🔥.
* MagicPython sirve mucho para darle formato a Python y que sea más legible.
* Las extensiones de Icon sirven para diferenciar tipos de archivos. 📁
* Rainbow Brackets sirve para cambiar los colores de los paréntesis y no tener errores 🌈.
* Remote Development te descarga múltiples extensiones que te sirven trabajar de manera remota. 🌎

Uso de VSCode notebooks
-----------

* Esto es un nuevo estilo de Notebook, integrado dentro de VSCode 🤯.
* Puedes abrir VSCode en una carpeta específica para ver todos los archivos dentro (y solo esos). Menos distracción que tener todo abierto con WSL. 😆
* Podemos correr los archivos .py directamente en la terminal dando click en ▶️.
* Con las extensiones que instalamos, podemos darle formato de manera automática a nuestro código 🐍.
* Dentro de los Jupyter Notebook en VSCode podemos usar todas estas extensiones 💕. La extensión de los Notebooks es .ipynb. Podemos exportar los notebooks a texto plano!.



Entorno de desarrollo con Anaconda
============

¿Qué son los ambientes virtuales?
-----------

* En la vida real, no vas a trabajar en un solo trabajo, si no en varios, y cada uno tendrá diferentes dependencias y requerimientos 🤔.
* Cuando se actualizan o se cambia la configuración de las dependencias de un ambiente que tiene varios proyectos asociados puede haber errores 🛑.
* Para poder separar proyectos, lo que hacemos es crear ambientes virtuales diferentes para cada proyecto. 🧠 Entonces la configuración y actualizaciones son para cada proyecto.
* Ambiente virtual: Proyecto que puede tener sus propias dependencias, independientemente de las dependencias que tengan los demás proyectos (Scott Robinson y la gente de Real Python).



Instalar Conda a través de la terminal
-----------

Conda: Programa diseñado para gestión de paquetes, dependencias y entorno para cualquier lenguaje: Python, R, Ruby, Lua, Scala, Java, JavaScript, etc. Además, es multiplataforma. 🖥️

Para instalar conda debes instalar anaconda (versión completa, metapaquete de ciencia de datos) o miniconda (versión mínima). 🐍

Para instalar conda:

Anaconda | Individual Edition

O bien hacer 


```bash
wget -0 anaconda.sh https://repo.anaconda.com/archive/Anaconda3-2021.05-Linux-x86_64.sh.
```

Para instalar hacemos 

```bash
bash anaconda.sh
```
🐍

Para abrir notebooks usamos 

```bash
jupyter-notebooko
```
o bien

```bash
jupyterlab
```

Los notebooks que creas ahí también los puedes abrir en VSCode.

Para abrir VSCode en la carpeta en el que te encuentras, usas 

```bash
code .
```
.

Crear y actualizar ambientes Conda
-----------

```bash
$ conda create --name [nombre] [paquete]=[versión]
```

Si no hay se especifíca una versión, se instalará la última disponible.

Para ver los paquetes(si no se especifican los paquetes, dará una lista de los ambientes virtuales):

```bash
$ conda list [paquete]
```

Para activar y desactivar los ambientes:


```bash
$ conda activate [nombre del ambiente] 
```
desactivar 

```bash
$ conda deactivate
```
Para actualizar paquetes:

```bash
$ conda update [paquete]
```
Para instalar un paquete específico:

```bash
$ conda install [paquete]=[versión]
```
Para clonar un ambiente:
```bash
$ conda --name [nuevo ambiente] --copy --clone [ambiente]
```



Abrir VSCode Notebooks con tu ambiente creado Conda
-----------

Eliminar ambientes y librerías Conda
-----------

Listar los ambientes:

```bash
$ conda env list
```

Para desinstalar un paquete:

```bash
$ conda remove [paquete]
```

Para eliminar un ambiente (el ambiente debe estar desactivado):

```bash
$ conda env remove --name [nombre de un ambiente]
```


Comandos avanzados Conda
-----------

```bash
conda create --name py39 python=3.9 pandas
```
```bash
conda activate py39 
```
```bash
conda install boltons 
```
```bash
conda install --chanel conda-forge boltons 
```
```bash
conda list boltons 
```
```bash
conda remove boltons 
```
```bash
conda install --revision boltons 
```
```bash
conda list --revision 
```
```bash
conda install --revision 0
```
```bash
conda env export
```
```bash
conda env export --no-builds
```
```bash
conda env export --from-history
```
```bash
conda env export --from-history --file environment.yml
```
```bash
conda env create --file environment.yml

```
Acelerar la creación de ambientes virtuales con Mamba
-----------

```bash
conda install --channel conda-forge mamba

```
```bash
mamba --help

```
```bash
mamba env create --file environment.yml

```

Bonus: divide y vencerás
-----------


Entorno de desarrollo con Anaconda
-----------




¿Qué sigue con estas herramientas?
============


Cómo seguir tu camino en ciencia de datos
-----------


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
      * [Ambientes virtuales](#ambientes-virtuales)
      * [Instalar Conda a través de la terminal](#instalar-conda-a-través-de-la-terminal)
      * [Crear y actualizar ambientes](#crear-y-actualizar-ambientes-conda)
      * [Abrir VSCode Notebooks con tu ambiente creado Conda](#abrir-vscode-notebooks-con-tu-ambiente-creado-conda)
      * [Eliminar ambientes y librerías](#eliminar-ambientes-y-librerías-conda) 
      * [Comandos avanzados Conda](#comandos-avanzados-conda)  
      * [Acelerar la creación de ambientes virtuales con Mamba](#acelerar-la-creación-de-ambientes-virtuales-con-mamba)  
      * [Divide y vencerás](#divide-y-vencerás) 
      * [Entorno de desarrollo con Anaconda](#Entorno-de-desarrollo-con-Anaconda) 
   * [¿Qué sigue con estas herramientas?
](#¿Qué-sigue-con-estas-herramientas?)
      * [Cómo seguir tu camino en ciencia de datos](#Cómo-seguir-tu-camino-en-ciencia-dedatos) 


Introducción a las notebooks
============

Lugares programar para ciencia de datos
-----------

There are many platforms to work in Data Science, it is recommended to use a UNIX-based Operating System using Linux, MacOS or WSL on Windows, in editors there are VSCode, PyCharm, Deepnote, Google Colab, and the one we will use Jupyter, all based on Notebooks that They allow you to execute pieces of code, in which you can write a few lines of code, test them, make sure they are correct and continue with another piece, there you can also add code, equations, graphs, rich text, etc.

Notebooks Vs Scripts

Both are useful, although the Scripts are more direct, the Notebooks allow you to see what you do, as you do it, in these you can take care of experimenting and prototyping your script and finally pass it to a Script when it is ready and be sure that everything works as expected


Google Colab: primeros pasos
-----------

It is a cloud-based tool that allows you to work on notebooks, and they are saved in your Google Drive account 😃.

Cloud vs local: Both are useful, but they differ in the configuration of environments, since in the cloud they are already preloaded, and from local you have to configure it manually. The execution time and scalability are also different: the cloud has more power because you can rent it! 💸

Google Colab: Cloud service based on Jupyter Notebooks, requires no configuration and has file-level work (the notebook is the base). It has free use of GPUs and TPUs to run large models. ☁️

You can access Google Colab from your drive or from the browser.

To learn Markdown.

MarkdownGuide

Variables are persistent (preserved) between cells of code! 🔥

To call the command line, we must first use an exclamation mark ! and then a valid command, for example !pwd or !pip install session-info.


Google Colab: ciencia de datos
-----------

You can upload files to your notebook from your computer, but they will be deleted once you close your notebook. You can also link your google drive to take the files from there and thus keep them.

Colab is focused on working with Python (you can also use other languages) and already comes with preloaded data science libraries such as:

* matplotlib: Generation of plots from lists or arrays.

* numpy: Scientific computation for manipulating vectors.

* pandas: Manipulating and analyzing data from tables and time series.

* scipy: Mathematical tools and algorithms.

* seaborn: Visualization of statistical data.

Colab also has code snippets (similar to Excel's insert function tool) that make programming easy.
With ctrl + shift +p you open the command palette, if you write shortcuts or keyboard shortcuts it will show you a list of all the shortcuts that you can execute in Colab.

Utilizar Deepnote
-----------

* Deepnote is a cloud service based on Jupyter Notebooks. It requires no configuration and has project-level work. It has real-time collaboration, integration with multiple Apps and has access to a built-in terminal or command line 😎.
* It also has environment variables and allows you to publish projects (to build a portfolio). 🎉
* We can run and add the same as in Colab, but we can also upload files that always stay in the project.
It allows to preview the CSV files in a very nice way 😄.
* Part of the power of Deepnote is that we can integrate so many things 🔥.
* Not only can we add code and text cells, but in the Block option there are many more types, such as input, chart, sql dataframe, etc 🤯. You can create graphs automatically without code!
* To access the keyboard shortcuts we use Ctrl + i.
* It is also important to note that we have an integrated terminal 🤖


Configuración de VSCode
============

Instalar VSCode
-----------

Code editors: Focused on multiple languages. They can be potential with extensions or plugins. They are usually free. Better this one 😄. We have Pycharm VSCode, Atom, etc.
IDE (Integrated Development Environments): Focused on a single language and tracking a single project. They are usually paid 💸

Windows Subsystem for Linux
-----------

Windows Subsystem for Linux is a compatibility layer developed by Microsoft to run Linux executables natively on Windows 10 and Windows Server 2019. As of June 2019, WSL version 2 is available, which incorporates important changes, such as the use of a kernel actual Linux.

Agregar extensiones para VSCode
-----------

* There are many extensions for VSCode that make working with data more comfortable. ☁️
* All extensions can be installed directly from VSCode 😄.
* It is recommended to activate the automatic synchronization in the cloud, so that you can always have your work environment wherever you are. You can connect it with your GitHub account 🤖
* There is a Python extension that includes many features 🔥.
* MagicPython is very useful for formatting Python and making it more readable.
* Icon extensions are used to differentiate file types. 📁
* Rainbow Brackets is used to change the colors of the brackets and not have errors 🌈.
* Remote Development downloads multiple extensions that help you work remotely. 🌎

Uso de VSCode notebooks
-----------

* Esto es un nuevo estilo de Notebook, integrado dentro de VSCode 🤯.
* Puedes abrir VSCode en una carpeta específica para ver todos los archivos dentro (y solo esos). Menos distracción que tener todo abierto con WSL. 😆
* Podemos correr los archivos .py directamente en la terminal dando click en ▶️.
* Con las extensiones que instalamos, podemos darle formato de manera automática a nuestro código 🐍.
* Dentro de los Jupyter Notebook en VSCode podemos usar todas estas extensiones 💕. La extensión de los Notebooks es .ipynb. Podemos exportar los notebooks a texto plano!.



Entorno de desarrollo con Anaconda
============

Ambientes virtuales
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

Divide y vencerás
-----------


Entorno de desarrollo con Anaconda
-----------




¿Qué sigue con estas herramientas?
============


Cómo seguir tu camino en ciencia de datos
-----------


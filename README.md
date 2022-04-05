# JupyterNotebooks_Anaconda

## Description

----

## Jupyter Notebooks - Anaconda 


   * [Introduction to notebooks
](#introduction-to-notebooks)
      * [Places to program for data science](#places-to-program-for-data-science)
      * [Google Colab: Getting Started](#google-colab-getting-started)
      * [Google Colab: Data Science](#google-colab-data-science)
      * [Use Deepnote](#use-deepnote)
   * [VSCode Settings
](#vscode-settings)
      * [Install VSCode](#install-vscode)
      * [Windows Subsystem for Linux](#windows-subsystem-for-linux)
      * [Add extensions for VSCode](#add-extensions-for-vscode)
      * [Using VSCode notebooks](#using-vscode-notebooks)
   * [Development environment with Anaconda
](#development-environment-with-anaconda)
      * [Virtual environments](#virtual-environments)
      * [Install Conda through the terminal](#install-conda-through-the-terminal)
      * [Create and update environments Conda](#create-and-update-environments-conda)
      * [Abrir VSCode Notebooks con tu ambiente creado Conda](#abrir-vscode-notebooks-con-tu-ambiente-creado-conda)
      * [Eliminar ambientes y librerías](#eliminar-ambientes-y-librerías-conda) 
      * [Comandos avanzados Conda](#comandos-avanzados-conda)  
      * [Acelerar la creación de Virtual environments con Mamba](#acelerar-la-creación-de-ambientes-virtuales-con-mamba)  
      * [Divide y vencerás](#divide-y-vencerás) 
      * [Development environment with Anaconda](#Entorno-de-desarrollo-con-Anaconda) 
   * [¿Qué sigue con estas herramientas?
](#¿Qué-sigue-con-estas-herramientas?)
      * [Cómo seguir tu camino en ciencia de datos](#Cómo-seguir-tu-camino-en-ciencia-dedatos) 


Introduction to notebooks
============

Places to program for data science
-----------

There are many platforms to work in Data Science, it is recommended to use a UNIX-based Operating System using Linux, MacOS or WSL on Windows, in editors there are VSCode, PyCharm, Deepnote, Google Colab, and the one we will use Jupyter, all based on Notebooks that They allow you to execute pieces of code, in which you can write a few lines of code, test them, make sure they are correct and continue with another piece, there you can also add code, equations, graphs, rich text, etc.

Notebooks Vs Scripts

Both are useful, although the Scripts are more direct, the Notebooks allow you to see what you do, as you do it, in these you can take care of experimenting and prototyping your script and finally pass it to a Script when it is ready and be sure that everything works as expected


Google Colab: Getting Started
-----------

It is a cloud-based tool that allows you to work on notebooks, and they are saved in your Google Drive account 😃.

Cloud vs local: Both are useful, but they differ in the configuration of environments, since in the cloud they are already preloaded, and from local you have to configure it manually. The execution time and scalability are also different: the cloud has more power because you can rent it! 💸

Google Colab: Cloud service based on Jupyter Notebooks, requires no configuration and has file-level work (the notebook is the base). It has free use of GPUs and TPUs to run large models. ☁️

You can access Google Colab from your drive or from the browser.

To learn Markdown.

MarkdownGuide

Variables are persistent (preserved) between cells of code! 🔥

To call the command line, we must first use an exclamation mark ! and then a valid command, for example !pwd or !pip install session-info.


Google Colab: Data Science
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

Use Deepnote
-----------

* Deepnote is a cloud service based on Jupyter Notebooks. It requires no configuration and has project-level work. It has real-time collaboration, integration with multiple Apps and has access to a built-in terminal or command line 😎.
* It also has environment variables and allows you to publish projects (to build a portfolio). 🎉
* We can run and add the same as in Colab, but we can also upload files that always stay in the project.
It allows to preview the CSV files in a very nice way 😄.
* Part of the power of Deepnote is that we can integrate so many things 🔥.
* Not only can we add code and text cells, but in the Block option there are many more types, such as input, chart, sql dataframe, etc 🤯. You can create graphs automatically without code!
* To access the keyboard shortcuts we use Ctrl + i.
* It is also important to note that we have an integrated terminal 🤖


VSCode Settings
============

Install VSCode
-----------

Code editors: Focused on multiple languages. They can be potential with extensions or plugins. They are usually free. Better this one 😄. We have Pycharm VSCode, Atom, etc.
IDE (Integrated Development Environments): Focused on a single language and tracking a single project. They are usually paid 💸

Windows Subsystem for Linux
-----------

Windows Subsystem for Linux is a compatibility layer developed by Microsoft to run Linux executables natively on Windows 10 and Windows Server 2019. As of June 2019, WSL version 2 is available, which incorporates important changes, such as the use of a kernel actual Linux.

Add extensions for VSCode
-----------

* There are many extensions for VSCode that make working with data more comfortable. ☁️
* All extensions can be installed directly from VSCode 😄.
* It is recommended to activate the automatic synchronization in the cloud, so that you can always have your work environment wherever you are. You can connect it with your GitHub account 🤖
* There is a Python extension that includes many features 🔥.
* MagicPython is very useful for formatting Python and making it more readable.
* Icon extensions are used to differentiate file types. 📁
* Rainbow Brackets is used to change the colors of the brackets and not have errors 🌈.
* Remote Development downloads multiple extensions that help you work remotely. 🌎

Using VSCode notebooks
-----------

* This is a new style of Notebook, built right into VSCode 🤯.
* You can open VSCode in a specific folder to see all the files inside (and only those). Less distraction than having everything open with WSL. 😆
* We can run the .py files directly in the terminal by clicking on ▶️.
* With the extensions we install, we can automatically format our code 🐍.
* Within the Jupyter Notebook in VSCode we can use all these extensions 💕. The extension for Notebooks is .ipynb. We can export notebooks to plain text!


Development environment with Anaconda
============

Virtual environments
-----------

* In real life, you will not work in one job, but in several, and each one will have different dependencies and requirements 🤔.
* When updating or changing the configuration of the dependencies of an environment that has several associated projects, there may be errors 🛑.
* In order to separate projects, what we do is create different virtual environments for each project. 🧠 So the configuration and updates are for each project.
* Virtual environment: Project that can have its own dependencies, regardless of the dependencies that other projects have (Scott Robinson and the Real Python people).


Install Conda through the terminal
-----------

Conda: Program designed to manage packages, dependencies and environments for any language: Python, R, Ruby, Lua, Scala, Java, JavaScript, etc. Also, it is cross-platform. 🖥️

To install conda you must install anaconda (full version, data science metapackage) or miniconda (minimum version). 🐍

To install conda:

Anaconda | Individual Edition

or else do

```bash
wget -0 anaconda.sh https://repo.anaconda.com/archive/Anaconda3-2021.05-Linux-x86_64.sh.
```

To install we do

```bash
bash anaconda.sh
```
🐍

To open notebooks we use

```bash
jupyter-notebooko
```
O well

```bash
jupyterlab
```

The notebooks you create there can also be opened in VSCode.

To open VSCode in the folder you're in, you use.

```bash
code .
```

Create and update environments Conda
-----------

```bash
$ conda create --name [nombre] [paquete]=[versión]
```


If no version is specified, the latest available will be installed.

To see the packages (if packages are not specified, it will list the virtual environments):

```bash
$ conda list [paquete]
```

To activate and deactivate scenes:


```bash
$ conda activate [nombre del ambiente] 
```
deactivate
 

```bash
$ conda deactivate
```
To update packages:

```bash
$ conda update [paquete]
```
To install a specific package:

```bash
$ conda install [paquete]=[versión]
```

To clone an environment:

```bash
$ conda --name [nuevo ambiente] --copy --clone [ambiente]
```


Abrir VSCode Notebooks con tu ambiente creado Conda
-----------

Eliminar ambientes y librerías Conda
-----------

List the environments:

```bash
$ conda env list
```

To uninstall a package:

```bash
$ conda remove [paquete]
```

To delete an environment (the environment must be disabled):

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
Acelerar la creación de Virtual environments con Mamba
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


Development environment with Anaconda
-----------




¿Qué sigue con estas herramientas?
============


Cómo seguir tu camino en ciencia de datos
-----------


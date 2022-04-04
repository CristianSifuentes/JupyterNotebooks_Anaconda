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
      * [Instalar WSL: usa Linux dentro de Windows](#instalar-WSL:-usa-Linux-dentro-de-Windows)
      * [Agregar extensiones para VSCode](#agregar-extensiones-para-vscode)
      * [Uso de VSCode notebooks](#uso-de-vscode-notebooks)
      * [Configuración de VSCode](#configuración-de-vscode)
   * [Entorno de desarrollo con Anaconda
](#entorno-de-desarrollo-con-anaconda)
      * [¿Qué son los ambientes virtuales?](#¿Qué-son-los-ambientes-virtuales?)
      * [Instalar Conda a través de la terminal](#instalar-conda-a-través-de-la-terminal)
      * [Conda: crear y actualizar ambientes](#Conda:-crear-y-actualizar-ambientes)
      * [Conda: abrir VSCode Notebooks con tu ambiente creado](#Conda:-abrir-VSCode-Notebooks-con-tu-ambiente-creado)
      * [Conda: eliminar ambientes y librerías](#Conda:-eliminar-ambientes-y-librerías) 
      * [Conda:-comandos-avanzados](#Conda:-comandos-avanzados)  
      * [Acelerar la creación de ambientes virtuales con Mamba](#Acelerar-la-creación-de-ambientes-virtuales-con-Mamba)  
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

Utilizar Deepnote.

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

Instalar WSL: usa Linux dentro de Windows
-----------

Agregar extensiones para VSCode
-----------

Uso de VSCode notebooks
-----------

Configuración de VSCode
-----------



Entorno de desarrollo con Anaconda
============

¿Qué son los ambientes virtuales?
-----------

Instalar Conda a través de la terminal
-----------

Conda: crear y actualizar ambientes
-----------

Conda: abrir VSCode Notebooks con tu ambiente creado
-----------

Conda: eliminar ambientes y librerías
-----------

Conda: comandos-avanzados
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


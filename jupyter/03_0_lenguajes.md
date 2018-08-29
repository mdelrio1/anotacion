
## III. Lenguajes para el análisis de secuencias
1. Linux
2. Python 
3. R
4. Instalación de programas

# 1. Linux

## Unix
El sistema operativo Unix tiene sus inicios en 1969 en los laboratorio Bell de AT&T. Ken Thompson lo desarrolló y posteriormente, colaboró con Dennis Ritchie, creador del lenguaje C, para hacerlo un sistema operativo transportable. Con el paso del tiempo se hizo un sistema independiente y de [libre acceso](http://histinf.blogs.upv.es/2011/12/23/historia-de-linux/)
Es ampliamente utilizado en los servidores y supercomputadoras, independientemente que cada fabricante de computadoras tiene su propio sistema operativo. 


## Software libre

La implementación de programas o software libre o sin costo tiene una historia larga. 

El movimiento de sorftware libre surgió como un medio para no someterse al poder de los desarrolladores del software. Es un movimiento que busca la libertad del usuario de cómputo y cuenta con su página en The Free Software Foundation [(FSF)](https://www.fsf.org). Esta fundación se dedica a que [no haya restricciones sobre la copia, redistribución, entendimiento, y modificación de programas de computadoras](https://es.wikipedia.org/wiki/Portal:Software_libre). 

Asimismo está el licenciamiento de los programas para que el usuario sea capaz de modificarlo a sus necesidades. Esta licencia se encuentra en términos generales por [Creative Commons](https://creativecommons.org/licenses/by-sa/4.0/) 

Esto requiere un sistema operativo y un núcleo o core para su funcionamiento.

## [Gnu](http://www.gnu.org) (ñu) 
<img src="http://www.gnu.org/graphics/heckert_gnu.transp.small.png" width=10%>
Es un sistema operativo que no tiene costo y permite que el usuario tenga el control de lo que se instala en su computadora. 
## Linux
<img src="http://histinf.blogs.upv.es/files/2011/12/21.png" width = 10%>

Es el núcleo o kernel general que utiliza sintaxis similar a Unix en las computadoras personales y como un movimiento en contra del monopolio de Windows.
<img src="http://histinf.blogs.upv.es/files/2011/12/23.png" width = 10%>


## Gnu/Linux 
<img src="http://www.gnu.org/graphics/gnu-and-penguin-color-300x276.jpg" width = 30%>
Es el sistema más utilizado para las computadoras personales de uso personal con software libre. En la mayoría de las ocasiones es conocido solo como **Linux**


# 2. Python
![](https://www.python.org/static/img/python-logo.png)
[Es un leguaje de programación tipo intérprete, interactivo y orientado a objetos](https://docs.python.org/3/faq/general.html#what-is-python), que incorpora módulos, excepciones, escritura dinámica, tipos de datos dinámicos a un nivel elevado. Combina un gran pocer y una sintaxis clara. Tiene interfaces a muchos sistemas y muchas bibliotecas, así como a sistemas de ventanas. Se puede hacer extensible a códigos de C o C++. Así como un lenguaje de extensión para aplicaciones que requieren de una interfase programable. Se puede ejecutar en muchas variantes de Unix, en los iOS (Mac) y en Windows 2000 en adelante.
Fue creado por Guido van Rossum y se rige por una [filosofía](http://www.thezenofpython.com).

1. Lindo es mejor que feo.
2. Explícito es mejor que implícito.
3. Simple es mejor que complejo.
4. Complejo es mejor que complicado.
5. Plano es mejor que anidado.
6. Espaciado es mejor que denso.
7. La legibilidad es importante.
8. Los casos especiales no son lo suficientemente especiales como para romper las reglas.
9. Sin embargo la practicidad le gana a la pureza.
10. Los errores nunca deberían pasar silenciosamente.
11. A menos que se silencien explícitamente.
12. Frente a la ambigüedad, evitá la tentación de adivinar.
13. Debería haber una, y solamente una, manera obvia de hacerlo.
14. A pesar de que no sea obvio a menos que seas Holandés (como GvR)
15. Ahora es mejor que nunca.
16. A pesar de que nunca es muchas veces mejor que justo ahora.
17. Si la implementación es dificil de explicar, es una mala idea.
18. Si la implementación es fácil de explicar, quizás sea una buena idea.
19. Los espacios de nombres son una gran idea, ¡tengamos más de esas!

(https://es.wikipedia.org/wiki/Zen_de_Python)


```python
# Easter Egg
# esta filosofía se puede invocar desde python con el siguiente comando
import this
```

    The Zen of Python, by Tim Peters
    
    Beautiful is better than ugly.
    Explicit is better than implicit.
    Simple is better than complex.
    Complex is better than complicated.
    Flat is better than nested.
    Sparse is better than dense.
    Readability counts.
    Special cases aren't special enough to break the rules.
    Although practicality beats purity.
    Errors should never pass silently.
    Unless explicitly silenced.
    In the face of ambiguity, refuse the temptation to guess.
    There should be one-- and preferably only one --obvious way to do it.
    Although that way may not be obvious at first unless you're Dutch.
    Now is better than never.
    Although never is often better than *right* now.
    If the implementation is hard to explain, it's a bad idea.
    If the implementation is easy to explain, it may be a good idea.
    Namespaces are one honking great idea -- let's do more of those!


(https://github.com/python/peps/blob/master/pep-0020.txt)

Se considera que python es un lenguaje de propósito general. Se le usa desde la elaboración de códigos muy sencillos hasta en servidores que ofrecen servicios 24/7. Asimismo, debido a que es relativamente sencillo de aprender, es ampliamente aceptado por científicos y por niños que empiezan a programar.
Su historia se remota a fines de los 80s y principios de los [90s](https://es.wikipedia.org/wiki/Historia_de_Python).

### Derivaciones de *Python*

Muchos personas han desarrollado diferetes formas de hacer más fácil el uso de python. Por ejemplo: 
### [IPython](https://es.wikipedia.org/wiki/IPython) 
![](https://ipython.org/_static/IPy_header.png)

es una terminal(shell) que permite una actividad interactiva que agrega ciertas  funcionalidades al modo interactivo incluido con Python. Estas funcionalidades son, entre otras: resaltado de líneas y errores mediante colores, una sintaxis adicional para la terminal, autocompletado mediante tabulador de variables, módulos y atributos; entre otras funcionalidades. Es un componente del paquete SciPy, el cual ha sido desarrollado para apoyo a aspectos científicos.
### [Jupyter](https://jupyter.org/about)
![](https://jupyter.org/assets/nav_logo.svg)

El proyecto Jupyter es derivado del Ipython y es una proyecto libre de lucro y de código abierto. Está considerado como de soporte para el cómputo científico interactivo para todos los lenguajes de programación. Se dice que Jupyter siempre será un software 100% de código abierto. Se implementó a partir del lenguaje [Julia](https://julialang.org) para navegar en la red, [Python](https://www.python.org) y [R](https://cran.r-project.org).

### [Bitácora electrónica Jypyter](https://jupyter-notebook.readthedocs.io/en/stable/)
<img src="https://jupyter.org/assets/jupyterpreview.png" width="30%">
es una aplicación que se ejecuta en el navegador de la red (web) y que permite hacer un seguimiento de los comandos utilizados. El lenguaje por omisión suele ser Python 3, por lo que en este curso es el lenguaje por omisión. Inicialmente se utilizaban núcleos (kernels) de Python y R, pero en la actualidad existe ya núcleos para otros lenguajes

### [Anaconda](https://www.anaconda.com)
Es una distribución de Python



### [Biopython](https://biopython.org)
<img src="https://biopython.org/assets/images/biopython_logo_white.png" width="30%">
Es un juego de herramientas gratuitas para realizar el cómputo con datos biológicos, está escrito en Python por un grupo internacional de desarrolladores.


# 3. R
<img src="https://cran.r-project.org/Rlogo.svg" width = 15%>
Es un lenguaje de programación enfocado principalmente a cómputo estadístico y gráfico que es soportado por la [*R Foundation for Statistical Computing*](https://cran.r-project.org/doc/FAQ/R-FAQ.html#What-is-R_003f). Se ha desarrollado para ejecutarse en sistemas compatibles con Unix, Windows y Mac(iOS).
Es un paquete que se rige por las características de programas de código abierto (Gnu).

Una de sus características primordiales es su ejecución en línea de comandos. Sin embargo existen ambientes desarrollo integrales (integrated development environment, o IDE)) como [RStudio](https://github.com/rstudio/rstudio) <img src="https://avatars0.githubusercontent.com/u/513560?s=200&v=4" width = 10%>que permite una interface gráfica con todas las herramientas para trabajar con R en un solo lugar (consola, fuentes, gráficas, área de trabajo, ayuda e historial). Además permite observar la edición de los comandos sobresaltada, ejecutar directamente desde el editor, entre otras características.

### Derivaciones de *R*

### [Bioconductor](http://www.bioconductor.org)
<img src="http://www.bioconductor.org/images/logo_bioconductor.gif" width="25%">
Es un proyecto de programación de gratuito y de código y fuentes abiertos, para el análisis de datos genómicos. Se basa principalmente en lenguaje R y, muy poco, en otros lenguajes de programación.


# 4. Instalación de programas

Cada uno de los programas arriba indicados se puede instalar de manera independiente en las computadoras personales.
1. [linux]()
2. [python]()
2.1 [biopython](https://biopython.org)
3. [R](https://cran.r-project.org)
3.1 [RStudio]()

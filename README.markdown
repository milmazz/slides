Presentaciones
==============

Aca podrá encontrar aquellas presentaciones que he generado para dar
charlas, talleres, entre otros.

Las presentaciones se encuentran organizadas por tópicos en particular.

El software que he utilizado para generar las presentaciones es [Beamer][],
la cual es una clase [LaTeX][] que facilita enormente la producción de
presentaciones de alta calidad, este software trabaja de la mano con `pdflatex`,
también con `dvips`.

Lista de presentaciones
-----------------------

 * *Functional Geometry Description of Escher’s Fish* es un trabajo basado en
   la publicación *Functional Geometry* de Peter Henderson. En dicha
   publicación Henderson deconstruye la obra _Square Limit_ de M.C. Escher
   haciendo uso de _álgebra de imágenes_.
 * *Análisis estático del código fuente en Python*, se describe el concepto
del análisis estático del código, se indica los pasos a seguir para la
detección de errores mediante la herramienta **Pylint**, se exponen sus
funcionalidades, reportes y se muestran ejemplos para corregir los errores
encontrados por la herramienta.
 * *Desarrollo colectivo en Turpial*, se describe la visión del cliente para
*Twitter* [Turpial][], sus funcionalidades actuales, el uso de herramientas
como [Transifex][], [PyBabel][], [Distutils][], [Sphinx][], dichas herramientas facilitan
y mejoran la calidad del software que se desarrolla.
 * *Canaima GNU/Linux, una introducción*, se describe la historia, definición
del proyecto [Canaima], principales características, procesos para colaborar,
enlaces de interés, entre otros.
 * *Uso de dbconfig-common*, presentación que es parte de la serie *Mejores
prácticas para el empaquetamiento de aplicaciones en Debian*, se describe el
uso de la herramienta y su respectiva integración con el asistente
**debhelper**
 * *Conociendo el framework web Django*, introducción, historia,
características, primeros pasos, instalación y demostración de desarrollo de
una aplicación sencilla bajo este excelente framework basado en el lenguaje de
Programación [Python][]
 * *Novela gráfica creada con el motor Ren'Py*, se relata la experiencia del
desarrollo de una novela gráfica para niños de 5to. grado de educación, de
acuerdo a currículo impartido en las escuelas venezolanas.
 * *Trac*, herramientas libres para el apoyo en el proceso de desarrollo de
software, se discute las características y funcionalidades que ofrece el
software. Además del proceso de personalización por medio de complementos o
plugins.
 * *GnuPG, GNU Privacy Guard*, importancia del cifrado de la información,
diferencias entre llaves simétricas y asimétricas, criptografía, fiestas de
firmado de llaves, beneficios. Instalación y suo práctico de GnuPG.

Convertir las fuentes .tex a PDF
--------------------------------

Lo primero que debe hacer es descargar el código fuente en LaTeX de las
presentaciones, debe tomar en cuenta que para ello necesita tener
instalado [Git][]:

    $ git clone --recurse-submodules http://github.com/milmazz/slides.git
    $ cd slides

Antes de utilizar el comando `pdflatex` asegúrese de tener instalado
el paquete [Beamer][], el procedimiento de instalación puede variar
dependiendo de su Distribución GNU/Linux o Sistema Operativo.

En sistemas Debian GNU/Linux o derivados para instalar el paquete
[Beamer][] es tan sencillo como ejecutar el siguiente comando
como superusuario:

    # apt-get install latex-beamer

Finalmente, podrá generar la presentación de la siguiente manera:

    $ pdflatex <presentacion>.tex

[Beamer]: http://latex-beamer.sourceforge.net/ 'The LaTeX Beamer Class'
[LaTeX]: http://www.latex-project.org/ 'LaTeX – A document preparation system'
[Turpial]: http://www.turpial.org.ve 'Turpial – Cliente para Twitter'
[Transifex]: http://www.transifex.net/ 'Transifex – The Open Translation Platform'
[PyBabel]: http://babel.edgewall.org/ 'Babel – Collection of tools for internationalizing Python applications'
[Distutils]: http://docs.python.org/library/distutils.html 'Distutils – Building and installing Python modules'
[Sphinx]: http://sphinx.pocoo.org/ 'Sphinx – Python Documentation Generator'
[Git]: http://git-scm.com/ 'Git - the fast version control system'
[Canaima]: http://canaima.softwarelibre.gob.ve 'Canaima GNU/Linux'
[Python]: http://www.python.org

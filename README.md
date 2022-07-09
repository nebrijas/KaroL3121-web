
# PERIODISMO DE DATOS-REPOSITORIO DE TRABAJO

### Actividades Dirigidas asignadas en el curso

1. [Actividad dirigida 1 de PD2](ad1.md)

2. [Actividad dirigida 2 de PD2](ad2.md)

3. [Actividad dirigida 3 de PD2](ad3.md)

4. [Actividad dirigida 4 de PD2](api-covid-pandas.md)


###  Ejercicio final de Programación Literaria/ Aprendizaje durante la asignatura

La materia de **Periodismo de Datos II: Herramientas  Digitales para la Visualización y Presentación de Datos** fue un aprendizaje de principio a fin, porque desconocía la mayoría de las aplicaciones y comandos  empleados durante el curso.

A nivel general destaco los conocimientos adquiridos en: lenguaje *Markdown*, uso del *GitHub*, manejo de *Git Bash*, empleo del cuaderno  de *Jupyter*, además de la elaboración de gráficas con  Pandas.

#### 1. Adentrándonos en Markdown
La **Actividad Dirigida 1** introdujo la versatilidad y sencillez de un lenguaje como Markdown, en el que empleando  símbolos del teclado del ordenador se le puede dar formato a los textos. En este sentido, por ejemplo, un `#` viene a ser un h1, es decir que con agregar almohadillas podemos conferirle formato de título a los escritos.

Además, con la ayuda de otras definiciones  podemos trabajar textos más complejos.

A título personal, uno de los elementos de marcación que he encontrado más fascinante ha sido el de enlaces [nombre en el escrito](link). De igual forma los de listas y de cursiva `*` y negrita `**` me han cautivado.

En esta etapa conocí el *GitHub*, el cual no sabía que existía y me ha parecido un servicio de *hosting* de gran utilidad y amigable para las personas sin conocimientos previos.

#### 2. Conociendo Git Bash
La **Actividad Dirigida 2** presentó nuevamente un mundo desconocido. La acción más retadora, inicialmente, fue el `git clone` porque había seguido los pasos en clases y cuando posteriormente retomé, intenté clonar y ya el paso había sido ejecutado previamente por lo que me enviaba un aviso advirtiéndome que el directorio ya existía.

Para solucionarlo, en el momento, eliminé la carpeta que estaba en mi ordenador, pero luego en clase  supe que no era necesario borrarla, adicional a que  el lío es cuando está en la misma ubicación o nivel del ordenador. 

Luego de superado este inconveniente aprendí a modificar y a  crear contenido desde esta terminal, a través de `nano.exe`.

En la terminal de *Git Bash* son claves comandos como `git status` (para conocer las actualizaciones o estados de los archivos que se trabajan), `git add` (para añadir cambios o nuevos archivos al repositorio web), `git commit-m "comentario` (colocar un indicativo a los cambios generados), así como el `git push` (para impulsar a que los cambios se reflejen y guarden en la web). No hay que dejar de lado la funcionalidad de  `pwd, cd, ls y del git pull`.

#### 3. Anaconda y Júpiter
El proceso de instalación de Anaconda fue complicado, sin embargo, en una amplia explicación brindada en una clase  posterior pude determinar los errores que estaba cometiendo y tomar nota por si en algún momento requiero instalarlo en otro ordenador. En mi caso tenía problemas con la carpeta que lo alojaba en la computadora, tras intentar descargarlo en múltiples ocasiones ya esta existía.

El acceso al cuaderno de Jupyter, una vez instalado Anaconda, fue más fácil. La actividad asignada consistió en un ejercicio de programación literaria con un código de *Python*  elaborado en una materia previa.  

En el mismo se combinó lenguaje *Markdown y code*. Incluyó así mismo una documentación sobre cómo funciona este cuaderno: cómo se crea un archivo, cómo se generan nuevas celdas, la funcionalidad de *Kernel o Run*.

#### 4. Elaborando gráficas
Una de las partes más esperadas llegó en este módulo. Trabajando en el cuaderno de *Jupyter*, pero usando Pandas pudimos visualizar datos sobre las cifras de **Covid-19 en España, Panamá y América Central**.

En esta parte pude aprender sobre urls, dominios y sobre todo de códigos para facilitar estas visualizaciones: `df, pd.read_json()` y por supuesto *plotear* para visualizar las gráficas. 

Una de las indicaciones con las que me quedo es agrupar los contenidos con concatenación al momento de elaborar gráficas y darles un nombre sencillo, en lugar de uno complicado, dado que ello  no determina el gráfico, sino es para entender de qué se trata. Por ejemplo: `df_ca = pd.concat([casos_pa,casos_cr,casos_hon,casos_ni,casos_gua,casos_sal],axis=1)`.

En concreto ha sido una materia para comprender que los lenguajes de códigos  y demás elementos de marcación no son imcomprensibles para aquellas personas que no los ven en su día a día, sino que pueden ser un gran aliado en el periodismo.









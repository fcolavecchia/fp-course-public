# F#: your first functional programming language

> This is a work in progress, as (my course on F#)[https://ibprogramacionavanzada.github.io/] is progressing
> the first semester of 2023. Atención, que por ahora la mayoría del contenido es en español.

- [F#: your first functional programming language](#f-your-first-functional-programming-language)
  - [Introduction](#introduction)
  - [Working with the notebooks](#working-with-the-notebooks)
    - [Using binder](#using-binder)
      - [Fork it!](#fork-it)
    - [Installing polyglot notebooks](#installing-polyglot-notebooks)
  - [Index](#index)
  - [Resources](#resources)


## Introduction

These guides are oriented to those programmers interested in learning some concepts on functional programming, 
from a practical perspective. F\# is an excelent _first_ functional programming language: it is functional (of course), it has a clean and readable syntax (not a lot of fancy symbols and stuff), it is flexible (in case you need to grasp some other paradigm in the middle of your code) and it is concise enough to express your ideas with clarity. 

Learning a new language _and_ a new programming paradigm is a wonderful adventure. You do not need any special preparation, although I assume that the reader has some background in at least one popular language (let us say C, Python, Java or JavaScript, for example). 

This guides are entirely written as Jupyter Notebooks. Yes, it is possible to run F\# in a Jupyter notebook interactive environment, which is fantastic for learning.

[This repository] contains the Jupyter Notebooks edition of the course. The content is in english in the `en` folder, mientras que el contenido en español está 
en el directorio `es`. Para los lectores en español, la traducción está hecha en forma automática, con la edición correspondiente en los casos en que el traductor no trabaja adecuadamente. 

> Sin embargo, hasta tanto no se consolide el contenido, dejaré la traducción automática como sale del traductor. Sepan disculpar mis lectores hispano hablantes este detalle por el momento.

The course can also be accesed as a read only content [in my blog](https://flavio.colavecchia.net/blog/), or as a course format in [Programación avanzada](https://ibprogramacionavanzada.github.io/),
the last one with exercises.

## Working with the notebooks

### Using binder

I managed(*) to develop the connection to [Binder](mybinder.org), so you can open the course directly there, just 
click this button

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fcolavecchia/fp-course.git/binder?labpath=en%2F)

You will land in a page that shows you all the magic that is behind running binder. After a while, you will land into this page:

<img src="img/mybinder-config.png" alt="Binder landing page" width="400"/>

Click on the folder icon on the left, and you will see all the available notebooks. Open the one of your
choice, check that the `Kernel` on the right is properly selected. 

It automatically detects .NET C\#, 

<img src="img/i-do-not-want-csharp.png" alt="I do not want C#" width="400"/>

but that is not the language you are looking for:

<img src="img/i-want-fsharp.png" alt="This is it" width="400"/>

and you are good to go.

> (*) I have found instructions on how to build .NET in Binder [here](https://www.macivortech.com/blog/how-to-run-dotnet-on-binder/) and copied config files from [here](https://github.com/oddrationale/AdventOfCode2021FSharp/tree/main/.binder), updated to .NET 7.
>
#### Fork it!

You can keep your own copy of this repo by forking it. Following the instructions above, you can make all the code editable in your own repo, using binder.

### Installing polyglot notebooks

If you want to experience the notebooks at your own computer, fork it and install the polyglot notebooks, follow the instructions [here](https://github.com/dotnet/interactive/blob/main/docs/NotebookswithJupyter.md). 



## Index 

En español, próximamente en otros idiomas...

- [¿Qué es F#?  ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/Intro.ipynb)
- [Fundamentos  ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/Fundamentals_new.ipynb)
- [¿Qué es una función?  ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/Functions_new.ipynb)
<!-- - [Ejercicios sobre funciones   ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/Exercises.ipynb) -->
- [Más sobre funciones   ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/MasSobreFunciones.ipynb)    
- [Pensar con tipos   ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/IntroToTypes_es.ipynb)        
- [Discriminated Unions  ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/DiscriminatedUnions_es.ipynb) 
- [Records  ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/Records_es.ipynb)
<!-- - [Ejercicios de tipos   ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/Exercises.ipynb) -->
- [Manejando por las ramas   ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/ControlFlow.ipynb)      
<!-- - [Ejercicios  ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/Exercises.ipynb)  -->
- [Tuplas   ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/Tuples.ipynb)
- [Colecciones   ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/OnCollections.ipynb) 
<!-- - [Ejercicios  ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/Exercises.ipynb) -->
- [Más sobre Colecciones   ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/MoreOnCollections.ipynb)
- [Diccionarios   ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/Maps.ipynb)
- [Excepciones   ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/Exceptions.ipynb)
<!-- - [Ejercicios  ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/Exercises.ipynb) -->
- [El tipo Result   ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/Results.ipynb)
- [Unidades de medida   ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/Units.ipynb) 
<!-- - [Un kata clásico  ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/Exercises.ipynb) -->
- [Secuencias    ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/YetAnotherTakeOnCollections.ipynb)
- [Leyendo y escribiendo archivos   ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/IO.ipynb)
<!-- - [Ejercicios  ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/Exercises.ipynb)  -->
- [Resources   ](https://github.com/fcolavecchia/fp-course-public/blob/main/es/_resources.ipynb) 


## Resources

- [The Jupyter notebook edu book](https://jupyter4edu.github.io/jupyter-edu-book/).

# F#: your first functional programming language



- [F#: your first functional programming language](#f-your-first-functional-programming-language)
  - [Quick start](#quick-start)
    - [Quick tour](#quick-tour)
    - [Fork it](#fork-it)
    - [Using binder to run on the web](#using-binder-to-run-on-the-web)
    - [Installing polyglot notebooks to run in your own computer](#installing-polyglot-notebooks-to-run-in-your-own-computer)
  - [I do not read spanish (No leo español)](#i-do-not-read-spanish-no-leo-español)
  - [About the course](#about-the-course)
  - [Index](#index)
  - [Resources](#resources)




> This is a work in progress, as [my course on F#](https://ibprogramacionavanzada.github.io/) is moving through
> the first semester of 2023. 

## Quick start

The course is structured as a collection of [Polyglot Jupyter Notebooks](https://devblogs.microsoft.com/dotnet/announcing-polyglot-notebooks-harness-the-power-of-multilanguage-notebooks-in-visual-studio-code/). 

### Quick tour

Just open this repo in MyBinder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fcolavecchia/fp-course-public.git/HEAD)

Give it a little time, and this will open the notebooks in My Binder.

### Fork it

You can keep your own copy of this repo by forking it. Following the instructions above, you can make all the code editable in your own repo, using binder.

### Using binder to run on the web

Once you fork the repo, go to [MyBinder](https://mybinder.org/). You will land into this page:

<img src="img/mybinder-config.png" alt="Binder landing page" width="400"/>

Copy the url of your forked repo into the `GitHub` field, and you can leave the `Git ref` and `Path to a notebook` 
empty. Click on launch and wait a while until My Binder works the magic. 

One the binder is opened, click on the `es` directory in the panel at the left, and you will see all the available notebooks. 

<img src="img/jupyter-at-mybinder.png" alt="I do not want C#" width="400"/>

Open the one of yourchoice, check that the `Kernel` on the right is properly selected. 

It automatically detects .NET C\#, 

<img src="img/i-do-not-want-csharp.png" alt="I do not want C#" width="400"/>

but that is not the language you are looking for:

<img src="img/i-want-fsharp.png" alt="This is it" width="400"/>

and you are good to go.


>
### Installing polyglot notebooks to run in your own computer

If you want to experience the notebooks at your own computer, you need to install the [polyglot extension for VS Code](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode), and follow the instructions there.


## I do not read spanish (No leo español)

No problem, until I manage to translate the content (which can take a while...), and if you can tolerate the automagic translation, you can use [nbTranslate](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/nbTranslate/README.html), a [Jupyter notebook extension](https://github.com/ipython-contrib/jupyter_contrib_nbextensions) that creates multilanguage notebooks by translating the content using google translate. Follow the instructions in those sites to get it work.




## About the course 

These guides are oriented to those programmers interested in learning some concepts on functional programming, 
from a practical perspective. F\# is an excelent _first_ functional programming language: it is functional (of course), it has a clean and readable syntax (not a lot of fancy symbols and stuff), it is flexible (in case you need to grasp some other paradigm in the middle of your code) and it is concise enough to express your ideas with clarity. 

Learning a new language _and_ a new programming paradigm is a wonderful adventure. You do not need any special preparation, although I assume that the reader has some background in at least one popular language (let us say C, Python, Java or JavaScript, for example). 

This guides are entirely written as Jupyter Notebooks. Yes, it is possible to run F\# in a Jupyter notebook interactive environment, which is fantastic for learning.

This repository contains the Jupyter Notebooks edition of the course. El contenido **más completo** está en español 
en el directorio `es`.

> As stated before, you can install the proper tools to translate the notebooks to your language of choice.

The course can also be accesed as a read only content [in my blog](https://flavio.colavecchia.net/blog/), or as a course format in [Programación avanzada](https://ibprogramacionavanzada.github.io/), the last one with exercises.

## Index 

Most of the notebooks names are self-explanatory, but here it is the index for a clearer organization:

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
- Instructions on how to build .NET in Binder [here](https://www.macivortech.com/blog/how-to-run-dotnet-on-binder/) and copied config files from [here](https://github.com/oddrationale/AdventOfCode2021FSharp/tree/main/.binder), updated to .NET 7.

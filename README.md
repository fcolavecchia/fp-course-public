# F#: your first functional programming language

## About the course 

These guides are oriented to those programmers interested in learning some concepts on functional programming, 
from a practical perspective. F\# is an excelent _first_ functional programming language: it is functional (of course), it has a clean and readable syntax (not a lot of fancy symbols and stuff), it is flexible (in case you need to grasp some other paradigm in the middle of your code) and it is concise enough to express your ideas with clarity. 

Learning a new language _and_ a new programming paradigm is a wonderful adventure. You do not need any special preparation, although I assume that the reader has some background in at least one popular language (let us say C, Python, Java or JavaScript, for example). 

This guides are entirely written as Jupyter Notebooks. Yes, it is possible to run F\# in a Jupyter notebook interactive environment, which is fantastic for learning.

The course can also be accesed as a read only content in [Programación avanzada](https://ibprogramacionavanzada.github.io/), en español.

> The course was produced originally in spanish, the english version was generated automagically. Hopefully you can tolerate this, until the course settles down and I can have some time to proofread 
> that translation. If you need the course in other language, you can use [nbTranslate](https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/nbextensions/nbTranslate/README.html), a [Jupyter notebook extension](https://github.com/ipython-contrib/jupyter_contrib_nbextensions) that creates multilanguage notebooks by translating the content using google translate. Follow the instructions in those sites to get it work.

## Quick start

The course is structured as a collection of [Polyglot Jupyter Notebooks](https://devblogs.microsoft.com/dotnet/announcing-polyglot-notebooks-harness-the-power-of-multilanguage-notebooks-in-visual-studio-code/). 

### Quick tour

Just open this repo in MyBinder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fcolavecchia/fp-course-public.git/main?urlpath=en/00_Index.ipynb)

Give it a little time, and this will open the notebooks in My Binder.

### Fork it

You can keep your own copy of this repo by [forking it](https://github.com/fcolavecchia/fp-course-public). Once you have your own copy, you can make all the code editable in your own repo, using binder, as explained below.

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

### Installing polyglot notebooks to run in your own computer

If you want to experience the notebooks at your own computer, you need to install the [polyglot extension for VS Code](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode), and follow the instructions there.


# Index 

## [Introduction to F#](https://github.com/fcolavecchia/fp-course-public/blob/main/en/00_Intro.ipynb)

## Functions 
  
  - [Fundamentals](https://github.com/fcolavecchia/fp-course-public/blob/main/en/01_Fundamentals.ipynb)
  - [Functions](https://github.com/fcolavecchia/fp-course-public/blob/main/en/02_Functions.ipynb)
  - [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/03_Exercises.ipynb)
  - [More on Functions](https://github.com/fcolavecchia/fp-course-public/blob/main/en/10_MoreOnFunctions.ipynb)  

## Types

  - [An Introduction to types](https://github.com/fcolavecchia/fp-course-public/blob/main/en/11_IntroToTypes.ipynb)        
  - [Discriminated Unions](https://github.com/fcolavecchia/fp-course-public/blob/main/en/12_DiscriminatedUnions.ipynb) 
  - [Records](https://github.com/fcolavecchia/fp-course-public/blob/main/en/13_Records.ipynb)
  - [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/14_Exercises.ipynb)

## Control Flow 

  - [Driving around the code with `if`, recursion and _pattern matching_](https://github.com/fcolavecchia/fp-course-public/blob/main/en/20_ControlFlow.ipynb)      
  - [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/21_Exercises.ipynb)  

## On collections 

  - [Heterogeneous collections](https://github.com/fcolavecchia/fp-course-public/blob/main/en/30_Tuples.ipynb)
  - [Homogeneous collections](https://github.com/fcolavecchia/fp-course-public/blob/main/en/31_OnCollections.ipynb) 
  - [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/33_Exercises.ipynb)

## More on collections 

  - [More on collections](https://github.com/fcolavecchia/fp-course-public/blob/main/en/40_MoreOnCollections.ipynb)
  - [Maps](https://github.com/fcolavecchia/fp-course-public/blob/main/en/41_Maps.ipynb)
  - [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/43_Exercises.ipynb)

## Managing Errors 

  - [Exceptions](https://github.com/fcolavecchia/fp-course-public/blob/main/en/42_Exceptions.ipynb)
  - [The `Result` type](https://github.com/fcolavecchia/fp-course-public/blob/main/en/50_Results.ipynb)

## [Units of measure](https://github.com/fcolavecchia/fp-course-public/blob/main/en/51_Units.ipynb) 

## Intermezzo: [A classic Kata](https://github.com/fcolavecchia/fp-course-public/blob/main/en/53_Exercises.ipynb)

## [Yet another take on collections](https://github.com/fcolavecchia/fp-course-public/blob/main/en/60_YetAnotherTakeOnCollections.ipynb)

## Intermezzo: [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/63_Exercises.ipynb) 

## Input/Output 
  
  - [Basics](https://github.com/fcolavecchia/fp-course-public/blob/main/en/61_IO.ipynb)
  - [Back to the Vending Machine](https://github.com/fcolavecchia/fp-course-public/blob/main/en/70_VendingMachineReadFood.ipynb)
  - [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/73_Exercises.ipynb) 

## Processing structured data files
  - [Type Providers](https://github.com/fcolavecchia/fp-course-public/blob/main/en/80_TypeProviders.ipynb)
  - [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/83_Exercises.ipynb) 
  
## Welcome to .NET! 
  - [.Net projects and solutions](https://github.com/fcolavecchia/fp-course-public/blob/main/en/90_Dotnet.ipynb)
  - [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/93_Exercises.ipynb)

## Tests
  - [Basics](https://github.com/fcolavecchia/fp-course-public/blob/main/en/A0_Tests.ipynb) 
  - [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/A3_Exercises.ipynb) 

## Coda: More exercises  

  - [The Gilded Rose Kata](https://github.com/fcolavecchia/fp-course-public/blob/main/en/B_GildedRose.ipynb)
  - [Advent of Code, day 2](https://github.com/fcolavecchia/fp-course-public/blob/main/en/C_AdventOfCodeDay2.ipynb)
  - [Terminal Frost games](https://github.com/fcolavecchia/fp-course-public/blob/main/en/F_inal_2023.ipynb)

## [Resources](https://github.com/fcolavecchia/fp-course-public/blob/main/en/Resources.ipynb)


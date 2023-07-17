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

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fcolavecchia/fp-course-public.git/main?labpath=en%2F00_Index.ipynb)

Give it a little time, and this will open the notebooks in My Binder.

### Fork it

You can keep your own copy of this repo by [forking it](https://github.com/fcolavecchia/fp-course-public).

### Using Binder to run on the web

Once you fork the repo, go to [MyBinder](https://mybinder.org/). You will land into this page:

<img src="img/mybinder-config.png" alt="Binder landing page" width="400"/>

Copy the url of your forked repo into the `GitHub` field, and you can leave the `Git ref` and `Path to a notebook` 
empty. Click on launch and wait a while until My Binder works the magic. 

One the binder is opened, click on the `es` (en español) or `en` (english version) directory in the panel at the left, and you will see all the available notebooks. 

<img src="img/jupyter-at-mybinder.png" alt="I do not want C#" width="400"/>

Open the one of yourchoice, check that the `Kernel` on the right is properly selected. 

It automatically detects .NET C\#, 

<img src="img/i-do-not-want-csharp.png" alt="I do not want C#" width="400"/>

but that is not the language you are looking for:

<img src="img/i-want-fsharp.png" alt="This is it" width="400"/>

and you are good to go.

### Installing polyglot notebooks to run in your own computer

If you want to experience the notebooks at your own computer, you need to install the [polyglot extension for VS Code](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode). Follow the instructions there to get everything working offline.

### I do not want to use the notebooks!

No problem simply copy/paste the codes from the notebooks in the repo into [Fable REPL](https://fable.io/repl/), which is an online F# compiler. Just write your code in the left pane, click the usual play button (or Alt+Enter) and that's it, you're programming in F\#!


## Syllabus

### [Introduction to F#](https://github.com/fcolavecchia/fp-course-public/blob/main/en/00_Intro.ipynb)

### Functions 
  
- [Fundamentals](https://github.com/fcolavecchia/fp-course-public/blob/main/en/01_Fundamentals.ipynb)
- [Functions](https://github.com/fcolavecchia/fp-course-public/blob/main/en/02_Functions.ipynb)
- [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/03_Exercises.ipynb)
- [More on Functions](https://github.com/fcolavecchia/fp-course-public/blob/main/en/10_MoreOnFunctions.ipynb)  

### Types

- [An Introduction to types](https://github.com/fcolavecchia/fp-course-public/blob/main/en/11_IntroToTypes.ipynb)        
- [Discriminated Unions](https://github.com/fcolavecchia/fp-course-public/blob/main/en/12_DiscriminatedUnions.ipynb) 
- [Records](https://github.com/fcolavecchia/fp-course-public/blob/main/en/13_Records.ipynb)
- [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/14_Exercises.ipynb)

### Control Flow 

- [Driving around the code with `if`, recursion and _pattern matching_](https://github.com/fcolavecchia/fp-course-public/blob/main/en/20_ControlFlow.ipynb)      
- [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/21_Exercises.ipynb)  

### On collections 

- [Heterogeneous collections](https://github.com/fcolavecchia/fp-course-public/blob/main/en/30_Tuples.ipynb)
- [Homogeneous collections](https://github.com/fcolavecchia/fp-course-public/blob/main/en/31_OnCollections.ipynb) 
- [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/33_Exercises.ipynb)

### More on collections 

- [More on collections](https://github.com/fcolavecchia/fp-course-public/blob/main/en/40_MoreOnCollections.ipynb)
- [Maps](https://github.com/fcolavecchia/fp-course-public/blob/main/en/41_Maps.ipynb)
- [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/43_Exercises.ipynb)

### Managing Errors 

- [Exceptions](https://github.com/fcolavecchia/fp-course-public/blob/main/en/42_Exceptions.ipynb)
- [The `Result` type](https://github.com/fcolavecchia/fp-course-public/blob/main/en/50_Results.ipynb)

### [Units of measure](https://github.com/fcolavecchia/fp-course-public/blob/main/en/51_Units.ipynb) 

### Intermezzo: [A classic Kata](https://github.com/fcolavecchia/fp-course-public/blob/main/en/53_Exercises.ipynb)

### [Yet another take on collections](https://github.com/fcolavecchia/fp-course-public/blob/main/en/60_YetAnotherTakeOnCollections.ipynb)

### Intermezzo: [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/63_Exercises.ipynb) 

### Input/Output 
  
- [Basics](https://github.com/fcolavecchia/fp-course-public/blob/main/en/61_IO.ipynb)
- [Back to the Vending Machine](https://github.com/fcolavecchia/fp-course-public/blob/main/en/70_VendingMachineReadFood.ipynb)
- [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/73_Exercises.ipynb) 

### Processing structured data files
- [Type Providers](https://github.com/fcolavecchia/fp-course-public/blob/main/en/80_TypeProviders.ipynb)
- [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/83_Exercises.ipynb) 
  
### Welcome to .NET! 
- [.Net projects and solutions](https://github.com/fcolavecchia/fp-course-public/blob/main/en/90_Dotnet.ipynb)
- [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/93_Exercises.ipynb)

### Tests
- [Basics](https://github.com/fcolavecchia/fp-course-public/blob/main/en/A0_Tests.ipynb) 
- [Exercises](https://github.com/fcolavecchia/fp-course-public/blob/main/en/A3_Exercises.ipynb) 

### Coda: More exercises  

- [The Gilded Rose Kata](https://github.com/fcolavecchia/fp-course-public/blob/main/en/B_GildedRose.ipynb)
- [Advent of Code, day 2](https://github.com/fcolavecchia/fp-course-public/blob/main/en/C_AdventOfCodeDay2.ipynb)
- [Terminal Frost games](https://github.com/fcolavecchia/fp-course-public/blob/main/en/F_inal_2023.ipynb)

## [Resources](Resources.ipynb)

This is an opinionated list of web resources and books that helped me with F\#. These are books and sites I use frequently, for a more
a complete list of resources, check [the list of the F\# Foundation](https://fsharp.org/learn/) and [the learning resources in Microsoft .NET site](https://dotnet.microsoft.com/en-us/learn/fsharp).

### Books

- [Stylish F# 6](https://link.springer.com/book/10.1007/978-1-4842-7205-3) by Kit Eason. Loved the first chapter about the sense of style in programming, and the next chapters follows that spirit.

- [Essential Functional-First F#](https://leanpub.com/essential-fsharp), by Ian Russell. With a big difference from other approaches, this book starts with a full example in F# that is througly discussed, and _then_ presents the elements of the language in the next chapters. 

- [Beginning F# 4.0](https://link.springer.com/book/10.1007/978-1-4842-1374-2), by Robert Pickering and Kit Eason. Just a little outdated (we are now at version 7.0), approaches the language from its different paradigms, from functional to object oriented to imperative programming. 

- [Expert F# 4.0](https://link.springer.com/book/10.1007/978-1-4842-0740-6), by Don Syme, Adam Granicz, Antonio Cisternino. By the very same creator of the language, it also showcases the flexibility of F# to adopt different programming paradigms. The examples are advanced in general, but useful to understand deeply the inner works of F#. 


### Functional Programming with F\#

- [F# for fun and profit](https://fsharpforfunandprofit.com/), by Scott Wlaschin. One of the most complete references with detailed examples and a profound view of fundamentals. Check also 
Scott's presentations in YouTube.

- [What I wish I knew when learning F#](https://danielbachler.de/2020/12/23/what-i-wish-i-knew-when-learning-fsharp.html), by Daniel Bachler.

### Web Development resources

- [Fable](https://fable.io/), the amazing transpiler from F# to JavaScript (and lately, [other languages](https://fable.io/blog/2022/2022-06-06-Snake_Island_alpha.html). Is not just a compiler, but a way to use these languages together. Depending on the recipe you would like to prepare, add the ingredients at your own pleasure. Also, check [Fable REPL](https://fable.io/repl/), where you can sketch with F#, no installation of anything needed

- [Feliz](https://zaid-ajaj.github.io/Feliz/)  is kind of hard to define, but basically it enables you to build and/or interact with React components directly in F#.

- [Feliz.Bulma](https://dzoukr.github.io/Feliz.Bulma) is a wrapper around the well-known [Bulma](https://bulma.io/) CSS framework, tailored to the [Feliz](https://zaid-ajaj.github.io/Feliz/) DSL. 

- [Html2Feliz](https://thisfunctionaltom.github.io/Html2Feliz/) enables you to translate plain HTML into Feliz.

- [SAFE Stack](https://safe-stack.github.io/docs/) is a full fledged F# framework to build web applications. It takes care of the front end, the backend and even the deployment into the Azure cloud. 


### High performance F\# 

- [Topological sort in F#](https://www.youtube.com/channel/UCnOx0OGml1t-6u_v2N0GemA) by Matthew Crews. In this fantastic series, Matthews starts with a pure functional version of a topological sort, and squeezes all the (rather advanced to me) features of F\# to speed up the code. 

### Misc stuff

- [What I wish I knew when learning F#](https://danielbachler.de/2020/12/23/what-i-wish-i-knew-when-learning-fsharp.html), by Daniel Bachler. 
- [A nice thread on reusability of binding names](https://github.com/dotnet/fsharp/issues/9900).
- [Decoupling decisions from effects](https://blog.ploeh.dk/2016/09/26/decoupling-decisions-from-effects/), by Mark Seemann.
- [Dependency Rejection](https://blog.ploeh.dk/2017/02/02/dependency-rejection/), by Mark Seemann.

### `fun` stuff

[The interview](https://aphyr.com/posts/342-typing-the-technical-interview).

### Interesting videos 

A [playlist of videos](https://youtube.com/playlist?list=PLnMc6Rr34vPYU5liVvEL_irif5XJQoBpK) somewhat related to this content.

### Some people to follow

- [Serge Tihon](@sergetihon) for a weekly summary of F# stuff.
- [Mark Seemann](https://blog.ploeh.dk/), fantastic in-deep blog on programming.
- [Scott Hanselman](@shanselman) for software, the universe and everything.
- [F# Online](@fsharponline) for, well, all F#.
- [Fast F#](@FastFSharp), squeezing out F# for performance.
- [Angel Muñoz](@angel_d_munoz), for F# and the www.

### Educational Resources

- [The Jupyter notebook edu book](https://jupyter4edu.github.io/jupyter-edu-book/).

- Instructions on how to build .NET to work Binder [here](https://www.macivortech.com/blog/how-to-run-dotnet-on-binder/) and copied config files from [here](https://github.com/oddrationale/AdventOfCode2021FSharp/tree/main/.binder), updated to .NET 7.


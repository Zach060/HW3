# HW3
# Zachary Ruhl
# Why are Certain Programming Languages More Suited for Certain Tasks?

## Overview

This LLM Research explores the question why certain programming languages are more suitable for specific tasks than others. Programming languages are made and fitted with distinct features that give them an advantage in certain areas such as performance and memory management. By looking at historical development of the languages and how they evolved over time this paper sheds light to why we can’t have a universal language to fit every task and how these languages will continue to evolve. 


## Introduction

  Programming languages are created with various features that are supposed to give them an edge over others when completing certain tasks. Some important features that one might strive for includes performance, ease of use, platform dependencies, memory, etc. 
		With the understanding that different programming languages are used to accomplish different tasks as they have a certain “edge”, it’s important to ask well how did they do this? Well these languages are suited for their respective roles based on how their core design aligns with what tasks need to be completed. An example of this can be with memory management. If someone were to create a language and wanted to change the performance of certain components they’d have to have control over the amount of memory being used. This is heavily important in areas such as game development where you want to avoid performance bottleneck areas such as garbage collection pauses. 


## Historical Development

The first programming language first arose back in the 1940’s known as Assembly Language. Assembly language was developed with the main purpose of being able to control early electronic computers easier such as ENIAC, where instead of typing in 0’s and 1’s to edit configurations in the hardware, developers could use the assembly language for more human-like instructions. Following that Fortran in the 1950s was developed which was considered the first high-level programming language specifically manufactured for scientific and engineering computations. These languages highlight the importance of the production of further programming languages to be able to advance technology in specific areas.  

## Popular Programming Languages

### C#
C# was introduced back in the early 2000’s by Microsoft where it was created as part of Microsoft's .NET alternative that was to expand and improve upon Java and C++. The language came about because they needed a language for their .NET framework which was a platform intended to help with creating applications for windows in efficient ways while being able to perform web and mobile applications. A key feature of this language is that it’s object oriented, meaning that the code is very modular and easy to maintain. Also the language has a strong type system that checks static types at compile time rather than run-time. The most common places we’ve seen C# used has been for web applications and desktop applications as C# is compatible with Linux and Mac-OS servers, not just windows. Most importantly it’s been used heavily in game development where it is the primary programming language in Unity which is a huge development platform for both 2D and 3D games. This language remains popular because of it’s ease of use with it’s good balance between power and simplicity and it’s close ties to the .NET core where it allowed developers create applications for multiple operating systems. 
### Java
Java first originated back in 1995 by a team of engineers at Sun Microsystems. The language was originally intended for the use of interactive televisions, however the language was seen to be too advanced for cable at the time. It shifted it’s focus from televisions and was changed to be able to be used for a broad range of applications. The most popular being web applets with expanding into other areas such as consumer electronics and mobile devices. Java was known for one of its main features when it was created which was  it’s platform independency. This meant that any platform that had JVM(Java Virtual Machine) installed would be able to run the compiled bytecode anywhere giving it’s slogan “write once, run anywhere”. This made Java ideal for networked environments such as the web. Java remains popular now It’s widely used in enterprise environments due to its reliability, scalability, and rich ecosystem of libraries and frameworks.

### Python
Python was first created back in 1991 by Guido van Rossum with the purpose of a language that’s easy to understand but still complete complex tasks. While being produced the language had the philosophy that there should be one clear way to complete a given task. This gave the language a super easy learning curve due to it’s clean syntax. A key feature of python is that it’s dynamically typed meaning you don’t need to declare variables. In addition the language abstracts away from low-level details of the computer making it easier to focus on the problem at hand rather than underlying system hardware. Some criticisms about the language is that python is a lot slower than languages such as Java or C++ because of it’s an interpreted language with dynamic typing that comes with runtimes overhead. This makes it less viable for performance critical applications. However it has been known to dominate the data science and machine learning field. This is due to the vast amount of libraries that python has for it such as Numpy and Pandas.
## Influential Researchers

- [**Anders Hejlsberg**](https://en.wikipedia.org/wiki/Anders_Hejlsberg) – Lead architect of C# and contributor to TypeScript.
- [**James Gosling**](https://en.wikipedia.org/wiki/James_Gosling) – Creator of Java, a language that transformed web and enterprise development.
- [**Guido van Rossum**](https://en.wikipedia.org/wiki/Guido_van_Rossum) – The creator of Python, known for its readability and simplicity.

## Why Can't We Have a Universal Programming Language?
Since specific languages give us advantages that others don’t, why can’t we just make one universal language that checks all the boxes? While this idea may seem appealing there are many reasons as to why this would never be a feasible option due to languages being optimized for certain tasks and attributes that couldn’t be possible with a combination. 

The idea of a universal language is appealing, but several reasons make it impractical:
1. **Trade-offs in Language Design**: Performance vs Flexibility-Low level languages offer more control over memory and hardware which in result gives high performance. However there is a much steeper learning curve and could result in more errors revolving around the performance. On the contrary Python, a very high level language offers flexibility and ease of use but can’t give you a good performance result. 
2. **Different Domain Requirements**: Each domain of software development has a different set of requirements that makes them unique. Real-time systems would use languages like C++ because they have predictable performance and memory usage unlike python which could introduce unexpected delays such as garbage collection since you don’t have as much control over the hardware.
3. **Performance Optimization**: Different languages are made and optimized for different types of performance. For low-level performance one might use C or C++ for more control over the memory and processor. These types of languages are a necessity when you need high throughput and minimal overhead. 
For high productivity one would have to write clean organized code but come with an overhead. This is quite the opposite to the other.
4. **Programming Paradigms**: Programming languages are built around various paradigms such as being object oriented or functional. Functional would consist of higher-order functions, and declarative programming. Good languages for this are Haskel or Lisp. While object oriented it focuses on Organizing code around objects and data structures. Languages like Java are good for these sort of tasks
5. **Community and Ecosystem**: Programming languages often become successful because of their communities/ecosystems such as libraries or IDE’s.Combining all these tools and libraries into one universal ecosystem would be overwhelming and could result in a fragmented or less effective toolset.
6. **Evolution of Languages**: Finally programming languages evolve over time to fit specific demands or needs. Each individual language can focus on it’s needs in it’s domain, however if it were to be one universal language it would have to expand and evolve in all directions simultaneously.

## Optimizations in Programming Languages

Memory Management Optimizations have been made to languages such as GO and Java to determine whether objects should be allocated to the stack or the heap, thus reducing the overhead garbage collection. This improves performance by limiting heap allocations and the garbage collection costs. Another important optimization that was added over the years for most languages were type systems. The compiler deduces the type of variables and expressions without explicit type annotations. This improves code readability without sacrificing the benefits of static typing. 

It is pretty mind blowing seeing just how much more a language can improve as more versions of it are released with improvement to various categories. A prime example of this is with python. At this point python is in it’s third version where it is seeing to be hundreds of times faster than when it was in it’s 1.x model for specific operations.


## References

- [Praxent - History of Programming Languages](https://praxent.com/blog/history-of-programming-languages)
- [101.school - Compilers and Languages](https://101.school/courses/compilers-and-languages/modules/3-language-design-criteria/units/2-language-design-trade-offs)
- [IEEE Xplore - Programming Languages: The First 25 Years](https://ieeexplore.ieee.org/abstract/document/1674589)
- GPT 4o
---

This paper highlights the complexity of language design and how the demands of different fields necessitate diverse programming languages.

# 8W8L-Summer-Project
**Mentor** : [Yugesh Kothari](https://github.com/yugeshk)

## *AIM*

The main aim of this project is to get familiar with different languages and programming models and how they are fundamentally different from one another. 
*****************************
### *General Concepts*

The following aspects of a language must be kept in mind while using it:

#### 1. The Programming Model
   It refers to the way or style of writing programs. Some common programming models are:
   Procedural Oriented (C), Object Oriented (Ruby, C++),Functional (Haskell), Logic (Prolog).Hereby, a small description for each model has been provided:</br>
   - ***Procedural Oriented***: In such languages, the program code is written as a sequence of instructions mainly in the form of sub-functions. This has been derived from structured programming.Examples include C and FORTRAN.</br>
   - ***Purely Object Oriented***: In such languages, everything is compiled as an object. Cosequently, such languages become extensible too as one can define his own fucntions specific to even any constant( like a number)!. Ruby is one such language.</br>
   - ***Purely Functional***: In languages like Haskell, *everything* is considered to be a function. Here, functions also do not have any side-effects ,i.e., no function can alter the internal state of some variable.</br>
   - ***Logic Programming***: For these, PROLOG(*pro*gramming in *log*ic) is the best known example. Here, a program is executed by an “inference engine” that answers a query by searching these relations systematically to make inferences that will answer a query.</br>
   
#### 2. The Programming Paradigm
   From a wider aspect, this includes the imperative and declarative paradigms. Decalrative expresses the logic of             computation without describing its workflow whereas imperative programming computes with full control over the control flow. Declarative is more about telling what to do and imperative is about telling out exactly how to compute some expression.<br>The two common kinds of declarative languages are logic and functional languages.Procedural oriented is considered to be belonging to the imperative paradigm.

#### 3. Syntax
   Syntax of a programming language is like its spelling and grammar. It is a set of rules which define the combinations of symbols which will be considered as correctly structured.

#### 4. Type System
   The type system is a set of rules which assign a property called "type" to various components of a program. Having a good type system can help to reduce bugs.</br>
   Main categories:</br></br>
   A. *Strong vs Weak typing<*/br>
      The distinction is not strict. If typing rules are enforced more strictly, the typing is said to be strong and weak if otherwise. The terms are relative. E.g. Java is considered strong while Javascript is considered weak.</br></br>
   B. *Static vs Dynamic typing*</br>
      In static typing, the type is determined at compile time/time of writing the code. Examples include C, C++, Haskell, etc. In dynamic typing, type safety is verified at runtime. Examples of dynamically typed languages are Python and Ruby.</br></br>
   C. *Manifest vs Inferred*</br>
      In manifest typing, type has to be explicitly declared, e.g. as in C. While in inferred typing, the type is intelligently detected e.g. as in Python.</br></br>
   D. *Nominal vs Structural*</br>
      Nominal typing means that two variables are type-compatible if and only if their declarations name the same type. For example, in C, two struct types with different names in the same translation unit are never considered compatible, even if they have identical field declarations. In structural type system, equivalence is determined only by the type's actual structure. Examples of languages following this are OCaml and Go.</br></br>
   E. *Duck Typing*</br>
      It is similar to, but different from structural typing. An object's suitability is determined by the presence of certain methods and properties, rather than the type of the object itself. That is, if we have different types which have the same method, we can write code agnostically.
******************************************
### *Python*
- Python is an interpreted, high-level, general purpose programming language.
- import module is used to make speciality functions available.
- Python's design philosophy emphasizes code readability with its notable use of significant whitespace.
- print() outputs the data on the screen.
- There are 5 data types: Numbers, Strings, List, Tuple, Dictionary.
- " ** " >exponential calculation, " // " Floor division
- Dicts can't be join with '+'.
- Python interpreter and the extensive standard library are available in source or binary form without charge for all major platforms, and can be freely distributed.

#### CLASSES AND OBJECTS 
The concept of OOP allows us to model real world things using code.</br>
Every object has attributes like (color, height, weight) which are object variables.</br>
Every object has abilities like (walk, talk, eat) which are object functions.</br>
You can't access this value directly because it is private.</br>
You can inherit all of the variables and methods from another class.</br>
Polymorphism allows use to refer to objects as their super class and the correct functions are called automatically.</br>

***********************************
### *Ruby*

************************************
### *Haskell*
***About the language*** </br>Haskell is a purely Functional programming language with inferred, strong and static type discipline.
Functional programming is very different from Imperative programming in which programs consist of a sequence of commands, which are strictly evaluated one after the other. A functional program is a single expression, which is executed by evaluating the expression. Compared to the traditional programming languages, Haskell allows us to write much shorter and cleaner code. It is also easier to maintain. Another advantage of Haskell is that there are no "side effects", that is, functions cannot change state like changing the contents of a variable. This seems limiting at first glance, but helps to minimise bugs in the code and makes it easy to debug. Haskell follows "lazy" evaluation, which means that it doesn't evaluate or calculate things unless it's really forced to.</br></br>
***In this project*** </br> We will be using the Glasgow Haskell Compiler (GHC) which comes along with the Haskell Platform which also has useful packages included. Apart from the official documentation, we will use the book "Learn You a Haskell for Great Good!" as reference.</br></br>
***Relevant Links*** </br>Docs: https://www.haskell.org/documentation/ </br>Reference: http://learnyouahaskell.com/chapters
************************************
### *Scala*
***About the Language*** </br>
Scala, developed by Martinn Odersky and his team, is a really cool modification of the legendary Java. It was developed with the main motive of enhancing the scalability of Java as languages like Rails and Python are scalable, but only to an extent. It inherits in itself properties of both, Object Oriented Languages and Functional Languages.
Scala gives us control over the internal state of the variables by providing two types for variable declaration, var and val, the latter being immutable. It is a statically typed and an extensible programming language.</br></br>
***In this project***</br>
The official documentations for Scala were good enough for the team  to understand and appreciate Scala, which is a multiple paradigm language. Apart from the docs, however, we referred the book 'Scala for the Impatient' which covered almost all aspects of the Scala(ble) Language.</br></br>
***Relevant Links***</br>
Docs: https://docs.scala-lang.org/tour/tour-of-scala.html </br>


*******
### *Tasks*

Following are the tasks given till now:

1.[Python] To implement basic command line utilities. </br>
2.[Haskell] To implement some simple functions.

************************************
### Link to Repositories of the Team Members
- Kartikeya Gupta: https://github.com/kartikcode/8W8L
- Harish Adsule  : https://github.com/harishss3/8l8w
- Pranay Agarwal: https://github.com/pranay12345678/8lang
- Tushar Kumar: https://github.com/ktushar585/Summercamp
- Tej Prakash: https://github.com/tej4826/Eight_Weeks_8L

************************************
### Contributed by: </br>
- [Harish Adsule](https://github.com/harishss3)
- [Kartikeya Gupta](https://github.com/kartikcode)
- [Tej Prakash](https://github.com/tej4826)


# 8W8L-Summer-Project
**Mentor** : [Yugesh Kothari](https://github.com/yugeshk)

## *AIM*

The main aim of this project is to get familiar with different languages and programming models and how they are fundamentally different from one another. 
*****************************
***Contribution***: </br>
- [Harish Adsule](https://github.com/harishss3)
- [Kartikeya Gupta](https://github.com/kartikcode)
- [Tej Prakash](https://github.com/tej4826)
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


- import module is used to make speciality functions available.
- print() outputs the data on the screen.
- There are 5 data types: Numbers, Strings, List, Tuple, Dictionary.
- " ** " >exponential calculation, " // " Floor division
- Dicts can't be join with '+'.



##STRINGS</br>
**A string is a series of characters surrounded by ' or "**</br>
long_string = "I'll catch you if you fall - The Floor"
 
**Retrieve the first 4 characters**</br>
print(long_string[0:4])
 
**Get the last 5 characters**</br>
print(long_string[-5:])
 
**Everything up to the last 5 characters**</br>
print(long_string[:-5])
 
**Concatenate part of a string to another**</br>
print(long_string[:4] + " be there")
 
**String formatting**</br>
print("%c is my %s letter and my number %d number is %.5f" % ('X', 'favorite', 1, .14))
 
**Capitalizes the first letter**</br>
print(long_string.capitalize())
 
**Returns the index of the start of the string case sensitive**</br>
print(long_string.find("Floor"))
 
**Returns true if all characters are letters ' isn't a letter**</br>
print(long_string.isalpha())
 
**Returns true if all characters are numbers**</br>
print(long_string.isalnum())
 
**Returns the string length**</br>
print(len(long_string))
 
**Replace the first word with the second (Add a number to replace more)**</br>
print(long_string.replace("Floor", "Ground"))
 
**Remove white space from front and end**</br>
print(long_string.strip())

**Split a string into a list based on the delimiter you provide**</br>
quote_list = long_string.split(" ")
print(quote_list)
##FILE I/O -------------
 
**Overwrite or create a file for writing**</br>
test_file = open("test.txt", "wb")
 
**Get the file mode used**</br>
print(test_file.mode)
 
**Get the files name**</br>
print(test_file.name)
 
**Write text to a file with a newline**</br>
test_file.write(bytes("Write me to the file\n", 'UTF-8'))
 
**Close the file**</br>
test_file.close()
 
**Opens a file for reading and writing**</br>
test_file = open("test.txt", "r+")
 
**Read text from the file**</br>
text_in_file = test_file.read()
 
print(text_in_file)
 
**Delete the file**</br>
os.remove("test.txt")

##CLASSES AND OBJECTS -------------
**The concept of OOP allows us to model real world things using code**</br>
**Every object has attributes (color, height, weight) which are object variables**</br>
**Every object has abilities (walk, talk, eat) which are object functions**</br>
 
class Animal:
    *** None signifies the lack of a value
    *** You can make a variable private by starting it with __
    __name = None
    __height = None
    __weight = None
    __sound = None
 
    *** The constructor is called to set up or initialize an object
    *** self allows an object to refer to itself inside of the class
    def __init__(self, name, height, weight, sound):
        self.__name = name
        self.__height = height
        self.__weight = weight
        self.__sound = sound
 
    def set_name(self, name):
        self.__name = name
 
    def set_height(self, height):
        self.__height = height
 
    def set_weight(self, height):
        self.__height = height
 
    def set_sound(self, sound):
        self.__sound = sound
 
    def get_name(self):
        return self.__name
 
    def get_height(self):
        return str(self.__height)
 
    def get_weight(self):
        return str(self.__weight)
 
    def get_sound(self):
        return self.__sound
 
    def get_type(self):
        print("Animal")
 
    def toString(self):
        return "{} is {} cm tall and {} kilograms and says {}".format(self.__name, self.__height, self.__weight, self.__sound)
 
**How to create a Animal object**</br>
cat = Animal('Whiskers', 33, 10, 'Meow')
 
print(cat.toString())
 
**You can't access this value directly because it is private**</br>
print(cat.__name)
 
**INHERITANCE -------------**
**You can inherit all of the variables and methods from another class**</br>
 
class Dog(Animal):
    __owner = None
 
    def __init__(self, name, height, weight, sound, owner):
        self.__owner = owner
        self.__animal_type = None
 
        *** How to call the super class constructor
        super(Dog, self).__init__(name, height, weight, sound)
 
    def set_owner(self, owner):
        self.__owner = owner
 
    def get_owner(self):
        return self.__owner
 
    def get_type(self):
        print ("Dog")
 
    *** We can overwrite functions in the super class***
    def toString(self):
        return "{} is {} cm tall and {} kilograms and says {}. His owner is {}".format(self.get_name(), self.get_height(), self.get_weight(), self.get_sound(), self.__owner)
 
    *** You don't have to require attributes to be sent***
    *** This allows for method overloading***
    def multiple_sounds(self, how_many=None):
        if how_many is None:
            print(self.get_sound)
        else:
            print(self.get_sound() * how_many)
 
spot = Dog("Spot", 53, 27, "Ruff", "Derek")
 
print(spot.toString())
 
**Polymorphism allows use to refer to objects as their super class and the correct functions are called automatically**</br>
 
class AnimalTesting:
    def get_type(self, animal):
        animal.get_type()
 
test_animals = AnimalTesting()
 
test_animals.get_type(cat)
test_animals.get_type(spot)
 
spot.multiple_sounds(4)


***********************************
### *Ruby*

************************************
### *Haskell*

************************************
### *Scala*



*******
### *Tasks*

Following are the tasks given till now:

1.[Python] To implement basic command line utilities. </br>
2.[Haskell] To implement some simple functions.

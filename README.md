# Scala Koans

This is a custom version of the [Scala Koans](http://scalakoans.webfactional.com/) test suite.     

The versions of scala and scalatest that they use are a little outdated. This project uses 
the more current versions of those, and removes all the custom bootstrap code that 
is now incompatible and unnecessary (IMHO) for running the tests.

## Getting Started
To get started (and assuming you have sbt installed), open a terminal to the root of this project and run:
    
    sbt test
    
Alternatively, if you use a decent IDE (Intellij IDEA), you should be able to import the project 
by pointing its import wizard at *build.sbt*.  Once imported, you should just be able to right click
the *src/tests* folder, and select the *run* option.


## License

This is essentially the same code from the Scala Koans project, 
so [their license](http://scalakoans.webfactional.com/license) is this project's 
license - the  
[Attribution-NonCommercial-ShareAlike 3.0 Unported (CC BY-NC-SA 3.0)](https://creativecommons.org/licenses/by-nc-sa/3.0/)  


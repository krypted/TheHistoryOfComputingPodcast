# The Evolution Of Language Through The Use of Hello World
Sure, it's probably more useful to instatiate and manipulate variables, highlight different techniques for recursion, or different data structures, but the number of characters required to print "Hello Cruel World!" to a screen is perhaps a good litmus for the productivity level of developers.

## Machine Code
## Assembly
## CODASYL
## COBOL
```
IDENTIFICATION DIVISION.
PROGRAM-ID. HELLOWORLD.
ENVIRONMENT DIVISION.
PROCEDURE DIVISION.
    DISPLAY 'Hello Cruel World!'.
    STOP RUN.
```
## FORTRAN
### FORTRAN 66
```
WRITE (6,7,8)
FORMAT(13H Hello Cruel World)
STOP
END
```
### FORTRAN 77
```
PROGRAM HELLOWORLD
     PRINT '(A)', 'Hello Cruel World!'
     STOP
END
``` 
### Fortran 90
```
program hellocruelworld
  print *, 'Hello Cruel World!'
end program hellocruelworld
```
## ALGOL
```
printf(($gl$, "Hello Cruel World!"))
```
## Lisp

### Most Modern Lisps
```
(format t "Hello Cruel World!")
```
## BASIC
```
10 print "Hello Cruel World!"
```
## C
```
#include <stdio.h>
int main() {
printf("Hello Cruel World!");
return 0;
}
```
## AWK
## Smalltalk
## PASCAL
## C++
```
#include <iostream>

int main() {
	std::cout << "Hello Cruel World!";
	return 0;
}
```
## C#
```
namespace HelloCruelWorld
{
    class Helloworld {        
        static void Main(string[] args)
        {
            System.Console.WriteLine("Hello Cruel World!");
        }
    }
}
```
## Hypercard
## Java
```
class HelloCruelWorld {
    public static void main(String[] args) {
        System.out.println("Hello Cruel World!"); 
    }
}
```
### Scala
```
object Hello extends App {
	printIn("Hello Cruel World!")
}
```
## Turbo Pascal
## Delphi
## .Net
## Visual Basic
## Perl
## Raku
## PHP
## Python
## Ruby
## Go
## MATLAB
```
disp('Hello Cruel World!');
```

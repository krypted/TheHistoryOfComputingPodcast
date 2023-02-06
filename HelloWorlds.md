# The Evolution Of Language Through The Use of Hello World
This is meant to be used in conjunction with Chapter 6 of "The History of Computing" to highlight one of the ways programming languages have evolved over the past 60+ years. Sure, it's probably more useful to instatiate and manipulate variables, highlight different techniques for recursion, different data structures, typing, etc. But the number of characters required to print "Hello Cruel World!" to a screen is perhaps a good litmus for the productivity level of developers.

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
FORTRAN was initially used with punch cards and so for some of the earlier versions it was necessary to punch certain characters into a given like (like if commenting out code). So while it hasn't necessary gotten easier once punched, it's easier to not have to maybe...
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

### Common Lisp
```
puts "Hello Cruel World!"
```
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
```
awk 'BEGIN { print "Hello Cruel world!" }'
```
## Smalltalk
```
'Hello Cruel World!' printNl !
```
## PASCAL
```
```
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
```
```
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
```
```
## Delphi
```
```
## .Net
```
```
## Visual Basic
```
```
## Perl
```
perl -e "print qq{Hello Cruel World\n}" 
```
## Raku
```
```
## PHP
```
```
## Python
```
```
## Ruby
```
puts "Hello World"
```
## Go
```
import "fmt"
func main() {
    fmt.Println("Hello Cruel World!")
}
```
## MATLAB
```
disp('Hello Cruel World!');
```
## Swift
```
print("Hello Cruel World!") 
```

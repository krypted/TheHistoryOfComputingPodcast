# The Evolution Of Language Through The Use of Hello World
This is meant to be used in conjunction with Chapter 6 of "The History of Computing" to highlight one of the ways programming languages have evolved over the past 60+ years. Sure, it's probably more useful to instantiate and manipulate variables, highlight different techniques for recursion, different data structures, typing, etc. But the number of characters required to print "Hello Cruel World!" to a screen is perhaps a good litmus for the productivity level of developers. Here we have two characters in the exclamation point (!) and the space that usually need to be escaped or casue the whole string to be treated as a literal. Some of these are compiled languages and others are interpretated (some can be both), which is covered in more depth in the book.

To see these on a timeline, see: https://miro.com/app/board/uXjVOcM3Y-M=/?invite_link_id=982806079617.

Also, contributions are welcome!

## Binary
```
1001000 1100101 1101100 1101100 1101111 100000 1000011 1110010 1110101 1100101 1101100 100000 1010111 1101111 1110010 1101100 1100100 100001
```
## Hex
```
48656c6c6f20437275656c20576f726c6421
```
## Assembly
This can vary wildly based on the version of Assembly (e.g. the 6502 vs a modern ARM or Intel variant). The more common is probably x86, so... 
```
    org  0x100       
    mov  dx, msg     
    mov  ah, 9       
    int  0x21        
    mov  ah, 0x4c    
    int  0x21        
    msg  db 'Hello Cruel World!', 0x0d, 0x0a, '$'
```
To see a number of different basics, check out http://helloworldcollection.de.    
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
BEGIN DISPLAY("Hello Cruel World!") 
END.
```
Or for more modern incantations
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
## APL
```
'Hello Cruel World!'
```
## C
```
#include <stdio.h>
int main() {
printf("Hello Cruel World!");
return 0;
}
```
## Bash
```
echo "Hello Cruel World!"
```
## AWK
```
awk 'BEGIN { print "Hello Cruel world!" }'
```
## TCL
```
puts "Hello Cruel World!"
```
## Smalltalk
```
'Hello Cruel World!' printNl !
```
## PASCAL
```
program HelloCruelWorld;
begin
  writeln ('Hello Cruel World!');
end.
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
## F#
```
printfn "Hello Cruel World!"
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
## JavaScript
```
console.log("Hello Cruel World!");
```
## Typescript
```console.log 'Hello Cruel World!'
```
### Scala
```
object Hello extends App {
	printIn("Hello Cruel World!")
}
```
## Turbo Pascal
```
program Hello;
begin
  writeln ('Hello Cruel World!');
end.
```
## Delphi
```
WriteLn('Hello Cruel World!');
    ReadLn;
```
## HTML and .Net
Fine, this is more of a layout than a language, language, but bear with me...
```
<html>
   <body>

      <h1>Hello Cruel World!</h1>

   </body>
</html>
```
## Visual Basic
```
Module HelloCruelWorld
     Sub Main( )
        System.Console.WriteLine("Hello Cruel World!")
     End Sub
  End Module
```
## Perl
```
perl -e "print qq{Hello Cruel World\n}" 
```
or for more modern versions:
```
print "Hello Cruel World!";
```
## Raku
```
say 'Hello Cruel World!';
```
or
```
print("Hello Cruel World!\n");
```
## PHP
CLI
```
echo "Hello Cruel World!";
```
Or to print to a page:
```
<?php
  echo "Hello Cruel World!";
?>
```
## Python
```
print('Hello Cruel World!')
```
## Ruby
```
puts "Hello Cruel World!"
```
## Go
```
printfn "Hello Cruel World!"
```
Or in a function:
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
## Kotlin
```
fun main(args: Array<String>){
	println("Hello Cruel World!")
}
```
## R
```
cat('Hello Cruel World!')
```
## Dart
```
void main() {
  print("Hello Cruel World!");
}
```

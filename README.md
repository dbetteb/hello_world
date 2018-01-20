# hello_world
Summarizes many hello_world programs in many languages

## Purpose of the project

As many of us will first start learning a programming language with a 'Hello World' programs.

## Imperative languages

### C

#### Raw C-code

```c
// hello.c
#include <stdio.h>

int main() {
    printf("Hello, world !\n");
    return 0;
}
```
#### Use of the code

The previous code should be written and saved in a file named `hello.c`, then on UNIX-like systems (Unix, Linux, Mac OS X), on a
terminal type

```bash
gcc -o hello hello.c
```

Note: on a UNIX-like system ran on Windows (namely that call `.exe` MS Windows), you might need to add a `.exe` ending to run
the program

```bash
gcc -o hello hello.c
```


and then run the executable 
```bash
./hello
```

you should see then
```bash
./hello
Hello, world !
```

## Object-oriented languages

### Java

#### Raw Java code

```java
public class Hello {

    public static void main(String[] args) {
        System.out.println("Hello, World");
    }

}
```

#### Use of code

The previous code should be written and saved in a file named `Hello.java`, then
```bash
javac Hello.java
```

and then

```bash
java Hello.java
```

### C++

#### Raw C++ code

```cpp
// hello.cpp
#include <iostream>
using namespace std;

int main()
{
    cout << "Hello, world!" << endl;
    return 0;
}
```

#### Use of code

The previous code should be written and saved in a file named `hello.cpp`, then on UNIX-like systems (Unix, Linux, Mac OS X), on a
terminal type

```bash
g++ -o hello_cpp hello.cpp
```

Note: on a UNIX-like system ran on Windows (namely that call `.exe` MS Windows), you might need to add a `.exe` ending to run
the program

```bash
g++ -o hello_cpp.exe hello.cpp
```


and then run the executable 
```bash
./hello_cpp
```

you should see then
```bash
./hello
Hello, world !
```

### Python (2.7)

```python
print "Hello, world !"
```


### Python (> 3.X)

#### Raw Python code

```python
print("Hello, World !")
```


#### Use of code

The previous code should be written in file named `hello.py`, then 

```bash
python hello.py
```


### Scala

#### In `scala` REPL interpreter

```bash
scala>println("Hello, world!")
```

#### Raw scala code

```scala
object HelloWorld {
  def main(args: Array[String]): Unit = {
    println("Hello, world!")
  }
}
```

#### Use of code

```bash
scalac HelloWorld.scala
```

### Node.js

#### In `node` interpreter

```bash
> console.log("Hello, world!")
```

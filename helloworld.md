# Helloworld Programs
***

![Hello World!](./helloworld.png)

We list below Helloworld programs for different programming languages, i.e. programs that print "Hello, World!". The specified compiler or interpreter is required for each programming language.

The table below summarizes the programs:

| Language        | Language (Spec) Site                                                                           | Section                     | Build / Run Toolchain | Debian / Ubuntu Packages |
|-----------------|------------------------------------------------------------------------------------------------|-----------------------------|-----------------------|--------------------------|
| C               | [The standard - C](https://www.iso-9899.info/wiki/The_Standard)                                | [C](#c)                     | GCC                   | build-essential          |
| C++             | [The standard - C++](https://isocpp.org)                                                       | [C++](#c++)                 | GCC / G++             | build-essential, g++     |
| Dlang           | [D Programming Language: Home](https://dlang.org/)                                             | [Dlang](#dlang)             | Dlang                 | build-essential, gdc     |
| Go              | [The Go Programming Language](https://go.dev/doc/)                                             | [Go](#go)                   | Go                    | golang                   |
| Rust            | [Rust Programming Language](https://rust-lang.org/learn/)                                      | [Rust](#rust)               | Rust (Crate)          | rustlang                 |
| Java            | [Java Programming Language](https://www.java.com/en/download/help/whatis_java.html)            | [Java](#java)               | JDK                   | openjdk-17-jdk           |
| x86_64 assembly | [x86 and amd64 instruction reference](https://www.felixcloutier.com/x86/)                      | [x86_64 assembly](#asm_x86) | GCC / GAS             | build-essential          |
| ARM64 assembly  | [Arm A64 Instruction Set Architecture](https://developer.arm.com/documentation/102374/latest/) | [ARM64 assembly](#asm_arm)  | GCC / GAS (AArch64)   | build-essential          |
| Bash            | [Bash Reference Manual](https://www.gnu.org/software/bash/manual/bash.html)                    | [Bash](#bash)               | Bash                  | bash                     |
| Python          | [Welcome to Python.org](https://www.python.org/)                                               | [Python](#python)           | Python                | python                   |
| Ruby            | [Ruby Programming Language](https://www.ruby-lang.org/en/)                                     | [Ruby](#ruby)               | Ruby                  | ruby                     |
| PHP             | [PHP: Hypertext Preprocessor](https://www.php.net/)                                            | [PHP](#php)                 | PHP                   | php                      |
| Perl            | [The Perl Programming Language](https://www.perl.org/)                                         | [Perl](#perl)               | Perl                  | perl                     |
| Lua             | [The Programming Language Lua](https://www.lua.org/)                                           | [Lua](#lua)                 | Lua                   | lua                      |


## C

```c
#include <stdio.h>

int main(void) {
    puts("Hello, World!");
    return 0;
}
```

Build with:

```bash
gcc -Wall -o helloworld helloworld.c
```

Run with:

```bash
./helloworld
```

## C++

```cpp
#include <iostream>

int main() {
    std::cout << "Hello, World!" << std::endl;
    return 0;
}
```

Build with:

```bash
g++ -Wall -o helloworld helloworld.cpp
```

Run with:

```bash
./helloworld
```

## Dlang

```cpp
import std.stdio;

void main() {
    writeln("Hello, World!");
}
```

Build with:

```bash
gdc -Wall -o helloworld helloworld.cpp
```

Run with:

```
./helloworld
```

## Go

```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!");
}
```

Build and run with:

```bash
go run helloworld.go
```

## Rust

```rs
fn main() {
    print!("Hello, World!");
}
```

Build with:

```bash
ruustc helloworld.rs
```

Run with:

```bash
./helloworld
```

## Java

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

Build with:

```bash
javac HelloWorld.java
```

Run with:

```bash
java HelloWorld
```

## x86_64 Assembly

```
; mr. cdl instructor, you have some work left to do
```

Build with:

```bash

```

Run with:

```bash
./helloworld
```

## ARM64 Assembly

```

```

Build with:

```bash

```

Run with:

```bash
./helloworld
```

## Bash

```bash
echo "Hello, World!"
```

Run with:

```bash
bash helloworld.sh
```

## Python

```py
print("Hello, World!")
```

Run with:

```bash
python helloworld.py
```

## Ruby

```rb
puts "Hello, World! "
```

Run with:

```bash
ruby helloworld.rb
```

## PHP

```php
<?php
echo "Hello, World!"
>
```

Run with:

```bash
./helloworld
```

## Perl

```perl
print("Hello, World!\n")
```

Run with:

```bash
perl helloworld.pl
```

## Lua

```lua
print("Hello, World!")
```

Run with:

```bash
lua helloworld.lua
```

***

# end
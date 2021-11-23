---
layout: page
title: "Why C# is the best programming language"
date: 2021-11-22 20:15:00 -0400
categories: blog
---

## C# is widely regarded as the best programming language.

It's incredibly versatile, widely supported, and actively being contributed to.

But why is it considered one of the best languages? Today, I give my take.

## Part 1: The history of C#

C# has its roots set in the early 2000s. You may think that C# is an extension of C++ or C, but you'd be wrong.

C# was originally created as an answer to Java. If you've coded in one language, you'll see that you can easily translate between the two.

When it was created in 2002, it was originally released as a language packaged with Visual Studio 2002, and as a part of the .NET framework. The early version was much different than today's C#.

Many versions of C# and the .NET framework later, as of November 2021, we have C# 10.0 and .NET 6.0.

## Part 2: Why C#?

So... Why C#? I'll list 3 main reasons.

### Ease of use

Though VB.NET was the first actual programming language I learned, C# is the first programming language I've learned that is actually widely used.

I, personally, found it very easy to learn and use. 

Simple `hello world` application:

```cs
using System;

class Program {
    static void Main() {
        Console.WriteLine("Hello World!");
    }
}
```

Yes, there are some languages that are a lot simpler than C#, e.g. Python.

Don't worry, we'll talk about that later.

### Compatibility

C# used to be pretty much exclusively Windows before .NET Core was released in 2016.

.NET core works a lot like Java.

.NET Framework 4.x relies on Windows APIs to accomplish its task, and thus can't be run on a Mac or Linux machine without the use of Wine.

.NET core allows .NET languages to be compiled to DLLs to that anyone with the Dotnet runtime (natively available on windows, mac, and linux) can run the program natively without the help of programs like Wine.

But what about Java itself?

Yes, Java does much of the same stuff as .NET Core, but to actually make a .JAR file, you need to have the actual class itself, the Manifest file, as well as a bunch of other stuff. With Dotnet, you can just navigate to the project directory and execute `dotnet run` to compile the program straight to an EXE or DLL, and execute it.

### Web Applications

Yes, C# even does server-side web applications!

ASP.NET allows you to build web apps with C#, much like Node.JS, Python, or Ruby, with a language used commonly in many other places.

### C# vs. Other Programming Languages

Now, I'm going to put C# head to head with the other top 10 programming languages (that aren't strictly web-based), using a simple "Hello World" program.

Once again, C#'s Hello World:

```cs
using System;

class Program {
    static void Main() {
        Console.WriteLine("Hello World!");
    }
}
```

Python:
```py
print("hello world")
```
Now, wait a minute! 6 lines of C# vs 1 line of Python? Python obviously takes the cake here!

Yes, Python's code is a *lot* simpler than that of C#, however, you must understand that python uses an interpreter rather than a compiler. What this means is that the program that executes python script is reading the code as is executes it, much like basic on an Apple II or a Commodore computer.

This can result in slower execution and much more resources being used to execute the program.

Node.JS (Note: Rather than print "hello world" to a console prompt, this displays the text "Hello World!" on a web server hosted at localhost:8080.):

```js
var http = require('http');

http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/html'});
  res.end('Hello World!');
}).listen(8080); 
```

Node.JS, like python, uses an interpreter, though node is more used for web applications, so it's not fair to make an apples-to-oranges comparison here.

C:

```c
#include <stdio.h>
int main() {
   printf("Hello, World!");
   return 0;
}
```

C, like C++, R, and C# is object oriented and compiled into an EXE that can be run natively on any Windows, Mac, or Linux Computer.

However, C# has features like Garbage Collectiom that automatically remove unused classes once they will no longer be used. In languages like C, C++, and R, it is up to the programmer to do this themselves.


Swift:
```swift
import foundation

print("Hello World!");
```

Swift is mainly a language specifically intended for Apple Devices only. Though it may run faster and be lighter than C#, it is severely limited in terms of compatibility.

## TL;DR, Why C#?

C# is easy to pick up for beginner programmers, excellent for server-side web apps, has great compatibility with other operating systems since the release of .NET Core, and has extra useful features like Garbage Collection which other languages like R, C, and C++ don't have.

{{site.blogpostfooter}}

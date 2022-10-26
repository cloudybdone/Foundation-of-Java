
# Foundation of Java Programming

### In this Article I would be discuss following topics:

* What is Java?
* What is Java used for? 
* Short History 
* Features
* Why You Should Learn Java?
* Compiled vs Interpreted Language
* Java Components (JDK,JRE,JVM,Java & JIT Compiler)
* How Java is Platform Independent?
* JVM Architecture

### What is Java?
 Java is a cross-platform object-oriented programming language that was released by Sun Microsystems in the year 1995. It is similar to C++, but with advanced and simplified features. This language is free to access and can run on all platforms.

 Java is: –

  1. **Concurrent** where you can execute many statements instead of sequentially executing it.
  2. **Class-based** and an **object-oriented** programming language.
  3. **Independent** programming language that follows the logic of **“Write once, Run anywhere”** i.e. the compiled code can run on all platforms which supports java.

### What is Java used for? 

It is highly popular and has dominated this field from early 2000’s till the present 2022.
    
Some of the applications are listed below:-

 * **Banking:** To deal with transaction management.
 * **Retail:** Billing applications that you see in a store/restaurant are completely written in Java.
 * **Information Technology:** Java is designed to solve implementation dependencies.
 * **Android:** Applications are either written in Java or use Java API.
 * **Financial services:** It is used in server-side applications.
 * **Stock market:** To write algorithms as to which company they should invest in.  
 * **Big Data:** Hadoop MapReduce framework is written using Java.
 * **Scientific and Research Community:** To deal with huge amount of data.

### Short History 

Java is a programming language developed by **James Gosling** with other team members named **Mike Sheridan** and **Patrick Naughton** also called as **Green Team** in **1995** for **Sun Microsystems** for digital devices such as set-top boxes, televisions etc. Now, let us explore the language in detail.

### Features

**Simple:** Java has made life easier by removing all the complexities such as pointers, operator overloading as you see in C++ or any other programming language.

**Portable:** This is platform independent which means that any application written on one platform can be easily ported to another platform.

**Object-oriented:** Everything is considered to be an “object” which possess some state, behavior and all the operations are performed using these objects. 

**Secured:** All the code is converted in **bytecode** after compilation, which is not readable by a human. and java does not use an explicit pointer and run the programs inside the sandbox to prevent any activities from untrusted sources. It enables to develop virus-free, tamper-free systems/applications.

**Dynamic:** It has the ability to adapt to an evolving environment which supports dynamic memory allocation due to which memory wastage is reduced and performance of the application is increased.

**Distributed:** This language provides a feature which helps to create distributed applications. Using Remote Method Invocation (RMI), a program can invoke a method of another program across a network and get the output. You can access files by calling the methods from any machine on the internet.

**Robust:** Java has a strong memory management system. It helps in eliminating error as it checks the code during compile and runtime.

**High Performance:** Java achieves high performance through the use of bytecode which can be easily translated into native machine code. With the use of **JIT (Just-In-Time) compilers**, it enables high performance.

**Multithreaded:** Java supports multiple threads of execution (a.k.a., lightweight processes), including a set of synchronization primitives. This makes programming with threads much easier.

### Why You Should Learn Java?

Here are the reasons that will elaborate on why to learn Java:-

  * **Java is Easy to Learn:** Java is quite easy to learn and can be understood in a short span of time as it has a syntax similar to English. You can also follow Java Tutorials. This will guide you on how to get started with Java and make yourself proficient in it

  * **Beginner Friendly and Competitive Edge:** The best part while you learn Java is its beginner-friendly nature. The syntax of Java matches a lot with its predecessors, C, C++, etc. Of course, Java has inherited its predecessors, but also, Java comes with some advanced features to help programmers in real-time.

    Unlike its predecessors, Java comes with advanced memory management tools. Runtime Environment takes care of memory allocation, reallocation, and deallocation automatically via an in-built software tool called the Garbage collector.

    The object-oriented programming nature of the language makes it more precise, readable, and the best in class when it comes to getting started with real-time projects, even at the beginner's stage.

* **Code Portability and Versatility:** Java follows a fundamental principle that worked well for Java to date. The "Write Once, and Run Anywhere" principle. Now, Java uses a software tool that comes along with the Java download file. It is called the Java Virtual Machine (JVM).

  The primary objective of JVM is to convert the code written in the user's language into machine level language (ByteCode), and then the interpreter will compile and execute the code. The same protocol is followed regardless of the type of the host operating system.

  Next, the language's object-oriented nature makes Java-capable bind the data members and data manipulating methods together. Data binding makes the data to be more secure. Not just security, Java is also capable of working with various resources and working over the network.

  Data binding and security features make Java a most versatile programming language.

  Followed by platform independence and the versatile nature of Java, we have the open-source library support of Java.

* **Java has an Abundant API:** Java has an abundant Application Programming Interface (API) that includes many Java classes, packages, interfaces, etc. This is useful for constructing applications without necessarily knowing their inside implementations. Java has mainly three types of API i.e. **Official Java core APIs**, **Optional official Java APIs**, and **Unofficial APIs**. These APIs overall are used for almost everything including networking, I/O, databases, media, XML parsing, speech synthesis, etc. 

* **Wide Range of Powerfull Development Tools:** There are many Integrated development environments (IDEs) in Java that provide various facilities for software development to programmers. Powerful Java IDEs such as **Eclipse**, **NetBeans**, **IntelliJ IDEA**, etc. play a big role in the success of Java. These IDEs provide many facilities such as debugging, syntax highlighting, code completion, language support, automated refactoring, etc. that make coding in Java easier and faster. Java has created a base for the Android operating system and opted around 90% of fortune 500 companies to develop a lot of back-end applications. Also, it plays a great role in Apache Hadoop data processing, Amazon Web Services, Windows Azure, etc. 

* **Java has Great Documentation Support:** The documentation support for Java is excellent using Javadoc which is the documentation generator for Java. It uses the Java source code to generate the API documentation in HTML format. So, Javadoc provides a great reference while coding in Java so that understanding the code is quite simple. 

* **Java has Multiple Open Source Libraries:** Open-source libraries have resources that can be copied, studied, changed, shared, etc. There are multiple open source libraries in Java such as **JHipster**, **Maven**, **Google Guava**, **Apache Commons**, etc. that can be used to make Java development easier, cheaper and faster. 

* **High Demand:** Java Developers are one of the high paid developers out here in the IT industry, and this is because of the widespread dependency on the Java Programming language.

###  Compiled vs Interpreted Language

Every program is a set of instructions, whether it’s to add two numbers or send a request over the internet. **Compilers** and **Interpreters** take human-readable code and convert it to computer-readable machine code.

In a compiled language, the target machine directly translates the program. In an interpreted language, the source code is not directly translated by the target machine. Instead, a different program, aka the interpreter, reads and executes the code.

**Compiled Languages:**

Compiled languages are converted directly into machine code that the processor can execute. As a result, they tend to be faster and more efficient to execute than interpreted languages. They also give the developer more control over hardware aspects, like memory management and CPU usage. Compiled languages need a “build” step – they need to be manually compiled first. You need to “rebuild” the program every time you need to make a change.

Examples of pure compiled languages are **C**, **C++**, **Java**, **Erlang**, **Haskell**, **Rust**, and **Go**.

**Interpreted Languages:**

Interpreters run through a program line by line and execute each command. Interpreted languages were once significantly slower than compiled languages. But, with the development of **just-in-time(JIT)** compilation, that gap is shrinking. 

Examples of common interpreted languages are **PHP**, **Ruby**, **Python**, **Perl** and **JavaScript**.

### Interpreter vs Compier: How is an Interpreter different than a compiler?

The table below will help you in understanding the differences between an Interpreter and a Compiler :-


| Interpreter | Compiler |
| :---:  | :---:  |
| Translates Program Line by Line | Translates entire program together  |
| Compile-time is Less but Execution is Slower  | Compile-time is More but Execution is Faster  |
| Will not generate Intermediate Object Code  | Generates Intermediate Object Code  |
| Program is Compiled until an Error is found  | Error is displayed at the end of Compilation  |
| **Python**, **PHP**, **Perl**, **Ruby** use Interpreter  |  **C**, **C++**, **Scala**, **Java** use Compilers  |

### Java Components (JDK,JRE,JVM,Java & JIT Compiler)

**Java Architecture** combines the process of compilation and interpretation. It explains the various processes involved whilst formulating a Java program. 

**What is Java Architecture?**

* In **Java**, there is a process of compilation and interpretation.
* The code written in **Java**, is converted into byte codes which is done by the **Java Compiler**.
* The byte codes, then are converted into machine code by the **JVM.**
* The Machine code is executed directly by the machine.

This diagram illustrates the internal working of a Java code, or precisely, Java Architecture!

![Java Architecture](https://github.com/cloudybdone/Foundation-of-Java/blob/main/javaArchitecture.png)





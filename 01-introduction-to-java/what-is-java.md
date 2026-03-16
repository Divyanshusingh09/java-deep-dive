# ☕ Basic Introduction to Java

> Java is a **high-level, object-oriented, class-based, platform-independent programming language** used to build secure, scalable, and reliable software.

---

## 📌 What is Java?

Java is a programming language as well as a platform.

**Java is a language**,as it provides syntax and rules to write programs.

**Java is a platform**, as it provides a complete environment to develop and run applications using:
- JDK
- JRE
- JVM
- Standard libraries

So Java is not just about writing code. It is a complete ecosystem.

---

## 🌍 Why Java Was Created

Before Java, software was usually tied to a specific operating system and hardware.

That means:

- a program written for one system often could not run on another
- developers had to write separate versions for different platforms
- portability was a big problem

Sun Microsystems wanted a language that could solve this problem.

Their goal was simple:

> **Write code once and run it on multiple systems without rewriting it.**

That idea became one of Java's strongest features:

## ✨ Write Once, Run Anywhere (WORA)

---

## 🕰 Evolution of Java

Java was originally developed by **James Gosling** and his team at **Sun Microsystems**.

### Early story
- Initially, Java was called **Oak**
- It was designed for **consumer electronic devices**
- Later, it was adapted for the internet era
- In 1995, it was officially released as **Java**

### Why the name changed from Oak
The name Oak was already taken, so the team renamed it Java.

---

## 📈 Major Versions of Java

| Version | Year | Major Highlights |
|--------|------|------------------|
| Java 1.0 | 1996 | First public release |
| Java 1.2 | 1998 | Collections Framework |
| Java 5 | 2004 | Generics, annotations, enhanced for-loop |
| Java 8 | 2014 | Lambda expressions, Stream API |
| Java 9 | 2017 | Module system |
| Java 11 | 2018 | LTS release |
| Java 17 | 2021 | LTS release, modern stable version |
| Java 21 | 2023 | Latest LTS with many modern improvements |

---

## 🚀 Key Features of Java

## 1. Simple
Java syntax is simpler than older languages like C++.

It removed many complex features such as:
- pointer arithmetic
- operator overloading in the C++ style
- manual memory management

---

## 2. Object-Oriented
Java follows OOP principles:

- Encapsulation
- Inheritance
- Polymorphism
- Abstraction

This helps in:
- modular design
- code reuse
- maintainability

---

## 3. Platform Independent
Java code is compiled into **bytecode**, not machine-specific binary.

That bytecode runs on JVM, which can exist on different operating systems.

So the same `.class` file can run on:
- Windows
- Linux
- macOS

provided a suitable JVM is installed.

---

## 4. Secure
Java was designed with security in mind.

It provides:
- bytecode verification
- class loader isolation
- runtime security checks
- no direct pointer manipulation

This reduces many low-level risks.

---

## 5. Robust
Java is robust because it has:
- strong type checking
- exception handling
- automatic garbage collection
- runtime checks

That means Java tries to prevent many common programming errors.

---

## 6. Multithreaded
Java has built-in support for multithreading.

This allows a program to perform multiple tasks concurrently.

Examples:
- downloading a file while updating UI
- processing requests in parallel on a server

---

## 7. Distributed
Java provides APIs to build distributed applications over networks.

This became especially important for:
- enterprise systems
- backend services
- web servers
- microservices

---

## 8. High Performance
Java is not as low-level as C/C++, but with **JIT compilation**, modern JVMs provide strong performance.

So Java can handle:
- enterprise applications
- large-scale backend systems
- high-throughput services

---

## 🧠 Is Java Compiled or Interpreted?

> Java is both compiled and interpreted.

### Why?
- Java source code (`.java`) is first **compiled** by `javac` (compiler)
- This produces **bytecode** (`.class`)
- JVM then **interprets** or **JIT-compiles** (Just In Time) bytecode into machine code

So Java uses a hybrid execution model.

---

## 🏗 Java in Real World

Java is used in many areas:

- Backend development
- Enterprise applications
- Banking systems
- Android development (historically via Java concepts)
- Distributed systems
- Web services
- Microservices
- Big data tools

Large companies have heavily used Java because it is:
- stable
- scalable
- maintainable
- supported by a huge ecosystem

---

## 📦 Java Is More Than a Language

Java includes:

```text
Java Language
Java Compiler
JVM
JRE
JDK
Standard Libraries
Tools

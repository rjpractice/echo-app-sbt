# echo-app-sbt

A minimal Scala 3 console application created using **sbt**, as part of the [DIBS](https://dibs.pages.dev/) course (Design and Implementation of Software Libraries).

This project serves as a starting point to explore the basics of project structure, build tooling, and compilation using `sbt`, the most widely used build tool in the Scala ecosystem.

> 🗣 Although the course materials are in Spanish, this repository and its code are written in English to make the project more accessible to a wider audience.

## 📚 About this Lesson

This project accompanies the following lesson:  
👉 [Creating a Basic Project with sbt](https://dibs.pages.dev/docs/build-systems/init/sbt/)

The goal of the lesson is to:

- Introduce `sbt` and how to install it.
- Generate a new Scala 3 project using the official Giter8 template.
- Understand the generated project structure.
- Write and run a simple program using the `@main` entry point annotation in Scala 3.

The project includes a single `Main.scala` file with a short line inspired by *Gyo*, a horror manga by Junji Ito:

```scala
@main def main(): Unit =
    println("The smell... it's coming from the sea.")
```

## 🚀 Running the App

Make sure you have [sbt](https://www.scala-sbt.org/) installed, then from the root of the project run:

```bash
sbt run
```

You should see output similar to:

```plaintext
[info] running 'main'
The smell... it's coming from the sea.
```

## 🛠️ Requirements

- Scala 3.x
- sbt 1.10+
- Java 17 or later (tested with Java 23)

## 📂 Project Structure

```
.
├── .gitignore
├── README.md
├── build.sbt
├── project/
│   └── build.properties
└── src/
    ├── main/
    │   └── scala/
    │       └── Main.scala
    └── test/
        └── scala/
            └── MySuite.scala
```

## 🎓 Part of the DIBS Course

This repository is part of the official examples used in the *Diseño e Implementación de Bibliotecas de Software* (DIBS) course.  
To explore more lessons and materials, visit [dibs.pages.dev](https://dibs.pages.dev/).

## study-references

Repo with somewhat curated content about programming languages and computer science in general;  
It will be constantly updated and improved.

---

## Index 
- [Computer Science in general](#computer-science-in-general)
  * [Zines](#zines)
- [Project Ideas](#project-ideas)
- [InfoSec](#infosec)
  * [Infosec in general](#infosec-in-general)
  * [Case studies](#case-studies)
  * [Vulnerabilities](#vulnerabilities)
  * [Specific topics](#specific-topics)
- [Forensics](#forensics)
  * [Data recovery](#data-recovery)
- [Tools related](#tools-related)
  * [Docker](#docker)
- [Language specific stuff](#language-specific-stuff)
  * [Go](#go)
  * [Java](#java)
    + [Other Java stuff](#other-java-stuff)
  * [Javascript](#javascript)
- [Coding Practices](#coding-practices)
  * [Good/Bad Practices](#good-bad-practices)
  * [TDD](#tdd)

---

## Computer Science in general
<div align="right"><b><a href="#index">↥ Index</a></b></div>

[The basics you won't learn in the basics](https://pmihaylov.com/category/the-basics-you-wont-learn-in-the-basics/) by Preslav Mihaylov
Basics about memory, how processors work, etc...
Must read for anyone curious about how stuff works in the lower levels.  

12 Articles in total (in the order they were posted):  
  * [Introduction to Computer Memory](https://pmihaylov.com/intro-to-computer-memory/)
  * [How does the processor work](https://pmihaylov.com/how-does-the-processor-work/)
  * [Introduction to binary numbers](https://pmihaylov.com/intro-binary-numbers/)
  * [Negative binary numbers](https://pmihaylov.com/negative-binary-numbers/)
  * [Floating point numbers](https://pmihaylov.com/floating-point-numbers/)
  * [How the binary nature of computers affects our data types](https://pmihaylov.com/how-does-binary-affect-data-types/)
  * [What you need to know about character sets and encoding](https://pmihaylov.com/character-sets-and-encoding/)
  * [Introduction to bitwise operations](https://pmihaylov.com/bitwise-operations/)
  * [What you don’t know about sorting algorithms](https://pmihaylov.com/sorting-algorithms/)
  * [Understanding Standard Input and Output](https://pmihaylov.com/standard-io/)
  * [Languages High and Low](https://pmihaylov.com/languages-high-and-low/)
  * [The build process of programming languages](https://pmihaylov.com/the-build-process-of-programming-languages/)

### Zines
<div align="right"><b><a href="#index">↥ Index</a></b></div>

[Wizard zines](https://wizardzines.com)
Zines about specific topics in computer science, networking, etc...
 * Some are free (see [Free posters](https://wizardzines.com/#posters)) but most are paid.

---

## Project Ideas
<div align="right"><b><a href="#index">↥ Index</a></b></div>

Out of ideas? Don't know where to start? Check out the links below.

[Javascript Projects for beginners](https://www.freecodecamp.org/news/javascript-projects-for-beginners/) - From FreeCodeCamp.org  
Beginner projects with HTML, CSS and vanilla Javascript/React/Typescript.

[app-ideas](https://github.com/florinpop17/app-ideas) - From florinpop17 @ Github  
Beginner, intermediate and advanced project ideas;
  * Shows a project description/user stories and general guidelines for the project;
  * You must implement everything yourself.
  * The most advanced projects are complete applications (frontend + backend).

[Back-end Challenges](https://github.com/CollabCodeTech/backend-challenges)
  * Repo with Back-end interview tests and challenges in different stacks/programming languages (mostly in Portuguese though)

[Front-end Challenges](https://github.com/felipefialho/frontend-challenges)
  * Repo with Front-end interview tests and challenges in different stacks/programming languages (mostly in Portuguese though)

---

## Infosec
<div align="right"><b><a href="#index">↥ Index</a></b></div>

### Infosec general
[tl;dr sec](https://tldrsec.com)
Short and quick posts about the newest stuff. Exploits, tools, etc
  * Has a good newsletter

### Case studies
[When you browse Instagram and find former Australian Prime Minister Tony Abbott's passport number](https://mango.pdf.zone/finding-former-australian-prime-minister-tony-abbotts-passport-number-on-instagram)
Case study about Open-source Intelligence and a security vunlnerability in an Airline website.

### Vulnerabilities
[SQL Injection Tutorial - What is SQL Injection and How to Prevent it](https://www.freecodecamp.org/news/what-is-sql-injection-how-to-prevent-it/)
Title self explanatory.

### Specific topics
[What is a Buffer Overflow attack - and how to stop it](https://www.freecodecamp.org/news/buffer-overflow-attacks/)
Technical explanation of a buffer overflow.

[filesignatures.net](https://filesignatures.net/index.php?page=all)
To find out filetypes by signature in the first bytes (usually 4 to 8 bytes)

---

## Forensics
<div align="right"><b><a href="#index">↥ Index</a></b></div>

### Data recovery

[Data Recovery basics](https://help.ubuntu.com/community/DataRecovery) @ help.ubuntu.com
Lists the most common tools and utilities used for data recovery

### Forensics Tools
[TestDisk and PhotoRec](https://www.cgsecurity.org/wiki/Main_Page)
CLI tools, made by [Christophe GRENIER](https://github.com/cgsecurity)
  * TestDisk allows to check integrity of drives and rebuild partitions
  * PhotoRec is for carving data (specially proprietary file formats) from disk images
    + Any code files (.java, .js, .h, etc) are extracted as well, but as internally they are just plaintext (no file headers), they probably won't have the correct extension.  

  * [Testcases for TestDisk and PhotoRec](https://www.cgsecurity.org/wiki/TestDisk_and_PhotoRec_in_various_digital_forensics_testcase)
    + [Testing images](http://dftt.sourceforge.net/)
    Download these images to practice your skills

---

## Tools related
<div align="right"><b><a href="#index">↥ Index</a></b></div>

### Docker
#### Docker Security

[Boas práticas de segurança usando o Docker](https://www.sidechannel.blog/boas-praticas-de-seguranca-usando-o-docker/index.html)
From Fran Lauriano

---

## Language specific stuff
### Go
<div align="right"><b><a href="#index">↥ Index</a></b></div>

[gRPC With Go Crash Course](https://pmihaylov.com/grpc-with-go-crash-course/) From Preslav Mihaylov @ pmihaylov.com

Articles:
  * [Introduction](https://pmihaylov.com/grpc-with-go-intro/)
  * [Service Schemas](https://pmihaylov.com/grpc-with-go-schemas/)
  * [Basic RPC Routines](https://pmihaylov.com/grpc-with-go-basic-rpcs/)
  * [Unidirectional Streams](https://pmihaylov.com/grpc-with-go-unidirectional-streams/)
  * [Bidirectional Streams](https://pmihaylov.com/grpc-crash-course-bidi-streams/)

---

### Java
<div align="right"><b><a href="#index">↥ Index</a></b></div>

Interesting short Linkedin posts (in Portuguese)  
From [Pedro Cavalero](https://allmylinks.com/pedro-cavalero) @ Linkedin

  * [A versões do Java](https://www.linkedin.com/posts/pedrocavalero_vamos-relembrar-as-vers%C3%B5es-do-java-em-activity-6779779296828391424-ayf8/)
  * [Funcionalidades do Java 5](https://www.linkedin.com/posts/pedrocavalero_nessa-semana-de-lan%C3%A7amento-do-java-16-vamos-activity-6780504142789021696-8qZc)
  * [Curiosidades do Java 8](https://www.linkedin.com/posts/pedrocavalero_java-java8-java11-activity-6781228912513978368-Vqbq)
  * [Novidades do Java 11](https://www.linkedin.com/posts/pedrocavalero_java-java8-java11-activity-6781953446372229120-rjgb)
  * [O que são classes e objetos?](https://www.linkedin.com/posts/pedrocavalero_java-java8-java11-activity-6782316164790943744-oTiJ)
  * [O que é Spring Boot?](https://www.linkedin.com/posts/pedrocavalero_springboot-java-springframework-activity-6776905016545443841-cmso)
  * [O que é Spring Boot?](https://www.linkedin.com/posts/pedrocavalero_springboot-java-springframework-activity-6776904954658488320-xhws)

#### Other Java stuff
<div align="right"><b><a href="#index">↥ Index</a></b></div>

[Springboot e Docker](https://carloshenriquereis-17318.medium.com/spring-boot-e-docker-2cafaa0f3e1a)
Deploy of a Spring Boot application using Tesseract OCR to return the text in a given image.

[String Performance Hints](https://www.baeldung.com/java-string-performance)
Analysing the performance of string methods.

---

### Javascript
<div align="right"><b><a href="#index">↥ Index</a></b></div>

#### Linting

[JavaScript Standard Style: melhores práticas em JS](https://blog.geekhunter.com.br/javascript-standard-style)
[eslint-config-standard-with-typescript](https://github.com/standard/eslint-config-standard-with-typescript)
[ESLint with Typescript](https://blog.geekhunter.com.br/eslint-typescript-tutorial/)

---

## Coding Practices
<div align="right"><b><a href="#index">↥ Index</a></b></div>

### Good/Bad practices

[HTMHell - Markup from hell](https://www.htmhell.dev/)
Examples of bad HTML explained and how to fix them.

[CSS Hell - Collection of common CSS mistakes, and how to fix them](https://csshell.dev/)
Examples of bad CSS code explained and with corrections. (In *Portuguese*)

### TDD

[Test Smell Examples](https://testsmells.org/pages/testsmellexamples.html)
Examples of badly written tests using Test/Behavior Driven Development (using Java)
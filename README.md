Repo with somewhat curated content about programming languages and computer science in general;  
It will be constantly updated and improved.

---
## Index
- [Index](#index)
- [Computer Science in general](#computer-science-in-general)
  - [Zines](#zines)
  - [Tools](#tools)
  
- [Networking](#networking)
  - [Protocols](#protocols)
  
- [Project Ideas](#project-ideas)

- [Infosec](#infosec)
  - [Infosec - General](#infosec---general)
  - [Infosec - Case studies](#infosec---case-studies)
  - [Infosec - Other](#infosec---other)
  - [Infosec - Vulnerabilities](#infosec---vulnerabilities)
  - [Infosec - Tools](#infosec---tools)
  
- [Forensics](#forensics)
  - [Forensics - Data recovery](#forensics---data-recovery)
  - [Forensics - Tools](#forensics---tools)
  
- [Tools related](#tools-related)
  - [Bash](#bash)
  - [Docker](#docker)
    - [Docker Security](#docker-security)
  - [Git](#git)
  - [Kubernetes](#kubernetes)
  - [Nginx](#nginx)
  
- [Application examples](#application-examples)
  - [NodeJS](#nodejs)
  - [Serverless](#serverless)
  
- [Language specific stuff](#language-specific-stuff)
  - [Golang](#golang)
  - [Java](#java)
    - [Other Java stuff](#other-java-stuff)
  - [Javascript](#javascript)
    - [JS - Arrays](#js---arrays)
    - [JS - Linting](#js---linting)
    - [JS - Build tools](#js---build-tools)
  - [NodeJS](#nodejs)
  
- [Coding Practices](#coding-practices)
  - [Good/Bad practices](#goodbad-practices)
  - [TDD](#tdd)
  - [Logging](#logging)
  
- [Algorithms](#algorithms)

- [Newsletters](#newsletters)
  - [English](#english)
  - [Portuguese](#portuguese)
  
---

## Computer Science in general
<div align="right"><b><a href="#index">↥ Index</a></b></div>

[The basics you won't learn in the basics](https://pmihaylov.com/category/the-basics-you-wont-learn-in-the-basics/) - by Preslav Mihaylov

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

### Tools
<div align="right"><b><a href="#index">↥ Index</a></b></div>

[IEEE-754 Floating Point Converter](https://www.h-schmidt.net/FloatConverter/IEEE754.html)
* Good to understand how floats are actually stored in memory and understand why `0.1 + 0.2 != 0.3` is `false` in languages such as Python and Javascript.

[regexr.com](https://regexr.com/)
* Good Regex tool for Javascript/PHP, real-time feedback.

---

## Networking
<div align="right"><b><a href="#index">↥ Index</a></b></div>

### Protocols

[TCP vs UDP – Which Protocol is Faster?](https://www.freecodecamp.org/news/tcp-vs-udp-which-is-faster/)

[What is the TCP/IP Model? Layers and Protocols Explained](https://www.freecodecamp.org/news/what-is-tcp-ip-layers-and-protocols-explained/)

---

## Project Ideas
<div align="right"><b><a href="#index">↥ Index</a></b></div>

Out of ideas? Don't know where to start? Check out the links below.

[Javascript Projects for beginners](https://www.freecodecamp.org/news/javascript-projects-for-beginners/) - From FreeCodeCamp.org  
* Beginner projects with HTML, CSS and vanilla Javascript/React/Typescript.

[app-ideas](https://github.com/florinpop17/app-ideas) - From florinpop17 @ Github  
* Beginner, intermediate and advanced project ideas;
  + Shows a project description/user stories and general guidelines for the project;
  + You must implement everything yourself.
  + The most advanced projects are complete applications (frontend + backend).

[dev-practice](https://github.com/alinebastos/dev-practice)
* Challenges and app/games ideas, separated by programming language.

[desafios-de-ti](https://github.com/wbraganca/desafios-de-ti)
* Back-end/Front-end interviews/challenges (in Portuguese).

[Back-end Challenges](https://github.com/CollabCodeTech/backend-challenges)
* Repo with Back-end interview tests and challenges in different stacks/programming languages (mostly in Portuguese though)

[Front-end Challenges](https://github.com/felipefialho/frontend-challenges)
* Repo with Front-end interview tests and challenges in different stacks/programming languages (mostly in Portuguese though)

[Fullstack Challenges](https://github.com/alinebastos/fullstack-challenges)
* Repo with fullstack interview tests and challanges (mostly in Portuguese)

---

## Infosec
<div align="right"><b><a href="#index">↥ Index</a></b></div>

### Infosec - General
[tl;dr sec](https://tldrsec.com)
* Short and quick posts about the newest stuff. Exploits, tools, etc
  + Has a good newsletter

### Infosec - Case studies
[When you browse Instagram and find former Australian Prime Minister Tony Abbott's passport number](https://mango.pdf.zone/finding-former-australian-prime-minister-tony-abbotts-passport-number-on-instagram)
* Case study about Open-source Intelligence and a security vunlnerability in an Airline website.

### Infosec - Other
[What is a Buffer Overflow attack - and how to stop it](https://www.freecodecamp.org/news/buffer-overflow-attacks/)
* Technical explanation of a buffer overflow.

[filesignatures.net](https://filesignatures.net/index.php?page=all)
* To find out filetypes by signature in the first bytes (usually 4 to 8 bytes)

### Infosec - Vulnerabilities
[SQL Injection Tutorial - What is SQL Injection and How to Prevent it](https://www.freecodecamp.org/news/what-is-sql-injection-how-to-prevent-it/)
* SQL Injection basics

[Cross Site Request Forgery – What is a CSRF Attack and How to Prevent It](https://www.freecodecamp.org/news/what-is-cross-site-request-forgery/)
* CSRF basics

### Infosec - Tools
[osquery](osquery.io/)
* "Query your devices like a database"
  + "Osquery uses basic SQL commands to leverage a relational data-model to describe a device."
  + For MacOS, Windows and Linux

---

## Forensics
<div align="right"><b><a href="#index">↥ Index</a></b></div>

### Forensics - Data recovery

[Data Recovery basics](https://help.ubuntu.com/community/DataRecovery) @ help.ubuntu.com
* Lists the most common tools and utilities used for data recovery

### Forensics - Tools
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

### Bash

[Monitorando processos com o htop](https://www.treinaweb.com.br/blog/monitorando-processos-com-o-htop)
* About **htop**, and it's output explained (in Portuguese)

### Docker
#### Docker Security

[Boas práticas de segurança usando o Docker](https://www.sidechannel.blog/boas-praticas-de-seguranca-usando-o-docker/index.html) - From Fran Lauriano
* Good security practices with Docker

### Git
[Boost Your Programming Skills by Reading Git's Code](https://www.freecodecamp.org/news/boost-programming-skills-read-git-code/) - From FreeCodeCamp.org
* About Git's first commit back in 2005, some C basics and explanations about Git's internals.
  * See also [baby-git](https://bitbucket.org/jacobstopak/baby-git) a commented version of the first commit.

[How Git Branches Work](https://www.freecodecamp.org/news/how-git-branches-work/) - From FreeCodeCamp.org
* The internals of Git branches (33 min video + full transcript)

### Kubernetes
[The Kubernetes Handbook](https://www.freecodecamp.org/news/the-kubernetes-handbook/) - From FreeCodeCamp.org
* Kubernetes handbook, good for using as reference.

### Nginx
[The NGINX Handbook](https://www.freecodecamp.org/news/the-nginx-handbook/) - From FreeCodeCamp.org
* Lenghty nginx guide

---

## Application examples
<div align="right"><b><a href="#index">↥ Index</a></b></div>

### NodeJS
[Serverless framework NodeJS examples](https://www.npmjs.com/package/serverless#services)
* Small application examples, useful for Serverless Framework and NodeJS.

### Serverless
[serverless/examples](https://github.com/serverless/examples) @ GitHub
* Serverless framework application examples in various languages (NodeJS, Golang, Python, Ruby, etc)

---

## Language specific stuff
<div align="right"><b><a href="#index">↥ Index</a></b></div>

### Golang

[Aprenda Go](https://www.youtube.com/playlist?list=PLCKpcjBB_VlBsxJ9IseNxFllf-UFEXOdg)
* Youtube playlist with Golang tutorials (in Portuguese)

[Run Go](https://medium.com/rungo)
* A Go-to guide for learning the Go programming language


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
* Deploy of a Spring Boot application using Tesseract OCR to return the text in a given image.

[String Performance Hints](https://www.baeldung.com/java-string-performance)
* Analysing the performance of string methods.

---

### Javascript
<div align="right"><b><a href="#index">↥ Index</a></b></div>

#### JS - Arrays

[The JavaScript Array Handbook – JS Array Methods Explained with Examples](https://www.freecodecamp.org/news/the-javascript-array-handbook/)

#### JS - Linting

[JavaScript Standard Style: melhores práticas em JS](https://blog.geekhunter.com.br/javascript-standard-style)
[eslint-config-standard-with-typescript](https://github.com/standard/eslint-config-standard-with-typescript)
[ESLint with Typescript](https://blog.geekhunter.com.br/eslint-typescript-tutorial/)

#### JS - Build tools

[Comparing the New Generation of Build Tools](https://css-tricks.com/comparing-the-new-generation-of-build-tools/)

### NodeJS
<div align="right"><b><a href="#index">↥ Index</a></b></div>

[JavaScript brief history and ECMAScript(ES6,ES7,ES8,ES9) features](https://madasamy.medium.com/javascript-brief-history-and-ecmascript-es6-es7-es8-features-673973394df4)

---

## Coding Practices
<div align="right"><b><a href="#index">↥ Index</a></b></div>

### Good/Bad practices

[HTMHell - Markup from hell](https://www.htmhell.dev/)
* Examples of bad HTML explained and how to fix them.

[CSS Hell - Collection of common CSS mistakes, and how to fix them](https://csshell.dev/)
* Examples of bad CSS code explained and with corrections. (In *Portuguese*)

[Ternary operator in Go](https://nilisnotnull.blogspot.com/2013/11/ternary-operator-in-go.html)
* Ugly implementation of a ternary using map (please don't do that)

### TDD

[Test Smell Examples](https://testsmells.org/pages/testsmellexamples.html)
* Examples of badly written tests using Test/Behavior Driven Development (using Java)

### Logging

[To Log, or Not to Log — An Alternative Strategy to Make Loggers Your Friends](https://www.freecodecamp.org/news/how-to-use-logs-effectively-in-your-code/)

[The problem with logging](https://blog.codinghorror.com/the-problem-with-logging/)

[Do not log](https://sobolevn.me/2020/03/do-not-log)

---

## Algorithms

[What is binary search](https://www.freecodecamp.org/news/what-is-binary-search/) - From FreeCodeCamp.org
* About binary search, and an implementation in C++ (in a 1:20 hour video)

## Newsletters

### English
[SANS.org](https://www.sans.org/newsletters/)
* Infosec newslettrs
[tl;dr sec](https://tldrsec.com)
* Short and quick posts about the newest stuff. Exploits, tools, etc
  * Has a good newsletter
[Bug Bounty Explained newsletter](https://mailing.bugbountyexplained.com/news1)
* In-depth explanations about bugs reported in bug bounty programs

### Portuguese
[Newsletter Luiz Tools](https://www.luiztools.com.br/)
* JS, NodeJS, Typescript, etc

---
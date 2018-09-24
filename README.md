# The Art Of Domain-Specific Languages: Let's Hack Our Own Languages!

by Jean-Marc Jézéquel and Mathieu Acher

The Science of Software faces new challenges with the advent of modern software-intensive systems such as complex critical embedded systems, cyber-physical systems and Internet of things. Application domains range from robotics, transportation systems, defense to home automation, smart cities, and energy management, among others. Software is more and more pervasive, integrated into large and distributed systems, and dynamically adaptable in response to a complex and open environment. As a major consequence, the engineering of such systems involves multiple stakeholders, each with some form of domain-specific modeling.
Model-Driven Engineering (MDE) aims at reducing the accidental complexity associated with developing complex software-intensive systems through the use of modeling techniques that support separation of concerns and automated generation of system artifacts from models. Separation of concerns is founded on the exploitation of different domain-specific modeling languages (DSLs), each providing constructs based on abstractions that are specific to a concern of a system. As such, DSLs are “the heart and soul” of MDE, and have major consequences on modern development processes.
The integration of domain-specific concepts and best practices development experience into DSLs can significantly improve software and systems engineers productivity and system quality. For such a purpose, the development of DSLs has been recently recognized as a significant software engineering task itself. Indeed, the development of DSLs is a challenging task which requires specialized knowledge. This recently resulted in the emergence of Software Language Engineering (SLE), defined as the application of systematic, disciplined, and measurable approaches to the development, use, deployment, and maintenance of software languages.
This course provides an end-to-end coverage of the engineering of DSLs to turn domain knowledge into tools. It introduces the foundations of MDE and SLE, with a specific focus on the use of modeling techniques for designing and implementing DSLs. It also provides various illustrations through the definition of different kinds of DSLs, their instrumentation with tools such as editors, simulators and generators, the integration of multiple DSLs to achieve a system view, and the validation of both models and tools. Finally the course provides the foundations for engineering a family of related DSLs, for modeling and managing variability, and for synthesising billions of variants out of textual or graphical specifications.

A project will be realized and will consist in "hacking" a domain-specific language (from the syntax to its execution) 

This course is part of The Research in Computer Science (SIF) master: http://master.irisa.fr/

### prerequisites
Basis of the Theory of Languages, Compilation, Object-Oriented Design, Typing
https://www.irisa.fr/lande/ridoux/ENS/COMP/compilation.pdf http://people.irisa.fr/Jean-Marc.Jezequel/enseignement/PolyUML/poly.pdf

Knowledge in programming languages (for example: Java, Scala, Python, Ocaml, JavaScript) 

## Objectives 

The course starts with an introduction to MDE and SLE, and then moves into a deeper discussion of how to express the knowledge of particular domains into tool supported DSLs. The second part lets students investigate the applications of MDE and SLE to different types of software systems, from different starting points (language, business knowledge, standard, etc.) and for different software engineering activities such as Requirement Engineering, Variability Management, Analysis, Design, Implementation, and Validation & Verification. 

Syllabus:
 * Introduction to DSLs, Model-Driven Engineering and Software Language Engineering (4h, JMJ, 18/9 & 20/9)
 ** slides: http://people.irisa.fr/Jean-Marc.Jezequel/enseignement/SIFDSL/Slides/IntroDSL.pdf 
 * Software Languages: from Fluent APIs, Internal DSLs, External DSLs to GPLs (2h, MA, 25/9)
   * including **project presentation**
   * slides: DSL.pdf 
 * Language workbenches: the Case of Xtext (2h, MA, 27/9)
 * Program & Model Transformations: the Case of Xtend (2h, MA, 4/10)
 * Introduction to Variability Modeling: software product lines and feature models (2h, MA, 9/10)
 * Automated reasoning (e.g., with solvers) and synthesis of variants (2h, MA, 11/10) 
 * Cost-effective strategies for verifying billions of variants (2h, MA, 16/10)
 * Machine learning and variability modeling (2h, MA, 18/10)
 * Families of DSLs: Safely Reusing Tools accross DSLs
 * DSLs for Model Based Testing, Integration of formal methods 


### What you will master	

Design and implement families of DSL and their tooling support, generative approaches with early early V & V, application to variability management for SPL

## Evaluation	
+ project (hack a DSL) with several intermediate deliverables (50%): a DSL for SAT solver variants https://docs.google.com/document/d/1v1YUDhcCjx42-amBqXqNzrI5LF9HfjXxku7kvG9zMoE/edit?usp=sharing
+ Written exam (2h, 50%) 

## Project 

(more to come)

## References	

"Engineering Modeling Languages: Turning Domain Knowledge into Tools" B Combemale, R France, JM Jézéquel, B Rumpe, J Steel, D Vojtisek, CRC Press

Feature-Oriented Software Product Lines: Concepts and Implementation
Apel, S., Batory, D., Kästner, C., Saake, G.

https://teaching.variability.io

## Key notions	

Principle of Separation of Concerns, Liskov's Substitution Principle, Theory and Practice of Hacking your own Languages, Large Scale Variability: 

Why is it crucial? 
Because complex software intensive systems : avionics, smart-* (cities,building,grid,farming) and software are eating the world

## Keywords	
DSL, MDE, SLE, SPL, Variability Management, Generative programming, early V&V, Separation of Concerns


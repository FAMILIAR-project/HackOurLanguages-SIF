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

You can find below the schedule and organization of the course, including:

* pointers to slides and material of the course
* milestones of the running project and intermediate deadlines 
* the dates of the courses and the instructors (JMJ means Jean-Marc Jezequel, MA means Mathieu Acher)

## Agenda

 * Introduction to MDE, SLE, DSL, metamodel and abstract syntax (JMJ, 12 september)
    * slides: http://people.irisa.fr/Jean-Marc.Jezequel/enseignement/SIFDSL/Slides/IntroDSL.pdf 
    * presentation of the running project
      * Slides `project.pdf`
      
 * Preliminary homework on the project (15 September)
    * Design the meta-model for your DSL
    * prepare presentation of the result for Sept. 22

 * Interpretation, Compilation, model transformation, Logo example (JMJ, 19 september)
    * slides: http://people.irisa.fr/Jean-Marc.Jezequel/enseignement/SIFDSL/Slides/IntroDSL.pdf
   
 * Language workbenches (MA, 22 september)
   * presentation of your meta-models + discussion
   * Course: Concrete syntax with Xtext
   * slides: `DSLXtext.pdf`

 * Home work (26 september)
    * design your concrete syntax of your DSL with Xtext 
    * prepare presentation of the result for Oct. 3
 
 * Program & Model Transformations: the Case of Xtend (MA, 29 september + 6 october)
   * slides: `ModelManagement.pdf`
   * intermediate control of the running project

* Families of DSLs: Safely Reusing Tools accross DSLs (JMJ, 3 October)
     * Slides `DSL-engineering.pdf`


     
* Home work (10 october)  
   * parsing, pretty printing, and first interpreter or compiler
   * prepare presentation of the result for Oct. 13 
     
* Automated assessement of compilers' variants and benchmarks (MA, 13 october)
   * slides: `AutomatedTesting.pdf`
   * intermediate control of the running project 

* Advanced model transformation and the expression problem (MA, 17 october)
   * example: https://github.com/arnobl/DSL-demo 
   * double dispatch: https://www.eclipse.org/xtend/documentation/202_xtend_classes_members.html#polymorphic-dispatch
   * slides: `ModelManagement.pdf` and slides of "Who is afraid of Object Algebras?" by Tijs Van Der Storm https://speakerdeck.com/joyofcoding/whos-afraid-of-object-algebras-tijs-van-der-storm 
   * we give a set of three papers on the expression problem that we will use in the final exam:
     - B. C. d. S. Oliveira and W. R. Cook, “Extensibility for the masses -
practical extensibility with object algebras,” in Proceedings of the 26th
European Conference on Object-Oriented Programming (ECOOP’12), 2012, pp. 2–27.
     - J. Jézéquel, B. Combemale, O. Barais, M. Monperrus, and F. Fouquet,
“Mashup of metalanguages and its implementation in the kermeta language
workbench,” Software and Systems Modeling, vol. 14, no. 2, pp. 905–920, 2015.
     - Bezanson, Jeff; Edelman, Alan; Karpinski, Stefan; Shah, Viral B. (7 February 2017). "Julia: A fresh approach to numerical computing". SIAM Review. 59 (1): 65–98. https://arxiv.org/abs/1411.1607 (especially Section 4)
     


  
* Home work (20 october)
     - milestone: testing your DSL, finding functional and non-functional bugs in your compilers/interpreters or in... existing libraries/tools

* Final exam (1 hour + 1 hour, MA, 7 november)
  * intermediate control of the running project: finding functional and non-functional bugs in a compiler 
  * exam on the expression problem
  * Introduction to Variability Modeling: software product lines and feature models (MA, 7 november) 
   * slides: `VariabilityAcherM-EJCP21-final.pdf`
   * https://github.com/diverse-project/varylatex

* Delivery of the projet (25 november)
 * [https://docs.google.com/document/d/10_wMFg5rODdOra9WQz8rC1vtyOwl6rvZcOEdWzspA0o/edit?usp=sharing](https://docs.google.com/document/d/1_ZvcWVgu10gKLBTBlYj14k0OX9jA0Nllme2buSsFA7w/edit?usp=sharing)

### What you will master	

Design and implement families of DSL and their tooling support, generative approaches with early early V & V, application to variability management for SPL

## Evaluation	
+ project (hack a DSL) with several intermediate deliverables (50%): a morphic DSL for CSV/JSON/machine learning 
+ [https://docs.google.com/document/d/10_wMFg5rODdOra9WQz8rC1vtyOwl6rvZcOEdWzspA0o/edit?usp=sharing](https://docs.google.com/document/d/1_ZvcWVgu10gKLBTBlYj14k0OX9jA0Nllme2buSsFA7w/edit?usp=sharing) 
+ Written exam (1h, 50%) 

## References	

"Engineering Modeling Languages: Turning Domain Knowledge into Tools" B Combemale, R France, JM Jézéquel, B Rumpe, J Steel, D Vojtisek, CRC Press

Feature-Oriented Software Product Lines: Concepts and Implementation
Apel, S., Batory, D., Kästner, C., Saake, G.

https://teaching.variability.io

Short video explaining MDE and DSL with the mineSeeper game example: https://www.youtube.com/watch?v=3aoLV5i1feo

## Key notions	

Principle of Separation of Concerns, Liskov's Substitution Principle, Theory and Practice of Hacking your own Languages, Large Scale Variability 

Why is it crucial? 
Because complex software intensive systems : avionics, smart-* (cities,building,grid,farming) and software are eating the world

## Keywords	
DSL, MDE, SLE, SPL, Variability Management, Generative programming, early V&V, Separation of Concerns


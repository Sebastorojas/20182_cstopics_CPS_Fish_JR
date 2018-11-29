# CPS_Fish_JR FINAL PROJECT OF INTRODUCTION TO ARTIFICAL INTELIGENCE

UNIVERSIDAD SANTO TOMAS
BY JUAN SEBASTIAN ROJAS AGUILAR

PROBLEM:
In the fish company JR there is a maintenance area in charge of keeping all the machines in proper operation. To do this, the maintenance of each machine must be planned. However, there are an problem in this process. The problem is that it is not possible for the maintenance area to know which machines require a stop or require a repair at the time it is necessary
To solve this, will have an intern in each area, where he will be in charge of performing preventive maintenance to the machines, update the resume and repairs of the same and finally generate reports to supervisors of the maintenance area in case there is a machine that requires repair. This is also a way for practitioners in their student form to understand the whole plant process and not stay in one place.

THEORETICAL FOUNDATIONS 
Constraint Satisfaction Problems

They are problems which have a set of specific variables within a process, in this process specific restrictions must be met, it begins to study in the year 1970 and it was advancing as an important topic in the investigation or logistics of operations and intelligence artificial. They are based on the combinatorial search for a solution that satisfies all the restrictions that the process variables have. Some great examples of the algorithms of satisfaction of restrictions more known by its acronym in English CPS would be:

- Problem of the eight queens 
- Theorem of the four colors or better known as map coloring
 - Answer set programming

Just to name some of the many problems that can be solved or all the applications that can have, these problems can be quite complicated or very simple. Since they can provide a solution that complies with all the restrictions, they can also return a response stating that the organization of the entries cannot meet all the restrictions. Some of the main applications of the CPS are the allocation of resources and the approach of organizational solutions.

For a technical definition of a CPS problem one should speak of 3 parts normally expressed as (X, D, C) which have the following meaning
X Are all the variables of the system, these variables are the basis of everything, there are problems which will have dynamic variables entered by a user or acquired from abroad or variables already established in the program
DSince the variables must be grouped, initialized or organized in such a way that the restrictions are met, a list of possible missing states must be kept for each variable, called the domain, as one of its definitions says, domain is where it can exist. this represents the values that the variable can still take.
These domains can be infinite or finite, finite domains are used for organization problems.
C These are the restrictions, they can be of several types such as unitary, binary or higher order. For organizational problems, unitary and binary restrictions are normally used, which can be defined as:

- Unitary restrictions only affect one variable, these are destined to assign a value to that variable, for example

Variable: Sky
Restriction: Sky = Blue
The restriction in this case says that the sky must be blue, and it cannot be of another color

- Binary restrictions affect more than two variables, such as:

Variables = Juan's workplace, Carlos's workplace.
Restriction: Juan's workplace = Carlos's place of work
The restriction says that both must be in the same place of work because there is already a working relationship between them.

To solve a problem cps of must consider 2 things, the first is called arc consistency which means to eliminate the possible values of the domains of each variable each time you fence assigning a value. For example:

Variables: A, B and C

Restriction: A = B and C different than A
Domains:
A = 1,2,3
B = 1,2,3
C = 1,2,3

Interaction 1:

A = 2

Domains applying arc consistency

A = 2
B = 2
C = 1.3


The other thing to keep in mind is to follow the backtrack-search strategy which says that in each interaction a value must be assigned to a variable, this form can be in order or randomly. After the assignment, you must verify all the restrictions that this assignment may have, if the case is not met, the arc consistency can be performed, otherwise it will not reduce domains and another assignment will be chosen for the variable.

FLOW DIAGRAM   

Please go to the image Flow diagram

TECHNICAL SPECIFICATIONS

To apply the CPS to the problem, the following considerations will be considered.

- The domains will be finite.
- The restrictions will be binary.

Variables:

The variables can be entered through an .xml file which can be edited by the supervisor of the maintenance area. He can choose between 7 names, which are:

•	Carolina
•	Sebastian
•	Gonzales
•	Juana
•	Andrew
•	Santiago
•	Antonio

Restrictions:

Please see the Constrains image.

Example of operation:

1. Enter names - see image Names_Entry_EX1
2. Iterations until you get an answer  See document Iterations_EX1
3. Scheduled graph with solution  See image Schedule_EX1


Youtube link:


DEPENDENCIES AND INSTRUCTIONS TO RUN THE PROJECT
Please go to the file call instrucciones.txt

RESOURCES

-	http://hrudnick.sitios.ing.uc.cl/paperspdf/Gil.pdf 
-	https://scielo.conicyt.cl/scielo.php?pid=S0718-221X2001000100006&script=sci_arttext 
-	http://repositorio.ufpso.edu.co:8080/dspaceufpso/bitstream/123456789/1609/3/30122.pdf 
-	https://cstopics.github.io/cstopics/artificial-intelligence/CSP/csp 
-	Kolaitis, Phokion G.; Vardi, Moshe Y. (2000). «Conjunctive-Query Containment and Constraint Satisfaction». Journal of Computer and System Sciences 61 

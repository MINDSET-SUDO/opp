# objected oriented  analysis and design(cmt 310)

## lecture 1
cat 1 10th october 2023
  
phases of system projects  include
planning ,analysis ,design and implementation

unified modelling language(uml) accelerated the change to system analysis and design

**system analyst** analyses the business situation identify opportunity for improvement and designs the system.
challenges the way the current organization works

**objective for a system analyst**
to create value for the organisation hence increasing profits 

### The system development life cycle (SDLC)
Similar to the four fundamental phases i.e planning,analysis,design and implentation 

STEPS of SDLC
--
1.**planning**

fundamental process of understanding why a system should be build
 
 step one: of planning is identying system bussines value


 *system request* presents a brief summmary of business needs and explains how the system will increase business value

  step two: project management 

 creation of work plan staff the projects and techniques that will be used

 2.**Analysis**

  answers question of will use the system,what the system will do and when it will be used

  step one:Analysis

  step two:requirements gathering done through interviews
  
  step three:system proposal development 
  analysis system concept and models are combined into a document called **system proposal** 
  
  it describes the business requirements  the new system should meet

  3.**Design**

  decides on how the new system will operate in terms of hardware ,software requirement and type of network infrastructure;user interface forms and reports and specific programs ,databases and files that can be needed

  The design has four steps

  step one :design strategy

  step two:development of basic architecture design 
  describes hardware software and network infrastructure 

  step three:
  
  `data base and file specificaton are developed

  step four:
  
  program design defines the programs should be written and function of these programs(**system specification**)

4. **IMPLEMENTATION**

final phase,gets most attention longest and most expensive 

step one :system construction

system is build and tested to  ensure it performs as designed 

step two: system installation 
old system is turned off and the new one is included ik vn the system 

most important aspects is to train the users to the new system and help manage the new system


step three:analyst team establishes a support plan 
includes a formal and non formal review of the system 

#### SYSTEM DEVELOPMENT METHODOLOGIES
A methodology is a formalized apporach to implenting the SDLC

*categorizing the methodology*
-

**process centered methodology** emphasizes on the process models 

**data centered methodologies** emphasizes on data models as core of system concept

**object oriented methodologies** attempts to balance the focus  on both process and data and incorporating them to one model

*classes of system methodologies*
-


1.structured design

first category adopted in 1980's

adopts a step by step approach 
    example is the **1a.waterfall development**

    analysts and users proceed in sequence from one phase to the next

*advantages*

 1.identifies system requirements before programming begins

2.minimizes changes to the requirements

**1b. parallel development**

attempts to address the problem of long delays between analysis phase and delivery 

primary advantage is to reduce the time to deliver the system 

**2.rapid application development(R.A.D)**

attempt to address the weakness of structured methodology
recommends analysts to use special techniques and computer tools to speed up the analysis ,design and implementation  such as computer aided software

*2a. phased development*

breaks the overall system into a series of versions that are developed sequential

disadvantage 
users work with systems that are intentionally incomplete

*2b prototyping*

Performs the phases(analysis  design and implentation  )concurrently and all the three phases are repeated in a cycle until the system is completed 

first prototype is shown to the group for commments and approval 

*adavantage*
users can interact with system 

*disadanatage*faced paced systems undergoes many changes 

**2c throw away prototyping**
done at different points in the SDLC
have a relatively thorough analysis phase used to gather information 

design prototype is not working well helps users understand challenges facing the system(display)

design prototype are thrown away 

more stable and reliable systems 

**3.Agile methodologies**

focus is on the developers

based on 12 principles ;they include:

1.software is delivered early satisfying the customer

2.changing requirements are made

3.working software is delivered to the customer

4.customers and developers work together to face the challenges facing the system

5.motivated individuals provide solutions 

6.face to face communication within development time 

7.primary measure of the progress

8.customers and developers work at a pace that is timed 

9.simplicity 

10.technical excellence 

12.reflection from the development times to improve the end product

*critics to agile methodology*

1.business premises

2.if not carefully managed by definition its not 

3.large mission critical systems solutions 

**based on agile**

scrum and extreme programming 

*1a.extreme programming* founded on 4 core values 

comments on various systems of the code

recommended for small groups of developers

large systems build with extreme programming become hard to maintain

can not handle mission  critical business enterprises

*b.scrum programming*

as soon software development  starts to develop chaos break out and planning fails 

iteration takes about 31 working days 

most chaotic

non progress
 
 *practice*

teams organize themselves 

once iteration has began no addition of any other inputs

scrum meeting takes place on each day,any block identified its dealt with  

*limitation*

1.questionable since it cannot deal with mission critical systems 

2.not more than 7 members

*key things to consider while selecting a methodology*

1.Clarity of user requirement(users need to interact with technology to give more reliable feed back )(RAD or AGILE is best sine  the users are involved )

2.familiarity  with technology(RAD since one has to understand and learn the technology)

3.systems complexity

4.system reliability (important factor in systems development)(agile method is the best)

5.short time  schedules

6.schedule visibility

*SYSTEMS ANALYSIS ROLES AND  SKILLS*
Major categories of skills 

technical skill
( to understand the organization technical environment )

business skills
(to understand how IT will be applied to the investments)

analytical skills(problem solvers to the organization)

interpersonal skills (communication)

management skills

ethical skills 

**discuss the roles of the following in terms of their qualification 
competence 
development phases 

business analyst
system analyst
infrastructure analyst
change management
project analyst

x-stics of object oriented systems

objects 

classes template define and create objects

methods 

processes that the object should carry out include making an appointment checking last visit

inheritance 

polymorphism
# Distributed systems
 cmt 308
 ## lecture 0ne

introduction
--
distributed system/distributed computing 

This is a system with multiple components located in different locations communicate  and share resources in order to do different task in the network

include virtual machines and servers

**Benefits**

1.nodes in the distributed systems are connected to each other and one can share resources

2.easily add a node (scalability)

3.failure of one node does not lead to failure of the entire distributed systems

4.sharing of resources like printers

5.Doing different tasks at a time from different locations 

6.cost effective 

7.multiple processing can be done in the system

**challenges** 

1.overloading of a request can lead to down fall of the entire system

2.incase of malicious attack On one node it may attack the entire system

3.patching of the systems may be a bit difficult

4.data can be lost when moving it from one node to another 

5.troubleshooting and diagnostics can be difficult since you are working with different nodes at different locations

**Characteristics/elements**

1.Resources sharing 

2.scalability(adding more components to the system)

3.fault tolerance (system should continue working if a node fails)

4.compatibility

5.transparency (hides the complexity of the distributed system to the user)

6.concurrency

6.openness(no limitation )

**Types of distributed systems**

1.client - server system 

client - requests resources

server -process/allocates  resources

**adavantages**

centralized system 

cost effective in the long run

**disadvantage**

traffic issues

expensive in setting up

server failure may cripple the entire system

2.peer to peer system

nodes in peer to peer system have all equal rights

**advantages**

sharing of resources is equal to all nodes

failure of one node does not affect the system 

scalability

**Disadvantages**

no centralized system making it difficult to manage 

high risks of virus attacks

less secure due to transverse exchange 
 
files and resources are not centrally organized 

3.Three tier

uses separate servers and layers for each function of a program
 
 layers include:

 presentation layer(data encryption occurs)

 application layer(human interaction layer i.e access)

 data  link layer(defines format on data in the system)

4.N-tier distributed system

follows a similar structure to the three-tier but it can contain any number of functions in the system 

**APPLICATION AREAS OF DISTRIBUTED SYSTEMS**

finance and commerce

cloud technologies

health care (online patient records) 

education(e learning)

environment management

transport and logistics(google maps)

information society(search engines)

**evolution of distributed systems**

mainframe (1960-1967)

cluster networks(1970s)altenative for mainframe computers

internet and pcs(TCP/IP)connecting difgit ferent networks

world wide web -global interconnection

p2p,grids and web services

cloud computing,mobile and IoT(internet of things)

fog and edge computing

(Decentralization of resourcves breaches the gab between client and servers)
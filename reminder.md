# objected oriented  analysis and design(cmt 310)

## lecture 1
cat 1 10th october 2023
  
phases of system projects  include
planning ,analysis ,design and implementation

unified modelling language(uml) accelerated the change to system analysis and design

**system analyst** analyses the business situation identify opportunity for improvement and designs the system.
challenges the way the current organisaton works

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
  analysis system concept and models are combinedinto a document called **system proposal** 
  
  it describes the business requirements  the new system should meet

  3.**Design**

  decides on how the new system will operate in terms of hardware ,software requirement and type of network infrastructure;user interface forms and reports and specific programs ,databases and files that can be needed

  The design has four steps

  step one :design strategy

  step two:development of basic architecture design 
  describes hardware software and network infrastructure 

  step three:data base and file specificaton are developed

  step four:program design defines the programs should be written and function of these programs(**system specification**)

4.**IMPLEMENTATION**

final phase,gets most attention longest and most expensive 

step one :system construction

system is build and tested to  ensureit performs as designed 

step two:sytem installation 
old system is turned off and the new one is included in the sytem 

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

classes of system methodologies


1.structured design

first category adopted in 1980's

adopts a step by step appproach 
    example is the **1a.waterfall development**

    analysts and users proceed in sequence from one phase to the next

*advantages*

 1.identifies system requirements before programming begins

2.minimizes changes to the requirements

**1b.parallel development**

attempts to address the problem of long delays between analysis phase and delivery 

primary advantage is to reduce the time to deliver the system 

**2.rapid application development(R.A.D)**

attempt to address the weakness of structured methodology
recommends analysts to use special techniques and computer tools to speed up the analysis ,design and implentation  such as computer aided software

*2a. phased development*

breaks the overall system into a series of versions that are developed sequencial

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


# Distributed systems
 cmt 301
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

**characteristics**

1.Resources sharing 

2.scalability 

3.fault tolerance 

4.compatibility

5.transparency (hides the complexity of the distributed system to the user)

**Types of distributed systems**

1.client - server system 

client - requests resources 

2.peer to peer system

nodes in peer to peer system have all equal rights

**advantages**

sharing of resources is equal to all nodes

failure of one node does not affect the system 

**Disadvantages**







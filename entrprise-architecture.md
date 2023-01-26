## Notes on integration 

Referece:
1. [We can not buy integration](https://martinfowler.com/articles/cant-buy-integration.html)
2. [Software Engineering at Google](https://www.oreilly.com/library/view/software-engineering-at/9781492082781/)

## Keyword/Concepts:
tech debt, point-to-point integration, point-in-time integration

## Mindset 

- mindset, from thinking of how to solve integration problems with our tools to instead thinking of how to build the right interfaces to maximize agility.


## Notes:
- integration is not only connecting two sytem 
- integration should be broder defination
- Digital organizations shift the primary focus of integration from the systems to the capabilities, emphasizing clean interfaces over those capabilities.
  - interface should be simple
  - new system can be evolved through developement of new integration relatively quick and agile manner 

## Why simple interfaces:
- simple interfaces are one of the critical elements in creating a successful producr and to scaling inside a complex ecosystem
- clean and easy to use interfaces hide implementation details
- it is not about how good or bad technoogy is, rather providing a simople and easy to adopt interface


![Untitled presentation](https://user-images.githubusercontent.com/284564/214820897-0ecba622-fdaf-4669-b2b3-4e22e76b1b20.png)

Fig:It is possible to buy those box of system,however lines between them are not!

# Learning comment by Asraful:
- It is important to understand the capabilities and evolution of a system and and its internal integration also,alongside integration with other system
- DSL has significant role in clean interfaces and it helps to maintain organizational boundery across digital organization
- API consumers has no concerns and would be happy to not care about which systems the data comes from,they only care about how to get access to data
  - Explanation: Abstraction of critical data pipleline process and hide it well, so API consumer will ge the access of the data smoothly without knowing 
    its origin or complex pipleline
  - Abstract the capability, not the system

# Common mistakes
- Emphasizing the implementation languages in architecture diagrams
- Showing the commercial integration tool in an architecture diagram puts the emphasis on implementation details instead of interfaces and treats
  integration as a tactical concern
  
  
  
  

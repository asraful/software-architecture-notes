
 # Notes on Onion Architecture,EBI,Hexagonal Architecture 
 

![image](https://user-images.githubusercontent.com/284564/214033673-27948196-5b89-4a1a-9c51-307efbd5f3aa.png)

   Robert C. Martin 2012,[The Clean Architecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)

 
 ## [core intent of clean architecture](https://herbertograca.com/2017/09/28/clean-architecture-standing-on-the-shoulders-of-giants) 
 ## [The clean architecture,Uncle bob](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)

- independence of tools 
- independence of delivery mechanisms
- testibility in isolation

## Back in 2008, Jeffrey Palermo defined [four tenets of Onion Architecture:](https://jeffreypalermo.com/tag/onion-architecture/)

- The application is built around an independent object model
- Inner layers define interfaces.  Outer layers implement interfaces
- Direction of coupling is toward the center
- All application core code can be compiled and run separate from infrastructure
  - onion style seems like decoupled layred mechanism,where dependency direction towards its innermost layer !! 

## [Standing on the shoulders of EBI and MVC](https://herbertograca.com/2017/09/28/clean-architecture-standing-on-the-shoulders-of-giants/)

- Is it entity driven? 
- Is it domain diriven? 
- Is it making things complecated?
- What about data0deriven solutions?

## Learning by questions:

- The database is not the center.  It is external.
  - _how to desing the interaction of enity model ?_
- How to manage the numbers of adapters in onion architecture?
 - What kind of complexity we will face?
 - How it will evolve over the time?
 - There is a possibility of discontinued interfaces over the time ?
  - So,how to manage endoflie of those extran adapters and investing time and effort could backfire ?  


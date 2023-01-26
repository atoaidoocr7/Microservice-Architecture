# Microservice-Architecture


### Should you pivot to a Microservice Architecture ? 

There are many advantages  as well as disadvantages when it comes to working with a microservice architecture. Are you a startup, mid-size or even large size corporation looking to run a microservice architecture? Before deciding to pivot to a microservice architecture, there are some notable things: 

1. **Scalabilty** - Scalability in short terms refers to a measure of how easy it is to grow or shrink a piece of software based on the demand. There are times when an application might need to scale up and times when it might need to scale down. It is important to be ready to scale up and down at very unprecedented times. Your system and team must be ready to handle this. The advantage in regard to scalabilty is that teams will be able to rapidly scale up or down any component that is in need of scaling. In regards to scaability there really isn't much of a disadvantage. Being able to scale up and down as needed should be seen as an upside for any team.

2. **Agility** -  In short agile software development is  an iterative approach to project management and software development that helps teams deliver value to their customers faster and with fewer headaches.The advantage in regard to aglity is that teams are able to deliver business needs and features much quicker than they would in a non-agile environment. The downside is that if your team is not fit for unprecedented agility, this could cause disruptions in development.

3. **Distributed** - Microservices are distributed in nature in the sense that things like data stores and runtime and run on different computers. This leads to idealogies like eventual consistency. If your system cannot gracefully handle eventual consistency, it is most likely not a good idea to run a microservice architecture. Consistency refers to a database query returning the same data each time the same request is made. If you are building a system that needs data to be strongly consistent, there will be some tradeoffs such as high latency. It is important to think of such tradeoffs when deciding to pivot fully to a microservice architecture.


4. **DevOps and Architecture** - If you team has a solid devops team and has engineers that are well versed to switch between differnt complex designs and systems, this point should not be a big deal. On the contraray if your team is unable to handle unfamilair design methods, patterns and infrastructure, then it is probably not a good idea to pivot to a microservice architecture as this could cause disruption.

### Microservices are not the only way to go 

**Miniservices** and "Macroservices** are alternative apporaoches specially if the costs of running a microservice out weighs the benefits. Miniservice Architecture is in right in between microservice architecture and sercive oriented architecture(macro). In a miniservice archtecture, more than one feature is implemented and a few features may share the same runtime and data store.A macroservice architecture is essentially a miniservice architecture. For alot of teams, a a mioxture of these types of architecture might be better because not every part/feature of the application needs to be its own application.










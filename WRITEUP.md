# Project Write up
## Introduction
   Azure cloud infastructure offers many ways to deploy applications. Virtual machines allow developers to build as if they were on their local machine. This simplifies transition from local machines, at the cost of increased overhead in the form of increased OS and code management. App services allow developers to deploy web applications directly to Azure from local.This allows them to focus only on code, at the cost of flexibility as one is limited to Azure supported langauges. 
   
   Before making my choice, I made a pros and cons table below.  
   
| Service      | Pros | Cons | Scale | Cost |  
| ----------- | ----------- | ----------- | ----------- |  
| App Services      | Title       | Text        | Text        |  
| Virtual Machines   | Most simialar to traditional method of deploy- more resources and tutorials available, can install what is needed, more control        | Text        | Text        |  
## Virtual Machines-
Cons:  single machine, point of failure, need to monitor OS and everything installed on machine, pay for resources if used or not.
Pros: Most simialar to traditional method of deploy- more resources and tutorials available, can install what is needed, more control, always
have X resources available
Scale: Must create new virtual machines, then install any code dependencies to them.  
Cost: Fixed based on instance. 
Workflow: Take code that works on location machine, upload to machine via Github etc. 
Availability: Depends on machine or machines, 100% dependant on it.
## App Service-
Cons: Limited in programming languages, tutorials more limited, limited control over host machine or OS, non-traditional
Pros: Pay for what you use, can scale out to handle larger loads and in to minimize costs during downtime.
Scale: Can manually or set autoscale rules. 
Cost: Dependent on usage, as usage increases so does cost.  

## Choice

  Based upon the pros and cons listed above, I have selected App Service for deployment. I chose App Services as I don't anticipate much usage, making paying a fixed cost less apepealing. 
### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

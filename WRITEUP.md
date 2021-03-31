# Write-up Template
3/30/21  
Preface- 
Intro: Apps have traditionally been created and tested on local machines, before being deployed to cloud based VMs. 

VM-
CONS:  single machine, point of failure, need to monitor OS and everything installed on machine, pay for resources if used or not.
PROS: Most simialar to traditional method of deploy- more resources and tutorials available, can install what is needed, more control, always
have X resources available
Scale: Would have to make new VM for each app instance, harder to scale, more cumbersome.
Workflow: Take code that works on location machine, upload to machine via Github etc. 
Availability: Depends on machine or machines, 100% dependant on it.
App Service-
CONS: Limited in programming languages, tutorials more limited, limited control over host machine or OS, non-traditional
PROS: Pay for what you use, can scale out to handle larger loads and in to minimize costs during downtime.
Scale: Can manually or set autoscale rules. 
### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
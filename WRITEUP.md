# Project Write up- Brian Murphy
## Introduction
   Azure cloud infastructure offers many ways to deploy applications. Virtual machines allow developers to build as if they were on their local machine. This simplifies transition from local machines, at the cost of increased overhead in the form of increased OS and code management. App services allow developers to deploy web applications directly to Azure from local.This allows them to focus only on code, at the cost of flexibility as one is limited to Azure supported langauges. 
   
   Before making my choice, I made a pros and cons table below.  
   
| Service | Pros| Cons | Scale | Cost |  
| ----------- | ----------- | ----------- | ----------- |   ----------- |
| App Services      | Focus on code without worrying about OS or updates       | Newer, limited language support, less tutorials, limited control         | Automatic or manual scale based on needs|  Based on usage and service plan|
| Virtual Machines   | More traditional method to deploy, tutorials and resources more abundant, gaurenteed resources, more control  | Single point of failure, requires management of OS and software-web servers, code interpreters, etc.        | Requires new machines and installations        |  Fixed monthly costs| 

## Requirements
Requirements were as follows:
   * Article CMS, built using Python Flask
   * SQL Server for user and post data, and blob services for image hosting
   * Implement user authentication and login, including SQL Server and Microsoft Account with msal  
## Final choice
  Based upon the pros and cons listed above, I  selected App Service.   
  * Usage will be limited, or non existent, making a pay-as-you go model appealing. 
  * The app is small, and I would rather not have to deal with installing web servers, port configuration, domain registration, etc. for it. 
  * The project has no requirements for data storage, and is generally small.
  
## Assesing future needs
   In order for me to switch to virtual machines a few things would be needed. 
   
   * If data and application were required to be on the same machine in a specific area, such as HIPAA requirements, I would move to virtual machiens to gaurentee it. 
   * If the app was larger, requiring a certain level of resources or be available at all times, then a virtual machine may make sense. 
   * App usage would have to go up significantly, to make costs on par or less than running the application on app services. Alternatively, data storage costs would have to up, as at a certain point having VM with a MySQL server may cost the same or less.

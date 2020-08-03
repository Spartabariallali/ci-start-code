### CI/CD
#### Continous Integration
- CI is an automatic process that allows you to check the completeness of an application's code every time a team member makes a change. 
- CI requires the implementation of processes such (branch,commit, pull request, code review)
- To implement CI, it is necessary to have a Source Code Manager(SCM)

- source -> Build -> Test -> Production
- Differences between ci and cd - ci all commits are made to the development brance 
- cd (contonous delivery) is the practice of packaging and preparing the software as if it was sent to production
- for example:

``` Integrate --> Test --> Release --> Deploy test ```

``` Integrate --> Test --> Release --> Deploy test --> Deploy Production ```

``` Integrate --> Test --> Release --> Deploy test ```
 
### Continous Delivery
- After the code has been sent to the SCM it is ready to be deployed
- CD aims to test the entire application with all its dependencies.

### SDLC - software development lifecyle 

1. Development - software developers creating the code that makes the main infrastructure of the application (gives the application functionality)
2. Testing - can be both manual and automated 
3. Production - release the product live to the intended user 

###  SAAS - Software as a Service 
- Used directly by the client/end user
 
### Drawbacks in SDLC 
- Historically very slow process
- when the product was deployment a lot of bugs were uncovered 
- issues when it came to integration towards the end of the project
 

### DevOps has modernised the SDLC 
- Automate the whole process - intercept issues/bugs before they go live to the client 
- constant feedback on commits made by developers 
- Jenkins is a tool used to automate the DevOps process 
- after the all tests are passed in the integration stage we move on to the delivery stage 
- staging - testng - delivery 
- Delivery is a manual process 
- Continous Deployment is an invisible process - when a new functionality is ready to be lauched its added to the process



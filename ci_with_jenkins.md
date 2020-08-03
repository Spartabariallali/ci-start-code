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


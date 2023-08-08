---
name: To query a subset of products in the catalog.
about: Need the ability to query a subset of products in the catalog.
title: ''
labels: ''
assignees: ''

---

**As a** [User]  
 **I need** [The Query Functions]  
 **So that** [I can Query a subset of all products in the catalog]  
   
 ### Details and Assumptions

- Artifacts for cloud foundry app have already been created in branch 'cf-deploy'.
- [ ] Database will still need to be provisioned
- [ ] Apps needs to be pushed and connected to the database
 * [document what you know]
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given [The query functions has been built]
 When [A client visited our URL]
 Then [Ability to query a subset of all products catalog are functional]
 ```

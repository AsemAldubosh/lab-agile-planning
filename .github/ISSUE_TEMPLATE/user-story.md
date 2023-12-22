---
name: User Story
about: Finance Report
title: ''
labels: ''
assignees: ''

---

**As a** CFO  
 **I need** yearly procurement report
 **So that** I can set a budget plan for the next year 
   
 ### Details and Assumptions
 * We have a list of all procurement in our ERP System, and our ERP has an API that we can use

 ### Acceptance Criteria  
   
 ```gherkin
 Given there are 1000 rows in our procurement DB
 When there are 100 returned goods
 Then I should get a report containing 900 rows
 ```

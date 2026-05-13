---
name: User story
about: This template is for creating user stories
title: 'Create product in catalog'
labels: 'user story'
assignees: 'me'

---

**As a** catalog administrator  
**I need** to create a product in the catalog  
**So that** new products can be added to the system  
   
### Details and Assumptions
* Product information includes name, description, price, and category
* Only authorized administrators can create products
* The catalog database is already configured
   
### Acceptance Criteria  
   
```gherkin
Given I am an authenticated administrator
When I submit valid product information
Then the system creates the product successfully

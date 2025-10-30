---
name: User story
about: this template is for creating user stories
title: ''
labels: ''
assignees: ''
---

**As a** customer  
**I need** the ability to like a product in the catalog  
**So that** I can easily find my favorite products later  

### Details and Assumptions
* The user must be logged in to like a product.

### Acceptance Criteria  

```gherkin
Given the user is viewing the product catalog
When they click the “Like” button on a product
Then that product should appear in their favorites list

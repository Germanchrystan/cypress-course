# What is Cypress?
Cypress is a JS based test automation tool & framework for web developers. We can use Cypress to write automated tests for the website we are currently working on.
Cypress can be used to write E2E tests and component tests. Though this course here will be about end to end tests.

With E2E tests, we can have automated tests that test entire application flows.

E2E testing is all about testing these complete flows.
```
User visits page -> Enters text -> click button -> Todo item is added
```
```
User visits login page -> Enters credentials -> submits form -> Views dashboard
```

## E2E vs Unit Testing
| Unit Testing | E2E testing  |
|----------|:------------:|
| Test small app building blocks | test complete application workflows| 
| (e.g., and individual function)       | (e.g., login flow)| 
| Ensures correct functionality of individual units| Ensures correct functionality of core app features and processes| 
| Does not guarantee functionality of overall systems| Does not necessarily cover all building blocks of an app| 


## Installing Cypress
```
npm install cypress
```

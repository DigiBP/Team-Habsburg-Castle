# Team Habsburg Deliverables

Link to GitHub Repository:

https://github.com/DigiBP/Team-Habsburg-Castle

Link to GitHub WIKI:

https://github.com/DigiBP/Team-Habsburg-Castle/wiki

Link to GitHub Project Plan:

https://github.com/DigiBP/Team-Habsburg-Castle/projects

Link to Final BPMN version 1.0

https://github.com/DigiBP/Team-Habsburg-Castle/tree/master/src/main/resources/FinaL_Team_Habsburg_v1.0.bpmn

Link to Video Presentation:

https://www.youtube.com/watch?v=qLvF5JkMuK4&ab_channel=ChristopherGalli


Link to running instantiation of cloud based deployment:

http://digibp-habsburg.herokuapp.com/app/welcome/default/#!/login


https://dashboard.heroku.com/apps/digibp-habsburg


Login credentials:

Admin:      demo pw: demo

Assistant:  HbAssistant1 pw: Assistant1

Assistant:  HbAssistant2 pw: Assistant2

Assistant:  HbAssistant3 pw: Assistant3

Assistant:  HbAssistant4 pw: Assistant4

Pharmacist: HbPharmacist1 pw: Pharmacist1

Pharmacist: HbPharmacist2 pw: Pharmacist2


# DigiBP Camunda Template

[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![Deploy to Heroku](https://img.shields.io/badge/deploy%20to-Heroku-6762a6.svg?longCache=true)](https://heroku.com/deploy)

## Releases

### [7.13.0](https://github.com/DigiBP/digibp-camunda-template/tree/7.13.0)
- Updating Camunda to 7.13.0
- Updating Camunda Spring Boot Starter to 7.13.0
- Updating Spring Boot to 2.2.5.RELEASE

### [3.4.0](https://github.com/DigiBP/digibp-camunda-template/tree/3.4.0)
- Updating Camunda to 7.12.0
- Updating Camunda Spring Boot to 3.4.0
- Updating Spring Boot to 2.2.1.RELEASE

### [3.3.0](https://github.com/DigiBP/digibp-camunda-template/tree/3.3.0)
- Updating Camunda to 7.11.0
- Updating Camunda Spring Boot to 3.3.4
- Updating Spring Boot to 2.1.6.RELEASE
- Removing Maven Wrapper
- Removing Camunda Modeler Templates

### 3.2.3
- Adding `spring-boot-starter-jdbc` dependency, otherwise `spring:datasource` is ignored.

### 3.2.2
- Use of Camunda deployment procedure (embedded:deployment) instead of Spring Boot (embedded:app)
- Change of resource folder structure due to the use deployment procedure  

### 3.2.1
- Rearrange the order of the REST and Web Apps dependencies

### 3.2.0
- Updating Camunda Spring Boot to 3.2.0
- Updating Spring Boot to 2.1.1.RELEASE

### 3.1.0
- Updating Camunda to 7.10.0
- Updating Camunda Spring Boot to 3.1.0

### 3.0.0
- Updating Camunda to 7.9.0
- Updating Camunda Spring Boot to 3.0.0
- Updating Spring Boot to 2.0.2.RELEASE

### 2.0.7
- Default Maven goal `clean spring-boot:run`
- Camunda Modeler Element Template (not in archetype)

### 2.0.6
- A much nicer `deploy to Heroku` shield.

### 2.0.5
- Adding 'authorization: enabled: false' to application.yaml

### 2.0.4
- Adding application-local.yaml to .gitignore
- Updating application.yaml and application-heroku.yaml

### 2.0.3
- Adding a README.md file

### 2.0.2
- Adding a .gitignore file

### 2.0.1
- Adding a .gitignore template file

### 2.0.0
- Updating Camunda Spring Boot to 2.3.0
- Updating Spring Boot to 1.5.8.RELEASE

### 1.0.6

- Updating Camunda Spring Boot to 2.1.0
- Updating Spring Boot to 1.5.3.RELEASE
- Adding to application.yaml: `camunda:bpm:authorization:enabled:true`

### 1.0.5

- Updating Camunda Enterprise Edition to 7.6.4
- Uncommenting Camunda REST API
- Adding (uncommented) Spring Boot Data
- Adding (uncommented) Hibernate configuration to application.yaml

### 1.0.4

- Adding Camunda Enterprise Edition

### 1.0.3

- Fixing the Maven issue

### 1.0.2

- Fixing the Eclipse issue

### 1.0.1

- Fixing the basic package

### 1.0.0

- Initial version

## Maintainer
- [Andreas Martin](https://github.com/andreasmartin)

## License
- [Apache License, Version 2.0](https://github.com/DigiBP/digibp-archetype-camunda-boot/blob/master/LICENSE)

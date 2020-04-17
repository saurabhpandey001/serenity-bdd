## Serenity BDD Project

### Pull the code base and create a maven project

#### How to run serenity test ?
Create a maven run configuration and run below command: 
- clean verify serenity:aggregate 

To run tests on a specific browser please run below command:
- clean verify -Dwebdriver.driver=chrome serenity:aggregate

### How to verify serenity report ?
Go to target -> site -> serenity and open index.html file, which is main report.
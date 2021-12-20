# The following concerns work completed in SNHU CS-305 Software Security
## Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
#### Artemis Financial is a fictional client in the banking industry interested in storing and securing data at rest and in transit.
## What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
#### I was able to identify and address several vulnerabilities, some in the main code and some were dependency related. I was able to address a Log4J vulnerability with RCE potential by using a more current version. Secure code adds a measure of stability to a company in terms of it being able to exert real control over its assets. 
## What about the process of working through the vulnerability assessment did you find challenging or helpful?
#### Learning the syntax for implementing my own keystore in a spring server was somewhat challenging. The sheer number and complexity of listed vulnerabilities was somewhat daunting, however it did seem manageable if I were tasked with systematically addressing each one listed by the dependency checker used. 
## How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
####  I was able to identify the need for https use and implement a solution in java for applying the selected encryption scheme with the message digest function.
## How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
#### I ran the OWASP dependency checker again after implementing my code and noted the impact of the new code, which was none. I used firefox to view the site being served locally to check the functionality of the encryption.
## What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
#### I was able to use spring, which I enjoyed. I think one of the biggest things I did in this work is learning how to read documentation for the language and software being used as tools. Essentially, learning to learn to use tools. The OWASP Dependency Checker and the National Vulnerability Database were also particularly useful.
## Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
#### I would probably point to my successful implementation of a spring server with a working security certificate.

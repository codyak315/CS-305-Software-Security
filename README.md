# CS305
Software Security

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

  Artemis Financial is a consulting company that sought a web-based solution to handle their client's sensitive information. Specifically financial portfolios and stock trading data and practices.  

What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

  Software security is important to everyone, not just institutions that handle sensitive data like our client Artemis Financial. Secure code may well just be synonomous with good code, if your code is not secure then it is not "good". That is to say the by applying best practices that result in easily readable and understandable code not only is it more likely that the operation is smooth but it makes it easier to spot any potential pitfalls as well as make it more difficult to hide anything malicious as well. In this specific instance I would say that through thorough static testing we have created an environment where we are keenly aware of our dependencies and their potential weakpoints which goes a long way towards a more secure environment. 

What about the process of working through the vulnerability assessment did you find challenging or helpful?

  The most challenging component of the vulnerability assessment is hands down the manual review. It is relatively easy to identify area's of security, and if you know how to operate the system static testing is largely done for you. Manual review however is all on the reviewer to have the knowledge to spot weakpoints that even a computer wouldn't notice. 

How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

  When considering layers of security I like to take an approach using a priority system, start with the components that you can control the most and work your way to the components you can control the least. In this regard the highest priority is making sure your code is secure. This is done by using best practices to name variables, javadoc on any methods that may not be explicitly clear, and verifying easily overlooked aspects of code such as case-sensitivity. From here static testing is the next logical step to make sure that the dependencies you are using are not opening your system to any vulnerabilities that you may not even realize because you didn't code it. 

How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

  Static testing was a big component of making sure no new vulnerabilities were added. The only added component of the refactor was a REST controller, so logically research needed to be done to make sure that the REST API did not contain any additional vulnerabilities and that coding practices were in line with the functionality of the REST controller to maintain a secure environment. 

What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

  It is difficult to choose any one thing that I have learned from completing these assignments to employ. I feel that utilizing SPRING and getting famililar with the Project Object Model (POM.xml) aspect of Maven have been invaluable. At first it seemed daunting to run a dependency check, having to modify an xml file to upgrade to the correct version, or even get the Spring Boot Application to run, but after spending time with the programs and manipulating files and locations I feel I have a far better understanding of not only how software security is applied, but even how applications are constructed fundamentally as well. 

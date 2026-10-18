# CS305-SoftwareSecurity
This is a repository for the CS305 Course


Client and Software Requirements
My mock client was Artemis Financial, a consulting company that develops personalized financial plans for its customers. The company wanted to improve the security of its web application to better protect sensitive financial information and ensure that data remained secure during transfers. Specifically, Artemis Financial needed a checksum verification process to detect changes to transferred data and secure communication through HTTPS. My task was to refactor the existing application, implement SHA-256 checksum verification, configure a self-signed certificate, and test the application for potential security vulnerabilities.

What I Did Well and the Importance of Secure Coding
I did well by focusing on the security requirements and testing the application after making changes. I implemented SHA-256 checksum verification, configured HTTPS, and used OWASP Dependency-Check to identify known vulnerabilities in the application's dependencies. I also reviewed and tested the refactored code to check for syntax, logic, and security issues.

Coding securely is important because software vulnerabilities can expose sensitive information, allow unauthorized access, and damage a company's reputation. For a company like Artemis Financial, protecting customer information is especially important because customers rely on the company to handle their financial data responsibly. Secure coding practices can reduce the risk of data breaches, avoid costly security incidents, and help maintain customer trust. These benefits support the company's long-term success and overall well-being.

The Most Challenging or Helpful Part of the Vulnerability Assessment
The challenging part was understanding the testing results and determining what needed further attention. As all of it seems related to outdated versions, but in order to allow the use of the school labs, which all run on older versions of software, it makes it hard to determine if the updated versions should be used or not. A successful application run does not necessarily mean that the application is secure. I learned that security testing requires more than checking whether the code compiles and runs. It also requires reviewing dependencies, examining the code, and verifying that security features work as expected.

Adding Layers of Security and Assessing Future Vulnerabilities
I increased the application's security by combining several measures that address different risks. SHA-256 checksum verification helps detect changes to transferred data, while HTTPS protects information during transmission. I configured a self-signed certificate for secure communication during testing and used OWASP Dependency-Check to identify known vulnerabilities in software dependencies. I also manually reviewed the code and performed functional testing to check that the application worked as intended.

In future projects, I would begin by reviewing the application's requirements and identifying the most sensitive data and potential attack points. I would use tools such as OWASP Dependency-Check and static analysis tools, along with manual code reviews and functional security tests, to identify potential weaknesses. I would then prioritize vulnerabilities based on their severity, likelihood of exploitation, and potential impact. After applying mitigation techniques, I would rerun the tests to verify the changes and check for new issues.

Ensuring the Application Was Functional and Secure
I checked the application's functionality by compiling and running the refactored code, verifying checksum generation and verification, and confirming that the application could communicate over HTTPS. I also reviewed the code for syntax, logic, and potential security issues. These steps helped me confirm that the changes worked without disrupting the application's expected behavior.

To check for newly introduced vulnerabilities, I ran OWASP Dependency-Check and reviewed its report for known vulnerabilities in the application's dependencies. I also manually reviewed the code I added and tested the application's behavior after refactoring. When testing identifies errors or potential vulnerabilities, the results should be investigated, addressed as needed, and tested again. This process helps reduce the chance of introducing additional security problems while improving the application.

Resources, Tools, and Coding Practices
Several resources and tools from this assignment will be useful in future projects. Java Keytool helped me generate a self-signed certificate, while HTTPS configuration demonstrated how to establish encrypted communication between a browser and a web application. Implementing SHA-256 checksum verification helped me understand how hashing can be used to check data integrity. OWASP Dependency-Check was also useful for identifying known vulnerabilities in software dependencies.

I will continue using secure coding practices such as validating application behavior, reviewing code changes, managing dependencies, and testing after making modifications. I also learned the importance of using multiple security measures rather than relying on a single solution. These practices can help me identify problems earlier and develop applications that are more reliable and secure.

Demonstrating My Skills to Future Employers
I could use this assignment as an example of my ability to improve an existing application while considering its security requirements. The refactored code would demonstrate my experience implementing SHA-256 checksum verification, configuring HTTPS, and working with Java Keytool to generate a certificate. I could also show screenshots of the successful checksum verification, secure webpage, application execution, and OWASP Dependency-Check results as evidence of my testing process.

This project also demonstrates my understanding of secure coding, vulnerability assessment, and functional testing. It shows that I can follow technical requirements, use security tools, investigate potential weaknesses, and verify application behavior after making changes. These are valuable skills for software development roles because security must be considered throughout the development process, not just after an application has been completed.

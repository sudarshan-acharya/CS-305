## CS-305 Portfolio

### Artifact

**Artemis Financial Practices for Secure Software Report**

This project demonstrates my knowledge of secure coding, software security testing, and improving the security of a Java web application.

## Reflection

## Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a financial consulting company that provides services such as savings, retirement, investments, and insurance planning. The company wanted to improve the security of its web application so that the customer information would be protected during communication. My task was to add HTTPS, generate a SHA-256 checksum, create a self-signed certificate, and test the application for security vulnerabilities.

## What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I think I did a good job following secure coding practices and testing the application after making changes. I made sure the application still worked while adding new security features. Coding securely is important because it helps protect customer information, reduces security risks, and builds trust between the company and its customers.

## Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging part was working with the OWASP Dependency Check plugin. I spent a lot of time trying different plugin versions, Maven settings, and an NVD API key, but the scan could not finish because of an external NVD server timeout. Even though it was frustrating, I learned more about security tools and troubleshooting.

## How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased security by adding HTTPS, creating a self-signed certificate, using SHA-256 hashing, and testing the application after making changes. In the future, I would continue using tools such as OWASP Dependency Check, manual code reviews, and secure coding guidelines to identify vulnerabilities and choose the best way to fix them.

## How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I tested the application after each change to make sure it still worked correctly. I verified that the HTTPS connection worked, confirmed the SHA-256 checksum was generated correctly, and attempted to run the OWASP Dependency Check plugin. Although the dependency scan could not finish because of an external NVD server issue, the application compiled and ran successfully without errors.

## What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Some of the most helpful tools were Java Keytool, Maven, Eclipse, Spring Boot, SHA-256 hashing, HTTPS, and the OWASP Dependency Check plugin. I also learned the importance of testing changes often, reading error messages carefully, and documenting the troubleshooting process.

## Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show employers this project because it demonstrates that I can improve software security by implementing HTTPS, generating certificates, using SHA-256 hashing, and testing a Java application. It also shows that I can troubleshoot technical problems, document my work, and continue working through challenges even when external tools do not behave as expected.
 

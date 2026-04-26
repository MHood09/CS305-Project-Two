# CS305-Project-Two
Artemis Financial secure software project

1. Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial was the client, and they needed help improving the security of their software application. Their system handled sensitive financial data, so it was important that it was protected from vulnerabilities and potential attacks. The main issue they wanted addressed was making sure their application followed secure coding practices, protected data during transmission, and reduced any known security risks.

2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I think I did a good job identifying security weaknesses and taking steps to fix them instead of just pointing them out. I applied multiple layers of security like adding HTTPS, creating a certificate, and using hashing to protect data integrity.

Coding securely is important because it helps prevent data breaches, protects sensitive information, and keeps systems from being exploited. Security adds value to a company by protecting customer trust, reducing risk, and helping avoid financial or legal issues that could come from a security failure.

3. Which part of the vulnerability assessment was challenging or helpful to you?

The most challenging part was setting up the dependency-check tool and waiting for it to run correctly, especially with the network delays and warnings. However, it was also helpful because it showed how real-world security tools work and how vulnerabilities can be identified in project dependencies. It gave me a better understanding of how to analyze security beyond just writing code.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased layers of security by enabling HTTPS, generating a self-signed certificate, and implementing SHA-256 hashing for data verification. I also used dependency-check to scan for known vulnerabilities in the project.

In the future, I would continue using tools like OWASP dependency-check, along with other vulnerability scanning tools and secure coding practices. I would also follow industry standards and guidelines to decide which mitigation techniques are best based on the type of vulnerability.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

I made sure the application was functional by running it in Eclipse and verifying that it started without errors and displayed the correct output on the webpage. I tested the /hash route to confirm that the checksum feature worked properly.

To check for security, I ran the dependency-check tool to scan for known vulnerabilities after making changes. This helped confirm that the updates did not introduce new issues and that the application remained secure.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

Some of the most helpful tools I used were Eclipse, Java Keytool, and OWASP dependency-check. I also used secure coding practices like hashing with SHA-256 and enabling HTTPS for secure communication.

These tools and practices will be useful in future projects because they help improve application security, test for vulnerabilities, and ensure that software is built with security in mind from the beginning.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

From this assignment, I could show employers my ability to identify and fix security vulnerabilities, implement secure communication using HTTPS, and apply hashing for data integrity. I could also show my experience using tools like dependency-check to analyze security risks.

This project demonstrates that I understand basic software security concepts and can apply them in a real application, which is important for any role involving secure software development.

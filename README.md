# CS305
Artemis Financial Practices for Secure Software Report

  -Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
	
  Artemis Financial is a consulting company that develops financial plans, which includes savings, retirement, and investments.
      
  -What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
	
   One thing I did particularly well in was figuring out potential dependencies in the code through integrating the Maven dependency-check plug-in, which was something I have never had experience doing before! It is important to code securely because it limits potential threats from being introduced into the code, and it ensures that your code is easily maintainable for future updates. Software security is valuable to a company's overall well-being because it is what protects sensitive information, such as passwords and addresses, from being accessed by malicious threats.
      
  -Which part of the vulnerability assessment was challenging or helpful to you?
	
   Using the dependency-check plug-in was helpful to me throughout this course, as it was a simple and easy way to see all vulnerabilities in one place, as well as links to depositories that could help resolve the dependencies. 
      
  -How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
	
  I increased the layers of security by implementing the dependency-checks and cryptography/certificates into the program. In the future I believe that I will be able to utilize the self-signed certificate generation for testing purposes, as it gives me a way to see which info should and should not be seen by the end user.
      
  -How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
	
   To make sure that the code and the software application was functional and secure, I had to use the SHA-256 hashing protocol to generate a secure encryption key that allowed for the http/https server to connect securely. Then, after refractoring the code I made sure to compare the before and after dependency-check to ensure that no more vulnerabilities were introduced.
      
  -What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
	
  I utilized the textbook for the class, as well as Reddit threads on cryptology to give me an idea of which hashing protocol was the most secure and hardest to crack. Also, using open-source plug-ins that help me keep track of the libraries that I use in my code proved to be incredibly useful, as sometimes it is easy to skip over or miss a certain library! (Especially after coding for a few hours straight)
      
  -Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

   From this assignment, I would show how I created the self-signed certificate and how it was beneficial to the software. 

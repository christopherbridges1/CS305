# CS305
CS 305 Mod 8
Chris Bridges

/* Answers pending 

  Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?
Artemis FInancial is consulting company that provides individualized financial plans for their customers. These plans include savings, retirement, investments and insurance.
Artemis requests a web based application that meets federal and international compliances. These compliances include industry standard encryption, protocols, and secure communication.  

  What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I added a self signed certificate for secure communication and used the SHA-256 algortihm for encryption. It is important to code securely to mitigate your vulnerabilities and reduce the risk of being atatcked. By adding software security features to your code, you create something that is less prone to attacks. This saves time, money, and resources for a company. 

  Which part of the vulnerability assessment was challenging or helpful to you?
When I attempted to update Springboot, I found that Java would need to be updated as well. I tried working around it, and using different ways but I never could get it to update properly.  

  How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
By using encapsulation within the code, adding encrytion algorithms, and the HTTPS protocol. In the future I would use the same features in projects I work on. I would also try to break the code I create from the user's side.  

  How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
 The same vulnerabilities were present both befroe and after I refactored the code. So I know I introduced no new problems. Doing a static test using the maven dependency plugin.

  What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
Knowing how to create a self signed certificate will be useful for testing future projects before going to production and using a real certificate. 

  Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would demonstrate the ability to create a self signed certificate, The algorithm code I created to generate the checksum, and how I ran a dependency check to search for vulnerabilities. 
*/


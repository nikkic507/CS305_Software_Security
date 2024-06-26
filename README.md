# CS305_Software_Security
Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial is a financial company that helped their clients with financial planning that include savings, retirement, investments, and insurance. They want to modernize their business needs by using the most effective and current software security to protect themselves and their clients information. The specifically wanted to add file verification to their web app for secure communications. 

What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I used the OWASP Dependency-Check Maven to get an accurate view of what vulnerabilities were present. I also suppressed any false positives to clean up the check for clarification on what exactly needed to be looked at. This allowed me to see what corrections needed to be made and ensure we were using all the updated versions for this application to keep it as secure at possible. Software security is very valuable to any company that uses software for their business. It keeps the information safe and puts up barriers to prevent attacks for them and their clients. When a customer feels safe using the app or service they will keep coming back.  

What part of the vulnerability assessment was challenging or helpful to you?

I found the vulnerability assessment process flow diagram very helpful. It broke down the step and gave a clear picture of what vulnerabilities needed to be focused on for software security. At first it was challenging to completely understand what "category" the vulnerabilities might fall under or exactly where I needed to focus because they all blend together if worked properly and are all important when providing a secure application. 

How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

To increase layers of security I implemented a checksum and generated a self-signed certificate using the Java Keytool.  In the future I will continue to use the OWASP Dependency-Check, suppressing the false positives and mitigating the true issues that are present. In this case most issues were using out of date apllications or libraries. 
How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I used the dependency check tool to check for vulnerabilities. I manually reviewed the code after it was complete and ran a debug test to see if there were any issues. I ran the dependency check again to ensure no new vulnerabilities were introduced after the refactoring. 

What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I used to resources provided by the instructor that included tutorials, mavens dependency check, vulnerability assessment process flow diagram, NIST website, github information, Eclipse offers a ton of helpful information if you get stuck, and of using industry best practice standards. 

Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would show future employers the layers of security used to add to the application with help of the rubric.I would demonstrate that use of tools that were available to me and highlight the understanding that is present in the template. 

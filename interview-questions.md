## Intern/Entry Level Interview Questions
Intern/Entry level interviews aren't as difficult interviews compared to security engineers and tier 2/3 security analyst interviews. During these interviews, the hiring manager is looking to see if you understand basic network and security fundamentals. Questions asked in these interviews are typically straightforward with few scenario-based questions. During this stage in your career, it's extremely important that you showcase your willingness to learn. You will accomplish this by talking about how you are keeping up with cyber security news, home labs you have built(don't worry, I'll create a repository for home labs as well), and how you are contributing to the security community (this is a major bonus).
* Tell me about yourself. (This question is not meant for you to give your life story. This question is meant for you to give an overview of your career  geared towards cybersecurity, your educational background, why you chose cybersecurity, your passion for cybersecurity, etc.)
* What steps would you take you secure a server? (This question is asked to see if you have a basic understanding of how to secure a server. This does not mean you will be administering servers, but it lets the interviewer know that you understand basic fundamentals of system hardening.)
* What is the difference between UDP and TCP? (Testing you networking and protocol knowledge. Hint: One protocol is primarily used in Video Streaming. The other protocol is used to send emails.)
* How do you stay up to date with the latest security news?
*  Are there any high-profile security incidents that have interested you lately and why?
* What are the default ports for HTTP and for HTTPS? (Requires basic port and protocol knowledge.)
* Explain the CIA Triad. (The CIA Triad is the backbone of cybersecurity. It's important to understand it.)
* What is two-factor authentication? (You don't need to know how to implement it, but understanding it full and knowing why you should use it is important.)
* Explain the OSI Model. (This requires networking knowledge. Hint to remember the 7 layers: All People Seem to Need Data Processing. (This is a Mnemonic) )
* Explain a 3 way handshake. (Requires basic networking knowledge. Hint: When thinking about a 3 way handshake, think about a mailman delivering a package with a tracking number)
* What is the difference between Symmetric and Asymmetric encryption? (Basic knowledge of encryption. Hint: Symmetric = Same, Asymmetric = Different)
* How does encryption, encoding and hashing differ? (Basic knowledge of encryption. Hint: The CIA triad)
* What are some important protocols and their respective ports? What are those protocols used for? (Basic networking knowledge. Interviewer is looking to gauge your networking experience and how well you explain their purpose.)
* Explain the differences between risk, vulnerability, and a threat. (The interviewer is looking for a clear and concise answer. Less words are more.)
* What happens when you enter a site on google in your browser? (Test networking and protocol knowledge, hint think of DHCP, NAT, DNS & it's recursion, IP Addresses, TLS )
* Can you explain the difference between true positive, false positive, and false negative?
* What is SSL (Secure Sockets Layer)? Explain how it works
* What is TSL (Transport Layer Security)? Explain how it works
* What is a Firewall and why is it used? (Explain the Difference between a stateful and stateless firewall).
* Explain MITM attack and how to prevent it?
* Explain DDOS attack and how to prevent it?
* Can you describe a standard cyber security incident response process? (USE NIST IR process and give some details about what happens at each stage).
* Explain what subnetting is and why it's important?
* Explain NAT and why it's Important?
* What are some common Cyber Attacks?
* Go Over the pyramid of pain from top to bottom and explain how blue teams use it in conjugation with mitre att&ck to make attackers objectives harder?

## Scenario Based Questions
* You receive an alert for an incident, how would you investigate it? (There's no right or wrong answer to this situation. This is a vague question, in which you have to ask questions to gather information before deciding how you're going to answer the question. Having experience conduction investigations will help you with this, but not having experience isn't the end of the world. Think out loud of your solutions so that they can hear your thought process. Hearing your thought process is extremely important.)
* A user reports that their computer is running slow and acting abnormal. You investigate it and notice that the computer has been making requests to an unknown IP address, what do you? (This question gauges your knowledge on attack methods and networking. Hint: DNS requests is  🔑 )
*  How would you triage(analyze) an unusual authentication alert in the environment?
*  How would you investigate a malicious phishing alert
*  How would you determine if data exfiltration has taken place?
*  How would you triage a user downloading potential malicious software?
*  How would you analyze a suspicious process alert firing for an endpoint? How would you determine if it's malicious?
*  Lets say a user account was compromised? How would you look for lateral movement in the environment?
*  An S3 bucket was made public, how do you determine if this activity is suspicious or a false positive?
*  How would you triage unusual IAM activity for a user in AWS?
*  What would you do if noticed mimikatz on a domain controller?
*  What would you do if you observed multiple user accounts were compromised?
* Can you tell me about a favorite threat detection that you have built? How did you build it? What problem did it solve? (This question may be geared towards security engineers and/or tier 3. This question will be to gauge the complexity of threat detections you have built, what data sources you have used, etc. It's also a time to show off your critical thinking skills on how & why you developed them. As well as how you were able to solve problems that the organization may or may not have known existed)
  

## Network Security Interview Questions
* Which is more secure HTTPS, SSL, or TLS. (This is a trick question. Requires basic networking knowledge. Hint: What does HTTPS use to encrypt data?)
* What is the importance of DNS monitoring? What are DNS attack methods? (Straight forward question. Intermediate networking knowledge. The interviewer is gauging your overall knowledge of DNS and how it can be exploited)

## Application Security
When interviewing for cybersecurity positions, there won't be many application security questions unless you're applying for cloud, appsec, etc type roles. You still need to understand the fundamental concept of application security, although.
* What is the OWASP Top 10? (These are the most critical security risks to web applications)
* Explain XSS and how can to prevent it? (XSS is apart of the OWASP Top 10)
* Explain SQL Injection and how to prevent it? (SQL Injection is apart of the OWASP Top 10)
* Explain CORS and how can to prevent it?
* Explain CSRF and how can to prevent it?
* Explain Command Injection and how can to prevent it?


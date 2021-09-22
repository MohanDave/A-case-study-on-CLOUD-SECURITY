

Application Programming Interface (API) Keys [19] on the cloud were first used solely as the identifier for 
client programs running on a cloud. This allowed for the management of client programs and users to be moni-
tored so as to backtrack events and log usage. While initially this had no security issues involved, later progress 
on cloud infrastructure has expanded the use of these keys [2]. In some cases it has been reported that these keys 
are used for authorization. Thus having this key gives one the power to alter delete or transfer an account’s data 
or to use the servers for any other purpose, which would then be traced back and billed to the account holder [2]. 
After these keys became security risks the major problem was that they were not treated like them. Developers 
would email them around and store them in their hard drives, where snooping and sniffing could find them. 
Years ago Google and Yahoo were making this mistake, but it was not long until the risks were found. They 
have since bulked their authorization security using Security Assertion Markup Language [21], and hashed- 
based authentication codes [22]. Yet the issue remains a threat as developers fail to follow best practices and 
continue to use API Keys for security purposes [2]. The older, more experienced businesses like Yahoo, Google, 
and Amazon have all either fallen into this trap before or are aware of the faults present. These companies can be 
trusted to build better software and control data flow than startups. If API Keys are going to secure information, 
they need to be handled with greater care. 
4.3. APIs 
Application Programming Interfaces or APIs, give what is almost a roadmap into how an application works [9] 
[10]. They are usually treated securely but not often enough. The University of Texas at Austin and Stanford 
University examined several commonly used web services [10]. Payment services at several of them were found 
to have vulnerabilities in the Secure Sockets Layer (SSL) protocol when accessed through APIs not meant for a 
browser [3]. Taking advantage of this flaw led to getting access to a user’s files. Applications like Chase Mobile 
Banking and Instagram failed to implement SSL with complete security [10]. 


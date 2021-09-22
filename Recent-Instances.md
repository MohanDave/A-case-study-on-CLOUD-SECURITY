   Recent Instances
In recent years, one of the companies on the vanguard of cloud technology—Amazon.com, Inc.—fell prey to 
such an attack. In 2010 hijackers performed a cross-site scripting (XSS) attack on some site to gain its creden-
tials, and were successful [23]. The attackers then infiltrated the Amazon Relational Database Service (RDS) [7] 
such that, even if they lost their original access, they would still have a backend into the Amazon system. From 
that point on, they could capture the login information of anyone who clicked the login button on the Amazon 
homepage. 
The attackers used their servers to infect new machines with the Zeus Trojan horse [23] and control machines 
already infected with it (Zeus is a piece of malware designed for Windows most often used for stealing bank in-
formation through form-grabbing and password-logging via a man-in-the-browser attack [24] [25]). Computers 
infected with the malware began to report to Amazon’s EC2 for updates and instructions [23]. 
One of the most interesting facts about this case was that it was not, strictly speaking, Amazon’s fault. The at-
tackers gained access through some other, more vulnerable domain [23]. This reveals one truth about the cloud: 
on it, even one vulnerable system may lead to the compromising of the whole network. Furthermore, Amazon 
was only one of several sites to suffer this type of attack in the period of just a few months, and it was not in bad 


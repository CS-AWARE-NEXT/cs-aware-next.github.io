+++
title = "nhancing your security with open-source tools"
date = "2023-08-29T12:00:00+02:00"
tags = ["cybersecurity","open source"]
categories = ["all","status"]
description = "nhancing your security with open-source tools"
banner = "img/cs-aware.png"
authors = ["Alsu"]
+++
## Enhancing your security with open-source tools

With cybersecurity gaining increased attention in Italy, it has emerged as the top priority for digital investment among businesses in 2023. Notably, both large enterprises and SMEs recognize the significance of robust cybersecurity measures. Recent data reveals that a staggering 61% of organisations with over 250 employees have chosen to boost their cybersecurity budgets in the past year. Moreover, the Italian cybersecurity market is projected to witness remarkable growth, reaching a value of 1.86 billion euros in 2022, reflecting an exceptional acceleration of +18% compared to the previous year. In this article, we delve into the realm of monitoring and analysis, exploring the potential of open-source solutions to strengthen cybersecurity defences and address the evolving challenges faced by Italian organisations.
Fluentd

The collection and analysis of logs is an indispensable part of detecting potential threats to systems and networks. The collected logs need to be stored, as they are needed for a variety of purposes: debugging programs, analysing incidents, as a help for the technical support service, etc. In addition, it is sometimes necessary to provide the ability to search the entire retrieved data.

Fluentd, a popular open-source data collector, collects logs from various sources and passes them on to other applications for further processing.

The process of collecting and analysing logs using Fluentd can be represented as follows:


Caption: Illustration showcasing Fluentd's data collection capabilities.

Image Source: Image sourced from the official Fluentd documentation [1].


The main advantages of Fluentd are the following:

Low system resource requirements. 
Unified logging format. Fluentd converts data received from various sources into JSON format. This helps solve the problem of collecting logs from various systems and opens up wide opportunities for integration with other software solutions.
Convenient architecture. The Fluentd architecture allows you to extend the existing set of functions with the help of numerous plugins, with which you can connect new data sources and display data in various formats.
Ability to integrate with various programming languages. Fluentd can receive logs from Python, Ruby, PHP, Perl, Node.JS, Java, and Scala applications.



Fluentd is distributed free of charge under the Apache 2.0 licence. The project is well-documented and updated.


Suricata
Suricata is an open-source project focused on solving basic computer security problems. In particular, it includes an intrusion detection system, an intrusion prevention system, and a network security monitoring tool.

Suricata offers the flexibility to configure it to receive alerts only, so one can focus on threat detection without blocking network traffic. The tool is useful on bare metal or within AWS with the traffic mirroring.
Zeek

Zeek is another open-source intrusion detection system and network security monitoring tool that can detect anomalies such as suspicious or dangerous activities.  In addition to rule exceptions, Zeek captures metadata to provide context for unusual network behaviour. This allows analysts to examine protocols, packet headers, and domain names, revealing valuable insights about potential threats.


Conclusion

Fluentd, Suricata, and Zeek exemplify the power of open-source innovation, providing powerful capabilities for log collection, network intrusion detection, and network monitoring, respectively. By adopting these open-source tools, organisations can enhance their ability to detect, analyse, and respond to potential cyber threats in real-time, bolstering their overall cybersecurity posture. The collaborative nature of open-source development ensures that these tools continue to evolve to meet the evolving challenges of the cybersecurity landscape.


[1] Official Fluentd documentation: https://www.fluentd.org/architecture



This article from Julie Haney of NIST deals with some of the misconceptions and pitfalls that cyber security professionals fall victim to. These pitfalls reflect a tendency in the cyber security community “to focus and depend on technology to solve today’s security problems while at the same time failing to appreciate the human element: the individual and social factors affecting security adoption.” 

To appreciate the importance of the human element in cyber security, Haney suggests it would be best to understand the concepts of usability and usable cyber security.
The International Organization for Standardization definition of usability is ‘the extent to which people can use systems, products, and services with effectiveness, efficiency, and satisfaction to accomplish their goals in a specified context of use’.  

In the context of cyber security, systems, products, and services can actually be many different things.  In a similar fashion, Users can seen as people involved in or affected by “interactions with the systems, products and services.”

### Usable cyber security

Hany quotes a report of the U.S. Department of Homeland Security that identified 11 hard problems in information security research, one of which was “usable security”. 
The definition is still relevant today:

‘Security must be usable by persons ranging from nontechnical users to experts and system administrators. Furthermore, systems must be usable while maintaining security. In the absence of usable security, there is ultimately no effective security.

“Usable security” includes not just usability but also extends to considering the “perceptions, relationships and behaviours of people when engaging with security.” The focus is, Haney asserts,  on the human element. Most importantly, usable security should be an enabler, not an obstacle, to cyber security. The goal of usable security programs should be to develop systems, products, and services that are “usable and result in improved security outcomes.”

Haney notes that many organisations and professionals in cyber security attach a certain importance to the human element, the cyber security fields is perceived as “technology-centric by nature” and the ultimate solutions to security issues. Haney quotes one cyber security professional: ‘Humans have always been a big part of the computing picture, but for some reason, we always thought only technology solutions alone can fix or prevent issues … That is not a workable strategy’ 

Few security professional seem to have had much formal or professional training regarding the human element or those non-technical skills like “security risk communication, interpersonal skills or usability that all tend to facilitate interaction with non-experts.  Adopting a human-centric approach is perceived often as resource intensive and an obstacle to implementing security efficiently.

Finally, Haney suggests that cyber security professionals may well hold some unintended misconceptions about the role of the human and the people they are supposed to be helping.
Haney outlined the following “pitfalls” for cybersecurity professionals:

### Pitfall #1: Assuming people are stupid. 

The belief that ‘users are the weakest link’ or ‘users are stupid’ is prevalent throughout the cyber security community as a result of an “unhealthy, ‘us versus them’ relationship between cyber security professionals and the people they are ultimately tasked to support”.
Aim to empower, Haney suggests, instead of a ‘blame game’, focus on empowering users to be active, capable partners in cyber security. and seek to move beyond the ‘us versus them’ mentality. 

### PITFALL #2: Not tailoring communications to the audience. 
Basically, the issue is that it is not unusual for cyber security professionals to have a difficult time translating technical information into a language understandable to their intended audience.

Be context aware: Being aware of your audience, Haney notes,  is a crucial first step in effective communication. Seek to Identify users, their skill levels, constraints, values and environments where users tend to interact with cyber security systems, products and services. 

### PITFALL #3: Unintentionally creating insider threats due to poor usability. 
Solutions that are limited to cyber security without considering usability can backfire. In environments where users may be already pushed to their limits by time pressures or other distractions, unusable security can increase user burden. 
Do basic usability testing  and provide tools and “actionable guidance to help people. Think about what can be done to lessen the burden on end users so that they are not forced to make decisions they may not be ill equipped to make,

### PITFALL #4: Having too much security. 
The most secure solution may not be necessary in every situation and may be impractical from both a resource and usability perspective.35 Overly rigid and restrictive security rules and solutions often create the illusion of security but may result in unanticipated negative consequences for both technical and end users.
Take a risk-based approach and avoid a ‘one-size-fits-all’ stance on what security solutions are implemented. Performing a risk assessment  can help determine what level of cyber security is appropriate for the environment.

Understand and support the capability of users and seek to understand how well the users are equipped to implement and react to the security measures. Furthermore, attempt to understand the current constraints and pressures of end users and how added security processes may negatively affect their work

### PITFALL #5: Depending on punitive measures or negative messaging to get users to comply.
Many organisation resort to penalising measures or focus on negative messaging to convince users to comply with recommended security practices.
Motivating and empowering people to have “confidence in their ability to do something about a possible threat” is an important step. Likewise, taking a collaborative, rather than punitive, approach can also be effective in encouraging the adoption of security practices.

### PITFALL #6: Not considering User-Centric measurements of effectiveness.
Collecting meaningful security related measurements can be challenging.  The return on investment is often being difficult to measure. Unfortunately, organisations may neglect, for a variety of motives,  to seek out data about user behaviours and attitudes. Without this data, organisations are left in the dark about areas in which employees are doing well or shortfalls for which they may need more support. 

### Concluding remarks
Haney argues having usable security programs in place will allow organisations  to develop products and services that are “usable and result in improved security outcomes.”  Clearly, the focus needs to be not just on technological needs but also on social and economic aspects.

### References
https://govwhitepapers.com/whitepapers/users-are-not-stupid-six-cyber-security-pitfalls-overturned Julie Haney.  National Institute of Standards and Technology (NIST)


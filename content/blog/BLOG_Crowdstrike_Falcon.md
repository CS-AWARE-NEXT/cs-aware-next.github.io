+++
title = "The Crowdstrike Falcon outage"
date = "2024-07-24T13:00:00+02:00" ## please change and see the T separates Date and Time
tags = ["Outage", "Crowdstrike", "Falcon", "Windows"]
categories = ["all"]
description = "The Crowdstrike Falcon outage"
banner = "img/cs-aware.png"
authors = ["University of Oulu"]
+++


A faulty update was distributed to a cybersecurity software called The Falcon Sensor, provided by the company Crowdstrike. The botched update to the configuration files of the kernel-level vulnerability scanner caused an out-of-bounds memory read operation that resulted in affected machines booting over and over again. The fault was found and a fix was distributed within 12 hours, but damage had already been caused. Manually fixing the affected machines would take a lot longer. A total of over 8.5 million Windows systems had crashed, causing a multitude of different businesses to have their services to be hindered or even completely halted, including airlines, banks, different government agencies, railway traffic, and media companies.
 
The financial impact on Crowdstrike will be significant, not only in terms of the immediate costs associated with the upcoming lawsuits, but also potential long-term damage to their reputation and customer trust.

In the wake of the incident, several key lessons emerged for both industries and governments. The risk assessment in this case has clearly failed to some degree, and will be the thing companies should address. The importance of rigorous testing and validation of updates before deployment should also be assessed not only in Crowdstrike, but also other companies providing similiar software. The incident highlighted the need for robust contingency planning. Businesses were reminded of the importance of having backup systems and disaster recovery plans in place to mitigate the impact of unexpected disruptions. 

The Crowdstrike Falcon Sensor update fiasco is and was a stark reminder of the vulnerabilities inherent in our increasingly digital world. While the immediate fallout was quite severe, the lessons learned promise a move toward a more resilient and vigilant approach to supply chain and system security and robustness. As software-dependent businesses and software providers alike adapt and evolve, the hope is that such incidents become rarer the more time passes.


https://www.crowdstrike.com/falcon-content-update-remediation-and-guidance-hub/
https://www.scmp.com/news/world/article/3271419/crowdstrike-outage-cost-economy-tens-billions-dollars-and-firms-want-recoup-losses
https://www.crowdstrike.com/blog/falcon-update-for-windows-hosts-technical-details/





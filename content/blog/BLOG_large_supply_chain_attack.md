+++
title = "Large supply chain attack targeting Node Package Manager"
date = "2025-09-22T08:00:00+02:00"
tags = ["Cybersecurity", "Cyberattack"]
categories = ["all"]
description = "Large supply chain attack targeting Node Package Manager"
banner = "img/cs-aware.png"
authors = ["Juho Bruun"]
+++

On September 15th, a supply chain attack targeting the Node Package Manager (npm) ecosystem was discovered. A package maintainer's account was compromised and malicious code was injected into widely used JavaScript packages. One of the payloads injected was a worm-type malware known as Shai-Hulud. It was also deduced by Palo Alto Networks unit 42 that for some of the bash scripts used in the attack, an LLM was used as a co-author. 

This attack targeting the open-source community behind npm highlights the need for sound cybersecurity measures even in high-trust environments like open-source development communities. Malware like the Shai-Hulud seen in this attack thrive in such environments and only need to compromise a single high enough agency account to deploy a wide ranging attack. 


https://www.trendmicro.com/en_us/research/25/i/npm-supply-chain-attack.html
https://unit42.paloaltonetworks.com/npm-supply-chain-attack/
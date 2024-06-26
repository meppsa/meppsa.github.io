---
project: true
layout: post
title:  "Network Overhaul Part 1"
date:   2024-06-26 11:09:03 +0300
categories: projects, network, configuration, outline
---
## Introduction

Today I would like to outline a new project to overhaul my network configuration. I will openly admit that this project has been inspired by some discrepancies and inconsistencies that I have found after coming back from vaction. After coming back from vacation earlier this week, I found that my wirelessly connected devices were cutting in and out from the connection to the WAPs. Once I viewed the running configuration on my switch I was able to notice that the port that the WAP was plugged into had lost it's configuration. I realized that I must not have saved the configuration and that the power must have gone out when I was away. I was able to configure the port to trunk mode and set the allowed VLAN list. After doing so, the wireless devices that previously had trouble were now connecting consistently and without fail. I can not have this happen again and certainly not in a production environment. I admit that I have much to learn, even with an entry level networking certification, I have to dial in my focus to practice secure configurations and standard operating procedures. I figure, the information for advanced networking practices are out there so why not take it to the next level? I'll outline my objectives here in part 1 and follow up with my next steps and phases in subsequent project posts. 

## Objectives

1) Utilize NSA's Network Infrastructure Security Guide to reference against the configurations on my networked devices. The guide can be found here: [media.defense.gov](https://media.defense.gov/2022/Jun/15/2003018261/-1/-1/0/CTR_NSA_NETWORK_INFRASTRUCTURE_SECURITY_GUIDE_20220615.PDF). The Center for Internet Security also maintains benchmarks and guides on different devices and operating systems, they can be found here: [cisecurity.org](https://www.cisecurity.org/cis-benchmarks). 

2) Update all networked device's operating systems (if applicable).

3) Establish a DMZ within the network. 

4) Install Kali Purple on a NUC mini-pc for future Cybersecurity learning and projects.

## Summary

Utilizing secure configurations is paramount to protecting and allowing for continuos use of information and data systems. This has led me to research and look for what I can do to protect information and traffic on my home network. All future posts regarding this project will be in subsequent parts with this first post being part 1. Stay tuned. 



---
project: true
layout: post
title:  "Installing Wazuh"
date:   2024-06-19 11:09:03 +0300
categories: projects, wazuh, EDR, reporting, analytics
---
Choosing Wazuh as my go-to endpoint detection, reponse, and monitoring platform came down to a few reasons, one being that it is open-source, no need to worry about shelling away money and the second being that it is easy to install, learn, and improve upon. For the installation, I ended up creating a Hyper-V VM inside my instance of Windows Server 2012 R2. Keeping in mind that I had to use the necessary amount of resources for what Wazuh requires. I went with a 2 core proceessor, 8 GB of RAM, and 500 GB of storage. That way I could install Wazuh and leave room for other services if desired. For the operating system, Wazuh outlines that it will run on most distros of Linux. I installed the latest LTS release of Ubuntu. In order to suceessfully boot using the Ubuntu ISO, I had to disable secure boot inside the VM settings. 

Setting up Ubuntu for the first time is incredibly easy and smooth. Everything is well explained and laid out neatly, nothing ever left me wondering, what should I configure here? Once the setup was completed, I was able to install Wazuh by following their official installation guide. Essentially the steps were as follows: Install the agent using curl on the command line, take note of the output credentials, and then login to the web interface.



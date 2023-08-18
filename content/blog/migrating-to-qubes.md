+++
title = "Migrating to Qubes OS"
date = "2023-08-17T18:00:00-00:00"
author = "OniSec"
authorTwitter = "" #do not include @
cover = ""
tags = ["Qubes OS", "Linux", "Virtualization", "Home Lab", "Knowledge Garden"]
keywords = ["", ""]
description = ""
showFullContent = false
readingTime = false
hideComments = false
color = "" #color from the theme settings
+++

Greetings,

At this time, the blog and knowledge garden are a work-in-progress as I have migrated from Manjaro Linux to Qubes OS as my daily driver. I still plan on working on a tailored Arch install, and eventually Gentoo, but for the time being those two projects are not as high priority as the migration to Qubes.

Qubes OS has a reputation for being used for what some would call paranoid security. I see some value in the capabilities as a security professional, but I am actually on Qubes OS to use those capabilities for a different purpose.

Specifically, I am using Qubes OS to build a home lab. Why? Well, I'm a bit limited in the ability to house a rackmount server, a cloud based lab has some costs that will eventually add up, and as far as I am aware you can't run Hyper-V on a system and still be able to daily drive the same machine unless you are using Windows. (yuck) So, I am using Qubes as a hypervisor and daily driver OS.

Admittedly, this takes a good bit of getting used to. It's also a challenge getting set up in a reasonable manner with memory management, proper isolation for some things to mitigate risks. Once I have gotten set up and have taken care of some higher priorities, I will do some diagramming of my configuration, explain why I chose the configuration I went with, and provide a guide on how to replicate my setup so it can be scrutinized by the Qubes community and anyone else.

Speaking of the Qubes community, wow. This is a wonderful community of likeminded individuals who have probably gone through the same process as you may if you decide to try Qubes. For me, it seems I can just explain my thought process and goal and people just come through and say hey it's been done, here's the github repo for it. Others provide general instructions to accomplish the goals I have. It is pretty awesome.

With that in mind, I'm still in the process of setting up my workspace. Once I am done my priority will be getting the Knowledge Garden cleaned up a bit so I can start adding writeups, documenting the attack lifecycle, and creating a framework within the knowledge garden that will help keep things organized. I will be looking to provide a general overview of the attack lifecycle and have sections that go into details for methodology.

I will be adding a separate section that goes over different attack types, hopefully I can showcase vulnerable code, exploit examples, and how you would remediate those vulnerabilities. I am still debating on when to start worrying about CWEs, ATT&CK Matrix, but those will come in due time.

The intention for all of this is to learn the material well enough to teach and showcase that knowledge while creating a learning resource for the the infosec community or even youth looking to learn and hopefully use what they learn for good.

Thanks for reading and hopefully you'll enjoy the content going forward.

OniSec
---
title: "Precautions for Investigations"
subtitle: "Steps to take to protect yourself and your agency."
date: 2022-11-27T23:06:00-05:00
draft: false
author: "Rich"
authorLink: "https://iotdetective.net"
description: ""
tags: [Investigations,Precautions]
categories: [OSINT]
featuredImage: "https://images.unsplash.com/photo-1557075831-9227ec7d0097?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwxMTc3M3wwfDF8c2VhcmNofDIwfHxwcmVjYXV0aW9uc3xlbnwwfHx8fDE2NTYxMzEzNzU&ixlib=rb-1.2.1&q=80&w=2000"
---

## Digital Officer Safety

We are all ingrained with a law enforcement concern, that above all else, officer safety is key.  Investigators sometimes lose sight of what this means for them in their role.  This is mainly due to the large scale differences between patrol and investigative work, but we shouldn't underestimate the need for officer safety in all that we do.  After all, if you are hurt or injured as an investigator, you aren't there to be able to help your colleagues when they need you the most.  If you don't take the necessary precautions in an OSINT investigation, you risk, at the least, tipping off your suspect and blowing up your case. On the other hand, you also risk leaking your own personal or department information to be used by criminals.

So, let's switch gears into online officer safety, what are some considerations we need to have in mind when are conducting OSINT investigations?  I have put together a list of the things I feel are absolutely necessary when digging up information online about your investigative target.  Additionally, I have put together some options that are either paid or free for those departments with varying degrees of available funding.  Here's a side note, eventually I want to put together and build out a forum platform that is integrated with this website.  I want those of you who have experience or insight specific to these types of investigations to be able to share your own opinions, experiences, tools, etc. I am hoping to get this functionality up and running by April 2022, so keep this in mind and check back often for updates.

## 2022 Pre-OSINT Investigation Check List

1.  _Review your department policy and check with your supervisor and IT contacts before using department issued devices for OSINT research online._

This is the absolute must for any investigator, you need to know the limitations that are in place based on policy. Transparent communications with your supervisors on the topic about what you need and why you need it is always better than asking for forgiveness later when devices on your network get locked with ransomware and department data is leaked..

When you start here, you have the best chance at success, because your department's IT staff is typically more willing to work with you to set up devices off your CJIS network that are specifically for use with online investigations. They would much rather you use these dedicated devices and networks than infecting a machine with sensitive data attached.

Doing this ahead of time increases your department's overall cyber security posture and helps show you know what your doing and how important it is to be secure when conducting online investigations.

2.  _Use a dedicated computer for OSINT investigations, if this is not possible utilize virtual machines disconnected from your CJIS Network._

Have a dedicated laptop or desktop that is on a separate network than your CJIS devices with the ability to run virtual machines. What are virtual machines? I'll get into that in the next bullet point, for now just know that one of the requirements of a good online investigative workstation you need to be able to have a machine that can run virtual machines. Most devices built within the past 10 years will likely have this ability, check with your IT department to see if you can recycle a device taken out of commission recently. After all, this isn't a device you need to have the latest operating system running on or have to worry about security patches, etc. This is a device which doesn't touch your regular network that you don't care about if the device dies or gets infected by malware. This machine should be considered disposable, your IT department can always wipe the machine and start over if problems arise without any concern for lost data or a security breach.

Here is the paid alternative: Have your IT department look into setting up an online instance through AWS, Linode,or some other cloud service provider with the ability to host virtual machines. My suggestion would be a service like Kasm with is a service based on Docker that allows the investigator to spin up instances of Google Chrome, Firefox, Brave, or TOR Browser that are easily destroyed after you're done with your investigation. Additionally, you can spin up full instances of a Linux desktop to conduct your investigation as if sitting at a workstation with access to any took you wish to utilize during your investigation. NetworkChuck has a great video on Kasm that he recently published on his YouTube channel, check it out here:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/U7e-mcJdZok/0.jpg)](https://www.youtube.com/watch?v=U7e-mcJdZok)‌

3.  _Deploy each investigation in a new virtual environment._

A virtual machine or virtual environment is simply a computer within a computer. With advancements in computing, you can now use the same device and run multiple operatings systems on one machine. Each operating system has the ability to make use of the resources of the computer itself like RAM and hard drive space. Ideally, you want a virtual machine that reverts back to its original form each time you start the machine so that it is fresh.

Even Windows 10 devices come pre-packaged with the ability to run a virtual machine, called a "sandbox". This could be a simple solution if you have a Windows 10 device available for recycle within your department. Here is a step by step video from How-To Desktop:

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/HRxbBCGQPR0/0.jpg)](https://www.youtube.com/watch?v=HRxbBCGQPR0)

4.  _Use covert accounts and never link accounts between two covert accounts or between a covert account and your personal account._

Establish online identities that you can use to conduct your OSINT investigation that do not reveal your own personal information or data. Next week I am going to have a full walk-through on how to set up a sample covert account. It is always easier to stick the accounts you already have established, so if you have accounts established already the key here is never to link two different accounts together so that identities stay separate and to never use your personal or work accounts to conduct research on a subject online. Why? Because you risk loosing access to your covert accounts if the platform suspects your are acting suspicious during your investigations. If you use your personal accounts you risk appearing as a "friend suggestion" or as a recent visitor to your suspects profile.

5.  _Validate your collected information through multiple sources before you act on that intelligence._

This should go without saying, but I will say it anyway. Always make sure you validate any information you have learned through multiple sources before you rely on that information. OSINT is rarely ever validated as accurate when you first collect the information, unless you already have the information available to confirm. For example, if you collect a telephone number you feel is accurate for a suspect. Why not utilize other open source tools to validate this, such as SlyDial to dial the number and listen to the assigned voicemail for the recording of your suspects name or voicemail box message.

Do what you can to make sure the information you're using is otherwise validated. Every step you take to validate this information, such as a subpoena for subscriber data related to a telephone number, helps boulster your case in terms of probable cause for an arrest or search warrant

## Review

Always take steps to make sure your information stays secure, your network stays secure, and you're not giving away the tactical advantage to the suspect of your OSINT investigation.  Additionally, make sure you take steps to validate the information you learn before acting on that information or including that information within a report or affidavit. Feel lost at this point?  Don't worry, part of my goal for this blog will be a step-by-step overview of each of the bullet points above in a simple terms.
---
title: "Windows Sandbox for Investigators"
subtitle: "What is it and how can I use it?"
date: 2022-11-27T23:17:00-05:00
draft: false
author: "Rich"
authorLink: "https://iotdetective.net"
description: ""
tags: [Windows-Sandbox]
categories: [OSINT]
featuredImage: "https://images.unsplash.com/photo-1559667326-e5edc968aeac?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=MnwxMTc3M3wwfDF8c2VhcmNofDJ8fHNhbmRib3h8ZW58MHx8fHwxNjU2MTMxMTYx&ixlib=rb-1.2.1&q=80&w=2000"
---

## The Sandbox

I'm going to continue on the path of sanitization when it comes to conducting online investigations.  Every training I have even attended that deals with online open source investigations emphasizes the need to obfuscate your online identity. In plain language, we need to hide our tracks online because when we fail to do so, we may disclose to the subject of our investigations that they are the subject of an investigation. Additionally, we need to keep our accounts separated from our own machines to prevent blending and the loss of online covert accounts used to conduct OSINT investigations.  So what is a fast solution to this problem?

Well, the answer is that there are many, but I like simple options that all of us may have access to with the least amount of headache and troubleshooting when it comes to investigations.  My answer is Windows Sandbox in conjunction with a free VPN client, RiseUp.  Initial configuration warning here, you will most likely need to have your information technology administrator set this up, at least initially for you, especially if you are not given any admin rights to a department issued computer.  However, even with a dedicated investigative machine within the department, Windows Sandbox should be set up.  Windows Sandbox creates a virtualized environment of Windows that can be trashed when your investigation is completed, it helps protect your online covert accounts and presents a clean installation of Windows for every investigation you conduct.

## Here's the How-To:

Step 1: Ensure your hardware supports virtualization and enable virtualization in the BIOS if needed.  Most devices manufactured in the last 5 years or so typically come with virtualization enabled by default within the bios.  If not, here is a YouTube video from Triple-A Tech Solutions:

‌[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/MOuTxfzCvMY/0.jpg)](https://www.youtube.com/watch?v=MOuTxfzCvMY)

Step 2: Make sure your Windows 10 or Windows 11 machine is fully updated with all security and feature updates.

Step 3: Enable Windows Sandbox feature in Windows.  Here's another walkthrough video on YouTube, this one from Techademics.
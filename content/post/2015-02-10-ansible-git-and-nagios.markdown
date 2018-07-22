---
author: 'mark david mcCreary'
date: 2015-02-10 22:45:24+00:00
draft: false
title: Ansible, Git and Nagios
type: post
url: /ansible-git-and-nagios/
---

It's February 10 2015, and I see my last post was January 23, 2014.  What happened ?




 




I started a relatively simple project of converting my configuration management from a home grown system to Ansible, a new configuration management system.  Ansible is a very nice package that is simple and powerful.




 




Before I would run a few steps by hand, and then transfer a bunch of files and configuration scripts automatically.  Run a few steps by hand, transfer some more files via script.




 




Ansible allows me to automate everything, from booting up a recent Ubuntu AWS server image, to the final step of saving the newly built machine as an Amazon image.  Plus, when I change a configuration file or program, I can rerun the Ansible Playbook and only the changes will get replaced, the other steps will be bypassed because they are not needed.




 




I love Ansible.




 




Git is a version control system, typically used for managing source code.  When I first started programming mainframes, we used keypunch cards and Panvalet was our source code control package.




 




That was 1977, and since that first job, I’ve never used a version control system.  And I worked in a lot of corporate shops where they should have had such tools.  But most corporations were Cowboy Programmer shops, and version control and testing were rarely a concern.




 




The past 5 or 10 years, Time Machine has been my version control system, and it worked for me.  Every time I screwed something up, and need to go back a version or two, Time Machine had the document.  Thanks Apple !




 




Nagios is an open source monitoring system, and I’ve been using it for a long time, but in a fairly limited fashion.  Just monitoring if my servers were up and if I had enough disk space.  But after a couple of small disasters around Labor Day, I decided I need to monitor everything I could find.




 




And the strength of Nagios is that there are hundreds and thousands of simple plugins that do monitor just about anything you can name.  Thanks to hundreds and thousands of programmers scratching an itch for themselves, and then taking the extra time to make it available to guys like me.  Thanks guys.




 




So configuration management, version control and monitoring are all important tools in running a software system, no doubt about it.  But why did it take me 12 months to accomplish these tasks.  I'm very happy with the results, but I'm also very critical of the amount of time I spent.

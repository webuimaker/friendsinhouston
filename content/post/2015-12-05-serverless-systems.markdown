---
author: 'mark david mcCreary'
date: 2015-12-05 17:39:18+00:00
draft: false
title: Serverless Systems
type: post
url: /serverless-systems/
---

The Amazon Cloud has changed everything, and I’m very grateful for fantastic tools this little bookstore in Seattle has brought to the IT World. While Sun Microsystems went out of business, and IBM keeps downsizing, Amazon has started with a blank sheet of paper and just keeps adding managed services at fantastic prices.




I used to run my own servers out of my kitchen, but in 2008 Hurricane Ike roared through Houston and knocked out power for many days. And my backup generator was too small to keep my approximately 25 servers running continuously. So in 2009 I started migrating my software up to the Amazon Cloud. Back then they only servers they had were instance based versions, which meant that when a crash occured, all data on the hard disk was lost.




Later on they came out with EBS volumes which separated the hard disk from the CPU, so that the data on the hard disk could be a bit more resilient.




And they have kept adding new services ranging from DNS to queues to data streams to auto scaling to load balancing to monitoring. And those are just the services I use, and there are dozens and dozens more that I don’t need or even understand.




Their latest service that I’m drolling over is Lambda, which are serverless functions. Not that the functions don’t need a computer to run on, it’s just that it does not have to be my server. Amazon has dedicated a bunch of hardware to run my software, and they will charge me for the number of milliseconds it takes to run.




So that means I don’t have to provision servers, update operating systems, update software packages or back those up servers. And I don’t have to add more capacity when things get busy, Amazon is going to provide that capacity for me, behind the scenes.




Now this does not mean that my system will never go down, it just means that I’ve transferred that responsibility to Amazon. And they are much better qualified to keeping operating systems, servers, monitoring services, etc etc up and running that I am.




So this changes everything once again. Amazon is taking over a lot of critical low level tasks that need highly skilled people to operate them. And everybody else gets to move up a level and focus more on doing things that are more visible to the paying customer.




My existing software is not ready to convert into Lambda functions. Instead of big programs with thousands of lines of code, I need to chop that up into dozens and dozens of discrete functions. And I need to build a RESTful API interface to those discrete functions.




That’s not going to be rocket science, as I already have working software, but it’s going to take a lot of time to get from here to there.




And if I do get there, then I have a system that is very scalable, and very robust.




So almost all software in the future is going to be serverless, and I’m sure other cloud providers will come out with their own versions of Lambda.




Since most listserv software is 20 or 30 years old, I doubt that many of those packages are going to be converted. And I’m not sure the listserv market is big enough that somebody new is going to create a new serverless solution from scratch.




So I have a chance to be the first serverless listserv system out there.

---
author: 'mark david mcCreary'
date: 2013-11-16 20:58:42+00:00
draft: false
title: State Of The System, Circa End Of 2013
type: post
url: /state-of-the-system-circa-end-of-2013/
---

[![Mail-List System Mindmap](/uploads/2013/12/Mail-List-System-Mindmap-286x300.png)
](/uploads/2013/12/Mail-List-System-Mindmap.png)Mail-List.com is easy to use, has lots of documentation and runs smoothly for people with large or small mailing lists. In fact, the bigger the list, the more they need Mail-List.com because of our great deliverability and extensive set of features.

However, for people that manage many different lists, the current system forces them to log in and out of each list to manage it. So if they want to change a moderator on all of their lists, it's a tedious process.

In addition, some groups would like us to provide a membership database, where they would keep all of their member's details. Their biggest problem is identifying who is on their list based on the email address, since some people might join with their work address, and subscribe to the list with their home email address. Or vice versa.

An integrated billing system would be nice, more from our point of view than theirs.

While we are running in the cloud, we are not taking advantage of some of the best features of the cloud platforms, like message queueing and auto scaling.

On the positive side, all of my programs have been replaced by RG II's programs, and he is a world class programmer, especially brilliant with regular expressions. A lot of difficulties in processing email is the large number of variations due to loose and ambiguous specifications from many years ago, combined with the multitude of implementations of Message Transfer Agents (MTA) and Mail User Agents (MUA).

[![mail-filter mindmap](/uploads/2013/12/mail-filter-mindmap-300x253.png)
](/uploads/2013/12/mail-filter-mindmap.png)For example, RG II has written 3,000 lines of code, just to convert incoming email of all types into small plain text messages that are easy to read for all the subscribers. This program has 50 different functions, including translating between different character sets, trimming long top posted replies, removing boilerplate text in replies that was placed there in our footers, snipping ads and disclaimers, replacing long URL's with short URL's so they don't linewrap and processing all parts of the email against anti-virus programs.

This is not your typical mailing list system and the results are best seen in long running email conversations, because the noise and artifacts from many replies is eliminated.

In addition, we have sub systems for anonymously crowd-sourcing a knowledgebase from the email stream, web interfaces for subscription management, monitoring inbox delivery, scanning delivery logs for bogus bounce messages, searchable web archives, short term web archives, handling abuse feedback loops from the ISP's, distributed cloud storage for attachments, URL translation for blacklisted URL's, anti virus systems, and a web interface, database, and configuration system for our clients to manage their list settings.

It's a self serve system, and our clients have easy access to everything they need to run a successful mailing list.

Internally, we have our own configuration management system for setting up the various servers, like email gateways, email delivery machines, the actual listserv machines, etc. We have monitoring systems, test systems, source code control, internal documentation etc. However, we are lacking a comprehensive test network.

Each month the system delivers more than 6 million messages into inboxes, costs $1,500 in Amazon Cloud and third party service charges and requires approximately 5 hours of direct support time. The majority of that time is helping new people get comfortable with the system.

It's a very solid base upon which to expand from.

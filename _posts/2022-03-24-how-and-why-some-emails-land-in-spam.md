---
layout: post
title:  "How and Why some emails land in SPAM"
author: GG
categories: [ Sales, Marketing, Email ]
tags: [Email]
image: assets/images/why-my-email-lands-in-spam.jpg
# beforetoc: "Prism highlighter is a very powerful thing."
# toc: true
description: "Why some of my emails land in Spam. What is really in my control ? What can I do to avoid my email landing in spam"
# rating: 4.5
---
TLDR; Don't sent unsolicited emails. But if you still do then control the controllable, i.e. subject and body. 

An attempt to share some experience and understanding about why email is landing in spam. 

You may be using various email services to send email. Like Sendgrid, AWS SES, Mailchimp, Gsuite email service, etc. 

## Using email service; Things you cannot control
Typically the the email service provider would have many IPs from the IP farm to send email. Which exact IP your email uses is not in your control.

That IP may be blacklisted already or may not be. 

The email service providers would surely monitor the ips from there IP farm for being blacklisted. And would continue to take them out of the farm if blacklisted and add new one. 

This is an ongoing process for them. Email Service provider team routinely flushes out blacklisted IPs to keep business going. 

Email Service Providers put limits and checks on their customers usage in terms of bounce rate and complaint rates, so that one user of there service does not impact others adversely. 

More stricter those checks, better is the service in terms of email deliverability. 

It would be your bad luck at times when you are specifically testing the email for SPAM, if that specific email got sent out from an IP which is blacklisted. 

There is no control on which IP from the farm will be picked. 

## Some options around domain usage
Few choose to use different domains than their primary domain. These temporary domains are used only for unsolicited email purposes. 

But here too they would have to use some email service. If not AWS SES or Sendgrid of the world, then Gmail or Office365 or something else. 

Similar IP farm scenario will appear there too. 

## Email Receiving Server processing
Every email received by the email receiving server has it own rules and logic to mark the email as Spam. These Spam engines are complex and continue to evolve over time and is completely out of the control of the email sender. 

Only thing the sender can make sure is to send legitimate and personal emails. Which the sender really would open and read. 

## So what do I do then 
**Control the controllable.**   

Check your Email subject line SPAM score is 90+. Check your email body also has no issues like wrong links, big attachments. 

Test you complete email for spam and look at the report. 

Correct the things you can. Like DKIM, DMARC beyond subject and body.

## Conclusion
There is no guarantee any email service provider can provide that emails will 100% not land into spam. Same email - some may land into spam and some wont. 

## 7Targets Assistant
Assistant can do its bit of simulating humans and not send all emails at once, remember timings of each person to send emails, but assistant cannot control IP allocation. All email marketing campaigns have these nuances, but they are still cost effective compared to LinkedIn/Google campaigns where we do not come to know who clicked on emails.

Feel free to [sign-up](https://7targets.ai/sign-up.html?utm_medium=zoho-vs-7ts&utm_source=7tsblogs) and give it a try. Or simply book a meeting with us to know more.
---
title: Phishing Done Right
date: 2017-05-04 01:05:00 -04:00
tags:
- tech
image: "/uploads/gdocphish1.png"
---

Oh boy, today I got a notification from New York University's Chief Information Officer about a phishing scam happening to many universities nation wide, I was both concerned and excited. In order for such a phishing campaign to be successful and got past most difficulties, it must be well designed!

## The New York University Memo
![gdocmemo.PNG](/uploads/gdocmemo.PNG)

## What is phishing?
For those that are unfamiliar with the term "phishing," it is basically the act of impersonating a reputable company by sending something that looks legitimate but turns out revealing sensitive information about the person who wrongfully believed it to be originating from said reputable company. The sensitive information may contain your contacts, credit card information, your address, or even your passwords. Each phishing attack targets different information, so you have to judge it on a case by case basis to see what might be compromised if you did fall for the phishing attack.

Let's dive into the technicalities of the actual phishing scam, not that I was successfully phished or anything (my friends would know since had I authorized, everyone on my contact list would've gotten the phishing email too).

## Things that this phishing attack did right:
1. It uses the existing and legitimate Google login system
2. It uses an app name that seems legitimate (Google Docs)
3. Gains access to your account by OAuth and propagates itself through contacts
4. Since it is an OAuth application, you have already granted it permission, so it ignores all MFA securities
5. Hard to detect for normal users

## How could I have detected the phish?
Well, you had to be very diligent about everything you receive. Google Docs is a Google Suite App, and it should never ever have to ask you for permission to use it. Even if Google made it so that it did, the other way to detect the phishing trick was to click on the actual application name to see the website link.

## Did you get the email?
I actually did not get the email, I guess Google shut it down pretty quickly. I only learned about this email because a co-worker of mine received it and sent it directly to his Trash (good on him)!

## Will this happen again?
I mean, Google only shut down the phishing user's account, but did not actually block off the method of doing said phishing method (as of this post). One way for Google to counteract to this is to not allow similar names for OAuth apps that are also their native apps.

Or they could just slap a giant warning on the OAuth page telling users to check the actual website of the application they are giving permission to. Perhaps maybe even put a human on top of approving OAuth application submissions. (But this costs time and money)

So really there is no "great" way to solve this problem, only workarounds or really gimmicky hacks. Even the page that Google took you to when they shut down the OAuth on the account was a temporary page. Everything was done in a rush, but at least people won't get phished anymore from that account.

Yay?
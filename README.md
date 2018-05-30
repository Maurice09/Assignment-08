# Assignment-08

# Project 8 - Pentesting Live Targets

Time spent: **6** hours spent in total

> Objective: Identify vulnerabilities in three different versions of the Globitek website: blue, green, and red.

The six possible exploits are:
* Username Enumeration
* Insecure Direct Object Reference (IDOR)
* SQL Injection (SQLi)
* Cross-Site Scripting (XSS)
* Cross-Site Request Forgery (CSRF)
* Session Hijacking/Fixation

Each version of the site has been given two of the six vulnerabilities. (In other words, all six of the exploits should be assignable to one of the sites.)

## Blue

Vulnerability #1: SQL Injection (SQLi)

https://github.com/Maurice09/Assignment-08/blob/master/SQLi.gif?raw=true

Vulnerability #2: Session Hijacking/Fixation

https://github.com/Maurice09/Assignment-08/blob/master/Session%20Hijacking_.gif

## Green

Vulnerability #1: Cross-Site Scripting (XSS)

https://github.com/Maurice09/Assignment-08/blob/master/XSS.gif?raw=true

Vulnerability #2: Username Enumeration

https://github.com/Maurice09/Assignment-08/blob/master/Username%20Enumeration.gif?raw=true

## Red
Vulnerability #1: Insecure Direct Object Reference (IDOR)

https://github.com/Maurice09/Assignment-08/blob/master/Insecure%20Direct%20Object%20Reference.gif?raw=true

Vulnerability #2: Cross-Site Request Forgery (CSRF)

https://github.com/Maurice09/Assignment-08/blob/master/Cross-Site%20Request%20Forgery.gif?raw=true

## Notes
In the process...

## Which attacks were easiest to execute? Which were the most difficult?

The list is listed from easiest to most difficult: SQLi, Username Enumeration, IDOR, Session Hijacking, XSS, CSRF

## What is a good rule of thumb which would prevent accidentally username enumeration vulnerabilities like the one created here?
 
Given details about which username is valid and which is not can be dangerous. Showing an error for all wrong usernames can be          bad. So, to avoid this, one needs to give no validation of an active account. 

## Since you should be somewhat familiar with the CMS and how it was coded, can you think of another resource which could be made vulnerable to an Insecure Direct Object Reference? What code could be removed which would expose it? (Hint: It was also the answer to the first bonus objective to the Weekly Assignment for week 3.)
  
  o	


## Many SQL Injections use OR as part of the injected code. (For example: ' OR 1=1 --'.) Could AND work just as well in place of OR? (For example: ' AND 1=1 --'.) Why or why not?

## A stored XSS attack requires patience because it could be stored for months before being triggered. Because of this, what important ingredient would an attacker most likely include in a stored XSS attack script?

## Imagine that one of your classmates is an authorized admin for the site's CMS and you are not. How would you get them to visit the self-submitting, hidden form page you created in Objective #5 (CSRF)?

##	Compare session hijacking and session fixation. Which attack do you think is easier for an attacker to execute? Why? One of them is much easier to defend against than the other. Which one and why?



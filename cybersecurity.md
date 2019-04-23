# Cyber security notes
Cyber security is not like other things where once it works it works, with cybersecurity you have to think in the negative space and make sure it only works in the ways you want it to.

The content of the readings will be on the quiz

## Three key ideas to communicate:
1.	Don’t store passwords in plain text, never do that. Never handle authentication by yourself, use an official library.
2.	Don’t trust the browser. Validate everything on the server side. You can’t trust the browser.
3.	Be aware of the libraries you are using (cases of npm packages being hacked and malware being put on them)


Topics:
- sql injection
- xss
- csrf
- password management

### Questions for each:

a.	What is it?

b.	How does one exploit it?

c.	How does one prevent it?

1.	SQL injection
a.	An injection by the user of SQL code, usually to get data
b.	If you know the SQL queries that are running
c.	Don’t use sql, use prepared statements

2.	CSRF
a.	The website tricks the user to change state
b.	Like a button that says one thing but does another thing
c.	The http is correct and coming from the right place
3.	XSS	
a.	Client extension tag. Messes with your javascript. Send you stuff that aren’t plain text and can perform a javascript task
b.	N/a
c.	Filter some data, use javascript tester, from users to other users. 


SQL injection line 56
86-91 they are just inserting the usernames
Line 56: SQLI
Line 23: SQLI, but it uses hash of the password which is not that bad

File:
https://github.com/JasonHinds13/hackable/blob/master/main.py#L87


### Notes from NYT article:
It is very hard to teach people how to succeed in cyber security, because successful students in school are using not well fitted to the rebellious mindset that is required for someone to succeed in cybersecurity. Some teachers have created assignments like asking students to cheat to help them think creatively to develop the mindset required for cyber security.

### Schneier: 
Like the NYT article, the main point is about having the security mindset and thinking about how anything can be exploited to not work the way it should work.

### Newscientist:
There are many vulnerabilities on UK websites, mostly caused by outdated software and protocols, and through not looking through the CVE list of vulnerabilities. 



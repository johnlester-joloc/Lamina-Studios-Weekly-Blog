# WEEK 3 (June 22-26)
---

# Day 1

For the first day of week 3, I spent the day watching lecture videos about social engineering and phishing attacks. This is for the Weekly Task 4 lecture report.
I was introduced to a cool new cybersecurity tool that I will definitely not use to prank my thesis groupmates, and it's called Social Engineering Toolkit. This neat
little CLI tool can be used to create and simulate social engineering attacks. This is typically used for testing organization security, but of course it can also be
used maliciously. Everything in cybersecurity is a double-edged sword, after all. Anyways, I finished the lecture report in no time because I planned to finish Weekl Tasks
4-6 for this week.

*Documentation*
![](https://github.com/user-attachments/assets/b447440b-fe28-49f7-a5a8-e520e8a1b4bb)

---

# Day 2

I spent Day 2 doing Weekly Task 4. I have to simulate a phishing attack, which is illegal by the way. Of course, the target victim is me, I phished myself for this activity.
This is when I discovered just how powerful SET is. I browsed for phishing tutorials and discovered that SET can **clone websites**. This was surprising to me and shows
just how scary cyber attacks can be. The idea is to clone the website's login page and when the target types their credentials, it gets logged in SET. I tested this by
replicating an old Twitter login page, hosted the fake website on Kali Linux, and typed a fake username and password which was logged in SET. With port forwarding and using
a domain that looks legit, attackers can easily steal credentials with this method.

After finishing this activity, I was done with Weekly Task 4.

*Documentation*
![](https://github.com/user-attachments/assets/8942dd36-8acd-4ee6-95d7-aed55fac8a6d)

---

# Day 3

Weekly Task 5 was my agenda for this week. As usual, I started by watching the lectures. It was all about web penetration testing, or as I like to call it: web
exploitation. There were many tricks discussed such as SQL injection, code injection, etc., which are all outdated at this point thanks to modern cloud computing
services such as AWS and Cloudflare. I finished the lectures and created the lecture report after.

*Documentation*
![](https://github.com/user-attachments/assets/c0485255-c398-4bd0-b200-9a55f66d0cb5)


---

# Day 4

For Day 4, I focused on the activity itself. I had to setup Damn Vulnerable Web Application (DVWA) on an Ubuntu machine. This meant I had to install an Ubuntu 
virtual machine in VirtualBox. The setup took forever and I ended up wasting the whole day waiting for it to be mounted on VirtualBox. There were times when it was
stuck and I had to restart the process. I then realized that I didn't have to do any of this since Metasploitable 2 is an Ubuntu machine and has DVWA preinstalled.
I was already out of time so I decided to move it to day 5.

*Documentation*
![](https://github.com/user-attachments/assets/c5be29a5-af06-4e52-bdd3-5c8b825d882e)


---

# Day 5

I started Day 5 by doing what I was supposed to finish in Day 4. With DVWA already setup in Metasploitable 2, it was simply a matter of doing the activity.
I finished it in no time and decided to experiment with DVWA. You can configure the security level of DVWA and it will change how each attack strategy works. 
For example, performing an SQL injection on a low security level configuration is easy. However, if you set the security to high, it is much harder because the website
will perform input sanitization, so you have to be creative with SQL injection.

*Documentation*
![](https://github.com/user-attachments/assets/a966b8ea-1efa-48b2-8474-2f1dee13f632)


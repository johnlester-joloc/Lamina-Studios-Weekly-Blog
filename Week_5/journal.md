# WEEK 5 (July 6-10)

---

# Day 1

We received a message from the supervisor that we no longer need to finish all 13 tasks. We only needed to finish 6 weeks worth of tasks, which is 6 tasks. This was great news to me because frankly, I was already burnt out from all the tasks that I finished. This meant that I technically didn't need to do anything anymore since I am already finished with my tasks. Still, I wanted to finish a few more so that I would have something to do. Weekly Task 8 was the next task, and I decided to finish the lecture reports on day 1.

*Documentation*
![](https://github.com/user-attachments/assets/e78f6f7c-1399-4f89-bd6d-301a3e4c1596)

---

# Day 2

With the lecture reports already finished, I moved on with the task itself. It was a defense simulation task involving software hardening. The defending machine in this case is an Ubuntu machine with DVWA and LAMP stack installed. I could not use Metasploitable 2 here because that machine has a dozen vulnerabilities, and the entire point of the task is software hardening. This means I need to install Ubuntu ISO and mount it as a virtual machine. This didn't take long. I was then met with the setup process for the OS itself, and that one took too long. For some reason, it kept on freezing after installing all the needed dependencies. I had to start over several times. It didn't take long for the MyHours app to reach the 8 hour marker, meaning I have to finish the setup process for another day.

*Documentation*
![](https://github.com/user-attachments/assets/8346543d-f039-4706-81ba-627828b03b29)

---

# Day 3
After the setup process disaster form yesterday, I decided to try again. I tried different Ubuntu versions, different virtual machine settings, and it still kept on failing. Clearly, something is wrong with my hardware. I tried updating my Windows machine, and it still did not work. I asked my co-interns and they did not experience the same problem. I was once again out of time.

*Documentation*
![](https://github.com/user-attachments/assets/b24d3b29-2af9-45f1-b24f-8f07c9654a82)

---

# Day 4
I was very frustrated with the setup process failure I experienced in the previous two days. I finally realized what the problem was: my main machine only had 15 GB left. This was all because of my games auto-updating. I deleted those games for now and tried installing Ubuntu again. It finally worked. I then installed DVWA and the LAMP stack on the Ubuntu machine. I started the activity only to be met with an Apache error. Turns out, there were some errors in the Apache and SQL configuration. I spent the remainder of the day trying to figure it out but I never managed to fix it.

*Documentation*
![](https://github.com/user-attachments/assets/3c298ca4-4778-42c0-bfd4-a0b6d5453e3c)

---
# Day 5
Apparently the Ubuntu setup process failure was just an appetizer, as the Apache config failure was a whole other mess. When I try accessing DVWA, it gives me an Apache error stating that a connection was not established. I looked up on YouTube how to fix this, and there were several config files that I had to edit. After enabling key features, I tried it again but this time, it says that the current user does not have the permission to access the website. I tried fixing the SQL and Apache credentials, and it still did not work. I tried reinstalling DVWA, deleting the old database to make a new one, setting my user to root, and it still failed. I ended up running out of time, meaning I have to finish Weekly Task 8 for the next week.

*Documentation*
![](https://github.com/user-attachments/assets/d4b29c0b-3ccf-4f45-98d4-e9bf5a262b86)


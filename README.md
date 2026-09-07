# My eJPT Journey

### From Knowing the Tools to Understanding the Penetration Testing Methodology

## The Beginning

I graduated with a Diploma in Cybersecurity from **King Abdulaziz University (KAU)**.

During my studies, I gained practical experience with several cybersecurity and penetration testing tools. However, I realized that knowing individual tools was not enough. My biggest challenge was understanding **how to approach a target and how to decide what to do next** during a penetration test.

I could recognize tools and commands, but I sometimes struggled with questions such as:

> Where should I start?

> What should I look for?

> What does this result mean?

> What should I do next?

In other words, I had experience with individual techniques, but I needed a clearer understanding of the complete penetration testing methodology, from **Reconnaissance and Enumeration** through **Exploitation, Privilege Escalation, and Post-Exploitation**.

After deciding to continue toward **Red Team / Offensive Security**, I chose the **eJPT** certification to strengthen both my practical skills and my methodology.

My goal was not simply to earn another certification. I wanted to reach a point where I could approach a target systematically and understand **how to think, where to start, and how to determine the next step**.

---

## How I Started the Journey

My journey started with a **cybersecurity bootcamp organized by a King Abdulaziz University student club**.

The bootcamp consisted of eight lectures covering the general topics related to the certification.

It gave me an initial understanding of the eJPT domains and motivated me to continue with the official training.

After the bootcamp, I subscribed to **INE** and started studying the official eJPT training path.

I decided to follow the course **from beginning to end** and completed it in approximately **three months**.

The training was highly practical, so my preparation was not limited to watching videos or memorizing commands. Whenever possible, I learned the concept and then applied it directly through Labs and practical environments.

---

## My Study Approach

I followed the course **from beginning to end** and studied almost every day.

The course was extensive, and staying consistent sometimes became challenging. However, I decided not to jump randomly between topics.

Whenever a video included a Lab, I stopped and attempted the Lab myself before continuing.

Over time, I noticed a major change in the way I approached problems.

At first, I mainly focused on:

> "What command should I run?"

Eventually, I started asking:

> "Why am I using this tool? What am I looking for? And if I get this result, what should I do next?"

That shift from **command-based thinking to methodology-based thinking** became one of the most important parts of my eJPT journey.

---

## When Did I Start Seeing the Difference?

I cannot point to one specific Lab or moment and say that my skills changed instantly.

The improvement was gradual.

It came from consistently studying the course and solving practical Labs over time.

At the beginning, I often spent a lot of time trying to determine where to start or what the next step should be.

Eventually, I started approaching targets differently.

I would begin with **Enumeration** and ask:

**What did I find? What does it mean? What can I investigate next?**

I also noticed that I was memorizing less and understanding more.

I still use documentation and search for specific commands or technical details when needed. The difference is that I no longer feel completely lost when facing a target.

---

# What the Practical Experience Taught Me

The practical side of eJPT was especially valuable because it required me to connect different penetration testing techniques instead of treating them as isolated tasks.

The overall methodology involved areas such as:

```text
Reconnaissance
      ↓
Host Discovery
      ↓
Service Enumeration
      ↓
Vulnerability Identification
      ↓
Initial Access
      ↓
Credential Discovery
      ↓
Privilege Escalation
      ↓
Post-Exploitation
      ↓
Pivoting
      ↓
Internal Network Enumeration
```

This helped me understand that penetration testing is not simply about finding one vulnerability.

Each discovery can provide information that leads to the next stage of the assessment.

---

## Reconnaissance and Enumeration

One of the first steps in a penetration test is understanding the environment.

I practiced identifying hosts, open ports, services, versions, operating systems, and applications.

My general approach became:

```text
Hosts
  ↓
Ports
  ↓
Services
  ↓
Versions
  ↓
Operating Systems
  ↓
Applications
  ↓
Potential Attack Surface
```

This stage taught me the importance of thorough enumeration.

Instead of immediately looking for an exploit, I learned to first understand what is actually exposed.

---

## Vulnerability Identification

After identifying services and applications, I moved into vulnerability identification.

The general process I practiced was:

```text
Service
  ↓
Version
  ↓
Vulnerability Research
  ↓
Available Exploits
  ↓
Validation
  ↓
Potential Initial Access
```

This helped me understand the relationship between enumeration and exploitation.

A vulnerability should not simply be assumed because a service or version looks interesting. The available information needs to be investigated and validated before deciding on an attack path.

---

## Initial Access and Exploitation

During my practical training, I worked with different attack surfaces involving Linux and Windows systems as well as web applications and network services.

I practiced using tools such as:

* Nmap
* Metasploit
* Burp Suite
* Gobuster
* WPScan
* SearchSploit
* Netcat
* John the Ripper

The important lesson was not simply learning how to execute an exploit.

It was understanding the relationship between:

```text
Enumeration
     ↓
Vulnerability Identification
     ↓
Exploit Selection
     ↓
Initial Access
     ↓
Further Enumeration
```

Gaining an initial foothold was often the beginning of the next stage rather than the end of the assessment.

---

## Credential Discovery

Another important part of my practical preparation was learning how credentials can be discovered during post-exploitation.

I practiced investigating:

* Configuration files
* Application data
* Databases
* User information
* Password hashes
* Windows credential artifacts

The general workflow was:

```text
Initial Access
      ↓
File / Configuration Enumeration
      ↓
Credential Discovery
      ↓
Hash Analysis
      ↓
Password Recovery
      ↓
Credential Reuse
```

This taught me to continuously look for information that could provide additional access or expand the attack surface.

---

## Linux Privilege Escalation

I also practiced Linux privilege escalation techniques in controlled environments.

One of the key lessons was the importance of checking system configuration and permissions rather than relying only on known vulnerabilities.

A typical workflow became:

```text
Initial Access
      ↓
Current User
      ↓
System Enumeration
      ↓
Permissions / Sudo Checks
      ↓
Misconfiguration or Weakness
      ↓
Privilege Escalation
```

This strengthened my understanding of how seemingly small configuration weaknesses can have a significant security impact.

---

## Windows Enumeration and Post-Exploitation

The practical environments also gave me experience working with Windows systems and services.

I practiced enumerating and investigating services such as:

* SMB
* FTP
* RPC
* RDP
* WinRM
* IIS

I also worked with Windows credential artifacts and password hashes during controlled exercises.

The general workflow was:

```text
Windows Enumeration
      ↓
Service Discovery
      ↓
User / File Enumeration
      ↓
Credential Discovery
      ↓
Password Attacks
      ↓
Further Access
      ↓
Post-Exploitation
```

This helped me understand how Windows enumeration can support both initial access and lateral movement.

---

# Pivoting and Internal Network Enumeration

One of the most valuable concepts I practiced was **network pivoting**.

A compromised system can sometimes provide access to another network that is not directly reachable from the attacker's original position.

The concept can be represented as:

```text
Attacker
   |
   v
Compromised Host
   |
   v
Second Network Interface
   |
   v
Internal Network
   |
   v
Internal Hosts
```

After establishing a pivot, the assessment does not end.

The methodology continues with:

```text
Pivot
  ↓
Internal Host Discovery
  ↓
Port Enumeration
  ↓
Service Identification
  ↓
New Attack Surface
  ↓
Further Investigation
```

This was one of the concepts that helped me understand penetration testing as a connected process rather than a sequence of unrelated techniques.

---

# My Exam Preparation

After completing the course, I moved from studying the content to **intensive practical preparation**.

I had a specific list of practical Labs that I wanted to revisit, so I focused on solving them repeatedly rather than constantly switching between different resources.

I continued practicing until I reached a point where I felt **genuinely ready**.

At that point, I decided not to postpone the exam any longer and booked my attempt.

My preparation focused mainly on strengthening my ability to:

* Enumerate targets systematically.
* Identify relevant services and attack surfaces.
* Research vulnerabilities.
* Select appropriate exploitation techniques.
* Search for credentials.
* Perform privilege escalation.
* Analyze Windows and Linux systems.
* Perform password attacks in controlled environments.
* Understand pivoting and internal network enumeration.
* Think about the next logical step instead of relying on memorized commands.

---

# My Exam Experience

The exam was a long practical experience that tested more than technical knowledge.

I started the exam at **12:00 AM** and submitted it at **6:00 AM the following day**. The overall experience extended across approximately **30 hours**, including breaks and sleep.

At the beginning, I was progressing well.

Later, I became stuck on one of the systems, and this became the most challenging part of the experience both technically and mentally.

I tried different approaches, but eventually realized that continuing without a break was not helping.

I took a longer break and slept for around **6 hours**.

After returning, I was able to look at the problem with a clearer mind and approach it from a different perspective.

That experience taught me an important lesson:

**Taking a break can sometimes be more productive than continuing to work while exhausted.**

After completing the assessment, I reviewed my answers again and ultimately changed only **two answers**.

I finished the exam with a score of **84%** and earned the **eJPT certification**.

---

# What I Learned From the Experience

The biggest change was not the number of tools I learned.

It was **the way I think about penetration testing**.

Before eJPT, I knew tools and commands, but I lacked a consistent sequence:

> Where do I start?

> What should I look for?

> What does the result mean?

> What should I try next?

After the experience, I started viewing penetration testing as a connected process rather than a collection of individual commands.

I also learned that practical Labs are extremely important.

Knowing a command or watching someone solve a problem does not necessarily mean that you can apply it when you are facing a target yourself.

The most important lesson for me was:

**Do not try to memorize everything. Understand the methodology, and learn how to search, analyze, and think.**

---

# The Mental Side of the Exam

One of the biggest lessons I took from the experience was that a practical penetration testing exam does not only test technical knowledge.

Sometimes you may know the required techniques, but **fatigue and pressure can prevent you from seeing the solution**.

In my case, taking a break, sleeping, and returning with a clearer mind was one of the best decisions I made during the exam.

The experience taught me that managing time, energy, and focus is also part of performing well in a long practical assessment.

---

# If I Were Starting Again

If I went back to the first day of my eJPT journey, I would still follow the same general approach of completing the course and practicing after each video.

However, I would focus more from the beginning on understanding the **methodology** rather than focusing mainly on individual commands.

My advice to anyone starting eJPT would be:

* Follow the content in order.
* Do not just watch the Labs; solve them yourself.
* Do not be afraid to use documentation and references.
* Understand why you are using a tool, not just how to use it.
* Do not take the exam simply because you finished the course; practice until you feel ready.
* Practice thinking about the next logical step.
* Do not ignore time and fatigue management.
* If you get stuck, do not assume that the solution is to keep working for hours without stopping.
* Sometimes you simply need to **pause, reorganize your thoughts, and return with a clearer mind**.

---

# Conclusion

For me, eJPT was not simply another certification to add to my CV.

It was a stage that helped me move from someone who knew several penetration testing tools to someone with a **clearer methodology for approaching a target**.

I started the journey knowing the tools but sometimes not knowing where to begin.

I finished it with a much better understanding of how to approach a penetration test through:

**Reconnaissance → Enumeration → Vulnerability Identification → Exploitation → Credential Discovery → Privilege Escalation → Post-Exploitation → Pivoting → Internal Network Enumeration**

The certification was the result, but the real growth was in **the way I think about penetration testing**.

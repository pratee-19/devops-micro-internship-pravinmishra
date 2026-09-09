# Week 00 - Internet and Networking

Part of the DevOps Micro Internship (DMI) Cohort 3 with Agentic AI

---

# 🧑‍💻 Task 1: Using ChatGPT as Your Learning Assistant

## Scenario

You're new to DevOps and will frequently encounter technical questions. ChatGPT can be your learning companion.

## Your Task

Write a clear ChatGPT prompt to help you understand:

> "What is a protocol in networking? Explain with a simple real-life example."

Take a screenshot of your interaction showing:

* Your detailed prompt (with clear expectations)
* ChatGPT's simplified response with an example

## Screenshot

Save your screenshot in the `screenshots` folder and update the file name below.

![Task 1 Screenshot](screenshots/chatgpt_interaction)


Replace `task-1-chatgpt.png` with your actual screenshot file name.

---

## What I Learned (2–3 lines)

I learned how to ask for help, guidance and support from this AI tool called ChatGPT. In the video, sir mentioned that a 6th-standard student won't understand what a developer with 5 years of experience can, and ChatGPT doesn't know with whom it's actually conveying the information, so we should provide a detailed prompt to get simplified answers

---

# 🌐 Task 2: Internet and Networking

## Scenario

Your friend is launching an online bookstore named **EpicReads**.

He asked you to explain how users globally can access his website hosted in Finland.

## Your Task

Write a short explanation (**100–150 words**) that includes:

* Packet Switching
* IP Address
* TCP/IP
* HTTP/HTTPS

💡 **Tip:** You may use ChatGPT (as demonstrated in Task 1) to refine your explanation.

## Answer

An online bookstore named "EpicReads" can be accessed by anyone around the world who has access to the internet. The internet is basically a network of networks that enables smooth communication between two sides: the source and the destination. In the past, people used to communicate using letters, which were sent through the post. It could take months and sometimes even years to reach the destination. When there was an emergency or some information needed to be delivered quickly, this mechanism was not efficient. Hence, to overcome such problems, the internet was developed and initially used by the defence sector. Today, data is transferred through large optical fibre networks, which is one of the major reasons behind the fast communication we have today. Data can be sent through different paths, and later at the destination, it gets reassembled. This concept is called packet switching. In the earlier days, when letters were sent through the post, they had an address written on them, which helped identify the destination. The letter also had information about the sender, so if, for some reason, the letter could not be delivered, it could be sent back to the source. This can be related to the concept of an IP address in networking, which helps identify and communicate with devices on a network. In the internet world, there are different types and modes of communication, and devices can be identified using IP addresses. Sending a particular type of message or information has its own set of rules, and these rules depend on the mode of communication. For example, for video calls and voice calls, UDP is commonly used because speed is more important than guaranteed delivery. Some other important protocols are TCP/IP, HTTP, and HTTPS. HTTP is mainly used for web-related communication, while HTTPS is the secure version of HTTP, which provides encrypted communication over the web.


---

# 🏗️ Task 3: Application Architecture & Stack

## Scenario

EpicReads bookstore has two application versions:

### Two-Tier Application

* Frontend
* Database

### Three-Tier Application

* Frontend
* Backend
* Database

## Your Task

* Draw simple diagrams (hand-drawn or tool-based such as draw.io)
* Label each layer clearly
* List at least two common technologies or tools used for each layer
* Submit a screenshot or photo clearly showing your own drawing

## Diagram Screenshot / Photo

Save your diagram image in the `screenshots` folder and update the file name below.

![Application Architecture Diagram](screenshots/Architecture)


Replace `task-3-diagram.png` with your actual diagram file name.

---

## Technologies Used

### Frontend

* HTML
* JAVASCRIPT

### Backend

* SPRINGBOOT
* NODE JS

### Database

* MYSQL
* MONGODB

---

# 🌍 Task 4: Domain Name & DNS (Basic Concepts)

## Scenario

Your friend's bookstore **EpicReads** is currently accessible through:

```text
52.172.142.222:3000
```

He purchased the domain:

```text
epicreads.com
```

## Your Task

In **50–100 words**, explain in your own words:

1. What is DNS (Domain Name System)?
2. Which DNS record type should be used to connect the domain to the given IP, and why?

## Answer

IP address is the unique address of the device to identify from where to whom the data is communicated to and remembering those numbers for eg: 52.172.142.222 is hard, and if a user have to access it they cant do it . To solve that problem Domain name is used. It simply provides a simplified version by specifying a name for the IP address to easily access it, i.e., a "human-readable address" as well as helping with branding. Domain names can be obtained through domain registrars. When we type any domain name in the browser, and we know the application is being served from a certain IP address, then the domain name is translated; this job is done by DNS(Domain Name System), similar to the phonebook (contacts).To find what exactly is running on a particular IP Address Record type is used. Based on the application's nature, there are different types of DNS record types eg: A record type for(IPV4) and AAAA record type for(IPV6) to run different applications

---

# 💻 Task 5: Visual Studio Code Setup (Hands-on)

## Your Task

Install Visual Studio Code (if not already installed).

Take a screenshot of your VS Code environment showing:

* Terminal open inside VS Code
* Running a basic command:

### Windows

```powershell
dir
```

### Linux / macOS

```bash
pwd
ls
```

* Your selected VS Code theme clearly visible

⚠️ **Important:** The screenshot must show your username or another identifiable detail to confirm it is your environment.

## Screenshot

Save your screenshot in the `screenshots` folder and update the file name below.

![VS Code Setup Screenshot](screenshots/VSCODE)


Replace `task-5-vscode.png` with your actual screenshot file name.

---

# 🔗 Task 6: Publish Your Assignment as a LinkedIn Post

## Objective

Publishing on LinkedIn helps you:

* Build your professional online presence
* Reinforce your learning
* Document your DevOps journey publicly

## Your Task

Summarize your answers from Tasks 1–5 into a LinkedIn post.

Clearly structure your post into the following sections:

* ChatGPT
* Internet & Networking
* App Architecture
* DNS
* VS Code Setup

Use the credit note that matches your track:

Add the following credit note at the end of your post **(If you are DMI Cohort 3 student)**:

> **P.S. This post is part of the DevOps Micro Internship (DMI) with Agentic AI — Cohort 3 — by Pravin Mishra. My graded progress is public: https://dmi.pravinmishra.com/s/YOUR-GITHUB-USERNAME.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=cohort3**


Add the following credit note at the end of your post **(If you are DMI Self-paced track student)**:

> **P.S. This post is part of the DevOps Micro Internship (DMI) — Self-Paced Engineer Track — by Pravin Mishra. My graded progress is public: https://dmi.pravinmishra.com/s/YOUR-GITHUB-USERNAME.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=self-paced**

Add the following credit note at the end of your post **(If you are DMI Campus student)**:

> **P.S. This post is part of the DevOps Micro Internship (DMI) — Campus — by Pravin Mishra. My graded progress is public: https://dmi.pravinmishra.com/s/YOUR-GITHUB-USERNAME.html · Start your DevOps journey: https://dmi.pravinmishra.com/?utm_source=student&utm_medium=ps-linkedin&utm_campaign=campus**

Replace `YOUR-GITHUB-USERNAME` with your GitHub username — that link is your public DMI progress page (your graded badge page).
---

## LinkedIn Post URL

Paste your LinkedIn post URL here:

```text
https://lnkd.in/p/gvf8qDJi
```

---

## LinkedIn Post Backup Copy

Paste the full text of your LinkedIn post here:

Week 00 of my DevOps Learning Journey!
I’ve started learning DevOps through the DevOps Micro Internship (DMI) — Self-Paced Engineer Track, and this week was about understanding the fundamentals of the Internet, Networking, and development environments.
ChatGPT
I learned how to use ChatGPT effectively as a learning assistant. One important thing I understood is that the quality of the prompt matters. By clearly explaining my level of understanding and what kind of explanation I need, I can get much more useful answers.
Internet & Networking
I learned the basic idea of how the Internet works as a network of networks. I understood concepts like packet switching, IP addresses, TCP/IP, HTTP and HTTPS.
The real-life examples helped me understand how data travels between a source and destination instead of just memorising definitions.App Architecture
I learned about two-tier and three-tier architectures using the example of an online bookstore called EpicReads.
Two-Tier:
Frontend → Database
Three-Tier:
Frontend → Backend → Database
I also explored technologies such as HTML, JavaScript, Spring Boot, Node.js, MySQL and MongoDB.
DNS
I learned why we use domain names instead of remembering IP addresses such as 52.172.142.222.
DNS works like a phonebook of the Internet, translating domain names into IP addresses. I also learned about DNS record types such as A records for IPv4 and AAAA records for IPv6.
VS Code Setup
Finally, I set up my VS Code environment and practiced using the integrated terminal and basic commands.
This week helped me understand the foundation of networking and application architecture, which I know will be important as I continue learning DevOps.
Looking forward to learning more and building step by step!
#DevOps #DevOpsJourney #Networking #DNS #CloudComputing #SoftwareDevelopment #LearningInPublic #DMI #DevOpsMicroInternship
P.S. This post is part of the DevOps Micro Internship (DMI) — Self-Paced Engineer Track — by Pravin Mishra. My graded progress is public: https://lnkd.in/gEpECNd2 · Start your DevOps journey: https://lnkd.in/gA958u8g

---

# Reflection – Week 0

### What did you find easy?

Interacting with CHATGPT was quite easy 

---

### What was difficult?

DNS record type, I think I got the basic Knowledge about I want to explore it more deeply to get to know it to the fullest

---

### What will you improve next week?

I will try to explore more than the given content 

---

## 📌 About DMI & CloudAdvisory

DevOps Micro Internship (DMI) is a project-based DevOps program run by Pravin Mishra (The CloudAdvisory) focused on real-world execution, systems thinking, and career readiness.

It helps learners build strong DevOps foundations with hands-on experience.


## 📌 Resources

- 🌐 **DMI Official Website:** https://dmi.pravinmishra.com?utm_source=github&utm_medium=readme  
- 🎓 **University:** https://university.pravinmishra.com?utm_source=github&utm_medium=readme  
- 💬 **Discord Community:** https://discord.pravinmishra.com?utm_source=github&utm_medium=readme  
- 📝 **Blog:** https://dmi.pravinmishra.com/blog?utm_source=github&utm_medium=readme  
- ▶️ **YouTube Playlist (DMI Cohort 3):** https://www.youtube.com/playlist?list=PLFeSNDtI4Cho  
- 🔗 **Pravin Mishra (LinkedIn):** https://www.linkedin.com/in/pravin-mishra-aws-trainer/  
- 🏢 **CloudAdvisory (LinkedIn):** https://www.linkedin.com/company/thecloudadvisory/

---

*This submission is part of DevOps Micro Internship (DMI) Cohort 3 — Agentic AI Track*

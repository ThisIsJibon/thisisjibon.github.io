---
title: "UniManage"
date: 2022-06-30T23:15:00+07:00
slug: unimanage
category: projects
summary:
description:
cover:
  image:
  alt:
  caption:
  relative: true
showtoc: true
draft: false
---

# Overview

UniManage is a web platform designed to streamline university administration processes. Our innovative approach includes a robust **third normal form** database architecture to ensure data integrity. With features like real-time **results updates**, convenient **course registration**, and personalized **daily schedules**, UniManage empowers universities to operate more efficiently and provide a seamless experience for students and faculty.
![Functional Dependency](/images/projects/unimanage/4.png)

# Features

📊 **Efficient Database Design:**
At the core of UniManage lies a robust designed database structure. By achieving third normal form (3NF), we have minimized data redundancy and ensured that every piece of information finds its rightful place. This approach not only enhances system performance but also simplifies maintenance.
![ER Diagram](/images/projects/unimanage/7.png)
![Normalized Database](/images/projects/unimanage/5.png)
![Functional Dependency](/images/projects/unimanage/6.png)

🌐 **Robust REST API:**
We developed a REST API that seamlessly handles Create, Read, Update, and Delete (CRUD) operations. This enables smooth data interactions and facilitates the application's efficiency.

📚 **Course Registration:**
Students can easily register for courses each semester, with real-time status updates. SysAdmins can efficiently manage and update registration statuses, ensuring a smooth process.
![Functional Dependency](/images/projects/unimanage/2.png)

📈 **Result Querying:**
SysAdmins provide result data for specific courses, enabling students to check semester-wise and overall results for the courses they've taken.
![Functional Dependency](/images/projects/unimanage/3.png)

📅 **Custom Daily Schedules:**
UniManage empowers students with personalized daily schedules. By querying the courses taken by each student, the system generates fully customized schedules. SysAdmins can also communicate updates, rescheduling, or cancellations directly to students.
![Functional Dependency](/images/projects/unimanage/1.png)

# Technical Aspect

🛠️ **Frontend:** React, ChakraUI, Bootstrap \
🔧 **Backend:** Node, Express \
💾 **Database:** PostgreSQL

# Links

[GitHub repository ](https://github.com/ThisIsJibon/UniManage)

[Youtube Demo](https://youtu.be/w_rFpJ27n38)

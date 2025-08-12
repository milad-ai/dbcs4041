---
layout: page
title: Syllabus
permalink: /Syllabus/
---
# **Course Objectives**
This course provides a comprehensive introduction to **database management systems (DBMS)** and their role in modern data-driven applications. It covers the **fundamentals of database theory**, **conceptual and logical design**, and **data access and manipulation** while emphasizing **best practices** for modeling, implementation, and optimization.

Students will gain proficiency in **relational database concepts** through **Entity-Relationship (ER) modeling**, mapping ER diagrams to **relational schemas**, and formulating complex **SQL queries** for real-world analytical tasks.

The course also introduces key **data concepts and ethical considerations**:  

- Understanding the **data hierarchy (DIKW pyramid: Data → Information → Knowledge → Wisdom)**.  
- Introducing **bias and basic ethical issues** in working with data, along with emerging concepts such as **dataism**.  
- Learning the **four levels of data analytics**: descriptive, diagnostic, predictive, and prescriptive.
  
Beyond the fundamentals, the course introduces **modern trends and tools** in database management, such as:

- **Embedded and analytical databases** (e.g., DuckDB) for fast local processing.
- **Analytical vs transactional systems**: understanding **OLAP (Online Analytical Processing)** vs **OLTP (Online Transaction Processing)**.
- **Data Warehouse** vs **Data Lake** vs **Lakehouse** architectures: understanding their differences, purposes, and how they integrate in modern data ecosystems.
- **Introduction to NoSQL databases** (e.g., MongoDB) and understanding when to choose them over relational systems.
- **Query optimization and indexing** for improved performance in large datasets. 
- **Big Data frameworks** (e.g., PySpark) for large-scale data analytics.  
- **Vector Databases** and their role in **AI-driven semantic search** and **retrieval-augmented generation (RAG)**, including a **pgvector tutorial** demonstrating how to integrate vector search into PostgreSQL for similarity queries and AI use cases.
- **Integration with visualization tools** (Power BI) and **web applications** (Streamlit) for presenting insights interactively.
- **API development** for exposing database functionality and enabling programmatic access to data.

Upon successful completion of this course, the student will be able to:

- Introduce fundamental concepts, terminology, and applications of databases.  
- Design ER models for simple applications and convert them into relational tables.
- Differentiate between **OLAP and OLTP systems** and understand their real-world use cases.
- Compare Data Warehouse, Data Lake, and Lakehouse approaches and determine when each is most effective.
- Formulate SQL queries effectively for data retrieval and manipulation.  
- Compare relational approaches with **NoSQL** paradigms and understand their trade-offs.
- Learn to connect databases with **Python** and perform **data analysis with Pandas and PySpark**.  
- Perform **data extraction, transformation, and visualization** to support business decisions.
- Build basic **APIs** to expose and integrate database functionalities into external applications.


The primary hands-on environment will be **PostgreSQL**, supplemented by **DuckDB, Marimo notebooks, and Power BI**, providing both industry-standard and cutting-edge perspectives on database management.

In the final project, students will design and implement a complete database system from conceptual modeling to relational implementation, accompanied by an interactive analytical dashboard and a simple web application for data exploration and reporting.


# **📚 [View Detailed Teaching Plan](https://dbcs.ir/Teaching_Schedule/)↵**


## **Homework Assignments**

You will have five sets of homework assignments, which together carry a total of 5 points. These assignments include both theoretical and practical exercises to help reinforce your learning throughout the course (See the [homework page](https://dbcs.ir/assignments/), which will be updated during the course). The due dates for these assignments will be posted on this website.

## Homework Submission Instructions
{% include image.html url="/_images/Annotation 2025-08-04 194554.png" width=450 align="right" %}
{% include image.html url="/_images/Annotation 2025-08-05 113141.png" width=450 align="right" %}
Please follow the instructions to turn in your homework:  

- Homeworks must be submitted electronically.  
- The **subject line of your email** must follow this naming scheme:  
  - `HW<2-digits homework number>_<LastName>_<FirstName>`  
  - For instance, my first homework would be called: `HW01_Vazan_Milad`  
  - 📧 Send your homework to **hw@dbcs.ir**

⚠️ **Important:** Emails with this exact subject format will receive an automatic confirmation reply upon submission. If you do not receive this confirmation within **five minutes**, it means your email was not received.  

> The **deadline** for each assignment will be **announced separately**. An **automatic reminder** will be sent **one day before the deadline** to the email address you provided to the instructor during the **first session**.
> If the **deadline is extended**, students who have **not submitted** their assignment will receive another **automatic email** **one day before the new deadline**.



## **Exams**

The course will include **two exams**. Both exams will assess the required readings and topics covered in class. The first exam will be an "in-class" [midterm](https://dbcs.ir//exams), while the second will be a [final exam](https://dbcs.ir//exams) scheduled during the University's final examination period at the end of the semester.

**If you need to miss the midterm test due to illness or a family affliction, please contact me by email. A make-up exam for the midterm might be organized.**
{: 	.text-green-200 }

## **Attendance and Participation**

**Attendance is required**, and exceeding four absences may result in a penalty of up to 2 points off your total grade. Active participation in both in-class activities and the online message board is highly encouraged.

# **Grading**
- Class attendance and participation: **2** points 
- Homeworks: **5** points
- Final project: **5** points 
- Midterm exam (-----): **3** points
- Final exam (-----): **5** points 


## **Seeking Assistance**

Here are the available help resources, organized by the urgency of your issue:

### **Messaging**
Our course will utilize a Telegram group (link to be provided in class) as the primary communication platform for announcements and discussions. This is an ideal space for asking questions that can be answered by anyone. It's best to use this resource for non-urgent inquiries.

### **Talk with the Instructor**
For any issues at all, please reach out to the instructor:

- Speak with me before class  
- Raise your hand or speak up during class

## **Required Tools and Accounts**

To successfully participate in this course, students are expected to prepare the following tools and accounts prior to the practical sessions:

- **Python**: [Install](https://www.python.org/downloads/) the latest stable version of Python for running scripts and interacting with databases.  
- **GitHub Account**: Create a [GitHub](https://github.com/) account.
- **Streamlit Account and GitHub Integration**: Link your GitHub account to [Streamlit](https://share.streamlit.io/) to deploy database-driven web applications.
- **Ploomber Cloud**: [create a Ploomber Cloud account](https://www.platform.ploomber.io/register/)
- **[Visual Studio Code](https://code.visualstudio.com/download)**
- **[PostgreSQL](https://www.postgresql.org/download/)**
- **Neon**: Sign up at [Neon](https://neon.com/) for serverless PostgreSQL database hosting.
- **DuckDB**: Install DuckDB for lightweight, embedded database tasks and analytical queries.
- **[Power BI](https://powerbi.microsoft.com/)**: Used for data visualization and creating interactive dashboards to analyze database results. (Optional – used in one session for connecting to PostgreSQL and creating basic visualizations)
- **Marimo**: This will be used as the primary environment for interactive notebooks and coding sessions.
  > pip install "marimo[recommended]"
- **Pandas**:
  > pip install pandas
- **PySpark**:
  > pip install pyspark

 

### **Hardware Requirement**

For the SQL and practical sessions, students will need **a laptop or a smartphone** to follow along and complete in-class exercises.

## **Collaboration Policy**

You are encouraged to discuss the content of this course with anyone you like; however, it is essential to **maintain academic integrity** in your work. All homework assignments, projects, and exams must be completed independently, meaning you are not permitted to copy any part of another student’s solution, collaborate with others on your assignments, or use solutions from unauthorized sources, including the Internet. **Therefore, the solution you submit for each assignment must be solely your own, reflecting your understanding and effort.**


### **📜 [View Generative AI Usage Guidelines](https://dbcs.ir/AI_Guidelines/)↵**


## **Related Courses**
### Other Databases courses 
<!--- ### What is this course like in other places?--->
- [New York University - Database Design & Implementation](https://knowledge.kitchen/content/courses/database-design/schedule/)
- [UC Berkeley - Introduction to Database Systems](https://cs186berkeley.net/)
- [CARNEGIE MELLON UNIVERSITY - Database Systems](https://15445.courses.cs.cmu.edu/spring2024/schedule.html)
- [University of Washington - Introduction to Database Systems](https://courses.cs.washington.edu/courses/cse414/)
- [The University of Chicago - Introduction to Database Systems](https://classes.cs.uchicago.edu/archive/2023/spring/23500-1/)
- [University of Waterloo - CS 348: Introduction to Database Systems](https://cs.uwaterloo.ca/~smaiyya/cs348/)
- [NTHU - CS 471000 Introduction to Database Systems](https://nthu-datalab.github.io/db/)
- [The Ohio State University - Introduction to Database Systems](https://syllabi.engineering.osu.edu/syllabi/cse_3241)

## **A note on self care.** 
Please take care of yourself. Do your best to maintain a healthy lifestyle this semester by eating well, exercising, getting enough sleep and taking some time to relax. This will help you achieve your goals and cope with stress. 

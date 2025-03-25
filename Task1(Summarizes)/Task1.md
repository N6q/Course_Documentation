# 📚 Task 1: Summarizes

Welcome to the repository where we summarize various topics in software development, web development, and more! Below is an organized table of contents for easy navigation.

---

## 📋 Table of Contents

1. [Software Development Life Cycle (SDLC)](#software-development-life-cycle-sdlc)
   - [Phases of SDLC](#phases-of-sdlc)
   - [Roles and Responsibilities in SDLC](#roles-and-responsibilities-in-sdlc)
2. [Web Development Stacks](#web-development-stacks)
   - [Parts and Services of Web Applications](#parts-and-services-of-web-applications)
   - [Comparison of Web Stacks](#comparison-of-web-stacks)
   - [Tools in the .NET Stack](#tools-in-the-net-stack)
3. [Agile and Scrum](#agile-and-scrum)
   - [Agile Methodology](#agile-methodology)
   - [Comparison of Agile and Waterfall Models](#comparison-of-agile-and-waterfall-models)
   - [Frameworks for Implementing Agile](#frameworks-for-implementing-agile)
   - [Scrum Framework](#scrum-framework)
4. [Git Version Control](#git-version-control)
   - [What is Git?](#what-is-git)
   - [Cloud Repositories Using Git](#cloud-repositories-using-git)
   - [Git Commands Explained](#git-commands-explained)
5. [References](#references)

---

## 🌟 Software Development Life Cycle (SDLC)

### Phases of SDLC

The Software Development Life Cycle (SDLC) consists of several phases, each with its own role, input, and output. Below is a detailed breakdown:

1. **Analysis**
   - **Role**: Gathering requirements and information about the software from the client.
   - **Input**: Client needs, interviews
   - **Output**: Software Requirement Specification (SRS)

2. **Design**
   - **Role**: The designer will design the software based on the client requirements/needs.
   - **Input**: Software Requirement Specification (SRS)
   - **Output**: UI/UX, System architecture

3. **Development**
   - **Role**: Based on UI/UX and system architecture, the developer will develop the software.
   - **Input**: UI/UX, System architecture
   - **Output**: Software

4. **Testing**
   - **Role**: Test the software for any errors or issues based on acceptance criteria of user stories.
   - **Input**: Software, acceptance criteria of user story, test cases
   - **Output**: Test report, fix the errors

5. **Deployment**
   - **Role**: Deploy the software to production.
   - **Input**: Software without any errors
   - **Output**: Live system

6. **Maintenance**
   - **Role**: Provides ongoing maintenance, updates, and bug fixes.
   - **Input**: User feedback
   - **Output**: Updated error-fixed software versions

---

### Roles and Responsibilities in SDLC

Each phase involves specific roles and responsibilities, along with tools commonly used by professionals:

1. **Analysis**
   - **Product Owner**: Defines product vision, sets priorities, and ensures the team builds what stakeholders want.
     - Tools: Jira
   - **Project Manager**: Plans project scope, timeline, resources, and risks.
     - Tools: Jira, Trello, Microsoft Project
   - **Business Analyst**: Converts requirements into a format developers and designers can understand.
     - Tools: Lucid Chart, To-Do List
   - **CTO**: Provides tools and software that should be used.

2. **Design**
   - **System Architect**: Designs the overall system architecture, including databases, servers, and software components.
     - Tools: Lucid Chart, Star UML
   - **UX/UI Designer**: Designs the user experience (UX) and user interface (UI) of the software.
     - Tools: Figma, Adobe XD, Adobe Photoshop, Canva

3. **Development**
   - **Front-end Developer**: Develops user interfaces.
     - Tools: React.js, Angular, VS Code, Git
   - **Back-end Developer**: Develops server-side applications.
     - Tools: Node.js, Python, Java, MySQL, Git, Docker

4. **Testing**
   - **QA Engineer**: Designs test cases and performs automated tests.
     - Tools: Selenium
   - **Tester**: Executes manual and automated tests.
     - Tools: Postman
   - **DevOps**: Automates testing in CI/CD pipeline.
     - Tools: Jenkins

---

## 🌐 Web Development Stacks

### Parts and Services of Web Applications

A typical web application consists of several parts and services:

1. **Database**
   - Stores user data, transactions, and application settings.
   - Examples: MySQL, MongoDB, SQL Server, PostgreSQL
   - ORM: Entity Framework (C#), Mongoose (Node.js), Hibernate (Java)

2. **Frontend (Client-Side)**
   - The user interface (UI) and experience (UX) of the web application.
   - Examples: HTML, CSS, JavaScript
   - Frameworks: React, Angular, Vue.js

3. **Backend (Server-Side)**
   - Handles business logic, authentication, and database interactions.
   - Examples: Node.js, Python (Django/Flask), Ruby (Rails), Java (Spring), C# (.NET)

4. **API**
   - Enables communication between frontend and backend.
   - Examples: REST, GraphQL

5. **Hosting**
   - A platform that helps deploy and scale web applications efficiently.
   - Examples: Azure, AWS

6. **DevOps**
   - Automates deployment, testing, and scaling.
   - Examples: Docker

7. **Web Server**
   - Processes client requests and serves web pages.
   - Examples: Apache

---

### Comparison of Web Stacks

Here’s a comparison of popular web stacks:

1. **.NET**
   - Database: SQL Server
   - Programming Language: C#
   - Framework: .NET / .NET Core
   - Where to use: Enterprise apps, financial systems, e-commerce platforms
   - When to use: For large-scale applications requiring reliability, scalability, and maintainability.
   - Features: High performance, Common Type System, strong IDE support (Visual Studio), security.

2. **Java**
   - Database: Oracle SQL
   - Programming Language: Java
   - Framework: Spring
   - Where to use: Enterprise apps, e-commerce platforms, social media apps
   - When to use: When building complex systems that require multi-threading and robustness.
   - Features: Object-Oriented, Platform Independence, Scalability.

---

## 🚀 Agile and Scrum

### Agile Methodology

**Explanation**:  
Agile project management is a process for managing a project that involves constant collaboration and working in iterations. It works off the basis that a project can be continuously improved upon throughout its lifecycle and adapt to changes quickly.

**Purposes of Agile**:  
1. Customer satisfaction through early and continuous software delivery.
2. Frequent delivery of working software.
3. Embrace changing requirements, even in later stages.
4. The main measure of progress is working software.
5. The team reflects on how to become more effective at regular intervals, adjusting behavior accordingly.
6. Faster Time to Market.

---

### Scrum Framework

**Explanation**:  
Scrum is a management framework that teams use to self-organize and work towards a common goal. It describes a set of meetings, tools, and roles for efficient project delivery.

#### Timing & Meetings
- **Sprint Planning**: A meeting held at the start of each Sprint to define the work to be done.
- **Daily Standup (Daily Scrum)**: A short daily meeting (15 minutes) where team members discuss progress, plans, and blockers.
- **Sprint Review**: Held at the end of the Sprint to showcase the completed work to stakeholders.
- **Sprint Retrospective**: A meeting to reflect on the Sprint and identify areas for improvement.

#### Roles
1. **Product Owner**: Focuses on ensuring the development team delivers the most value to the business.
2. **Scrum Master**: Champions Scrum within the team and coaches them to improve processes.
3. **Development Team**: A cross-functional group responsible for delivering potentially shippable increments of the product.

---

## 🛠️ Git Version Control

### What is Git?

**Description**:  
Git is a distributed version control system that tracks versions of files. It is often used to control source code by programmers who are developing software collaboratively.

#### Why Use Git?
- **Version Tracking**: Git tracks the changes you make to files, so you have a record of what has been done, and you can revert to specific versions if needed.
- **Collaboration**: Git makes collaboration easier, allowing changes by multiple people to all be merged into one source.

#### When to Use Git
- Git is particularly beneficial in large-scale projects involving multiple team members, where efficient version control and collaboration are essential.

---

### Git Commands Explained

#### Setup
- `git config --global user.name "Samir"`
  - Set username for Git.
- `git config --global user.email "Samir@email.com"`
  - Set email for Git.

#### Start a New Project
- `git init`
  - Create a new local repository.
- `git clone <url>`
  - Clone a remote repository to your local machine.

#### Work Locally
- `git add <file>`
  - Move a specific file from the working directory to the staging area.
- `git add .`
  - Move all files in the folder to the staging area.
- `git commit -m "message/comment/updates"`
  - Commit staged changes with a message.

#### Connect to Remote Repository
- `git push <alias>`
  - Upload local commits to the remote repository.
- `git pull`
  - Fetch and merge changes from the remote repository to the local repository.

---

## 🔗 References

- [Wikipedia: Git](https://en.wikipedia.org/wiki/Git)
- [Noble Desktop: What is Git?](https://www.nobledesktop.com/learn/git/what-is-git)
- [Simplilearn: Git Tutorial](https://www.simplilearn.com/tutorials/git-tutorial/what-is-git)
- [Upwork: Best Git Repository Tools](https://www.upwork.com/resources/best-git-repository-google-github-bitbucket)
- [Atlassian: Git Glossary](https://www.atlassian.com/git/glossary#commands)

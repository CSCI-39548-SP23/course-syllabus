# CSCI-395.48 - Practical Web Development <br/> Spring 2023, Hunter College
### Wednesday, 5:30pm - 8:00pm <br/> Room TH405

---

## Course Description

This elective course is meant to introduce Computer Science students to modern day web development practices, languages, and frameworks that are in use in the industry today to do full stack web development. The course is mostly practical and hands-on to give the students as close to a real-world industry experience as possible. Students will spend the majority of the semester building web applications of varying degrees, from small assignments with initial boilerplate/template code, to building their own web app from scratch as part of a final project.

After the completion of this course, students are expected to have at least a basic understanding of how web application development works, and should be comfortable setting up a basic fullstack web-apps from scratch.

---

## Course Prerequisites

- Successfully completed CSCI 235

Recommended prerequisites:
- Comfortable working on the command line
- Comfortable writing/testing/debugging code.
- IDE/Code Editor (VSCode, WebStorm, Sublime)
- Familiarity with Git/GitHub/GitHub Classroom

---

## Grading

40% - Assignments (4 x 10%) (Late submission penalties applied at 10% per week) <br/>
10% - Lab Report <br/>
10% - Participation/Presentation <br/>
40% - Final Project (30%) + Presentation (10%) <br/>

Just to be completely transparent about grades, you can calculate your final grade with the formula below:

```text
FinalGrade =
.10 * (assignment 1 grade) +
.10 * (assignment 2 grade) +
.10 * (assignment 3 grade) +
.10 * (assignment 4 grade) +
.10 * (lab report grade) +
.10 * (participation/presentation) +
.40 * (final project grade)
```

The formula should be pretty straightforward to understand. Your final letter grade is based on CUNY grading ranges as outlined [here](https://hunter.cuny.edu/students/registration/records-and-transcripts/grading-structure/). 

---

## Course Materials/Readings
This is a zero-textbook cost course, and as such we don't have any required textbooks. Instead, we will mostly be going over API documentations, code samples, and other reading materials related to various frameworks and technologies that we will cover in this course. Below are links to some of the course materials we'll be using throuhgout the semester:

Books:

* https://eloquentjavascript.net/ <br/>
  * Amazon Link: https://www.amazon.com/Eloquent-JavaScript-3rd-Introduction-Programming/dp/1593279507
  * Useful book, content is also available online at the website above that the author made.


* JavaScript: The Good Parts
  * Amazon Link: https://a.co/d/83NUXkY
  * Really good light/intro reading on JavaScript


Documentations:
* MDN Docs: https://developer.mozilla.org/en-US/
  * Useful documentation from Mozilla Developer Network
  * Has information on HTML/CSS/JS syntax and methods.

* ReactJS Docs: https://reactjs.org/docs/getting-started.html
  * Official documentation for ReactJS


* NodeJS Docs: https://nodejs.org/en/docs/
  * Official documentation for NodeJS
  * We will be using Node.js 17.x and +
  * Focusing mostly around the http module.


* ExpressJS Docs: https://expressjs.com/en/4x/api.html
  * Official documentation for ExpressJS
  * Minimal web framework build on top of NodeJS.

And additional documentations around frameworks that we'll take a look at.

In lieu of office hours, we will be leveraging Slack as a class-wide communication/collaboration platform. You can post questions/comments on anything regarding our course materials, assignment and projects. Please do be respectful of on another and avoid any (unintentional) plagiarism on the platform.

## Slack
We'll be using Slack as our primary communication platform. This is probably the best way to reach me, aside from my email/office hour meetings. I tend to check Slack throughout the day, especially if I'm at work, and will try and answer all questions/inquiries as soon as possible.

- Check our class Blackboard for the most up to date Slack invite link.
- Invites will not be emailed out individually so it's import that you join our classroom Slack yourself via the link provided on Blackboard.
- Reach out to me if you run into any issues with joining Slack!

---

### GitHub Classroom
We will be using GitHub classroom to complete our assignments. Each assignment link will be handed out via BlackBoard, which will give you access to your own personal assignment GitHub repository, where you will commit code/answers to your assignments.

As part of `assignment0` (not graded), you will be required to properly set up your GitHub account, and join our GitHub classroom.

---

## Course Topics/Schedule
Content/order subject to change*

### Introduction
- Introductions and overview of web development
- Going over syllabus and course content
- Brief overview of full-stack web development, the internet, backend/frontend web development
### Assignment 0

### Git/GitHub
- Quick introduction/primer on using Git as a version control system
- Overview of GitHub as a service and GitHub classroom
- Going over assignment setup and submissions

### HTML/CSS
- Introduction to HTML
    - Overview of how websites are rendered. HTML and the DOM
    - Debugging HTML code via debugger console (rendered code, console, network tab, etc...)
- Introduction to CSS
    - CSS selectors and ordering
    - Flexbox and responsive designs/styling
### Assignment 1

### Javascript
- History of JS, ECMA script
- Functional programming pattern vs. OOP
- JS Basic syntax and primitive types.
- Objects and functions in JS
- DOM manipulation using JS
- Functional programming methods
    - Map, reduce, filter
- Intro to asynchronous programming
    - Callback functions
    - HTML Events
    - Network/API calls
### Assignment 2

### NodeJS
- What is a framework?
- Looking at different NodeJS modules
    - Focusing primarily on web related modules (HTTP, file I/O, streaming/sockets)
- NPM and package management
    - Looking at common/popular NPM packages

### ExpressJS
- Introduction to ExpressJS
    - ExpressJS as a framework based off of NodeJS
- REST-ful API development (CRUD, HTTP Requests)
- Integrating with other REST-ful APIs:
    - https://thecatapi.com/
    - https://www.deckofcardsapi.com/
### Assignment 3

### ReactJS
- ReactJS overview and history
- Class vs functional ReactJS
- JSX and DOM manipulation
- React component props, states, refs.
- React Router
- Connecting React FE app to backend APIs

### ReduxJS
- ReduxJS overview and architecture pattern
    - Flux architecture
    - Single source of truth
- Redux store, actions, reducer.
- Integrating Redux with React app.
### Assignment 4 & Project Proposals

### Persisting Data/DBs
- FE vs BE persisting
    - Browser cache/cookies
    - BE caching
- DB setup and basic commands (SQL)
    - Setting up PostgreSQL
    - C.R.U.D operation with DB
- Sequelize ORM
    - What is an Object Relational Mapping?
    - Using Sequelize ORM to Node/ExpressJS
- A look at No-SQL DBs.
    - MongoDB, Firebase (realtime DB)
    - Connecting to MongoDB/Firebase
### Lab Report

### Additional Topics/Studies
- ReactJS testing using react testing library
- RXJS: Realtime JS framework (also available in Java and other languages)
- NextJS: ReactJS with built-in routing
- Deploying webapps to production. Production build using webpacks, deploying backend services & monitoring
- a11y compliance

### Final Project
- Final project presentations

---

## Participation/Presentation

Aside from your final presentation, 10% of your grade will be from a personal/individual presentation work. The web dev field is one that's always evolving, with new technologies/frameworks being adopted every day.

As part of your presentation, you can give a short ~5 min talk/report on what are some of the interesting changes that are happening in our field. This can be anything from a new framework that you picked up, a new JS library, or new technologies being developed that impacts the internet/web dev field.

We will devote the start of the class session (limited to 3 presentations max per class) to presentation, sign up sheet link will be posted on BlackBoard, and are on a first come first serve basis!

---

## Hunter Policies
**_Policy on Academic Integrity:_** Hunter College regards acts of academic dishonesty (e.g. plagiarism, cheating on examinations, obtaining unfair advantage,
and falsification of records and official documents) as serious offenses against
the values of intellectual honesty. The College is committed to enforcing the CUNY Policy on Academic Integrity and will pursue cases of academic dishonesty according to the Hunter College Academic Integrity Procedures.

**_ADA Compliance:_** In compliance with the American Disability Act of 1990
(ADA) and with Section 504 of the Rehabilitation Act of 1973, Hunter College is
committed to ensuring educational parity and accommodations for all students
with documented disabilities and/or medical conditions. It is recommended that
all students with documented disabilities (Emotional, Medical, Physical and/
or Learning) consult the Office of AccessABILITY located in Room E1124 to
secure necessary academic accommodations. For further information and assistance please call (212-772-4857)/TTY (212-650-3230).
Hunter College Policy on Sexual Misconduct: In compliance with the

**_CUNY Policy on Sexual Misconduct_**, Hunter College reaffirms the prohibition
of any sexual misconduct, which includes sexual violence, sexual harassment,
and gender-based harassment retaliation against students, employees, or visitors, as well as certain intimate relationships. Students who have experienced
any form of sexual violence on or off campus (including CUNY-sponsored trips
and events) are entitled to the rights outlined in the Bill of Rights for Hunter
College.

a. Sexual Violence: Students are strongly encouraged to immediately report
the incident by calling 911, contacting NYPD Special Victims Division Hotline
(646-610-7272) or their local police precinct, or contacting the College’s Public
Safety Office (212-772-4444).

b. All Other Forms of Sexual Misconduct: Students are also encouraged
to contact the College’s Title IX Campus Coordinator, Dean John Rose (jtrose@hunter.cuny.edu or 212-650-3262) or Colleen Barry (colleen.barry@hunter.cuny.edu or 212-772-4534) and seek complimentary services through the Counseling
and Wellness Services Office, Hunter East 1123. CUNY Policy on Sexual Misconduct Link: http://www.cuny.edu/about/administration/offices/la/Policy-onSexual-Misconduct-12-1-14-withlinks.pdf

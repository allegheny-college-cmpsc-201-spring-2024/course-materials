![CMPSC 201: Programming Languages origami fish in various states of structural unmaking](https://private-user-images.githubusercontent.com/1552764/296600874-61517376-1325-4491-851b-0e48d3b8d834.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MDUzNzkwMjgsIm5iZiI6MTcwNTM3ODcyOCwicGF0aCI6Ii8xNTUyNzY0LzI5NjYwMDg3NC02MTUxNzM3Ni0xMzI1LTQ0OTEtODUxYi0wZTQ4ZDNiOGQ4MzQucG5nP1gtQW16LUFsZ29yaXRobT1BV1M0LUhNQUMtU0hBMjU2JlgtQW16LUNyZWRlbnRpYWw9QUtJQVZDT0RZTFNBNTNQUUs0WkElMkYyMDI0MDExNiUyRnVzLWVhc3QtMSUyRnMzJTJGYXdzNF9yZXF1ZXN0JlgtQW16LURhdGU9MjAyNDAxMTZUMDQxODQ4WiZYLUFtei1FeHBpcmVzPTMwMCZYLUFtei1TaWduYXR1cmU9NjcyMTRmYzQ3MDQ4Zjc5ZjY3OWM2YmY3NzkyMDk4N2NkYTM5NTYzMGE1NmI4YWM2MDNhMGY2NzU4YzJiODE4NyZYLUFtei1TaWduZWRIZWFkZXJzPWhvc3QmYWN0b3JfaWQ9MCZrZXlfaWQ9MCZyZXBvX2lkPTAifQ.qLrd89bQsEDhRRn_EaOd5Yvx9ZhDsz0Mni9T8pivSUw)

# CMPSC 201: Programming Languages

## Important Resources

* [Office Hours schedule](https://chompe.rs/office-hours)
* [Course Calendar](https://chompe.rs/201-schedule)

## Syllabus

### Course information

#### Meeting times

|Day(s) of Week            |Time          |Purpose     |Location                        |
|--------------------------|--------------|------------|--------------------------------|
|Monday, Wednesday, Friday |10:00 - 10:50 |Activities  |Alden 109                       |
|Monday                    |14:30 - 16:30 |Lab session |Alden 109                       |

### Contact

* Instructor: Douglas Luman
* Email: dluman@allegheny.edu
* Telephone: `+1 814 332 2136`
* Office: Alden Hall, 112 (next to the copier)

### Office hours

|Day(s) of Week            |Time           |          |
|--------------------------|---------------|----------|
|Monday                    | 12:00 - 14:30 |Alden 112 |
|Wednesday                 | 13:00 - 16:00 |Alden 112 |
|Friday                    | 12:00 - 13:30 |Alden 112 |

To reserve a 15-minute slot during the above times, visit my office hours calendar [listed above](#important-resources).

### Canonical course description

A study of the fundamental concepts that arise in different programming language paradigms. Students learn how programming languages 
are designed and implemented, and how these factors affect the overall usability, performance, and effectiveness of computer software. 
Participating in hands-on activities that often require teamwork, students gain experience in leveraging the styles and features of 
programming languages to implement and evaluate correct and efficient computer software. During a weekly laboratory session, students 
use state-of-the-art technology to complete projects, reporting on their results through both written documents and oral presentations. 
Students are invited to use their own departmentally approved laptop in this course; a limited number of laptops are available for 
use during class and lab sessions.

Prerequisite: `CMPSC 101` or `CMPSC 102`.

Distribution Requirements: `QR`, `SP`.

#### Distribution requirements

##### `QR`

Students who successfully complete this requirement will demonstrate an understanding of how to interpret numeric data and/or their 
graphical or symbolic representations.

##### `SP`

Students who successfully complete this requirement will demonstrate an understanding of the nature, approaches, and domain of scientific inquiry.

### Course learning objectives

|Objective |Related Distribution Requirement(s) |
|:---------|:-----------------------------------|
|Correctly identify and describe the steps in the design and implementation of a programming language| `QR`, `SP` |
|Effectively use programming language constructs to design correct, efficient, and well-tested programs in multiple programming languages, including but not limited to Java.| `QR`, `SP` |
|Interpret and use an existing programming language grammar.| `QR` |
|Design, implement, and evaluate a correct scanner and parser for a programming language.| `QR`, `SP` |
|Using knowledge of the general principles of programming languages, correctly implement a computer program in a heretofore unknown programming language. | `QR`, `SP` |

Each of these course learning outcomes support the Allegheny College CIS Department and Software Engineering program learning outcomes which are available
on the [CIS Department's website](https://cis.allegheny.edu).

### Required materials

#### Course resources

This courses uses a free open access textbook, available at the following URL:

* [_Crafting Interpreters_](https://craftinginterpreters.com/contents.html)

#### Platforms

This course relies on your regular use of:

* [GitHub](https://github.com)
* [Discord](https://discord.com)

These two platforms constitute the main channels for class communication and issuing, working on, and evaluating assignments.

### Evaluation

The course relies on three main types of exercises:

|Course assignment |Percentage weight |Course points |
|:-----------------|:-----------------|:-------------|
|Lox repository    |50%               |600 pts       |
|Code golf         |10%               |100 pts       |
|Course project    |40%               |400 pts       |
|**Total**             |**100%**              |**1000 pts**      |

#### Lox

This course uses extra challenges in the [course's textbook](#course-resources) as the main mechanism for assessing student achievement of learning
outcomes. The overwhelming majority of the implementation of the text's novel programming language, Lox, is provided in a single repository. Students
take responsibility for maintaining, updating, and "hacking" on this respository, which serves as one of the main evaluative mechanism of the course.

For the purposes of this course, these challenges are _required_ and not _extra_.

Students earn points for Lox-based assignments based on the `gatorgrade` specifications-grading report.

#### Code golf

On Fridays, students will engage with a "code golf" challenge in which asks them to deploy novel techniques using either a given or student-chosen novel
programming language. In these challenges, students attempt to achieve a provided programming task in _as few bytes as possible_. Often, this leverages
characteristics of programming languages which rely on their design and construction, demonstrating understanding of a wide variety of programming
language design principles and/or paradigms.

Students earn points for code golf challenges by completing challenges. At the end of the semester, students ranking in the top five (5) "golfers" (i.e.
students with the five lowest scores) receive 10% (100) extra credit points.

#### Course project

Students will complete a summative course project which offers three paths:

* Students may choose to implement the Lox interpreter in a language other than Java which implements one additional feature not present in the current Lox implementation
* Students may choose to develop a "code golfing" language which solves the golfing challenges undertaken during the semester
* Students may choose to develop a "golfed" version of the `jlox` interpreter

Students earn points for the course project assignment basd on the `gatorgrade` specifications-grading report.

### Course preparation

I expect students to arrive to class prepared. Here, "prepared" means having completed reading assignments, compiled questions, 
and being ready to engage thoughtfully with course material. In order to assist students' preparedness efforts, I will provide a 
[schedule](#important-resources) with assignments and accompanying materials or readings.

### Allegheny College Statement of Community

Allegheny College also expects students and faculty to act according to its Statement of Community:

> Allegheny students and employees are committed to creating an inclusive, respectful and safe residential learning community 
> that will actively confront and challenge racism, sexism, heterosexism, religious bigotry, and other forms of harassment and 
> discrimination. We encourage individual growth by promoting a free exchange of ideas in a setting that values diversity, trust 
> and equality. So that the right of all to participate in a shared learning experience is upheld, Allegheny affirms its commitment 
> to the principles of freedom of speech and inquiry, while at the same time fostering responsibility and accountability in the 
> exercise of these freedoms. This statement does not replace existing personnel policies and codes of conduct.

### Honor Code

All students and faculty at Allegheny College are bound by the Honor Code. Everyone expects that your behavior reflects this commitment. Given the eminently shareable and reproducible nature of code, the Department of Computer Science adds the following statement to the general college policy:

> It is recognized that an important part of the learning process in any course, and particularly in computer science, derives from 
> thoughtful discussions with teachers, student assistants, and fellow students. Such dialogue is encouraged. However, it is necessary 
> to distinguish carefully between the student who discusses the principles underlying a problem with others, and the student who 
> produces assignments that are identical to, or merely variations on, someone else’s work. It will therefore be understood that all 
> assignments submitted to faculty of the Department of Computer Science are to be the original work of the student submitting the assignment. 
> Appropriate action will be taken when assignments give evidence that they were derived from the work of others.

The above statement, of course, also applies to solutions derived from discussions on Stack Overflow and other similar resources.

#### AI tools

I fully expect that many of you will use tools like OpenAI's GPT code completion, GitHub Co-pilot, and others on assignments. These are professional, industry-grade tools. However, there is a marked difference between implementing the solutions these tools suggest and copying their suggestions wholesale. In many cases, these tools will lead you to either incorrect or significantly advanced answers. As one might say in the consumer trade, _caveat emptor_.

One of the goals of your time in this class, much less at Allegheny, is to learn how the subjects discussed in classes relate and impact your future work. While there are many ways that your assignments will test your understanding of the concepts underlying our coursework, I ask a few of things from you completely aware that you are fully on your own honor with any of these:

* be prepared to explain a detailed understanding of the code you're offering for review, documenting where and how you used an assistant tool in:
  * technical reports
  * code comments, specifically labeling the portions of code derived from use of AI tools
* consider how you might improve an assistant-generated solution, documenting this in reports and implementing your improvements in code
* keep an operating assumption that I'm not reviewing your solutions for a "gotcha"; I only assume the best of your effort

### Classroom ethics

The discipline of computer science, like many others, encourages its members to act according to discipline-specific ethics. I encourage you to take time to review the Association for Computing Machinery (ACM) [Code of Ethics](https://www.acm.org/binaries/content/assets/about/acm-code-of-ethics-booklet.pdf).

### Seeking assistance

#### Assistance with course concepts

Students who struggle to understand knowledge and skills defined in this course are encouraged to seek assistance from instructional staff. To meet with me, consult my available office hours (above) and make an appointment.

Historically, students who are successful in my courses visit and discuss course concepts with instructors or TLs early and often. See [above for my office hours](#office-hours) or go to [this schedule for Technical Leaders' office hours](https://www.cs.allegheny.edu/teaching/technicalleaders/).

#### Assistance outside of the course

If you find yourself in difficult circumstances which affect your ability to participate in or complete course work, let me know immediately. Full stop.

Do not wait until the end of the semester. 

*It is part of my job* to make sure that students receive the assistance they need. Do not hesitate to let me know if there is anything I can do with respect to your ability to handle your work. This is especially true of our current circumstances. Again, let me remind you -- __**it is part of my job**__ to help you access Allegheny College resources that will enable your safety and success.

In many situations, the following list of resources may help:

* [The Maytum Learning Commons](https://sites.allegheny.edu/learningcommons/)
* [Allegheny College Counseling Center](https://sites.allegheny.edu/learningcommons/)
* [The Winslow Health Center](https://sites.allegheny.edu/healthcenter/)
* [Student Life](https://sites.allegheny.edu/studentlife/)

### Special needs and disability

Students with disabilities who need accommodations in this course are encouraged to contact Disability Services at `+1 814-334-2898`. Disability Services is part of the Learning Commons, located in Pelletier Library. Should you need accommodations, contact this office as soon as possible to ensure that approved accommodations are communicated and implemented as quickly as possible. This serves both you and me in providing the best environment for learning and support.

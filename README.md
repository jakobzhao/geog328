# Summer 2023: GEOGRAPHY 328 - Web GIS

**Instructor:** Bo Zhao | zhaobo@uw.edu | Office Hour: Thursdays 1:00 to 4:00 PM by [appointment](https://calendar.google.com/calendar/u/0/selfsched?sstoken=UUZvU2gxXzVlZnZpfGRlZmF1bHR8NzM4ODA5MzUyNjAxZDU2Y2ViNTZiMzk2ZmM0N2VmNzI)

 Web-based Geographic Information Systems (Web GIS), which combines web, mobile technology, and GIS, is a rapidly growing and promising area in both academia and industry. It has expanded the capabilities of GIS from local servers to the cloud, making online maps and geospatial intelligence more accessible to various fields such as geography, built environment, transportation, forestry, and oceanography. The integration of the web and GIS has led to numerous technological advancements, including smart cities, location-based services, autonomous driving, and pandemic dashboards. This course is designed to equip students with the necessary skills for managing web GIS projects, utilizing the latest geospatial cloud technologies for building modern web GIS applications, and providing real-world case studies for inspiration.

**As ChatGPT continues to gain widespread usage in academia and society, this summer course will explore the potential of utilizing it for assisting Web GIS development.** For example, Its natural language interface can simplify development by enhancing productivity and reducing the learning curve. ChatGPT's error analysis and suggestion capabilities can save time and effort in debugging, while its data analysis capabilities can provide insights into patterns and trends. It can also produce GeoJson data for story maps, making web GIS applications more immersive and engaging for users. ChatGPT's user recommendation feature can provide personalized suggestions, enhancing the user experience and accessibility of web GIS applications.

In order to ensure equal access to web mapping technology, we have made sure that all of the Web GIS applications included in the course materials can be executed, debugged, or further developed on both Windows and Mac OSX operating systems. Additionally, all of the required software and packages are either open-source or free to use. The course is divided into two major components: lectures and lab exercises. During the lectures, students will learn about the theories and principles that underlie Web GIS, such as web architecture, front-end coding, responsive design, and web-based spatial analyses. In the labs, students will have the opportunity to put these theories into practice and develop their skills in web programming and web GIS development.

![course cover](assets/img/cover.jpg)

> _This web page is the syllabus. The course schedule might be slightly updated when the quarter unfolds, the latest schedule will be on this web page. Please ensure to check it frequently. If you have any question :raising_hand:, feel free to contact [Dr. Bo Zhao](mail://zhaobo@uw.edu)_

## Course Objectives

- Acquire a comprehensive understanding of the fundamental concepts and principles of web systematic architecture, GIS project management, geospatial data client, server, and web-based spatial analyses.

- Develop the necessary skills to build web-based GIS applications using either open-source or proprietary geospatial web frameworks.

- Demonstrate competence in managing web GIS projects by gaining hands-on experience in web server management (e.g., Apache 2 server, tomcat, etc.), coding with the latest web technologies (e.g., html, css, JavaScript), becoming familiar with web-based geospatial cloud technologies (e.g., MapBox, Leaflet, OpenStreetMap, etc.), and conducting spatial analysis on the web.

- Evaluate the user experience of a real-world web GIS application and reflect on its social implications, such as geo-privacy and geospatial data authenticity.

- Use ChatGPT to assist the design and development of WebGIS applications.

## Weekly Schedule

To get started, you need to [Gear up the working environment](gearup.md). ***Over this quarter, you are expected to read all the assigned reading materials by the end of the Wednesday of each week and complete the lab assignment and quiz by the due day***.

### Week 1: Fundamentals

<!-- June 20 -->

This week introduces you to the fundamentals of Web GIS.To test how well you are familiar with the reading materials and the handouts, you are required to complete the Quiz all by yourself before the due day. Over this quarter, you will frequently use GitHub for synchronizing course material and managing Web GIS project. So, in Lab 1, you will learn to manage a web-based project using GitHub.

-   **Handouts:** [Part 1](modules/module01/module01.pdf) and [Part 2](modules/module02/module02.pdf).
-   **Quiz:** [Web Basics](https://canvas.uw.edu/courses/1655792/quizzes/1874078) `Due by the Thursday, June 22, 23:59 pm PST)`
-   **Lab:** [Project management using GitHub](labs/lab01) `Due by Sunday, June 25, 23:59 pm PST)`
-   **Thinkpiece:** ［Sharing your experience of using ChatGPT or other AI tools in finishing this lab assignment](https://canvas.uw.edu/courses/1655792/discussion_topics/8193934) `Due by Monday, June 26, 23:59 pm PST)`
-   **Readings:** *To help you grasp the gist of the reading material, you can refer to the [study questions 1](modules/module01/readme.md) and [study questions 2](modules/module02/readme.md).*
  
    - [Intro to Web GIS](modules/module01/intro-to-webgis.pdf).
    - [Technical basics of Web GIS](modules/module02/tech-basics.pdf).
    - [Getting started with the web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web). This document introduces you to the practicalities of web development.
    - [The web, web standards](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/The_web_and_web_standards) and [web mechanics](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics).
    - [Git Handbook `Optional`](https://guides.github.com/introduction/git-handbook/). Git is an example of a distributed version control system (DVCS) commonly used for open source and commercial software development. With Git, Developers can work anywhere and collaborate asynchronously from any time zone.
    - [Mastering Markdown `Optional`](https://guides.github.com/features/mastering-markdown/). Markdown is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown.

### Week 2: Front-End Coding

<!-- June 27 -->

This week will introduce you to Front-end coding. You will learn the basics of HTML, CSS and Javascript. HTML is the fundamental technology used to define the structure of a webpage, CSS is used to style the web page, and JavaScript takes the charge of the behaviors of the Web. For web applications, geographical data are stored in the JavaScript Object Notation (JSON) format, or namely GeoJSON. This week will aos introduce you to GeoJSON. Similar to the previous week, we offer a quiz on Front-end coding, and a new lab on how to do responsive design.

-   **Handouts:** [Part 1](modules/module03/module03.pdf) and [Part 2](modules/module04/module04.pdf).
-   **Quiz:** [Front-end Coding](https://canvas.uw.edu/courses/1655792/quizzes/1874080) `Due by Thursday June 29, 23:59 pm PST`.
-   **Lab:** [Responsive web page design](labs/lab02) `Due by Sunday July 2, 23:59 pm PST)`
-   **Thinkpiece:** [Sharing your experience of using ChatGPT or other AI tools in finishing this lab assignment](https://canvas.uw.edu/courses/1655792/discussion_topics/8193936) `Due by Monday July 3, 23:59 pm PST)`
-   **Readings:** *To help you grasp the gist of the reading material, you can refer to the [study questions 1](modules/module03/readme.md) and [study questions 2](modules/module04/readme.md).*
    - [HTML basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML) *(The section on "Debugging HTML" and the two following assessments are not required)* and [Work with Multimedia](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding). *(The section on the assessment is not required).*
    - [CSS basics](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps), [selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors) and [layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Introduction).
    - [JavaScript basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps) and [building blocks](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks).
    - [Working with JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON).
    - [Introduction to GeoJSON](https://en.wikipedia.org/wiki/GeoJSON).

### Week 3: Dig into the Server Side

<!-- July 4 -->

In this week, we will learn the server side of Web GIS. First, we will study geospatial web servers. A geospatial web server plays a significant role in maintaining web based geospatial application. It stays in the cloud and provides multiple services relevant to geospatial data, such as geospatial data indexing, data format conversation, reprojection, and even spatial analyses. In this week, two geospatial web servers are introduced, including Mapbox (Proprietary) and GeoServer (Open Source). In addition, we will introduce how to make basic thematic maps on the web, also practice how to load geospatial data on the web asynchronously.The web based interactive map is built upon MapBox, which is a popular map library. It not only contains fundamental map related functions, but also offers a lot of cool map features for your use and further explore.

-   **Lab:** [Asynchronous GeoJSON data loading and visualization](labs/lab03) `Due by Sunday, July 9, 23:59 pm PST`
-   **Thinkpiece:** [Sharing your experience of using ChatGPT or other AI tools in finishing this lab assignment](https://canvas.uw.edu/courses/1655792/discussion_topics/8193937) `Due by Monday, July 10, 23:59 pm PST`
-   **Readings:** *To help you grasp the gist of the reading material, you can refer to the study questions **`To be added`**.*
    - [Web map service from GeoServer](https://docs.geoserver.org/latest/en/user/services/wms/index.html).
    - [Publish geospatial data on GeoServer](https://docs.geoserver.org/latest/en/user/gettingstarted/shapefile-quickstart/index.html).
    - [Making asynchronous programming easier with async and await](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Async_await) More recent additions to the JavaScript language are async functions and the await keyword, added in ECMAScript 2017. These features basically act as syntactic sugar on top of promises, making asynchronous code easier to write and to read afterwards. They make async code look more like old-school synchronous code, so they're well worth learning. This article gives you what you need to know.
    - [Making thematic map on the web](https://docs.mapbox.com/help/tutorials/create-a-map-with-data-visualization-component/).
    - [Add interactive makers to web maps](https://docs.mapbox.com/help/tutorials/custom-markers-gl-js/).

### Week 4: GIS Analysis on the Web

<!-- July 11 -->

In this week, we will introduce you to a series of GIS analysis, including geographical measurement, nearest neighbor analysis, buffer, and isochrone analysis. These analysis are widely used in GIScience and GIS applications. In addition, we will introduce you to the concept of web mapping application programming interface (API). A web mapping API is a set of programming instructions and standards for accessing web based geospatial data and services. It is a set of routines, protocols, and tools for building software and applications. In this week, you will learn how to use the Mapbox API and Turf.js to perform GIS analysis on the web.

-   **Lab:** [Interactive web mapping](labs/lab04) `Due by Sunday, July 16, 23:59 pm PST`
-   **Thinkpiece:** [Sharing your experience of using ChatGPT or other AI tools in finishing this lab assignment](https://canvas.uw.edu/courses/1655792/discussion_topics/8193938) `Due by Monday, July 17, 23:59 pm PST`
-   **Readings:** *To help you grasp the gist of the reading material, you can refer to the study questions **`To be added`**.*
    - [Sort data by Distance: Part I](https://docs.mapbox.com/help/tutorials/building-a-store-locator/)
    - [Sort data by Distance: Part II](https://docs.mapbox.com/help/tutorials/geocode-and-sort-stores/)
    - [Nearest neighbor analysis](https://docs.mapbox.com/help/tutorials/analysis-with-turf/)
    - [Buffer and isochrone analysis](https://docs.mapbox.com/help/tutorials/get-started-isochrone-api/)

## Course Requirement

**GitHub:** This course material will be hosted on GitHub instead of UW Canvas. On this dedicated GitHub repository, you can find most of the course material, participate in group discussions by submitting GitHub issues, and create new GitHub repositories to turn in the lab deliverables. By the end of this quarter, you will be more proficient in operating a cloud-based coding environment and able to host your work online as a way to gain public and peer attentions.

**Participation:** You should participate in the ad-hoc discussion items and complete all assigned readings and get familiar with the lab instructions before class meetings.

**Quizzes:** There will be two quizzes in this quarter. Each quiz is designed to test your comprehension of new material. Questions may include multiple choice questions, matching questions, fill-in-the-blank questions, and short answer questions.  Before you answer the questions, please read the following instructions carefully:

- You are forbidden to use ChatGPT or any other AI tools to help you answer the questions.
- You’ll have unlimited time.
- You are welcome to use your notes, course material, and online resources, but you are asked to work alone (not in consultation with your classmates).
- You will be given only one attempt at each quiz.
- After completing the quiz, the first time, you'll see which questions you got right and wrong and get feedback on your answer selections.

**Lab Assignments:** You need to finish all four labs by the due date. ***You are encouraged to work on the lab assignments in groups, However, each student should submit their own work. In addition, you are encouraged to use ChatGPT or other AI tools to finish the Lab Assignments.*** If you have any questions about the lab further, please look for tech support from the instructor.

**Thinkpieces:** Every week, you are required to compose a thinkpiece with a minimum length of 350 words and share it on the Canvas discussion board. Your thinkpiece should delve into your utilization of AI tools such as ChatGPT, Github Copilot, or any other relevant tools, in completing the lab assignment. Once you have posted your thinkpiece, please engage with your classmates' contributions by commenting on or liking at least two of their thinkpieces. To grade your work, I will divide the students into three groups based on the number of likes and comments they receive by the end of the following week. For instance, the thinkpiece submitted in the first week will be evaluated at the conclusion of the second week. Self-generated likes and comments will not be considered in the assessment. Students who receive the highest number of likes and comments will be awarded 7 points, while those who secure the second highest number will earn 6 points. The remaining students who submitted a thinkpiece will receive 5 points.

## Grading

| **Grading Items**          | **%**|
| -------------------------- | ---- |
| Participation              |  2%  |
| Lab Assignments            | 40%  |
| Quizzes                    | 30%  |
| ChatGPT Experience Sharing | 28%  |

## Troubleshooting

- Problems with labs and quizzes: visit the office hours of your Instructor.
- Problems with Canvas: Use the Help button on Canvas or contact the UW-IT helpdesk. If you are unable to access Canvas or your problems with Canvas are affecting your ability to submit course assignments, reach out to the instructor via email or Canvas Message.
- Problems with QGIS: You can also stop by your Instructor’s office hours to get help in real-time.  You can also get help through the Suzzallo GIS Lab or the Center for Social Science Computation and Research. Finally, if those don’t work, you can email or Canvas Message your course instructor or TA, being sure to include screenshots of what you are struggling with. 
- Problems with Mapbox, VSCode, or GeoServer: You can also stop by your Instructor’s office hours to get help in real-time. If it still cannot be solved, you can email or Canvas Message your course instructor, being sure to include screenshots of what you are struggling with. 
- Stressed Out: If something about this course is causing you stress or your stress level is affecting your performance in this class, reach out to the course instructor via email or Canvas Message or stop by your instructor’s office hours.  You can find additional help from Student Services or the Counseling Center.
- **E-mail:** is the easiest way of reaching me. I will respond to all e-mails during office hours, and will periodically return e-mail at other times. Please note that the answer to many commonly e-mailed questions can be found in the syllabus or on the course website. Please also note that in order to respond your e-mail you MUST include the following information in every e-mail:

    -  A Salutation (Both Dr. Zhao and Professor Zhao are acceptable)
    -  Your Full Name
    -  What class you are in
    -  Subject line summarizing your e-mail (i.e. “Question regarding Map Design” for example)

## Equity & Inclusivity

Our very highest priorities include creating a brave and supportive class environment where each of us contributes, we can ask big questions, we give and receive critiques in a supportive way, we notice and engage the ways that we are differently situated within past and present relationship of power, privilege and oppression. I invite you to think hard about how race, gender identity, religion, age, citizenship status, first language, ability, sexuality, class, and other axes are at work in our interactions, and what this might mean in terms of when to speak up, when to step back, how to listen, and much more. Each of you is a welcome and invaluable part of our collective whole.

## Disability Accommodations

We welcome the opportunity to work with any students with disabilities in this class to ensure equal access to the course. If you have a letter from Disability Resources for Students (DRS) outlining your academic accommodations, please present the letter to me (or email us, to confirm, if the letter is electronic) as soon as possible so that we can discuss the accommodations you may need for this class. Any discussions between student and professor need to occur as early as possible in order for adequate arrangements to be made. If you do not yet have a letter from DRS, but would like to request academic accommodations due to a disability, please contact DRS [here (Links to an external site.)](https://depts.washington.edu/uwdrs/), or in-person at 011 Mary Gates Hall, or at 206-543-8924 (Voice & Relay), <mailto:uwdrs@uw.edu>.

## Religious Accommodations

Washington state law requires that UW develop a policy for accommodation of student absences or significant hardship due to reasons of faith or conscience, or for organized religious activities. The UW’s policy, including more information about how to request an accommodation, is available at [Religious Accommodations Policy](https://registrar.washington.edu/staffandfaculty/religious-accommodations-policy/). Accommodations must be requested within the first two weeks of this course using the [Religious Accommodations Request form](https://https:/registrar.washington.edu/students/religious-accommodations-request/).

 ## Student Care & Safety

It is important that you take care of yourselves inside and outside of class as you work through stress and other obstacles. There are many different support services on campus that can help, such as the Counseling Center, Hall Health, and the IMA. UW’s Student Care program can help you connect to these and other resources. Learn more an contact them directly: http://depts.washington.edu/livewell/student-care/, livewell@uw.edu, or 206.543.6085. If you are concerned about yourself or a friend who is struggling SafeCampus is a helpful resource. Please add 206.685.7233 to your phones

## Copyright

This course advocates for the open culture. The course materials are open source for both students and open source community to access. This course also builds on the work of Bo Zhao, Xiaoqi "Steven" Bao, among many others, who have designed and taught or TA-ed previous iterations of this course.

Notably, students are not allow to videotape or audio-tape (record) this class in any form, and sharing recordings outside of class without the written consent of each student in the class is not permitted by [FERPA](https://registrar.washington.edu/students/ferpa/). However, I will try to record most of the classes via Zoom and share them via Canvas. Even so, I still encourage each of you attend the lectures instead of watching the recorded videos afterwards. Your in-class participation is a key factor to yield the best learning outcome. The instructor determines if their class can and cannot be recorded. This decision should be clearly communicated by the instructor at the beginning and throughout the quarter. In Zoom, the recording feature can be controlled by the instructor, as the meeting host.

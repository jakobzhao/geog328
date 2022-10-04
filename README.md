# GEOGRAPHY 495B:  Web GIS

**Meetings:**

-   **Lectures:** Tuesdays and Thursdays 1:00 - 2:20 PM SMI 105
-   **Labs:** Friday 12:30 - 1:20 PM (BA) and 1:30 -  1:20 PM (BB) in SMI 401


**Instructional Team:**

-   **Bo Zhao**, Instructor, zhaobo@uw.edu | Office Hour: Thursdays 2:45 to 4:45 PM by [appointment](https://calendar.google.com/calendar/u/0/selfsched?sstoken=UUZvU2gxXzVlZnZpfGRlZmF1bHR8NzM4ODA5MzUyNjAxZDU2Y2ViNTZiMzk2ZmM0N2VmNzI)
-   **Steven Bao**, Teaching Assistant, bxq98@uw.edu |  Office Hour: Mondays 2:30 to 3:30PM at SMI 401 (It is recommended to [make an appointment here](https://calendar.google.com/calendar/u/0/selfsched?sstoken=UURaSkhXOURSSUd4fGRlZmF1bHR8Y2I1OTM0ODUyODg3ZDZiNWZiYjVlOTY3MjhmMWMwYjQ) if you plan to come.)

> _This web page is the syllabus. The course schedule might be slightly updated when the quarter unfolds, the latest schedule will be on this web page. Please ensure to check it frequently. If you have any question :raising_hand:, feel free to contact The TA or [Dr. Bo Zhao](mail://zhaobo@uw.edu)_

![course cover](assets/img/cover.jpg)

Web GIS, the convergence of web, mobile technology, and GIS, is a promising and fast-growing field in academia and industry. It has extended the power of GIS from local servers to the cloud, and put online maps and geospatial intelligence in multiple aspects of human society. In the past decades, multiple disciplines such as geography, built environment, transportation, forestry, and oceanography have benefited from the expanded analytical power of GIS from the local to the web. The integration of the Web and GIS has catalyzed an increasing number of significant technological advances, such as smart cities, location-based services, autonomous driving, or pandemic dashboards. This course provides students with the essential knowledge for web GIS project management, teaches the latest geospatial cloud technologies for building modern web GIS applications, and inspires students with real-world case studies. To promote equal access to web mapping technology, we ensure all the Web GIS applications from course materials can be executed, debugged, or further developed in either Windows or Mac OSX operating systems. And all the required software and packages are open source or free. This course is comprised of two major components, including lectures and lab exercises. The lectures focus on the theories and principles behind Web GIS, including web architecture, front-end coding, responsive design, and web-based spatial analyses. The labs help students to practice what has been learned from the lecture sessions and hone their skills in web programming and web GIS development.

## :dart: Course Objectives

- Grasp the fundamental knowledge of web systematic architecture, GIS project management, geospatial data client, server, and web based spatial analyses.
- Develop web-based GIS applications using either open source or proprietary geospatial web frameworks.
- Demonstrate competence with hands-on experiences in managing web GIS projects (e.g., web server, Apache 2 server, tomcat, etc.), coding with latest web technologies (e.g., html, css, JavaScript), getting familiar with web based geospatial cloud technologies (e.g., MapBox, leaflet, OpenStreetMap, etc.), and conducting spatial analysis on the web.
- Assess the user experience of a real-world web GIS application, and reflect upon its social implications (e.g., geo-privacy, geospatial data authenticity, etc.)


## :calendar: Weekly Schedule

- **Preparation:** [Gear up the working environment](gearup.md) :computer: :beer:
- **Weekly Expectations:** Each student is supposed to a) attend both lecture and lab sections each week, b) complete all weekly readings before the lecture begins.

### Week 1: Intro to Web GIS

<!-- Oct 3 -->

The lecture sessions in this week introduces you to the fundamentals of Web GIS. Over this quarter, you will frequently use GitHub for synchronizing course material and managing Web GIS project. So, in Lab 1, you will learn to manage a web-based project using GitHub.

-   **Readings:** 
    - [Intro to Web GIS](https://canvas.uw.edu/courses/1604818/files/folder/assets?preview=81407677)
    - [Git Handbook `Optional`](https://guides.github.com/introduction/git-handbook/). Git is an example of a distributed version control system (DVCS) commonly used for open source and commercial software development. With Git, Developers can work anywhere and collaborate asynchronously from any time zone.
    - [Mastering Markdown `Optional`](https://guides.github.com/features/mastering-markdown/). Markdown is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. 
    - `To grasp the gist of the reading material, you can refer to the` [study questions](modules/module01/readme.md) `of this week.`

    

-   **Lab 1:** [Project management using GitHub](labs/lab01) `Due by the end of week 1 (Oct. 9th, 23:59)`

### Week 2: Web Fundamentals

<!-- Oct 10 -->

Today, almost everyone has used the Internet. To develop Web applications by yourselves, you need to dive into some fundamental concepts. So, in this week, you will learn the basics of the web environment, its mechanics and standards. To maximize your learning outcome, we encourage you to read over the reading materials before the lectures. To test how well you are familiar with the materials and the lecture content, you are required to complete the Quiz 1 all by yourself before the due day.
    
-   **Readings:**
    - [Getting started with the web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web). This document introduces you to the practicalities of web development. 
    - [The web and web standards](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/The_web_and_web_standards). This article provides some useful background on the Web — how it came about, what web standard technologies are, how they work together, why "web developer" is a great career to choose, and what kinds of best practices you'll learn about through the course.
    - [Common questions on Web mechanics](https://developer.mozilla.org/en-US/docs/Learn/Common_questions#web_mechanics). This document covers questions relating to general knowledge of the web ecosystem and how it works.
    - [Technical basics of Web GIS](https://canvas.uw.edu/courses/1604818/files/folder/assets?preview=81660132)
    - `To grasp the gist of the reading material, you can refer to the` [study questions](modules/module02/readme.md) `of this week.`

-  [Lecture Slides](modules/module02/module02.pdf) 

-   **Quiz 1:** [Web Basics](https://canvas.uw.edu/courses/1604818/quizzes/1748487) `Due by the end of week 2 (Oct. 16th, 23:59)`


### Week 3: Front-end Coding: HTML and CSS

<!-- Oct 17 -->

To build websites, you should know about HTML, CSS and JavaScript. HTML is the fundamental technology used to define the structure of a webpage, CSS is used to style the web page, and JavaScript takes the charge of the behaviors of the Web. We will spend two weeks to focus on these three primary coding languages of the Web. This week mainly introduces you to HTML and CSS. To evaluate your learning outcomes, we offered a quiz and a lab for your practice.

-   **Readings:** 
    - [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML). This document sets the stage, getting you used to important concepts and syntax, looking at applying HTML to text, how to create hyperlinks, and how to use HTML to structure a webpage. *The section on "Debugging HTML" and the two following assessments are not required.* 
    - [Multimedia and embedding](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding) This document explores how to use HTML to include multimedia in your web pages, including the different ways that images can be included, and how to embed video, audio, and even entire other webpages. *The section on the assessment is not required.* 
    - [CSS First Steps](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps) CSS (Cascading Style Sheets) is used to style and lay out web pages — for example, to alter the font, color, size, and spacing of your content, split it into multiple columns, or add animations and other decorative features. This module provides a gentle beginning to your path towards CSS mastery with the basics of how it works, what the syntax looks like, and how you can start using it to add styling to HTML.
    - [CSS Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors) In CSS, selectors are used to target the HTML elements on our web pages that we want to style. There are a wide variety of CSS selectors available, allowing for fine-grained precision when selecting elements to style. In this article and its sub-articles we'll run through the different types in great detail, seeing how they work.
    - [Introduction to CSS layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Introduction) This article will recap some of the CSS layout features we've already touched upon in previous modules, such as different display values, as well as introduce some of the concepts we'll be covering throughout this module.
    - `To grasp the gist of the reading material, you can refer to the` [study questions](modules/module03/readme.md) `of this week.`
-   [Lecture Slides](modules/module03/module03.pdf) 
-   **Quiz 2:** [HTML Fundamentals](https://canvas.uw.edu/courses/1604818/quizzes/1748488) `Due by the end of week 3 (Oct. 23rd, 23:59)`
-   **Quiz 3:** [CSS Fundamentals](https://canvas.uw.edu/courses/1604818/quizzes/1748485) `Due by the end of week 3 (Oct. 23rd, 23:59)` 
-   **Lab 2:** [Responsive web page design](labs/lab02) `Due by the end of week 4 (Oct. 30th, 23:59)`


### Week 4: Front-end Coding: Javascript and GeoJSON

In this week, we will focus on learning JavaScript. Also, for web applications, geographical data are stored in the JavaScript Object Notation (JSON) format, or namely GeoJSON. This week will introduce you to the general format of GeoJSON, demonstrate how to asynchronously load GeoJSON data to your Web GIS application. Similar to the previous week, we offer a quiz on JavaScript and a new lab on how to load, parse and map GeoJSON data on the web.

<!-- Oct 24 -->

-   **Readings:** 
    - [JavaScript First Steps](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps). In this document,we first answer some fundamental questions such as "what is JavaScript?", "what does it look like?", and "what can it do?", before moving on to taking you through your first practical experience of writing JavaScript. After that, we discuss some key building blocks in detail, such as variables, strings, numbers and arrays.

    - [Javascript Building Blocks](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks). In this document, we continue our coverage of all JavaScript's key fundamental features, turning our attention to commonly-encountered types of code blocks such as conditional statements, loops, functions, and events. You've seen this stuff already in the course, but only in passing — here we'll discuss it all explicitly.


    - [Working with JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON). JavaScript Object Notation (JSON) is a standard text-based format for representing structured data based on JavaScript object syntax. It is commonly used for transmitting data in web applications (e.g., sending some data from the server to the client, so it can be displayed on a web page, or vice versa). You'll come across it quite often, so in this article we give you all you need to work with JSON using JavaScript, including parsing JSON so you can access data within it, and creating JSON.
    
    - [Making asynchronous programming easier with async and await](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Async_await) More recent additions to the JavaScript language are async functions and the await keyword, added in ECMAScript 2017. These features basically act as syntactic sugar on top of promises, making asynchronous code easier to write and to read afterwards. They make async code look more like old-school synchronous code, so they're well worth learning. This article gives you what you need to know.
    
    - [GeoJSON](https://en.wikipedia.org/wiki/GeoJSON). GeoJSON is an open standard format designed for representing simple geographical features, along with their non-spatial attributes. It is based on the JSON format. In addition, a notable offspring of GeoJSON is TopoJSON, an extension of GeoJSON that encodes geospatial topology and that typically provides smaller file sizes.
    - `To grasp the gist of the reading material, you can refer to the` [study questions](modules/module04/readme.md) `of this week.`

-  [Lecture Slides](modules/module04/module04.pdf) 

-  **Presentation 1 & 2**

-   **Quiz 4:** [Javascript Fundamentals](https://canvas.uw.edu/courses/1604818/quizzes/1748486) `Due by the end of week 4 (Oct. 30th, 23:59)`
-   **Lab 3:** [Asynchronous GeoJSON data loading and visualization](labs/lab03) `Due by the end of week 6 (Nov. 13th, 23:59)`
-   **Thinkpiece #1**: Main article - [Mapping COVID-19: How web-based maps contribute to the infodemic](readings/thinkpiece1/Dialogues-in-Human-Geography-2020-Mooney-Juhasz-Mapping-COVID-19-How-web-based-maps-contribute-to-the-infodemic.pdf), [Extended readings](readings/thinkpiece1) `Thinkpiece #1 post due by the end of week 5 (Nov. 6th, 23:59)` `Thinkpiece #1 comments due by the end of week 6 (Nov. 13th, 23:59)`


### Week 5: Geospatial Web Server

In this week, we will focus on geospatial web servers. A geospatial web server plays a significant role in maintaining web based geospatial application. It stays in the cloud and provides multiple services relevant to geospatial data, such as geospatial data indexing, data format conversation, reprojection, and even spatial analyses. In this week, two geospatial web servers are introduced, including Mapbox (Proprietary) and GeoServer (Open Source).

<!-- Oct 31 --> 
<!-- needs to be covered by Steven due to my travel demands -->

-   **Presentation 3 & 4**
-   **Readings:**
    - [Web map service from GeoServer](https://docs.geoserver.org/latest/en/user/services/wms/index.html)
    - [Publish geospatial data on GeoServer](https://docs.geoserver.org/latest/en/user/gettingstarted/shapefile-quickstart/index.html)
    - starting from this week, we will have active learnings in class. So please make sure read the reading materials before class. Here in a list of [active learning activities](modules/module05/readme.md) that will be demonstrated in the lecture session.


### Week 6 : Thematic Map Design on the Web

In this week, we will introduce you to map making on the web. The web based interactive map is built upon MapBox, which is a popular map library. It not only contains fundamental map related functions, but also offers a lot of cool map features for your use and further explore. We will walk you through at least two MapBox applications, and you will use MapBox to make an interactive web map in the lab session too.

<!-- Nov 7 -->

-   **Presentation 5 & 6**
-   **Readings:**
    - [Making thematic map on the web](https://docs.mapbox.com/help/tutorials/create-a-map-with-data-visualization-component/)
    - [Add interactive makers to web maps](https://docs.mapbox.com/help/tutorials/custom-markers-gl-js/)
    list of [active learning activities](modules/module06/readme.md) that will be demonstrated in the lecture session.
-   **Lab 4:** [Interactive web mapping](labs/lab04) `Due by the end of week 8 (Nov. 27th, 23:59)`
-   **Thinkpiece #2**: Main article - [Humanistic GIS: Toward a Research Agenda](readings/thinkpiece2/Humanistic-GIS-Toward-a-Research-Agenda.pdf), [Extended readings](readings/thinkpiece2) `Thinkpiece #2 post due by the end of week 7 (Nov. 20th, 23:59)` `Thinkpiece #2 comments due by the end of week 8 (Nov. 27th, 23:59)`



### Week 7 : Geocoding 

Starting from this week to the last week, we will dive into a series of lectures on web-based spatial analysis. In this week, we will introduce you to web-based geocoding using MapBox Geocoding API. The Mapbox Geocoding API allows you to make forward geocoding, which means that a text query like University of Washington gets turned into longitude and latitude coordinates. But sometimes it's not enough to find query results. Often, you want the geocoder to find query results that are biased toward a location, limited to a specific area, or both.

<!-- Nov 14 -->

-   **Presentation 7 & 8**
-   **Readings:** 
    - [Local search with the Geocoding API](https://docs.mapbox.com/help/tutorials/local-search-geocoding-api/)


### Week 8 : Web-based Spatial Analysis I: Sorting by Distance

In this week, we will introduce you to a basic spatial analysis that uses distance to sort geographical data. This application is made upon MapBox too. Starting from this week, you will work on your final project. Its requirement will be introduced in this week's lab session. In short, you will need to make an advanced spatial analysis to deal with a real-world problem.

<!-- Nov 21 -->

<!-- Nov 24, 25 holiday, thursday and friday -->

-   **Readings:** 
    - [Sort data by Distance: Part I](https://docs.mapbox.com/help/tutorials/building-a-store-locator/)
    - [Sort data by Distance: Part II](https://docs.mapbox.com/help/tutorials/geocode-and-sort-stores/)
-   **Final Project:** [Web GIS Application](project/readme.md) 
-   **Final Project Checkpoint #1**: [Project proposal](https://github.com/jakobzhao/geog495/tree/main/project#week-8---checkpoint-1-project-proposal-due-by-the-end-of-week-8-15-pts) `Due by the end of week 8 (Nov. 13th, 23:59)`

### Week 9 : Dealing with Time on the Web

In this week, we will introduce how to deal with time on the web. The instructor will walk you through a more complicated application that illustrate how geographical data changes over time. In the lab session, you will continue to work on your final project.

<!-- Nov 28 -->

-   **Presentation 9 & 10**
-   **Readings:** 
    [Visualize geographical changes over time](https://docs.mapbox.com/help/tutorials/show-changes-over-time/)
-   **Final Project Checkpoint #2**: [Data preparation](https://github.com/jakobzhao/geog495/tree/main/project#week-9---checkpoint-2-data-preparation-due-by-the-end-of-week-9-10pts) `Due by the end of week 9 (Dec. 4th, 23:59)`


### Week 10 : Web-based Spatial Analysis II

This week will focus on web-based spatial analysis. One is on nearest neighbor analysis and the second is on buffer and isochrone analysis. In the last lecturer, the instructor will summarize this course and provide you a few emerging topics in Web GIS.

<!-- Dec 5 -->

-   **Readings:** 
    - [Nearest neighbor analysis](https://docs.mapbox.com/help/tutorials/analysis-with-turf/)
    - [Buffer and isochrone analysis](https://docs.mapbox.com/help/tutorials/get-started-isochrone-api/)


<!-- ### Week 11 : Summary

**The lecture on Tuesday will be cancelled.** Then you can focus on your final project. In the second lecture of this week, the instructor will share with you a summary of this course and some emerging topics that you can explore in the future.  -->



## :bell: Course Requirement

**GitHub:** This course material will be hosted on GitHub instead of UW Canvas. On this dedicated GitHub repository, you can find most of the course material, participate in group discussions by submitting GitHub issues, and create new GitHub repositories to turn in the lab deliverables. By the end of this quarter, you will be more proficient in operating a cloud-based coding environment and able to host your work online as a way to gain public and peer attentions.

**Participation:** You should complete all assigned readings and get familiar with the lab instructions before class meetings, and actively participate in critical discussions of those readings.

**In-class presentation:** Each group will lead the presentation about an assigned topic at least once throughout this quarter. We will start assign the group presentation assignment in Week 4. Each group will present an pre-assigned web GIS related example or tutorial. If you prepare slides for the presentation, please send it to the instructor before class via email.

**Think Pieces:** For week 5 and 7, there will be reading assignments. To evaluate your reflection upon each week's reading material, we set up a discussion board for the weeks. You need to submit your written response (think piece) to the assigned readings. Your think pieces should be at least 350 words and engage substantially with the reading materials, and connections to the lab assignments and lectures. Guiding questions or prompts will be included in each week's discussion section on canvas to help frame your thinking. After each think piece post is due, you will have one week to read your classmates' thinkpieces and then provide comments or thoughts on your classmates thoughts. You should submit at least two meaningful comments, with each of them being 100 words or more. Submit your think pieces on Canvas in the applicable week's discussion section (https://canvas.uw.edu/courses/1434645/discussion_topics).

**Quizzes:** There will be three quizzes before Week 5. Each quiz is designed not only to test your comprehension of new material. Questions may include multiple choice questions, matching questions, fill-in-the-blank questions, and short answer questions.  

- You’ll have unlimited time.
- You are welcome to use your notes, course material, and online resources, but you are asked to work alone (not in consultation with your classmates).
- You will be given only one attempt at each quiz.
- After completing the quiz, the first time, you'll see which questions you got right and wrong and get feedback on your answer selections.

**Lab Assignments:** You need to finish all four labs by the due date. To help you work on each lab, we will walk through most of the labs during the lab sessions. If you have any questions about the lab, please look for tech support from the TA

**Final Project:**  Final project will be conducted by a group of 4 to 5 students who are from the same Lab session. It needs to be submitted by June 8th, 11:59pm. Check out [the detailed requirement for final project](project/readme.md).


## :heavy_check_mark: Grading

| Grading items         | %    |
| --------------------- | ---- |
| Participation         | 4%   |
| In-class Presentation | 6%   |
| Thinkpiece            | 10%  |
| Quizzes               | 20%  |
| Lab Assignments       | 40%  |
| Final Project         | 20%  |

> The item `participation` includes your participation in the class (e.g., self-introduction, answer questions in class, etc.) and/or your response on GitHub issues (ask questions via GitHub issue, and help your classmates using the GitHub issues function).

## 🛠️: Troubleshooting

- Problems with labs and quizzes: visit the office hours of your TA. 
- Problems with Canvas: Use the Help button on Canvas or contact the UW-IT helpdesk. If you are unable to access Canvas or your problems with Canvas are affecting your ability to submit course assignments, reach out to the TA or instructor via email or Canvas Message.
- Problems with QGIS:  You can also stop by your TA’s office hours to get help in real-time.  You can also get help through the Suzzallo GIS Lab or the Center for Social Science Computation and Research. Finally, if those don’t work, you can email or Canvas Message your course instructor or TA, being sure to include screenshots of what you are struggling with. 
- Problems with Mapbox, VSCode, or GeoServer: You can also stop by your TA’s office hours to get help in real-time.  If it still cannot be solved, you can email or Canvas Message your course instructor, being sure to include screenshots of what you are struggling with. 
- Stressed Out: If something about this course is causing you stress or your stress level is affecting your performance in this class, reach out to the course instructor via email or Canvas Message or stop by your instructor’s office hours.  You can find additional help from Student Services or the Counseling Center.


**E-mail:** is the easiest way of reaching me. I will respond to all e-mails during office hours, and will periodically return e-mail at other times. Please note that the answer to many commonly e-mailed questions can be found in the syllabus or on the course website. Please also note that in order to respond your e-mail you MUST include the following information in every e-mail:

    -  A Salutation (Both Dr. Zhao and Professor Zhao are acceptable)
    -  Your Full Name
    -  What class you are in
    -  Subject line summarizing your e-mail (i.e. “Question regarding Map Design” for example)

## :notebook_with_decorative_cover: Equity & Inclusivity

Our very highest priorities include creating a brave and supportive class environment where each of us contributes, we can ask big questions, we give and receive critiques in a supportive way, we notice and engage the ways that we are differently situated within past and present relationship of power, privilege and oppression. I invite you to think hard about how race, gender identity, religion, age, citizenship status, first language, ability, sexuality, class, and other axes are at work in our interactions, and what this might mean in terms of when to speak up, when to step back, how to listen, and much more. Each of you is a welcome and invaluable part of our collective whole.

## :love_letter: Disability Accommodations

We welcome the opportunity to work with any students with disabilities in this class to ensure equal access to the course. If you have a letter from Disability Resources for Students (DRS) outlining your academic accommodations, please present the letter to me (or email us, to confirm, if the letter is electronic) as soon as possible so that we can discuss the accommodations you may need for this class. Any discussions between student and professor need to occur as early as possible in order for adequate arrangements to be made. If you do not yet have a letter from DRS, but would like to request academic accommodations due to a disability, please contact DRS [here (Links to an external site.)](https://depts.washington.edu/uwdrs/), or in-person at 011 Mary Gates Hall, or at 206-543-8924 (Voice & Relay), <mailto:uwdrs@uw.edu>.

## :church:  Religious Accommodations

Washington state law requires that UW develop a policy for accommodation of student absences or significant hardship due to reasons of faith or conscience, or for organized religious activities. The UW’s policy, including more information about how to request an accommodation, is available at [Religious Accommodations Policy](https://registrar.washington.edu/staffandfaculty/religious-accommodations-policy/). Accommodations must be requested within the first two weeks of this course using the [Religious Accommodations Request form](https://https:/registrar.washington.edu/students/religious-accommodations-request/).

 ## :memo:  Student Care & Safety

It is important that you take care of yourselves inside and outside of class as you work through stress and other obstacles. There are many different support services on campus that can help, such as the Counseling Center, Hall Health, and the IMA. UW’s Student Care program can help you connect to these and other resources. Learn more an contact them directly: http://depts.washington.edu/livewell/student-care/, livewell@uw.edu, or 206.543.6085. If you are concerned about yourself or a friend who is struggling SafeCampus is a helpful resource. Please add 206.685.7233 to your phones

## :book: Copyright

This course advocates for the open culture. The course materials are open source for both students and open source community to access.

This course also builds on the work of Bo Zhao, Xiaoqi "Steven" Bao, among others, who have designed and taught or TA-ed previous iterations of this course. 

Notably, students are not allow to videotape or audio-tape (record) this class in any form, and sharing recordings outside of class without the written consent of each student in the class is not permitted by [FERPA](https://registrar.washington.edu/students/ferpa/). However, I will try to record most of the classes via Zoom and share them via Canvas. Even so, I still encourage each of you attend the lectures instead of watching the recorded videos afterwards. Your in-class participation is a key factor to yield the best learning outcome. The instructor determines if their class can and cannot be recorded. This decision should be clearly communicated by the instructor at the beginning and throughout the quarter. In Zoom, the recording feature can be controlled by the instructor, as the meeting host.

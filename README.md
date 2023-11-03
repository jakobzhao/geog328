# Autumn 2023: GEOGRAPHY 328 - Web GIS

-   **Lectures:** Tuesdays and Thursdays 1:00 - 2:20 PM LOW 205
-   **Labs:** Friday 12:30 - 1:20 PM (AA) and 1:30 -  2:20 PM (AB) in SMI 401

**Instructional Team:**

-   **Bo Zhao**, Instructor, zhaobo@uw.edu | Office Hour: Thursdays 2:45 to 4:45 PM, making a appointment [here](https://t.ly/7nWDj)
-   **Liz Peng**, Teaching Assistant, lp36@uw.edu |  Office Hour: Wednesdays 1:00 to 3:00 PM, SMI 430


 Web-based Geographic Information Systems (Web GIS), which combines web, mobile technology, and GIS, is a rapidly growing and promising area in both academia and industry. It has expanded the capabilities of GIS from local servers to the cloud, making online maps and geospatial intelligence more accessible to various fields such as geography, built environment, transportation, forestry, and oceanography. The integration of the web and GIS has led to numerous technological advancements, including smart cities, location-based services, autonomous driving, and pandemic dashboards. This course is designed to equip students with the necessary skills for managing web GIS projects, utilizing the latest geospatial cloud technologies for building modern web GIS applications, and providing real-world case studies for inspiration.

**As ChatGPT continues to gain widespread usage in academia and society, this course will explore the potential of utilizing it for assisting Web GIS development.** For example, Its natural language interface can simplify development by enhancing productivity and reducing the learning curve. ChatGPT's error analysis and suggestion capabilities can save time and effort in debugging, while its data analysis capabilities can provide insights into patterns and trends. It can also produce GeoJson data for story maps, making web GIS applications more immersive and engaging for users. ChatGPT's user recommendation feature can provide personalized suggestions, enhancing the user experience and accessibility of web GIS applications.

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


### Week 1: Intro to Web GIS

<!-- Oct 2 -->

The lecture sessions in this week introduces you to the fundamentals of Web GIS. Over this quarter, you will frequently use GitHub for synchronizing course material and managing Web GIS project. So, in Lab 1, you will learn to manage a web-based project using GitHub.

-   **Readings:** 
    - [Intro to Web GIS](https://canvas.uw.edu/courses/1675206/files/folder/assets?preview=109758124)
    - [Git Handbook `Optional`](https://guides.github.com/introduction/git-handbook/). Git is an example of a distributed version control system (DVCS) commonly used for open source and commercial software development. With Git, Developers can work anywhere and collaborate asynchronously from any time zone.
    - [Mastering Markdown `Optional`](https://guides.github.com/features/mastering-markdown/). Markdown is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. 
    - `To grasp the gist of the reading material, you can refer to the` [study questions](modules/module01/readme.md) `of this week.`
-  [Lecture Slides](modules/module01/module01.pdf) 

    

-   **Lab 1:** [Project management using GitHub](labs/lab01) `Due by the end of week 1 (Oct. 8th, 23:59)`

### Week 2: Web Fundamentals

<!-- Oct 9 -->

Today, almost everyone has used the Internet. To develop Web applications by yourselves, you need to dive into some fundamental concepts. So, in this week, you will learn the basics of the web environment, its mechanics and standards. To maximize your learning outcome, we encourage you to read over the reading materials before the lectures. To test how well you are familiar with the materials and the lecture content, you are required to complete the Quiz 1 all by yourself before the due day.
    
-   **Readings:**
    - [Getting started with the web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web). This document introduces you to the practicalities of web development. 
    - [The web and web standards](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/The_web_and_web_standards). This article provides some useful background on the Web — how it came about, what web standard technologies are, how they work together, why "web developer" is a great career to choose, and what kinds of best practices you'll learn about through the course.
    - [Common questions on Web mechanics](https://developer.mozilla.org/en-US/docs/Learn/Common_questions#web_mechanics). This document covers questions relating to general knowledge of the web ecosystem and how it works.
    - [Technical basics of Web GIS](https://canvas.uw.edu/courses/1675206/files/folder/assets?preview=109758127)
    - `To grasp the gist of the reading material, you can refer to the` [study questions](modules/module02/readme.md) `of this week.`

-  [Lecture Slides](modules/module02/module02.pdf) 

-   **Quiz 1:** [Web Basics](https://canvas.uw.edu/courses/1604818/quizzes/1748487) `Due by the end of week 2 (Oct. 15th, 23:59)`


### Week 3: Front-end Coding: HTML and CSS

<!-- Oct 16 -->

To build websites, you should know about HTML, CSS and JavaScript. HTML is the fundamental technology used to define the structure of a webpage, CSS is used to style the web page, and JavaScript takes the charge of the behaviors of the Web. We will spend two weeks to focus on these three primary coding languages of the Web. This week mainly introduces you to HTML and CSS. To evaluate your learning outcomes, we offered a quiz and a lab for your practice.

-   **Readings:** 
    - [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML). This document sets the stage, getting you used to important concepts and syntax, looking at applying HTML to text, how to create hyperlinks, and how to use HTML to structure a webpage. *The section on "Debugging HTML" and the two following assessments are not required.* 
    - [Multimedia and embedding](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding) This document explores how to use HTML to include multimedia in your web pages, including the different ways that images can be included, and how to embed video, audio, and even entire other webpages. *The section on the assessment is not required.* 
    - [CSS First Steps](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps) CSS (Cascading Style Sheets) is used to style and lay out web pages — for example, to alter the font, color, size, and spacing of your content, split it into multiple columns, or add animations and other decorative features. This module provides a gentle beginning to your path towards CSS mastery with the basics of how it works, what the syntax looks like, and how you can start using it to add styling to HTML.
    - [CSS Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors) In CSS, selectors are used to target the HTML elements on our web pages that we want to style. There are a wide variety of CSS selectors available, allowing for fine-grained precision when selecting elements to style. In this article and its sub-articles we'll run through the different types in great detail, seeing how they work.
    - [Introduction to CSS layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Introduction) This article will recap some of the CSS layout features we've already touched upon in previous modules, such as different display values, as well as introduce some of the concepts we'll be covering throughout this module.
    - `To grasp the gist of the reading material, you can refer to the` [study questions](modules/module03/readme.md) `of this week.`
-   [Lecture Slides](modules/module03/module03.pdf) 
-   **Quiz 2:** [HTML Fundamentals](https://canvas.uw.edu/courses/1604818/quizzes/1748488) `Due by the end of week 3 (Oct. 22nd, 23:59)`
-   **Quiz 3:** [CSS Fundamentals](https://canvas.uw.edu/courses/1604818/quizzes/1748485) `Due by the end of week 3 (Oct. 22nd, 23:59)` 
-   **Lab 2:** [Responsive web page design](labs/lab02) `Due by the end of week 4 (Oct. 29th, 23:59)`


### Week 4: Front-end Coding: Javascript and GeoJSON

In this week, we will focus on learning JavaScript. Also, for web applications, geographical data are stored in the JavaScript Object Notation (JSON) format, or namely GeoJSON. This week will introduce you to the general format of GeoJSON, demonstrate how to asynchronously load GeoJSON data to your Web GIS application. Similar to the previous week, we offer a quiz on JavaScript and a new lab on how to load, parse and map GeoJSON data on the web.

<!-- Oct 23 -->

-   **Readings:** 
    - [JavaScript First Steps](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps). In this document,we first answer some fundamental questions such as "what is JavaScript?", "what does it look like?", and "what can it do?", before moving on to taking you through your first practical experience of writing JavaScript. After that, we discuss some key building blocks in detail, such as variables, strings, numbers and arrays.

    - [Javascript Building Blocks](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks). In this document, we continue our coverage of all JavaScript's key fundamental features, turning our attention to commonly-encountered types of code blocks such as conditional statements, loops, functions, and events. You've seen this stuff already in the course, but only in passing — here we'll discuss it all explicitly.


    - [Working with JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON). JavaScript Object Notation (JSON) is a standard text-based format for representing structured data based on JavaScript object syntax. It is commonly used for transmitting data in web applications (e.g., sending some data from the server to the client, so it can be displayed on a web page, or vice versa). You'll come across it quite often, so in this article we give you all you need to work with JSON using JavaScript, including parsing JSON so you can access data within it, and creating JSON.
    
    - [Making asynchronous programming easier with async and await](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Async_await) More recent additions to the JavaScript language are async functions and the await keyword, added in ECMAScript 2017. These features basically act as syntactic sugar on top of promises, making asynchronous code easier to write and to read afterwards. They make async code look more like old-school synchronous code, so they're well worth learning. This article gives you what you need to know.
    
    - [GeoJSON](https://en.wikipedia.org/wiki/GeoJSON). GeoJSON is an open standard format designed for representing simple geographical features, along with their non-spatial attributes. It is based on the JSON format. In addition, a notable offspring of GeoJSON is TopoJSON, an extension of GeoJSON that encodes geospatial topology and that typically provides smaller file sizes.
    - `To grasp the gist of the reading material, you can refer to the` [study questions](modules/module04/readme.md) `of this week.`

-  [Lecture Slides](modules/module04/module04.pdf) 

-  **Quiz 4:** [Javascript Fundamentals](https://canvas.uw.edu/courses/1604818/quizzes/1748486) `Due by the end of week 4 (Oct. 29th, 23:59)`
-  **Lab 3:** [Asynchronous GeoJSON data loading and visualization](labs/lab03) `Due by the end of week 6 (Nov. 12th, 23:59)`
-  **Thinkpiece #1**: Main article - [Mapping COVID-19: How web-based maps contribute to the infodemic](readings/thinkpiece1/Dialogues-in-Human-Geography-2020-Mooney-Juhasz-Mapping-COVID-19-How-web-based-maps-contribute-to-the-infodemic.pdf), [Extended readings](readings/thinkpiece1) `Thinkpiece #1 post due by the end of week 5 (Nov. 5th, 23:59)` `Thinkpiece #1 comments due by the end of week 6 (Nov. 12th, 23:59)`


### Week 5: Geospatial Web Server

In this week, we will focus on geospatial web servers. A geospatial web server plays a significant role in maintaining web based geospatial application. It stays in the cloud and provides multiple services relevant to geospatial data, such as geospatial data indexing, data format conversation, reprojection, and even spatial analyses. In this week, two geospatial web servers are introduced, including Mapbox (Proprietary) and GeoServer (Open Source).

<!-- Oct 30 -->

-  **Presentation**
   -  Tuesday, Oct 31: [Debugging](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools), Walkthrough the debugging steps with example(s)
   -  Thursday, Nov 2: [Chroma.js](https://gka.github.io/chroma.js/),How to use the library (on maps), Color Schemes for maps, Some examples of creative use of map colors, (Optional) how to create legend on web maps

-   **Readings:**
    - [Web map service from GeoServer](https://docs.geoserver.org/latest/en/user/services/wms/index.html)
    - [Publish geospatial data on GeoServer](https://docs.geoserver.org/latest/en/user/gettingstarted/shapefile-quickstart/index.html)
    - starting from this week, we will have active learnings in class. So please make sure read the reading materials before class. Here in a list of [active learning activities](modules/module05/readme.md) that will be demonstrated in the lecture session.
    - **Instructions for GeoServer Installation on Windows and Mac** If you are using Windows, please download the MSI file for [the stable version of GeoServer](https://geoserver.org/release/stable/) and proceed with the installation. For Mac users, download the [Platform Independent Binary version](https://geoserver.org/release/stable/) instead. Regardless of your operating system, it's essential to [install Eclipse Adoptium's OpenJDK](https://adoptium.net/temurin/releases/?version=11) beforehand to ensure a successful GeoServer installation. Please ensure you download version 11 of OpenJDK, as the latest version (version 2*) is not compatible. Mac users can follow [this tutorial](https://docs.geoserver.org/2.19.x/en/user/installation/osx_binary.html) for detailed instructions on installing GeoServer, as well as starting and shutting it down.

-   **[Final Project](project/readme.md):** Introduce the requirements of the final project.

### Week 6 : Thematic Map Design on the Web

In this week, we will introduce you to map making on the web. The web based interactive map is built upon MapBox, which is a popular map library. It not only contains fundamental map related functions, but also offers a lot of cool map features for your use and further explore. We will walk you through at least two MapBox applications, and you will use MapBox to make an interactive web map in the lab session too.

<!-- Nov 6 -->

-   **Readings:**
    - [Making thematic map on the web](https://docs.mapbox.com/help/tutorials/create-a-map-with-data-visualization-component/)
    - [Add interactive makers to web maps](https://docs.mapbox.com/help/tutorials/custom-markers-gl-js/)
    list of [active learning activities](modules/module06/readme.md) that will be demonstrated in the lecture session.
-   **Lab 4:** [Interactive web mapping](labs/lab04) `Due by the end of week 8 (Nov. 26th, 23:59)`
-   **Thinkpiece #2**: Main article - [Humanistic GIS: Toward a Research Agenda](readings/thinkpiece2/Humanistic-GIS-Toward-a-Research-Agenda.pdf), [Extended readings](readings/thinkpiece2) `Thinkpiece #2 post due by the end of week 7 (Nov. 19th, 23:59)` `Thinkpiece #2 comments due by the end of week 8 (Nov. 26th, 23:59)`

### Week 7 : Geocoding 

Starting from this week to the last week, we will dive into a series of lectures on web-based spatial analysis. In this week, we will introduce you to web-based geocoding using MapBox Geocoding API. The Mapbox Geocoding API allows you to make forward geocoding, which means that a text query like University of Washington gets turned into longitude and latitude coordinates. But sometimes it's not enough to find query results. Often, you want the geocoder to find query results that are biased toward a location, limited to a specific area, or both.

<!-- Nov 13 -->

-   **Presentation**
    -   Tuesday, Nov 14 (Andres S Rovalo): [Create interactive hover effects with Mapbox GL JS](https://docs.mapbox.com/help/tutorials/create-interactive-hover-effects-with-mapbox-gl-js/), Combine with Create a hover effect, or other features listed under the "Next steps" section of the provided document.
    -   Thursday, Nov 16: [Filter symbols by toggling a list](https://docs.mapbox.com/mapbox-gl-js/example/filter-markers/), Deploy your example using an individual github repository

-   **Readings:**
    - [Local search with the Geocoding API](https://docs.mapbox.com/help/tutorials/local-search-geocoding-api/)


### Week 8 : Web-based Spatial Analysis I: Sorting by Distance

In this week, we will introduce you to a basic spatial analysis that uses distance to sort geographical data. This application is made upon MapBox too. Starting from this week, you will work on your final project. Its requirement will be introduced in this week's lab session. In short, you will need to make an advanced spatial analysis to deal with a real-world problem.

<!-- Nov 20 -->

<!-- Nov 23, 24 holiday, thursday and friday, influencing the thursday lecture and the lab sessions -->
    
-   **Readings:**
    - [Sort data by Distance: Part I](https://docs.mapbox.com/help/tutorials/building-a-store-locator/)
    - [Sort data by Distance: Part II](https://docs.mapbox.com/help/tutorials/geocode-and-sort-stores/)
-   **Final Project:** [Web GIS Application](project/readme.md) 
-   **Final Project Checkpoint #1**: [Project proposal](https://github.com/jakobzhao/geog328/tree/main/project#week-8---checkpoint-1-project-proposal-due-by-the-end-of-week-8-15-pts) `Due by the end of week 8 (Nov. 26th, 23:59)`

### Week 9 : Dealing with Time on the Web

In this week, we will introduce how to deal with time on the web. The instructor will walk you through a more complicated application that illustrate how geographical data changes over time. In the lab session, you will continue to work on your final project.

<!-- Nov 27 -->

-   **Presentation**
    -   Tuesday, Nov 28 (Noah Rarick): [Display buildings in 3D](https://docs.mapbox.com/mapbox-gl-js/example/3d-buildings/) and [Add 3D terrain to a map](https://docs.mapbox.com/mapbox-gl-js/example/add-terrain/), Briefly discuss scenarios that 3d mapping would be preferred over traditional 2d mapping, (Highly recommended) How to show your own data in 3D.

-   **Readings:** 
    [Visualize geographical changes over time](https://docs.mapbox.com/help/tutorials/show-changes-over-time/)
-   **Final Project Checkpoint #2**: [Data preparation](https://github.com/jakobzhao/geog328/tree/main/project#week-9---checkpoint-2-data-preparation-due-by-the-end-of-week-9-10pts) `Due by the end of week 9 (Dec. 3th, 23:59)`


### Week 10 : Web-based Spatial Analysis II

This week will focus on web-based spatial analysis. One is on nearest neighbor analysis and the second is on buffer and isochrone analysis. In the last lecturer, the instructor will summarize this course and provide you a few emerging topics in Web GIS.

<!-- Dec 4 -->

-   **Readings:** 
    - [Nearest neighbor analysis](https://docs.mapbox.com/help/tutorials/analysis-with-turf/)
    - [Buffer and isochrone analysis](https://docs.mapbox.com/help/tutorials/get-started-isochrone-api/)

### Week 11 : Final Project Submission and Presentation

**Final Project Presentation**：will be held on Friday Dec. 11th 4:30 to 7:00 pm in SMI 401.


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

**Final Project:**  Final project will be conducted by a group of 4 to 5 students who are from the same Lab session. To submit your final project, you will need to share the url link of your final project's GitHub repository to a dedicated final project submission tab on Canvas by the end of Week 11 on Sunday (Dec 12th) by 11:59 pm.Check out [the detailed requirement for final project](project/readme.md).


## Grading

| Grading items         | %    |
| --------------------- | ---- |
| Participation         | 5%   |
| Thinkpiece            | 10%  |
| Quizzes               | 20%  |
| Lab Assignments       | 40%  |
| Final Project         | 25%  |

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

This course advocates for the open culture. The course materials are open source for both students and open source community to access. This course also builds on the work of Bo Zhao, Liz Peng, Xiaoqi "Steven" Bao,among many others, who have designed and taught or TA-ed previous iterations of this course.

Notably, students are not allow to videotape or audio-tape (record) this class in any form, and sharing recordings outside of class without the written consent of each student in the class is not permitted by [FERPA](https://registrar.washington.edu/students/ferpa/). However, I will try to record most of the classes via Zoom and share them via Canvas. Even so, I still encourage each of you attend the lectures instead of watching the recorded videos afterwards. Your in-class participation is a key factor to yield the best learning outcome. The instructor determines if their class can and cannot be recorded. This decision should be clearly communicated by the instructor at the beginning and throughout the quarter. In Zoom, the recording feature can be controlled by the instructor, as the meeting host.

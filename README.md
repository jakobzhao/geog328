# GEOGRAPHY 495B: Web & Mobile GIS

**Meetings:**
-   **Lectures:** Tuesdays and Thursdays 1:00 - 2:20 PM
    - All the lectures prior to November 1st will be held on [Zoom](https://washington.zoom.us/j/98531562117), while ones after November 1st will be held in person in SIG 224;
    - If you happen to be on campus during the lecture session, feel free to use SIG 224 to remotely access the lectures;
    - Watch the [recorded lectures](https://canvas.uw.edu/courses/1479441/pages/recorded-lectures).
-   **Labs:** Friday 12:30 - 1:20 PM (BA) and 1:30 -  1:20 PM (BB) in [SMI 401](https://www.google.com/maps/place/Smith+Hall+(SMI)/@47.6564039,-122.3096954,17z/data=!3m1!4b1!4m5!3m4!1s0x5490148d3c47332b:0x804039aa1d9e590b!8m2!3d47.6563716!4d-122.3074586)

**Instructional Team:**

-   **Bo Zhao**, Instructor, zhaobo@uw.edu | Office Hour: Thursdays 3 to 6:00 PM on [Zoom](https://calendar.google.com/calendar/u/0/selfsched?sstoken=UUZvU2gxXzVlZnZpfGRlZmF1bHR8NzM4ODA5MzUyNjAxZDU2Y2ViNTZiMzk2ZmM0N2VmNzI) or by appointment
-   **Steven Bao**, Teaching Assistant, bxq98@uw.edu |  Office Hour: Thursdays 11:00 AM to 12:30 PM  on [Zoom](https://calendar.google.com/calendar/u/0/selfsched?sstoken=UURaSkhXOURSSUd4fGRlZmF1bHR8Y2I1OTM0ODUyODg3ZDZiNWZiYjVlOTY3MjhmMWMwYjQ) or by appointment

> _This web page is the syllabus - There is no printed version, please refer here instead. Make sure refer to this page as often as possible. Also, Feel free to ask the instructor for clarifications whenever needed._

![course cover](assets/img/cover.jpg)


Web & Mobile GIS, the combination of web, mobile technology, and GIS, is a promising and fast-growing field. It has extended the power of GIS from local servers to the cloud, and put online maps and geospatial intelligence in multiple aspects of human society. This course aims to provide students with the essential knowledge needed for managing web & mobile GIS projects, teach students the latest geospatial cloud technologies needed for building modern web GIS applications, and inspire students with real-world case studies. To cultivate the spirit of open source, all the required software, packages are open source, and the course handout will be shared on GitHub. To promote the equal access to web mapping technology, we ensure all the Web GIS applications from course materials can be opened, debugged or further developed in either Windows or Mac OSX operating systems, and all the relevant software or services are either open source or free. This course is comprised of two major components, including lectures and lab exercises. The lectures focus on the theories and principles behind Web GIS, including the web architecture, front-end coding, responsive design, web based spatial analyses.
pin
**The course schedule might be slightly updated when the quarter unfolds, the latest schedule will be on the github repository front page. Please ensure to check it frequently.** If you have any question :raising_hand:, feel free to contact [Dr. Bo Zhao](mail://zhaobo@uw.edu).


## :calendar: Weekly Schedule

- **Preparation:** [Gear up the working environment](gearup.md) :computer: :beer:
- **Weekly Expectations:** Each student is supposed to a) attend both lecture and lab sections each week, b) complete all weekly readings before the lecture begins.

### Week 1: Intro to Web GIS

<!-- Sept 29 -->

The first lecture introduces you to the fundamentals of Web GIS. Over this quarter, you wil frequently use GitHub for synchronizing course material and managing Web GIS project. So, in Lab 1, you will learn to manage a web based project using GitHub.

-   **Readings:** 
    - [Intro to Web GIS](https://canvas.uw.edu/courses/1479441/files/folder/assets?preview=81407677)
    - [Git Handbook `Optional`](https://guides.github.com/introduction/git-handbook/). Git is an example of a distributed version control system (DVCS) commonly used for open source and commercial software development. With Git, Developers can work anywhere and collaborate asynchronously from any time zone.
    - [Mastering Markdown `Optional`](https://guides.github.com/features/mastering-markdown/). Markdown is a lightweight and easy-to-use syntax for styling all forms of writing on the GitHub platform. You control the display of the document; formatting words as bold or italic, adding images, and creating lists are just a few of the things we can do with Markdown. 
    - `To grasp the gist of the reading material, you can refer to the` [study questions](modules/module01/readme.md) `of this week.`

    

-   **Lab 1:** [Project management using GitHub](labs/lab01) `Due: Oct 8th, by 11:59pm`

### Week 2: Web Fundamentals

<!-- Oct 4 -->

Today, almost everyone have used the Internet for some purposes. To develop Web or Mobile GIS, you need to dive into some more fundamentals of the Web. So, in this week, you will learn the basics of the web, its mechanics and standards. To maximize your learning outcome,  we highly encourage you to read over the reading materials before the lectures. To test how well you are familiar with the reading materials and the lecture content, you need to complete the Quiz 1 all by yourself before the due day. 
    
-   **Readings:** 
    - [Getting started with the web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web). This document introduces you to the practicalities of web development. 
    - [The web and web standards](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/The_web_and_web_standards). This article provides some useful background on the Web — how it came about, what web standard technologies are, how they work together, why "web developer" is a great career to choose, and what kinds of best practices you'll learn about through the course.
    - [Common questions on Web mechanics](https://developer.mozilla.org/en-US/docs/Learn/Common_questions#web_mechanics). This document covers questions relating to general knowledge of the web ecosystem and how it works.
    - [Technical basics of Web GIS](https://canvas.uw.edu/courses/1479441/files/folder/assets?preview=81660132)
    - `To grasp the gist of the reading material, you can refer to the` [study questions](modules/module02/readme.md) `of this week.`

-  [Lecture Slides](modules/module02/module02.pdf) 

-   **Quiz 1:** [Web Basics](https://canvas.uw.edu/courses/1479441/quizzes/1531301) `Due: Oct 8th, by 11:59pm`


### Week 3: Front-end Coding: HTML and CSS

<!-- Oct 11 -->

To build websites, you should know about HTML, CSS and JavaScript. HTML is the the fundamental technology used to define the structure of a webpage, CSS is used to style the web page, and JavaScript takes the charge of the behaviors of the Web. We will spend two weeks to focus on these three primary coding languages of the Web. This week introduces you to HTML and CSS. To evaluate your learning outcomes,  we offered two quizzes and a lab for your practice. 

-   **Readings:** 
    - [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML). This document sets the stage, getting you used to important concepts and syntax, looking at applying HTML to text, how to create hyperlinks, and how to use HTML to structure a webpage. *The section on "Debugging HTML" and the two following assessments are not required.* 
    - [Multimedia and embedding](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding) This document explores how to use HTML to include multimedia in your web pages, including the different ways that images can be included, and how to embed video, audio, and even entire other webpages. *The section on the assessment is not required.* 
    - [CSS First Steps](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps) CSS (Cascading Style Sheets) is used to style and lay out web pages — for example, to alter the font, color, size, and spacing of your content, split it into multiple columns, or add animations and other decorative features. This module provides a gentle beginning to your path towards CSS mastery with the basics of how it works, what the syntax looks like, and how you can start using it to add styling to HTML.
    - [CSS Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors) In CSS, selectors are used to target the HTML elements on our web pages that we want to style. There are a wide variety of CSS selectors available, allowing for fine-grained precision when selecting elements to style. In this article and its sub-articles we'll run through the different types in great detail, seeing how they work.
    - [Introduction to CSS layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Introduction) This article will recap some of the CSS layout features we've already touched upon in previous modules, such as different display values, as well as introduce some of the concepts we'll be covering throughout this module.
    - `To grasp the gist of the reading material, you can refer to the` [study questions](modules/module03/readme.md) `of this week.`

-  [Lecture Slides](modules/module03/module03.pdf) 

-   **Quiz 2:** [HTML Fundamentals](https://canvas.uw.edu/courses/1479441/quizzes/1531299) `Due: Oct 15th, by 11:59pm`
-   **Quiz 3:** [CSS Fundamentals](https://canvas.uw.edu/courses/1479441/quizzes/1531540) `Due: Oct 17th, by 11:59pm`
-   **Lab 2:** [Responsive web page design](labs/lab02) `Due: Oct 22nd, by 11:59pm`


### Week 4: Front-end Coding: Javascript and GeoJSON

In this week, we will focus on learning JavaScript. Also, for web applications, geographical data are stored in the JavaScript Object Notation (JSON) format, or namely GeoJSON. This week will introduce you to the general format of GeoJSON, demonstrate how to asynchronously load GeoJSON data to your Web GIS application. Similar to the previous week, we offer a quiz on JavaScript and a new lab on how to load, parse and map GeoJSON data on the web.

<!-- Oct 18 -->

-   **Readings:** 
    - [JavaScript First Steps](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps). In this document,we first answer some fundamental questions such as "what is JavaScript?", "what does it look like?", and "what can it do?", before moving on to taking you through your first practical experience of writing JavaScript. After that, we discuss some key building blocks in detail, such as variables, strings, numbers and arrays.

    - [Javascript Building Blocks](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks). In this document, we continue our coverage of all JavaScript's key fundamental features, turning our attention to commonly-encountered types of code blocks such as conditional statements, loops, functions, and events. You've seen this stuff already in the course, but only in passing — here we'll discuss it all explicitly.


    - [Working with JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON). JavaScript Object Notation (JSON) is a standard text-based format for representing structured data based on JavaScript object syntax. It is commonly used for transmitting data in web applications (e.g., sending some data from the server to the client, so it can be displayed on a web page, or vice versa). You'll come across it quite often, so in this article we give you all you need to work with JSON using JavaScript, including parsing JSON so you can access data within it, and creating JSON.
    
    - [Making asynchronous programming easier with async and await](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Async_await) More recent additions to the JavaScript language are async functions and the await keyword, added in ECMAScript 2017. These features basically act as syntactic sugar on top of promises, making asynchronous code easier to write and to read afterwards. They make async code look more like old-school synchronous code, so they're well worth learning. This article gives you what you need to know.
    
    - [GeoJSON](https://en.wikipedia.org/wiki/GeoJSON). GeoJSON is an open standard format designed for representing simple geographical features, along with their non-spatial attributes. It is based on the JSON format. In addition, a notable offspring of GeoJSON is TopoJSON, an extension of GeoJSON that encodes geospatial topology and that typically provides smaller file sizes.
    - `To grasp the gist of the reading material, you can refer to the` [study questions](modules/module04/readme.md) `of this week.`

-  [Lecture Slides](modules/module04/module04.pdf) 

-   **Quiz 4:** [Javascript Fundamentals](labs/lab03) `Due: Oct 22th, by 11:59pm`
-   **Lab 3:** [Asynchronous GeoJSON data loading and visualization](labs/lab03) `Due: Oct 29th, by 11:59pm`


### Week 5: Geospatial Web Server

In this week, we will focus on geospatial web servers. A geospatial web server plays a significant role in maintaining web based geospatial application. It stays in the cloud and provides multiple services relevant to geospatial data, such as geospatial data indexing, data format conversation, reprojection, and even spatial analyses. In this week, two geospatial web servers are introduced, including Mapbox (Proprietary) and GeoServer (Open Source). 

<!-- Oct 25 -->

-   **Readings:**
    - [Web Map Service from GeoServer](https://docs.geoserver.org/latest/en/user/services/wms/index.html)
    - [Publish a shapefile](https://docs.geoserver.org/latest/en/user/gettingstarted/shapefile-quickstart/index.html)


### Week 6 : Thematic Map Design on the web

In this week, we will introduce you to map making on the web. The web based interactive map is built upon MapBox, which is a popular map library. It not only contains fundamental map related functions, but also offers a lot of cool map features for your use and further explore. In this week, we will walk you through at least two mapbox applications, and you will use mapbox to make an interactive web map in the lab session.

<!-- Nov 1 -->

-   **Readings:**
    - [making thematic map using mapbox](https://docs.mapbox.com/help/tutorials/create-a-map-with-data-visualization-component/)
    - [Add custom markers in Mapbox GL JS](https://docs.mapbox.com/help/tutorials/custom-markers-gl-js/)


-   **Lab 4:** [Interactive web mapping](labs/lab04) `Due: Nov 12th, by 11:59pm`



### Week 7 : Geocoding 

In this week, we will start a series of lectures on web-based spatial analysis. In this week, we will introduce you to web-based geocoding based on mapbox Geocoding API. The Mapbox Geocoding API allows you to make forward geocoding, which means that a text query like University of Washington gets turned into longitude and latitude coordinates. But sometimes it's not enough to find query results. Often, you want the geocoder to find query results that are biased toward a location, limited to a specific area, or both.

<!-- Nov 8 -->

-   **Readings:** 
    - [Local search with the Geocoding API](https://docs.mapbox.com/help/tutorials/local-search-geocoding-api/)


### Week 8 : Web-based spatial analysis I: Sorting by distance

In this week, we will introduce you to a basic spatial analysis that uses distance to sort geographical data. This application is made upon MapBox too. Starting from this week, you will work on your final project. Its requirement will be introduced in this week's lab session. In short, you will need to make an advanced spatial analysis to deal with a real-world problem.

<!-- Nov 15 -->

-   **Readings:** 
    - [Sort data by Distance](https://docs.mapbox.com/help/tutorials/building-a-store-locator/)
-   **Final Project:** [Web-based spatial analysis](labs/lab05) 

### Week 9 : Dealing with time on the web

In this week, we will introduce how to deal with time on the web. During the lectures, the instructor will walk you through a more complicated application that illustrate how geographical data changes over time. In the lab session, you will continue to work on your final project.

<!-- Nov 22 -->

-   **Readings:** 
    [Visualize geographical changes over time](https://docs.mapbox.com/help/tutorials/show-changes-over-time/)


### Week 10 : Web-based spatial analysis II

This week will still focus on web-based spatial analysis. One is on nearest neighbor analysis and the second is on buffer and isochrone analysis.

<!-- Nov 29 -->

-   **Readings:** 
    - [Nearest neighbor analysis](https://docs.mapbox.com/help/tutorials/analysis-with-turf/)
    - [Buffer and isochrone analysis](https://docs.mapbox.com/help/tutorials/get-started-isochrone-api/)


### Week 11 : Summary and Final Project Presentation

In the first lecture of this week, the instructor will share with you a summary of this course and some emerging topics to explore. During the lecture on Thursday and the lab session, each student will present the final project to the whole class. More information about final project will be shared after the mid-term.


<!-- Dec 6 -->


## :bell: Course Requirement

**Student Tech Support:**

The Student Tech Loan Program is expanding as quickly as possible. We announced this to undergrads as soon as it hit the airwaves, in hopes some of them who need hardware can reserve for spring quarter. They expect new/additional machines to arrive in April. STLP Website: <https://stlp.uw.edu/> (check the [Spring Announcement](https://drive.google.com/file/d/1qlbUBPdQFJt_jXS2fAOtORwNrBVtZqCb/view)).


**E-mail:**
E-mail is the easiest way of reaching me. I will respond to all e-mails during office hours, and will periodically return e-mail at other times. Please note that the answer to many commonly e-mailed questions can be found in the syllabus or on the course website. Please also note that in order to respond your e-mail you MUST include the following information in every e-mail:

-  A Salutation (Both Dr. Zhao and Professor Zhao are acceptable)
-  Your Full Name
-  What class you are in
-  Subject line summarizing your e-mail (i.e. “Question regarding Map Design” for example)

`For all the questions related to quizzes and labs, please contact the TA.`

**GitHub:** This course material will be hosted on GitHub instead of UW Canvas. On this dedicated GitHub repository, you can find most of the course material, participate in group discussions by submitting GitHub issues, and create new GitHub repositories to turn in the lab deliverables. By the end of this quarter, you will be more proficient in operating a cloud-based coding environment and able to host your work online as a way to gain public and peer attentions.

**Labs:** You need to finish all four labs by the due date. In order to help you work on each lab, we will walk through most of the labs during the lab sessions. If you have any questions about the lab, please look for tech support from the TA. 

**Quizzes：** In the first half of the quarter, we have set up four quizzes to help you get familiar with the web and front-end coding. For each quiz, you have unlimited time to answer it. You can refer to any lecture notes or internet resource to answer it, but you can only just try each quiz once. Please work on each quiz ALL BY YOURSELF. 

**Participation in in-class discussion:** Complete all assigned readings and get familiar with the lab instructions before class meetings, and actively participate in critical discussions of those readings. You should have completed all of the weekly readings before our Friday lab sections as these sections will be devoted to critical discussion and engagement with the required readings.

**Final Project:**  [Requirement](project.md)


## :heavy_check_mark: Grading

| Grading items   | %   |
| --------------- | --- |
| Participation   | 5%  |
| Quizzes         | 25% |
| Lab Assignments | 30% |
| Final project   | 15% |

> The item `participation` includes your participation in the class (e.g., self-introduction, answer questions in class, etc.) and/or your response on GitHub issues (ask questions via GitHub issue, and help your classmates using the GitHub issues function). 


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

 Notably, students are not allow to videotape or audio-tape (record) this class in any form, and sharing recordings outside of class without the written consent of each student in the class is not permitted by [FERPA](https://registrar.washington.edu/students/ferpa/). However, I will try to record most of the classes via Zoom and share them via Canvas. Even so, I still encourage each of you attend the lectures instead of watching the recorded videos afterwards. Your in-class participation is a key factor to yield the best learning outcome. The instructor determines if their class can and cannot be recorded. This decision should be clearly communicated by the instructor at the beginning and throughout the quarter. In Zoom, the recording feature can be controlled by the instructor, as the meeting host.

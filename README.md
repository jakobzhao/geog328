# GEOGRAPHY 495B: Web & Mobile GIS

**Meetings:**

-   **Lectures:** Tuesdays and Thursdays 1:00 - 2:20 PM PST on [Zoom]()
-   **Labs** Friday 12:30 - 1:20 PM PST in SMI 401 and remotely on [Zoom]() by Appointment 

**Personnel:**

-   **Bo Zhao**, Instructor, zhaobo@uw.edu | Office Hour: Thursdays 3 to 6:00 PM PST on [Zoom](https://calendar.google.com/calendar/u/0/selfsched?sstoken=UUZvU2gxXzVlZnZpfGRlZmF1bHR8NzM4ODA5MzUyNjAxZDU2Y2ViNTZiMzk2ZmM0N2VmNzI) or by appointment

-   **Steven Bao**, Teaching Assistant, bxq98@uw.edu |  Office Hour: Fridays 12:30 to 1:30 PM PST on [Zoom](https://washington.zoom.us/j/4874322240) or by appointment

> _This web page is the syllabus - There is no printed version, please refer here instead. Make sure refer to this page as often as possible. Also, Feel free to ask the instructor for clarifications whenever needed._

![course cover](assets/img/cover.jpg)

Web & Mobile GIS, the combination of web, mobile technology, and GIS, is a promising and fast-growing field. It has extended the power of GIS from local servers to the cloud, and put online maps and geospatial intelligence in multiple aspects of human society. This course aims to provide students with the essential knowledge needed for managing web & mobile GIS projects, teach students the latest geospatial cloud technologies needed for building modern web GIS applications, and inspire students with real-world case studies. To cultivate the spirit of open source, all the required software, packages are open source, and the course handout will be shared on GitHub. 

This course introduces concepts and techniques of web programming, digital storytelling, online project management, and web-based cartographic principles for developing, evaluating, and using web maps. To promote the equal access to web mapping technology, we ensure all the web mapping applications from course materials can be opened, debugged or further developed in either Windows or Mac OSX operating systems, and all the relevant software or services are either open source or free. This course is comprised of two major components, including lectures and lab exercises. The lectures focus on the theories and principles behind web mapping, including system architecture, responsive user graphic design, map design and geo-narrative. The lab exercises focus on practical skills for web programming, 2d and 3d web mapping, web mapping services, and digital storytelling. 

From this course, students can learn both the principles of web-based cartography and the practical skills for web mapping, and develop the capabilities of map aesthetics and critique. **The course schedule might be slightly updated when the quarter unfolds, the latest schedule will be on the github repository front page. Please ensure to check it frequently.** If you have any question :raising_hand:, feel free to contact [Dr. Bo Zhao](mail://zhao2@oregonstate.edu).


## :calendar: Weekly Schedule

#### Preparation: [**Gear up the working environment**](assets/gearup.md) :computer:  :beer:

#### Weekly Expectations:

-   You should try to attend both lecture and lab sections each week.
-   You should complete all weekly readings before the Friday Lab sections

### Week 1: Intro to Web GIS

<!-- Sept 29 -->

This week’s lecture and lab will prepare you for the course, and provide a theoretical and technical foundation to build from. We’ll work through the syllabus together, and answer any questions you all may have. Each student is expected to read the Ash et al (2018) paper. After completing Lab 1, you will be able to clone/synchronize the course material, set up a personal website, and gain practical experience using github to manage your digital geographies projects.

-   **Readings** 
    - 扫描 Web GIS 这本书
    - [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

-   **Lab 1:** [Project management using GitHub](labs/lab01) `Due: Jan 16th, by 11:59pm`

### Week 2: Web Fundamentals

<!-- Oct 4 -->
    
-   **Readings** 
    - [Getting started with the web](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web). This is a concise series introducing you to the practicalities of web development. You'll set up the tools you need to construct a simple webpage and publish your own simple code.
    - [The web and web standards](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/The_web_and_web_standards). This article provides some useful background on the Web — how it came about, what web standard technologies are, how they work together, why "web developer" is a great career to choose, and what kinds of best practices you'll learn about through the course.
    - [Common questions on Web mechanics](https://developer.mozilla.org/en-US/docs/Learn/Common_questions#web_mechanics). This document covers questions relating to general knowledge of the web ecosystem and how it works.

-   **Quiz** 
    - [Web Basics](https://canvas.uw.edu/courses/1479441/quizzes/1531301) 


### Week 3 : Front-end Coding: Html and CSS

<!-- Oct 11 -->
To build websites, you should know about HTML — the fundamental technology used to define the structure of a webpage. HTML is used to specify whether your web content should be recognized as a paragraph, list, heading, link, image, multimedia player, form, or one of many other available elements or even a new element that you define.

Cascading Stylesheets — or CSS — is the first technology you should start learning after HTML. While HTML is used to define the structure and semantics of your content, CSS is used to style it and lay it out. For example, you can use CSS to alter the font, color, size, and spacing of your content, split it into multiple columns, or add animations and other decorative features.

-   **Reading** 
    - [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML). This document sets the stage, getting you used to important concepts and syntax, looking at applying HTML to text, how to create hyperlinks, and how to use HTML to structure a webpage.
    - [Multimedia and embedding](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding) This document explores how to use HTML to include multimedia in your web pages, including the different ways that images can be included, and how to embed video, audio, and even entire other webpages.
    - [CSS First Steps](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps) CSS (Cascading Style Sheets) is used to style and lay out web pages — for example, to alter the font, color, size, and spacing of your content, split it into multiple columns, or add animations and other decorative features. This module provides a gentle beginning to your path towards CSS mastery with the basics of how it works, what the syntax looks like, and how you can start using it to add styling to HTML.
    - [CSS Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors) In CSS, selectors are used to target the HTML elements on our web pages that we want to style. There are a wide variety of CSS selectors available, allowing for fine-grained precision when selecting elements to style. In this article and its sub-articles we'll run through the different types in great detail, seeing how they work.
    - [Introduction to CSS layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Introduction) This article will recap some of the CSS layout features we've already touched upon in previous modules, such as different display values, as well as introduce some of the concepts we'll be covering throughout this module.

-   **Quizzes:** 
    - [html fundamentals](https://canvas.uw.edu/courses/1479441/quizzes/1531299) 
    - [css fundamentals](https://canvas.uw.edu/courses/1479441/quizzes/1531540) 

-   **Lab 2:** [html page design](labs/lab03) `Due:Feb 12th, by 11:59pm`


### Week 4 : Front-end Coding: Javascript and GeoJson

<!-- Geospatial Data Transferring and visualization -->

-   **Readings** 
    - [JavaScript First Steps](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps). In this document,we first answer some fundamental questions such as "what is JavaScript?", "what does it look like?", and "what can it do?", before moving on to taking you through your first practical experience of writing JavaScript. After that, we discuss some key building blocks in detail, such as variables, strings, numbers and arrays.

    - [Javascript Building Blocks](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks). In this document, we continue our coverage of all JavaScript's key fundamental features, turning our attention to commonly-encountered types of code blocks such as conditional statements, loops, functions, and events. You've seen this stuff already in the course, but only in passing — here we'll discuss it all explicitly.


    - [Working with JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON). JavaScript Object Notation (JSON) is a standard text-based format for representing structured data based on JavaScript object syntax. It is commonly used for transmitting data in web applications (e.g., sending some data from the server to the client, so it can be displayed on a web page, or vice versa). You'll come across it quite often, so in this article we give you all you need to work with JSON using JavaScript, including parsing JSON so you can access data within it, and creating JSON.

    - [Making asynchronous programming easier with async and await](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Async_await) More recent additions to the JavaScript language are async functions and the await keyword, added in ECMAScript 2017. These features basically act as syntactic sugar on top of promises, making asynchronous code easier to write and to read afterwards. They make async code look more like old-school synchronous code, so they're well worth learning. This article gives you what you need to know.

    - [GeoJSON](https://en.wikipedia.org/wiki/GeoJSON). GeoJSON is an open standard format designed for representing simple geographical features, along with their non-spatial attributes. It is based on the JSON format. In addition, a notable offspring of GeoJSON is TopoJSON, an extension of GeoJSON that encodes geospatial topology and that typically provides smaller file sizes.


    <!--https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Manipulating_documents-->

    <!--https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Fetching_data-->
    

through ajax. await

-   **quiz 4:** [javascript](labs/lab02) 

-   **Lab 3:** [Load geojson data as a table](labs/lab03) `Due:Feb 12th, by 11:59pm` 


### Week 5 : UX/UI Design

<!-- Feb 1 to 5 -->

-   **Readings:** a) 3WSchool UI Design, side panel, time slider, navbar, etc. b) icons.


<!--  b) [The Guide to Map Design](weeks/week05/mapbox-design.pdf), b) [BaseMap design using Mapbox Studio](https://docs.mapbox.com/studio-manual/overview/)  -->


### Week 6 : Thematic Maps

<!-- Feb 8 to 12 -->


-   **Readings:**


12.	marker map, map icons
13. Heatmap
14.	choropleth


-   **Lab 4:** [a web site?](labs/lab01) `Due: Jan 16th, by 11:59pm`
   1. 给一个网站，让大家做一个类似的？
   2. 然后制作相应的控件。（或者就是那个美国的）

### Week 7 : Geocoding 

<!-- Feb 15 to 19 -->

This week we will explore the concept of geo-narrative, the use of storytelling in mapping practice, by looking at existing geo-narrative mapping projects and engaging in a group discussion and map critique.

-   **Readings:**  geocoder.  以及数据的geocoder。



### Week 8 : Spatial analysis I: Time and Routing

<!--(Feb 22 to 26) -->

This week will focus on two emerging topics related to digital geographies, including cloud point visualization and real-time environment data collection, and explore their promise and pitfalls.


-   **Readings:**  time . and route plan， mapbox
-   **Lab 5:** [final](labs/lab01) `Due: Jan 16th, by 11:59pm`


### Week 9 : Spatial analysis II (distance, buffer) 

<!--(Feb 22 to 26) -->

This week will focus on two emerging topics related to digital geographies, including cloud point visualization and real-time environment data collection, and explore their promise and pitfalls.

-   **Readings:** distance，buffer 的课件。



### Week 10 : Summary and Final Project Presentation

<!-- Mar 15 to 19 -->

During the last two meeting sessions, each group will present their final projects. More information about final project will be shared after the mid-term.


During these two weeks, each group will focusing on their final projects and essay. The instructor and teaching assistant are available during the normal lecture period, lab sections and office hours if help is needed. Below are some resources for you to develop your final project.



## :bell: Course Requirement

**Student Tech Support:**

The Student Tech Loan Program is expanding as quickly as possible. We announced this to undergrads as soon as it hit the airwaves, in hopes some of them who need hardware can reserve for spring quarter. They expect new/additional machines to arrive in April. STLP Website: <https://stlp.uw.edu/> (check the [Spring Announcement](https://drive.google.com/file/d/1qlbUBPdQFJt_jXS2fAOtORwNrBVtZqCb/view)).

**GitHub:** This course material will be hosted on GitHub instead of UW Canvas. On this dedicated GitHub repository, you can find most of the course material, participate in group discussions by submitting GitHub issues, and create new GitHub repositories to turn in the lab deliverables. By the end of this quarter, you will be more proficient in operating a cloud-based coding environment and able to host your work online as a way to gain public and peer attentions.

**Labs:** You need to finish all four labs by the due date. In order to help you work on each lab, we will walk through most of the labs in class.

**Think Pieces:** for week 1 to 8, there will be weekly reading assignments. To evaluate your reflection upon each week's reading material, we set up a discussion board for each week. You need to submit think pieces to **3** out of the 8 weeks' discussion topics. Your think pieces should be completed by Thursday @ 5 pm PST for the weeks you are submitting a piece. Your think pieces should be at least 350 words and engage substantially with the reading materials, and connections to the lab assignments and lectures. Guiding questions or prompts will be included in each week's discussion section on canvas to help frame your thinking. Submit your think pieces on Canvas in the applicable week's discussion section (https://canvas.uw.edu/courses/1434645/discussion_topics).

**Participation in in-class discussion:** Complete all assigned readings and get familiar with the lab instructions before class meetings, and actively participate in critical discussions of those readings. You should have completed all of the weekly readings before our Friday lab sections as these sections will be devoted to critical discussion and engagement with the required readings.

**Individual Final Project:** Considering the difficulty of working as a team when you cannot meet each other in person, I have decided to change the final collaborative project as individual base, and cancel lab 5. So, at the end of this quarter, you only need to submit this final project. check out  [the detailed requirement for final project](project/project.md)

**Essay:** Each student will complete an essay that engages with the readings and the course themes, along with additional readings that you bring into conversation with the assigned course readings. You are aiming for ~~10 pages (double-spaced)~~ **no less than 1500 words** coalescing around ideas and readings from this quarter. Essay is due no later than the end of **Week 10**. Check out [the detailed requirement for essay](project/essay.md).

## :two_men_holding_hands: Targeted Audience

This course targets students who have a background in fundamental geographic information science or equivalent computational or programming skills. This course is designed for students who are willing to learn defined GIS skills that will be important to many emerging jobs in location-based services, autonomous driving, web mapping, geographic data collection (using drone or LiDAR) and analyses. This course is also suitable for students who are interested in learning and critically reflecting upon cutting-edge geospatial techniques.

## :heavy_check_mark: Grading

| Grading items   | %   |
| --------------- | --- |
| Participation   | 5%  |
| Quizzes         | 25% |
| Lab Assignments | 30% |
| Final project   | 15% |

> The item `participation` includes your participation in the class (e.g., self-introduction, answer questions in class, etc.) and/or your response on GitHub issues (ask questions via GitHub issue, and help your classmates using the GitHub issues function). As well as participation in the weekly lab/discussion sections.

## :love_letter: Accommodations

We welcome the opportunity to work with any students with disabilities in this class to ensure equal access to the course. If you have a letter from Disability Resources for Students (DRS) outlining your academic accommodations, please present the letter to me (or email us, to confirm, if the letter is electronic) as soon as possible so that we can discuss the accommodations you may need for this class. Any discussions between student and professor need to occur as early as possible in order for adequate arrangements to be made. If you do not yet have a letter from DRS, but would like to request academic accommodations due to a disability, please contact DRS [here (Links to an external site.)](https://depts.washington.edu/uwdrs/), or in-person at 011 Mary Gates Hall, or at 206-543-8924 (Voice & Relay), <mailto:uwdrs@uw.edu>.

 Washington state law requires that UW develop a policy for accommodation of student absences or significant hardship due to reasons of faith or conscience, or for organized religious activities. The UW’s policy, including more information about how to request an accommodation, is available at [Religious Accommodations Policy](https://registrar.washington.edu/staffandfaculty/religious-accommodations-policy/). Accommodations must be requested within the first two weeks of this course using the [Religious Accommodations Request form](https://https:/registrar.washington.edu/students/religious-accommodations-request/).

## :book: Copyright

 This course advocates for the open culture. The course materials are open source for both students and open source community to access.

 Notably, **students are not allow to videotape or audio-tape (record) this class in any form, and sharing recordings outside of class without the written consent of each student in the class is not permitted by [FERPA](https://registrar.washington.edu/students/ferpa/).** However, I will try to record most of the classes via Zoom and share them via Canvas. Even so, I still encourage each of you attend the lectures instead of watching the recorded videos afterwards. Your in-class participation is a key factor to yield the best learning outcome.

 The instructor determines if their class can and cannot be recorded. This decision should be clearly communicated by the instructor at the beginning and throughout the quarter. In Zoom, the recording feature can be controlled by the instructor, as the meeting host.

## :bouquet: Acknowledgement

<a href="https://hgis.uw.edu"><img src="assets/logo.png" align="right" width="230px" target="_blank" /></a> The development of this course has been financially supported by UW's data science minior committee. This course is largely based upon material designed with Tyler McCrea, and also I sincerely appreciate Jou Ho, Fengyu Xu for their assistances in developing this course.

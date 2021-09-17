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

-   **Readings:** 
    - 扫描 Web GIS 这本书

-   **Lab 1:** [Project management using GitHub](labs/lab01) `Due: Jan 16th, by 11:59pm`

### Week 2: Web Fundamentals

<!-- Oct 4 -->

This week we’ll focus on providing you all with the fundamental skill set for web programming.  We will begin with an overview of the system architecture required for a digital geographies project,  then guide you through some of the essential front-end fundamentals. Including, internet basics, html, javascript, and css. This week requires a lot of self-learning,  and includes fairly lengthy readings and practical exercises. Please be prepared.

-   **Lecture Notes:** 

    
-   **Readings:** 
    - [Intro to the Web](weeks/week01/intro-web)
    - [System architecture](weeks/week02/architecture)

-   **quiz 1:** [web fundamentals](labs/lab02) 


### Week 3 : Front-end Coding: Html and CSS

<!-- Jan 18 to 22 -->

This week’s focus is on processing geospatial data for your digital geographies projects. We will begin by introducing the structure of the geojson format, and then look at techniques for collecting, converting and visualizing geojson objects/features in a web or desktop environment such as QGIS. After completing Lab 2, students will have learned how to collect geo-tagged tweets using specific keywords/topics (e.g., etc.), and methods for visualizing the spatial distribution of the locations for those tweets.



-   **Readings:** 
        [W3School Tutorials on Html, CSS](weeks/week02/tech-readings.md)

     
-   **quiz 2:** [html](labs/lab02) 
-   **quiz 3:** [css](labs/lab02) 


-   **Lab 2:** [html page design](labs/lab03) `Due:Feb 12th, by 11:59pm`


### Week 4 : Front-end Coding: Javascript and GeoJson

<!-- Geospatial Data Transferring and visualization -->

-   **Readings:** a) [Javascript](https://www.forbes.com/sites/drsarahbond/2017/10/20/how-is-digital-mapping-changing-the-way-we-visualize-racism-and-segregation/#4df35c7d33fa); b) [GeoJSON](weeks/week03/assets/geojson.pdf); c) GEOJSON.IO； d) create geojson

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

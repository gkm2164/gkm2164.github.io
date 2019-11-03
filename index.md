---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
# Curriculum Vitae

## Profile
### Biography
* Name: Gyeongmin Go (Ben)
* E-mail: gkm2164\__at_\_gmail\__dot_\_com
* Job Title: Backend Developer, Data Engineer
* Organization: Kakao Corp.
* Git repository: [Github](https://github.com/gkm2164), [Bitbucket](https://bitbucket.org/gkm2164), [Private Bitbucket](https://vcs.gyeongmin.co)

### Introduction
* Highly motivated on desining, implementing and managing software to be safe and well reusable
* Currently working with Go, Scala, Kotlin for server development
* Interested in develop software with Functional Programming approach
* "How to make good software? (in terms of safety, reusability, efficiency)", that's my main concern.
* Interested in inspect user data.

### Currently Operating Services!
* [Ben's URL Shortener](https://gben.me): This is for URL shortener. Anyone can use this! (Scala, Akka HTTP, Angular TypeScript)
* [For word study](https://eng.gyeongmin.co): Words which occurred on GRE frequently. (Scala, Akka HTTP, Angular TypeScript, Oxford Dictionary API)(Scala, Akka HTTP, Angular TypeScript, Oxford Dictionary API)
* [Wiki pages](https://docs.gyeongmin.co): *Confluence*, as my blog.
* [Repositories](https://vcs.gyeongmin.co): *Bitbucket*,  as my source code repository.

### Private Projects
* [Java doc generator](https://github.com/gkm2164/java-doc-creator): Java document generator (code reformatting)
* [lengine](https://github.com/gkm2164/lisp-parser): Another lisp engine written in Scala

## Work Experience

### [Kakao](https://www.kakaocorp.com), Republic of Korea
#### R&D Center

{:.float-right}
_Apr. 2018 ~ Present_

* Domain Agent(Skill server) for Kakao Mini AI speaker, Apr. 2018 ~ Present
   * skill server for several domains
      * Domain: Lotto (Golang), Exchange Rate (Golang), Fortune (Golang), Calendar (Golang), Hometraining (Springboot with Kotlin)
   * developing Go version library for developing skill server 
   * Serving information for user's preprocessed query.
   * Go, Kotlin, Spring
      * during developing go version library, developed go/java doc generator too. (Scala, Java, https://gben.me/fnRNalbL) to reduce the cost to write documentation

* Middle layer of Daum Search, Apr. 2019
   * web app which provides _missing child finding service_ for Daum portal service, the data is provided from [Safe182](http://www.safe182.go.kr) API
   * design, develop, and maintaining
   * Kotlin, used several functional approach(Monad, immutable data structure)

* Lazzy, personalized portal service, July. 2018 ~ Jan. 2019
   * backend server - middle layer, lineup server
   * developed recommend system
   * data engineering - appplied several ML algorithms and applied to service, to synonym, recommend, image process, etc.

* &#35; Tab in Kakao, June. 2018 ~ July. 2018
   * admin tool with vue.js, golang
   * redis writer, deadlink checker
   * fast json reader(https://gben.me/W6TOA1uH)
      * read necessary data only with a field name as an input.

### [Satrec Initiative](https://www.satreci.com), Republic of Korea
#### Defense System Software Development Division

{:.float-right}
_Sep. 2016 - Mar. 2018_

* Cloud Detection on Satellite image, Jul. 2017 ~ Oct. 2017
  * Implemented cloud identification algorithm which is based on CNN
  * [Source Codes](https://gben.me/Pb4UtFoH)
* 3D Virtual Globe Map Tile Server, Sep. 2017 - Feb. 2018
  * SMUDI 3D Virtual Globe Development Project, Satrec Initiative Defense Division.
  * I designed architecture of server, implemented it.
  * Constructing tiling server using Scala/Akka/Play Framework/Spark/GeoTrellis
  * Scala, Akka Framework, Spark, Hadoop, Redis
* Special Project, Oct. 2016 - Sep. 2017, _Project_, ADD
  * Applied Functional Programming approach for large size of data processing.
  * C# 6.0, .Net Framework 4.5, WPF, MS-SQL 2012

### [Elice](https://elice.io), Daejeon, Republic of Korea

{:.float-right}
_Aug. 2017 ~ June. 2018_

* **Teaching Assistant**, Algorithm, Data Structure, _June. 2018 ~ June. 2018_
* **Teaching Assistant**, Sooncheon Univ. Artificial Intelligence Course, _Mar. 2018 ~ May. 2018_
* **Instructor**, Basic AI course, _Feb. 2018 ~ Mar. 2018_, Live coding
* **Teaching Assistant**, netmarble AI course, _Dec. 2017 ~ Jan. 2018_
* **Teaching Assistant**, Artificial Intelligence Course, _Aug. 2017 - Sep. 2017_

### JU Consulting, Daejeon, Republic of Korea
#### Part Time Developer

{:.float-right}
_Jan. 2015 ~ Mar. 2015_

* Built a website with Ruby on Rails (http://goo.gl/F3dEjo).

### SMARDI, Suwon-si, Republic of Korea
#### Part Time Developer

{:.float-right}
_Sep. 2011 ~ Apr. 2012_

* API and library for a communication over audio connector, Java.
  * Make a communication library which uses different pitches as a packet.
  * Make module as a jar file and was deployed by SMARDI on April 2012.
  * Java
  
* A-Scan, a measuring application for alchol concentration in breath, Android Application.
  * Developed an android application for measuring alcohol concentration in human breathe uses an external device that is connected through the audio connector.
  * Refactored previously developed codes and add several features
  * Java, This application was successfully deployed to SMARDI on Dec. 2011.

### Dept. of Computer Engineering, Sungkyunkwan University (SKKU), Suwon-si, Republic of Korea
#### Research Assistant

{:.float-right}
_Mar. 2011 ~ Aug. 2012_

* Project: Developing an administration website for the Department of Software Engineering
    * Website, based on PHP, several important design patterns, such as MVC, Layered architecture.
    * Deployed to the Administration of Department of Software Engineering in SKKU

* Project: Recovering family trees for slaves during Joseon Dynasty
    * Data engineer project to recover family relations during the Joseon Dynasty with CSV format data (95,000 slaves' information)
    * Used the frequent itemset mining algorithm and used and the method suggested relations for approximately 9,000 ~ 10,000 slaves
    * PHP, MySQL for suggestion tool and Excel for data inspection

#### Part Time Lecturer

{:.float-right}
_Sep. 2010 ~ Apr. 2011_

* Taught 4 students from Saudi Arabia Korean speaking courses, System Programming, and Operating System in English.

### Computer Systems Laboratory, Sungkyunkwan University (SKKU), Suwon-si, Republic of Korea

#### Research Assistant

{:.float-right}
_Oct. 2010 ~ Dec. 2011_

* Researched a hybrid file system that loads the metadata to secondary non-volatile memory (such as PRAM) to decrease the number of writing counts over SSD
* Served as a teaching assistant for Operating System course and supported students to learn & develop OS with PintOS kernel
* Mastered the  structure and development of Windows/Linux kernel module, device driver(disk driver), and file system

## OpenSource Contribution
* [Ktor](https://github.com/ktorio/ktor), a Kotlin web framework library
   * introduced allowing many Content-Type not only ```application/json``` but also other custom types for Ktor client, _Apr. 2019 ~ May. 2019_, (Pull request: https://github.com/ktorio/ktor/pull/1036)
* [Levsha HTML](https://github.com/fomkin/levsha), Fast Scala eDSL for HTML
   * suggestion for adding ```enableAutoIndent``` option to ```TextPrettyPrintingConfig```, _June. 2019_, (Pull request: https://github.com/fomkin/levsha/pull/23)

## Educations
* **Ph.D. Candidate in Computer Science**; Korea Advanced Institute of Science and Technology (Yuseong, Daejeon), 2015 - _Present_
   * Software Architecture Laboratory

* **M.S. in Computer Science**; Korea Advanced Institute of Science and Technology (Yuseong, Daejeon), 2013 - 2015
   * Thesis title: An Application Technique of Software Binding for Automation of Software Configuration*
   * Software Architecture Laboratory

* **B.S. in Computer Engineer**; Sungkyunkwn University (Suwon, Gyeonggi), 2006 - 2012
    * Graduation Work: Department of Software Engineer Administrative System

## Publications
* Younghun Han, **Gyeongmin Go**, Sungwon Kang, Heuijin Lee, "A Feature-Oriented Mobile Software Development Framework to Resolve the Device Fragmentation Phenomenon for Application Developers in the Mobile Software Ecosystem," The 6th EAI International Conference on Cloud Computing(Cloudcomp 2015), Oct. 28-29, 2015. (Daejeon, Republic of Korea)

* **Gyeongmin Go**, Sungwon Kang, and Jongsun Ahn, “A Software Binding Application Tool based on Orthogonal Variability Description Language for Software Product Line Development,” In Proceedings of 16th IEEE/ACIS International Conference on Software Engineering, Artificial Intelligence, Networking and Parallel/Distributed Computing (SNPD 2015), Takamatsu, Japan, 2015
  * [Tool link here](https://bitbucket.org/gkm2164/sbat-ovdl)
* **Gyeongmin Go**, Sungwon Kang, Jongsun Ahn, "A Software Binding Application Tool based on Orthogonal Variability Description Language for Software Product Line Development," In Proceedings of 17th Korea Conference for Software Engineering(KCSE 2015), Pyeongchang Gangwon-do, 2015. (Korean)

## Courses

### Functional Programming in Scala Specialization Course, Coursera

{:.float-right}
_Aug. 2018 ~ Sep. 2018_
* [Certificate link](https://gben.me/lH0BQC7B)
* Course lists
  * Functional Programming Principles in Scala, Coursera, [certificate](https://gben.me/3hEagb34)
  * Functional Programming Design in Scala, Coursera, [certificate](https://gben.me/ZCIP2nUo)
  * Parallel Programming, [certificate](https://gben.me/OZ4Giejf)
  * Big Data Analysis with Scala and Spark, Coursera, [certificate](https://gben.me/O1Fs4c2z)
  * Functional Programming in Scala Capstone, [certificate](https://gben.me/RM0lAhtS)


### Data Scientist Course, Elice

{:.float-right}
_2017.04 ~ 2017.08_

* Course for training data scientist.
* Projects: Parliament Chatbot (Kakao Plus friend: ParChat)

### C4I/NCW specialist course, Agency of Defensive Development in Korea

{:.float-right}
_28, Aug, 2017 ~ 29, Aug, 2017_
* Overview of C4I communication system.
  * Command, Control, Communications, Computers and Intelligence
  * Overview of NCW Network Centric Warfare

### Machine Learning by Stanford University, Coursera

{:.float-right}
_Dec. 2016 ~ Jan. 2017_
  * Machine Learning by Stanford University on Coursera.
  * Certificate earned at Tuesday, January 31, 2017 5:39 AM GMT
  * [Certification Link](https://www.coursera.org/account/accomplishments/certificate/BGQZ4YPZ4ADC)

### Requirement Engineering Short-term lecture, Software Society

{:.float-right}
_20, Jul, 2016 ~ 22, Jul, 2016_

* Learned Requirement Driven Development methodology
* Overview for how to draw usecase diagram and how to apply those concepts to architecture.

## Skill
### Languages
  * Go, Scala, Java, Kotlin, C#, C, C++
  * HTML, CSS
  * Bash, Ruby, Python, JavaScript, TypeScript
  * Prolog
  * Clojure
  * UML, UPPAAL, NuSMV

### Frameworks
  * Spring Boot Framework, Akka Framework, Ruby on Rails, WPF

## Language
English(fluent), Korean(native)

## Sites
* [Blog](https://blog.gyeongmin.co)
* [Docs](https://docs.gyeongmin.co)
* [VCS](https://vcs.gyeongmin.co)
* [URL Shortener](https://gben.me)

# PCFJavaWorkshop-WithSCS
Java workshop with Pivotal Cloud Foundry and Spring Cloud Services (SCS)


## Instructors
- Parag Doshi, Platform Architect, pdoshi@pivotal.io
- David Dieruf, Platform Architect, ddieruf@pivotal.io

## Agenda

Time | Session
---- | -------
9:00 AM - 9:15 AM | Welcome and Introductions
9:15 AM - 9:45 AM | Session 1: _Intro to Pivotal Cloud Foundry_
9:45 AM - 10:00 AM | Lab 0: _Accessing the Workshop Environment_
10:00 AM - 10:30 AM | Lab 1: _Pushing Your First Application_
10:30 AM - 10:45 AM | _Break_
10:45 AM - 11:00 AM | _Labs Review_
11:00 AM - 11:45 AM | Lab 2: _Scaling, Auto Scaling and Zero Downtime Deployment Lab_
11:45 PM - 12:30 PM | Lab 3: _Monitoring, Metrics and HA Lab_
12:30 PM - 1:00 PM  | _Lunch_
1:00  PM - 1:30 PM  | _Labs Review_ 
1:30 PM - 2:00 PM | Session 2: _Cloud Native Design and Microservices with Spring Cloud Services_
2:00 PM - 2:30 PM | Lab 4: _Dynamic Configuration Loading with Spring Cloud Services - Config Server_
2:30 PM - 3:15 PM | Lab 5: _MicroServices Registration and Discovery with Spring Cloud Services - Eureka_
3:15 PM - 3:30 PM | _Break_
3:30 PM - 4:00 PM | Lab 6: _Fault Tolerant Design with Spring Cloud Services - Hystrix_
4:00 PM - 4:15 PM | _Labs Review_
4:15 PM - 4:45 PM | Session 3: Continuous Integration/Continuous Delivery with PCF
4:45 PM - 5:00 PM | Demo: _CI/CD pipeline with Jenkins and PCF_
5:00 PM - 5:30 PM | Wrap-Up & Q&A - Lessons Learnt - what doesn't work.

This is a _loose_ schedule for the day. We will adjust as necessary based on our pace through the material.

## Getting started

Start by downloading the course materials.  This can be accomplished either through the GitHub website or if you have Git installed, use the following commands:

```
$ git clone https://github.com/git-paragdoshi/PCFJavaWorkshop-WithSCS
$ cd PCFJavaWorkshop-WithSCS/
$ git fetch --all
```

**Prerequisites**
- [Cloud Foundry CLI](https://github.com/cloudfoundry/cli)
- [Git Client](https://git-scm.com/downloads)
- [Intellij Version 2016.1 or later](https://https://www.jetbrains.com/idea/download/)
- PWS account registration complete at http://run.pivotal.io

## Course Materials

#### Session 1 [(Slides)](session_01/Session_1_Cloud_Native_Introduction.pdf): _Intro to Pivotal Cloud Foundry_
  - [Lab 0 - Accessing the Workshop Environment](session_01/lab_00/lab_00.adoc)
  - [Lab 1 - Pushing Your First Application](session_01/lab_01/lab_01.adoc)
  - [Lab 2 - Scaling, Auto Scaling and Zero Downtime Deployment Lab](session_01/lab_02/lab_02.adoc)
  - [Lab 3 - Monitoring, Metrics and HA Lab](session_01/lab_03/lab_03.adoc)
  - [Lab Review - PCF Architecture and PCF Push](session_01/Labs_Review_01_PCF_Deep_Dive.pdf)
  - [Lab Review - Scaling, Metrics, Logs and HA](session_01/Labs_Review_02_Zero_Dep_Services_Logs_HA.pdf)

#### Session 2 [(Slides)](session_02/Session_2_CloudNativeDesignDev.pdf): _Cloud Native Design and Microservices with Spring Cloud Services_
  - [Lab 4 - Dynamic Configuration Loading with Spring Cloud Services - Config Server](session_02/lab_04/lab_04.adoc)
  - [Lab 5 - MicroServices Registration and Discovery with Spring Cloud Services - Eureka](session_02/lab_05/lab_05.adoc)
  - [Lab 6 - Fault Tolerant Design with Spring Cloud Services - Hystrix](session_02/lab_06/lab06.adoc)
  - Lab Review - Spring Cloud Services - Discussion

#### Session 3 [(Slides)](session_03/Session_3_Continuous_Integration_Delivery.pdf): _Continuous Integration/Continuous Delivery with PCF_
  - Demo - CI/CD pipeline with Jenkins and PCF

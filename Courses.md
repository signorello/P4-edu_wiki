# P4 and P4-NetFPGA Related Courses

## Courses dedicated just to P4
TBD, nothing at the moment

## Undergraduate Courses

## Graduate Courses

### Build an Internet Router (CS344)
**University:** Stanford University

**Aims of the course:** High-performance network system design. Students will work in teams of two to build a fully functioning Internet router. Students will design the control plane in Python on a linux host and will design the data plane in the P4 language on the NetFPGA SUME 4 x 10GE switch. For the midterm milestone, teams must demonstrate that their routers can interoperate with the other teams by building a small topology utilizing everyone's router. In the final 3-4 weeks of the class, teams will participate in an open-ended design challenge.

**Target audience and prerequisites:** Graduate and advanced undergraduate students that are interested in obtaining practical, hands-on experience. Prerequisites: (1) Experience with Python, (2) At least one member in each group should have a strong understanding of static router functionality, e.g. completed [Lab 3](http://web.stanford.edu/class/cs144/assignments/router/assignment.html) of CS144 at Stanford

**Length of the course:** 10 Weeks

**Relation to P4:** Students implement the data-plane of the router in P4 using the [P4->NetFPGA](https://github.com/NetFPGA/P4-NetFPGA-public/wiki) workflow. Many teams also do interesting P4 projects during the design challenge.

**Website:** https://build-a-router-instructors.github.io/

**Available material:** There are two github organizations:

1. [Build-A-Router-Instructors](https://github.com/Build-A-Router-Instructors) - Instructors should be added to this organization. It contains two repositories: (1) P4-NetFPGA-Router-Instructors which is a fork of the P4-NetFPGA-live repo that contains the solution for the Internet router assignment, (2) Build-A-Router-Instructors.github.io which is the repo for the course website.

2. [Build-A-Router-Students](https://github.com/Build-A-Router-Students) - Students should be added to this organization. It currently contains one repository, P4-NetFPGA-Router-Students, which is also a fork of the P4-NetFPGA-live repo that contains the starter code for the router assignment. At the time the course is offered, instructors should also fork the [p4lang/tutorials](https://github.com/p4lang/tutorials) repo into this organization.

**Status:** This course was offered in Spring 2018 at Stanford. The class consisted of 12 students total, only three of which had any experience with HDL prior to taking the course. All teams were able to successfully build and test their routers within 6.5 weeks. All teams completed interesting, research-oriented, design challenge projects.


### High Performance Networking (P51)
**University:** University of Cambridge

**Aims of the course:** A practical course providing an introduction to high-performance network devices. Covers aspects of realistic switch design, understanding network-device architecture and performance. Students are assessed based on a practical assignment: the design of a high-performance network device. 

**Target audience and prerequisites:** Graduate students (Masters and PhD level), also taken not-for-credit by postdocs. Prerequisites include an undergraduate course in networking, good working knowledge of C/C++, ECAD, Unix.

**Length of the course:** 6 lecture hours, 10 (5x2) lab hours. Students are expected to do their project outside lab hours.

**Relation to P4:** Practical work (i.e. project) using P4-NetFPGA.

**Website:** [http://www.cl.cam.ac.uk/teaching/current/P51](http://www.cl.cam.ac.uk/teaching/current/P51)

**Available material:** All the course's materials are available [on the course website](http://www.cl.cam.ac.uk/teaching/current/P51/materials.html).

**Status:** In 2017/18 the course was delivered using NetFPGA (not P4-NetFPGA), as the platform (PTA) wasn't ready.
Lab 1-2 require rewriting, may also add another programmable devices lecture, instead of (e.g.,) latency.

**Wishful thinking:** Creating an online P4-NetFPGA tutorial that compiles programs, like the NetFPGA verilog tutorial used for P33 (Building an Internet Router).

## Template
Please use the template below to describe a course

### Course Name
**University:**

**Aims of the course:**

**Target audience and prerequisites:**

**Length of the course:**

**Relation to P4:**

**Website:**

**Available material:**

**Status:**
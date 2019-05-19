This page summarizes the results of the P4 Education survey, conducted in May 2019.
The survey was answered by 19 people.

**1. What is your role?**
- 42.1% Researcher / Engineer
- 36.8% Lecturer / Professor
- 15.8% Students
- 5.3% Teaching assistant / Instructor

**2. Are you teaching, or have you taught in the past, programmable data planes?**
- 52.6% No
- 47.4% Yes

**3. If you answered yes, are you using (or have you used) P4 in your course?**
- 100% of those who replied "Yes" to the previous question, have replied "Yes" here too

**4. Are you using, or have you used in the past, programmable data planes in your (or your students') research?**
- 84.2% Yes
- 15.8% No

**5. If you answered yes, are you using (or have you used) P4 in your research?**
- 84.2% Yes
- 15.8% No
- (Similar to the previous question)

**6. If you (or your students) use P4 in your research, what type of technologies are you using? (multiple answers allowed)**
- 73.7% Behavioral models (e.g., bmv2)
- 57.9% Simulation tools (e.g., Mininet, ns3)
- 42.1% Switch ASIC (e.g., Barefoot Tofino)
- 36.8% FPGA (e.g., SDNet, P4->NetFPGA)
- 31.6% SmartNIC (e.g., Netronome, NetCope)

**7. What are the exact hardware and software targets that are you using? (multiple answers allowed)**
- 67% bmv2 
- 60% Mininet 
- 53.3% Barefoot Tofino 
- 40% NetFPGA 
- 20% Netronome Agilo
- 13.3% NS-3 
- 6.6% MACSAD
- 6.6% NetCope
- 6.6% P4@ELTE
- 6.6% SDNet and various Xilinx boards

**8. How did YOU learn P4? (multiple answers allowed)**
- 94.7% On my own / from the spec
- 52.6% Online tutorial
- 36.8% Tutorial at a conference or a dedicated event
- 5.3% from a colleague
- 5.3% I attended an academic course
- 5.3% I attended a commercial course

**9. How did your students learn P4? (10 responses, multiple answers allowed)**
- 60% They attended an academic course
- 50% Online tutorial
- 30% On their own / from the spec
- 20% Tutorial at a conference or a dedicated event
- 10% They attended a commercial course
- 10% They have never learnt P4

**10. Describe the existing P4 educational materials that you have used**
(answers removed or altered to maintain anonymity)
- Barefoot Academy
- P4 spec
- Tutorials / P4lang/tutorial
- We have four hours of lectures with a general introduction and discussion of three papers. We have one small project on P4 that varies each year.
- I have used sigcomm online tutorial, p4lang sample project reposity
- https://p4.org/specs and https://p4.org/publications
- Tutorial VM, Slides from past P4 and P4-NetFPGA tutorials, P4-NetFPGA respository etc
- P4 workshops, SIGCOMM tutorial
- P4-16 specification and examples from the p4lang/p4-spec github repository
- youtube videos, specifications, ONF connect collateral webpage
- hhk3.kau.se/dpp
- slides and assignments from past P4 tutorials 

**11. What P4 educational materials are currently missing?**
(answers removed or altered to maintain anonymity)
- Too many to name :)
- P4 toolchains
- Integration with control plane like OpenDaylight, NOS(SONIC etc) etc.
- Material for bmv2 backend exist, but p4 for smartnic for example has different specifications. For example, cloning packets, metadata field sizes are different from bmv2 based p4 specs. Also I didn't found good documentation for software p4 based kernel bypass targets. 
- Materials for undergraduate courses
- NDAs with the Tofino are the biggest problem at the moment. It makes the real P4 inaccessible to the students. 
- more production like use case.
- Case studies: short 5-10 minute labs, with a specific but typical task, some pointers how the solution would look like, and a mininet (or similar) environment in which the developed solution can be tried out; these are called "tasks" in Kubernetes docs, see e.g., https://kubernetes.io/docs/tasks/run-application/run-single-instance-stateful-application or https://istio.io/docs/tasks/traffic-management/fault-injection.
- The basics are there, but need more in-depth and very good documentation of existing tools. It is especially hard to match the spec with different targets.
- getting from zero to running P4 program is an untenable disaster
- Focused tutorials on specific topics (e.g. registers, re-circulation, P4_16 Externs) and not only per use cases. 
- it only teaches about the P4 language but doesnot tell anything about the control of switches from remote controller using P4Runtime. Although specification is present but it not very clear how to use P4Runtime in the specification either.
- Imho, it is not the content missing rather the right format for different purposes. For example, it would be great to have introductory courses of different levels meant for different target audiences. I would also go for an open template-format where lecturers can remove from/add to at their convenience. 

**12. Have you developed any P4 related teaching materials? (18 replies)**
- 50% Yes
- 50% No

**13. If you answered Yes, please provide a short description of the teaching materials.**
(answers removed or altered to maintain anonymity)
- Multiple different websites were pointed to
- I have some teaching material that glues together different talks (re-adapted) or slides from other universities. 
- No directly meant for teaching but can be used in the long term for teaching. The idea, is to build R&E use case step by step. One step being a lab. 
- Slides and labs
- My own slides and re-interpretations of P4 association diagrams
- Undergrad networking lab on the internals of a router. Grad class on P4 using P4 github repo examples
- I have prepared slides and hands-on assignments for master's courses and for tutorials at international conferences on networking-related topics.

**14. If you answered Yes, have you made this materials openly available? (9 replies)**
- 66.7% Yes
- 33.3% No

**15. If you answered No, why have you not made these materials openly available?**
- They contain proprietary information
- The material is not of high-quality.
- I have thought the material fit perfectly for the purpose of my teaching activities, but I am not sure that has been prepared in a way others could easily borrow it for their own purposes.

**16. What will motivate you to engage with the P4 Education work group?**
- Hopefully we can d- evelop some common, generally useful stuff
- Increase developers who know P4 well.
- Sharing ideas on teaching
- Share our resource and create these LABS together would be perfect fit so that R&E from any organization worldwide can implement the reference use cases 
- Need more contributors and better effort distribution, instead of each group developing on its own.
- my motivation is only tempered by my need to continue making a living :-)
- See a roadmap with collaborative actions on a common repository of code and teaching material that facilitates re-use and updates 
- Making open hardware FPGA-based platforms more accessible
- Learning from others
- being an early researcher (and lecturer too), it would encourage me knowing this is a community where I can share my teaching material/experience and get a constructive feedback about it (especially from senior lecturers). 

**17. Other comments**
- P4 resources are scattered in the web using different software set. It would be great to have a reference place where any person with or without any knowledge can get access to a list of reference labs. Each lab having a tag qualifying the tag. lab code having the tag: BUILD_COMPONENT can be cut and paste into a production code. (ARP learning code for example) Also it would be great to have EDITOR like netbeans having a P4 as a selectable language. Cherry on the cake would be to have a "Visual Pipeline diagram", each part of the diagram can be clickable and give access to a CODE box. I can click on the Parser part of the diagram and get a sub code window where I can put the Parser code.
- P4 itself is a very nice construct. The Xilinx P4-SDNet compiler not implementing several parts of the specification is much more problematic...






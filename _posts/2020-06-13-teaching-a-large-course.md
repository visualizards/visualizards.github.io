---
title: Teaching a large course at a university
layout: post
categories: [Teaching]
description: "Reflections after teaching a large course at a university"
---

# Teaching a large course at a university

**Recently, I had the pleasure of teaching the introduction to programming course at the Norwegian University of Life Sciences. This course is one of the largest at the university with almost 450 enrolled students. I learned a lot while teaching that course, and in this blog post, I hope to share some of these experiences.**

## Setting up for a large course
Before starting to teach a course with this many students, you must plan how to teach it. We decided to have one 90 minute theory lecture (2x45 minutes + 15-minute break) and one 90 minutes live programming lecture each week. Also, we hired a large team of teaching assistants to host a total of 10 tutorial sessions per week, each lasting for 90 minutes. In these sessions, students could ask the teaching assistants (TAs) questions about weekly problem sheets and the mandatory coursework.

At NMBU, we usually hire final year undergraduate students and first-year master's students as teaching assistants. For INF120, we hired a total of 7 teaching assistants to avoid any one of them having to spend too long time grading. Then, I asked the most experienced TA if she wanted to take the role of head TA. This role entailed being the primary contact point for students with administrative questions, coordinating the other TAs and publishing weekly exercises and coursework on the course page on Canvas (our digital learning platform).

## Preparing information for students
The first lecture did not contain any curricular information. Instead, it was split into a *why should you learn programming* presentation and half an hour with information about the course. I also asked any students that had chronic diseases or other reasons that may impede their ability to work on mandatory coursework to contact me immediately, so I was aware beforehand. 

After asking them to contact me, one student came down and thanked me for asking them to contact me immediately. They were affected by a disorder that sporadically made them unable to both work and ask for extensions. Therefore, they often wanted to tell lecturers early on but were not comfortable telling them unsolicited. This interaction made me realise that asking students to contact you immediately if they know their ability to work may be impeded in the future.

Also, in the same lecture, I made it clear that I generally do not answer e-mails from students. The only exception was if I could see from the subject line that the inquiry was not something that can be handled by the TAs. Examples of such inquiries are: 

1. death in the family, leading to reduced work capacity
1. illness that the student is not comfortable discussing with TAs
 
In essence, students should only e-mail me if they had personal matters they did not want to share with their peers. Moreover, if I did not respond to an e-mail that the student found important, they were to send follow up e-mails until I answered.

Still, it is crucial to allow the students to ask questions. If they had any issues, then I would stay after lectures and help them. Alternatively, they could e-mail the head TA, or they could ask a TA in one of the many weekly tutorial session. 

## Get it in writing
Immediately after the first lecture, I published a lengthy Q&A section on Canvas, elaborating all ground rules of the course. I repeated all the points I made clear in the first lecture, including the number of mandatory coursework exercises, how they would cope if they failed some of the coursework, etc. This Q&A was essential, because whenever I got an e-mail from a disgruntled student, then I could point to that section and inform them that they should have known better.

## Be strict
If you are teaching a course with several hundred students, then you cannot feel bad for anyone that did not do their work correctly. If they didn't meet the deadline, it's their fault, and they will fail. If they didn't ask for an extension beforehand, it's their fault. If they are elite athletes that ask for extensions the same day as the deadline, it's their fault. Never make exceptions (unless they have a doctors note), because that will only lead to countless of new e-mails.

Also, it may be tempting to answer e-mails, but don't if anyone has a question that is of interest, ignore their e-mail and publish an announcement for everyone to read.

## Make decisions in a team
Any decision that inconveniences the students are bound to make them unhappy, even if it is for their good. To avoid students being angry at you for any such decision, you need to make the decisions in a team. For me, that entailed me asking my colleagues during the morning coffee if they agreed to my judgment.

Finally, when you get requests to go back on these decisions, say that you will bring it up on the next meeting. Then, mention it to your colleagues and ask what they think. This strategy will allow you to keep authority — you didn't backpedal on your decision; instead, the section reevaluated a group decision.

## Lecture notes
I did not publish any lecture notes or code from lectures. Instead, all lectures were recorded and posted online. Thus students needed to write their notes. Some students loudly complained that they did not like this solution, but after polling, I learned that students liked it that way too.

## Mandatory coursework vs weekly problem sheets
We hired students to make the weekly problem sheets and to make them relevant for the students. Still, most students did not work on the weekly problems. Even the mandatory coursework was often sloppily done. Therefore, for future courses, I would have more mandatory coursework where each hand-in is easy to pass.

## Lecture structure
As mentioned earlier, we had one theory lecture each week and one live-programming lecture each week. For the theory lectures, I used a document camera/visualiser. With this camera, I could write on paper, which in turn was projected on the wall behind me. By using pre-defined colours for theory (black) code (blue) code output(red) and remarks (green), I made clear notes that the students could easily copy into their notebooks. 

For the live-programming lectures, I would start on small code snippets, which I in turn asked the students to complete. Then, 5-15 minutes would be spent by the students programming and me walking around, before I would program the solution live. This teaching style showed how we, knowing only a small amount of programming, could solve real-world engineering problems. Examples of such tasks were:
* parsing GPS/GNSS logs (NMEA files)
* reorganising spectrometry data files to analyse them with different tools
* performing simple stochastic pandemic simulations 
* visualising data from the local climate station
In addition, I planned to analyse insulation data from experimental buildings, but unfortunately, I had to drop that project because of COVID-19.

Based on the course review, the students were excited about this way of teaching programming. For future courses, I would reorganise the timeline somewhat, so students learned visualisation with Matplotlib and Pandas earlier, to make some of the examples more exciting.

## Lessons from COVID-19 and online learning

Half-way through the semester, COVID-19 struck, and we had to move all teaching online. There were some problems, but we also learned some intriguing facets of video teaching. Specifically, I tried two different formats for the theory lectures: long-form videos where I made notes on an iPad while I simultaneously recorded audio; and short-form videos where I sped up my notetaking speed and narrated the video afterwards. The length of the notes where the same, but the second format yielded ~30 minutes of video divided over four videos in a playlist instead of one 60 minute video.

Then, I asked the students which format they preferred, and to my surprise, their preference was split approximately 50-50 between the two forms. Considering the extra time-effort needed for the short-form videos and those students who prefer longer videos are likely more diligent than those who prefer short videos, I decided to continue with the long-form videos.

## Summary
In summary, I recommend that anyone teaching a large course does the following steps
1. hire a head TA to be the primary contact for students with questions
1. ask students with a good reason for possibly needing extensions on deadlines to contact you after the first lecture
1. make it clear that you will not reply to e-mails, instead, stay after lectures and answer questions
1. make team decisions
1. have everything in writing
1. be strict with the rules

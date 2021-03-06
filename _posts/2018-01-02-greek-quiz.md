---
title: 'Writing a Greek quiz app.'
date: 2018-01-02
permalink: /greek-quiz/
tags:
  - quiz
layout: post
excerpt: "I'm in the process of creating an online quiz app for my Homer students in Spring 2018. The idea is that the app will present the student with a certain number of inflected verb, noun, or adjective forms..."
---

I'm in the process of creating an online quiz app for my Homer students in Spring 2018. The idea is that the app will present the student with a certain number of inflected verb, noun, or adjective forms of the most frequent ones listed in William Owen and Edgar Goodspeed's *Homeric Vocabularies: Greek and English Word-Lists for the Study of Homer* (Norman 1969), and the student will be asked to return the first principal part.

So, for example, the app will ask a student how many forms he or she would like to be quizzed on. Say the student inputs "6." Afterward, the quiz app will present, e.g., ἄξομαι. The student, to move on, will need to input ἄγω. This will happen six times.

A few things I'm learning as I try to write the Python code. 1: There are *so. many. inflected. verb. forms.* One regular verb (all six principal parts, active and medio-passive forms, all moods) comprises over 100 forms! 2: Full stack developers are crazy. It was hard enough to come up with this back-end Python code, but now I'm trying to teach myself Flask and Heroku (and thus HTML, CSS, and Javascript) to get my code to render on the front end. HOW do you keep all this information straight?!

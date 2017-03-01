---
layout:  home
title:   Formal Labs
tagline: Formal Languages & Automata Labs
---
# Labs

<ul class="posts">
  {% for post in site.posts reversed %}
    <li>
    <small class="post-date">{{ post.date | date: '%-d %b' }}</small>
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
      – {{ post.tagline }}
    </li>
  {% endfor %}
</ul>

# Administration

The lab activity will consist of implementing **3 projects**. You can chose the subject for each of them (choices listed below).

During the labs, we will discuss the projects and afterwards you will submit your solution (timetable listed below).

**Evaluation**: each project will receive a 1-10 grade, final grade is their average. *Exceptional* project implementations can receive up to 12. Bonuses can be awarded for class work.

**Timetable**:

![timetable](assets/timetable.pdf)

*Note:* We'll have to reschedule/find a solution for Lab 4: 20 Apr — easter break, 13 Apr — I'll be out of the country.

**Project choices**:

Project 1

- DFA accepter


- *bonus:* NFA accepter

Project 2 *(subject to change)*

- λ-NFA → NFA
- NFA → DFA
- *bonus:* DFA minimization

Project 3 *(subject to change)*

- RE → DFA
- CYK
- *bonus:* DFA → RE
- *bonus:* CNF

**Programming languages**: you can implement the projects in any language you want. I highly recommend **C++** as it will also help you in your OOP course. Examples will be given in C++ as well.

**Attendance**: mandatory (at least for project submission).



## Links

Attendance, projects and grades: [bit.ly/lab-lfa](http://bit.ly/lab-lfa) (Gr 134 & 135)

Moodle: [moodle.fmi.unibuc.ro/course/view.php?=id=432](http://moodle.fmi.unibuc.ro/enrol/index.php?id=432)

## Contact

Stefan Niculae (Teaching Assistant) — stefan1niculae@gmail.com

Andrei Paun (Professor) — apaun@fmi.unibuc.ro
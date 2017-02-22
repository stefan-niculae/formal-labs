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

# Purpose

This supplement aims to be a quick-ref — between a lesson and a cheatsheet.

It has three purposes:

1. help me organize what to write on the whiteboard
2. help you quickly recap previous labs
3. give you a quick run-down in case you skipped a lab (hopefully not used very often)

This page alone is not sufficient for the class. It is not a substitute for **attending** the labs or the lectures.


# Administrative issues

TBA: homework, tests etc

## Links

Attendance sheet: [bit.ly/lab-lfa](http://bit.ly/lab-lfa). Sheets for 134 and 135.

Moodle: [moodle.fmi.unibuc.ro/course/view.php?=id=432](http://moodle.fmi.unibuc.ro/enrol/index.php?id=432) password: TBA


# Contact

Stefan Niculae (Teaching Assistant) — stefan1niculae@gmail.com

Andrei Paun (Professor) — TBA

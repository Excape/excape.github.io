---
permalink: /projects
layout: single
author_profile: true
toc: true
header:
  image: /assets/images/lisbon.jpg
---

I publish all my code from my projects and experiments to my <i class="fab fa-github"></i> [GitHub](https://github.com/Excape){:target="blank"} page.

Here I'll highlight some things I've been working on:

## Projects

### [<i class="fab fa-github"></i>](https://github.com/public-transport-quality-grades){:target="blank"} Public Transport Quality Grades (2018)

This is my just finished bachelor thesis. It's about grading public transport service in Switzerland. We created a new specification and implemented a CLI tool using Python to generate the gradings, which can be visualized inside a React application.

Technologies: <i class="fab fa-python"></i> Python, Flask, <i class="fab fa-react"></i> React, <i class="fas fa-database"></i> PostgreSQL, PostGIS


---

### [<i class="fab fa-github"></i>](https://github.com/plazaroute){:target="blank"} PlazaRoute (2017)

This was my student research project. We used data from [OpenStreetMap](https://www.openstreetmap.org){:target="blank"} and improved on pedestrian routing through open areas by calculating shortest paths through them.

Technologies: <i class="fab fa-python"></i> Python, Flask 

---

### [<i class="fab fa-github"></i>](https://github.com/examibur){:target="blank"} Examibur (2017)

This was an engineering project for my studies. We created a web application to grade and review exams. It was also an exercise in using SCRUM in a team of 4 people.

Technologies: <i class="fab fa-java"></i> Java, Java Spark, <i class="fas fa-database"></i> PostgreSQL

---

### [<i class="fab fa-github"></i>](https://github.com/Excape?tab=repositories&q=hsr-docs){:target="blank"} HSR Study Notes (2016 - 2018)

From my second semester at [HSR](http://hsr.ch){:target="blank"} onward, I wrote all my notes for my classes in Markdown and built a static website using [MkDocs](https://www.mkdocs.org/){:target="blank"}. That way, I always had a nicely formatted site of my notes without any overhead.

The websites are all still online:

* [Spring Semester 2016](https://robinsuter.ch/hsr-docs-fs16/){:target="blank"}
* [Fall Semester 2016](https://robinsuter.ch/hsr-docs-hs16/){:target="blank"}
* [Spring Semester 2017](https://robinsuter.ch/hsr-docs-fs17/){:target="blank"}
* [Fall Semester 2017](https://robinsuter.ch/hsr-docs-hs17/){:target="blank"}
* [Spring Semester 2018](https://robinsuter.ch/hsr-docs-fs18/){:target="blank"}

Technologies: Markdown, MkDocs, Travis CI

---

### [<i class="fab fa-github"></i>](https://github.com/openhsr/connect){:target="blank"} Open\HSR Connect (2016)

With our group of Open Source enthusiasts ([Open\HSR](https://www.openhsr.ch/){:target="blank"}) we created a Python application to handle the common tasks in our university more easily (specifially on Linux machines), like installing a printer or downloading the lecture slides.
My contribution was a file synchronisation between the remote file server and the local computer.

Technologies: <i class="fab fa-python"></i> Python

## Experiments

Here are some ideas I've played around with. They never grew to be complete projects and they were mostly created in an afternoon.

---

### [<i class="fab fa-github"></i>](https://github.com/Excape/lyrics-analysis){:target="blank"} Lyrics Analysis (2017)

When the [Natural Language API](https://cloud.google.com/natural-language/){:target="blank"} from Google was released, I thought it would be fun to feed some lyrics into it. I gathered lyrics from the charts in the last 20 years from various APIs and fed them through the Google API to get the sentiment score (how positive or negative a text is). I never got any meaningful results, but it was fun to play around with.

Technologies: <i class="fab fa-python"></i> Python

---

### [<i class="fab fa-github"></i>](https://github.com/jmatj/har2pcap){:target="blank"} har2pcap (2016)

One afternoon we were playing around with the Chrome developer tools and wanted to analyze some network traffic with Wireshark. But Chrome works with the HAR format, Wireshark with pcap. We didn't find any tool to convert between those formats, so we wrote one ourselves.
It was an interesting challenge to pick apart a binary protocol (pcap) and construct data according to the protocol specifications.

Technologies: <i class="fab fa-python"></i> Python, TCP/IP

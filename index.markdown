---
layout: home
---

## Welcome to the Karlsruhe Rationality Meetup

We meet monthly to discuss rationalist ideas, inspired by the [ACX Meetups Everywhere](https://astralcodexten.substack.com/p/meetups-everywhere-2024) and the [LessWrong Community](https://lesswrong.com/community). 

Our next meetup is: 
- **Date**: Wednesday, 6th November 18:30
- **Location**: Student Centre Z10, 'Salon' (2. OG/Raum 15)

Check out more details on the [Events](/events) page.

### Recent Posts

<ul>
  {% for post in site.posts limit: 3 %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

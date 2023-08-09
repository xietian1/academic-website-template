---
title: "Team"
layout: gridlay
sitemap: false
permalink: /team/
---

## Team

 **We are  looking for new team members** [(see news)]({{ site.url }}{{ site.baseurl }}) **!**

<h2 class="team-role">Faculty</h2>
{% assign group = "PI" %}
{% assign sorting_criteria = "bio.start" %}
{% include_relative members.md %}

---


<h2 class="team-role">Ph.D.</h2>
{% assign group = "PhD" %}
{% assign sorting_criteria = "bio.startDate" %}
{% include_relative members.md %}


---

<h2 class="team-role">Alumni</h2>

#### Ph.D. Students

{% assign group = "Alumni-PhD" %}
{% assign sorting_criteria = "bio.endDate" %}
{% include_relative members.md %}

<br>
#### Master Students & Undergraduate Students



---




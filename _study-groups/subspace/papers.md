---
layout: post
title: "Paper discussions in the subspace group"
---

#### Paper discussions

***
{% for discussion in site.data.subspace.paper_discussions.papers %}
###### {{ discussion.title }} -- *{{ discussion.author }}*

* [**Link to paper**]({{ discussion.paper-url }})
* [**Click here to watch on YouTube!**]({{ discussion.recording-url }}) (Duration: {{ discussion.duration }})

***

{% endfor %}
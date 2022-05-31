---
layout: post
title: "The #BSIsubspace Virtual Talks"
---

### Virtual talks
##### 2021

{% for discussion in site.data.subspace.talks.talks %}
<div class="text-left people-modal">
    <div class="modal-body">
        <div class="people-details">
            <div class="row">
                <div class="col-md-2 col-sm-2">
                    {% assign speaker = site.data.speakers[ page.leader ] %}
                    <div class="flow-img img-circle people-img" style="background-image: url({{ site.baseurl | append: '/img/people/' | append: discussion.speaker-img }})"></div>
                </div>
                <div class="col-lg-10 col-sm-10 details">
                    <p class="name" style="font-size: 18px"> {{ discussion.title }} 
                        <span class="position">- {{ discussion.speaker }}</span>
                    </p>
                    <p>
                        <a href="{{ discussion.paper-url }}" target="_blank">
                            <strong>Link to paper</strong>
                        </a>
                    </p>
                    <p>
                        <a href="{{ discussion.recording-url }}" target="_blank">
                            <strong>Click here to watch on YouTube!</strong>
                        </a>
                    </p>
                </div>
            </div>
        </div>
    </div>
</div>
{% if forloop.index == 3 %}
<!-- more -->
{% endif %}
{% endfor %}

### Virtual talks
##### 2021
[![]({{ site.baseurl }}/img/subspace-updates/Virtual_Talks_Info.png)](https://www.youtube.com/playlist?list=PLADTemYh-7P3ih6KDbhvLEzsGnYcoez_x)


<iframe width="560" height="315" src="https://www.youtube.com/embed/videoseries?list=PLADTemYh-7P3ih6KDbhvLEzsGnYcoez_x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

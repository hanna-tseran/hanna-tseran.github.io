---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find some of my publications on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

{% if author.googlescholar %}
  You can also find some of my publications on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<div>

  <div class="author__urls-wrapper">
    <button class="btn btn--inverse">Follow</button>
    <ul class="author__urls social-icons">
      {% if author.googlescholar %}
        <li><a href="{{ author.googlescholar }}"><i class="fas fa-fw fa-graduation-cap"></i> Google Scholar</a></li>
      {% endif %}
    </ul>
  </div>
</div>

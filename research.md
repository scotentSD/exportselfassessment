---
title: Research Timeline
---

<section id="research">
  <h1>Research Timeline</h1>
  <ul class="timeline_ul">
    {% for post in site.posts %}
        <li class="timeline_card">
            <a href="{{site.url}}/{{site.github.repository_name}}{{post.url}}">
              <div class="date_other"> {{ post.display_date }} :: {{ post.rtitle}} </div>
          </a>
       </li>
    {% endfor %}
  </ul>
</section>

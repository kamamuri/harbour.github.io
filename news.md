---
layout: default
title: "News Archive"
---

# News Archive

This page gives you some of the main changes introduced in recent versions of
Harbour. To view the latest [`ChangeLog.txt`](changelog.html) or
[download](https://sourceforge.net/projects/harbour-project/files/) lastest
stable release of Harbour.

You can find the detailed list of changes
[here](https://raw.githubusercontent.com/harbour/core/master/doc/oldnews.txt).

---

<div markdown="1" class="news news-full">
{% for story in site.data.news %}
  {{ story.date }}
  : **{{ story.title }}**<br>
    <p>{{ story.text }}
{% endfor %}
</div>
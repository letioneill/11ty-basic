---
title: My first page
layout: base.njk
templateEngineOverride: njk,md
---
# Blog Posts

{% include "postlist.njk" %}

## Cat of the Day

<img class="cat-img" src="{{ catpic }}" />

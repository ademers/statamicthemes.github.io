---
title: "Accessing Member Fields"
layout: post
meta_desc: >
  If you need to output a member field and
  don't want to wrap your content in a
  `{{ member:profile }}` tag pair then you
  can just use a single tag.
author: garethredfern
categories:
  - template tags
tags:
  - reference
summary: >
  If you need to output a member field and don't
  want to wrap your content in a `{{ member:profile }}`
  tag pair then you can just use a single tag.
---
{% raw %}
~~~.language-markup
{{ current_member:field_name }}
~~~
{% endraw %}
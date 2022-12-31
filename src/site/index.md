---
title: Systemantics
subtitle: People-centered design management and enablement systems.
layout: layouts/base.njk
---

## Jay Smith

I’m a system-thinking design leader collaborating with other cool humans at the nation’s [largest consumer cooperative](https://www.rei.com/). I really&mdash;really&mdash;love helping teams create, scale, and maintain accessible, cohesive experiences.

Currently working and living in the Ballard neighborhood of Seattle.

## Writing

Reflections on past experiences and forward-looking ideas.

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>

## Contact

The best way to get in touch is an [email](mailto:jaysmizle@gmail.com). Feel free to also connect with me on [LinkedIn](https://www.linkedin.com/in/jaysmizle/), [ADP List](https://adplist.org/mentors/jay-smith), or [GitHub](https://github.com/jaysmizle).

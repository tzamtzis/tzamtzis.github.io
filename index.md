---
layout: home
title: "Tzam"
---

# Hi, I'm Panagiotis — most people call me Tzam 👋

I'm a team lead at [Baresquare](https://baresquare.com),
based in Thessaloniki, Greece. You can also find me at my personal site
[tzamtzis.gr](https://tzamtzis.gr). I lead the Digital Analytics Developers team
and work with clients like Sony and Condé Nast on data engineering, tagging
operations, and AI-assisted automation.

Outside of work I'm usually:

- tinkering with **smart-home automation** (Shelly devices, Home Assistant,
  solar water heaters, irrigation controllers)
- self-hosting things on a **Synology NAS** (Jellyfin, Perplexica, nginx
  reverse proxy, the usual rabbit hole)
- **running** — currently training for the Marakez Pyramids Half Marathon
  in Cairo, December 2026
- writing notes in **Obsidian** about all of the above

## What's here

- **[About](/about/)** — longer bio and what I work on
- **[Projects](/projects/)** — selected technical projects and write-ups
- **[Notes](/notes/)** — short-form posts on analytics, AI tooling, and home automation
- **[Uses](/uses/)** — hardware, software, and self-hosted stack

## Latest posts

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>— {{ post.date | date: site.minima.date_format }}</small>
    </li>
  {% endfor %}
</ul>

---

Find me on [GitHub](https://github.com/tzamtzis) ·
[tzamtzis.gr](https://tzamtzis.gr) ·
[email](mailto:panagiotis@baresquare.com)

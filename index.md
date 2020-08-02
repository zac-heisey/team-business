---
layout: default
title: Team Business
description: ''
intro-big: We Teach the Hard-Learned Lessons of Business Through Face-to-Face Experiences
intro-small: We Are Team Business
video-heading: There's An Easier Way to Learn the Hard Way
video-sub-text: Fast-track your team’s business acumen with hands-on business training
  simulations. For anyone from students to executives, Team Business can help turn
  principles of business operation into habits.
video-id: zWNO2mUUcYA
sections:
- heading: Our Programs
  include: programs.html
- heading: Our Services
  include: services.html
- heading: What Our Clients Say
  include: testimonial.html
- heading: Who We've Worked With
  include: clients.html

---
<!-- This pulls text from the 'Intro Main' and 'Intro Sub' fields in the left-hand pane -->
{% capture big %}{{ page.intro-big }}{% endcapture %}
{% capture small %}{{ page.intro-small }}{% endcapture %}

{% include intro.html hero-intro-1=big hero-intro-2=small %}

___

<!-- Homepage Video (you can edit the video ID, heading, and sub-text fields below) -->
{% capture video-heading %}{{ page.video-heading }}{% endcapture %}
{% capture video-sub %}{{ page.video-sub-text }}{% endcapture %}
{% capture video-id %}{{ page.video-id }}{% endcapture %}

{% include video.html id=video-id heading=video-heading sub-text=video-sub %}

___

<!-- Loop through section headings and includes -->

{% for section in page.sections %}

  <h2 id="{{ section.heading | slugify }}">{{ section.heading }}</h2>

  {% include {{ section.include }} %}

  ___

{% endfor %}

<!-- Site-wide CTA -->
{% include cta.html %}

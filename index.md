---
layout: default
title: Team Business
description:
intro-main: We Teach the Hard-Learned Lessons of Business Through Face-to-Face Experiences
intro-sub: We Are Team Business
---

<!-- This pulls text from the 'Intro Main' and 'Intro Sub' fields in the left-hand pane -->
{% include intro.html hero-intro-1="{{ page.intro-main }}" hero-intro-2="page.intro-sub" %}

___

<!-- Homepage Video (you can edit the video ID, heading, and sub-text fields below) -->
{% include video.html id="zWNO2mUUcYA" heading="There's An Easier Way to Learn the Hard Way" sub-text="Fast-track your team’s business acumen with hands-on business training simulations. For anyone from students to executives, Team Business can help turn principles of business operation into habits." %}

___

## Our Programs
<!-- Add, delete, or edit these in 'Data/programs.yml' -->
{% include programs.html %}

___

## Our Services
<!-- Add, delete, or edit these in 'Data/services.yml' -->
{% include services.html %}

___

## What Our Clients Say
<!-- Add, delete, or edit these in 'Clients' -->
{% include testimonial.html %}

___

## Who We've Worked With
<!-- Add, delete, or edit these in 'Clients' -->
{% include clients.html featured=true %}

___

{% include cta.html %}

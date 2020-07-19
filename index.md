---
layout: default
title: Team Business
description: ''
intro-big: We Teach the Hard-Learned Lessons of Business Through Face-to-Face Experiences
intro-small: We Are Team Business
video:
- heading: There's An Easier Way to Learn the Hard Way
- id: zWNO2mUUcYA
- sub-text: Fast-track your team’s business acumen with hands-on business training simulations. For anyone from students to executives, Team Business can help turn principles of business operation into habits.
section-headings:
- programs: Our Programs
- services: Our Services
- testimonials: What Our Clients Say
- featured-logos: Who We've Worked With
---

<!-- This pulls text from the 'Intro Main' and 'Intro Sub' fields in the left-hand pane -->
{% capture big %}{{ page.intro-big }}{% endcapture %}
{% capture sub %}{{ page.intro-small }}{% endcapture %}

{% include intro.html hero-intro-1=big hero-intro-2=small %}

___

<!-- Homepage Video (you can edit the video ID, heading, and sub-text fields below) -->
{% capture video-heading %}{{ page.video.heading }}{% endcapture %}
{% capture video-sub %}{{ page.video.sub-text }}{% endcapture %}
{% capture video-id %}{{ page.video.id }}{% endcapture %}

{% include video.html id=video-id heading=video-heading sub-text=video-sub %}

___

## {{ page.section-headings.programs  }}
<!-- Add, delete, or edit these in 'Data/programs.yml' -->
{% include programs.html %}

___

## {{ page.section-headings.programs  }}
<!-- Add, delete, or edit these in 'Data/services.yml' -->
{% include services.html %}

___

## {{ page.section-headings.testimonials  }}
<!-- Add, delete, or edit these in 'Clients' -->
{% include testimonial.html %}

___

## {{ page.section-headings.featured-logos  }}
<!-- Add, delete, or edit these in 'Clients' -->
{% include clients.html featured=true %}

___

{% include cta.html %}

---
layout: page
title: About
permalink: "/about/"
description: Team Business helps universities, colleges, high schools, businesses,
  and organizations build business experience through specialized programs and workshops.
section-title:
intro-1: Our Experience Can Improve Your Learning Experience
intro-2: Team Business believes that hands-on experiences are the best way to build
  business experience. So our goal is to create safe places for those experiences
  to happen.
header-image: 'https://res.cloudinary.com/zheisey/image/upload/f_auto/v1568839102/teambusiness/about-bg.jpg'

---
## Team Business offers business education programs in the form of hands-on simulations that are designed to teach through experience.

The Team Business experiences use basic financial tools to plan production activities, resource requirements, measure performance and benchmark against the competition. Participants get to observe the outcome of their business decisions, acquiring an understanding of the relationship between decisions made and outcomes realized.

We believe in learning through doing, so we create a safe environment to make mistakes and ask questions. All of the Team Business simulations and programs are designed with the principles of peer feedback, team-building, competition, and communication. Each program is facilitated by an expert certified instructor. Team Business is able to accommodate all levels of learning, from interns to C-suite executives.

<!-- Buttons -->
<div style="display:flex; justify-content:center; flex-wrap:wrap; margin:2rem 0;">
  <a href="#" class="btn btn-default" style="margin:10px;">Learn More About Our Programs</a>
  <a href="#" class="btn btn-default" style="margin:10px;">View Our Corporate Offerings</a>
</div>

<!-- Team Business Programs Video -->
{% include video.html id="M9_TtXZFefc" heading="See Our Programs in Action" sub-text="" %}

## Team Business is honored to work with top universities, colleges, high schools, businesses and organizations.

<!-- Client Logo Display -->
<div class="client-logo-wrapper">
  {% for client in site.clients %}
  <div class="client-logo-item" style="background-image: url({{ client.logo }});"></div>
  {% endfor%}
</div>

## What Our Clients Say
<!-- Testimonials -->
{% include testimonial.html %}

## Who is Team Business?

{% include team.html %}

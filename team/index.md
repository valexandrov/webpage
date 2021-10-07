---
title: Team
nav:
  order: 4
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team
Thank you for being interested in our research! Our work in Alexandrov Research Group is based on Shared knowledge and skills, an optimistic, can-do attitude, and mutual respect.


{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdoc"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: phd"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: postdog"
%}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
  style="button"
%}
{:.center}

{% include section.html %}

## Gallery

Gallery
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/gallery-1.jpg"
  link1="https://valexandrov.github.io/varg/images/gallery-1.jpg"

  image2="images/gallery-2.jpg"
  link2="https://valexandrov.github.io/varg/images/gallery-2.jpg"

  image3="images/gallery-3.jpg"
  link3="https://valexandrov.github.io/varg/images/gallery-3.jpg"

  image4="images/gallery-4.mov"
  link4="https://valexandrov.github.io/varg/images/gallery-4.mov"

  image5="images/photo.jpg"
  link5=""
  tooltip5="Cool Institute"

  image6="images/photo.jpg"
  link6=""
  tooltip6="Cool Initiative"
%}

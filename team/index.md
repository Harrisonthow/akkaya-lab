---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# <i class="fas fa-microscope"></i>Principal Investigators

Akkaya Lab studies adaptive immunity and immunoregulation in the context of autoimmune diseases and cancer and is composed of two research groups led by Drs. Billur Akkaya and Munir Akkaya.

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}

{% include section.html %}

# <i class="fas fa-users"></i>Researchers
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
  filters="role: mdphd"
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
  filters="role: highschool"
%}

{:.center}

{% include section.html %}

# <i class="fas fa-users"></i>Alumni

{:.center}

{% include section.html background="images/banner.webp" dark=true%}

<p style="text-align:center">“Science is the most reliable guide in life.”</p>
<p style="text-align:center"><i>Mustafa Kemal Ataturk</i></p>





{% include section.html %}

## Funding

Our work is made possible by funding from the following organizations.
{:.center}

{%
  include gallery.html

  image1="images/funding/nih.webp"
  link1="https://nih.gov/"
  tooltip1="National Institutes of Health"

  image2="images/funding/pelotonia.webp"
  link2="https://cancer.osu.edu/for-cancer-researchers/research/research-institutes-and-centers/pelotonia-institute-for-immuno-oncology"
  tooltip2="Pelotonia Institute for Immuno-Oncology"

  image3="images/funding/Ohio-State.webp"
  link3="https://idi.osu.edu/"
  tooltip2="Ohio State University Infectious Disease Institute"
%}
{:.center}
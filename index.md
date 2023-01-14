---
title: Home
carousels:
  - images: 
    - image: /images/carousel/akkaya.webp
    - image: /images/carousel/christmas.webp
    - image: /images/carousel/wex.webp
    - image: /images/carousel/lab.webp
    - image: /images/carousel/dodd.webp
---

# In immune system we trust!


The Akkaya lab combines the efforts of [Billur Akkaya, MD, DPhil](members/billur.html) and [Munir Akkaya, MD, DPhil](members/munir.html). The wife-and-husband team worked together at the National Institutes of Health. Since 2021, Drs Billur and Munir Akkaya have been working at the Ohio State University Wexner Medical Center. Billur works in the T cell lab, and works to uncover specific targets for precision therapies in the treatment of autoimmune disorders and cancers. Munir's research follows the interactions between different B cell activation modalities and how these signals collectively determine B cell fates.



{%
  include link.html
  type="link"
  icon=""
  text="Current T-Cell Projects"
  link="/t-cell"
  style="button"
%}
{%
  include link.html
  type="link"
  icon=""
  text="Current B-Cell Projects"
  link="/b-cell"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include carousel.html height="40" unit="%" duration="10" number="1" %}

{% include section.html %}

# Highlights

{% capture text %}
Autoimmune disorders and cancer are among leading causes of chronic disease and death in the US and worldwide. While Regulatory T cells (Tregs) are central to protecting body from autoimmunity, they can also promote tumor progression via restricting anti-tumor immune responses. These make Tregs an attractive, yet a risky, target for treating both ends of the spectrum, therefore we need a thorough understanding of how they mediate their inhibitory functions. Main focus of the research led by Billur Akkaya is elucidating the molecular machinery underlying interactions of Tregs with antigen presenting cells in the context of autoimmunity and cancer to reveal new specific targets for precision therapies.

{%
  include link.html
  link="/t-cell"
  text="Learn More"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/home/TCell.webp"
  link="/t-cell"
  title="T-Cell Side"
  flip=true
  text=text
%}

{% capture text %}
Vaccines have had the greatest impact on human health of all interventions. All vaccines currently in use depend on their ability to induce B cells to make high affinity long-lived antibody responses. Thus, understanding the mechanisms underlying B cell activation will clearly benefit vaccine design and development. Main focus of the research led by Munir Akkaya is to investigate the role of pathogen associated molecular patterns in B cell fate decision and identifying effector mechanisms such as cytokines and transcription factors which might drive the activation induced changes in B cell metabolism and differentiation.

{%
  include link.html
  link="/b-cell"
  text="Learn More"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include featurevideo.html
  image="images/home/ezgif.com-gif-maker.webm"
  text=text
  flip=true
%}


{% capture text %}
Meet the researchers at the Akkaya Lab!

{%
  include link.html
  link="/team"
  text="Meet the team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/home/lab.webp"
  link="/team"
  title="Team"
  flip=true
  text=text
%}
{:.center}

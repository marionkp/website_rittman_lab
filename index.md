---
title: Home
---

# Welcome to the Dementia Informatics Lab!

Thanks for checking out our website. The Dementia Informatics lab is based at the University of Cambridge. We seek to understand how dementia affects the whole brain, using a combination of brain imaging, pathology data, genetic? and cognitive testing.

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{% include section.html full=true %}

{% include banner.html image="images/banner1.jpg" %}

{% include section.html %}

# Highlights

{% capture text %}
Our research focuses on consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

[See what we've published &nbsp;→](research)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/MPRgif.gif"
  link="research"
  headline="Our Research"
  text=text
%}

{% capture text %}
We work on many different projects including basic, translational, clinical trials etc. We use various datasets and tools. QMIN MC study, Pippin? etc

[See our resources &nbsp;→](resources)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/QMINMC_logo.png"
  link="resources"
  headline="Our Resources"
  text=text
%}

{% capture text %}
We are a friendly team, include additional text in the future. Find out what everyone is working on. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

[Meet our team &nbsp;→](team)
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/Team.jpg"
  link="team"
  headline="Our Team"
  text=text
%}


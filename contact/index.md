---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Please feel free to contact the lab using information below!

{%
  include button.html
  type="email"
  text="J Nic Fisk"
  link="j.nicholas.fisk@uri.edu"
%}
{%
  include button.html
  type="phone"
  text="401.874.4473"
  link="+1-401-874-4473"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/AVMq8siANqnZDtYp7"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

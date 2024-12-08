---
title: Contact
nav:
  order: 7
  tooltip: Email, address, and location
---

# {% include headicons.html icon="fa-regular fa-envelope" %}Contact

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include button.html
  type="email"
  text="abhinay.ramaprasad@glasgow.ac.uk"
  link="abhinay.ramaprasad@glasgow.ac.uk"
%}
{%
  include button.html
  type="phone"
  text="+44 78531 41356"
  link="+447853141356"
%}
{%
  include button.html
  type="address"
  text="B625, Sir Graeme Davies Building,<br>120, University Place<br>Glasgow G12 8TA" 
  link="https://maps.app.goo.gl/tFZayEEmoZoUFYbD9"
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

{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

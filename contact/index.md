---
title: Contact
nav:
  order: 7
  tooltip: Email, address, and location
---

# {% include headicons.html icon="fa-regular fa-envelope" %}Contact

We are part of the School of Infection and Immunity, University of Glasgow and the Center for Parasitology. You can find us in the 6th floor of the Sir Graeme Davies Building.

{%
  include button.html
  type="email"
  text="abhinay.ramaprasad<br>@glasgow.ac.uk"
  link="abhinay.ramaprasad@glasgow.ac.uk"
%}

{%
  include button.html
  type="address"
  text="B625, Sir Graeme Davies Building,<br>120, University Place<br>Glasgow G12 8TA" 
  link="https://maps.app.goo.gl/WLvzMyJa332NamAG8"
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

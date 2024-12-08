---
title: Contact
nav:
  order: 7
  tooltip: Email, address, and location
---

# {% include headicons.html icon="fa-regular fa-envelope" %}Contact

We are part of the School of Infection and Immunity and the Center for Parasitology at the University of Glasgow. You can find us on the 6th floor of the Sir Graeme Davies Building.

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

{% capture content %}

{% include figure.html image="images/CenterforParasitology.png" link="" %}
{% include figure.html image="images/UoG_colour.png" link="" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

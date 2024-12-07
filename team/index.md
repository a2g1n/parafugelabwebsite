---
title: Team | Join us
nav:
  order: 4
  tooltip: About our team
---

# {% include headicons.html icon="fa-solid fa-users" %}Team | Join us

We are a fresh and dynamic malaria lab (just <span id="lab-age"></span> months old!) situated within Glasgow’s vibrant parasitology community. We are always eager to welcome motivated scientists to join us!

In our lab, we use advanced molecular genetic tools, such as CRISPR-Cas9 and DiCre, to precisely edit or knockout parasite genes and routinely identify interesting candidates that could be investigated further to uncover their essential roles. With this as a starting point, we can shape projects around your interests and also offer support to help create strong proposals for independent fellowships or studentships. Feel free to contact us to discuss opportunities!

We also cater standard 

<script>
  function calculateLabAge(startDate) {
    const start = new Date(startDate);
    const current = new Date();
    const diffInMonths = (current.getFullYear() - start.getFullYear()) * 12 + current.getMonth() - start.getMonth();
    return diffInMonths;
  }

  document.getElementById("lab-age").innerText = calculateLabAge("2024-09-02"); // Replace with your lab's start date
</script>

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

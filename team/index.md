---
title: Team
nav:
  order: 4
  tooltip: About our team
---

# {% include headicons.html icon="fa-solid fa-users" %}Team

We are a fresh and dynamic malaria lab (just <span id="lab-age"></span> months old!) situated within Glasgow’s vibrant parasitology community. We love constructing plasmids, culturing malaria parasites, and disrupting genes and are always looking for better and more efficient ways to get these done. 
The mutants we generate often lead us down intriguing and unexpected paths of enquiry, pushing us to continuously learn, collaborate and imbibe new techniques and technologies. Omics approaches play a central role in our studies.
We foster a positive and inclusive lab environment, where diversity in skills and perspectives is celebrated and encouraged.

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

## Join us

We have open positions!

In our lab, we use  and routinely identify interesting candidates that could be investigated further to uncover their essential roles. With this as a starting point, we can shape projects around your interests and also offer support to help create strong proposals for independent fellowships or studentships. Feel free to contact us to discuss opportunities!

{% include section.html %}



{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

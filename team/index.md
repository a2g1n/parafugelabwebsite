---
title: Team
nav:
  order: 3
  tooltip: About our team, joining us and our funders
---

# {% include headicons.html icon="fa-solid fa-users" %}Team

We are a fresh and dynamic malaria lab (just <span id="lab-age"></span> months old!) situated within Glasgow’s vibrant parasitology community. We love constructing plasmids, culturing malaria parasites and disrupting genes, and are always looking for better and more efficient ways to get these done. 
The mutants we generate often lead us down intriguing and unexpected paths of enquiry, pushing us to continuously learn, collaborate and imbibe new techniques and technologies.

We foster a lab environment that is positive, inclusive and supportive, where diversity in skills and perspectives are celebrated and encouraged. Learn more about our <a href="../values/index.html">approach to science</a>.

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

At the lab, we routinely identify interesting essential genes that could be investigated further to uncover their important roles in the parasite. With this as a starting point, we can shape projects around your interests and also offer support to help create strong proposals for independent fellowships or studentships. Feel free to contact us to discuss opportunities!

{% include section.html %}

## Our Funders

{% capture content %}

{% include figure.html image="images/ukri-mrc-square-logo.png" link="https://www.ukri.org/opportunity/career-development-award/" caption="MRC Career Development Award (2024-29)" %}
{% include figure.html image="images/UoG_colour.png" link="https://www.gla.ac.uk/research/lkas/lkasfellowships/" caption="Lord Kelvin / Adam Smith Fellowship (2024-29)" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

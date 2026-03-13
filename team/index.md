---
title: Team
redirect_from:
  - /lab-members
  - /alums
  - /mascots
  - /staff
  - /trainees
---

# <i class="fas fa-users"></i>

## Research Group

Our lab is a team focused on improving the reach, accuracy, and speed of computational analysis, specifically as
it relates to genomics (and Biology more broadly).  We are a varied and friendly bunch.  If you're interested in
the work we're doing, please reach out!

{% capture html %}
<!-- {% include team-list.html role="pi" group="current" %} -->
{% include team-list.html role="codirector" group="current" %}
{% include team-list.html role="postdoc" group="current" %}
{% include team-list.html role="phd" group="current" %}
{% include team-list.html role="undergrad" group="current" %}
{% include team-list.html role="programmer" group="current" %}
{% include team-list.html role="mascot" group="current" %}
{% endcapture %}

{% include centerer.html html=html %}

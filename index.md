---
---

# STIF research team from ENSTA

The Structures in Interaction with Fluids (STIF) team from the Institut de Recherche Dupuy de Lôme (IRDL - UMR 6027) is composed of researcher various and complementary backgrounds in the fields of fluid mechanics and mechanical engineering. 

# Our affiliations
{% capture content %}
{%
  include figure.html
  image="images/IRDL-FRE-logo-1.png"
  caption="IRDL website"
  link="https://www.irdl.fr/"
  width="70%"
%}
{%
  include figure.html
  image="images/Logo_ENSTA-2025.svg.png"
  caption="ENSTA website"
  link="https://www.ensta-bretagne.fr/fr"
  width="70%"
%}
{%
  include figure.html
  image="images/ipparis-logo-770x197.png"
  caption="IPP website"
  link="https://www.ip-paris.fr/"
  width="70%"
%}
{% endcapture %}

{%
  include grid.html
  content=content
  style="square"
%}

{% include section.html %}

# Our expertise

## Highlights

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}

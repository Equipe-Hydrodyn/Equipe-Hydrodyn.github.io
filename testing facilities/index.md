---
title: testing facilites
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Testing facilities

The STIF team is lucky to benefit from the support of the MASMECA testing platforme at ENSTA.

A wide range of experiments and tests can performed inhouse. Test benchs, high speed camera, lightings, laser ilumination and post-processing softwares are available and used daily by our researchers and research engineers.

{%
  include section.html
  background="images/back_hydro.png"
  dark=false
  size=full
%}
## Aero-HYdro dynamics applications

{% capture text %}
Our low-speed wind tunnel is primarly designed to preform aero-hydro dynamics eperiments for naval applications. The test section is higly modular and can be addapted to your need (closed or open test section). For qualitative analysis, the full test section can be used to increase the cross section of the testing area.

***Wind tunnel aprticular's:***
 - test section: $1.5m \times 1.5m \times 3m$
 
 - maximu wind speed: $35m/s$

***Measurment apparatus:***
- 6 axis load cell

- LaVision 2D averaged PIV 

- 32 channel pressur scanner

- 7 holes multipurpose Pitot tube

{% endcapture %}

{%
  include feature.html
  image="images/icon.png"
  link=""
  title="Low speed wind tunnel"
  text=text
  flip=false
%}


{% capture text %}
Our low-speed wind tunnel is primarly designed to preform aero-hydro dynamics eperiments for naval applications. The test section is higly modular and can be addapted to your need (closed or open test section). For qualitative analysis, the full test section can be used to increase the cross section of the testing area.

***Choc machine aprticular's:***
 - water tank: $1.5m \times 1.5m \times 3m$
 
 - maximu wind speed: $35m/s$

***Measurment apparatus:***
- 6 axis load cell

- LaVision 2D averaged PIV 

- 32 channel pressur scanner

- 7 holes multipurpose Pitot tube

{% endcapture %}

{%
  include feature.html
  image="images/machine_choc.png"
  link=""
  title="Water entry choc machine"
  text=text
  flip=false
%}

{%
  include section.html
  background=""
  dark=false
  size=full
%}

{%
  include section.html
  background="images/back_pyro.png"
  dark=false
  size=full
%}

## High speed dynamic applications

### Two stage gas gun

{% include list.html component="card" data="projects" filter="!group" style="small" %}

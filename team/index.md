---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team


{% include section.html %}

The current members of the group are:

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: vi"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: undergrad"
%}
{:.center}

{% include section.html background="images/banner.png" dark=true%}

We work closely with these collaborators:

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: collaborator"
%}

{% include section.html %}


{% include section.html %}

Past members of our team are:

 * [Miguel Garcia](https://www.linkedin.com/in/miguelgarciavera/)
 * [Erick Rundo](https://www.linkedin.com/in/erick-rundo-01651458/)
 * [Stephany Vargas](https://www.linkedin.com/in/stephany-vargas/)
 * [Cristina Mantilla Suarez](https://www.linkedin.com/in/cristina-mantilla-suarez-78420998/) - Currently Lederman Fellow at Fermilab.
 * [Daniel Guerrero](https://www.linkedin.com/in/daniel-guerrero-2ba498106/) - Currently  Postdoc at Fermilab.
 * [Pablo Rivadeneira](https://www.linkedin.com/in/pablo-rivadeneira-bracho/)

## Join us

We are always glad to discuss with new students for projects related to High Energy Physics and CERN in general. If you want to discuss it, book a meeting in the link below.

_Siempre estamos gustosos de conversar con nuevos estudiantes sobre proyectos relacionados a Física de Altas Energías y CERN en general. Si quieres discutir algun proyecto, agenda una reunión con nosotros en el siguiente link._

<!-- Calendly inline widget begin -->
<div class="calendly-inline-widget" data-url="https://calendly.com/alefisico/30min" style="min-width:320px;height:630px;"></div>
<script type="text/javascript" src="https://assets.calendly.com/assets/external/widget.js" async></script>
<!-- Calendly inline widget end -->
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/senescyt.jpg"
  link1="https://www.educacionsuperior.gob.ec/"
  tooltip1="Secretaria Nacional de Ciencia y Tecnología - Senescyt"

  image2="images/Escudo_de_la_Escuela_Politécnica_Nacional.png"
  link2="https://www.epn.edu.ec/"
  tooltip2="Escuela Politécnica Nacional"

%}

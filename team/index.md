---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team


{% include section.html %}

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

## Join us

We are always glad to discuss with new students for projects related to High Energy Physics and CERN in general. If you want to discuss it, book a meeting in the link below.

_Siempre estamos gustosos de conversar con nuevos estudiantes sobre proyectos relacionados a Física de Altas Energías y CERN en general. Si quieres discutir algun proyecto, agenda una reunión con nosotros en el siguiente link._

<!-- Calendly badge widget begin -->
<link href="https://assets.calendly.com/assets/external/widget.css" rel="stylesheet">
<script src="https://assets.calendly.com/assets/external/widget.js" type="text/javascript" async></script>
<script type="text/javascript">window.onload = function() { Calendly.initBadgeWidget({ url: 'https://calendly.com/alefisico/30min', text: 'Schedule time with me', color: '#0069ff', textColor: '#ffffff', branding: true }); }</script>
<!-- Calendly badge widget end -->

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

%}

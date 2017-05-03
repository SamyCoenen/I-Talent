+++
# Date this page was created.
date = "2017-04-08"

# Project title.
title = "End User Computing"

# Project summary to display on homepage.
summary = "Seminarie gegeven door OpenLine in PXL op 26/10/2016"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = ""

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Seminaries"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = "My caption :smile:"
[image]
preview = "openline-logo.png"
caption = ""
+++

preker

In de beginjaren van remote desktop hebben Citrix en Windows een discussie gehad omtrent rechten en toen hebben ze besloten om toch samen te werken door Windows als OS te gebruiken en Citrix als applicatie. Het eerste grote voorbeeld was Windows Terminal Server.

Citrix is heel sterk in Remote Desktop omdat ze een eigen protocol hebben dat heel sterk is, namelijk ICA:
- De connectie gaat over TCP maar gebruikt een ICA connectie, deze bevat meerdere virtuele kanalen en elk kanaal zorgt voor een Citrix functie.

Een groot voordeel van Citrix is dat er geen rekening hoeft genomen te worden met systeemvereisten op clients om updates uit te voeren.
Een groot nadeel is dat indien de server offline gaat, er niemand meer kan werken.

Een nieuwe toevoeging is XenDesktop, dit had als voorloper XenApp, dit zorgt ervoor dat elke gebruiker zijn eigen virtuele machine heeft, er is nu ook beperkte ondersteuning voor GNU/Linux besturingsystemen zoals Redhat, SUSE en Centos.

---
layout: match
locale: es
category: match
race_id: 1
title: "Carrera: 1"
date: 2017-05-12
location: "Madrid"
year: 2017
flickr_icon_race_picid: 36902992930
flickr_banner_race_picid: 36463385394
type: pro

players:
  - name: "Joseph Catalan"
    nick: "dronner"
    score: "334"
    team: "Individual"
    best_time: "245.454 secs."
  - name: "Luis Cabrera"
    nick: "onionlord"
    score: "300"
    team: "Individual"
    best_time: "233.454 secs."
  - name: "Ana Kprilovich"
    nick: "kna"
    score: "225"
    team: "Individual"
    best_time: "245 secs."
  - name: "Carlos Camacho"
    nick: "spinner"
    score: "0"
    team: "Individual"
    best_time: "320 secs."

# Main race picture
flickr_picid: 35779582404

# To show tome pictures in the gallery
flickr_galleryid: 72157681090125822

---

Nos encontramos en la carrera número {{ page.race_id }}
de la competición de carreras de drones FormulaD.
Esta carrera se realizará el día {{ page.date }}
y existen {{ page.players | size }} competidores.
Todos ellos deberán llevar a cabo el recorrido acumulando
la mayor cantidad de puntos posibles para poder clasificar para
las siguientes carreras.

Información de la carrera
=========================

La carrera se realizará en {{ page.location }},
todos los resultados serán mostrados en esta página y los
resultados globales del evento estarán disponibles en la
[página de resultados](/{{ site.locale }}/{{ page.date | date: "%Y" }}/results-pro/ "Página de resultados").

Los pilotos de esta carrera son:

{% for player in page.players %}
* {{ player.name }}
{% endfor %}


---
layout: match
locale: es
category: match
race_id: 2
title: "Carrera: 2"
date: 2017-05-12
location: "Madrid"
year: 2017
flickr_icon_race_picid: 36902992930
flickr_banner_race_picid: 36463385394
type: "open"

players:
  - name: "Mario Delgado"
    nick: "mdelg"
    team: "Individual"
    times: [1234.52, 44.6, 235.6, 64.5, 100]
  - name: "Pepe Truen"
    nick: "onionlord"
    team: "Individual"
    times: [90.52, 50.6, 62.6, 63.5, 450]
  - name: "José Noguera"
    nick: "kna"
    team: "Individual"
    times: [90.52, 73.6, 55.6, 534.5, 102]
  - name: "Carolina Berroteran"
    nick: "cbeerr"
    team: "Individual"
    times: [15.52, 80.6, 99.6, 50.5, 545]
  - name: "Francisco Quiroz"
    nick: "fq"
    team: "Individual"
    times: [90.52, 66.6, 100.6, 15.5, 102]
  - name: "Jose Madriz"
    nick: "jam"
    team: "Individual"
    times: [422.52, 80.6, 99.6, 24.5, 2000]

# Main race picture
flickr_picid: 35779582404

# To show tome pictures in the gallery
flickr_galleryid: 72157681090125822

---

Nos encontramos en la carrera OPEN número {{ page.race_id }}
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
[página de resultados](/{{ site.locale }}/{{ page.date | date: "%Y" }}/results-open/ "Página de resultados").

Los pilotos de esta carrera son:

{% for player in page.players %}
* {{ player.name }}
{% endfor %}


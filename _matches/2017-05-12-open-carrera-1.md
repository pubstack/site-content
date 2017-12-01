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
type: "open"

players:
  - name: "Joseph Catalan"
    nick: "dronner"
    team: "Individual"
    times: [122.52, 444.6, 235.6, 534.5, 1000]
  - name: "Luis Cabrera"
    nick: "onionlord"
    team: "Individual"
    times: [90.52, 100.6, 235.6, 534.5, 450]
  - name: "Ana Kprilovich"
    nick: "kna"
    team: "Individual"
    times: [90.52, 106.6, 100.6, 534.5, 102]
  - name: "Carlos Camacho"
    nick: "spinner"
    team: "Individual"
    times: [224.52, 80.6, 99.6, 534.5, 2000]
  - name: "Pedro Autn"
    nick: "paut"
    team: "Individual"
    times: [90.52, 66.6, 100.6, 15.5, 102]
  - name: "Maria Fonseca"
    nick: "mfonse"
    team: "Individual"
    times: [44.52, 80.6, 99.6, 534.5, 2000]

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


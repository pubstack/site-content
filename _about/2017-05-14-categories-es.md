---
locale: es
category: about-categories
title: Categorias
local_stored_specs: true
s3_category_pdf: /assets/specs/multigp-fpv-racing-league-2017-specs.pdf
s4_category_pdf: /assets/specs/multigp-fpv-racing-league-2017-specs.pdf
open_category_pdf: /assets/specs/multigp-fpv-racing-league-2017-open-spec.pdf
---



{:.text-main-1}
#### Tamaño de la aeronave

+ Diámetro máximo de la hélice de 5 pulgadas.
+ Tamaño del marco 330 milímetros máximo.
+ Embarcación multirotor con motores min 4.
+ Batería LiPo 4S máxima, máximo 4,2 voltios por celda.
+ Debe ser capaz de duraciones de carrera de hasta 3 minutos.

{:.text-main-1}
#### Transmisores de video

Se requieren transmisores de video seleccionados para competir en la serie de carreras de drones.

+ Potencia de salida: 25mw - 200mw o conmutable.
+ Canales requeridos: Banda capaz, 40 canales.

Encenderlos en cualquier momento cuando no esté compitiendo resultará en la descalificación inmediata.

Se requiere que todos los corredores proporcionen un VTX de 200
mw adecuado. Tenga en cuenta que los requisitos de VTx pueden
cambiar por evento. Se usarán y determinarán 25mw o 200mw antes del evento.

Todos los pilotos deben ser capaces de entender completamente todas las operaciones
de su Tx, y ser capaces de cambiar los canales y la potencia según lo requerido
por la pista y los oficiales de carrera. En todos los casos que no sean carreras,
los Tx deben estar apagados. Los canales serán preasignados antes de la carrera.
Los corredores deben poder cambiar los canales en su VTX con relativa facilidad
si así lo requiere el director de la carrera.

{:.text-main-1}
#### Antenas RH y LH
Relación axial recomendada: .6

Es muy recomendable traer varios juegos de antenas para mano
derecha e izquierda. También actualice sus antenas a las últimas
iteraciones (relaciones axiales de .60 o mejor) para garantizar
una señal limpia con mayor número de pilotos por curso en varias pistas.

{:.text-main-1}
#### Requisitos de gafas
Los pilotos con gafas podrán conectarse a las estaciones de tierra con
los cables provistos. Si tiene otro tipo de gafas, puede traer su propio adaptador RCA.



{:.text-main-1}
#### Verificaciones de los drones

Las consignas y verificaciones tienen como objetivo mantener a las aeronaves
y los asistentes dentro de unos parámetros de Seguridad mínimos, ya que debido
a la concentración y diversidad de material que nos encontramos, hay que
mantener unos estándares de Seguridad válidos para todos.

Os enumeramos del 1 al 5 las consignas que el equipo técnico de verificaciones
del STAFF llevará a cabo en el momento de la entrada al recinto.

Si no se cumple alguna de las condiciones, el piloto dispondrá de una zona de
boxes y asistencia técnica, donde podrá corregirlas.

Una vez pasadas todas las comprobaciones, la aeronave se marcará con pintauñas
o similar, en un lugar visible, para confirmar que está VERIFICADA y es apta
para volar.

Antes de cada vuelo, se verificará que las aeronaves que van a salir a pista,
llevan la marca de VERIFICACION.

Se recuerda a todos los participantes que queda terminantemente prohibido
conectar cualquier aeronave dentro del recinto CON LAS HELICES PUESTAS.
La Organización deberá preveer un espacio asegurado para que los pilotos puedan
hacer pruebas de vuelo en tercera persona.



1. **Emisor de video** El emisor de video debe quitarse del quad, o en su defecto, asegurar su
desconexión.

2. **Cableado VTX** Comprobar que se llevan los dos cables Mollex conectados y con la
lengueta anulada.

3. **Gafas** El receptor que llevan las gafas, debe quitarse para evitar problemas.

4. **Helices** No se permite llevar las helices puestas cuando se vaya a manipular el
quad.

5. **FailSafe** Comprobación del sistema failsafe del quad efectivo. (emisora o controladora)


















{:.text-main-1}
#### Las clases son importantes por las siguientes razones

{:.text-white}
+ Permiten nivelar el campo de vuelo, de esta manera ningun piloto
tendrá ventajas sobre otros al utilizar equipos mas poderosos.
Esto permite al piloto ganar la carrera, no a su equipación.
+ Las aeronaves pueden ser diseñadas con confianza ya
que serán aceptadas en la competencia.
+ Permitiran determinar que los componentes emisores de radiofrecuencias
serán compatibles y no causarán interferencias.

<div class="nk-tabs">
  <ul class="nav nav-tabs nav-tabs-fill" role="tablist">
    <li class="nav-item">
      <a class="nav-link active" href="#tabs-1-1" role="tab" data-toggle="tab">Clase 3S</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="#tabs-1-2" role="tab" data-toggle="tab">Clase 4S</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="#tabs-1-3" role="tab" data-toggle="tab">Clase abierta</a>
    </li>
  </ul>
<div class="tab-content">
  <div role="tabpanel" class="tab-pane fade show active" id="tabs-1-1">
    <div class="nk-gap"></div>
    <p>
La clase clase 4S engloba drones adecuados tanto para principiantes como para profesionales.
Los pilotos pueden controlar sus aviones sin temor a que sus equipos superen sus habilidades
de vuelo. Sin embargo, todavía ofrece poder realizar
carreras de alta velocidad.
*
</p>
{% if page.local_stored_specs == true %}
{% assign pdf_path = base | append: page.s3_category_pdf %}
{% else %}
{% assign pdf_path = page.s3_category_pdf %}
{% endif %}
    <p>Descargar el brochure:
    <a class="nk-social-twitter" target="_blank" href="{{ pdf_path }}" target="_blank">
      <span class="fa fa-download"></span>
    </a>
    </p>
    <div class="nk-gap"></div>
  </div>
  <div role="tabpanel" class="tab-pane fade" id="tabs-1-2">
    <div class="nk-gap"></div>
<p>
La clase clase 4S engloba drones adecuados a pilotos de carreras FPV avanzados.
Los pilotos deben tener un nivel de habilidad lo suficientemente alto como para
controlar la aeronave de manera apropiada o se sobrecargarán rápidamente y perderán
la precisión necesaria para competir competitivamente.
*
</p>
{% if page.local_stored_specs == true %}
{% assign pdf_path = base | append: page.s4_category_pdf %}
{% else %}
{% assign pdf_path = page.s4_category_pdf %}
{% endif %}
    <p>Descargar el brochure:
    <a class="nk-social-twitter" target="_blank" href="{{ pdf_path }}" target="_blank">
      <span class="fa fa-download"></span>
    </a>
    </p>
    <div class="nk-gap"></div>
  </div>
  <div role="tabpanel" class="tab-pane fade" id="tabs-1-3">
    <div class="nk-gap"></div>
    <p>
La clase abierta está disponible para todos los multirrotores.
Esta clase está diseñada para promover la competencia entre todos
los estilos y configuraciones de aeronaves para ayudar a desarrollar
la innovación en tecnología y diseño.
*
</p>
{% if page.local_stored_specs == true %}
{% assign pdf_path = base | append: page.open_category_pdf %}
{% else %}
{% assign pdf_path = page.open_category_pdf %}
{% endif %}
    <p>Descargar el brochure:
    <a class="nk-social-twitter" target="_blank" href="{{ pdf_path }}" target="_blank">
      <span class="fa fa-download"></span>
    </a>
    </p>
    <div class="nk-gap"></div>
  </div>
</div>
</div>

{:.text-main-1}
#### Especificaciones de las aeronaves

{:.nk-table}
| Clase | Chasis     | Hélices       | Peso       | Batería         | VTX        | Especial   |
| ----- | ---------- | ------------- | ---------- | --------------- | ---------- | ---------- |
| 3S    | 305mm Max  |6” (152mm) Max | 800g Max   | 3 cell Lipo Max | 250mw Max  |            |
| 4S    | 305mm Max  |6” (152mm) Max | 800g Max   | 4 cell Lipo Max | 250mw Max  |            |
| OPEN  | Sin límite | Sin límite    | Sin límite | Sin límite      | Sin límite | 250mw Max. |

<br/>


{:.text-main-1}
#### Comments

{:.text-white}
+ Recuerde, las clases son pautas para proporcionar estándares competitivos
dentro de un día típico de carreras en formula-d.
+ Muchos pilotos preguntarán por qué el límite de potencia del transmisor
de video (VTx) está configurado a 250 mW. Esto es para aumentar la tasa
de éxito de múltiples pilotos que tienen una transmisión de video perfectamente
clara. Si algunos pilotos están transmitiendo a una potencia más alta, la
probabilidad de experimentar problemas de frecuencia aumenta.
+ A medida que se lanza la nueva tecnología, las clases y especificaciones se
actualizarán para incorporar o retener los avances para mantener la competencia
leal como la prioridad número uno.
+ Todas las aeronaves se deben construir con la capacidad de cambiar fácilmente
los canales vTx de manera oportuna y precisa.


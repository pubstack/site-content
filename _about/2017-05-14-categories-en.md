---
locale: en
category: about-categories
title: Categories
local_stored_specs: true
s3_category_pdf: /assets/specs/multigp-fpv-racing-league-2017-specs.pdf
s4_category_pdf: /assets/specs/multigp-fpv-racing-league-2017-specs.pdf
open_category_pdf: /assets/specs/multigp-fpv-racing-league-2017-open-spec.pdf
---

{:.text-main-1}
#### Classes are important for the following reasons

{:.text-white}
+ They level the playing field so one pilot doesn’t have an advantage over another by using more powerful equipment.  This allows the pilot’s skill to win the race, not their equipment.
+ Aircraft builds can be planned with confidence that they will be accepted into competition.
+ To ensure radio equipment is compatible with fellow pilot’s equipment as to not cause interference.

<div class="nk-tabs">
  <ul class="nav nav-tabs nav-tabs-fill" role="tablist">
    <li class="nav-item">
      <a class="nav-link active" href="#tabs-1-1" role="tab" data-toggle="tab">3S Class</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="#tabs-1-2" role="tab" data-toggle="tab">4S Class</a>
    </li>
    <li class="nav-item">
      <a class="nav-link" href="#tabs-1-3" role="tab" data-toggle="tab">Open Class</a>
    </li>
  </ul>
<div class="tab-content">
  <div role="tabpanel" class="tab-pane fade show active" id="tabs-1-1">
    <div class="nk-gap"></div>
    <p>The 3S Class produces a multirotor well suited for beginners and professionals alike.  Pilots are able to control their aircraft without fear of their equipment over-powering their flight skills. However, it still delivers the high-speed, adrenaline pumping racing they demand. *</p>
{% if page.local_stored_specs == true %}
{% assign pdf_path = base | append: page.s3_category_pdf %}
{% else %}
{% assign pdf_path = page.s3_category_pdf %}
{% endif %}
    <p>Download brochure specs:
    <a class="nk-social-twitter" target="_blank" href="{{ pdf_path }}" target="_blank">
      <span class="fa fa-download"></span>
    </a>
    </p>
    <div class="nk-gap"></div>
  </div>
  <div role="tabpanel" class="tab-pane fade" id="tabs-1-2">
    <div class="nk-gap"></div>
    <p>The 4S Class produces a multirotor tailored to the advanced FPV racing pilot.  Pilots must have a skill level high enough to control the aircraft appropriately or will quickly become over powered and lose the precision needed to race competitively. *</p>
{% if page.local_stored_specs == true %}
{% assign pdf_path = base | append: page.s4_category_pdf %}
{% else %}
{% assign pdf_path = page.s4_category_pdf %}
{% endif %}
    <p>Download brochure specs:
    <a class="nk-social-twitter" target="_blank" href="{{ pdf_path }}" target="_blank">
      <span class="fa fa-download"></span>
    </a>
    </p>
    <div class="nk-gap"></div>
  </div>
  <div role="tabpanel" class="tab-pane fade" id="tabs-1-3">
    <div class="nk-gap"></div>
    <p>The Open Class is available to all multirotors.  This class is designed to promote competition between all styles and configurations of aircraft to help evolve innovation in technology and design. *</p>
{% if page.local_stored_specs == true %}
{% assign pdf_path = base | append: page.open_category_pdf %}
{% else %}
{% assign pdf_path = page.open_category_pdf %}
{% endif %}
    <p>Download brochure specs:
    <a class="nk-social-twitter" target="_blank" href="{{ pdf_path }}" target="_blank">
      <span class="fa fa-download"></span>
    </a>
    </p>
    <div class="nk-gap"></div>
  </div>
</div>
</div>

{:.text-main-1}
#### Aircraft Specifications

{:.nk-table}
| Class | Frame     | Prop          | Weight   | Battery         | VTX      | Special |
| ----- | --------- | ------------- | -------- | --------------- | -------- | ------- |
| 3S    | 305mm Max |6” (152mm) Max | 800g Max | 3 cell Lipo Max | 250mw Max|         |
| 4S    | 305mm Max |6” (152mm) Max | 800g Max | 4 cell Lipo Max | 250mw Max|         |
| OPEN  | No Limit  |No Limit       | No Limit | No Limit        | 250mw Max|         |

<br/>


{:.text-main-1}
#### Gate Specifications

{:.nk-table}
| Class | Gate Opening                     | Material           |
| ----- | -------------------------------- | ------------------ |
| 3S    | 25 sq ft (5’x5’ - 1.52m x 1.52m) | PVC and Vinyl Mesh |
| 4S    | 25 sq ft (5’x5’ - 1.52m x 1.52m) | PVC and Vinyl Mesh |
| OPEN  | 25 sq ft (5’x5’ - 1.52m x 1.52m) | PVC and Vinyl Mesh |

<br/>

{:.text-main-1}
#### Comments

{:.text-white}
+ Remember, classes are guidelines to provide competitive standards within a typical MultiGP race day.  Chapters can choose to define and run their own classes if they wish by definining them during event planning.
+ Many pilots will ask why the power limit of the Video Transmitter (VTx) is limited to 250mW.  This is to increase the success rate of multiple pilots having perfectly clear video transmission.  If some pilots are transmitting at a higher power, the chance of experiencing frequency issues increases.
+ As new technology is released, classes and specs will be updated to either incorporate or withhold the advancements to maintain fair competition as the number one priority.
+ All aircraft must be built with the ability to easily change vTx channels in a timely and accurate manner.



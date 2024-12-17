---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

- Diana Vieira Fernandes, Nicolas Christin, Soummya Kar, [*Peer-to-Peer (P2P) Electricity Markets for Low Voltage Networks*](https://ieeexplore.ieee.org/abstract/document/10738057). 2024 IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm), Oslo, Norway, 2024, pp. 485-491, doi: 10.1109/SmartGridComm60555.2024.10738057.

- Silva, C.S.; Fernandes, D.V.; Gomes, R.; Costa, F.P.; Pinto, L.; Scuri, S.; Brito, A.; Nunes, B.; Silva, S.P. [CLIMAEXTREMO: A New Risk Indicator for the Health Risk to Building Occupants during Extreme Weather Events in Portugal](https://doi.org/10.3390/su16125171). Sustainability 2024, 16, 5171. https://doi.org/10.3390/su16125171

- Diana Neves, Patrícia Baptista, Ricardo Gomes, Sónia Cunha, Mexitli Sandoval-Reyes, Diana Vieira Fernandes, Catarina Rolim, Carlos A Silva, [*MetaExplorer: Collaborative development of urban metabolism platform for decision making support*](https://doi.org/10.1016/j.esr.2023.101041). *Energy Strategy Reviews*, 45, 101041, 2023.

- Fernandes, D. V., & Silva, C. S. (2022). [*Open Energy Data—A regulatory framework proposal under the Portuguese electric system context*](https://doi.org/10.1016/j.enpol.2022.113240). *Energy Policy*, 170, 113240.
  
- Vieira Fernandes, Diana (December 2018) [“Power purchase agreements -  energy contracting under Private Law”](https://run.unl.pt/handle/10362/56406) (master's thesis, Universidade Nova de Lisboa, Portugal). Available at: https://run.unl.pt/handle/10362/56406 


{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

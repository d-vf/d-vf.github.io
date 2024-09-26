- Diana Vieira Fernandes, Nicolas Christin, Soummya Kar, [*Peer-to-Peer (P2P) Electricity Markets for Low Voltage Networks*](https://doi.org/10.48550/arXiv.2407.21403). To appear in *IEEE SmartGridComm'24 - 2024 IEEE International Conference on Communications, Control, and Computing Technologies for Smart Grids (SmartGridComm)*.

- Silva, C.S.; Fernandes, D.V.; Gomes, R.; Costa, F.P.; Pinto, L.; Scuri, S.; Brito, A.; Nunes, B.; Silva, S.P. CLIMAEXTREMO: A New Risk Indicator for the Health Risk to Building Occupants during Extreme Weather Events in Portugal. Sustainability 2024, 16, 5171. https://doi.org/10.3390/su16125171

- Diana Neves, Patrícia Baptista, Ricardo Gomes, Sónia Cunha, Mexitli Sandoval-Reyes, Diana Vieira Fernandes, Catarina Rolim, Carlos A Silva, [*MetaExplorer: Collaborative development of urban metabolism platform for decision making support*](https://doi.org/10.1016/j.esr.2023.101041). *Energy Strategy Reviews*, 45, 101041, 2023.

- Fernandes, D. V., & Silva, C. S. (2022). [*Open Energy Data—A regulatory framework proposal under the Portuguese electric system context*](https://doi.org/10.1016/j.enpol.2022.113240). *Energy Policy*, 170, 113240.

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

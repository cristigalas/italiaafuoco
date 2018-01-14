---
layout: page
title: Link Utili
permalink: /link_utili/
---

{: .table .table-striped #links}
Nome            |Link
:---------------|:-----------------------
{% for member in site.data.links %} {{member.Nome}} | [Link]({{member.Link}})
{% endfor %}

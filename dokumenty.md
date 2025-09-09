---
layout: page
title: Dokumenty
---

Ke stažení zde jsou dostupné:

### Stanovy spolku
  - [webová verze](/stanovy)
  - [verze ve formátu PDF](/files/CNA_stanovy_v2.pdf)

## Výroční zprávy

<table class="table table-striped">
    <thead>
        <tr>
        <th>Datum schůze</th>
        <th>Soubor</th>
        <th>Zapsal(a)</th>
        </tr>
    </thead>
    <tbody>
        {% for f in site.data.zapisy %}
        <tr>
        <td>{{ f.datum }}</td>
        <td><a href="/docs/{{ f.soubor }}"><i class="fas fa-file-pdf"></i> {{ f.soubor }}</a></td>
        <td>{{ f.zapsal }}</td>
        </tr>
        {% else %}
        <tr>
            <td colspan="3">Žádné výroční zprávy zatím nejsou k dispozici, spolek byl založen v roce 2025.</td>
        </tr>
        {% endfor %}
    </tbody>
</table>

## Zápisy ze zasedání Komise

Zápisy ze zasedání komise jsou k dispozici pouze členům asociace

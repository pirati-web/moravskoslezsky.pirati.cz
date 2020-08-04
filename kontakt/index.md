---
layout: contacts
description: Pirátská strana v Moravskoslezském kraji je otevřená a ráda přivítá dobrovolníky a odpoví na dotazy kritiků.
keywords: kontakt, adresa, telefon, mail, facebook, kde najdu, kde jsou
# Pokud nechcete, aby se zobrazovalo kontaktní místo, můžete odkomentovat následující řádek:
# noresidence: yes
contentSize: even
contactPersons:
  - id: lukas.cernohorsky
    position: Poslanec
  - id: ondrej.polanecky
    position: Poslanec    
  - id: jiri.demel
    position: Předseda krajského sdružení
  - id: zuzana.klusova
    position: Kontakt pro novináře
  - id: jakub.dedek
    position: Kontakt pro dobrovolníky
  - id: sarka.vaclavikova
    position: Kontakt pro krajské volby 2020
---

<div class="o-section-header o-section-header--indented">
  <h1 class="t-h2-alt">Zapojte se</h1>
</div>

Zajímá vás co piráti dělají? <a href="https://nalodeni.pirati.cz/">Naloďte se</a> a buďte v obraze, nebo kontaktujte našeho koordinátora (viz kontakt pro dobrovolníky).

Finanční dary můžete posílat na <a href="https://dary.pirati.cz">zde</a>.
Pokud chcete darovat přimo našemu kraji, poraďte se prosím s koordinátorem.


## Poslanci

{% assign person = site.people | where_exp: "item","item.uid contains 'lukas.cernohorsky'" | first  %}
{% include people/profile-badge.html item=person imgSize='big' imgStyle='round' class='c-profile-badge--centered' %}
<br>
{% assign person = site.people | where_exp: "item","item.uid contains 'ondrej.polansky'" | first  %}
{% include people/profile-badge.html item=person imgSize='big' imgStyle='round' class='c-profile-badge--centered' %}
</div>


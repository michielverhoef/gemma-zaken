---
title: "Gegevensmodel Besluiten-API"
date: '27-02-2019'
---

# GEGEVENSMODEL BESLUITEN API

voor de functionele beschrijving van de API <a href="https://github.com/VNG-Realisatie/gemma-zaken/blob/Remkodehaas-patch-3/docs/_content/overige/functioneel/besluiten_api.md">klik hier</a>


In de volgende diagram staan de resources van de Besluiten-API:

<table>
<tbody>
<tr class="odd">
<td><strong>Diagram Besluiten-API</strong></td>
</tr>
<tr class="even">
<td><img src="https://github.com/VNG-Realisatie/gemma-zaken/blob/Remkodehaas-patch-3/docs/_content/overige/functioneel/assets/gegevensmodel_besluit_compact.png" width="706" height="371" border="0" " /></td>
</tr>
<tr class="odd">
<td><strong>Diagram ZGW-API's</strong></td>
<tr class="even">
<td><img src="https://github.com/VNG-Realisatie/gemma-zaken/blob/Remkodehaas-patch-3/docs/_content/overige/functioneel/assets/gegevensmodel_zgw_overview_tbv_Besluit.png" width="1067" height="980" border="0" " /></td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr class="odd">
<td><strong>Resource</strong></td>
<td><strong>Definitie</strong></td>
</tr>
<tr class="even">
<td>Besluiten</td>
<td>Een na overweging of beraadslaging vastgestelde beslissing voor een individueel of concreet geval.</td>
</tr>
<tr class="odd">
<td>Besluitinformatieobjecten</td>
<td>Informatie-object = Geheel van gegevens met een eigen identiteit ongeacht zijn vorm, met de bijbehorende metadata ontvangen of opgemaakt door een natuurlijke en/of rechtspersoon bij de uitvoering van taken. </br>
Besluitinformatieobject: een Besluit kan vastgelegd zijn in 1 of meerdere informatieobjecten 
</td>
</tr>
<tr class="even">
<td>Besluittype</td>
<td>Generieke aanduiding van de aard van een besluit</td>
</tr>
<tr class="odd">
<td>Zaken</td>
<td>Een samenhangende hoeveelheid werk met een welgedefinieerde aanleiding en een welgedefinieerd eindresultaat, waarvan kwaliteit en doorlooptijd bewaakt moeten worden.</td>
</tr>

</tbody>
</table>


## Toelichting
Bij ZGW leidt een zaak in veel gevallen tot één of meer BESLUITen. Kenmerken van groepen vergelijkbare BESLUITen leggen we vast met het BESLUITTYPE uit de ZAAKTYPEN-API. Een besluit wordt veelal schriftelijk vastgelegd maar dit is niet noodzakelijk. Vandaar de optionele relatie naar INFORMATIEOBJECT (= Besluitinformatieobjecten).

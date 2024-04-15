# Verwerking waarden

Zelfs als een ontvangend systeem bepaalde waarden uit een waardelijst niet kent, moeten die in veel gevallen wel door
dat ontvangende systeem worden geaccepteerd en verwerkt.

## TE005.001: Ontvangen waarden in een 'extensible' waardelijst die binnen het codestelsel van de waardelijst vallen MOETEN door systemen worden verwerkt als geldige waarden

Zelfs als een systeem een bepaalde waarde/code niet kent, dient deze te worden verwerkt en correct te worden getoond
door dat systeem indien de waardelijst-binding 'extensibe' is.

| Toepasselijke rollen | Eisniveau |
|----------------------|-----------|
| Systeemontwikkelaar  | MUST      |

## TE005.002: Ontvangen waarden in een 'dynamische' waardelijst die binnen de meest recente versie van het onderliggende codestelsel vallen MOETEN door systemen worden verwerkt als geldige waarden

Wanneer een systeem een waarde/code ontvangt die valt binnen de (SNOMED CT) referentieset of terminologie-query op de
meest recente versie van de achterliggende terminologie, dan moet het systeem deze waarde/code correct verwerken en
tonen, zelfs al gebruikt het systeem zelf een oudere versie van de terminologie waarin de waarde/code niet voorkomt.

| Toepasselijke rollen | Eisniveau |
|----------------------|-----------|
| Systeemontwikkelaar  | MUST      |
# Binding waardelijst

Waardelijsten worden op verschillende manieren aan een zib-element gekoppeld of 'gebonden'. Als de binding van een
waardelijst 'required' is, mogen uitsluitend waarden uit de gedefinieerde waardelijst worden gebruikt. Als de waarde
'extensible' is, mogen ook andere  waarden uit hetzelfde codesysteem (terminologie) als waarop de waardelijst is
gebaseerd worden gebruikt.

## TE001.001: De binding van een waardelijst ZOU 'extensible' moeten zijn

Zorgverleners moeten altijd de mogelijkheid hebben om andere waarden vast te leggen dan de waarden in de waardelijst. De
waardelijst-binding 'extensible' maakt het mogelijk om naast de waarden in de waardelijst ook andere termen uit de
achterliggende terminologie te selecteren. De waardelijst-binding 'extensible' is ook beter bestand tegen situaties
waarin een systeem een code ontvangt van een ander systeem, dat niet in de waardelijst zelf is opgenomen. Dit komt
bijvoorbeeld voor in het geval van versieverschillen bij referentiessets. De waarden in de waardelijst kunnen als
voorkeuswaarden worden gezien.

| Toepasselijke rollen | Eisniveau |
|----------------------|-----------|
| Zib-ontwerper        | SHOULD    |

## TE001.002: ALS aanvullende termen onmiskenbaar in geen enkele zorg- of gezondheidscontext toepasbaar zijn, DAN: MAG de binding van een waardelijst 'required' zijn

Soms is absoluut zeker dat een vaste set van waarden in alle gevallen volstaat (usecase-onafhankelijk). Alleen in die
gevallen mag de waardelijst-binding 'required' worden gebruikt.

| Toepasselijke rollen | Eisniveau |
|----------------------|-----------|
| Zib-ontwerper        | MAY       |

## TE001.003: ALS de waardelijst een gehele codelijst/terminologie bevat EN dynamisch is, DAN: MAG de binding van een waardelijst 'required' zijn

Wanneer een waardelijst een gehele terminologie bevat en dynamisch is, dan heeft de waardelijst-binding 'extensible'
geen effect. Er zijn immers niet nog meer termen in de achterliggende terminologie die gebruikt kunnen worden.

| Toepasselijke rollen | Eisniveau |
|----------------------|-----------|
| Zib-ontwerper        | MAY       |

## TE001.004: ALS de binding van een waardelijst 'required' is, DAN: MOET een waarde 'OTH' worden toegevoegd aan de waardelijst

Zorgverleners moeten altijd de mogelijkheid hebben om andere waarden vast te leggen dan de waarden in de waardelijst.
Overweeg een waardelijst-binding van het type 'extensible'.

| Toepasselijke rollen | Eisniveau |
|----------------------|-----------|
| Zib-ontwerper        | MUST      |

## TE001.005: Systemen MOGEN de waarden van waardelijsten met een binding 'extensible' aan de eindgebruiker tonen als voorkeurstermen/startlijst

De waarden in een 'extensible' waardelijst zijn bedoeld als voorkeurskeuzes. Een user interface ontwerp mag hierop
aansluiten door een voorkeursset te tonen, naast een mogelijkheid om in de uitgebreide set (de achterliggende
terminologie) te selecteren/zoeken.

| Toepasselijke rollen | Eisniveau |
|----------------------|-----------|
| Systeemontwikkelaar  | MAY       |

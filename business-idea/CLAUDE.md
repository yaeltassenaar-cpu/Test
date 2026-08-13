# Schrijfstijl en regels — business-idea documenten

Deze regels gelden voor **alle** bestanden onder `business-idea/`, nu en bij
elke toekomstige wijziging. Bij twijfel: consistentie met de bestaande
bestanden in deze map heeft voorrang boven een nieuwe interpretatie.

## Taal
Alle documenten zijn in het **Nederlands** — inhoud, koppen en bestandsnamen.

## Toon
Formeel ondernemingsplan-register, zoals een bank of investeerder verwacht:
derde persoon, geen "ik"/"we". Gebruik **"het bedrijf"**, **"de onderneming"**
of **"de ondernemer"** als onderwerp — ook in de sectie over de ondernemer
zelf (bv. "De ondernemer wil dit bedrijf starten omdat…" in plaats van
"Ik wil…").

## Bronvermelding
Elke onderbouwde bewering of statistiek krijgt een bronvermelding. Plaats
bronnen als een `*Bronnen: ...*`-regel onderaan de sectie of het bestand
waar de bewering staat. Aannames/inschattingen zonder externe bron worden
expliciet als "indicatie" of "aanname" gelabeld — nooit als vaststaand feit
gepresenteerd.

## Cijfers en valuta
- Bedragen in euro, Nederlandse notatie met punt als duizendtal-scheiding,
  geen decimalen tenzij nodig: `€ 25.000`.
- Bereiken: `€ 25.000 – € 50.000` (en-dash met spaties).
- Percentages zonder spatie: `21%`.
- Andere valuta (bv. Britse pond bij een UK-referentie) alleen gebruiken bij
  een expliciete internationale vergelijking, en dan toelichten dat het om
  een niet-Nederlandse referentie gaat.

## Opmaak
- Markdown `##`/`###` voor secties, geen `#` (die is voorbehouden aan de
  bestandstitel).
- Tabellen voor financiële en vergelijkende data.
- Checklists (`- [ ]`) voor actiepunten en openstaande beslissingen.
- Geen emoji's.

## Onderhoud
Wijzig je een bestand in `business-idea/` — handmatig of via Claude — volg
dan deze regels. Nieuwe bestanden in deze map beginnen in het Nederlands, in
dezelfde toon en opmaak.

## Consistentiecontrole bij elke wijziging
Bij elke aanpassing aan een bestand in `business-idea/` (nieuw, gewijzigd of
verwijderd) geldt de volgende procedure, zonder uitzondering:

1. **Controleer het effect op andere bestanden**: ga na welke andere
   bestanden in `business-idea/` verwijzen naar, voortbouwen op, of
   cijfers/keuzes delen met het gewijzigde onderdeel (bv. een gewijzigde
   doelgroep, prijs, aantal abonnees, rechtsvorm, of tijdlijn).
2. **Signaleer tegenstrijdigheden expliciet**: benoem concreet welk
   bestand, welke passage, en welke tegenstrijdigheid ontstaat — niet
   alleen dat er "mogelijk impact" is.
3. **Vraag eerst toestemming**: wijzig géén ander bestand automatisch mee.
   Leg de gevonden tegenstrijdigheden en de voorgestelde aanpassing voor
   aan de gebruiker en wacht op akkoord voordat de andere bestanden worden
   aangepast.
4. Pas na toestemming de aangewezen bestanden aan, en vermeld in de
   commitboodschap welke bestanden zijn meegewijzigd en waarom.

Deze procedure geldt voor elke toekomstige wijziging aan documenten in deze
map, ongeacht wie of wat de wijziging aanbrengt.

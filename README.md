# Hackathon-PowerApps

Voor een bedrijf dat gereedschap verkoopt in een winkel mag je een aantal apps ontwikkelen die de medewerkers kunnen gebruiken om aankopen van klanten in te registeren in orders met bijbehorende orderregels. Ook de klanten zelf dienen in een losse app geregistreerd te kunnen worden. 

Er hoeft nog geen validatie te zijn of de producten op voorraad zijn of dat bepaalde leveringen al dan niet voltooid zijn.

In de bestellingapp dient de medewerker te kunnen registeren:
- ordernummer (autonummering, primaire kolom)
- besteldatum (date)
- Klant
- leverdatum (date)

Maak het mogelijk via de Dataverse dat de leverdatum nooit eerder kan zijn dan de besteldatum.

Ook dient via deze bestellingapp doorgeklikt te kunnen worden naar een ander scherm wat van de betreffende order, de orderregels toont.

Van de orderregels dient te worden geregistreerd:
- Order
- product
- aantal (whole number)

In de klantapp dient de medewerker te kunnen registeren:
- naam (samen) (text)
- straatnaam (text)
- huisnummer (text)
- postcode (text)
- woonplaats (text)

In de productenapp dient de medewerker te kunnen registreren:
- naam (text)
- omschrijving (1000 tekens)
- inkoopprijs (currency)
- verkoopprijs (currency)
- foto (image)
- voorraad (nummer)

Tot slot is het de bedoeling dat je op afroep een e-mail ontvangt met daarin een overzicht van de bestelde producten per klant van de afgelopen maand. Het is de bedoeling dat je hiervoor een Power Automate Flow gebruikt.

# Hackathon-PowerApps

Voor een bedrijf dat gereedschap verkoopt in een winkel mag je een aantal apps ontwikkelen die de medewerkers kunnen gebruiken om aankopen van klanten in te registeren in orders met bijbehorende orderregels. Ook de klanten zelf dienen in een losse app geregistreerd te kunnen worden. 

Er hoeft nog geen validatie te zijn of de producten op voorraad zijn of dat bepaalde leveringen al dan niet voltooid zijn.


## Details opdracht
In de bestellingapp dient de medewerker te kunnen registeren:
- besteldatum 
- Klant
- leverdatum 

Ook dient in de database aanwezig te zijn:
- ordernummer 

Maak het mogelijk via de Dataverse dat de leverdatum nooit eerder kan zijn dan de besteldatum.

Ook dient via de bestellingapp doorgeklikt te kunnen worden naar een ander scherm wat van de betreffende order, de orderregels toont.

Van de orderregels dient te worden geregistreerd:
- Order
- product
- aantal

In de klantapp dient de medewerker te kunnen registeren:
- naam (samen)
- straatnaam
- huisnummer
- postcode
- woonplaats

In de productenapp dient de medewerker te kunnen registreren:
- naam 
- omschrijving 
- inkoopprijs 
- verkoopprijs
- foto
- voorraad 

Tot slot is het de bedoeling dat de klant op zijn of haar e-mail adres een bevestiging van de bestelling ontvangt. Hiervoor dien je een Power Automate Flow te gebruiken.


## Documentatie
[https://docs.microsoft.com/en-us/powerapps/]
[https://docs.microsoft.com/en-us/power-automate/]


## Handige functies
- Filter(dataset, conditie);
- Search(dataset, conditie);
- First(dataset);
- Defaults(dataset);
- Patch(dataset, {});
- Update(dataset, rij, {});
- Set(var, {});
- UpdateContext(var, {});
- Refresh(dataset)
- Collect(var, waarde);
- ClearCollect(var);
- Navigate(scherm);

# Prometne nesreče v Sloveniji

## Člani skupine
Matej Vatovec 63190310

## Uvod
Za seminarsko nalogo bom analiziral podatke o prometnih nesrečah v Sloveniji za leti 2019 in 2020. Podatke sem pridobil
iz spletne strani policija.si (https://www.policija.si/o-slovenski-policiji/statistika/prometna-varnost). Isti podatki so tudi dostopni
na spletni strani podatki.gov.si (https://podatki.gov.si/dataset/mnzpprometne-nesrece-od-leta-2009-dalje), vendar manjkajo podatki za leto 2020.


## Cilji
  * Analiza in vizualizacija podatkov.
  * Odgovoriti na vnaprej postavljena vprašanja in na morebitna vprašanja, ki se pojavijo ob reševanju problema.
  * Napovedovanje klasifikacije nesreče.
  
  
  ### Vprašanja
  * Kateri vozniki povzročajo največ nesreč?
  * Kakšne okoliščine povzročajo največ nesreč?
  * Ali količina alkohola v krvi voznika, vpliva na težavnost poškodbe?
  

## Opis podatkov
Podatki so podani v 2 datotekah tipa csv. Datoteki obsegata ena 33896 in druga 26074 vrstic, kjer vsaka vrstica predstavlja eno nesrečo. Atributi:

* Številka za štetje in ločevanje posamezne prometne nesreče,
* klasifikacija nesreče glede na posledice (Izračuna se avtomatično glede na najhujšo posledico pri udeležencih v prometni nesreči),
* upravna enota, na območju katere se je zgodila prometna nesreča,
* datum nesreče (format: dd.mm.llll), 
* ura nesreče (format: hh) ,
* indikator ali se je nesreča zgodila v naselju (D) ali izven (N),
* lokacija nesreče,
* vrsta ceste ali naselja na kateri je prišlo do nesreče,
* oznaka ceste ali šifra naselja kjer je prišlo do nesreče,
* tekst ceste ali naselja, kjer je prišlo do nesreče,
* oznaka odseka ceste ali šifra ulice, kjer je prišlo do nesreče,
* tekst odseka ali ulice, kjer je prišlo do nesreče,
* točna stacionaža ali hišna številka, kjer je prišlo do nesreče,
* opis prizorišča nesreče,
* glavni vzrok nesreče,
* tip nesreče,
* vremenske okoliščine v času nesreče,
* stanje prometa v času nesreče,
* stanje vozišča v času nesreče,
* stanje površine vozišča v času nesreče,
* Geo Koordinata X (Gauß-Krüger-jev koordinatni sistem),
* Geo Koordinata Y (Gauß-Krüger-jev koordinatni sistem),
* številka za štetje in ločevanje oseb, udeleženih v prometnih nesrečah,
* kot kaj nastopa oseba v prometni nesreči,
* starost osebe (LL),
* spol,
* upravna enota stalnega prebivališča,
* državljanstvo osebe,
* poškodba osebe,
* vrsta udeleženca v prometu,
* ali je oseba uporabljala varnostni pas ali čelado (polje se interpretira v odvisnosti od vrste udeleženca) (Da/Ne),
* vozniški staž osebe za kategorijo, ki jo potrebuje glede na vrsto udeleženca v prometu (LL),
* vozniški staž osebe za kategorijo, ki jo potrebuje glede na vrsto udeleženca v prometu (MM),
* vrednost alkotesta za osebo, če je bil opravljen (n.nn v enoti mg alkohola/liter izdihanega zraka (mg/l)),
* vrednost strokovnega pregleda za osebo, če je bil odrejen in so rezultati že znani (n.nn v enoti g alkohola/kg krvi (g/kg)).

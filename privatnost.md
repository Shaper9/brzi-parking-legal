---
title: Politika privatnosti
permalink: /privatnost/
lang: sr-Latn
---

# Politika privatnosti – Brzi Parking

Poslednja izmena: 29. oktobar 2026.

Brzi Parking („mi”) je besplatna aplikacija za plaćanje parkinga SMS porukom u Novom Sadu i Beogradu. Kontakt: [brziparking@gmail.com](mailto:brziparking@gmail.com).

## Ukratko

- Nema naloga, registracije ni prijave.
- Tvoje tablice, istorija parkiranja i lokacija ostaju **samo na tvom telefonu**. Mi ih ne dobijamo, ne čuvamo i ne prodajemo.
- Aplikacija nema reklame, analitiku, praćenje ni izveštaje o greškama.
- Tablica napušta telefon jedino u SMS poruci kojom plaćaš parking.
- Sa interneta aplikacija preuzima samo delove mape i najnovije javne podatke o zonama. Ti zahtevi ne nose lične podatke, osim tvoje IP adrese, kao svaki zahtev na internetu.
- Napojnice su dobrovoljne i idu samo preko Google Playa ili App Storea. Podatke tvoje kartice ili računa nikad ne vidimo.

## Šta aplikacija čuva na tvom telefonu

Ovi podaci se čuvaju u lokalnoj bazi aplikacije i ne šalju se nama ni bilo kome drugom:

| Podatak                                                                                                                             | Zašto                                                               |
| ----------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------- |
| Registarske oznake i nazivi tvojih vozila                                                                                           | Da bi SMS za plaćanje sadržao tačnu tablicu                         |
| Istorija parkiranja: tablica, grad, zona, SMS broj, tekst poruke, vreme, a ako je lokacija bila uključena i mesto na kom je plaćeno | Odbrojavanje, podsetnici, produženje i lista aktivnih parkiranja    |
| Zapamćena mesta: lokacija, zona i vreme svakog plaćanja ili ručnog izbora zone                                                      | Da ti na istom mestu sledeći put odmah predloži istu zonu           |
| Grad u kom si sada ili poslednji put                                                                                                | Da se aplikacija otvori sa zonama tog grada                         |
| Podaci o zonama preuzeti za tvoj grad                                                                                               | Da imaš najnovije zone bez ažuriranja aplikacije                    |
| Podešavanja (jezik, tema, podsetnici)                                                                                               | Da aplikacija radi onako kako želiš                                 |
| Napomena da kupovina napojnice još nije završena (samo dok je tako)                                                                 | Da aplikacija može kasnije da je završi i da je prodavnica ne vrati |

**Kopija telefona (backup):** ako na telefonu imaš uključenu automatsku rezervnu kopiju (Google rezervna kopija na Androidu, iCloud na iPhoneu), sistem može da uključi i podatke ove aplikacije. Tu kopiju čuvaju Google ili Apple prema svojim pravilima i ona je vezana za tvoj nalog; mi joj nemamo pristup.

## Lokacija

- Aplikacija koristi lokaciju **samo dok je otvorena**, da bi pronašla grad i zonu u kojoj si. Nema praćenja u pozadini.
- Lokacija se obrađuje na telefonu i ne šalje se nama.
- Dozvolu možeš da ne daš ili da je povučeš u podešavanjima telefona. Tada zonu biraš ručno.

## SMS za plaćanje

Kad platiš, aplikacija otvara tvoju aplikaciju za poruke sa pripremljenim SMS-om na broj zone (na primer 8212 u Novom Sadu ili 9111 u Beogradu), a tekst poruke je tvoja registarska oznaka. Poruku šalješ ti, sa svog broja. Nju zatim obrađuju tvoj mobilni operater i JKP „Parking servis” Novi Sad ili JKP „Parking servis” Beograd, zavisno od grada, prema svojim pravilima o privatnosti. Mi tu poruku ne vidimo.

## Ažuriranje podataka o zonama

Da bi nove ili izmenjene zone stigle do tebe bez ažuriranja aplikacije, aplikacija najviše jednom u 8 sati, i samo dok je otvorena, proverava da li postoje noviji podaci o zonama. Za grad u kom si preuzima malu datoteku sa servisa [GitHub Pages](https://pages.github.com/) (`shaper9.github.io`), proverava njen digitalni potpis i koristi je od sledećeg pokretanja.

- Zahtev ne sadrži lične podatke, tablice ni lokaciju. GitHub vidi tvoju IP adresu i datoteku kog grada tražiš, pa može da zna u kom si od podržanih gradova, ali ne i gde u njemu. GitHub iz bezbednosnih razloga beleži IP adrese posetilaca, prema [GitHubovoj izjavi o privatnosti](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).
- Bez interneta aplikacija nastavlja da koristi zone koje već ima.

## Mapa

Da bi prikazala mapu, aplikacija preuzima delove mape sa interneta:

- **Android:** od servisa [OpenFreeMap](https://openfreemap.org/privacy/), koji koristi Cloudflare. Server vidi tvoju IP adresu i koji deo grada se prikazuje, ali ne i tvoju tačnu lokaciju. Prema svojoj politici, OpenFreeMap čuva zapise servera najviše 7 dana (do 30 dana kod bezbednosnih incidenata) i ne koristi kolačiće.
- **iPhone:** Apple Mape, prema [Appleovoj politici privatnosti](https://www.apple.com/legal/privacy/).

Bez interneta mapa se ne učitava, a sve ostalo radi.

## Podsetnici

Podsetnike pre isteka parkiranja zakazuje sam telefon. Nema servera za obaveštenja i ništa se ne šalje van telefona.

## Napojnice (dobrovoljno)

Aplikacija je besplatna i ništa u njoj nije zaključano. Ako želiš, u Podešavanjima možeš da ostaviš napojnicu. Napojnica ne otključava ništa.

- Napojnica je kupovina u **Google Playu** (Android) ili **App Storeu** (iPhone). Plaćanje, podatke za plaćanje i eventualni povraćaj novca obrađuju Google ili Apple, prema svojim politikama privatnosti ([Google](https://policies.google.com/privacy), [Apple](https://www.apple.com/legal/privacy/)).
- Aplikacija se povezuje sa prodavnicom samo dok je ekran za napojnicu otvoren, da bi prikazala cene i obavila kupovinu.
- Podatke tvoje kartice ili računa nikad ne dobijamo. Prodaju vidimo samo u izveštajima koje Google ili Apple daju prodavcima (na primer koja napojnica, cena, datum i zemlja).
- Aplikacija ne vodi evidenciju tvojih napojnica. Na telefonu čuva samo napomenu dok kupovina još nije završena, da bi mogla kasnije da je završi; napomena se briše čim se kupovina završi.

## Šta ne radimo

Nemamo server sa tvojim podacima. Ne koristimo reklame, analitiku, alate za praćenje ni izveštaje o greškama. Ne prodajemo i ne delimo podatke, jer ih nemamo. Napojnice u celosti obrađuju Google ili Apple.

## Brisanje podataka

- U aplikaciji: **Podešavanja → Obriši sve podatke** briše vozila, istoriju, zapamćena mesta i podešavanja.
- Brisanjem aplikacije sa telefona brišu se i svi njeni podaci (osim kopije telefona, ako je imaš; nju brišeš u podešavanjima Google ili Apple naloga).

## Deca

Aplikacija nije namenjena deci i ne prikuplja podatke o njima.

## Tvoja prava

Pošto ne prikupljamo tvoje podatke o ličnosti, nemamo šta da ti pokažemo, ispravimo ili obrišemo: sve je na tvom telefonu i pod tvojom kontrolom. Za podatke iz SMS plaćanja obrati se svom mobilnom operateru ili JKP „Parking servis” svog grada. Ako misliš da su ti prava prekršena, možeš da podneseš pritužbu [Povereniku za informacije od javnog značaja i zaštitu podataka o ličnosti](https://www.poverenik.rs).

## Izmene

Ako aplikacija dobije nešto što menja ovu politiku (na primer novi grad ili novu vrstu veze sa internetom), prvo ćemo ažurirati ovaj tekst i datum na vrhu.

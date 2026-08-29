# LAF — Prijedlog izmjena za redizajn weba

Dokument sažima što treba promijeniti na trenutnoj verziji (`index.html`) na temelju povratne informacije klijenta i reference [mintclub.hr](https://mintclub.hr/). Prije izrade nove verzije, ovo je za tvoju provjeru/izmjene — nakon toga stižu još 4 slike od klijenta i krećemo u build.

## 1. Kontekst

- Klijentu i "partnerima" trenutni prijedlog **nije "wow"** — traže da web djeluje **moćnije, modernije i "zatajno"** (diskretno, privatno), a ne samo dekorativno-glam kao sad (shimmer efekt na logu, purple glow pozadine, kurzivni serif citati).
- Referenca za raspored/kratkoću: **mintclub.hr** — ali klijentu se ne sviđa taj font (plain sistemski sans), samo raspored i izbornik ("Tu mi nije lijep font slova, ali ostalo mi je okej možda raspored i izbornik").
- Boje: **crno + rose gold** (prvi izbor), sa **zelenom kao alternativom** ("boje da su tako sve crno, rose gold ili zeleno").
- Klijent je tražio potvrdu do petka — vrijedi provjeriti je li taj rok još aktualan prije nego stavimo previše u prvi krug.

## 2. Vizualni identitet — što se mijenja

| | Sada | Novo |
|---|---|---|
| Boje | Zlatna `#B8965A` / `#D4AF6A`, tamnoljubičasta, bordo akcenti | Crno + **rose gold** kao primarna paleta; zelena varijanta kao opcija B |
| Fontovi | Cinzel, Cinzel Decorative, Cormorant Garamond, Josefin Sans, Raleway | Nova, prefinjenija kombinacija — izbjeći generički sans (to je točno ono što klijentu smeta kod Mint Cluba) |
| Ton | Glam/dekorativno — shimmer na logu, custom kursor, ljubičasti glow, floral/decorative serif citati | Suzdržanije, "moćnije" — manje ukrasa, više prostora, jači kontrast, mirnija tipografija koja odaje samopouzdanje i diskreciju |

## 3. Struktura stranice — pojednostavljenje po uzoru na Mint Club

**Sada** (dugačko, 9 sekcija): Nav → Hero → O nama/Iskustvo → Radno vrijeme + Dress code → Usluge (5 kartica) → Galerija → Rezervacije CTA → Recenzije → Kontakt s mapom → Footer.

**Mint Club** (kratko, direktno): Hero na cijeli ekran s videom + 3 velika pill-gumba (Eventi / Cabaret / Restoran) → kratke sekcije po temi → Galerija → Radno vrijeme → Kontakt i socialni linkovi u footeru. Nema recenzija, nema karte, nema dugih opisnih pasusa.

**Prijedlog nove strukture za LAF:**

1. **Hero** — video pozadina, kraći naslov, 2–3 pill-gumba umjesto trenutna dva teksta-gumba (npr. Klub / Restoran / Rezervacije — ovisi o odgovoru na pitanje o restoranu, vidi §5)
2. **O nama** — postojeći tekst skratiti na 2-3 rečenice, zadržati brojke (pratitelji, ocjena, radno vrijeme)
3. **Diskrecija / Privatnost** *(nova sekcija)* — vidi §4
4. **Radno vrijeme + Dress code** — zadržati, ali kompaktnije
5. **Paketi** *(nova sekcija)* — Petak/Subota cjenici, vidi §4
6. **Usluge / Restoran** — razmotriti izdvajanje Restorana u zaseban blok umjesto da je samo jedna od 5 kartica (pitanje za klijenta, §5)
7. **Galerija** — zadržati, nove slike
8. **Kontakt + rezervacija** — spojiti trenutne dvije odvojene sekcije (Rezervacije CTA + Kontakt) u jednu, kraću
9. **Footer** — zadržati kompaktan, kao sad

Recenzije sekciju predlažem **izbaciti ili svesti na jednu liniju u footeru** ("4,6 ★ na Google Mapsu") — Mint Club referenca nema recenzije, a ide u prilog kraćem, "moćnijem" dojmu bez da web djeluje kao da moli za potvrdu kroz tuđe recenzije.

## 4. Novi sadržaji koje treba ugraditi

**a) Poruka o diskreciji** (iz Instagram objave klijenta):

> "Mi ne snimamo, ne objavljujemo i ne otkrivamo naše goste."
> "LAF je mjesto koje ne pratiš — nego koje doživiš. Ono što se dogodi u LAF-u, ostaje u LAF-u."

Ovo je zapravo najjači materijal za "zatajni" ton koji klijent traži — trenutna stranica ima samo varijaciju te rečenice u Rezervacije sekciji ("What happens in LAF, stays in LAF"), a ne i samu politiku privatnosti gostiju. Vrijedi joj dati vlastitu sekciju/istaknuto mjesto.

**b) Paketi — cjenik** (iz poslanih grafika):

*Paketi petkom*

| Paket | Sadržaj | Redovna cijena | Posebna cijena |
|---|---|---|---|
| Paket 1 (4/6 osoba) | 2 boce (Jack Daniels, Finlandia vodka, Bombay gin) + 10 sokova + 1 plata po izboru | 310 € | 250 € |
| Paket 2 (8 osoba) | 4 boce + 20 sokova + 2 plate po izboru | 620 € | — |

*Paketi subotom*

| Paket | Sadržaj | Cijena |
|---|---|---|
| Premium paket | 1 plata po izboru + 2 boce (Grey Goose vodka, Gentleman Jack) + 10 sokova | **nije navedena na slici — treba tražiti od klijenta** |

## 5. Otvorena pitanja za klijenta (prije/tijekom izrade)

- Treba li **Restoran** dobiti zasebnu sekciju/stranicu (kao kod Mint Cluba), ili ostaje samo jedna od kartica pod "Usluge"? Klijent u poruci spominje "naš klub **i restoran**" kao dvije stvari koje web treba predstaviti.
- Konačna odluka: **rose gold ili zelena** paleta (ili napraviti obje pa klijent bira)?
- Nedostaje **cijena Premium paketa subotom** na poslanoj slici.
- Nedostaje broj osoba za Premium paket (subota) — kod petka je navedeno 4/6 i 8, kod subote nije.
- Zadržati Google Maps ugrađenu kartu u Kontaktu, ili samo tekstualna adresa (kraće, u duhu diskrecije)?
- Zadržati recenzije negdje na stranici ili potpuno izbaciti?

## 6. Slike

- Sve trenutne slike (`img/photo_01–09.jpg`) su placeholderi — zamijeniti materijalom s [@laf__club](https://www.instagram.com/laf__club/) i s 4 slike koje klijent šalje.
- S obzirom na poruku o diskreciji gostiju, birati kadrove koji naglašavaju **ambijent, interijer, detalje, atmosferu** radije nego prepoznatljiva lica gostiju — to je i vizualno dosljedno s porukom "ne otkrivamo naše goste".

## 7. Tehnički pristup

- Ostaje jednostavan, statičan HTML/CSS/JS (bez frameworka), kao sad — samo se mijenjaju CSS varijable za boje/fontove, skraćuje i reorganizira sadržaj sekcija, dodaju se dvije nove sekcije (Diskrecija, Paketi).

## Sljedeći koraci

1. Ti pregledaš/dopuniš ovaj dokument (posebno §5 — otvorena pitanja).
2. Klijent šalje 4 dodatne slike.
3. Krećemo u izradu nove verzije `index.html`.

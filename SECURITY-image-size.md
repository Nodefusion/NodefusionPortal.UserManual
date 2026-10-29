# Poznata ranjivost: image-size (bez dostupne zakrpe)

## Problem

Paket `image-size` (tranzitivna ovisnost preko `@docusaurus/mdx-loader`) sadrži
dvije DoS ranjivosti (beskonačna petlja pri parsiranju slika):

- **GHSA-w3rx-r6r6-pgpr** — ICNS parser
- **GHSA-5p2g-fcmc-qvqq** — JXL i HEIF parseri

Pogađaju sve verzije zaključno s najnovijom (2.0.2). **Upstream zakrpa trenutno
ne postoji**, pa nadogradnja ne rješava problem.

## Stvarni rizik

`image-size` se koristi samo tijekom builda, za slike iz repozitorija — ne
obrađuje sadržaj koji uploadaju korisnici u produkciji. Iskorištavanje bi
zahtijevalo da netko već ima pravo pisanja u repo (npr. maliciozan PR sa
zaraženom slikom).

## Rješenje

1. Pratiti upstream (`image-size` repo / GHSA stranice) i čim izađe zakrpa,
   odmah nadograditi.
2. Do tada, code review obavezan za svaki PR koji dodaje nove binarne/slikovne
   datoteke, kako bi se smanjila stvarna izloženost.

Dokument obrisati/ažurirati kada se ranjivost riješi.

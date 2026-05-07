# Računovodstvo FPZ — Dashboard

Referentni dashboardi za računovodstvo Fakulteta prometnih znanosti.
Primjenjivo od 01.01.2026.

## Stranice

- **`index.html`** — Izvori financiranja i konta prihoda (glavna stranica)
- **`mt.html`** — Mjesta troška (MT) s pripadajućim izvorima

Navigacija između stranica se nalazi ispod zaglavlja na svakoj stranici.

## Pristup

Otvori URL ovog repozitorija na GitHub Pages:

```
https://[korisničko-ime].github.io/[ime-repozitorija]/
```

Mt podstranica je dostupna na:

```
https://[korisničko-ime].github.io/[ime-repozitorija]/mt.html
```

## Funkcije

- Pretraga uživo kroz sva polja
- Filtriranje po skupinama (boja-kodirano)
- Klik na šifru ili konto kopira vrijednost u međuspremnik
- Sklopive napomene i legenda
- Prečac: `/` za fokus pretrage, `Esc` za brisanje

## Ažuriranje sadržaja

Kada Ministarstvo financija objavi izmjenu, izmijeni odgovarajući fajl u repozitoriju (sekcija `const DATA = [...]` na vrhu `<script>` bloka). Promjene su odmah vidljive svima preko GitHub Pages URL-a.

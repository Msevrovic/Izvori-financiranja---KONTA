# Izvori financiranja i konta prihoda

Referentni dashboard za računovodstvo FPZ-a.

Primjenjivo od 01.01.2026.

## Pristup

Otvori URL ovog repozitorija na GitHub Pages — adresa je oblika:

```
https://[korisničko-ime].github.io/[ime-repozitorija]/
```

## Funkcije

- Pretraga po šifri izvora, kontu, nazivu ili namjeni
- Filtriranje po skupinama izvora financiranja (1, 3, 4, 5, 6, 7, 8, XX)
- Klik na šifru ili konto kopira vrijednost u međuspremnik
- Sklopiva sekcija s pravilima i napomenama
- Prečac: `/` za fokus pretrage, `Esc` za brisanje

## Ažuriranje sadržaja

Kada Ministarstvo financija objavi izmjenu izvora ili konta, izmijeni `index.html` u repozitoriju (u sekciji `const DATA = [...]` na vrhu `<script>` bloka). Promjene su odmah vidljive svima preko GitHub Pages URL-a.

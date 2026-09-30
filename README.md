# Kormányhatározatok 2010–2026 — a 2000-es sorozat

Interaktív vizualizáció a kormany.hu által 2026-09-29-én közzétett,
korábban nem publikált kormányhatározatokról.

- **3 598** közzétett határozat, 2010–2026
- **491** visszatartott sorszám (kiadott: 4 089 → 12% nem került nyilvánosságra)
- **111** tematikus dosszié, ebből **40** kutatott (287 ellenőrzött forrás)

## Adatforrás

https://kormany.hu/kormanydontesek-20102026 — 17 PDF (évenként egy).
A `data.json` ezekből készült, szövegkoordináta-alapú táblázat-kinyeréssel.

## Fontos korlátok

- A kiadott anyag **dátumot nem tartalmaz** — az év a legfinomabb felbontás.
  A sorszám csak közelítő kronológia.
- **Egyetlen nyilvános forrás sem kapcsol konkrét 2000-es sorszámot
  kifizetett összeghez.** A pénzügyi adatok a *dossziéhoz* tartoznak,
  forrásmegjelöléssel, nem a sorszámhoz.
- Bizonyítási szintek: `allegation` / `official` / `documented_outcome`.
  Korrupciót a vizualizáció nem állít, csak dokumentált forrásokat idéz.
- 71 dosszié még kutatás nélkül — ezek jelölve vannak.

## Hozzájárulás

A hiányzó források pótlása PR-ral a leghasznosabb. Minden hivatkozásnak
ellenőrizhető, elérhető URL-re kell mutatnia.

## Felépítés

| fájl | |
|---|---|
| `index.html` | a teljes alkalmazás (nincs build) |
| `data.json` | 3 598 határozat + 111 dosszié, ~1 MB |
| `vercel.json` | cache-fejlécek |

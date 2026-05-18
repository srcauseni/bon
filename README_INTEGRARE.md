# Integrare bon + Farmacia

Fișier principal: `bon_integrat_farmacia.html`

Ce este inclus:
- `db.js` — catalog servicii medico-sanitare
- `prices.js` — prețuri externe pentru servicii, dacă sunt actualizate separat
- `farmacia_data.js` — pozițiile din Excel cu preț pe unitate
- `sursa_farmacia_pret_unitar.xlsx` — fișierul Excel sursă

Noutate:
- Căutarea din bon este unificată.
- În câmpul de căutare se caută simultan în:
  1. catalogul de servicii medicale;
  2. farmacia din Excel.
- Pozițiile din farmacie pot fi adăugate direct în bon.
- Prețul folosit este `pret_unitar`.

Cum se folosește:
1. Deschide `bon_integrat_farmacia.html`.
2. În câmpul „Sau caută după denumire” scrie denumirea: de exemplu `glucoz`, `ac chirurgical`, etc.
3. Alege poziția dorită.
4. Poziția intră automat în bon cu prețul pe unitate.

Important:
Toate fișierele trebuie să fie în același dosar.
Nu este nevoie de Google Drive.

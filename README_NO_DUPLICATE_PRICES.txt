MODIFICARE: fără dublarea prețurilor vechi

Dacă în Google Sheets / CSV există aceeași poziție cu același cod ca în farmacia_data.js,
programul NU mai afișează rândul vechi din farmacia_data.js.

Exemplu:
- farmacia_data.js are MED-0001 cu 32.49 lei
- Google Sheets are MED-0001 cu 3249 lei
În căutare va apărea doar MED-0001 cu 3249 lei.

Regula:
Google Sheets / CSV are prioritate față de farmacia_data.js.

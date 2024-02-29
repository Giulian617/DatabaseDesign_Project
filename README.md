# Retea de socializare pentru cititori

### Cerinte obligatorii

- [x] 1. Descrierea modelului real, a utilitatii acestuia si a regulilor de functionare.
- [x] 2. Prezentarea constrangerilor (restrictii, reguli) impuse asupra modelului.
- [x] 3. Descrierea entitatilor, incluzand precizarea cheii primare.
- [x] 4. Descrierea relatiilor, incluzand precizarea cardinalitatii acestora.
- [x] 5. Descrierea atributelor, incluzand tipul de date si eventualele constrangeri, valori implicite, valori posibile ale atributelor.
- [x] 6. Realizarea diagramei entitate-relatie corespunzatoare descrierii de la punctele 3-5.
- [x] 7. Realizarea diagramei conceptuale corespunzatoare diagramei entitate-relatie proiectata la punctul 6. Diagrama conceptuala obtinuta trebuie sa contina minimum 6 tabele (fara considerarea subentitatilor), dintre care cel putin un tabel asociativ.
- [x] 8. Enumerarea schemelor relationale corespunzatoare diagramei conceptuale proiectata la punctul 7.
- [x] 9. Realizarea normalizarii pana la forma normala 3 (FN1-FN3).
- [x] 10. Crearea unei secvente ce va fi utilizata in inserarea inregistrarilor in tabele.
- [x] 11. Crearea tabelelor in SQL si inserarea de date coerente in fiecare dintre acestea (minimum 5 inregistrari in fiecare tabel neasociativ; minimum 10 inregistrari in tabelele asociative).

### Cerinte de complexitate

- [x] 12. Formulati in limbaj natural si implementati 5 cereri SQL complexe ce vor utiliza, in ansamblul lor, urmatoarele elemente:
    - subcereri sincronizate in care intervin cel putin 3 tabele
    - subcereri nesincronizate in clauza FROM
    - grupari de date cu subcereri nesincronizate in care intervin cel putin 3 tabele, functii grup, filtrare la nivel de grupuri (in cadrul aceleiasi cereri)
    - ordonari si utilizarea functiilor NVL si DECODE (in cadrul aceleiasi cereri)
    - utilizarea a cel putin 2 functii pe siruri de caractere, 2 functii pe date calendaristice, a cel putin unei expresii CASE
    - utilizarea a cel putin 1 bloc de cerere (clauza WITH)
- [x] 13. Implementarea a 3 operatii de actualizare si 3 operatii de suprimare a datelor utilizand subcereri.
- [x] 15. Formulati in limbaj natural si implementati in SQL: o cerere ce utilizeaza operatia outer-join pe minimum 4 tabele, o cerere ce utilizează operatia division si o cerere care implementează analiza top-n
- [x] 16. Optimizarea unei cereri, aplicand regulile de optimizare ce deriva din proprietatile operatorilor algebrei relationale. Cererea va fi exprimata prin expresie algebrica, arbore algebric si limbaj (SQL), atat anterior cat si ulterior optimizarii.
- [x] 17. Realizarea normalizarii BCNF, FN4, FN5. Aplicarea denormalizarii, justificand necesitatea acesteia.

- [ ] 14. Nu a mai facut parte din proiect.

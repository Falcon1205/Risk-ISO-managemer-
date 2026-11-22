# Program praktyki z Claude – symulowane projekty

## Jak to działa

Przechodzisz **pełny cykl projektów doradczych** na fikcyjnej firmie **ACME Komponenty Sp. z o.o.** (`praktyka/acme/opis-firmy.md`).
Claude gra role: prezesa, dyrektora finansowego, kierownika IT, pracowników, audytowanych, a na koniec **ocenia Twoją pracę** jak starszy konsultant / lead auditor.

Każde ćwiczenie = **jeden realny produkt usługowy**, który później sprzedasz. Przerabiasz go najpierw „na sucho”, a gotowy dokument trafia do `toolkit/` jako szablon do pracy z klientami.

**Start ćwiczenia:** napisz np. `Start P3` – Claude ustawi scenę, poda rolę i zasady.
**Wynik:** zapisujemy w `praktyka/wyniki/` (ocena, mocne strony, luki, co powtórzyć).

### Zasady realizmu
- Postacie z ACME **nie są ekspertami** – mówią językiem biznesu, czasem się mylą, bronią się, coś ukrywają.
- Nie dostaniesz informacji, o którą nie zapytasz (jak w prawdziwym wywiadzie/audycie).
- Claude nie podpowiada w trakcie, chyba że napiszesz `pauza – podpowiedź`.
- Ocena wg rubryki: **merytoryka (normy/przepisy) · technika pracy (pytania, dowody) · komunikacja z klientem · jakość dokumentu · wartość biznesowa**.

### Uczciwie o ograniczeniach
Symulacja daje umiejętności, pewność siebie i gotowe szablony, ale **nie zastępuje udokumentowanej praktyki**
(jednostki certyfikujące i klienci będą pytać o realne audyty). Dlatego plan zawiera też 1–3 prawdziwe pilotaże (miesiące 3–6).

## Ścieżka ćwiczeń

| Nr | Ćwiczenie | Claude gra | Twój produkt | Powiązana usługa (sprzedaż) | Faza planu |
|---|---|---|---|---|---|
| **P0** | Quiz diagnostyczny ISO 27001 (stan wiedzy) | egzaminator | Mapa luk w wiedzy | – | start |
| P1 | Rozmowa wstępna z prezesem ACME – „po co nam to wszystko?” | prezes, sceptyczny | Notatka z potrzebami + propozycja zakresu | **rozmowa sprzedażowa (discovery)** | 1 |
| P2 | Ustalenie kontekstu, apetytu i kryteriów ryzyka z zarządem | prezes + CFO | Kryteria ryzyka i macierz akceptacji | warsztat ryzyka dla zarządu | 1 |
| P3 | Warsztat identyfikacji i oceny ryzyka (ransomware, dostawcy, OT) | kierownik IT, kierownik produkcji | Rejestr ryzyk + bow-tie | ocena ryzyka (projekt) | 1 |
| P4 | Ilościowa analiza ryzyka dla CFO – „ile nas to może kosztować?” | CFO | Analiza w PLN (Monte Carlo/FAIR-lite) | analiza ryzyka ilościowa | 1 |
| P5 | **Gap analysis ISO 27001** – wywiady + przegląd dokumentów | 4 osoby z ACME | Raport z luk + mapa drogowa | **gap analysis (produkt wejściowy)** | 2 |
| P6 | Zakres ISMS, SoA i plan postępowania z ryzykiem | kierownik IT | SoA + plan postępowania z ryzykiem | wdrożenie ISMS | 2 |
| P7 | **Audyt wewnętrzny ISO 27001** – plan, wywiady, próbki, niezgodności | audytowani (z ukrytymi problemami) | Plan audytu, raport, niezgodności | **audyt wewnętrzny (pierwsza płatna usługa)** | 2 |
| P8 | Spotkanie zamykające audyt – audytowany kwestionuje niezgodność | kierownik IT, defensywny | Obrona niezgodności, ustalenia | audyt | 2 |
| P9 | Czy ACME podlega NIS 2 / UKSC? + gap analysis NIS 2 | prezes, prawnik | Kwalifikacja podmiotu + raport luk NIS 2 | **gap analysis NIS 2** | 3 |
| P10 | BIA – wywiady z właścicielami procesów | kierownicy procesów | BIA (RTO/RPO/MTPD) | BIA / BCM | 4 |
| P11 | **Ćwiczenie tabletop „ransomware”** – Ty prowadzisz, zarząd ACME uczestniczy | zarząd ACME | Scenariusz + raport z ćwiczenia | **tabletop dla zarządu** | 4 |
| P12 | Diagnoza kultury ryzyka – wywiady, ankieta, raport | pracownicy różnych szczebli | Raport kultury ryzyka | diagnoza kultury (flagowa) | 5 |
| P13 | Prezentacja dla zarządu (art. 20 NIS 2) + negocjacja oferty na wdrożenie | prezes + CFO, twardzi negocjatorzy | Prezentacja + oferta | **zamknięcie sprzedaży** | 6 |

Dodatkowo co tydzień: **mini-quiz** (10 pytań) z bieżącego tematu i **„sytuacja z życia”** (krótki case: „klient mówi X – co odpowiadasz?”).

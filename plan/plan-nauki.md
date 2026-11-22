# Plan nauki – 12 miesięcy (wersja 2, dopasowana do profilu)

## Profil wyjściowy (stan: 2026-11)

- Praca w cyberbezpieczeństwie (blue team), certyfikaty techniczne – wiedza zdobywana głównie „pod egzamin”.
- **ISO/IEC 27001 Lead Auditor** – certyfikat jest, praktyki brak, wiedza wymaga odświeżenia.
- Czas: **1–2 h dziennie** (ok. 8–12 h tygodniowo). Budowa firmy obok etatu. Rynek: **Polska**, wszystkie sektory.
- Cel: **specjalista od ryzyka + wdrożenia i audyty ISO 27001 + ciągłość działania (ISO 22301)**.

### Co z tego wynika dla planu
1. **Nie uczysz się cyber od zera** – Twoja przewaga to rozumienie, jak zabezpieczenia działają w praktyce (SOC, incydenty, detekcja).
   Brakuje Ci warstwy **zarządczej**: ryzyko, system zarządzania, rozmowa z zarządem. Na tym skupia się plan.
2. **Problem „wiedzy pod egzamin”** rozwiązujemy zasadą: *każdy temat → zadanie praktyczne → dokument w portfolio → treść do publikacji*.
   Wiedza, którą wytłumaczysz komuś innemu, nie ulatuje.
3. **Nie robisz ISO 27001 Lead Implementer na start** – masz LA, a brakuje Ci praktyki, nie kolejnego certyfikatu. Budżet przeznacz na ISO 22301.
4. **Praktyka audytorska jest priorytetem** – bez niej certyfikat LA ma ograniczoną wartość rynkową (patrz „Ścieżka praktyki”).

## Przegląd

| Faza | Miesiące | Temat | Produkt (portfolio) | Certyfikacja |
|---|---|---|---|---|
| 1 | 1–2 | Fundamenty ryzyka: ISO 31000, NIST SP 800-30, ISO/IEC 27005, FAIR | **Metodyka zarządzania ryzykiem v1** | – |
| 2 | 3–4 | ISO/IEC 27001/27002 – odświeżenie z perspektywy wdrożeniowca **i** audytora | **Toolkit ISMS** + checklista audytowa | – |
| 3 | 5–6 | Regulacje: NIS 2, UKSC, RODO, KRI, DORA | **Mapowanie NIS 2/UKSC ↔ ISO 27001** + test „czy podlegasz NIS 2” | – |
| 4 | 7–8 | **Ciągłość działania**: ISO 22301, BIA, plany, testy | **Toolkit BCM** (BIA, BCP, scenariusz ćwiczenia) | **ISO 22301 Lead Implementer** |
| 5 | 9–10 | Kultura ryzyka – specjalizacja | **Model dojrzałości kultury ryzyka** + ankieta | – |
| 6 | 11–12 | Praktyka i start sprzedaży | Case study z 1–3 pilotaży | Rok 2: **CRISC** |

**Ścieżka praktyki** biegnie równolegle od 2. miesiąca – patrz niżej.
**Praktyka symulowana z Claude:** ćwiczenia P0–P13 (`praktyka/program-praktyki.md`) – P1–P4 w fazie 1, P5–P8 w fazie 2, P9 w fazie 3, P10–P11 w fazie 4, P12 w fazie 5, P13 w fazie 6.

### Kamienie milowe sprzedaży (szczegóły: `marka/model-przychodow.md`)
| Miesiąc | Sprzedaż |
|---|---|
| 1 | Sprawdzenie umowy o pracę; lista 30 kontaktów (firmy doradcze, IT/MSSP, kancelarie, znajomi w MŚP) |
| 2–3 | Zgłoszenie się jako podwykonawca/audytor do 5–10 firm i jednostek certyfikujących; **pierwsza płatna usługa: audyt wewnętrzny lub podwykonawstwo** |
| 4–6 | Oferta gap analysis 27001/NIS 2 ze stałą ceną; lead magnet NIS 2; 2 partnerów polecających |
| 7–9 | Tabletop i warsztat dla zarządu w ofercie; 2–3 rozmowy sprzedażowe tygodniowo |
| 10–12 | Pierwsze wdrożenie (samodzielnie lub z partnerem) → propozycja abonamentu |

---

## Rytm tygodnia (1–2 h dziennie)

| Dzień | Czas | Co |
|---|---|---|
| Pn–Czw | 60–75 min | Nauka: norma / przepis / książka + notatka w `normy/notatki/` (własnymi słowami, max 1 strona) |
| Pt | 60 min | Zadanie praktyczne tygodnia (dokument do portfolio) |
| Sob | 90–120 min | Dokończenie zadania + **1 post na LinkedIn** z tego, czego się nauczyłeś |
| Nd | 15 min | Wpis w `plan/dziennik-postepow.md`, plan następnego tygodnia; reszta – odpoczynek |

Zasada „**30 minut na odpytanie**”: raz w tygodniu poproś mnie o quiz / case study z bieżącego tematu – to najlepszy sposób, by nie wracać do nauki „pod egzamin”.

---

## Faza 1 – Fundamenty zarządzania ryzykiem (miesiąc 1–2)

| Tydz. | Temat | Materiał | Zadanie praktyczne |
|---|---|---|---|
| 1 | Definicja ryzyka („wpływ niepewności na cele”), apetyt, tolerancja, właściciel ryzyka | ISO 31073, ISO 31000 kl. 1–4 | Słowniczek 30 pojęć PL/EN; post: „Ryzyko to nie zagrożenie” |
| 2 | Ramy zarządzania ryzykiem i proces | ISO 31000 kl. 5–6 | Opis ram dla fikcyjnej firmy „ACME” (MŚP produkcyjne, 150 os.) – będzie Twoim poligonem przez cały plan |
| 3 | Model i proces oceny ryzyka NIST | **NIST SP 800-30 Rev.1** rozdz. 2–3 + zał. D–I | Porównanie ISO 31000 vs NIST 800-30 (1 strona) |
| 4 | Ryzyko w bezpieczeństwie informacji | **ISO/IEC 27005:2022** (podejście oparte na zdarzeniach vs na aktywach) | Wybór podejścia dla ACME z uzasadnieniem |
| 5 | Techniki oceny | IEC 31010 – bow-tie, scenariusze, FMEA, Delphi, BIA | Bow-tie „ransomware” – **wykorzystaj wiedzę blue team** (bariery prewencyjne = detekcja/prewencja, bariery łagodzące = IR/backup) |
| 6 | Ryzyko ilościowe | Hubbard & Seiersen *How to Measure Anything in Cybersecurity Risk*, rozdz. 1–4; podstawy FAIR | Symulacja Monte Carlo w Excelu: roczna strata z ransomware w PLN |
| 7 | ERM i ład korporacyjny | COSO ERM 2017 (streszczenie), IIA Three Lines Model, NIST IR 8286 (wybrane rozdziały) | Jak ryzyko cyber trafia do rejestru ryzyk zarządu ACME |
| 8 | Synteza | – | **Metodyka zarządzania ryzykiem v1** (8–15 str.) → `toolkit/` + artykuł |

## Faza 2 – ISO/IEC 27001 oczami wdrożeniowca i audytora (miesiąc 3–4)

Każdą klauzulę przerabiasz dwutorowo: **„jak to wdrożyć proporcjonalnie?”** oraz **„o co zapytam i jaki dowód chcę zobaczyć jako audytor?”**.

| Tydz. | Temat | Materiał | Zadanie praktyczne |
|---|---|---|---|
| 1 | Struktura (Harmonized Structure), kl. 4 + Amd 1:2024, zakres | 27001, 27000, 27003 | Kontekst, strony zainteresowane i zakres ISMS dla ACME |
| 2 | Kl. 5–6: przywództwo, polityka, cele, **ryzyko (6.1.2, 6.1.3)** | 27001, 27005 | Polityka (2 str.) + metodyka ryzyka ISMS spójna z fazą 1 |
| 3–4 | Załącznik A / 27002: 93 zabezpieczenia, atrybuty | 27002:2022 | **Deklaracja stosowania (SoA)** ACME; przy zabezpieczeniach technicznych – opisz, jaki dowód przedstawiłby Twój SOC |
| 5 | Kl. 7–8: kompetencje, świadomość, dokumentacja, działania | 27001 | Program świadomości oparty o zachowania (np. wskaźnik zgłoszeń phishingu, nie tylko „klikalność”) |
| 6 | Kl. 9–10: pomiar, audyt wewnętrzny, przegląd zarządzania, niezgodności | 27004, **ISO 19011**, 27007 | 10 KPI/KRI ISMS + program audytów wewnętrznych |
| 7 | Technika audytu: próbkowanie, dowody, formułowanie niezgodności | ISO 19011 kl. 6–7, ISO/IEC 27006-1 (w zarysie) | **Checklista audytowa 27001** + 10 przykładowych niezgodności (opis, wymaganie, dowód) |
| 8 | Synteza i harmonogram wdrożenia | – | **Toolkit ISMS** w `toolkit/` + harmonogram wdrożenia 6-mies. dla MŚP |

## Faza 3 – Regulacje (miesiąc 5–6)

| Tydz. | Temat | Materiał | Zadanie praktyczne |
|---|---|---|---|
| 1–2 | NIS 2: zakres, podmioty kluczowe/ważne, art. 20, 21, 23, nadzór, kary | Dyrektywa 2022/2555 | Drzewo decyzyjne „czy podlegasz NIS 2?” – **lead magnet** |
| 3 | Rozporządzenie wykonawcze 2024/2690 | Załącznik | Checklista wymagań technicznych |
| 4–5 | **UKSC po nowelizacji** – obowiązki, terminy, organy, audyty | ISAP, gov.pl/cyfryzacja | ⚠️ zweryfikuj aktualny stan prawny; harmonogram dostosowania dla podmiotu ważnego |
| 6 | Mapowanie NIS 2 art. 21 ↔ ISO 27001 Zał. A ↔ NIST CSF 2.0 | – | **Macierz mapowania** → `normy/mapowanie-nis2-iso27001.md` |
| 7 | RODO (art. 24, 25, 32, 35) + KRI § 20 (sektor publiczny) | – | Notatka „ISO 27001 a KRI – co wystarczy JST” |
| 8 | DORA (przegląd) | 2022/2554 + RTS 2024/1774 | Notatka 2-str. „DORA dla zarządu” |

## Faza 4 – Ciągłość działania / BCM (miesiąc 7–8)

| Tydz. | Temat | Materiał | Zadanie praktyczne |
|---|---|---|---|
| 1 | System BCM, kl. 4–10 (ta sama struktura co 27001!) | **ISO 22301:2019** | Mapa wspólnych elementów ISMS + BCMS (zintegrowany system) |
| 2–3 | **Analiza wpływu na działalność (BIA)**: MTPD, RTO, RPO, MBCO, zależności | ISO/TS 22317:2021, ISO 22313:2020 | BIA dla 5 procesów ACME |
| 4 | Ocena ryzyka ciągłości i strategie | ISO 22301 kl. 8.2–8.3 | Strategie dla 3 scenariuszy: ransomware, utrata dostawcy chmury, niedostępność zakładu |
| 5 | Plany: BCP, zarządzanie kryzysowe, komunikacja; ciągłość ICT | ISO 22301 kl. 8.4, **ISO/IEC 27031**, ISO 22361 (zarządzanie kryzysowe) | BCP + plan odtwarzania ICT – **Twoja wiedza z IR to atut** |
| 6 | Ćwiczenia i testy | ISO 22398 (w zarysie) | **Scenariusz ćwiczenia tabletop** (ransomware) dla zarządu – gotowa usługa do sprzedaży |
| 7 | NIS 2 art. 21 lit. c + DORA – wymagania ciągłości | – | Mapowanie ISO 22301 ↔ NIS 2 |
| 8 | **Kurs + egzamin ISO 22301 Lead Implementer** | PECB lub inny akredytowany | Certyfikat; **Toolkit BCM** w `toolkit/` |

## Faza 5 – Kultura ryzyka (miesiąc 9–10)

- Modele: IRM Risk Culture Framework, FSB (tone from the top, rozliczalność, komunikacja i prawo do kwestionowania, zachęty),
  COSO ERM „Governance & Culture”, NIST CSF 2.0 GOVERN, ENISA – aspekty behawioralne.
- Nauki behawioralne: *just culture* (Dekker), bezpieczeństwo psychologiczne (Edmondson), błędy poznawcze w ocenie ryzyka (Kahneman, Gigerenzer).
- Pomiar: ankiety, wskaźniki behawioralne (zgłoszenia incydentów i near-miss, czas eskalacji, jakość decyzji zarządu).
- Art. 20 NIS 2 – odpowiedzialność i szkolenia zarządu = wejście do zarządów.

**Produkty:** model dojrzałości (5 poziomów × 6–8 wymiarów), ankieta 20–30 pytań + raport wzorcowy,
warsztat dla zarządu 3–4 h (art. 20 NIS 2 + ćwiczenie tabletop z fazy 4).

## Faza 6 – Praktyka i start (miesiąc 11–12)

- 1–3 projekty pilotażowe (gap analysis NIS 2/ISO 27001 lub BIA) po obniżonej cenie lub pro bono w zamian za referencję i case study.
- Pakiet ofertowy: 3 usługi wejściowe ze stałą ceną (patrz `marka/strategia-marki.md`).
- Rok 2: **ISACA CRISC** (Twoje doświadczenie w cyber prawdopodobnie zaliczy się do wymaganego stażu – do sprawdzenia w wymaganiach ISACA),
  ewentualnie ISO 22301 Lead Auditor.

---

## Ścieżka praktyki (równolegle od miesiąca 2) – najważniejsza część planu

| Krok | Działanie | Efekt |
|---|---|---|
| 1 | **U obecnego pracodawcy:** zgłoś się do zespołu ISMS/compliance jako audytor wewnętrzny, uczestnik oceny ryzyka lub ćwiczeń BCM | Najszybsza i bezpłatna praktyka, wpis do CV |
| 2 | **Audyty wewnętrzne „na zewnątrz”:** 1–2 audyty wewnętrzne 27001 dla małych firm (znajomi, software house’y) – za symboliczną kwotę | Realne doświadczenie audytorskie |
| 3 | **Jednostki certyfikujące:** zgłoś się jako audytor kontraktowy – zwykle wymagany udział w audytach jako obserwator/audytor w szkoleniu; zapytaj o ścieżkę kwalifikacji | Praktyka „jak patrzy audytor zewnętrzny”, dodatkowy przychód, sieć kontaktów |
| 4 | **Społeczność:** ISSA Polska, ISACA Warsaw Chapter, meetupy – tam pojawiają się pierwsze zlecenia | Kontakty i polecenia |

⚠️ **Działalność obok etatu – sprawdź przed pierwszym zleceniem:** umowę o pracę (zakaz konkurencji, konflikt interesów,
klauzule o własności intelektualnej), regulamin pracy oraz to, czy klienci nie są klientami/konkurentami pracodawcy.

## Lista lektur (kolejność)

1. ISO 31000:2018 + ISO 31073:2022
2. **NIST SP 800-30 Rev.1** (bezpłatny, nist.gov)
3. ISO/IEC 27005:2022, potem 27001:2022 + 27002:2022 + ISO 19011:2018
4. Hubbard & Seiersen – *How to Measure Anything in Cybersecurity Risk* (2nd ed.)
5. Dyrektywa NIS 2 + rozporządzenie 2024/2690 + znowelizowana UKSC
6. ISO 22301:2019 + ISO/TS 22317:2021 (BIA) + ISO/IEC 27031
7. NIST CSF 2.0 + NIST IR 8286
8. IRM *Risk Culture*; Edmondson *The Fearless Organization*; Dekker *Just Culture*
9. Freund & Jones – *Measuring and Managing Information Risk: A FAIR Approach*

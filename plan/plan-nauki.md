# Plan nauki – 12 miesięcy (wersja 1, do dopasowania)

> Założenia robocze (do potwierdzenia): ok. **8–10 h tygodniowo**, start od podstaw w zakresie norm,
> pewne doświadczenie zawodowe w IT lub biznesie. Plan jest zasadą „**learn in public**” – każdy etap kończy się
> produktem, który jednocześnie buduje Twoje portfolio i markę (patrz `marka/strategia-marki.md`).

## Przegląd

| Faza | Miesiące | Temat | Produkt końcowy (portfolio) | Certyfikacja (opcjonalnie) |
|---|---|---|---|---|
| 0 | tydz. 1–2 | Diagnoza i organizacja | Profil kompetencji, zakupione normy | – |
| 1 | 1–3 | Fundamenty zarządzania ryzykiem + kultura ryzyka | **Własna metodyka zarządzania ryzykiem** (wersja 1) | ISO 31000 Risk Manager (PECB) lub IRM |
| 2 | 3–6 | ISO/IEC 27001/27002/27005 – wdrożenie ISMS | **Toolkit ISMS** (rejestr ryzyk, SoA, polityki) | **ISO/IEC 27001 Lead Implementer** |
| 3 | 6–8 | Regulacje: NIS 2, UKSC, DORA, RODO, KRI | **Mapowanie NIS 2/UKSC ↔ ISO 27001** + checklista gap analysis | NIS 2 Lead Implementer (opcjonalnie) |
| 4 | 8–10 | Kultura ryzyka (specjalizacja) + pomiar | **Model dojrzałości kultury ryzyka** + ankieta diagnostyczna | – |
| 5 | 10–12 | Audyt, ciągłość działania, praktyka | Pierwsze 1–3 projekty (pilotaż), case study | ISO/IEC 27001 Lead Auditor; potem CRISC |

---

## Faza 0 – Diagnoza i organizacja (tydzień 1–2)

- [ ] Odpowiedz na pytania diagnostyczne (patrz koniec pliku) – dopasujemy plan.
- [ ] Kup normy (PKN – polskie wersje PN; lub iso.org – EN). Minimum na start: **ISO 31000, ISO/IEC 27001, 27002, 27005**.
      Wskazówka: PKN ma czytelnię i bywa taniej w polskiej wersji; do pracy z klientem warto znać terminologię PL **i** EN.
- [ ] Załóż system notatek (np. Obsidian/Notion lub to repo – katalog `normy/notatki/`).
- [ ] Zaktualizuj profil LinkedIn wg `marka/strategia-marki.md` (wersja „w budowie” jest OK).

## Faza 1 – Fundamenty zarządzania ryzykiem (miesiąc 1–3)

**Cel:** rozumiesz ryzyko jako dyscyplinę zarządczą, nie jako tabelkę w Excelu.

| Tydzień | Temat | Materiał | Zadanie praktyczne |
|---|---|---|---|
| 1–2 | Pojęcia, definicja ryzyka („wpływ niepewności na cele”), apetyt i tolerancja | ISO 31073, ISO 31000 kl. 1–4 | Słowniczek 30 pojęć PL/EN |
| 3–4 | Ramy (framework): przywództwo, integracja, projekt, wdrożenie, ocena, doskonalenie | ISO 31000 kl. 5 | Opisz ramy dla wymyślonej firmy (np. MŚP produkcyjne, 150 os.) |
| 5–6 | Proces: kontekst, kryteria, identyfikacja, analiza, ewaluacja, postępowanie, monitorowanie, komunikacja | ISO 31000 kl. 6 | Rejestr ryzyka dla tej firmy (biznes + cyber) |
| 7–8 | Techniki oceny | IEC 31010 (wybierz 8: burza mózgów, Delphi, bow-tie, FMEA, scenariusze, BIA, macierz, Monte Carlo) | Jeden bow-tie dla ransomware, jeden dla awarii dostawcy |
| 9 | ERM i ład korporacyjny | COSO ERM 2017 (podsumowanie wykonawcze), Three Lines Model | Porównanie ISO 31000 vs COSO – **pierwszy artykuł** |
| 10 | Ryzyko ilościowe | Hubbard & Seiersen *How to Measure Anything in Cybersecurity Risk* (2. wyd.), wprowadzenie do FAIR | Prosta symulacja Monte Carlo w Excelu (strata roczna z ransomware) |
| 11 | Kultura ryzyka – wprowadzenie | IRM *Risk Culture* (model A–B–C: attitude, behaviour, culture), ISO 31000 kl. 4 (zasady) | Lista 10 symptomów słabej kultury ryzyka – **post/karuzela** |
| 12 | Synteza | – | **Metodyka zarządzania ryzykiem v1** (dokument 8–15 str.) → `toolkit/` |

## Faza 2 – ISO/IEC 27001 w praktyce (miesiąc 3–6)

**Cel:** potrafisz przeprowadzić wdrożenie ISMS od analizy luk do gotowości certyfikacyjnej.

| Tydzień | Temat | Materiał | Zadanie praktyczne |
|---|---|---|---|
| 1–2 | Struktura HLS (Harmonized Structure), kl. 4–10 | ISO/IEC 27001, 27000, 27003 | Mapa klauzul → wymagane dokumenty („documented information”) |
| 3 | Kontekst, strony zainteresowane, zakres (kl. 4) + Amd 1:2024 | 27001 kl. 4 | Dokument kontekstu i zakresu ISMS |
| 4 | Przywództwo, polityka, role (kl. 5) | 27001 kl. 5, 27014 | Polityka bezpieczeństwa informacji (2 str.!) |
| 5–7 | **Ryzyko w ISMS** (kl. 6.1.2, 6.1.3, 8.2, 8.3) | **ISO/IEC 27005:2022**, NIST SP 800-30 | Metodyka oceny ryzyka ISMS spójna z Twoją metodyką z fazy 1 |
| 8–10 | Załącznik A / ISO 27002 – 93 zabezpieczenia, atrybuty | 27002:2022 | **Deklaracja stosowania (SoA)** z uzasadnieniami |
| 11 | Wsparcie i działania (kl. 7–8): kompetencje, świadomość, komunikacja | 27001 kl. 7 | Program świadomości oparty o zachowania, nie o „slajdy raz w roku” |
| 12 | Ocena i doskonalenie (kl. 9–10): pomiar, audyt wewnętrzny, przegląd zarządzania | 27004, ISO 19011 | 10 wskaźników KPI/KRI ISMS |
| 13 | Proces certyfikacji (etap 1 / etap 2, nadzory, recertyfikacja), ISO/IEC 27006 w zarysie | – | Harmonogram wdrożenia 6-miesięcznego dla MŚP |
| 14 | **Kurs + egzamin ISO/IEC 27001 Lead Implementer** | PECB / IRCA / inne akredytowane | Certyfikat |

## Faza 3 – Regulacje (miesiąc 6–8)

| Tydzień | Temat | Materiał | Zadanie praktyczne |
|---|---|---|---|
| 1–2 | NIS 2 – zakres, podmioty kluczowe/ważne, art. 20, 21, 23, nadzór i kary | Dyrektywa 2022/2555 (motywy też!) | Drzewo decyzyjne „czy moja firma podlega NIS 2?” – **lead magnet** |
| 3 | Rozporządzenie wykonawcze 2024/2690 | Załącznik do rozporządzenia | Checklista wymagań technicznych |
| 4–5 | **UKSC po nowelizacji** – obowiązki w PL, terminy, organy (CSIRT, organy właściwe), audyty | Tekst ustawy (ISAP), materiały gov.pl/cyfryzacja | Harmonogram dostosowania dla podmiotu ważnego |
| 6 | Mapowanie NIS 2 art. 21 ↔ ISO/IEC 27001 Zał. A ↔ NIST CSF 2.0 | – | **Macierz mapowania** → `normy/mapowanie-nis2-iso27001.md` |
| 7 | RODO (art. 24, 25, 32, 35) i KRI § 20 | – | Wspólny rejestr ryzyka „bezpieczeństwo + prywatność” |
| 8 | DORA (jeśli finanse) lub CRA (jeśli producenci) – wybierz jedno | 2022/2554 + RTS 2024/1774 / 2024/2847 | Notatka 2-stronicowa „co to znaczy dla zarządu” |

## Faza 4 – Kultura ryzyka: Twoja specjalizacja (miesiąc 8–10)

**Cel:** masz autorski, mierzalny sposób diagnozowania i rozwijania kultury ryzyka. To będzie Twój „produkt flagowy”.

- Modele: IRM Risk Culture Framework (8 aspektów), FSB (tone from the top, rozliczalność, skuteczna komunikacja i wyzwanie, zachęty),
  COSO ERM komponent „Governance & Culture”, NIST CSF 2.0 GOVERN (GV.RR, GV.RM), ENISA – aspekty behawioralne.
- Nauki behawioralne: *just culture* (Sidney Dekker), bezpieczeństwo psychologiczne (Amy Edmondson – *The Fearless Organization*),
  heurystyki i błędy poznawcze w ocenie ryzyka (Kahneman; Gigerenzer *Risk Savvy*).
- Pomiar: ankiety kultury, wskaźniki behawioralne (zgłoszenia incydentów, near-miss, czas reakcji, wyniki phishing-symulacji vs. **odsetek zgłoszeń**),
  przegląd decyzji zarządu pod kątem ryzyka.
- Art. 20 NIS 2 (szkolenia zarządu, odpowiedzialność osobista) = **wejście do zarządów** z tematem kultury.

**Produkty:**
- [ ] Model dojrzałości kultury ryzyka (5 poziomów × 6–8 wymiarów)
- [ ] Ankieta diagnostyczna (20–30 pytań) + raport wzorcowy
- [ ] Warsztat dla zarządu 3–4 h „Odpowiedzialność zarządu za ryzyko cyber w NIS 2” (scenariusz + slajdy)

## Faza 5 – Audyt, ciągłość, praktyka (miesiąc 10–12)

- ISO 22301 (BCM) w zarysie + BIA – NIS 2 art. 21 lit. c wymaga ciągłości działania i zarządzania kryzysowego.
- ISO/IEC 27035 – proces obsługi incydentów pod terminy 24/72 h.
- ISO 19011 + **kurs ISO/IEC 27001 Lead Auditor** (audytor wewnętrzny / podwykonawca jednostki certyfikującej – dodatkowe źródło przychodu i wiedzy „jak patrzy audytor”).
- **Pilotaże:** 1–3 projekty po obniżonej cenie lub pro bono (fundacja, mała firma znajomego, JST) w zamian za referencję i case study.
- Następny krok certyfikacyjny: **ISACA CRISC** (ryzyko IT, rozpoznawalny globalnie; wymaga 3 lat doświadczenia do pełnej certyfikacji).

---

## Lista lektur (kolejność sugerowana)

1. ISO 31000:2018 + ISO 31073:2022
2. ISO/IEC 27001:2022 + 27002:2022 + 27005:2022
3. D. Hubbard, R. Seiersen – *How to Measure Anything in Cybersecurity Risk* (2nd ed., 2023)
4. J. Freund, J. Jones – *Measuring and Managing Information Risk: A FAIR Approach*
5. D. Hubbard – *The Failure of Risk Management* (2nd ed.)
6. NIST CSF 2.0 + NIST IR 8286
7. IRM – *Risk Culture: Resources for Practitioners*
8. A. Edmondson – *The Fearless Organization*; S. Dekker – *Just Culture*
9. Dyrektywa NIS 2 + rozporządzenie 2024/2690 + znowelizowana UKSC

## Rytm pracy (proponowany)

- **Pn–Czw:** 1 h dziennie nauki (norma/książka) + notatka.
- **Pt:** 1 h – zadanie praktyczne z tygodnia.
- **Weekend (opcjonalnie):** 1–2 h – przerobienie notatki na treść (post/artykuł).
- **Co miesiąc:** przegląd postępów w `plan/dziennik-postepow.md` i korekta planu.

## Pytania diagnostyczne (odpowiedz, a dopasuję plan)

1. Jakie masz obecnie doświadczenie (IT, audyt, compliance, finanse, zarządzanie, inne)? Ile lat?
2. Czy masz już jakieś certyfikaty (np. ISO, ITIL, CISSP, CISA, PRINCE2)?
3. Ile godzin tygodniowo realnie możesz poświęcić na naukę?
4. Jaki budżet roczny na szkolenia i certyfikacje (rząd wielkości)?
5. Jaki rynek docelowy: MŚP, sektor publiczny (JST, szpitale), finanse, produkcja, IT/software house, inny?
6. Czy pracujesz teraz na etacie i budujesz to „po godzinach”? Jaki horyzont startu firmy?
7. Rynek polski, czy także zagraniczny (treści po angielsku)?

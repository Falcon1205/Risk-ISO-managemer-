# Schemat główny: 7 pytań ryzyka (ISO = CO, NIST = JAK)

> To jest „szkielet”, na którym wieszamy CAŁĄ wiedzę o ryzyku. Nie uczysz się klauzul na pamięć –
> uczysz się 7 pytań, które każdy rozsądny człowiek zada, zanim podejmie decyzję. Numery klauzul przyjdą same, przez używanie.

**Most z SOC:** ocena ryzyka to **triage incydentu, który jeszcze się nie wydarzył**.

| # | Pytanie | Odpowiednik w SOC | ISO/IEC 27001 – **CO** musi być | NIST SP 800-30 – **JAK** to zrobić |
|---|---|---|---|---|
| 1 | **Co chronimy i po co?** | Inwentarz i krytyczność zasobów | Kontekst, strony zainteresowane, zakres (4.1–4.3) | Krok 1 – przygotowanie: cel, zakres, założenia, źródła informacji |
| 2 | **Kiedy ryzyko jest „za duże”?** | Progi severity (P1–P4), SLA | Kryteria ryzyka **i kryteria akceptacji**; powtarzalne, porównywalne wyniki (6.1.2 a, b) | Krok 1 – model ryzyka i skale (zał. G, H, I) |
| 3 | **Co może pójść źle?** | Threat modeling, use case’y detekcji | Identyfikacja ryzyk dla poufności, integralności, dostępności + **właściciel ryzyka** (6.1.2 c) | Zadania 2-1…2-3: źródło → zdarzenie → podatność + warunki sprzyjające (zał. D, E, F) |
| 4 | **Jak bardzo i jak często?** | Scoring alertu (impact × confidence) | Analiza: skutki, realne prawdopodobieństwo, poziom ryzyka (6.1.2 d) | Zadania 2-4, 2-5 (zał. G, H) |
| 5 | **Co najpierw?** | Kolejka priorytetów | Ewaluacja: porównanie z kryteriami, priorytety (6.1.2 e) | Zadanie 2-6, macierz (zał. I) |
| 6 | **Co z tym robimy i kto odpowiada?** | Playbook reakcji, eskalacja | Opcje postępowania, zabezpieczenia, porównanie z zał. A, **SoA**, plan postępowania, **akceptacja ryzyka szczątkowego przez właścicieli** (6.1.3 a–f) | Zał. J (reakcja na ryzyko); SP 800-39 „Respond” |
| 7 | **Czy to nadal prawda?** | Lessons learned, tuning reguł | Komunikacja; ocena w zaplanowanych odstępach **i przy istotnych zmianach**; realizacja planu; zapisy (8.2, 8.3, 9) | Krok 3 – komunikacja; Krok 4 – utrzymanie oceny |

## Ten sam schemat w języku NIST SP 800-39: F-A-R-M
| FARM (800-39) | Pytania |
|---|---|
| **F**rame – rama ryzyka | 1. Co chronimy i po co? · 2. Kiedy ryzyko jest „za duże”? |
| **A**ssess – ocena (SP 800-30) | 3. Co może pójść źle? · 4. Jak bardzo i jak często? · 5. Co najpierw? |
| **R**espond – reakcja | 6. Co z tym robimy i kto odpowiada? |
| **M**onitor – monitorowanie | 7. Czy to nadal prawda? |

## Skrót do odtwarzania z pamięci
**CO → KIEDY → CO ZŁEGO → JAK BARDZO → CO NAJPIERW → CO ROBIMY → CZY NADAL**

## Gdzie najczęściej „sypią się” wdrożenia (pytania audytora)
- Pyt. 2: brak **kryteriów akceptacji** albo nikt ich nie zatwierdził.
- Pyt. 3: ryzyka bez **właściciela** (albo właścicielem jest „dział IT”).
- Pyt. 6: plan postępowania bez terminów; ryzyko szczątkowe nieakceptowane przez właściciela.
- Pyt. 7: ocena nie zaktualizowana po istotnej zmianie (np. migracja do chmury).

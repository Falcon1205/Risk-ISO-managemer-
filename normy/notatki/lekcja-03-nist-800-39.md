# Lekcja 3 – NIST SP 800-39 (2011): zarządzanie ryzykiem w całej organizacji

## 1. Cztery składniki – „FARM”
| Składnik | Pytanie | Co powstaje |
|---|---|---|
| **Frame** – rama | W jakich warunkach podejmujemy decyzje o ryzyku? | Strategia ryzyka: **założenia** (np. jakie zagrożenia uznajemy za realne), **ograniczenia** (budżet, prawo, technologia), **tolerancja ryzyka**, **priorytety i kompromisy** |
| **Assess** – ocena | Jakie mamy ryzyka i jak duże? | Wyniki oceny (szczegóły: SP 800-30) |
| **Respond** – reakcja | Co z nimi robimy? | Decyzje: **akceptacja, unikanie, ograniczanie (mitigate), dzielenie/przeniesienie (share/transfer)** |
| **Monitor** – monitorowanie | Czy to nadal działa i czy coś się zmieniło? | Skuteczność reakcji, zmiany w otoczeniu, zgodność |

Frame jest „w środku” – kieruje pozostałymi trzema. Informacja płynie między wszystkimi (komunikacja).

## 2. Trzy poziomy (tiers)
| Poziom | Kto | Przykład decyzji w ACME |
|---|---|---|
| 1 – organizacja | Zarząd, „funkcja nadzoru nad ryzykiem” (risk executive function) | „Nie akceptujemy przestoju linii dłuższego niż 24 h” |
| 2 – procesy biznesowe | Kierownicy procesów, architektura | „Produkcja i ERP muszą mieć odseparowane sieci” |
| 3 – systemy | IT/OT, administratorzy | „MFA na poczcie, kopie offline ERP co noc” |
Decyzje płyną **z góry na dół** (strategia → wymagania → zabezpieczenia), informacje o ryzyku **z dołu do góry** (podatności, incydenty → raport dla zarządu).
**Analogia SOC:** alerty (poziom 3) → trendy i raport miesięczny (poziom 2) → decyzja budżetowa zarządu (poziom 1).

## 3. Opcje reakcji – NIST vs ISO/IEC 27005
| NIST SP 800-39 | ISO/IEC 27005:2022 | Przykład ACME |
|---|---|---|
| Accept – akceptacja | Retention – zatrzymanie | Akceptujemy ryzyko awarii drukarki etykiet |
| Avoid – unikanie | Avoidance – unikanie | Rezygnujemy ze zdalnego dostępu do HMI z internetu |
| Mitigate – ograniczanie | Modification – modyfikacja | MFA, segmentacja, kopie offline |
| Share / Transfer – dzielenie | Sharing – dzielenie | Ubezpieczenie cyber, umowa SLA z dostawcą ERP |

## 4. Tolerancja vs apetyt na ryzyko (w skrócie)
- **Apetyt** – ile ryzyka **chcemy** podjąć, by osiągać cele (poziom strategii, zarząd).
- **Tolerancja** – akceptowalne **odchylenie** w konkretnym obszarze (np. maks. 24 h przestoju linii).
W praktyce MŚP: zarząd często nie zna tych słów, ale **zna odpowiedź** – trzeba umieć zapytać (ćwiczenie P2).

## Zadanie
„Rama ryzyka” (Frame) dla ACME – po 2–3 punkty: założenia, ograniczenia, tolerancja, priorytety i kompromisy.

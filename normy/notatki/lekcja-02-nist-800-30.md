# Lekcja 2 – NIST SP 800-30 Rev.1 (2012) „Guide for Conducting Risk Assessments”

Bezpłatny: csrc.nist.gov (SP 800-30 Rev. 1). ~95 stron, z czego najcenniejsze: rozdz. 2–3 i załączniki D–I.

## 1. Miejsce w „rodzinie” NIST
- **SP 800-39** – zarządzanie ryzykiem w całej organizacji: **Frame → Assess → Respond → Monitor** (ramy, ocena, reakcja, monitorowanie).
- **SP 800-30** – szczegółowo tylko krok **Assess** (ocena ryzyka).
- Ocena na 3 poziomach (*tiers*): **1 – organizacja**, **2 – procesy biznesowe**, **3 – systemy informacyjne**.

## 2. Model ryzyka – łańcuch (serce dokumentu)
```
ŹRÓDŁO ZAGROŻENIA ──inicjuje──> ZDARZENIE ──wykorzystuje──> PODATNOŚĆ ──powoduje──> SKUTEK
(threat source)                 (threat event)              (vulnerability)          (adverse impact)
 cechy: zdolności,                                         + warunki sprzyjające     stopień szkody
 zamiar, ukierunkowanie                                      (predisposing conditions)
                      PRAWDOPODOBIEŃSTWO  ×  SKUTEK  =  RYZYKO
                      (zabezpieczenia wpływają na podatności i prawdopodobieństwo)
```
- **Typy źródeł zagrożeń:** celowe (*adversarial* – przestępcy, insider), przypadkowe (*accidental* – błąd człowieka),
  strukturalne (*structural* – awaria sprzętu/oprogramowania), środowiskowe (*environmental* – pożar, powódź, awaria zasilania).
- **Warunki sprzyjające** (*predisposing conditions*) – cechy organizacji, które zwiększają/zmniejszają szansę skutku,
  ale nie są „dziurą” (np. płaska sieć IT/OT, jedna lokalizacja, zależność od jednego dostawcy).
- **Prawdopodobieństwo** łączy dwie rzeczy: szansę, że zdarzenie zostanie zainicjowane/wystąpi, **oraz** szansę, że spowoduje szkodę.

## 3. Podejścia
- **Oceny:** jakościowe (bardzo niski … bardzo wysoki), półilościowe (skale punktowe), ilościowe (liczby, pieniądze).
- **Analizy:** zorientowane na zagrożenia, na skutki/aktywa, na podatności.

## 4. Proces – 4 kroki
1. **Przygotowanie:** cel, zakres, założenia i ograniczenia, źródła informacji, wybór modelu i skal.
2. **Przeprowadzenie** (zadania 2-1 … 2-6): źródła zagrożeń → zdarzenia → podatności i warunki sprzyjające →
   prawdopodobieństwo → skutek → ryzyko.
3. **Komunikacja wyników** (raport dla decydentów).
4. **Utrzymanie** (monitorowanie i aktualizacja oceny).

## 5. Załączniki – „skrzynka z narzędziami”
D – źródła zagrożeń · E – zdarzenia zagrażające · F – podatności i warunki sprzyjające · G – prawdopodobieństwo ·
H – skutki · I – wyznaczanie ryzyka (macierz) · J – reakcja na ryzyko · K – raport z oceny · L – podsumowanie zadań.
Skale 5-stopniowe: bardzo niski / niski / umiarkowany / wysoki / bardzo wysoki.

## 6. NIST 800-30 a ISO 27001 / 27005
| ISO/IEC 27001 kl. 6.1.2 wymaga… | NIST 800-30 daje… | Czego NIST nie daje (uzupełnij z ISO) |
|---|---|---|
| kryteriów ryzyka i akceptacji | skale i macierz (zał. G–I) | **kryteria akceptacji ryzyka** – decyzja zarządu |
| powtarzalnych, porównywalnych wyników | jednolity model i tabele | – |
| identyfikacji ryzyk | źródła, zdarzenia, podatności (zał. D–F) | **właściciela ryzyka** (risk owner) |
| analizy skutków i prawdopodobieństwa | zadania 2-4, 2-5 | – |
| oceny (ewaluacji) i priorytetów | zadanie 2-6, zał. I | – |

**Wniosek:** ISO mówi CO ma być w procesie, NIST 800-30 pokazuje JAK to policzyć. W praktyce konsultanta: metodyka klienta = wymagania ISO + mechanika NIST.

## 7. Przykład dla ACME (wzorcowy)
| Element | Treść |
|---|---|
| Źródło | Grupa ransomware (celowe; wysokie zdolności, motyw finansowy, ataki oportunistyczne) |
| Zdarzenie | Phishing → przejęcie konta → ruch boczny → szyfrowanie ERP i stacji HMI |
| Podatność | Brak MFA do poczty, konta admina używane na co dzień |
| Warunki sprzyjające | Płaska sieć IT/OT, kopie zapasowe w tej samej domenie |
| Prawdopodobieństwo | Wysokie |
| Skutek | Bardzo wysoki – zatrzymanie produkcji, kary umowne u klientów z DE |
| Ryzyko | **Bardzo wysokie** |

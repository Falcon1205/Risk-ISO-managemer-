# Lekcja 1 – ISO/IEC 27001 od podstaw: czym jest i jak jest zbudowana

## 1. Czym jest ISO/IEC 27001:2022
- Norma **wymagań** (*requirements*) dla **systemu zarządzania bezpieczeństwem informacji** – SZBI (*ISMS, Information Security Management System*).
- Słowo „**musi**” (*shall*) = wymaganie, które sprawdza audytor. „Powinien” (*should*) w innych normach = zalecenie.
- Tylko 27001 jest **certyfikowalna**. ISO/IEC 27002 to **wytyczne**, jak wdrażać zabezpieczenia – nie certyfikuje się na nią.
- Cel: chronić **poufność, integralność i dostępność** informacji (*CIA*) w sposób **oparty na ryzyku** i stale doskonalony.

**Analogia z blue teamu:** SOC ma zakres monitorowania, playbooki, metryki (MTTD/MTTR), przeglądy po incydentach i usprawnienia.
SZBI to dokładnie ta sama logika, tylko dla **całej organizacji i wszystkich ryzyk informacyjnych** – nie tylko dla detekcji.

## 2. Budowa normy
| Część | Co zawiera | Wymagania? |
|---|---|---|
| Kl. 0–3 | Wprowadzenie, zakres, odwołania normatywne (ISO/IEC 27000), terminy | Nie |
| **Kl. 4–10** | Wymagania dla systemu zarządzania | **Tak – wszystkie obowiązkowe, nie można ich wyłączyć** |
| **Załącznik A** | 93 zabezpieczenia w 4 grupach: organizacyjne (5.x – 37), ludzkie (6.x – 8), fizyczne (7.x – 14), technologiczne (8.x – 34) | Wybierane **na podstawie oceny ryzyka**; wyłączenia możliwe z uzasadnieniem w SoA |

Kl. 4–10 mają **wspólną strukturę** (*Harmonized Structure*) z ISO 9001, ISO 22301, ISO 14001 → dlatego łatwo budować systemy zintegrowane (np. ISMS + ciągłość działania).

## 3. Klauzule 4–10 w jednym zdaniu (PDCA)
| Kl. | Temat | Pytanie, na które odpowiada | PDCA |
|---|---|---|---|
| 4 | Kontekst organizacji | Kim jesteśmy, kto czego od nas oczekuje, co obejmuje system (zakres)? | Plan |
| 5 | Przywództwo | Czy zarząd naprawdę za tym stoi (polityka, role, odpowiedzialności)? | Plan |
| 6 | Planowanie | Jakie mamy ryzyka, co z nimi robimy, jakie cele sobie stawiamy? | Plan |
| 7 | Wsparcie | Czy mamy ludzi, kompetencje, świadomość, komunikację, dokumentację? | Do |
| 8 | Działania operacyjne | Czy realizujemy to, co zaplanowaliśmy (w tym regularne oceny ryzyka)? | Do |
| 9 | Ocena efektów | Skąd wiemy, że działa (pomiary, audyt wewnętrzny, przegląd zarządzania)? | Check |
| 10 | Doskonalenie | Co poprawiamy (niezgodności, działania korygujące, ciągłe doskonalenie)? | Act |

## 4. Logika „przepływu” – najważniejszy rysunek
```
Kontekst i strony zainteresowane (4.1, 4.2) → Zakres (4.3)
        → Polityka i role (5)
        → OCENA RYZYKA (6.1.2) → POSTĘPOWANIE Z RYZYKIEM (6.1.3) → SoA + plan postępowania z ryzykiem
        → Cele (6.2) → Wdrożenie zabezpieczeń i procesów (7, 8)
        → Pomiar, audyt wewnętrzny, przegląd zarządzania (9)
        → Działania korygujące, doskonalenie (10) → i od nowa
```
**Ryzyko jest silnikiem systemu:** zabezpieczenia wybiera się dlatego, że odpowiadają na ryzyka – nie dlatego, że są na liście.
To dlatego Twój plan zaczyna się od zarządzania ryzykiem.

## 5. Informacja udokumentowana (*documented information*)
- **„Utrzymywać”** (*maintain*) = dokument żywy, aktualizowany (np. polityka, zakres, metodyka ryzyka).
- **„Zachowywać”** (*retain*) = zapis/dowód, że coś zrobiono (np. wyniki oceny ryzyka, raport z audytu, protokół z przeglądu zarządzania).
- Norma nie wymaga konkretnej liczby dokumentów ani konkretnej formy – wymaga, by istniały tam, gdzie mówi „informacja udokumentowana”,
  oraz tam, gdzie organizacja uzna je za potrzebne (kl. 7.5.1 b).

## 6. Zadanie praktyczne (z normą w ręku)
1. Przejdź kl. 4–10 i wypisz **każde miejsce, gdzie norma wymaga informacji udokumentowanej**: numer klauzuli + czego dotyczy + „utrzymywać” czy „zachowywać”.
   (Wskazówka: jest ich kilkanaście–kilkadziesiąt; sprawdzimy razem.)
2. Dla każdej klauzuli 4–10 zapisz **jedno zdanie własnymi słowami** + **jeden przykład z Twojej pracy** (SOC/blue team), który do niej pasuje.
3. Otwórz Załącznik A i znajdź 5 zabezpieczeń, które **już stosujesz w pracy** (np. logowanie, monitorowanie, zarządzanie podatnościami).

## Pojęcia z lekcji (PL / EN)
SZBI / ISMS · wymaganie / requirement · zabezpieczenie / control · deklaracja stosowania / Statement of Applicability (SoA) ·
informacja udokumentowana / documented information · strona zainteresowana / interested party · zakres / scope ·
ryzyko szczątkowe / residual risk · niezgodność / nonconformity · działanie korygujące / corrective action

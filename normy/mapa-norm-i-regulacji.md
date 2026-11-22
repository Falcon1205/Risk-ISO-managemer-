# Mapa dokumentów normatywnych i regulacji

> Stan wiedzy: listopad 2026. Przed powołaniem się na dokument u klienta **zawsze zweryfikuj aktualne wydanie**
> (ISO: iso.org / PKN; prawo UE: eur-lex.europa.eu; prawo PL: isap.sejm.gov.pl, Dziennik Ustaw).
> Priorytet: 🔴 musisz znać na wylot · 🟠 musisz dobrze rozumieć · 🟢 warto znać / specjalizacja.

## 1. Zarządzanie ryzykiem – fundament (ryzyko „ogólne” / ERM)

| Prio | Dokument | O czym | Po co Ci to |
|---|---|---|---|
| 🔴 | **ISO 31000:2018** Risk management – Guidelines | Zasady, ramy (framework) i proces zarządzania ryzykiem | Twój „kręgosłup” – język wspólny dla cyber i biznesu. Zasady (klauzula 4) to w praktyce definicja kultury ryzyka |
| 🔴 | **ISO 31073:2022** Risk management – Vocabulary | Terminologia (zastąpiła ISO Guide 73) | Precyzja języka = wiarygodność eksperta |
| 🟠 | **IEC 31010:2019** Risk assessment techniques | ~40 technik oceny ryzyka (bow-tie, FMEA, Monte Carlo, Delphi, HAZOP…) | Dobór technik do klienta zamiast wszędzie „macierzy 5×5” |
| 🟠 | **COSO ERM 2017** – Integrating with Strategy and Performance | 5 komponentów, 20 zasad; komponent „Governance & Culture” | Standard rozmowy z zarządem, CFO i audytem wewnętrznym |
| 🟠 | **IIA Three Lines Model (2020)** | Model trzech linii | Gdzie siedzi risk manager, a gdzie audyt i biznes |
| 🟢 | ISO 31022:2020 (ryzyko prawne), ISO 31050:2023 (ryzyka wschodzące), ISO 22301:2019 (ciągłość działania – BCM) | Specjalizacje | ISO 22301 szczególnie – NIS2 wymaga ciągłości działania |
| 🟢 | IRM *Risk Culture – Guidance* (2012), FSB *Guidance on Risk Culture* (2014) | Modele i wskaźniki kultury ryzyka | **Twoja nisza** – na tym zbudujesz unikalność |

## 2. Zarządzanie ryzykiem w cyberbezpieczeństwie

| Prio | Dokument | O czym | Po co Ci to |
|---|---|---|---|
| 🔴 | **ISO/IEC 27005:2022** Guidance on managing information security risks | Proces ryzyka dla ISMS; podejście oparte na zdarzeniach (event-based) i na aktywach (asset-based) | Bezpośrednio realizuje wymagania 27001 kl. 6.1.2, 6.1.3, 8.2, 8.3 |
| 🔴 | **NIST CSF 2.0** (luty 2024) | 6 funkcji: Govern, Identify, Protect, Detect, Respond, Recover | Nowa funkcja **GOVERN** = kultura i nadzór nad ryzykiem cyber; rozpoznawalny globalnie |
| 🔴 | **NIST SP 800-30 Rev.1** (2012) Guide for Conducting Risk Assessments | Model ryzyka: źródło zagrożenia → zdarzenie → podatność / warunki sprzyjające → prawdopodobieństwo → skutek; proces w 4 krokach (przygotowanie, przeprowadzenie, komunikacja, utrzymanie); gotowe skale i tabele w załącznikach D–I | Darmowy, bardzo praktyczny – najlepsze źródło szablonów do metodyki oceny ryzyka ISMS; często używany razem z ISO/IEC 27005 |
| 🟠 | **NIST SP 800-39** + **SP 800-37 Rev.2** (RMF) | Ryzyko na 3 poziomach: organizacja – proces – system | Łączenie poziomu zarządu z poziomem technicznym |
| 🟠 | **NIST IR 8286** (seria A–D) Integrating Cybersecurity and ERM | Jak „wpiąć” ryzyko cyber do ERM | **Most między Twoimi dwoma światami** (cyber ↔ biznes) |
| 🟠 | **Open FAIR** (The Open Group: O-RT, O-RA) | Ilościowa analiza ryzyka w pieniądzu | Wyróżnik na rynku PL – mało kto liczy ryzyko w PLN |
| 🟢 | ENISA *Cybersecurity Culture Guidelines: Behavioural Aspects* (2019) | Kultura bezpieczeństwa, behawioralne aspekty | Druga noga Twojej niszy „kultury” |

## 3. Rodzina ISO/IEC 27000 (ISMS)

| Prio | Dokument | Uwagi |
|---|---|---|
| 🔴 | **ISO/IEC 27001:2022** (+ **Amd 1:2024** – zmiany klimatu w kl. 4.1 i 4.2) | Wymagania ISMS, kl. 4–10 + Załącznik A (93 zabezpieczenia). Okres przejściowy z wersji 2013 zakończył się 31.10.2025 |
| 🔴 | **ISO/IEC 27002:2022** | Wytyczne do 93 zabezpieczeń w 4 tematach (organizacyjne 37, ludzkie 8, fizyczne 14, technologiczne 34), atrybuty |
| 🔴 | **ISO/IEC 27000:2018** | Przegląd i słownik rodziny |
| 🟠 | ISO/IEC 27003:2017 | Wytyczne wdrożeniowe do kl. 4–10 |
| 🟠 | ISO/IEC 27004:2016 | Pomiar skuteczności ISMS (KPI/KRI) – ważne przy „kulturze” |
| 🟠 | ISO/IEC 27014:2020 | Governance bezpieczeństwa informacji – rozmowa z zarządem |
| 🟠 | **ISO 19011:2018** + ISO/IEC 27007 | Audytowanie systemów zarządzania (audyt wewnętrzny to obowiązek kl. 9.2) |
| 🟢 | ISO/IEC 27701 (wydanie 2025 – samodzielna norma PIMS) | Prywatność / RODO |
| 🟢 | ISO/IEC 27017, 27018 | Chmura |
| 🟢 | ISO/IEC 27035 (części 1–2: 2023) | Zarządzanie incydentami – kluczowe pod raportowanie NIS2 |
| 🟢 | ISO/IEC 27036 | Bezpieczeństwo w relacjach z dostawcami – łańcuch dostaw w NIS2 |
| 🟢 | ISO/IEC 42001:2023 | System zarządzania AI – rosnący rynek |

## 4. Regulacje (UE i Polska)

| Prio | Akt | Kluczowe elementy |
|---|---|---|
| 🔴 | **Dyrektywa NIS 2** – (UE) 2022/2555 | Podmioty kluczowe i ważne; **art. 20** – odpowiedzialność i obowiązkowe szkolenia organu zarządzającego; **art. 21** – środki zarządzania ryzykiem (lit. a–j, podejście „all-hazards”); **art. 23** – raportowanie (24 h wczesne ostrzeżenie / 72 h zgłoszenie / 1 miesiąc raport końcowy); kary do 10 mln EUR / 2% (kluczowe), 7 mln EUR / 1,4% (ważne) |
| 🔴 | **Rozporządzenie wykonawcze (UE) 2024/2690** | Szczegółowe wymogi techniczne i metodyczne dla m.in. dostawców DNS, chmury, centrów danych, MSP/MSSP – świetna „ściąga” do art. 21, przydatna także poza tymi sektorami |
| 🔴 | **Ustawa o krajowym systemie cyberbezpieczeństwa (UKSC)** z 5.07.2018 + **nowelizacja wdrażająca NIS 2** | ⚠️ Zweryfikuj aktualny stan nowelizacji (data wejścia w życie, okresy przejściowe, samoidentyfikacja/rejestracja podmiotów, procedura dostawców wysokiego ryzyka). To będzie Twój główny „generator popytu” w PL |
| 🟠 | **DORA** – (UE) 2022/2554 (stosowana od 17.01.2025) + RTS 2024/1774 (ramy zarządzania ryzykiem ICT) | Sektor finansowy; jeśli celujesz w finanse/fintech – obowiązkowe |
| 🟠 | **RODO** – art. 24, 25, 32 (bezpieczeństwo), 35 (DPIA) | Podejście oparte na ryzyku dla danych osobowych – wspólny mianownik z 27001 |
| 🟠 | **KRI** – rozporządzenie RM w sprawie Krajowych Ram Interoperacyjności (§ 20) | Sektor publiczny: wymóg SZBI opartego o normy PN-ISO/IEC 27001/27002 – duży rynek w PL (JST, szpitale) |
| 🟢 | **CRA** – Cyber Resilience Act (UE) 2024/2847 | Producenci produktów z elementami cyfrowymi; raportowanie od 09.2026, pełne stosowanie od 12.2027 |
| 🟢 | **AI Act** – (UE) 2024/1689 | System zarządzania ryzykiem dla AI wysokiego ryzyka (art. 9) |
| 🟢 | KNF: Rekomendacja D, Komunikat chmurowy | Banki i rynek finansowy w PL |

## 5. Jak te dokumenty się łączą (model mentalny)

```
                 ISO 31000 / COSO ERM  ← zasady, ramy, kultura (poziom zarządu)
                          │
          NIST IR 8286 – integracja cyber z ERM
                          │
   ISO/IEC 27005 / NIST 800-30 / FAIR  ← metody oceny ryzyka cyber
                          │
        ISO/IEC 27001 (system) + 27002 (zabezpieczenia)
                          │
   NIS 2 art. 21 / UKSC / DORA / RODO art. 32 / KRI  ← „co regulator chce zobaczyć”
```

**Twoja przewaga:** większość wdrożeniowców startuje od Załącznika A i checklist. Ty startujesz od ISO 31000
i kultury, a 27001 traktujesz jako narzędzie. To jest komunikat Twojej marki.

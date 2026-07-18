# MODEL K0NSULT GLOBAL — Filar „Argentyna / Ameryka Płd."

> **Status dokumentu:** OTWARTY MODEL / PROPOZYCJA (open-source). To NIE jest
> roszczenie, że AI rządzi jakimkolwiek państwem, ani że rząd Argentyny przyjął
> model K0NSULT. To propozycja **neutralnej, otwartej warstwy zaufania i nadzoru**,
> komplementarnej do polityki deregulacyjnej.
>
> **Doktryna trzymana w każdym zdaniu:** Human Override Always (człowiek nad AI),
> claim ≤ proof, art. 50 (oznaczanie AI), DID tożsamości agenta, reputacja
> soulbound (nie pieniądz), audyt SHA-256, **zero scoringu osób**.

---

## 1. Kontekst (fakty, cytowane)

**Data:** koniec maja 2026. **Źródło:** cyberdefence24.pl — „Argentyna pierwszym
rajem dla AI".

Fakty zweryfikowane z materiału źródłowego:

- Prezydent Argentyny **Javier Milei** złożył do parlamentu (koniec maja 2026)
  projekt ustawy mający uczynić Argentynę **„rajem AI"**.
- Projekt opiera się na **trzech filarach**:
  1. **Deregulacja** — AI ma pozostać **„nieuregulowane"**, z założeniem swobodnego,
     nieskrępowanego rozwoju.
  2. **Nowa kategoria prawna** — **spółki zarządzane przez roboty / agentów AI**
     (nowy typ podmiotu gospodarczego).
  3. **Konkurencyjne otoczenie finansowe** — niskie podatki, elastyczne prawo
     spółek, ujawnianie beneficjentów rzeczywistych.
- Milei posłużył się **analogią do Holenderskiej Kompanii Wschodnioindyjskiej
  (VOC, 1602)** — jako historycznego prototypu przełomowej formy organizacji
  gospodarczej.
- Retoryka programowa: **„AI wyzwoli ludzkość"**.
- Wprost **kontrastowany z podejściem UE (AI Act)** — regulacja vs. deregulacja.

> **Granica uczciwości:** powyższe to relacja z projektu ustawy i wypowiedzi
> politycznych. Złożenie projektu ≠ jego uchwalenie ≠ wdrożenie. Na dzień
> powstania tego dokumentu traktujemy to jako **zapowiedź legislacyjną**, nie
> obowiązujące prawo.

---

## 2. Teza

Deregulacja **tworzy przestrzeń** — obniża próg wejścia, dopuszcza nowe formy
podmiotów (spółki-agenci). Ale deregulacja sama w sobie **nie odpowiada na
pytanie o rozliczalność**: kto odpowiada za decyzję agenta AI, jak udowodnić, co
agent zrobił i dlaczego, jak odróżnić działanie autoryzowane od nadużycia.

**K0NSULT nie jest alternatywą dla deregulacji — jest jej dopełnieniem.**
Dostarcza **open-source'ową warstwę nadzoru**, dzięki której agentowe zarządzanie
staje się **przejrzyste i rozliczalne**, a nie czarną skrzynką.

Logika jest odwrotna do intuicji regulatora:
**im mniej regulacji odgórnej, tym większa wartość dobrowolnej, otwartej warstwy
dowodowej.** Gdy państwo dopuszcza spółki zarządzane przez agentów AI, tym
bardziej potrzebna jest warstwa, która pozwala **udowodnić tożsamość agenta,
prześledzić jego decyzje i utrzymać człowieka jako instancję nadrzędną** —
bez czekania na przymus ustawowy.

To jest oferta **infrastruktury zaufania**, nie nadzoru policyjnego.

---

## 3. Trzy warstwy K0NSULT zastosowane do Argentyny

Model K0NSULT to układ **3 warstw** (Tożsamość → Reputacja/Dowód → Nadzór).
Poniżej mapowanie na argentyński przypadek „spółek-agentów".

### ① Tożsamość agenta — DID

- Każda **spółka zarządzana przez agenta AI** otrzymuje zdekentralizowany
  identyfikator: `did:k0nsult:agent:*` (np. `did:k0nsult:agent:ar-<hash>`).
- DID wiąże agenta z:
  - modelem/wersją, na której działa (rozliczalność techniczna),
  - **beneficjentem-człowiekiem** (patrz filar nadzoru — jawność beneficjenta),
  - zakresem uprawnień (co agent może robić w imieniu spółki).
- Efekt: **odpowiedzialność prawna przestaje być nieustalona.** Agent bez
  tożsamości = luka odpowiedzialności; agent z DID = adres, pod który można
  przypisać działanie i skutek.

### ② Reputacja / Dowód — soulbound + claim ≤ proof + rejestr audytu

- **Reputacja soulbound** — nieprzenoszalna, przypisana do DID agenta.
  **Nie jest pieniądzem** i nie podlega obrotowi: nie da się jej kupić ani
  przetransferować, więc nie tworzy rynku „reputacji na sprzedaż".
- **claim ≤ proof** — agent (i spółka) może twierdzić tylko tyle, ile potrafi
  udowodnić. Każdy claim bez dowodu jest jawnie oznaczony jako GAP/ROADMAP,
  nie jako fakt.
- **Rejestr audytu decyzji agenta** — kluczowe decyzje agenta zapisywane
  z **hashem SHA-256** (niezaprzeczalność bez ujawniania treści wrażliwej).
  Pozwala **post factum** zweryfikować, co agent zrobił, kiedy i na jakiej
  podstawie — bez zaufania „na słowo".

### ③ Nadzór — Human Override + art. 50 + jawność beneficjenta

- **Human Override Always** — człowiek pozostaje instancją nadrzędną nad
  agentem. Każda spółka-agent ma zdefiniowany **punkt ludzkiego zatrzymania /
  nadpisania** decyzji. AI nie jest ostatnią instancją.
- **Art. 50 (oznaczanie AI)** — działania i komunikaty generowane przez agenta
  są **oznaczone jako AI**. Kontrahent wie, że rozmawia/kontraktuje z agentem,
  nie z człowiekiem. (Zbieżne z duchem AI Act art. 50, tu jako dobrowolny
  standard.)
- **Jawność beneficjenta-człowieka** — spina się wprost z trzecim filarem
  projektu Milei (ujawnianie beneficjentów rzeczywistych): za każdą
  spółką-agentem stoi **ustalony człowiek/podmiot odpowiedzialny**, widoczny
  w warstwie tożsamości.
- **Zero scoringu osób** — warstwa nadzoru dotyczy **agentów i ich decyzji**,
  nigdy oceny/scoringu ludzi. To twarda granica modelu.

---

## 4. Dlaczego to pasuje do otwartości i odwagi decyzji Argentyny (rzeczowo)

Bez pochlebstwa — argument merytoryczny:

- **Open-source = suwerenność, nie zależność od big-techu.** Kraj, który stawia
  na odważną deregulację, ryzykuje, że de facto odda infrastrukturę zaufania
  w ręce zamkniętych platform (proprietary trust). Otwarta warstwa nadzoru jest
  **kontrolowana lokalnie, audytowalna i nieodcinalna** przez jednego dostawcę.
- **Deregulacja + otwarta rozliczalność = wiarygodność inwestycyjna.** Kapitał
  wchodzi chętniej tam, gdzie da się **udowodnić**, co robią autonomiczne
  podmioty. Warstwa dowodowa obniża ryzyko kontrahenta bez przywracania ciężkiej
  regulacji.
- **Analogia VOC działa w obie strony.** Kompania Wschodnioindyjska była
  przełomem organizacyjnym — ale historia pokazała też koszty braku
  rozliczalności skoncentrowanej władzy. Otwarta warstwa nadzoru to
  **wyciągnięcie wniosku z tamtego prototypu**, nie jego naiwne powtórzenie.
- **Odwaga regulacyjna zyskuje kontrapunkt techniczny.** „Nieuregulowane" na
  poziomie państwa nie musi znaczyć „nieprześledzalne" na poziomie infrastruktury.
  To dwie różne osie — i K0NSULT operuje na tej drugiej.

---

## 5. GAP-y i granice (uczciwie)

To model, nie mandat. Deklarujemy wprost:

- **To propozycja, nie obowiązek.** K0NSULT nie ma i nie rości sobie mandatu
  regulacyjnego w Argentynie. Wdrożenie zależy wyłącznie od dobrowolnej adopcji.
- **Odpowiedzialność prawna agentów jest obszarem nierozstrzygniętym.** DID i
  audyt **pomagają przypisać** działanie, ale ostateczne ramy odpowiedzialności
  ustala prawodawca/sąd, nie warstwa techniczna. To jest GAP, nie rozwiązane.
- **Deregulacja bez warstwy zaufania = realne ryzyko nadużyć** (pranie
  odpowiedzialności przez podmiot-agent, brak śladu decyzyjnego, asymetria
  informacji wobec kontrahenta). Nasza teza adresuje to ryzyko, ale nie
  eliminuje go bez adopcji.
- **AI w zarządzaniu podmiotem gospodarczym to obszar wrażliwy.** Model celowo
  utrzymuje Human Override i zero scoringu osób jako nieprzekraczalne bezpieczniki.
- **Brak weryfikacji wdrożeniowej.** Na dziś nie istnieje pilotaż K0NSULT
  w argentyńskim porządku prawnym — wszystkie twierdzenia o skuteczności są
  ROADMAP, nie DOWÓD.
- **Ryzyko nadinterpretacji politycznej.** Ten dokument nie popiera ani nie
  krytykuje polityki rządu Argentyny — opisuje, gdzie **otwarta warstwa nadzoru**
  mogłaby się wpiąć, gdyby ktokolwiek zdecydował się jej użyć.

---

## 6. Źródła i odnośniki

- **Artykuł źródłowy:** cyberdefence24.pl — „Argentyna pierwszym rajem dla AI"
  (relacja z projektu ustawy Milei, koniec maja 2026).
- **Warstwa doktrynalna K0NSULT:** k0nsult.cloud/ai-truth.
- **Kontekst porównawczy:** AI Act UE (art. 50 — obowiązek oznaczania treści AI),
  jako punkt odniesienia dla dobrowolnego standardu oznaczania.

> **Klasyfikacja dowodowa całości:** Sekcja 1 = fakty cytowane ze źródła.
> Sekcje 2–4 = teza/model (NARRACJA + propozycja, nie roszczenie faktu).
> Sekcja 5 = jawne GAP-y. Żadne zdanie tego dokumentu nie twierdzi, że model
> jest wdrożony ani przyjęty.

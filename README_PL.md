# translateManga Tłumacz Mangi - Przewodnik Użytkownika

*Wybór języka: [English](README.md) | [繁體中文](README_TC.md) | [العربية](README_AR.md) | [Magyar](README_HU.md) | [ไทย](README_TH.md) | [한국어](README_KO.md) | [Türkçe](README_TR.md) | [Polski](README_PL.md) | [Français](README_FR.md) | [Русский](README_RU.md) | [Español](README_ES.md)*

![Baner tłumaczenia mangi](./images/宣传图001.png)

## 📚 Spis treści

- [🌟 Wprowadzenie do projektu](#wprowadzenie-do-projektu)
- [🔍 Zasady techniczne](#zasady-techniczne)
- [✨ Funkcje](#funkcje)
- [🚀 Przewodnik użytkowania](#przewodnik-użytkowania)
- [🌎 Adaptacja regionalna](#adaptacja-regionalna)
- [📊 Studia przypadków](#studia-przypadków)
- [❓ Często zadawane pytania](#często-zadawane-pytania)

## 🌟 Wprowadzenie do projektu

**translateManga** to zaawansowane narzędzie do tłumaczenia treści mangi, oparte na sztucznej inteligencji, które potrafi inteligentnie rozpoznawać tekst w mandze, zapewniając wysokiej jakości wielojęzyczne tłumaczenia przy jednoczesnym zachowaniu oryginalnego stylu artystycznego i układu mangi. Niezależnie od tego, czy jest to manga japońska, manhwa koreańska, czy komiksy zachodnie, możesz łatwo cieszyć się doświadczeniem czytania w różnych językach.

Oficjalna strona internetowa: [https://translatemanga.online](https://translatemanga.online)

### Główne zalety

- **Inteligentne rozpoznawanie**: Zaawansowana technologia OCR dokładnie identyfikuje tekst mangi w różnych czcionkach i układach
- **Precyzyjne tłumaczenie**: Tłumaczenie uwzględniające kontekst, oparte na najnowszych dużych modelach językowych (GPT-4, Claude itp.)
- **Zachowanie układu**: Przetłumaczony tekst doskonale integruje się z oryginalnymi dymkami i układem
- **Obsługa wielu języków**: Obsługuje tłumaczenia między ponad 100 językami
- **Przetwarzanie wsadowe**: Obsługuje wsadowe tłumaczenie całych tomów mangi

![Główne zalety](./images/宣传图002.png)

## 🔍 Zasady techniczne

### Silnik tłumaczeniowy oparty na AI

To narzędzie wykorzystuje najnowocześniejsze systemy tłumaczeniowe oparte na sieciach neuronowych, które nie tylko rozumieją znaczenie słów, ale także uchwycają niuanse kontekstowe, zapewniając naturalne i płynne wyniki tłumaczenia. System najpierw "czyta" całą mangę, uchwycając ogólny styl i cechy postaci, a następnie tworzy spójne i konsekwentne tłumaczenia.

![Architektura silnika tłumaczeniowego](./images/宣传图003.png)

### Technologia rozpoznawania tekstu OCR

Aby sprostać unikalnym wyzwaniom układu w mandze, opracowaliśmy specjalistyczny Comic Text Detector, który potrafi precyzyjnie identyfikować:

- Tekst pionowy i poziomy
- Czcionki w stylu odręcznym
- Specjalne czcionki efektów i onomatopeje
- Małe teksty tła i adnotacje
- Ozdobne dymki dialogowe

Dokładność rozpoznawania osiąga wiodący w branży poziom 99%, dokładnie wyodrębniając tekst nawet na złożonych tłach.

### Mechanizm zachowania układu

Po tłumaczeniu system inteligentnie dostosowuje rozmiar czcionki, odstępy między wierszami i układ, aby zapewnić, że przetłumaczony tekst doskonale integruje się z oryginalnymi dymkami i układem. Kluczowe technologie obejmują:

1. **Inteligentny algorytm składu tekstu**: Automatycznie dostosowuje rozmiar czcionki i odstępy między wierszami w oparciu o długość tekstu w języku docelowym
2. **Technologia odtwarzania tła**: Inteligentnie odtwarza tło po usunięciu oryginalnego tekstu
3. **Dopasowanie stylu**: Zachowuje spójny styl czcionki i wyrazistość z oryginalną mangą

![Efekt zachowania układu](./images/漫画翻译对比1.webp)

## ✨ Funkcje

### Tłumaczenie wsadowe

Obsługuje wsadowe przetwarzanie całych tomów mangi lub wielu stron, umożliwiając przesyłanie do 300MB plików PDF lub kolekcji obrazów. System automatycznie przetwarza każdą stronę i generuje kompletną przetłumaczoną wersję.

![Demo tłumaczenia wsadowego](./images/宣传图004.png)

### Tłumaczenie w czasie rzeczywistym

Dzięki rozszerzeniom przeglądarki możliwe jest tłumaczenie mangi internetowej w czasie rzeczywistym. Podczas przeglądania obsługiwanych stron z mangą, rozszerzenie automatycznie wykrywa i tłumaczy treści mangi na stronie bez konieczności pobierania oryginalnych obrazów.

Obsługiwane strony obejmują:
- MangaDex
- MangaFire
- ManhuaRen
- WebToonScan
- I ponad 100 innych stron z mangą

![Demo tłumaczenia w czasie rzeczywistym](./images/Auto-translator.mp4)

### Obsługa wielu języków

Kompleksowe wsparcie dla tłumaczeń między następującymi językami:

- Języki europejskie, takie jak angielski, francuski, niemiecki, hiszpański itp.
- Języki azjatyckie, takie jak chiński (uproszczony/tradycyjny), japoński, koreański itp.
- Systemy pisma RTL, takie jak arabski i hebrajski
- Języki słowiańskie, takie jak rosyjski i polski

System automatycznie dostosowuje układ tekstu i kierunek w oparciu o charakterystykę różnych języków.

### Funkcja tłumaczenia zrzutów ekranu

Dla fizycznych książek mangi lub stron internetowych, które nie obsługują automatycznego tłumaczenia, oferujemy potężną funkcję tłumaczenia zrzutów ekranu:

1. Kliknij przycisk zrzutu ekranu w rozszerzeniu
2. Wybierz obszar mangi, który chcesz przetłumaczyć
3. System automatycznie rozpoznaje i tłumaczy tekst
4. Wyniki tłumaczenia są wyświetlane bezpośrednio na oryginalnym obrazie

![Funkcja tłumaczenia zrzutów ekranu](./images/截图翻译.png)

### Dostosowywanie terminologii

Dla konkretnych dzieł mangi możesz tworzyć dedykowane glosariusze terminologiczne, aby zapewnić spójność w tłumaczeniu imion postaci, nazw specjalnych umiejętności i innych nazw własnych. Jest to szczególnie ważne dla długich serii lub franczyz mangi.

## 🚀 Przewodnik użytkowania

### Szybki start - Trzy kroki do tłumaczenia mangi

#### Krok 1: Prześlij mangę
1. Odwiedź platformę tłumaczeniową mangi [https://translatemanga.online](https://translatemanga.online)
2. Kliknij przycisk "Prześlij"
3. Wybierz pliki mangi (obsługiwane formaty to m.in. JPG, PNG, PDF itp.)

#### Krok 2: Wybierz język i ustawienia
1. Wybierz język źródłowy mangi
2. Wybierz docelowy język tłumaczenia
3. Dostosuj ustawienia tłumaczenia (opcjonalnie):
   - Styl czcionki
   - Tryb rozpoznawania tekstu
   - Ustawienia glosariusza terminologicznego

#### Krok 3: Uzyskaj wyniki tłumaczenia
1. Kliknij przycisk "Rozpocznij tłumaczenie"
2. Poczekaj na zakończenie procesu tłumaczenia (około 1-2 minuty)
3. Podgląd i pobierz przetłumaczoną mangę

![Wyniki tłumaczenia](./images/manga-translator%20演示.mp4)

### Zaawansowane wskazówki użytkowania

#### Korzystanie z rozszerzenia przeglądarki

1. Odwiedź oficjalną stronę internetową, aby pobrać i zainstalować rozszerzenie przeglądarki: [https://translatemanga.online](https://translatemanga.online)
2. Obsługiwane przeglądarki to Chrome, Firefox i Edge:
   ![Obsługiwane przeglądarki](./images/chrome.svg) ![Firefox](./images/firefox.svg) ![Edge](./images/edge.svg)
3. Wybierz domyślny język tłumaczenia w ustawieniach rozszerzenia
4. Podczas przeglądania obsługiwanych stron z mangą kliknij ikonę rozszerzenia, aby aktywować tłumaczenie
5. Użyj funkcji tłumaczenia zrzutów ekranu, aby przetłumaczyć dowolny panel mangi

![Rozszerzenie przeglądarki](./images/截图翻译演示.mp4)

#### Przetwarzanie dużych tomów mangi

1. Zapisz całą mangę jako PDF lub spakuj ją jako plik ZIP/CBZ
2. Prześlij na stronę przetwarzania wsadowego
3. Ustaw globalne parametry tłumaczenia
4. Rozpocznij tłumaczenie wsadowe; czas przetwarzania zależy od liczby stron
5. Pobierz kompletną przetłumaczoną wersję lub czytaj online

#### Śledzenie postępu czytania

Aby zapewnić pełniejsze doświadczenie czytania mangi, rozszerzenie translateManga oferuje również śledzenie postępu czytania na różnych platformach:

1. Włącz funkcję synchronizacji postępu czytania
2. System rejestruje rozdziały mangi, które czytasz na różnych stronach
3. Kontynuuj od miejsca, w którym skończyłeś, logując się z dowolnego urządzenia
4. Obsługa niestandardowych kategorii i ulubionych

![Śledzenie postępu czytania](./images/manga-tracker%20演示.mp4)

#### Optymalizacja jakości tłumaczenia

1. **Twórz glosariusze terminologiczne**: Dodaj pary tłumaczeń dla nazw własnych w konkretnej mandze
2. **Dostosuj czułość rozpoznawania**: Dostosuj parametry wykrywania tekstu dla mangi z nietypowymi czcionkami
3. **Ręczna edycja**: System obsługuje ręczną korektę i udoskonalanie po tłumaczeniu

## 🌎 Adaptacja regionalna

### Specjalne funkcje dla rynku zachodniego

Dla nawyków czytelniczych zachodnich czytelników mangi, translateManga oferuje następujące specjalne funkcje:

1. **Tryb czytania od lewej do prawej**: Automatycznie dostosowuje kierunek czytania mangi japońskiej i koreańskiej, aby dostosować go do zachodnich nawyków czytelniczych
2. **Optymalizacja czcionek zachodnich**: Zapewnia różne czcionki w stylu zachodnich komiksów, aby zachować spójność artystyczną po tłumaczeniu
3. **Lokalizacja slangu i odniesień kulturowych**: Inteligentnie konwertuje wyrażenia specyficzne dla danej kultury, aby tłumaczenia były bardziej odpowiednie dla docelowych odbiorców

![Funkcje adaptacji zachodniej](./images/宣传图006.png)

### Obsługa wielu platform

Aby zaspokoić nawyki użytkowników w różnych regionach, translateManga oferuje różne opcje użytkowania:

1. **Aplikacja internetowa**: Korzystaj bezpośrednio przez przeglądarkę bez instalacji
2. **Rozszerzenia przeglądarki**: Obsługa popularnych przeglądarek, w tym Chrome, Firefox i Edge
3. **Aplikacje mobilne**: Dedykowane aplikacje dla platform iOS i Android, obsługujące tłumaczenie offline
4. **Oprogramowanie desktopowe**: Profesjonalne wersje dla systemów Windows i macOS, zapewniające potężniejsze możliwości przetwarzania wsadowego

### Wsparcie lokalizacyjne

Dla specjalnych potrzeb różnych regionów, translateManga zapewnia następujące wsparcie lokalizacyjne:

1. **Języki interfejsu**: Lokalizacja interfejsu w 14 głównych językach
2. **Obsługa klienta**: Wielojęzyczna obsługa klienta i zlokalizowana dokumentacja pomocy
3. **Zgodność**: Przestrzeganie przepisów o ochronie danych, takich jak GDPR i CCPA w różnych regionach

## 📊 Studia przypadków

### Przypadek tłumaczenia mangi japońskiej

**Efekt tłumaczenia "SPY×FAMILY"**

Charakterystyka tłumaczenia:
- Zachowuje oryginalny humor
- Dokładnie przekazuje głos i ton postaci
- Precyzyjnie tłumaczy specjalistyczną terminologię
- Lokalizuje onomatopeje

### Przypadek tłumaczenia koreańskiej manhwy (webtoon)

**Efekt tłumaczenia "Tower of God"**

Charakterystyka tłumaczenia:
- Doskonale zachowuje pionowy układ pasków
- Zachowuje specjalne efekty wizualne czcionek
- Utrzymuje spójność terminologii
- Optymalizuje układ długich dymków dialogowych

### Przypadek tłumaczenia komiksów zachodnich

**Efekt tłumaczenia "Avengers"**

Charakterystyka tłumaczenia:
- Zachowuje układ zachodnich ramek dialogowych
- Odtwarza artystyczny wyraz efektów dźwiękowych
- Odpowiednio lokalizuje slang angielski
- Dopasowuje style specjalnych czcionek

## ❓ Często zadawane pytania

### Związane z dokładnością tłumaczenia

**P: Jak zapewniana jest jakość tłumaczenia?**
O: Używamy najbardziej zaawansowanych w branży dużych modeli AI (GPT-4o, Claude itp.) do tłumaczenia, w połączeniu z treningiem w dziedzinie mangi, aby znacznie poprawić dokładność w scenariuszach mangi. Przed tłumaczeniem system najpierw "czyta" całą mangę, aby zrozumieć kontekst, zapewniając spójne i konsekwentne wyniki tłumaczenia.

**P: Czy może obsłużyć specjalne memy kulturowe i gry słowne?**
O: System potrafi identyfikować większość powszechnych odniesień kulturowych i gier słownych, próbując znaleźć równoważne wyrażenia w języku docelowym. W przypadku wysoce specyficznych odniesień kulturowych system zachowuje oryginalne znaczenie i w razie potrzeby dodaje krótkie wyjaśnienia.

### Pytania techniczne

**P: Jakie formaty plików są obsługiwane?**
O: Obsługiwane są popularne formaty obrazów (JPG, PNG, WEBP), formaty specyficzne dla mangi (CBR, CBZ), a także formaty e-booków PDF i EPUB, z limitem rozmiaru pojedynczego pliku wynoszącym 300MB.

**P: Jak radzi sobie z bardzo długimi stronami mangi?**
O: System obsługuje niezwykle długie strony mangi w paski do 10 000 pikseli, automatycznie przetwarzając je w segmentach przy zachowaniu ogólnej spójności układu.

**P: Jak mogę zapisać przetłumaczone pliki?**
O: Wyniki tłumaczenia można zapisać w oryginalnym formacie (np. PDF pozostaje jako PDF) lub wyeksportować jako kolekcje obrazów lub linki do czytania online, ułatwiając udostępnianie i czytanie na różnych urządzeniach.

## Powiązane linki i informacje kontaktowe

- [Oficjalna strona internetowa](https://translatemanga.online)
- **Email**: support@translatemanga.online
- **Discord**: [Dołącz do naszej społeczności Discord](https://discord.gg/translatemanga)

Jeśli masz jakiekolwiek pytania lub sugestie, śmiało skontaktuj się z nami w dowolnym momencie!

---

*Ten dokument został ostatnio zaktualizowany w czerwcu 2024 roku* 
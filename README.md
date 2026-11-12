# Kalkulator altanki

Prosta aplikacja w przeglądarce do projektowania altanek i małych domków ogrodowych.

**Strona:** https://mrpankrecik.github.io/projektowanie-altanek/

## Co liczy

- **Kostka pod altaną** – wymiar, m² z zapasem, liczba sztuk i palet, głębokość koryta,
  kruszywo, piasek i cement na podsypkę.
- **Słupki** – ile ich potrzeba i gdzie dokładnie mają stać (współrzędne od rogu kostki i od narożnika
  altany), z równym rozstawem nieprzekraczającym podanego maksimum. Opcjonalnie słupek pod kalenicę.
- **Drzwi** – otwór na wybranej ścianie ze słupkami i kotwami po obu stronach oraz długość nadproża.
- **Drewutnia** – miejsce na drewno dobudowane z zewnątrz lub wydzielone w środku, zabudowane poziomymi
  łatami 5×7 cm (z przerwą 7 cm) albo kratownicą: dodatkowe słupki, łaty do zamówienia i pojemność w mp.
- **Obrzeże** – metry bieżące wokół kostki na wybranych bokach, sztuki na każdy bok z docinkami
  (obrzeża 100, 75 lub 50 cm) i beton na ławę pod obrzeże.
- **Dach i więźba** – dach jedno-, dwu- lub czterospadowy z okapem i daszkiem wysuniętym nad wejściem
  (na wspornikach albo na dodatkowych słupkach): krokwie, krokwie narożne i kulawe, jętki, oczepy, belki poprzeczne między słupkami,
  płatew kalenicowa, długości słupków, powierzchnia połaci, deski czołowe, łaty i okucie boczne na krawędziach szczytów, m³ drewna i zamówienie na wymiar do tartaku.
- **Ściany z boazerii** – wybrane ściany obite między słupkami albo na słupkach, deski poziomo lub pionowo
  (z ryglami), na pełną wysokość albo do zadanej; zakup w paczkach.
- **Pokrycie dachu** – gont bitumiczny (paczki z zapasem, gąsiory, papa podkładowa) , blachodachówka albo blacha trapezowa/na rąbek w arkuszach
  o zadanej szerokości krycia (lista arkuszy na wymiar, gąsior, wkręty, membrana), do tego okapnik i okucie boczne.
- **Boazeria na dach** – liczba rzędów na każdej połaci, układ desek z łączeniami tylko na krokwiach
  (na mijankę), zakup na wymiar (0,7–5 m) w pełnych paczkach albo z długości dostępnych w składzie, lista zakupu
  i plan cięcia z wykorzystaniem ścinków.
- **Zastrzały (miecze)** – ile i przy których słupkach (kierunek w tabeli słupków), ramię i przekrój do ustawienia.
- **Fundamenty** – kotwy, beton na stopy fundamentowe.
- **Projekty** – zapis pod nazwą w przeglądarce, link do projektu (do wysłania komuś albo na inne
  urządzenie), plik `.json` do pobrania i wczytania.
- **Wizualizacja 3D** – obracany model z kostką, obrzeżem, słupkami, drzwiami, drewutnią, więźbą
  i pokryciem dachu (pokrycie można schować, żeby zobaczyć krokwie).
- **Zamówienie** – jedna tabela ze wszystkim do kupienia (kostka, fundamenty, drewno z tartaku według przekrojów i długości, boazeria w paczkach, pokrycie i obróbki), do skopiowania do Excela albo pobrania jako CSV.
- **Rzut z góry** z wymiarami, instrukcja wytyczenia w terenie, lista zakupów do schowka i **eksport do PDF**.

## Uruchomienie

To jeden plik `index.html` bez instalacji. Wystarczy otworzyć go w przeglądarce albo użyć strony
na GitHub Pages. Eksport do PDF pobiera biblioteki z cdnjs, więc wymaga internetu.

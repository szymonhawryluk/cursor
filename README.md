# Animowane strony HTML

Kolekcja animowanych stron HTML — bez zależności, każdą wystarczy otworzyć w przeglądarce.

- `index.html` — Rosnące drzewo 🌳
- `silnik-w12.html` — Silnik W12, interaktywny model 3D ⚙️
- `silnik-w12-2d.html` — Silnik W12, animowany przekrój 2D

## Silnik W12 3D (`silnik-w12.html`)

Interaktywny, obracany model 3D silnika W12 (three.js — biblioteka dołączona lokalnie w `lib/`, strona działa offline):

- Pełny mechanizm: wał korbowy z 4 wykorbieniami, po 3 korbowody na każdym czopie, 12 tłoków w trzech ławach pod kątem 60°.
- Obracanie modelu myszką (przeciąganie), zoom kółkiem, przesuwanie prawym przyciskiem + tryb auto-obrotu.
- Półprzezroczyste tuleje cylindrów, głowice i skrzynia korbowa — suwak przezroczystości bloku pozwala odsłonić mechanizm.
- Błyski zapłonu w komorach spalania (suw pracy w cyklu 720°), obrotomierz, przycisk **Start/Pauza** z bezwładnością silnika i suwak obrotów.

## Silnik W12 2D (`silnik-w12-2d.html`)

Animowany rysunek techniczny przekroju silnika W12 w stylu blueprint:

- Trzy ławy cylindrów pod kątem 60° z tłokami napędzanymi poprawną kinematyką układu korbowego (wał korbowy → korbowody → tłoki).
- Cykl czterosuwowy: błysk spalania i iskra świecy przy GMP, animowane zawory ssące i wydechowe.
- Obrotomierz z płynnie rozpędzającą się wskazówką oraz panel kolejności zapłonu 12 cylindrów.
- Sterowanie: przycisk **Start/Pauza** (silnik płynnie się rozpędza i wybiega) oraz suwak obrotów.

## Rosnące drzewo (`index.html`)

Animowana strona HTML przedstawiająca proceduralnie generowane, rosnące drzewo.

Co się dzieje na stronie:

- Drzewo (fraktalne gałęzie SVG) wyrasta od pnia po najdrobniejsze gałązki.
- Na końcach gałęzi wyskakują liście i kwiaty, które kołyszą się na wietrze.
- Po wyrośnięciu pojedyncze liście opadają na ziemię.
- W tle: słońce z promieniami, dryfujące chmury, rosnąca trawa i kwiatki.
- Przycisk **„Posadź nowe drzewo”** generuje za każdym razem inne drzewo.

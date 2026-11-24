# NITIJP-S213053
# REPOZYTORIUM

## Spis treści
>[Temat repozytorium](#temat-repozytorium)\
>[CSV](#csv)\
>[JSON](#json)\
>[XML](#xml)\
>[XSD](#xsd)\
>[Porównanie danych](#porównanie-danych)\
>[Podsumowanie](#podsumowanie)

## Temat repozytorium

W każdym pliku znajduje się porównanie 5 najlepszych graczy gry CS2:
- ZyWoo
- Donk
- Ropz
- M0NESY
- sh1ro
  
Są oceniani pod względem:
- Wygrane Majory
- MVP
- Elo na faceit
- Obecna drużyna

## CSV

- Program wydaje się bardzo intuicyjny i wygodny do tworzenia tabel z danymi.
- Do oddzielenia poszczególnych pól wykorzystuje się przecinek.

## JSON

- Program trochę bardziej skomplikowany od csv.
- Nadal dość intuicyjny.
- Największy problem stwarza powtarzanie tagów.
- Zamiast pracować wierszami jak w csv, tworzy się kolumnami.

## XML

- Budowa podobna do **HTML**.
- Struktura podobna do drzewa.
- Treść się rozgałęzia z jednego trzonu.

## XSD

- Bezpośrednio połączony z XML.
- Odpowiada z za nadzór użytych typów zmiennych.
- Wydaje się mało przejrzysty przez zagnieżdżone funkcje.
- Warstwowy.

## Porównanie danych

|Cecha | CSV | JSON | XML i XSD|
| :--- | :--- | :--- | :--- |
|**Struktura**| Wierszowa | Obiektowa/Kolumnowa | Drzewo|
|**Przejrzystość**|Bardzo intuicyjne|Przejrzyste|Zagnieżdżone|
|**Sposób czytania**|tabela|Edytor kodu|Walidator online|


## Podsumowanie

Tą samą treść można utworzyć w różnych programach, które zawierają plusy i minusy:
- **CSV** - najlepszy do prostych tabel,
- **JSON** - najlepszy, gdy dane są obiektowe, 
- **XML i XSD** - najlepszy, gdy potrzeba kontroli nad treścią.


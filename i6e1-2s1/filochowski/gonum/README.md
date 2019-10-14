# Praca domowa z przedmiotu Metody i narzędzia wspomagania decyzji LAB 1

autor: Piotr Filochowski, I6E2S1

## Instalacja go

https://golang.org/doc/install?download=go1.13.1.windows-amd64.msi

## Instalacja biblioteki gonum:

```
go get -u -t gonum.org/v1/gonum/...
```

## Oficjalna strona gonum:

https://www.gonum.org/

## Opis biblioteki

Gonum jest to biblioteka języka Go która zawiera paczki służące do obliczeń takich zagadnień jak algebra liniowa, statystyka, rozkłady prawdopodobieństwa. Gonum posiada narzędzia do różnicowania funkcji, integracji i optymalizacji, oraz tworzenia i analiza sieci.

Gonum został zaprojektowany tak, aby był prosty, wydajny i modułowy. Twórcy tej biblioteki skupiali się na tym, aby kod biblioteki był łatwy do zrozumienia i przejżysty. Jedną z głównych różnic między Gonum a innymi popularnymi bibliotekami naukowymi jest to, że Go nie pozwala na przeciążanie operatora ani metody. Dlatego ten sam algorytm często potrzebuje kilku dodatkowych linii kodu w Go.

Wyróżnikiem Gonum jest to, że wymaga tylko jednego języka programowania: Go. Struktura Gonum zachęca użytkowników do wdrażania algorytmów w jednolitym stylu, dzięki czemu kod jest łatwy do odczytania i spójny dla wszystkich użytkowników.

### Instalacja rozwiązania:

1. Zainstalować gonum.
2. Ustawić wartość zmiennej środowiskowej GOPATH
3. W folderze na który wskazuje GOPATH utworzyć foldery: bin, pkg, src
4. W folderze src utworzyć folder pfilochowski a w nim umieścić plik z kodem źródłowym min1.go


## Kompilacja i uruchomienie

W folderze %GOPATH%/src/pfilochowski uruchomić w cmd:

```
go run ./min1.go
```

Oczekiwany rezultat:

opt: -8
x: [2 3 0 0]


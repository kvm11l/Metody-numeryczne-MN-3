# Metody-numeryczne-MN-3
## Interpolacja wielomianowa metodą Newtona - analiza błędów

Interpolacja wielomianowej funkcji `y = 2/x` za pomocą wielomianu Newtona w środowisku Octave. Analizowane są wartości funkcji w punktach pośrednich na podstawie danych węzłów interpolacyjnych oraz przeprowadzona jest szczegółowa analiza błędów.

## Dane wejściowe
- Funkcja: `y = 2/x`
- Węzły interpolacyjne:\
i	0	1	2	3\
xᵢ	1.70	1.71	1.72	1.73\
yᵢ	0.1852	0.1838	0.1825	0.1812

## Punkty analizy
- 1.705 - punkt pomiędzy x₀ a x₁
- 1.715 - punkt pomiędzy x₁ a x₂

## Wyniki
### Dla punktu x = 1.705
- Wartość wielomianu Newtona: 0.184487500000000
- Błąd oszacowany: -6.250000000001000e-06
- Wartość z Octave: 0.184487499999999
- Wartość dokładna funkcji: 1.173020527859237
- Błąd rzeczywisty: 0.988533027859237
- Różnica między metodami: 4.996003610813204e-16

### Dla punktu x = 1.715
- Wartość wielomianu Newtona: 0.183137500000000
- Błąd oszacowany: 6.250000000001092e-06
- Wartość z Octave: 0.183137500000000
- Wartość dokładna funkcji: 1.166180758017493
- Błąd rzeczywisty: 0.983043258017493
- Różnica między metodami: 2.220446049250313e-16

## Pliki w repozytorium
- `MNC6KP0404 - Sprawozdanie.pdf` - pełne sprawozdanie
- `MNC6KP0404 - Ocatve.pdf` - dokumentacja z Octave
- `zad441.txt`, `zad442.txt` - zapisy sesji obliczeniowych

